#### Test 5635717154d1b6f_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/PMS     (  906): acquireWL(43e6a7d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{41c634c0: PendingIntentRecord{424ac790 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=99208, Int=0
D/PMS     (  906): acquireWL(423dd758): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
D/PMS     (  906): releaseWL(43e6a7d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42e3abb8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(423dd758): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  906): releaseWL(42e3abb8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1181): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
,I/SensorManager(  906): mEventCount = 1200
D/WIFI_ICON( 1115): WifiActivity: 1
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/cutils-trace( 4827): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4827): ====startRecUseTime====
D/htc.customization.log.level( 4827):  is 
W/CustomizationLogLevel( 4827): Level value is invalid, use default level 2
D/CustomizationManager( 4827):  Read ACC file spent 0.050 (s)
D/CIDMapFileReader( 4827): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4827): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4827): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4827): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4827): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4827): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4827): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4827): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4827): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4827): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4827): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4827): Parsing tag category name = system
I/CustomizationCIDLoader( 4827): Parsing tag category name = application
I/CustomizationCIDLoader( 4827): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4827): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4827): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4827): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4827): Parsing tag category name = Settings
D/CustomizationManager( 4827):  Read CID file spent 0.088 (s)
D/CustomizationManager( 4827):  All configurations done spent 0.088 (s)
W/HtcNativeFlag( 4827): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4827): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4827): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4827): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  906): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  906): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4827
D/PMS     (  906): acquireHCC(42c85c38): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 906 1000 null
D/PMS     (  906): acquireHCC(441482d8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 906 1000 null
W/asset   (  906): Copying FileAsset 0x6f7a0150 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  906): @test_code: getHtcIntentFlag: 0 obj: 1114826112
I/FeedHostManager( 1264): [onPause]
I/FeedProviderManager( 1264): onPause
I/FeedHostManager( 1264): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c1ed58
I/SocialFeedProvider( 1264): +onPause
I/SocialFeedProvider( 1264): -onPause
D/PMS     (  906): acquireWL(42e827c8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
I/ActivityManager(  906): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4838 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1264): [trimMemory] 20
W/asset   ( 4838): Copying FileAsset 0x5c7273d0 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4838): Binding Chromium to main looper Looper (main, tid 1) {41ab0e08}
I/LibraryLoader( 4838): Expected native library version number "",actual native library version number ""
I/chromium( 4838): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4838): Initializing chromium process, renderers=0
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  906): java.lang.Throwable: stack dump
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42c64218:true
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4838): 1101819480: getState(). Returning 12
D/PMS     (  906): acquireWL(42abe5f0): PARTIAL_WAKE_LOCK  AudioMix 0x1 369 1013 null
D/PMS     (  906): acquireWL(4311f590): PARTIAL_WAKE_LOCK  AudioMix 0x1 369 1013 null
D/PMS     (  906): releaseWL(4311f590): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4838): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4838): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4838): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4838): Local Branch: 
I/Adreno-EGL( 4838): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4838): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4838):                  aa63bbd948f41d15fc72f585e
W/chromium( 4838): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4838): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4838): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4838): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4838): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4838): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4838): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4838): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4838): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4838): CordovaWebView is running on device made by: HTC
,W/AwContents( 4838): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  906): Disable input method client, pid=1264
,W/ResourceType( 4838): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4838): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41af8508, mServedView=org.apache.cordova.engine.SystemWebView{41abe170 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/ActivityManager(  906): Displayed com.test.thalitest/.MainActivity: +250ms
,W/AwContents( 4838): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  906): Enable input method client, pid=4838
W/XT9_C   ( 1206): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1206): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1206): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1206): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  906): releaseWL(42e827c8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4838): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4838): JniHelper::setJavaVM(0x41588048), pthread_self() = 1663829800
,D/JX-Cordova( 4838): jxcore cordova android initializing
,I/dalvikvm-heap( 4838): Grow heap (frag case) to 11.995MB for 42652-byte allocation
,D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=342 rxSum=343} preTxRxSum={txSum=342 rxSum=343}
D/WifiDataStallTracker(  906): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  906): onDataStallAlarm: tag=20593 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20594 delay=15s
D/PMS     (  906): acquireWL(423e7908): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{4260b948: PendingIntentRecord{42376b18 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=101450, Int=0
D/PMS     (  906): releaseWL(423e7908): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/dalvikvm-heap( 4838): Grow heap (frag case) to 12.072MB for 95956-byte allocation
,I/dalvikvm-heap( 4838): Grow heap (frag case) to 12.151MB for 143930-byte allocation
,I/dalvikvm-heap( 4838): Grow heap (frag case) to 12.266MB for 215890-byte allocation
,I/dalvikvm-heap( 4838): Grow heap (frag case) to 12.441MB for 323830-byte allocation
,I/dalvikvm-heap( 4838): Grow heap (frag case) to 12.713MB for 485740-byte allocation
,I/dalvikvm-heap( 4838): Grow heap (frag case) to 13.681MB for 1092904-byte allocation
,I/dalvikvm-heap( 4838): Grow heap (frag case) to 14.632MB for 1639352-byte allocation
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/dalvikvm-heap( 4838): Grow heap (frag case) to 15.877MB for 2459024-byte allocation
,I/dalvikvm-heap( 4838): Grow heap (frag case) to 18.065MB for 3688532-byte allocation
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 65
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 209
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1181): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,W/CpuWake (  906): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  906): <<release mCpuPerf_Freq wakelock
D/PMS     (  906): releaseHCC(42c85c38): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  906): releaseHCC(441482d8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4838): Initializing JXcore engine
,W/jxcore-log( 4838): JXcore engine is ready
,W/jxcore-log( 4838): Starting JXcore engine
,W/jxcore-log( 4838): Platform android
W/jxcore-log( 4838): 
,W/jxcore-log( 4838): Process ARCH arm
W/jxcore-log( 4838): 
,I/PMS     (  906): Going to sleep due to screen timeout...
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421f57a8
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  906): pid=906, uid=1000
I/ActivityManager(  906): mThumbnailWidth=360, mThumbnailHeight=640
V/LightsService(  906): setLight #2: color=#0
D/qdlights(  906): set_light_buttons_func: on=0 brightness=0
V/LightsService(  906): setLight #0: color=#0
,W/BatSI   (  906): Couldn't get kernel wake lock stats
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421f57a8, eanble = 0, strlen(mName) = 59
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41bcf6d0
W/SensorService(  906): Listener[1] = com.htc.smartdim.sensor_eye@42344378
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/WirelessDisplayService(  906): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  906): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  906): mWirelessDisplayManager is null
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/SurfaceControl(  906): Excessive delay in blankDisplay() while turning screen off: 319ms
D/PMS     (  906): nativeSetInteractive:false
D/PMS     (  906): nativeSetInteractive:false done
D/PMS     (  906): nativeSetAutoSuspend:true
D/PMS     (  906): nativeSetAutoSuspend:true done
D/HABCtrl (  906): TPE algorithm. remove timeout.
D/PMS     (  906): OOBE c monitor 11
D/NfcService( 1252): ScreenObserver: OFF
D/NfcService( 1252): applyRouting - 0
,D/NfcService( 1252): applyRouting -2
I/InputMethodManagerService(  906): screenObserver, isScreenOn=false
D/PMS     (  906): acquireWL(430fdb10): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1252 1027 null
D/PMS     (  906): releaseWL(430fdb10): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/InputMethodManagerService(  906): Disable input method client, pid=4838
I/InputManager(  906): Cancel all due to getting PMS screen off broadcast
,V/KeyguardServiceDelegate(  906): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@440c0128)
,I/IntentController( 1115): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  906): **** SHOWN CALLED ****
D/PMN     (  906): wakingUp
D/PMS     (  906): acquireWL(431069f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
D/PMS     (  906): releaseWL(431069f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/WindowManager(  906): No lock screen! windowToken=null
D/WirelessDisplayService(  906): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMN     (  906): onScreenOn
D/AlarmManager(  906): ACTION_SCREEN_ON
I/AlarmManager(  906): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done recovering
I/AlarmManager(  906): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done EPS screen off alarm recovering
D/HtcPowerSaver(  906): updateBatteryInfo
,D/PowerUI ( 1115): closing low battery warning: level=100
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/MtpService( 2794): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2794): [MTP][onReceive]-
D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_ON
,D/NfcService( 1252): applyRouting - 0
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20595 delay=15s
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,D/PMS     (  906): acquireWL(44370928): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1252 1027 null
,D/NfcService( 1252): applyRouting -2
D/PMS     (  906): releaseWL(44370928): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024631
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024755
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024824
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024826
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024938
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024944
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026236
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026250
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029201
,V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
W/ContextImpl( 4628): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1181): SET_SCREEN_ON:On
I/wpa_supplicant( 1181): htc_wext_set_keepalive +
I/wpa_supplicant( 1181): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1181): getPrivFuncNum +	
I/wpa_supplicant( 1181): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1181): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1181): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1181): BG scan when screen On
I/wpa_supplicant( 1181): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1181): htc_wext_set_TX_TRACKING - ret = 0
I/wpa_supplicant( 1181): wpa_supplicant_scan enter
I/wpa_supplicant( 1181): Match BG scan, scan!
I/wpa_supplicant( 1181): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1181): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1181): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1181): nl80211: Event message available
D/wpa_supplicant( 1181): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/WifiNative-wlan0(  906):    returned true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WIFI_ICON( 1115): WifiActivity: 0
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/SRS_Proc(  369): ParamSet string: screen_state=on
,D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,D/SmartSyncUtils( 4628): isEpsOn(), nState = 0
D/PMS     (  906): acquireWL(43113940): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4628 1000 null
,I/ClockThread( 1115): stop update clock
D/NetworkPolicy(  906): updateScreenOn: false
,D/SmartSyncUtils( 4628): getMobilePolicyEnabled, result = true
D/PMS     (  906): releaseWL(43113940): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/AutoSetting( 1325): receiver - intent: android.intent.action.USER_PRESENT
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
D/TetherSettings( 4198): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4198): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4198): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4198): Cust_ConnectToPC   : spcsc>false
D/        ( 4198): Cust_ConnectToPC   : IPT>true
D/        ( 4198): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 4198): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/AutoSetting( 1325): service - onCreate()
E/SmartNS_Utility( 4198): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4198): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4198): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/AutoSetting( 1325): service - AddressCache: using context: com.htc.Weather
I/PSReceiver( 4198): onReceive:android.intent.action.USER_PRESENT
D/AutoSetting( 1325): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/LocationManagerService(  906): request 425bcdf0 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,W/ContextImpl( 4198): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/LocationManagerService(  906): provider request: passive ProviderRequest[ON interval=0]
I/SmartNS_PSService( 4198): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4198): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 4198):  defaultType:0
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  906): acquireWL(4420f638): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(4420f638): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(4262ad88): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1776): onScreenOn: false
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1776): onScreenOn: 1453132541526
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1776): onScreenOn: 1453132541527
D/PMS     (  906): releaseWL(4262ad88): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41bcf6d0
,W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41bcf6d0, eanble = 0, strlen(mName) = 91
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  906): Listener[0] = com.htc.smartdim.sensor_eye@42344378
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  906): goingToSleep
D/PMS     (  906): acquireWL(43745d60): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 906 1000 null
,D/AlarmManager(  906): ACTION_SCREEN_OFF
I/AlarmManager(  906): [AlarmQueuing] screen off now: 
I/AlarmManager(  906): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=20595 mDataStallAlarmIntent=PendingIntent{4262e188: PendingIntentRecord{42376b18 android broadcastIntent}}
,D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 0
I/AlarmManager(  906): [AlarmQueuing] wifi connection: true
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024631
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024755
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024824
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024826
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024938
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024944
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026236
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026250
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029201
D/PMS     (  906): acquireWL(434be308): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 906 1000 null
,W/ContextImpl( 4628): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4628): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4628): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4628): getMobilePolicyEnabled, result = true
D/WifiService(  906): New client listening to asynchronous messages
,I/jxcore-log( 4838): JXcore Cordova bridge is ready!
I/jxcore-log( 4838): 
,W/jxcore-log( 4838): JXcore engine is started
,W/ResourceType( 4838): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4838): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41abe170 VFEDH.C. .F....ID 0,0-720,1134 #64}
,I/chromium( 4838): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/PMS     (  906): releaseWL(43745d60): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/jxcore-log( 4838): Toggling radios to true
I/jxcore-log( 4838): 
,D/BluetoothAdapter( 4838): enable(): BT is already enabled..!
,D/WifiManager( 4838): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  906): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 2
W/Settings:Agent(  906): >> traceCallingStack()
W/Settings:Agent(  906): Process.myPid(): 906
W/Settings:Agent(  906): Process.myTid(): 1381
W/Settings:Agent(  906): Process.myUid(): 1000
D/WifiService(  906): New client listening to asynchronous messages
D/WifiService(  906): setWifiEnabled: true pid=4838, uid=10389
E/WifiService(  906): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  906): isSprintWifiRestricted(): false
I/WifiService(  906): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  906): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/Settings:Agent(  906): 
W/Settings:Agent(  906): 
W/System.err(  906): java.lang.Throwable: stack dump
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
W/Settings:Agent(  906): << traceCallingStack(): 7(ms)
D/WifiManager( 4838): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiManager( 4838): reconnect: Base Package Name=com.test.thalitest, uid=10389
I/jxcore-log( 4838): Radios toggled
I/jxcore-log( 4838): 
I/jxcore-log( 4838): My device name is: HTC-HTC Desire 820
I/jxcore-log( 4838): 
,D/PMS     (  906): releaseWL(42abe5f0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1181): SET_SCREEN_ON:Off
I/wpa_supplicant( 1181): htc_wext_set_keepalive +
I/wpa_supplicant( 1181): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1181): getPrivFuncNum +	
I/wpa_supplicant( 1181): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1181): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1181): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1181): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1181): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 65
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 274
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1181): WiFioffload: SignalStrength: =97
I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42344378
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 1
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42344378, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 0
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42344378, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/WifiNative-wlan0(  906):    returned true
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42344378
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  369): ParamSet string: screen_state=off
E/ActivityThread(  906): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@425d2890 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@425d2890 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  906): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  906): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  906): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  906): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  906): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  906): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  906): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  906): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
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
,D/NetworkPolicy(  906): updateScreenOn: false
D/ContactMessageStore( 1238): start background delete task...
D/ContactMessageStore( 1238): size: 0 , 0
D/ContactMessageStore( 1238): Background delete complete
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] getTotalRam: 1873 Mb
,D/PMS     (  906): acquireWL(43ec0b48): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(43ec0b48): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4427a180): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1776): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1776): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1776): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1776): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1776): onScreenOff
D/PMS     (  906): releaseWL(4427a180): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1325): service - mHandler: cancel location update
,D/AutoSetting( 1325): service -           changes count: 0
,D/wpa_supplicant( 1181): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DISCONNECT
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1181): TDLS: Tear down peers
,I/wpa_supplicant( 1181): wpa_driver_nl80211_disconnect(reason_code=3)
D/PMS     (  906): releaseWL(434be308): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1181): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1181): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1181): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  906): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  906): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1181): TDLS: Remove peers on disassociation
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/HTCRequest(  906): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1181): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1181): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1181): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1181): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1181): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1181): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1181): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1181): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1181): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb7356bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1181):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1181): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1181): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1181): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1181): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1181): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1181): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1181): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1181): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1181): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1181): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1181): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1181): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1181): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1181): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1181): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1181): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1181): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1181): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1181): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1181): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1181): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1181): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1181): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1181): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1181): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1181): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1181): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1181): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1181): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1181): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1181): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplican,t( 1181): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1181): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1181): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1181): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1181): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1181): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1181): nl80211: Event message available
D/wpa_supplicant( 1181): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1181): nl80211: Ignore disconnect event triggered during reassociation
D/wpa_supplicant( 1181): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1181): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1181): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1181): nl80211: Survey data missing
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1181): Sorted scan results
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1181): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-85
D/wpa_supplicant( 1181): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1181): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1181): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1181): Add randomness: count=8 entropy=2
I/wpa_supplicant( 1181): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1181): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1181): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1181): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1181): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1181): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1181): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1181): nl80211: Survey data missing
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1181): Sorted scan results
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1181): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-85
D/wpa_supplicant( 1181): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1181): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1181): Add randomness: count=10 entropy=4
D/wpa_supplicant( 1181): Add randomness: count=11 entropy=5
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
,D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1181): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1181): wpa_supplicant_pick_network+
I/wpa_supplicant( 1181): clear disabled list - type=1
I/wpa_supplicant( 1181): No suitable network found
W/wpa_supplicant( 1181): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1181): State: DISCONNECTED -> INACTIVE
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/HTCRequest(  906): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/WifiNative-wlan0(  906):    returned true
D/WifiPerfLock(  906): release()
D/WifiStateMachine(  906): PerfLock released for exiting ConnectedState
,D/HTCRequest(  906): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  906): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
,D/HTCRequest(  906): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1181): Power_Mode_Type mode = 0
I/wpa_supplicant( 1181): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 61,
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  906): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =INACTIVE
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1181): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/ConnectivityService(  906): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  906): acquireWL(438b2f00): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 906 1000 null
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): InactiveState{ when=-3ms what=147462 obj=android.net.wifi.StateChangeResult@42746380 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-3ms what=147462 obj=android.net.wifi.StateChangeResult@42746380 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-4ms what=147462 obj=android.net.wifi.StateChangeResult@42746380 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0(  906):    returned true
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/DhcpStateMachine(  906): [RunningState] Stop DHCP
D/WifiNative-wlan0(  906): doBoolean: RECONNECT
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1181): wpa_supplicant_pick_network+
I/wpa_supplicant( 1181): Selecting BSS from priority group 1
I/wpa_supplicant( 1181): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1181): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1181): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1181): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1181):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1181):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1181): Start print parameters
I/wpa_supplicant( 1181): wpa_s->wpa_state is 0
I/wpa_supplicant( 1181): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1181): isConcurrentMode() is 0
I/wpa_supplicant( 1181): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1181): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1181): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1181): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1181): wpa_s->reassociate is 1
I/wpa_supplicant( 1181): wpa_s->is_screen_on 0
I/wpa_supplicant( 1181): wpa_s->ifname wlan0
I/wpa_supplicant( 1181): End print parameters
I/wpa_supplicant( 1181): selected network = 1
D/wpa_supplicant( 1181): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: DISCONNECTED  ssid=0xb73584e8  current_ssid=0x0
D/WifiP2pService(  906): InactiveState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024631
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024755
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024824
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024826
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024938
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024944
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026236
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026250
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029201
D/wpa_supplicant( 1181): wlan0: Request association with c0:ff:d4:d3:aa:48
D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
I/wpa_supplicant( 1181): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1181): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1181): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1181): check if in concurrent case
I/wpa_supplicant( 1181): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=20596 mDataStallAlarmIntent=null
D/wpa_supplicant( 1181): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1181): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1181): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1181): RSN: PMKSA cache search - network_ctx=0xb73584e8 try_opportunistic=0
D/wpa_supplicant( 1181): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1181): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1181): State: DISCONNECTED -> ASSOCIATING
D/wpa_supplicant( 1181): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1181): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1181): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
D/wpa_supplicant( 1181): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1181): nl80211: Unsubscribe mgmt frames handle 0xb7357718 (mode change)
D/wpa_supplicant( 1181): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7357718
D/wpa_supplicant( 1181): nl80211: Register frame type=0xd0 nl_handle=0xb7357718
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1181): nl80211: Register frame type=0xd0 nl_handle=0xb7357718
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1181): nl80211: Register frame type=0xd0 nl_handle=0xb7357718
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1181): nl80211: Register frame type=0xd0 nl_handle=0xb7357718
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1181): nl80211: Register frame type=0xd0 nl_handle=0xb7357718
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1181): nl80211: Register frame type=0xd0 nl_handle=0xb7357718
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1181): nl80211: Register frame type=0xd0 nl_handle=0xb7357718
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1181): nl80211: Register frame type=0xd0 nl_handle=0xb7357718
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1181): nl80211: Register frame type=0xd0 nl_handle=0xb7357718
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1181): nl80211: Register frame type=0xd0 nl_handle=0xb7357718
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1181): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1181):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1181):   * freq=2412
D/wpa_supplicant( 1181):   * Auth Type 0
D/wpa_supplicant( 1181):   * WPA Versions 0x2
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1181): nl80211: Connect request send successfully
D/wpa_supplicant( 1181): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1181): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1181): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1181): EAPOL: Ext,ernal notification - EAP fail=0
D/wpa_supplicant( 1181): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1181): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1181): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1181): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1181): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/UsbnetStateTracker(  906): isAvailable+-
D/UsbnetStateTracker(  906): reconnect
D/UsbnetStateTracker(  906): isAvailable+-
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 18
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =INACTIVE newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
D/WifiStateMachine(  906): Enter handleNetworkDisconnect
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1181): Power_Mode_Type mode = 0
I/wpa_supplicant( 1181): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 61
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  906): default: reconnect()
D/MDST    (  906): default: setTeardownRequested(false)
D/MDST    (  906): default: setEnableApn apnType =default , enable=true
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  906): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  906): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  906): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  906):    returned true
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1181): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/WISPrService( 4198): >>>>>WISPrService start isConnected = false<<<<<
V/NativeCrypto( 1365): Read error: ssl=0x6671f5e0: I/O error during system call, Connection timed out
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  906): Exit handleNetworkDisconnect
D/WifiNative-wlan0(  906): doBoolean: SET pno 1
D/WISPrService( 4198): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WifiP2pService(  906): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '33 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 33 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/ConnectivityService(  906): resetConnections(wlan0, 3)
D/WifiService(  906): New client listening to asynchronous messages
D/PMS     (  906): acquireWL(43567ed8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): flush DNS cache for net 1(wlan0)
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
V/NativeCrypto( 1365): SSL shutdown failed: ssl=0x6671f5e0: I/O error during system call, Broken pipe
D/wpa_supplicant( 1181): CTRL_IFACE SET 'pno'='1'
E/wpa_supplicant( 1181): send_and_recv error -16 - cmd 75
D/wpa_supplicant( 1181): nl80211: Sched scan start failed: ret=-16 (Device or resource busy)
D/libc    (  362): [NET] entry_id:6   entry:0xb8cde3c0  removed 
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1" Return -1
D/libc    (  362): [NET] entry_id:8   entry:0xb8cde1b8  removed 
D/libc    (  362): [NET] entry_id:5   entry:0xb8cde2d8  removed 
D/libc    (  362): [NET] entry_id:7   entry:0xb8cd9af8  removed 
D/libc    (  362): [NET] entry_id:10   entry:0xb8cde8d0  removed 
D/libc    (  362): [NET] entry_id:11   entry:0xb8cdea68  removed 
D/libc    (  362): [NET] entry_id:1   entry:0xb8ce2f70  removed 
D/libc    (  362): [NET] entry_id:3   entry:0xb8ce2da8  removed 
D/libc    (  362): [NET] entry_id:4   entry:0xb8cd9c20  removed 
D/libc    (  362): [NET] entry_id:2   entry:0xb8cde458  removed 
D/libc    (  362): [NET] entry_id:9   entry:0xb8cd9b80  removed 
D/libc    (  362): [NET] entry_id:12   entry:0xb8cdebe8  removed 
D/libc    (  362): *************************
D/libc    (  362): *** DNS CACHE FLUSHED ***
D/libc    (  362): *************************
D/WifiNative-wlan0(  906):    returned false
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1181): reply (376) for get BSS: id=0
I/wpa_supplicant( 1181): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1181): freq=5220
I/wpa_supplicant( 1181): level=-47
I/wpa_supplicant( 1181): tsf=0000000104811466
I/wpa_supplicant( 1181): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=NG7005g
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=1
I/wpa_supplicant( 1181): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1181): freq=2412
I/wpa_supplicant( 1181): level=-59
I/wpa_supplicant( 1181): tsf=0000000104811486
I/wpa_supplicant( 1181): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=NG700
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=2
I/wpa_supplicant( 1181): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1181): freq=2427
I/wpa_supplicant( 1181): level=-85
I/wpa_supplicant( 1181): tsf=0000000104811496
I/wpa_supplicant( 1181): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1181): ssid=Gonzos
I/wpa_supplicant( 1181): ####
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024631
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024755
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024824
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024826
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024938
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024944
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026236
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026250
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 104811466, distance: ?(cm), distanceSd: ?(cm)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029201
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 104811486, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -200, -1
V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2427, timestamp: 104811496, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 3 to mScanResults
D/PMS     (  906): acquireWL(43598600): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  906): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10029)
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=CONNECTING
D/WifiManager( 1219): getScanResults enter 
D/WISPrService( 4198): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4198): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
I//system/bin/ip(  362): RTNETLINK answers: No such process
D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
I/logwrapper(  362): /system/bin/ip terminated by exit(2)
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (3) end of scan result ==
D/ConnectivityService(  906): reportInetCondition for net -1, percentage: 0 by  (1365/10029)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (3) end of scan result ==
D/WifiStateMachine(  906): startScan Pid: 906 Uid 1000
D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=CONNECTING
D/WifiNative-wlan0(  906): doBoolean: SET pno 0
I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1181): CTRL_IFACE SET 'pno'='0'
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: SCAN
D/WirelessDisplayService(  906): getDiscoveryDongleList
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1181): wpa_supplicant_scan enter
I/wpa_supplicant( 1181): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1181): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  906):    returned true
E/wpa_supplicant( 1181): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1181): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1181): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1181): Failed to initiate AP scan
I/wpa_supplicant( 1181): Failed to initiate AP scan, Failed_to_scan_counter:1
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/BatSI   (  906): WIFI scan started for: 450a0300 uid:1000
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): releaseWL(43598600): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): mActiveDefaultNetwork: -1
D/ConnectivityService(  906): handleInetConditionChange: no active default network - ignore
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10029)
D/PMS     (  906): releaseWL(43567ed8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10029)
,I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:1
,D/wpa_supplicant( 1181): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1181): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1181): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1181): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1181): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1181): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1181): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1181): nl80211: Event message available
D/wpa_supplicant( 1181): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1181): nl80211: Connect event
D/wpa_supplicant( 1181): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1181): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1181): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1181): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1181): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1181): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1181): Add randomness: count=12 entropy=6
I/wpa_supplicant( 1181): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1181): TDLS: Remove peers on association
D/wpa_supplicant( 1181): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1181): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1181): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1181): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1181): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1181): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1181): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1181): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1181): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1181): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1181): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1181): EAPOL: enable timer tick
D/wpa_supplicant( 1181): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1181): htc_wext_set_keepalive +
I/wpa_supplicant( 1181): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1181): getPrivFuncNum +	
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
I/wpa_supplicant( 1181): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1181): htc_wext_set_keepalive fnum = 0x8bf6
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
I/wpa_supplicant( 1181): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1181): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1181): Get randomness: len=32 entropy=7
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  906): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  906): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  906): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  906): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  906): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  906): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  906): Enter handleAssociatedWithEvent
D/WifiStateMachine(  906): Associated
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString i,d=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  906): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  906): Exit handleAssociatedWithEvent
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  906): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
D/Tethering(  906): interfaceStatusChanged wlan0, true
D/Tethering(  906): [isWifi] getHotspotEnabled: false
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
I/wpa_supplicant( 1181): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/wpa_supplicant( 1181): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb73579f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1181):    addr=c0:ff:d4:d3:aa:48
D/WifiStateMachine(  906): This record is existed, only update it...
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  906): updateConnectedAP...
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1181): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1181): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1181): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f3ab4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1181):    broadcast key
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1181): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1181): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1181): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1181): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1181): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1181): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
,D/WifiMonitor(  906): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1181): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1181): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1181): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1181): set send_ind_to_ndc = 0
I/wpa_supplicant( 1181): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1181): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1181): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1181): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1181): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1181): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1181): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1181): EAPOL: SUPP_PAE entering state AUTHENTICATED
,D/wpa_supplicant( 1181): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1181): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1181): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1181): EAPOL authentication completed successfully
I/wpa_supplicant( 1181): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1181): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1181): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1181): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
,D/Tethering(  906): interfaceStatusChanged wlan0, true
D/Tethering(  906): [isWifi] getHotspotEnabled: false
,D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/WifiStateMachine(  906): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  906): This record is existed, only update it...
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): mActiveDefaultNetwork: -1
,I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WISPrService( 4198): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4198): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiNative-wlan0(  906): doBoolean: SET pno 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1181): CTRL_IFACE SET 'pno'='0'
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:0
,D/DhcpStateMachine(  906): [StoppedState] Start DHCP
D/WifiStateMachine(  906): handlePreDhcpSetup Held wake lock during DHCP
,D/PMS     (  906): acquireWL(424a3d60): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 906 1000 null
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1181): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 0
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1181): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1181): Power_Mode_Type mode = 1
I/wpa_supplicant( 1181): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/WifiStateMachine(  906): handlePreDhcpSetup mBluetoothConnectionActive: false
E/wpa_supplicant( 1181): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/wpa_supplicant( 1181): nl80211: Event message available
D/wpa_supplicant( 1181): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1181): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  906):    returned null
E/WifiStateMachine(  906): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  906):    returned null
D/WifiP2pService(  906): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@425be308 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@425be308 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  906): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4921 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/PMS     (  906): acquireWL(44268f50): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
,D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  906): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTING DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
D/CaptivePortalTracker(  906): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/CaptivePortalTracker(  906): NoActiveNetworkState
,D/Tethering(  906): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  906): bSetPropertyMultiRAB:false
,D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.backuptransport (1576/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): releaseWL(44268f50): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
I/Tethering(  906): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  906): ipv4Default null
I/Tethering(  906): No IPv4 upstream interface, giving up.
,D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
,I/ConnectivityHelper( 1264): [onReceive] WIFI(1): CONNECTING
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1264/10076)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4640/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4640/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024631
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024755
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024824
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024826
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024938
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024944
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026236
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026250
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029201
,I/MusicStore( 4921): Database version: 95
D/wpa_supplicant( 1181): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1181): EAPOL: disable timer tick
,W/ContextImpl( 4921): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4921): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  345): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4921): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  345): Returning OperationFailed - no handler for errno 30
,E/cutils  (  345): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4921): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  345): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4921): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  345): Returning OperationFailed - no handler for errno 30
W/Vold    (  345): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4921, uid=10154, userID:0
,D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
,D/MediaRouterService(  906): Client com.google.android.music (pid 4921): Registered
,D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
I/MediaRouter( 4921): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.music (4921/10154)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (2794/10021)
,I/ActivityManager(  906): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4941 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4921): getSelectedRoute
,I/NetworkMonitor( 4921): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (4921/10154)
,D/ACRA    ( 4941): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4941): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4941): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4921, uid=10154, userID:0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(43737428): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,W/SystemClassLoaderAdder( 4941): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4941): Preparing secondary program dexes.
V/DexLibLoader( 4941): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4941): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
,D/PMS     (  906): releaseWL(43737428): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
V/DexLibLoader( 4941): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4941): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
V/DexLibLoader( 4941): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
W/DexLibLoader( 4941): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4941): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4941): Dex already copied
D/OdexVerifier( 4941): Odex verification is skipped.
V/DexLibLoader( 4941): Creating class loader
V/DexLibLoader( 4941): Finished creating class loader
V/DexLibLoader( 4941): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4941): Dex already copied
D/OdexVerifier( 4941): Odex verification is skipped.
V/DexLibLoader( 4941): Creating class loader
V/DexLibLoader( 4941): Finished creating class loader
V/DexLibLoader( 4941): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4941): Dex already copied
D/OdexVerifier( 4941): Odex verification is skipped.
V/DexLibLoader( 4941): Creating class loader
V/DexLibLoader( 4941): Finished creating class loader
V/DexLibLoader( 4941): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4941): Dex already copied
D/OdexVerifier( 4941): Odex verification is skipped.
V/DexLibLoader( 4941): Creating class loader
V/DexLibLoader( 4941): Finished creating class loader
V/DexLibLoader( 4941): Verifying classes from secondary dexes.
D/DexLibLoader( 4941): DexLibLoader.ensureDexLoaded took 15 ms
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,I/jxcore-log( 4838): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 4838): 
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1181): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1181): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1181): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1181): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  906): releaseWL(424a3d60): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [4][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1181): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): gateway: /192.168.1.1
,D/WifiNative-wlan0(  906): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1181): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1181): htc_wext_set_keepalive +
I/wpa_supplicant( 1181): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1181): getPrivFuncNum +	
I/wpa_supplicant( 1181): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1181): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1181): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1181): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1181): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  906): VerifyingLinkState enter
D/WifiStateMachine(  906): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  906): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  906): VerifyingLinkState: enableIpv6
D/WIFI_ICON( 1115): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -57, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/NetworkPolicy(  906): mWifiStateReceiver: meteredHint=false,EPS mode=false
,D/WifiWatchdogStateMachine(  906): WAN detection
,I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
V/ConnectivityService(  906): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  906): default: teardown()
D/MDST    (  906): default: setTeardownRequested(true)
D/MDST    (  906): default: setEnableApn apnType =default , enable=false
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WISPrService( 4198): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [1][0][0]
,I/wpa_supplicant( 1181): Change stage from stage0 to stage3
D/MDST    (  906): default: setTeardownRequested(true)
D/ConnectivityService(  906): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  906): Unexpected mtu value: android.net.wifi.WifiStateTracker@4243ba38
,D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/WifiStateMachine(  906): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  906): syncGetConfiguredNetworks
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  906): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
W/dalvikvm( 4941): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/libc    (  362): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  906): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  906): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,W/dalvikvm( 4941): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4941): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
D/WirelessDisplayService(  906): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,D/WirelessDisplayService(  906):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
,W/dalvikvm( 4941): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  906): acquireWL(425f1448): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
W/dalvikvm( 4941): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
W/dalvikvm( 4941): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
I/QuickSettingWifi( 1115): receive.wifiConnect:true wifiAPname:NG700 elapse:1
W/dalvikvm( 4941): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
I//system/bin/ip(  362): RTNETLINK answers: No such file or directory
I/logwrapper(  362): /system/bin/ip terminated by exit(254)
,I//system/bin/ip(  362): RTNETLINK answers: No such process
,I/logwrapper(  362): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  906): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(425f1448): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/jxcore-log( 4838): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 4838): 
,I/jxcore-log( 4838): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 4838): 
,W/dalvikvm( 4941): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,I/jxcore-log( 4838): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 4838): 
,W/dalvikvm( 4941): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,I/jxcore-log( 4838): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 4838): 
,I/jxcore-log( 4838): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 4838): 
,I/jxcore-log( 4838): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 4838): 
,E/FbInjectorInitializer( 4941): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4941): Verify
,D/WifiService(  906): New client listening to asynchronous messages
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4941/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4941): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4941): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4941): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  906): killProcessQuiet, pid=4604
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 4604:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4604
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  906): Client connection lost with reason: 4
,D/AutoSetting( 1325): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  906): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4992 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1325/10055)
D/AutoSetting( 1325): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1325): service - onStartCommand() screen is off, don't request location
,D/AutoSetting( 1325): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1325): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1325/10055)
,W/fb4a(:<default>):UserScope( 4941): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4941): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/MobileConnectivityChangeReceiver( 4992): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4992): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4992): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4992): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,W/fb4a(:<default>):UserScope( 4941): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/PMS     (  906): releaseWL(438b2f00): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  906): NetTransition Wakelock for ConnectedState released by timeout
,I/ActivityManager(  906): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=5007 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
I/jxcore-log( 4838): Test app app.js loaded
I/jxcore-log( 4838): 
,D/Process (  906): killProcessQuiet, pid=4214
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/Choreographer( 4838): Skipped 262 frames!  The application may be doing too much work on its main thread.
I/ActivityManager(  906): Killing 4214:com.google.android.gm/u0a107 (adj 15): empty #17
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4992/10079)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4992/10079)
D/PMS     (  906): acquireWL(42630250): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2189 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4992/10079)
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
,I/CheckinService( 2189): Checkin interval check for package: unspecified last checkin: 1453132491027 min interval config: 0 actual interval: 55068
,V/Tethering(  906): bSetPropertyMultiRAB:false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  906): acquireWL(423f8348): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2189 10029 WorkSource{10029 com.google.android.gms}
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: true
D/PMS     (  906): releaseWL(42630250): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  906): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
I/chromium( 4838): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
I/Tethering(  906): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
,I/Tethering(  906): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  906): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  906): ipv4Default 0.0.0.0/0 -> 192.168.1.1
,I/Tethering(  906): Found interface wlan0
,D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
,D/CaptivePortalTracker(  906): NoActiveNetworkState
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(425c41d0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.backuptransport (1576/10029)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (4921/10154)
D/PMS     (  906): releaseWL(425c41d0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.musicenhancer (4316/10053)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4640/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
,I/NetworkMonitor( 4921): type=WIFI subType= reason=null isConnected=true
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/AccTypeManager( 1337): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ConnectivityHelper( 1264): [onReceive] WIFI(1): CONNECTED
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1264/10076)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.backuptransport (1576/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4992/10079)
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
I/CheckinService( 2189): Checking schedule, now: 1453132546119 next: 1453132520984
I/CheckinService( 2189): active receiver: enabled
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4640/10100)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024631
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2189, uid=10029, userID:0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42fc1528): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024755
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024824
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024826
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024938
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024944
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026236
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026250
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029201
,I/ActivityManager(  906): Recipient 4214
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,W/AccTypeManager( 1337): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1337): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(42fc1528): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  906): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5025 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,I/ActivityManager(  906): Killing 4653:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  906): killProcessQuiet, pid=4653
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/CheckinService( 2189): Preparing to send checkin request
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
,I/EventLogService( 2189): Accumulating logs since 1453132486754
,E/ExternalAccountType( 1337): Unsupported attribute readOnly
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4653
,I/dalvikvm-heap( 4941): Grow heap (frag case) to 9.954MB for 84664-byte allocation
E/dalvikvm( 4941): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4941): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,I/CheckinRequestBuilder( 2189): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  906): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2189): Failed to find provider info for com.google.android.wearable.settings
,I/dalvikvm-heap( 4941): Grow heap (frag case) to 9.968MB for 28144-byte allocation
,E/cutils  (  345): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/dalvikvm( 4941): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4941): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4941): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4941): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,W/Vold    (  345): Returning OperationFailed - no handler for errno 30
E/dalvikvm( 4941): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4941): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4941): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4941): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4941): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/ContextImpl( 5025): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/dalvikvm( 4941): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4941): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4941): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4941): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4941): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4941): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4941): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,E/cutils  (  345): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 5025): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  345): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 5025): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  345): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 5025): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  345): Returning OperationFailed - no handler for errno 30
,E/cutils  (  345): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 5025): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  345): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4941): Grow heap (frag case) to 10.014MB for 39954-byte allocation
,I/dalvikvm-heap( 4941): Grow heap (frag case) to 10.090MB for 79892-byte allocation
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (5025/10151)
,V/WebViewChromiumFactoryProvider( 5025): Binding Chromium to main looper Looper (main, tid 1) {41ab5fb8}
,I/LibraryLoader( 5025): Expected native library version number "",actual native library version number ""
,I/chromium( 5025): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5025): Initializing chromium process, renderers=0
,D/PMS     (  906): acquireWL(43747cf0): PARTIAL_WAKE_LOCK  AudioMix 0x1 369 1013 null
,D/PMS     (  906): acquireWL(43ec76f8): PARTIAL_WAKE_LOCK  AudioMix 0x1 369 1013 null
,E/AudioManagerAndroid( 5025): BLUETOOTH permission is missing!
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(43747cf0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (2189/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
I/Adreno-EGL( 5025): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 5025): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 5025): Build Date: 08/28/14 Thu
I/Adreno-EGL( 5025): Local Branch: 
I/Adreno-EGL( 5025): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 5025): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 5025):                  aa63bbd948f41d15fc72f585e
V/GLSActivity( 1365): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1365): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NSApplication( 5025): Starting up...
,I/dalvikvm-heap( 4941): Grow heap (frag case) to 10.276MB for 75760-byte allocation
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (5025/10151)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (5025/10151)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4941/10027)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4034/10160)
,I/ActivityManager(  906): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5062 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{437446a8 u0 ReceiverList{435ecf90 4941 com.facebook.katana/10027/u0 remote:43727ee0}}
,W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{437446a8 u0 ReceiverList{435ecf90 4941 com.facebook.katana/10027/u0 remote:43727ee0}}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4034/10160)
,W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4433d2b8 u0 ReceiverList{435a0790 4941 com.facebook.katana/10027/u0 remote:435a06c8}}
,D/Process (  906): killProcessQuiet, pid=4667
,I/ActivityManager(  906): Killing 4667:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
I/ActivityManager(  906): Recipient 4667
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024631
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024755
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024824
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024826
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024938
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024944
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026236
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026250
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029201
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4941/10027)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4941/10027)
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,W/dalvikvm( 5062): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4941/10027)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10029)
,W/dalvikvm( 5062): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 5062): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 5062): install
,I/MultiDex( 5062): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (2794/10021)
,I/MultiDex( 5062): loading existing secondary dex files
,I/MultiDex( 5062): load found 3 secondary dex files
,I/MultiDex( 5062): install done
,W/dalvikvm( 5062): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 5062): VFY: unable to resolve instance field 36
,W/dalvikvm( 5062): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 5062): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/PMS     (  906): acquireWL(425ce2b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(425ce2b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1325): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4992): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/AutoSetting( 1325): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/MobileConnectivityChangeReceiver( 4992): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1325): service - onStartCommand() screen is off, don't request location
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1325/10055)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1325/10055)
D/AutoSetting( 1325): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1325): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (5025/10151)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4034/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4034/10160)
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/cutils  (  345): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2189, uid=10029, userID:0
,W/Vold    (  345): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4941): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/cutils  (  345): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
,W/Vold    (  345): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4941): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/cutils  (  345): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,W/Vold    (  345): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4941): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10029)
,I/ProviderInstaller( 5062): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1219): callingUid 10029, callindPid: 1219
,W/dalvikvm( 5062): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 5062): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/LocationInitializer( 2189): Restart initialization of location
,E/MDM     ( 1219): [132] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/dalvikvm( 5062): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 5062): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 5062): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 5062): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 5062): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/AuthorizationBluetoothService( 1365): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1365): Proximity feature is not enabled.
,V/GLSActivity( 1365): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1219): No location to return for getLastLocation()
,W/FusedLocationProvider( 1219): location=null
D/PMS     (  906): acquireWL(442b2538): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(442b2538): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024631
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024755
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024824
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024826
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024938
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024944
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026236
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026250
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029201
,I/WVCdm   (  369): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  369): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  369): CdmEngine::OpenSession
,I/WVCdm   (  369): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  369): CdmEngine::GenerateKeyRequest
,D/NativeLibraryUtils( 5062): Install completed successfully. count=14 extracted=0
,W/dalvikvm( 4838): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4838): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 4838): BLE advertisement is supported
I/jxcore-log( 4838): 
,D/WVCdm   (  369): PrepareKeyRequest: nonce=228106990
,D/AutoSetting( 1507): service - handleMessage() stop self,
,I/WVCdm   (  369): CdmEngine::CloseSession
,D/AutoSetting( 1507): service - handleMessage() quit looper
,D/AutoSetting( 1507): service - onDestroy() END
,D/Process (  906): killProcessQuiet, pid=4433
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4433:com.google.android.talk/u0a111 (adj 15): empty #17
,W/Settings( 5062): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (5062/10029)
,I/ActivityManager(  906): Recipient 4433
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Adreno-EGL( 5062): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 5062): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 5062): Build Date: 08/28/14 Thu
I/Adreno-EGL( 5062): Local Branch: 
I/Adreno-EGL( 5062): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 5062): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 5062):                  aa63bbd948f41d15fc72f585e
,I/WVCdm   (  369): CdmEngine::OpenSession
,I/WVCdm   (  369): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  369): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  369): PrepareKeyRequest: nonce=641964698
,I/WVCdm   (  369): CdmEngine::CloseSession
,I/Adreno-EGL( 5062): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 5062): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 5062): Build Date: 08/28/14 Thu
I/Adreno-EGL( 5062): Local Branch: 
I/Adreno-EGL( 5062): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 5062): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 5062):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 5062): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 5062): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 5062): Build Date: 08/28/14 Thu
I/Adreno-EGL( 5062): Local Branch: 
I/Adreno-EGL( 5062): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 5062): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 5062):                  aa63bbd948f41d15fc72f585e
,I/CheckinRequestBuilder( 2189): Classify the device as Phone.
,D/libc    ( 2189): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2189): [NET] getaddrinfo-,err=8
D/libc    ( 2189): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2189): [NET] getaddrinfo-, 1
D/libc    ( 2189): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =120 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =8a96 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 96
D/libc    (  362): [NET]res_nsend:resplen=84
D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2189): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2189): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2189): [NET] getaddrinfo-,err=8
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  362): [NET]res_nsend:resplen=172
D/libc    (  362): [NET]res_queryN: exit 3, ancount=4
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  906): Find DNS Address www.htc.com/104.81.130.175
,D/libc    ( 2189): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2189): [NET] getaddrinfo-,err=8
D/libc    ( 2189): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2189): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2189): Sending checkin request (12206 bytes)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4941/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4941/10027)
,W/fb4a(:<default>):UserScope( 4941): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4941): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4941/10027)
,I/CheckinRequestBuilder( 2189): Checkin reason type: 8 attempt count: 1
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=11 [26][3][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/ActivityManager(  906): Cannot resolve ContentProvider=com.google.android.wearable.settings
,E/ActivityThread( 2189): Failed to find provider info for com.google.android.wearable.settings
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4941/10027)
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (2189/10029)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,I/CheckinRequestBuilder( 2189): Classify the device as Phone.
,I/CheckinTask( 2189): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 2189): Checking schedule, now: 1453132548989 next: 1453655485984
,I/CheckinService( 2189): active receiver: disabled
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2189, uid=10029, userID:0
,E/fb4a(:<default>):LocalFbBroadcastManager( 4941): Called registerBroadcastReceiver twice.
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024631
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024755
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024824
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024826
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024938
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024944
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026236
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026250
,D/CheckinService( 2189): Recording last checkin time for package unspecified as 1453132549006
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029201
,D/PMS     (  906): releaseWL(423f8348): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
,D/PMS     (  906): acquireWL(4414bcd0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 1365): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    ( 1365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1365): [NET] getaddrinfo-,err=8
D/libc    ( 1365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1365): [NET] getaddrinfo-, 1
,D/libc    ( 1365): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
,D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =6a18 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10029)
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 202
D/libc    (  362): [NET]res_nsend:resplen=79
,D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1365): [NET] getaddrinfo_proxy-, success
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4941/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4941/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4941/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4941/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4941/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4941/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4941/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4941/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4941/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4941/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4941/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4941/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4941/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4941/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4941/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4941/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4941/10027)
,D/libc    ( 1365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1365): [NET] getaddrinfo-,err=8
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4941/10027)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4941/10027)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4941/10027)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4941/10027)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4941/10027)
,D/WifiStateMachine(  906): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    ( 1365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1365): [NET] getaddrinfo-,err=8
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10029)
,D/PMS     (  906): acquireWL(42f58e30): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10029)
,D/PMS     (  906): releaseWL(4414bcd0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10029)
,D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1365/10029)
,D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
,D/PMS     (  906): releaseWL(42f58e30): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(426c22a8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10029)
,D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1365/10029)
,D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10029)
,D/PMS     (  906): releaseWL(43ec76f8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1365/10029)
,D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024631
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024755
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024824
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024826
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024938
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024944
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026236
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026250
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029201
,D/PMS     (  906): releaseWL(426c22a8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(425c46a8): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4921 10154 null
,W/ContextImpl( 4921): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4921, uid=10154, userID:0
I/MusicLeanback( 4921): Conditions not met for autocaching.
,D/PMS     (  906): releaseWL(425c46a8): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/MusicLeanback( 4921): Stop autocaching.
W/ContextImpl( 4921): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=30 [10][3][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,I/GAV2    ( 5025): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  906): killProcessQuiet, pid=4316
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4316:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4316
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  906): killProcessQuiet, pid=4705
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4705:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4705
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  906): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1337): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  906): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5119 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
I/Prism.ItemManager( 1264): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1264): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Prism.ItemManager( 1264): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
I/Launcher( 1264): Deferring update until onResume
,D/Launcher( 1264): waitUntilResume // bindAppsUpdated
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,W/SystemReader( 1252): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
W/AccTypeManager( 1337): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1337): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,E/ExternalAccountType( 1337): Unsupported attribute readOnly
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,D/PhoneApp( 1238): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 5119): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5119): MmsConfig.loadMmsSettings
,W/dalvikvm( 5119): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 5119): VFY: unable to resolve instance field 36
,W/dalvikvm( 5119): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
I/ActivityManager(  906): Waited long enough for: ServiceRecord{434abb90 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,V/JNIHelp ( 5119): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  906): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=5142 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=5119, uid=10111, userID:0
,D/MessageFrequencyProvider( 5142): onCreate
,W/Settings( 5119): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MmsCustomizationProvider( 5142): query uri: content://htc-mms-customization/mms-ua/ua_string
,V/GetPrviateResource( 5142): GetPrviateResource
,V/GetPrviateResource( 5142): GetPrviateResource
,D/MmsCustomizationProvider( 5142): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=5119, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=5119, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=5119, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=5119, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=5119, uid=10111, userID:0
I/Babel   ( 5119): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 5119): MmsConfig.loadFromDatabase
D/PMS     (  906): acquireWL(42e897d0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 5119 10111 null
E/Babel   ( 5119): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 5119): MmsConfig.loadFromResources
E/Babel   ( 5119): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 5119): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/[PluginManager]RegisterService( 1325): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
I/[PluginManager]RegisterService( 1325): handle notify Blinkfeed plugin client changed
W/PackageManager(  906): Unable to load service info ResolveInfo{426c86f0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,I/IcingCorporaProvider( 3035): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ProviderInstaller( 5119): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  906): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
D/PMS     (  906): acquireWL(431e0288): PARTIAL_WAKE_LOCK  Icing 0x1 2189 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(44334630): PARTIAL_WAKE_LOCK  AsyncService 0x1 4034 10160 null
D/PMS     (  906): releaseWL(44334630): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/PMS     (  906): releaseWL(42e897d0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
D/MessageCustFlag( 5142): sense_version=6.0
D/BTAccessoryUtil( 5142): createReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,D/BTAccessoryUtil( 5142): registerReceiver return intent = null
D/MessageCustFlag( 5142): sku_id=99
,W/SystemReader( 5142): Cannot find message_ambs_application_id, use default value instead
,D/Messaging( 5142): supportCMAS(SIE)/init? false/true
D/MmsConfig( 5142): networkCode: 
,D/MessageCustFlag( 5142): sku_id=99
D/MmsConfig( 5142): SIE smsPri: null
,D/MmsConfig( 5142): networkCode: 
,D/HtcTelephonyCapability( 5142): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 5142): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 5142): getRATByHtcTelephonyCapability:1
D/Process (  906): killProcessQuiet, pid=4640
,W/SystemReader( 5142): Cannot find qct_8960_interface, use default value instead
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 4640:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,D/PackageBroadcastService( 2189): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/ActivityManager(  906): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/ActivityManager(  906): Recipient 4640
,I/PackageBroadcastService( 2189): Null package name or gms related package.  Ignoreing.
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Icing   ( 2189): updateResources: need to parse f{com.google.android.gms}
I/ActivityManager(  906): Resuming delayed broadcast
,D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  906): start
,I/GCoreNlp( 1219): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  906): applying state to connected service
D/PMS     (  906): acquireWL(427e66d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(427e66d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  906): applying state to connected service
D/PMS     (  906): acquireWL(43b10b98): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(43b10b98): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4432a210): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4432a210): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 3035): UpdateCorporaTask done [took 427 ms] updated apps [took 427 ms] 
,I/Prism.ItemManager( 1264): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1264): loadItems() com.htc.launcher.pageview.WidgetManager@41b43c70 +
,I/Prism.WidgetManager( 1264): onLoadItems() +
,I/Icing   ( 2189): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2189): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  906): releaseWL(431e0288): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42727408): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  906): sending alarm PendingIntent{43502810: PendingIntentRecord{4237cc88 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=119790, Int=0
,D/PMS     (  906): acquireWL(43b468a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42727408): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10029)
,D/PMS     (  906): acquireWL(43da84e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(43da84e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(43b468a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(43742fe8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024631
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024755
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024824
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024826
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024938
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024944
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026236
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026250
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029201
,D/PMS     (  906): releaseWL(43742fe8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(43ed3398): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [9][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024631
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024755
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024824
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024826
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024938
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024944
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026236
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026250
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029201
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/Prism.WidgetManager( 1264): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1264): onLoadItems() -
,I/Prism.ItemManager( 1264): loadItems() com.htc.launcher.pageview.WidgetManager@41b43c70 -
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/PMS     (  906): acquireWL(43b03218): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4348fb90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1219): Vacuum at: now=1453132558289 tag=VacuumService
D/PMS     (  906): releaseWL(43ed3398): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(43b03218): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(43687ed0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10029)
,D/PMS     (  906): releaseWL(4348fb90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024631
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024755
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024824
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024826
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024938
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024944
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026236
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026250,
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029201
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(43687ed0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(44362880): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024631
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024755
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024824
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024826
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024938
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024944
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026236
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026250
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029201
D/PMS     (  906): releaseWL(44362880): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(426b8410): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024631
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024755
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024824
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024826
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024938
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024944
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026236
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026250
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029201
,D/PMS     (  906): releaseWL(426b8410): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(43933418): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024631
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024755
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024824
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024826
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024938
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024944
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026236
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026250
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029201
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(43933418): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(43b8fbe8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024631
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024755
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024824
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024826
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024938
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024944
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026236
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026250
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029201
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/PhoneApp( 1238): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1238): -- N1 =0
,D/PhoneApp( 1238): -- N2 =0
,D/PhoneApp( 1238): -- N3 =0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(4414b938): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4414b938): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42698b68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(43b8fbe8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4269f310): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024631
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024755
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024824
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024826
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024938
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024944
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026236
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026250
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029201
,D/PMS     (  906): releaseWL(4269f310): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/Messaging( 5142): mNeedToUpdateDate2 start
,D/MmsConfig( 5142): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 5142): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 5142): 
D/MmsAsyncWorkHandler( 5142): HM tk = 20001
D/ReportIndicatorCache( 5142): MSG_QUERY_REPORTS >>
,D/SettingsManager( 5142): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41ab7538
,I/Messaging( 5142): mccmnc> 
D/DraftCache( 5142): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 5142): [DraftCache/1] refresh
,D/MmsConfig( 5142): networkCode: 
,D/Messaging( 5142): ViewCache CreatePreloadOnlyConversationList
D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/MmsSmsV2Provider( 1238):  phoneType = -1
,D/MmsSmsV2Provider( 1238): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/MessageCustFlag( 5142): sense_version=6.0
,D/Jerry   ( 5142): start to preload cursor >>>>>>>
,D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/MmsSmsV2Provider( 1238):  phoneType = -1
,D/MmsSmsV2Provider( 1238): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/PhoneStorageUtil( 5142): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 5142): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 5142): createReceiver
,D/Messaging( 5142): mNeedToUpdateDate2: false
D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 69
,D/MmsSmsV2Provider( 1238):  phoneType = -1
,D/TelephUtils( 1238): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,V/MmsProvider( 1238): Update uri=content://mms, match=0
,V/MmsProvider( 1238): selection=st=129 AND m_type!=134
D/Messaging( 5142): Reset downloading state: 0
,V/MmsSystemEventReceiver( 5142): TransactionService is going to be woken up.
D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MmsSmsV2Provider( 1238):  phoneType = -1
,D/MmsSmsV2Provider( 1238): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/Messaging( 5142): ViewCache CreatePreload
,D/Messaging( 5142): ViewCache CreatePreloadOnlyMultipleOpsList
,V/TransactionService( 5142): 1-Creating TransactionService
,D/Cust_MMSMS( 5142): _has_set_default_values_2=true
D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 69
,D/AccFlag ( 1238): sku_id=99
,D/DraftCache( 5142): [DraftCache/511] rebuildCache
,D/MsgPreferenceUtils( 5142): def_index: 0
V/TransactionService( 5142): onStartCommand: 1
,D/MmsSystemEventReceiver( 5142): unRegisterForConnectionStateChanges
V/TransactionService( 5142): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 5142): Loading previous transactions.
,D/MsgPreferenceUtils( 5142): globalIndex = 1
D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/MmsSmsV2Provider( 1238):  phoneType = -1
D/MmsSmsV2Provider( 1238): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/MsgPreferenceUtils( 5142): phone state: true
,D/MsgPreferenceUtils( 5142): sd state: false
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/MsgPreferenceUtils( 5142): vIndex = 0
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1238): device_type: 1
D/TransactionService( 5142): Force set service start id to 1
V/TransactionService( 5142): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 5142): unRegisterForConnectionStateChanges
D/TransactionService( 5142): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 5142): Destroying TransactionService
,D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 69
,D/Jerry   ( 1238): URI_DRAFT
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
D/Messaging( 5142): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
V/TransactionService( 5142): 4-Handling incoming message: { when=-5ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/DraftCache( 5142): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 5142): [DraftCache/511] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 5142): 
D/MmsAsyncWorkHandler( 5142): HM tk = 20002
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1238): sku_id=99
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1238): sku_id=99
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1219): Scheduling Phenotype for one-off execution 6807 seconds from now (1453132559032)
,D/GetConfigurationSnapshotOperation( 1219): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1219): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1219): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  906): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/libc    ( 1219): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1219): [NET] getaddrinfo-,err=8
D/libc    ( 1219): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1219): [NET] getaddrinfo-, 1
,D/libc    ( 1219): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =37b +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  362): [NET] NOT IN CACHE
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  362): [NET]res_nsend:resplen=87
D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1219): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1219): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1219): [NET] getaddrinfo-,err=8
D/libc    ( 1219): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1219): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  906): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [8][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  906): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(438aa050): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,V/AlarmManager(  906): sending alarm PendingIntent{4232f458: PendingIntentRecord{422d8230 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=121712, Int=0
,D/LocationManagerService(  906): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(438aa050): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,V/GLSActivity( 1365): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1365): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 1365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1365): [NET] getaddrinfo-,err=8
D/libc    ( 1365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1365): [NET] getaddrinfo-, 1
,D/libc    ( 1365): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =bffd +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1365): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1365): [NET] getaddrinfo-,err=8
,D/libc    ( 1365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1365): [NET] getaddrinfo-,err=8
D/libc    ( 1365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1365): [NET] getaddrinfo-,err=8
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [10][0][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): releaseWL(42698b68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4243f2a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024631
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024755
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024824
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024826
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024938
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024944
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026236
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026250
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029201
,D/PMS     (  906): releaseWL(4243f2a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42e65ad0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10029)
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024631
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024755
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024824
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024826
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024938
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024944
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026236
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026250
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029201
,D/PMS     (  906): releaseWL(42e65ad0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/GAV4    ( 5119): Thread[GAThread,5,main]: No campaign data found.
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(42e64d78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/BatteryService(  906): n_update end
D/PMS     (  906): releaseWL(42e64d78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(423e53e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  906): sending alarm PendingIntent{442b6f00: PendingIntentRecord{4241cb60 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=134064, Int=0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1365/10029)
,D/PMS     (  906): releaseWL(423e53e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1325): service - mHandler: update timezone
,D/AutoSetting( 1507): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1507): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1507): service - onCreate()
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1507): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate,
,D/AutoSetting( 1507): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/DotMatrix( 1560): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1560): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1507): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1507): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1507): service - mHandler: update timezone
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1507): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1507): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1507): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1507): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1560): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1560): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1115): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41e11998 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.htc.htclocationservice 3 7 2 11
,D/AutoSetting( 1325): service - mHandler: update timezone
,D/AutoSetting( 1507): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1507): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1507): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1507): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 1507): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1507): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1507): service - mHandler: update timezone
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/DotMatrix( 1560): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
D/DotMatrix( 1560): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,D/AutoSetting( 1507): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1507): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1507): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1507): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1560): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1560): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,D/AutoSetting( 1325): service - handleMessage() stop self
,I/PhoneStatusBar( 1115): removeNotification.gc:60
,D/AutoSetting( 1325): service - handleMessage() quit looper
,D/AutoSetting( 1325): service - onDestroy() END
,I/RemoteViews( 1115): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41e88910 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.htc.htclocationservice 3 9 3 11
,D/PMS     (  906): acquireWL(43110bf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42330568: PendingIntentRecord{42329060 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142037, Int=0
,D/GpsLocationProvider(  906): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  906): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  906): acquireWL(426805f0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/PMS     (  906): releaseWL(43110bf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =5e8d +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  362): [NET]res_nsend:resplen=238
,D/libc    (  362): [NET]res_queryN: exit 3, ancount=10
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
I/global  (  906): call createSocket() return a new socket.
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  906): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  906): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  906): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  906):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  906): releaseWL(426805f0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/Process (  906): killProcessQuiet, pid=4735
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4735:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4735
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/ContactMessageStore( 1238): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1238): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{43806cd8 u0 com.htc.htclocationservice/.AutoSettingService}
,I/ClearcutLoggerApiImpl( 2189): disconnect managed GoogleApiClient
,D/PMS     (  906): acquireWL(41e8e478): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(41e8e478): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 1507): service - handleMessage() stop self
,D/AutoSetting( 1507): service - onDestroy() END
,D/AutoSetting( 1507): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=4722
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4722:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4722
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(4247f690): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10027}
,V/AlarmManager(  906): sending alarm PendingIntent{428bd650: PendingIntentRecord{42a7d2e8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=168934, Int=0
,D/PMS     (  906): releaseWL(4247f690): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1238): switchBindHtcMsgCursor: null
,D/PMS     (  906): acquireWL(42683bc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232f458: PendingIntentRecord{422d8230 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=181712, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42683bc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(425225d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): releaseWL(425225d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(41d04d50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(41d04d50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/ClearcutLoggerApiImpl( 1365): disconnect managed GoogleApiClient
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(4261af48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232f458: PendingIntentRecord{422d8230 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=241712, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4261af48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(435ec280): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(435ec280): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(426b0208): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4232f458: PendingIntentRecord{422d8230 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=301712, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(426b0208): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(42617ec8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42617ec8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4371ed00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4371ed00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4838): --= Surplus to requirements =--
I/jxcore-log( 4838): 
I/jxcore-log( 4838): ****TEST TOOK:  ms ****
I/jxcore-log( 4838): 
,I/jxcore-log( 4838): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4838): 
,E/cutils-trace( 5239): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 5239): ====startRecUseTime====
D/htc.customization.log.level( 5239):  is 
,W/CustomizationLogLevel( 5239): Level value is invalid, use default level 2
,D/CustomizationManager( 5239):  Read ACC file spent 0.120 (s)
D/CIDMapFileReader( 5239): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5239): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5239): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5239): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 5239): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5239): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 5239): Parsing tag item name = HTC__016
D/CIDMapFileReader( 5239): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5239): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5239): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5239): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 5239): Parsing tag category name = system
,I/CustomizationCIDLoader( 5239): Parsing tag category name = application
I/CustomizationCIDLoader( 5239): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5239): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5239): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5239): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 5239): Parsing tag category name = Settings
,D/CustomizationManager( 5239):  Read CID file spent 0.179 (s)
,D/CustomizationManager( 5239):  All configurations done spent 0.179 (s)
W/HtcNativeFlag( 5239): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 5239): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 5239): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 5239): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  906): deletePackageAsUser: pkg=com.test.thalitest, pid=5239, uid=2000 user=0
,I/ActivityManager(  906): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
,D/Process (  906): killProcessQuiet, pid=4838
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,I/ActivityManager(  906): Killing 4838:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
,W/ActivityManager(  906): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  906):   Force finishing activity ActivityRecord{41bd5bb8 u0 com.test.thalitest/.MainActivity t2}
,W/asset   (  906): Copying FileAsset 0x6f7a08d0 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,W/PackageSettings(  906): Skipping PackageSetting{421e6010 com.example.hello/10397} due to missing metadata
,E/JavaBinder(  906): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  906): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 1206): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  906): Got RemoteException sending setActive(false) notification to pid 4838 uid 10389
,I/ActivityManager(  906): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/WindowState(  906): WIN DEATH: Window{423f5cc8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  906): Client connection lost with reason: 4
,D/DotMatrix( 1560): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1560): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1560): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
,I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
,I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.test.thalitest
,I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1337): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/GeofencerStateMachine( 1219): Ignoring removeGeofence because network location is disabled.
D/PMS     (  906): acquireWL(44346d58): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(44346d58): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/VoicemailCleanupService( 1299): Cleaning up data for package: com.test.thalitest
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/Prism.ItemManager( 1264): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1264): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
,I/[PluginManager]RegisterService( 1325): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/Launcher( 1264): Deferring update until onResume
,D/Launcher( 1264): waitUntilResume // bindAppsRemoved
,D/Prism.PackageStateRece_( 1264): action: android.intent.action.PACKAGE_REMOVED
,I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/[PluginManager]RegisterService( 1325): handle notify Blinkfeed plugin client changed
,W/SystemReader( 1252): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,W/AccTypeManager( 1337): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1337): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/IcingCorporaProvider( 3035): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
,I/ActivityManager(  906): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5255 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,E/ExternalAccountType( 1337): Unsupported attribute readOnly
,I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,D/PhoneApp( 1238): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,D/PMS     (  906): acquireWL(43edd698): PARTIAL_WAKE_LOCK  Icing 0x1 2189 10029 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 3035): UpdateCorporaTask done [took 381 ms] updated apps [took 380 ms] 
,E/SQLiteDatabase( 5255): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 5255): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5255): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5255): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5255): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5255): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5255): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5255): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5255): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5255): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5255): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5255): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5255): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5255): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5255): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5255): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 5255): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 5255): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 5255): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 5255): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 5255): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 5255): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5255): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5255): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5255): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5255): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5255): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5255): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5255): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 5255): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 5255): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5255): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5255): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 5255): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 5255): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5255): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5255): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5255): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 5255): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 5255): 	at android.database.sqlite.SQLiteDatabase.open,Database(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 5255): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 5255): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 5255): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5255): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5255): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 5255): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 5255): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 5255): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 5255): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 5255): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 5255): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5255): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 5255): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 5255): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5255): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5255): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 5255): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 5255): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 5255): Opened ClientFlag.db in read-only mode
,E/SQLiteLog( 5255): (3850) statement aborts at 59: [DELETE FROM CachedSearch111 WHERE timestamp<?] disk I/O error
,W/GAV2    ( 5255): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/SQLiteDBG( 5255): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.apps.docs/databases/DocList.db, handle = 0x5c9dc210
E/AbstractDatabaseInstance( 5255): Failed to delete from CachedSearch111
E/AbstractDatabaseInstance( 5255): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AbstractDatabaseInstance( 5255): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AbstractDatabaseInstance( 5255): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AbstractDatabaseInstance( 5255): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AbstractDatabaseInstance( 5255): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AbstractDatabaseInstance( 5255): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AbstractDatabaseInstance( 5255): 	at ahl.b(AbstractDatabaseInstance.java:310)
E/AbstractDatabaseInstance( 5255): 	at aid.a(DatabaseModelLoader.java:340)
E/AbstractDatabaseInstance( 5255): 	at aiN.a(ObsoleteDataCleanerImpl.java:100)
E/AbstractDatabaseInstance( 5255): 	at fv.run(DocsApplication.java:288)
,W/dalvikvm( 5255): threadid=11: thread exiting with uncaught exception (group=0x41680e30)
E/AndroidRuntime( 5255): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 5255): Process: com.google.android.apps.docs, PID: 5255
E/AndroidRuntime( 5255): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 5255): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 5255): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 5255): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 5255): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 5255): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 5255): 	at ahl.b(AbstractDatabaseInstance.java:310)
E/AndroidRuntime( 5255): 	at aid.a(DatabaseModelLoader.java:340)
E/AndroidRuntime( 5255): 	at aiN.a(ObsoleteDataCleanerImpl.java:100)
E/AndroidRuntime( 5255): 	at fv.run(DocsApplication.java:288)
,I/ActivityManager(  906): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5278 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,E/ActivityManager(  906): App crashed! Process: com.google.android.apps.docs
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (5255/10100)
,D/Process ( 5255): killProcess, pid=5255
,D/Process ( 5255): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (5255/10100)
,E/DropBoxManagerService(  906): Can't write: system_app_crash
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
,I/ActivityManager(  906): Recipient 5255
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Process com.google.android.apps.docs (pid 5255) has died.
,W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.apps.docs/.sync.syncadapter.ContentSyncService in 1000ms
,W/ContextImpl( 5278): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  906): Delay finish: com.android.keychain/.KeyChainBroadcastReceiver
,E/SQLiteDatabase( 5278): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5278): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5278): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5278): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5278): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5278): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5278): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5278): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5278): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5278): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5278): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5278): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5278): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5278): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5278): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5278): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 5278): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 5278): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5278): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5278): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5278): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 5278): threadid=10: thread exiting with uncaught exception (group=0x41680e30)
,E/ActivityManager(  906): App crashed! Process: com.android.keychain
E/AndroidRuntime( 5278): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5278): Process: com.android.keychain, PID: 5278
E/AndroidRuntime( 5278): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5278): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5278): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5278): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5278): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5278): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5278): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5278): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5278): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5278): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5278): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5278): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5278): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5278): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5278): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 5278): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 5278): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5278): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5278): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5278): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
,D/Process ( 5278): killProcess, pid=5278
,D/Process ( 5278): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453132753812.dbox_tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager(  906): Recipient 5278
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.android.keychain (pid 5278) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10546ms
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=5295 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
,D/AppTag  ( 5295): getInstance(Context context)
,D/AppTag  ( 5295): getInstance(Context context)
,D/AppTag  ( 5295): onCreate()
,I/ActivityManager(  906): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  906): acquireWL(41ff4ea8): PARTIAL_WAKE_LOCK  AsyncService 0x1 4034 10160 null
,D/PMS     (  906): releaseWL(41ff4ea8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/Icing   ( 2189): Indexing 5DDFBB04CEF4FFE894538F4951832FAB899ACA77 from com.google.android.googlequicksearchbox
I/ActivityManager(  906): Resuming delayed broadcast
,W/PackageManager(  906): Unable to load service info ResolveInfo{42366138 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,I/Prism.ItemManager( 1264): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1264): loadItems() com.htc.launcher.pageview.WidgetManager@41b43c70 +
,I/Prism.WidgetManager( 1264): onLoadItems() +
,W/dalvikvm( 4477): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/Process (  906): killProcessQuiet, pid=4756
,I/ActivityManager(  906): Killing 4756:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PackageBroadcastService( 2189): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2189): Clearing selected account for com.test.thalitest
I/ActivityManager(  906): Recipient 4756
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/SQLiteLog( 2189): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 2189): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x6563a8b0
,I/LocationSettingsChecker( 2189): Removing dialog suppression flag for package com.test.thalitest
E/Icing   ( 2189): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
,E/Icing   ( 2189): Could not init tag ds.tag.deleted
,E/DriveAsyncService( 2189): disk I/O error (code 3850)
E/DriveAsyncService( 2189): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2189): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2189): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2189): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2189): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2189): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2189): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2189): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2189): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2189): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2189): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2189): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2189): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2189): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2189): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2189): 	at java.lang.Thread.run(Thread.java:864)
,E/SQLiteDatabase( 2189): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 2189): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2189): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2189): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2189): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2189): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2189): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2189): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2189): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2189): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2189): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2189): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2189): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2189): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2189): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2189): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 2189): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 2189): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 2189): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 2189): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2189): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2189): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2189): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 2189): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 2189): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 2189): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 2189): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 2189): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 2189): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 2189): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 2189): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 2189): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 2189): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 2189): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 2189): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 2189): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 2189): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 2189): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 2189): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 2189): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 2189): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 2189): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 2189): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 2189): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 2189): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 2189): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteDatabase( 2189): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 2189): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2189): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2189): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2189): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2189): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2189): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2189): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2189): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2189): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2189): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2189): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2189): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2189): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2189): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2189): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2189): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 2189): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2189): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2189): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2189): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/PhenotypeInitializer( 2189): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 2189): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 2189): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 2189): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/PhenotypeInitializer( 2189): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/PhenotypeInitializer( 2189): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 2189): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 2189): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 2189): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/PhenotypeInitializer( 2189): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/PhenotypeInitializer( 2189): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/PhenotypeInitializer( 2189): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/PhenotypeInitializer( 2189): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2189): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2189): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 2189): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 2189): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 2189): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 2189): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 2189): 	at android.os.Looper.loop(Looper.java:157)
E/PhenotypeInitializer( 2189): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/SQLiteOpenHelper( 2189): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 2189): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 2189): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,E/SQLiteLog( 2189): (8) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/gH_CompatibleDatabase( 2189): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,W/dalvikvm( 2189): threadid=45: thread exiting with uncaught exception (group=0x41680e30)
,E/ActivityManager(  906): App crashed! Process: com.google.android.gms
,D/Process ( 2189): killProcess, pid=2189
,D/Process ( 2189): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/AndroidRuntime( 2189): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 2189): Process: com.google.android.gms, PID: 2189
E/AndroidRuntime( 2189): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 2189): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2189): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 2189): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 2189): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2189): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 2189): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 2189): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 2189): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2189): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2189): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2189): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager(  906): Recipient 2189
,I/ActivityManager(  906): Process com.google.android.gms (pid 2189) has died.
,W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 10107ms
,W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 20107ms
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20104ms
D/WifiService(  906): Client connection lost with reason: 4
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20104ms
D/PMS     (  906): handleWLDeath(43edd698): PARTIAL_WAKE_LOCK  Icing 0x1
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20104ms
,I/ActivityManager(  906): Resuming delayed broadcast
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 20103ms
,W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 30103ms
,D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }

```
