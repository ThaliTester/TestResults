#### Test 561510933390750_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  910):    returned true
I/SensorManager(  910): mEventCount = 1200
E/cutils-trace( 4448): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4448): ====startRecUseTime====
D/htc.customization.log.level( 4448):  is 
W/CustomizationLogLevel( 4448): Level value is invalid, use default level 2
D/CustomizationManager( 4448):  Read ACC file spent 0.050 (s)
D/CIDMapFileReader( 4448): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4448): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4448): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4448): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4448): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4448): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4448): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4448): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4448): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4448): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4448): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4448): Parsing tag category name = system
I/CustomizationCIDLoader( 4448): Parsing tag category name = application
I/CustomizationCIDLoader( 4448): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4448): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4448): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4448): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4448): Parsing tag category name = Settings
D/CustomizationManager( 4448):  Read CID file spent 0.089 (s)
D/CustomizationManager( 4448):  All configurations done spent 0.089 (s)
W/HtcNativeFlag( 4448): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4448): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4448): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4448): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
W/CpuWake (  910): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  910): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  910): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  910): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  910): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  910): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  910): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4448
D/PMS     (  910): acquireHCC(4297e660): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 910 1000 null
D/PMS     (  910): acquireHCC(42899628): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 910 1000 null
W/asset   (  910): Copying FileAsset 0x6c644eb8 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  910): @test_code: getHtcIntentFlag: 0 obj: 1116560480
I/FeedHostManager( 1272): [onPause]
I/FeedProviderManager( 1272): onPause
I/FeedHostManager( 1272): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41fff500
I/SocialFeedProvider( 1272): +onPause
I/SocialFeedProvider( 1272): -onPause
D/PMS     (  910): acquireWL(4235a508): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 910 1000 null
I/ActivityManager(  910): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4459 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1272): [trimMemory] 20
W/asset   ( 4459): Copying FileAsset 0x5c6fccf0 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4459): Binding Chromium to main looper Looper (main, tid 1) {41e7aea0}
I/LibraryLoader( 4459): Expected native library version number "",actual native library version number ""
I/chromium( 4459): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4459): Initializing chromium process, renderers=0
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  910): java.lang.Throwable: stack dump
D/BluetoothManagerService(  910): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42ed7460:true
W/System.err(  910): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  910): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  910): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  910): 	at android.os.Binder.execTransact(Binder.java:412)
D/PMS     (  910): acquireWL(41edcb30): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  910): acquireWL(43380c70): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  910): releaseWL(43380c70): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
W/System.err(  910): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4459): 1105792512: getState(). Returning 12
I/Adreno-EGL( 4459): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4459): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4459): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4459): Local Branch: 
I/Adreno-EGL( 4459): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4459): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4459):                  aa63bbd948f41d15fc72f585e
W/chromium( 4459): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4459): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4459): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4459): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4459): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4459): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4459): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4459): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4459): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4459): CordovaWebView is running on device made by: HTC
,W/AwContents( 4459): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  910): Disable input method client, pid=1272
W/ResourceType( 4459): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4459): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41ec24b0, mServedView=org.apache.cordova.engine.SystemWebView{41e88118 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1209): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1209): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  910): Enable input method client, pid=4459
W/AwContents( 4459): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  910): Displayed com.test.thalitest/.MainActivity: +276ms
,D/PMS     (  910): releaseWL(4235a508): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4459): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4459): JniHelper::setJavaVM(0x41a3a010), pthread_self() = 1662999320
,D/JX-Cordova( 4459): jxcore cordova android initializing
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/dalvikvm-heap( 4459): Grow heap (frag case) to 12.001MB for 42652-byte allocation
,I/dalvikvm-heap( 4459): Grow heap (frag case) to 12.079MB for 95956-byte allocation
,I/dalvikvm-heap( 4459): Grow heap (frag case) to 12.159MB for 143930-byte allocation
,I/dalvikvm-heap( 4459): Grow heap (frag case) to 12.273MB for 215890-byte allocation
,I/dalvikvm-heap( 4459): Grow heap (frag case) to 12.449MB for 323830-byte allocation
,I/dalvikvm-heap( 4459): Grow heap (frag case) to 12.720MB for 485740-byte allocation
,I/dalvikvm-heap( 4459): Grow heap (frag case) to 13.696MB for 1092904-byte allocation
,I/dalvikvm-heap( 4459): Grow heap (frag case) to 14.640MB for 1639352-byte allocation
,I/dalvikvm-heap( 4459): Grow heap (frag case) to 15.885MB for 2459024-byte allocation
,D/WifiDataStallTracker(  910): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  910): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  910): updateDataStallInfo: mDataStallTxRxSum={txSum=133 rxSum=119} preTxRxSum={txSum=133 rxSum=119}
D/WifiDataStallTracker(  910): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  910): onDataStallAlarm: tag=20882 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  910): startDataStallAlarm: tag=20883 delay=15s
D/PMS     (  910): acquireWL(42816090): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
V/AlarmManager(  910): sending alarm PendingIntent{42a061a0: PendingIntentRecord{42743380 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=104655, Int=0
D/PMS     (  910): releaseWL(42816090): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/dalvikvm-heap( 4459): Grow heap (frag case) to 18.073MB for 3688532-byte allocation
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/CpuWake (  910): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  910): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  910): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  910): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  910): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  910): <<release mCpuPerf_Freq wakelock
D/PMS     (  910): releaseHCC(4297e660): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  910): releaseHCC(42899628): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4459): Initializing JXcore engine
,W/jxcore-log( 4459): JXcore engine is ready
,W/jxcore-log( 4459): Starting JXcore engine
,W/jxcore-log( 4459): Platform android
W/jxcore-log( 4459): 
,W/jxcore-log( 4459): Process ARCH arm
W/jxcore-log( 4459): 
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1184): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
,I/PMS     (  910): Going to sleep due to screen timeout...
,I/SensorManager(  910): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@425ba370
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  910): disable: get sensor name = CM36282 Light sensor
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 2
W/SensorService(  910): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@425ba370, eanble = 0, strlen(mName) = 59
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  910): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41f03260
W/SensorService(  910): Listener[1] = com.htc.smartdim.sensor_eye@42760708
W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  910): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  910): Couldn't get kernel wake lock stats
V/LightsService(  910): setLight #2: color=#0
D/qdlights(  910): set_light_buttons_func: on=0 brightness=0
V/LightsService(  910): setLight #0: color=#0
,D/WirelessDisplayService(  910): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  910): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  910): mWirelessDisplayManager is null
,D/SurfaceControl(  910): Excessive delay in blankDisplay() while turning screen off: 317ms
D/PMS     (  910): nativeSetInteractive:false
D/PMS     (  910): nativeSetInteractive:false done
D/PMS     (  910): nativeSetAutoSuspend:true
D/PMS     (  910): nativeSetAutoSuspend:true done
D/HABCtrl (  910): TPE algorithm. remove timeout.
D/PMS     (  910): OOBE c monitor 11
,I/InputManager(  910): Cancel all due to getting PMS screen off broadcast,
I/jxcore-log( 4459): JXcore Cordova bridge is ready!
I/jxcore-log( 4459): 
W/jxcore-log( 4459): JXcore engine is started
,I/chromium( 4459): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/IntentController( 1117): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  910): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@4356f620)
I/InputMethodManagerService(  910): screenObserver, isScreenOn=false
D/PMN     (  910): wakingUp
,I/InputMethodManagerService(  910): Disable input method client, pid=4459
,V/KeyguardServiceDelegate(  910): **** SHOWN CALLED ****
D/NfcService( 1258): ScreenObserver: OFF
D/NfcService( 1258): applyRouting - 0
W/ResourceType( 4459): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4459): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41e88118 VFEDH.C. .F....ID 0,0-720,1134 #64}
D/WirelessDisplayService(  910): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  910): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  910): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/NfcService( 1258): applyRouting -2
,D/WifiDataStallTracker(  910): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  910): startDataStallAlarm: tag=20884 delay=15s
I/WindowManager(  910): No lock screen! windowToken=null
D/PMN     (  910): onScreenOn
D/PMS     (  910): acquireWL(43574870): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/AlarmManager(  910): ACTION_SCREEN_ON
I/BatteryService(  910): n_update end
I/AlarmManager(  910): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  910): [AlarmQueuing] done recovering
I/AlarmManager(  910): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  910): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  910): acquireWL(44151198): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1258 1027 null
D/PMS     (  910): releaseWL(44151198): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMS     (  910): releaseWL(43574870): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/MtpService( 2379): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/NfcService( 1258): applyRouting - 0
D/MtpService( 2379): [MTP][onReceive]-
,D/NfcService( 1258): applyRouting -2
D/PMS     (  910): acquireWL(445fed10): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1258 1027 null
D/PMS     (  910): releaseWL(445fed10): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024692
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024830
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024904
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024918
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024936
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024947
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026329
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026341
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029154
D/PMS     (  910): releaseWL(41edcb30): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/ClockThread( 1117): stop update clock
I/ActivityManager(  910): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4509 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/WirelessDisplayService(  910): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  910): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  910): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/WifiNative-wlan0(  910): doBoolean: SET_SCREEN_ON 1
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1184): SET_SCREEN_ON:On
I/wpa_supplicant( 1184): htc_wext_set_keepalive +
I/wpa_supplicant( 1184): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1184): getPrivFuncNum +	
I/wpa_supplicant( 1184): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1184): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1184): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1184): htc_wext_set_TX_TRACKING (1)+
D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
I/wpa_supplicant( 1184): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  910):    returned true
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1184): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true,
,I/jxcore-log( 4459): Toggling radios to true
I/jxcore-log( 4459): 
,D/WifiStateMachine(  910): [ScoreAP] + current TXpacket:169, mTXpacketCount:169, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  910): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/BluetoothAdapter( 4459): enable(): BT is already enabled..!
,D/WifiManager( 4459): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
D/WifiService(  910): setWifiEnabled: true pid=4459, uid=10389
E/WifiService(  910): Invoking mWifiStateMachine.setWifiEnabled
,W/HtcDLNAServiceManager(  910): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  910): Settings:Agentname: wifi_on
,W/HtcDLNAServiceManager(  910): Settings:Agentvalue: 2
W/Settings:Agent(  910): >> traceCallingStack()
,V/SRS_Proc(  371): ParamSet string: screen_state=on
W/Settings:Agent(  910): Process.myPid(): 910
W/Settings:Agent(  910): Process.myTid(): 1346
W/Settings:Agent(  910): Process.myUid(): 1000
W/Settings:Agent(  910): 
W/Settings:Agent(  910): 
,W/System.err(  910): java.lang.Throwable: stack dump
W/System.err(  910): 	,at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  910): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  910): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
I/WifiService(  910): isSprintWifiRestricted(): false
D/WifiService(  910): New client listening to asynchronous messages
D/WIFI_ICON( 1117): WifiActivity: 0
I/WifiService(  910): isMdmWifiRestricted(): false
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiSettingsStore(  910): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
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
W/Settings:Agent(  910): << traceCallingStack(): 5(ms)
D/WirelessDisplayService(  910): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/WifiManager( 4459): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  910): doBoolean: DISCONNECT
D/WifiManager( 4459): reconnect: Base Package Name=com.test.thalitest, uid=10389
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): TDLS: Tear down peers
I/wpa_supplicant( 1184): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4459): Radios toggled
I/jxcore-log( 4459): 
,I/jxcore-log( 4459): My device name is: HTC-HTC Desire 820
I/jxcore-log( 4459): 
D/NetworkPolicy(  910): updateScreenOn: false
,W/ContextImpl( 4509): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  910): acquireWL(441b1408): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4509 1000 null
D/SmartSyncUtils( 4509): isEpsOn(), nState = 0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1184): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1184): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1184): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  910): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1184): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1184): send_and_recv error -67 - cmd 12
D/HTCRequest(  910): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1184): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  910): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  910): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1184): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1184): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb7ec5bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1184):    addr=c0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1184): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1184): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1184): netlink: Operstate: linkmode=-1, operstate=5
D/HTCRequest(  910): WifiMonitor:getFreqFromEventString() 2412
I/wpa_supplicant( 1184): htc_wext_set_TX_TRACKING (0)+
D/WifiMonitor(  910): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
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
D/wpa_supplicant( 1184): nl80211: Set suppl,icant port unauthorized for 00:00:00:00:00:00
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
D/wpa_supplicant( 1184): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1184): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1184): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1184): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1184): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1184): nl80211: Event message available
D/wpa_supplicant( 1184): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1184): nl80211: Ignore disconnect event triggered during reassociation
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  910):    returned true
D/WifiPerfLock(  910): release()
D/WifiStateMachine(  910): PerfLock released for exiting ConnectedState
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/Tethering(  910): [isWifi] getHotspotEnabled: false
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1184): Power_Mode_Type mode = 0
I/wpa_supplicant( 1184): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
D/ConnectivityService(  910): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  910): acquireWL(43575dc0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 910 1000 null
D/WifiP2pService(  910): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  910):    returned true
D/DhcpStateMachine(  910): [RunningState] Stop DHCP
D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/WifiP2pService(  910): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024692
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024830
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024904
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024918
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024936
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024947
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026329
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026341
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029154
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  910): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/WifiNative-wlan0(  910): doBoolean: RECONNECT
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): Fast associate: Old scan results
I/wpa_supplicant( 1184): wpa_supplicant_scan enter
I/wpa_supplicant( 1184): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1184): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1184): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  910):    returned true
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1184): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1184): nl80211: Event message available
D/wpa_supplicant( 1184): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiStateMachine(  910): Enter handleNetworkDisconnect
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  910): stopDataStallAlarm: current tag=20884 mDataStallAlarmIntent=PendingIntent{4351cf80: PendingIntentRecord{42743380 android broadcastIntent}}
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/SmartSyncUtils( 4509): getMobilePolicyEnabled, result = true
D/PMS     (  910): releaseWL(441b1408): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1184): Power_Mode_Type mode = 0
I/wpa_supplicant( 1184): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  910):    returned true
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024692
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024830
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024904
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024918
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024936
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024947
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026329
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026341
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029154
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  910): Provision feature enable=false
D/ConnectivityService(  910): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WifiP2pService(  910): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/WifiP2pService(  910): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 3816): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  910): Exit handleNetworkDisconnect
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WISPrService( 3816): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiService(  910): New client listening to asynchronous messages
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/UsbnetStateTracker(  910): isAvailable+-
D/UsbnetStateTracker(  910): reconnect
,D/UsbnetStateTracker(  910): isAvailable+-
,D/AutoSetting( 1328): receiver - intent: android.intent.action.USER_PRESENT
,D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  910): default: reconnect()
D/MDST    (  910): default: setTeardownRequested(false)
D/MDST    (  910): default: setEnableApn apnType =default , enable=true
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WISPrService( 3816): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 3816): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  910): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  910): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  910): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
,D/AutoSetting( 1328): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/TetherSettings( 3816): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3816): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3816): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3816): Cust_ConnectToPC   : spcsc>false
D/        ( 3816): Cust_ConnectToPC   : IPT>true
D/        ( 3816): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3816): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3816): hasRemovableStorageSlot: true
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/SmartNS_Utility( 3816): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/SmartNS_NSReceiver( 3816): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,V/NativeCrypto( 1366): Read error: ssl=0x662697b0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1366): SSL shutdown failed: ssl=0x662697b0: I/O error during system call, Broken pipe
I/PSReceiver( 3816): onReceive:android.intent.action.USER_PRESENT
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:0
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/PMS     (  910): acquireWL(429876e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(429876e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '33 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 33 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): handleConnectivityChange: resetting
D/ConnectivityService(  910): resetConnections(wlan0, 3)
D/PMS     (  910): acquireWL(445a8c60): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(42a07bd0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1366 10029 WorkSource{10029 com.google.android.gms}
W/ContextImpl( 3816): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/libc    (  364): [NET] entry_id:3   entry:0xb776e220  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb776dfd8  removed 
D/libc    (  364): [NET] entry_id:5   entry:0xb776e2f8  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb776e428  removed 
D/libc    (  364): [NET] entry_id:6   entry:0xb776e860  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb776e0e8  removed 
D/libc    (  364): [NET] entry_id:7   entry:0xb776e738  removed 
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
I/SmartNS_PSService( 3816): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3816): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3816):  defaultType:0
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024692
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024830
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024904
D/ConnectivityService(  910): flush DNS cache for net 1(wlan0)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024918
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024936
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024947
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026329
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026341
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029154
D/Nat464Xlat(  910): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  910): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1366/10029)
D/ConnectivityService(  910): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  910): reportInetCondition for net -1, percentage: 0 by  (1366/10029)
D/WirelessDisplayService(  910): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  910): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1748): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1748): onScreenOn: 1453032796877
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1748): onScreenOn: 1453032796877
D/PMS     (  910): releaseWL(445a8c60): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(439ae288): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1366/10029)
D/PMS     (  910): releaseWL(42a07bd0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
,D/ConnectivityService(  910): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/WifiStateMachine(  910): startScan Pid: 910 Uid 1000
D/WifiNative-wlan0(  910): doBoolean: SCAN
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1184): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  910):    returned false
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
D/BatSI   (  910): WIFI scan started for: 450a0300 uid:1000
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1366/10029)
D/PMS     (  910): releaseWL(439ae288): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1366/10029)
,D/Process (  910): killProcessQuiet, pid=3873
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/SensorManager(  910): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41f03260
,W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
,I/ActivityManager(  910): Killing 3873:com.google.android.music:main/u0a154 (adj 15): empty #17
W/SensorService(  910): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 2
W/SensorService(  910): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41f03260, eanble = 0, strlen(mName) = 91
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  910): Listener[0] = com.htc.smartdim.sensor_eye@42760708
,W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  910): goingToSleep
D/ConnectivityService(  910): mActiveDefaultNetwork: -1
D/ConnectivityService(  910): handleInetConditionChange: no active default network - ignore
D/PMS     (  910): acquireWL(4357a860): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 910 1000 null
,D/AlarmManager(  910): ACTION_SCREEN_OFF
I/AlarmManager(  910): [AlarmQueuing] screen off now: 
I/AlarmManager(  910): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  910): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  910): stopDataStallAlarm: current tag=20885 mDataStallAlarmIntent=null
,D/WifiNative-wlan0(  910): doBoolean: SET pno 1
D/WifiNative-wlan0(  910): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1184): SET_SCREEN_ON:Off
I/wpa_supplicant( 1184): htc_wext_set_keepalive +
I/wpa_supplicant( 1184): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1184): getPrivFuncNum +	
I/wpa_supplicant( 1184): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1184): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1184): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 1184): get_ip_address source addr = 02000000
I/wpa_supplicant( 1184): htc_wext_set_keepalive gateway addr = 00000000
,I/wpa_supplicant( 1184): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  910):    returned true
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1184): CTRL_IFACE SET 'pno'='1'
I/AlarmManager(  910): [AlarmQueuing] wifi connection: true
,D/PMS     (  910): acquireWL(43a7f910): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 910 1000 null
,V/SRS_Proc(  371): ParamSet string: screen_state=off
D/NetworkPolicy(  910): updateScreenOn: false
,D/ContactMessageStore( 1239): start background delete task...
D/ContactMessageStore( 1239): size: 0 , 0
,D/ContactMessageStore( 1239): Background delete complete
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1184): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1184): nl80211: Event message available
D/wpa_supplicant( 1184): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1184): nl80211: Event message available
D/wpa_supplicant( 1184): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1184): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1184): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1184): nl80211: Survey data missing
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1184): Sorted scan results
I/wpa_supplicant( 1184): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-51
D/wpa_supplicant( 1184): BSS: last_scan_res_used=1/32 last_scan_full=0
D/wpa_supplicant( 1184): Add randomness: count=7 entropy=0
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1184): WPS: AP[0] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1184): wpa_supplicant_pick_network+
I/wpa_supplicant( 1184): Selecting BSS from priority group 1
I/wpa_supplicant( 1184): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1184): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1184): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1184):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1184):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-51
I/wpa_supplicant( 1184): Start print parameters
I/wpa_supplicant( 1184): wpa_s->wpa_state is 3
I/wpa_supplicant( 1184): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1184): isConcurrentMode() is 0
I/wpa_supplicant( 1184): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1184): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1184): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1184): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1184): wpa_s->reassociate is 1
I/wpa_supplicant( 1184): wpa_s->is_screen_on 0
I/wpa_supplicant( 1184): wpa_s->ifname wlan0
I/wpa_supplicant( 1184): End print parameters
I/wpa_supplicant( 1184): selected network = 1
D/wpa_supplicant( 1184): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb7ec74e8  current_ssid=0x0
D/wpa_supplicant( 1184): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1184): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1184): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1184): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1184): check if in concurrent case
,I/wpa_supplicant( 1184): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiNative-wlan0(  910):    returned true
D/wpa_supplicant( 1184): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1184): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1184): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1184): RSN: PMKSA cache search - network_ctx=0xb7ec74e8 try_opportunistic=0
D/wpa_supplicant( 1184): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1184): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1184): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1184): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1184): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1184): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1184): nl80211: Unsubscribe mgmt frames handle 0xb7ec6718 (mode change)
D/wpa_supplicant( 1184): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7ec6718
D/wpa_supplicant( 1184): nl80211: Register frame type=0xd0 nl_handle=0xb7ec6718
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1184): nl80211: Register frame type=0xd0 nl_handle=0xb7ec6718
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1184): nl80211: Register frame type=0xd0 nl_handle=0xb7ec6718
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1184): nl80211: Register frame type=0xd0 nl_handle=0xb7ec6718
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1184): nl80211: Register frame type=0xd0 nl_handle=0xb7ec6718
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1184): nl80211: Register frame type=0xd0 nl_handle=0xb7ec6718
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1184): nl80211: Register frame type=0xd0 nl_handle=0xb7ec6718
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1184): nl80211: Register frame type=0xd0 nl_handle=0xb7ec6718
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1184): nl80211: Register frame type=0xd0 nl_handle=0xb7ec6718
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1184): nl80211: Register frame type=0xd0 nl_handle=0xb7ec6718
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
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1184): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1184): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
,D/WifiNative-wlan0(  910): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: SET pno 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): CTRL_IFACE SET 'pno'='1'
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  910): doString: LIST_DONGLES
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024692
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024830
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024904
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024918
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024936
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024947
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026329
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026341
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029154
D/PMS     (  910): releaseWL(43a7f910): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
W/ContextImpl( 4509): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  910): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1184): reply (523) for get BSS: id=0
I/wpa_supplicant( 1184): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1184): freq=5220
I/wpa_supplicant( 1184): level=-47
I/wpa_supplicant( 1184): tsf=0000000023080574
I/wpa_supplicant( 1184): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1184): ssid=NG7005g
I/wpa_supplicant( 1184): ====
I/wpa_supplicant( 1184): id=1
I/wpa_supplicant( 1184): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1184): freq=2412
I/wpa_supplicant( 1184): level=-51
I/wpa_supplicant( 1184): tsf=0000000106507651
I/wpa_supplicant( 1184): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1184): ssid=NG700
I/wpa_supplicant( 1184): ====
I/wpa_supplicant( 1184): id=2
I/wpa_supplicant( 1184): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1184): freq=2427
I/wpa_supplicant( 1184): level=-79
I/wpa_supplicant( 1184): tsf=0000000023080590
I/wpa_supplicant( 1184): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1184): ssid=Gonzos
I/wpa_supplicant( 1184): ====
I/wpa_supplicant( 1184): id=3
I/wpa_supplicant( 1184): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1184): freq=2437
I/wpa_supplicant( 1184): level=-92
I/wpa_supplicant( 1184): tsf=0000000023080594
I/wpa_supplicant( 1184): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1184): ssid=UPC4688432
I/wpa_supplicant( 1184): ####
,D/WirelessDisplayService(  910): getDiscoveryDongleList
,D/SmartSyncUtils( 4509): isEpsOn(), nState = 0
D/WifiStateMachine(  910): == begin of scan result ==
,D/WifiStateMachine(  910): == (4) end of scan result ==
D/SmartSyncUtils( 4509): getMobilePolicyEnabled, result = true
,D/WifiManager( 1222): getScanResults enter 
D/SmartSyncUtils( 4509): isEpsOn(), nState = 0
D/WifiStateMachine(  910): == begin of scan result ==
D/WirelessDisplayService(  910): getDiscoveryDongleList
,D/WifiStateMachine(  910): == (4) end of scan result ==
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/WifiStateMachine(  910): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 23080574, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 2412, timestamp: 106507651, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 23080590, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -92, frequency: 2437, timestamp: 23080594, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): add 4 to mScanResults
D/BatSI   (  910): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  910): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
I/SensorManager(  910): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42760708
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  910): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 1
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42760708, eanble = 0, strlen(mName) = 36
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  910): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 0
W/SensorService(  910): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42760708, eanble = 0, strlen(mName) = 36
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  910): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42760708
D/WifiService(  910): New client listening to asynchronous messages
W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
E/ActivityThread(  910): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42760c50 that was originally registered here. Are you missing a call to unregisterReceiver()?
,E/ActivityThread(  910): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42760c50 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
E/ActivityThread(  910): 	,at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  910): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  910): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  910): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  910): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  910): 	at dalvik.system.NativeStart.main(Native Method)
I/ActivityManager(  910): Recipient 3873
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  910): Client com.google.android.music (pid 3873): Died!
,D/AutoSetting( 1328): service - mHandler: cancel location update
,D/AutoSetting( 1328): service -           changes count: 0
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] getTotalRam: 1873 Mb
D/PMS     (  910): acquireWL(429601f0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1748): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1748): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1748): disableBatteryAlarm
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1748): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1748): onScreenOff
D/PMS     (  910): releaseWL(429601f0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(4361c980): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(4361c980): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
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
D/wpa_supplicant( 1184): Add randomness: count=8 entropy=1
I/wpa_supplicant( 1184): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1184): TDLS: Remove peers on association
D/wpa_supplicant( 1184): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1184): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1184): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
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
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
I/wpa_supplicant( 1184): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1184): Get randomness: len=32 entropy=2
D/WifiMonitor(  910): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  910): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
D/HTCRequest(  910): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  910): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  910): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  910): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  910): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  910): Enter handleAssociatedWithEvent
D/WifiStateMachine(  910): Associated
D/HTCRequest(  910): WifiMonitor:handleSupplican,tStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  910): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  910): Exit handleAssociatedWithEvent
D/WifiStateMachine(  910): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/WifiStateMachine(  910): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/Tethering(  910): interfaceLinkStateChanged wlan0, true
D/Tethering(  910): interfaceStatusChanged wlan0, true
D/WifiApDatabaseHandler(  910): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  910): This record is existed, only update it...
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  910): updateConnectedAP...
I/wpa_supplicant( 1184): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb7ec69f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1184):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1184): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1184): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f61b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1184):    broadcast key
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1184): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1184): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1184): State: GROUP_HANDSHAKE -> COMPLETED
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 1184): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1184): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 1184): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1184): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1184): set send_ind_to_ndc = 0
I/wpa_supplicant( 1184): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1184): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1184): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1184): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1184): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1184): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1184): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1184): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1184): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1184): EAPOL authentication completed successfully
I/wpa_supplicant( 1184): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1184): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1184): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1184): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  910): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  910): interfaceLinkStateChanged wlan0, true
D/Tethering(  910): interfaceStatusChanged wlan0, true
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/WifiStateMachine(  910): fetchFrequency(), freq = 2412
D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  910): WifiApDatabaseHandler, WiFi AP database Inserting ..,
D/WifiApDatabaseHandler(  910): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  910): This record is existed, only update it...
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiApDatabaseHandler(  910): updateConnectedAP...
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  910): Provision feature enable=false
D/ConnectivityService(  910): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WISPrService( 3816): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 3816): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiNative-wlan0(  910): doBoolean: SET pno 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1184): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1184): nl80211: Event message available
D/wpa_supplicant( 1184): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/DhcpStateMachine(  910): [StoppedState] Start DHCP
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1184): Power_Mode_Type mode = 1
I/wpa_supplicant( 1184): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  910):    returned null
E/WifiStateMachine(  910): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/WifiNative-wlan0(  910):    returned null
D/wpa_supplicant( 1184): nl80211: Event message available
D/wpa_supplicant( 1184): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1184): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/WifiStateMachine(  910): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  910): acquireWL(4362c098): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 910 1000 null
D/WifiStateMachine(  910): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  910): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42991660 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42991660 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:0
,W/ActivityManager(  910): Activity pause timeout for ActivityRecord{427570f0 u0 com.test.thalitest/.MainActivity t2}
,V/Tethering(  910): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  910): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  910): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4552 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
,D/GpsLocationProvider(  910): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  910): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTING DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  910): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  910): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  910): acquireWL(431810c8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/PMS     (  910): releaseWL(431810c8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1572/10029)
D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
D/CaptivePortalTracker(  910): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/CaptivePortalTracker(  910): NoActiveNetworkState
D/Tethering(  910): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  910): bSetPropertyMultiRAB:false
,D/Tethering(  910): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  910): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  910): ipv4Default null
I/Tethering(  910): No IPv4 upstream interface, giving up.
,D/Tethering(  910): TetherMasterSM: InitialState processMessage what=3
,I/ConnectivityHelper( 1272): [onReceive] WIFI(1): CONNECTING
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.launcher (1272/10076)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (4310/10100)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (4310/10100)
,D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024692
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024830
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024904
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024918
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024936
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024947
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026329
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026341
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029154
,I/MusicStore( 4552): Database version: 95
,W/ContextImpl( 4552): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4552): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4552): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4552): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4552): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4552, uid=10154, userID:0
,D/WifiDisplayAdapter(  910): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  910):     Client/Owner: Client
D/WifiDisplayAdapter(  910):     GroupId: 
D/WifiDisplayAdapter(  910):     Passphrase: 
D/WifiDisplayAdapter(  910):     SessionId: 0
D/WifiDisplayAdapter(  910):     IP Address: }
,D/wpa_supplicant( 1184): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1184): EAPOL: disable timer tick
D/MediaRouterService(  910): Client com.google.android.music (pid 4552): Registered
,D/WifiDisplayAdapter(  910): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  910):     Client/Owner: Client
D/WifiDisplayAdapter(  910):     GroupId: 
D/WifiDisplayAdapter(  910):     Passphrase: 
D/WifiDisplayAdapter(  910):     SessionId: 0
D/WifiDisplayAdapter(  910):     IP Address: }
I/MediaRouter( 4552): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.music (4552/10154)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (2379/10021)
,I/ActivityManager(  910): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4573 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4552): getSelectedRoute
,D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.google.android.music (4552/10154)
I/NetworkMonitor( 4552): type=WIFI subType= reason=null isConnected=false
,D/ACRA    ( 4573): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4573): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4573): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4552, uid=10154, userID:0
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,I/ActivityManager(  910): Killing 3851:com.htc.mediamanager/u0a34 (adj 15): empty #17
D/Process (  910): killProcessQuiet, pid=3851
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  910): acquireWL(4472bb80): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/PMS     (  910): releaseWL(4472bb80): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/SystemClassLoaderAdder( 4573): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4573): Preparing secondary program dexes.
V/DexLibLoader( 4573): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4573): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4573): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4573): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4573): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4573): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4573): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4573): Dex already copied
D/OdexVerifier( 4573): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4573): Creating class loader
V/DexLibLoader( 4573): Finished creating class loader
V/DexLibLoader( 4573): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4573): Dex already copied
D/OdexVerifier( 4573): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4573): Creating class loader
I/ActivityManager(  910): Recipient 3851
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
V/DexLibLoader( 4573): Finished creating class loader
V/DexLibLoader( 4573): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4573): Dex already copied
D/OdexVerifier( 4573): Odex verification is skipped. OS version not supported.
V/DexLibLoader( 4573): Creating class loader
V/DexLibLoader( 4573): Finished creating class loader
V/DexLibLoader( 4573): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4573): Dex already copied
D/OdexVerifier( 4573): Odex verification is skipped. OS version not supported.
V/DexLibLoader( 4573): Creating class loader
V/DexLibLoader( 4573): Finished creating class loader
V/DexLibLoader( 4573): Verifying classes from secondary dexes.
D/DexLibLoader( 4573): DexLibLoader.ensureDexLoaded took 18 ms
,D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,W/dalvikvm( 4573): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4573): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4573): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4573): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4573): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4573): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4573): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  910): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1184): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1184): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  910):    returned true
,D/WifiStateMachine(  910): handlePostDhcpSetup release wake lock during DHCP
D/WifiP2pService(  910): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): releaseWL(4362c098): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [3][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): gateway: /192.168.1.1
D/WifiNative-wlan0(  910): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
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
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  910): VerifyingLinkState enter
D/WifiStateMachine(  910): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  910): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  910): VerifyingLinkState: enableIpv6
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED -1 -> 3
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -51, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,V/NetworkPolicy(  910): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiWatchdogStateMachine(  910): WAN detection
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  910): Provision feature enable=false
D/ConnectivityService(  910): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  910): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  910): default: teardown()
D/MDST    (  910): default: setTeardownRequested(true)
D/MDST    (  910): default: setEnableApn apnType =default , enable=false
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/MDST    (  910): default: setTeardownRequested(true)
,D/ConnectivityService(  910): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/WISPrService( 3816): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  910): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  910): syncGetConfiguredNetworks
E/ConnectivityService(  910): Unexpected mtu value: android.net.wifi.WifiStateTracker@428071f0
D/ConnectivityService(  910): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  910): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  910): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  910): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  910): handleConnectivityChange: resetting
D/Nat464Xlat(  910): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  910): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  910): sendGeneralBroadcastDelayed, restrictEnable=false
D/PMS     (  910): acquireWL(43908670): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
D/ConnectivityService(  910): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  910): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
D/WirelessDisplayService(  910): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  910):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,I/QuickSettingWifi( 1117): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  910): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/PMS     (  910): releaseWL(43908670): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,W/dalvikvm( 4573): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4573): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4573): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4573): Verify
,D/WifiService(  910): New client listening to asynchronous messages
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4573/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4573): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4573): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4573): Grow heap (frag case) to 9.518MB for 73240-byte allocation
,D/Process (  910): killProcessQuiet, pid=4244
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  910): Killing 4244:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4244
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1328): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/WifiService(  910): Client connection lost with reason: 4
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1328/10055)
,D/AutoSetting( 1328): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1328): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 1328): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1328): service - onStartCommand() check timezone in 30000
I/ActivityManager(  910): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4624 uid=10079 gids={50079, 3003, 5012}
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1328/10055)
,D/MobileConnectivityChangeReceiver( 4624): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4624): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4624): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4624): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,W/fb4a(:<default>):UserScope( 4573): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4573): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4573): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
I/ActivityManager(  910): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4638 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4624/10079)
,D/Process (  910): killProcessQuiet, pid=4145
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  910): Killing 4145:com.google.android.talk/u0a111 (adj 15): empty #17
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4624/10079)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4624/10079)
,D/PMS     (  910): acquireWL(43e91d48): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43bb8528): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43e91d48): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I/CheckinService( 2179): Checkin interval check for package: unspecified last checkin: 1453032748957 min interval config: 0 actual interval: 50841
,I/CheckinService( 2179): Checking schedule, now: 1453032799804 next: 1453032778927
,I/CheckinService( 2179): active receiver: enabled
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2179, uid=10029, userID:0
,I/CheckinService( 2179): Preparing to send checkin request
,I/EventLogService( 2179): Accumulating logs since 1453032744209
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
,I/ActivityManager(  910): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4653 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,I/ActivityManager(  910): Killing 4277:com.google.android.partnersetup/u0a32 (adj 15): empty #17
D/Process (  910): killProcessQuiet, pid=4277
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Recipient 4145
,I/ActivityManager(  910): Recipient 4277
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/CheckinRequestBuilder( 2179): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  910): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2179): Failed to find provider info for com.google.android.wearable.settings
,I/dalvikvm-heap( 4573): Grow heap (frag case) to 9.962MB for 84664-byte allocation
E/dalvikvm( 4573): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4573): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4653): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4653): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4653): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4653): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
I/dalvikvm-heap( 4573): Grow heap (frag case) to 9.978MB for 28144-byte allocation
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/dalvikvm( 4573): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 4573): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4573): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4573): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4573): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4573): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4573): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4573): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4573): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4573): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4573): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4573): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4573): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4573): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4573): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4573): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,W/ContextImpl( 4653): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4573): Grow heap (frag case) to 10.022MB for 39954-byte allocation
,D/ConnectivityService(  910): getNetworkInfo networkType=9 called by com.google.android.gms (2179/10029)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm-heap( 4573): Grow heap (frag case) to 10.098MB for 79892-byte allocation
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4653/10151)
,V/WebViewChromiumFactoryProvider( 4653): Binding Chromium to main looper Looper (main, tid 1) {41e812c8}
,I/LibraryLoader( 4653): Expected native library version number "",actual native library version number ""
,I/chromium( 4653): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4653): Initializing chromium process, renderers=0
,D/PMS     (  910): releaseWL(43575dc0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  910): NetTransition Wakelock for ConnectedState released by timeout
,I/jxcore-log( 4459): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 4459): 
,E/AudioManagerAndroid( 4653): BLUETOOTH permission is missing!
D/PMS     (  910): acquireWL(433e01b0): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  910): releaseWL(433e01b0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/PMS     (  910): acquireWL(436a9408): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
I/jxcore-log( 4459): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 4459): 
I/Adreno-EGL( 4653): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4653): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4653): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4653): Local Branch: 
I/Adreno-EGL( 4653): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4653): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4653):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  910): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/ActivityManager(  910): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4683 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/AlarmManager(  910): [AlarmQueuing] connectivity wifi: true
,V/Tethering(  910): bSetPropertyMultiRAB:false
,D/Tethering(  910): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/Tethering(  910): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  910): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
,I/Tethering(  910): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  910): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  910): Found interface wlan0
D/Tethering(  910): TetherMasterSM: InitialState processMessage what=3
,D/CaptivePortalTracker(  910): NoActiveNetworkState
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/PMS     (  910): acquireWL(428b5070): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
,D/AccTypeManager( 1347): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,I/ConnectivityHelper( 1272): [onReceive] WIFI(1): CONNECTED
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.musicenhancer (3915/10053)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.launcher (1272/10076)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (4310/10100)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(42739758): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024692
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024830
D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,I/NetworkMonitor( 4552): type=WIFI subType= reason=null isConnected=true
D/GpsLocationProvider(  910): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  910): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  910): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  910): ignore wifi update if we are not in OPENING or CLOSING
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
I/jxcore-log( 4459): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 4459): 
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024904
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024918
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024936
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024947
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026329
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026341
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029154
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1572/10029)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.google.android.music (4552/10154)
D/PMS     (  910): releaseWL(42739758): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  910): releaseWL(428b5070): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
I/NSApplication( 4653): Starting up...
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1572/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4624/10079)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (4310/10100)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4653/10151)
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,I/jxcore-log( 4459): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 4459): 
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4653/10151)
W/AccTypeManager( 1347): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1347): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,W/dalvikvm( 4683): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 4683): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4683): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4683): install
,I/MultiDex( 4683): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/ExternalAccountType( 1347): Unsupported attribute readOnly
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (4080/10160)
,I/MultiDex( 4683): loading existing secondary dex files
,I/MultiDex( 4683): load found 3 secondary dex files
,D/Process (  910): killProcessQuiet, pid=4310
,I/MultiDex( 4683): install done
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (4080/10160)
,I/ActivityManager(  910): Killing 4310:com.google.android.apps.docs/u0a100 (adj 15): empty #17
I/dalvikvm-heap( 4573): Grow heap (frag case) to 10.284MB for 75760-byte allocation
,I/jxcore-log( 4459): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 4459): 
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,I/jxcore-log( 4459): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 4459): 
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4573/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42b77ce8 u0 ReceiverList{42a855d0 4573 com.facebook.katana/10027/u0 remote:4423f000}}
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,W/dalvikvm( 4683): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4683): VFY: unable to resolve instance field 36
,W/dalvikvm( 4683): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42b77ce8 u0 ReceiverList{42a855d0 4573 com.facebook.katana/10027/u0 remote:4423f000}}
W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{44288e60 u0 ReceiverList{44288e20 4573 com.facebook.katana/10027/u0 remote:43b69b70}}
,V/JNIHelp ( 4683): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1366/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1366/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (2379/10021)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024692
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024830
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024904
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024918
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024936
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024947
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026329
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026341
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029154
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4573/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4573/10027)
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4573/10027)
,I/ActivityManager(  910): Recipient 4310
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  910): acquireWL(4338d840): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1328): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4624): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4624): onReceive CONNECTIVITY_CHANGE networkType=1
D/PMS     (  910): releaseWL(4338d840): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1328/10055)
D/AutoSetting( 1328): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1328): service - onStartCommand() screen is off, don't request location
,D/AutoSetting( 1328): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1328): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1328/10055)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4653/10151)
I/ProviderInstaller( 4683): Installed default security provider GmsCore_OpenSSL
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (4080/10160)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (4080/10160)
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/dalvikvm( 4683): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
D/PMS     (  910): acquireWL(446a7818): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/dalvikvm( 4683): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,W/ContextImpl( 4573): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,I/CheckinService( 2179): Checkin interval check for package: unspecified last checkin: 1453032748957 min interval config: 0 actual interval: 51343
D/PMS     (  910): releaseWL(446a7818): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/dalvikvm-heap( 4080): Grow heap (frag case) to 13.509MB for 1821008-byte allocation
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/dalvikvm( 4683): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4683): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4683): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4683): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/ContextImpl( 4573): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,W/dalvikvm( 4683): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4573): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2179, uid=10029, userID:0
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,I/WVCdm   (  371): Level3 Library Nov 20 2013 18:09:31
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
W/WVCdm   (  371): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
I/WVCdm   (  371): CdmEngine::OpenSession
I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1366/10029)
,D/NativeLibraryUtils( 4683): Install completed successfully. count=14 extracted=0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1366/10029)
,D/WearableService( 1222): callingUid 10029, callindPid: 1222
,D/LocationInitializer( 2179): Restart initialization of location
,D/AuthorizationBluetoothService( 1366): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1366): Proximity feature is not enabled.
,E/MDM     ( 1222): [115] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WVCdm   (  371): PrepareKeyRequest: nonce=1907791773
,W/GCoreFlp( 1222): No location to return for getLastLocation()
,W/FusedLocationProvider( 1222): location=null
D/PMS     (  910): acquireWL(43948740): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(43948740): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024692
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024830
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024904
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024918
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024936
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024947
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026329
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026341
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029154
,I/WVCdm   (  371): CdmEngine::CloseSession
,W/Settings( 4683): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (4683/10029)
,I/jxcore-log( 4459): Test app app.js loaded
I/jxcore-log( 4459): 
,D/PMS     (  910): releaseWL(4357a860): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/chromium( 4459): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/Adreno-EGL( 4683): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4683): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4683): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4683): Local Branch: 
I/Adreno-EGL( 4683): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4683): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4683):                  aa63bbd948f41d15fc72f585e
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  371): PrepareKeyRequest: nonce=665668739
,I/WVCdm   (  371): CdmEngine::CloseSession
,I/Adreno-EGL( 4683): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4683): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4683): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4683): Local Branch: 
I/Adreno-EGL( 4683): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4683): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4683):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4683): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4683): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4683): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4683): Local Branch: 
I/Adreno-EGL( 4683): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4683): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4683):                  aa63bbd948f41d15fc72f585e
,I/CheckinRequestBuilder( 2179): Classify the device as Phone.
,D/libc    ( 2179): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2179): [NET] getaddrinfo-,err=8
,D/libc    ( 2179): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    ( 2179): [NET] getaddrinfo-, 1
,D/libc    ( 2179): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =e0c2 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 271
D/libc    (  364): [NET]res_nsend:resplen=84
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2179): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2179): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2179): [NET] getaddrinfo-,err=8
,D/libc    ( 2179): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2179): [NET] getaddrinfo-,err=8
,D/libc    ( 2179): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2179): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2179): Sending checkin request (12195 bytes)
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-,err=8
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  910): [NET] getaddrinfo-, 1
,D/libc    (  910): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =cb1a +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  910): Find DNS Address www.htc.com/104.81.130.175
,I/CheckinRequestBuilder( 2179): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  910): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2179): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  910): getNetworkInfo networkType=9 called by com.google.android.gms (2179/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=22 [22][5][0]
,I/CheckinRequestBuilder( 2179): Classify the device as Phone.
,I/CheckinTask( 2179): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2179): Checking schedule, now: 1453032802364 next: 1453555739359
,I/CheckinService( 2179): active receiver: disabled
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2179, uid=10029, userID:0
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024692
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024830
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024904
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024918
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024936
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024947
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026329
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026341
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029154
,I/CheckinService( 2179): Checking schedule, now: 1453032802392 next: 1453555739359
,I/CheckinService( 2179): active receiver: disabled
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2179, uid=10029, userID:0
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024692
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024830
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024904
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024918
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024936
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024947
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026329
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026341
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029154
D/CheckinService( 2179): Recording last checkin time for package unspecified as 1453032802398
D/PMS     (  910): releaseWL(43bb8528): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2179/10029)
D/PMS     (  910): acquireWL(4423ebf8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1366 10029 WorkSource{10029 com.google.android.gms}
D/GCM     ( 1366): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    ( 1366): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1366): [NET] getaddrinfo-,err=8
D/libc    ( 1366): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1366): [NET] getaddrinfo-, 1
,D/libc    ( 1366): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =6616 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1366/10029)
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 270
D/libc    (  364): [NET]res_nsend:resplen=79
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1366): [NET] getaddrinfo_proxy-, success
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4573/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4573/10027)
,D/libc    ( 1366): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1366): [NET] getaddrinfo-,err=8
,W/fb4a(:<default>):UserScope( 4573): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4573): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4573/10027)
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=25 [4][1][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/libc    ( 1366): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1366): [NET] getaddrinfo-,err=8
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [2][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1366/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1366/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1366/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1366/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4573/10027)
,D/PMS     (  910): acquireWL(446ef020): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1366 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1366/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1366/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1366/10029)
,D/PMS     (  910): releaseWL(4423ebf8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1366/10029)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1366/10029)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  910): handleInetConditionChange: starting a change hold
,D/PMS     (  910): releaseWL(446ef020): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43b80928): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1366 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1366/10029)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1366/10029)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1366/10029)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1366/10029)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1366/10029)
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024692
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024830
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024904
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024918
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024936
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024947
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026329
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026341
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029154
,D/PMS     (  910): releaseWL(43b80928): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,E/fb4a(:<default>):LocalFbBroadcastManager( 4573): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4573/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4573/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4573/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4573/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4573/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4573/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4573/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4573/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4573/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4573/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4573/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4573/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4573/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4573/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4573/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4573/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4573/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4573/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4573/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4573/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4573/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4573/10027)
,D/PMS     (  910): releaseWL(436a9408): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/PMS     (  910): acquireWL(4419a8e0): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4552 10154 null
,W/ContextImpl( 4552): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4552, uid=10154, userID:0
,I/MusicLeanback( 4552): Conditions not met for autocaching.
,I/MusicLeanback( 4552): Stop autocaching.
D/PMS     (  910): releaseWL(4419a8e0): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,W/ContextImpl( 4552): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/ConnectivityService(  910): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=66 [3][2][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/AutoSetting( 1520): service - handleMessage() stop self
,D/AutoSetting( 1520): service - onDestroy() END
,D/AutoSetting( 1520): service - handleMessage() quit looper
,D/Process (  910): killProcessQuiet, pid=4326
,I/ActivityManager(  910): Killing 4326:com.htc.backup/1000 (adj 15): empty #17
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  910): Recipient 4326
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiStateMachine(  910): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  910): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,D/ContactMessageStore( 1239): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1239): MSG_NOTIFY_CS_TO_SYNC <<
,I/GAV2    ( 4653): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  910): killProcessQuiet, pid=4296
,I/ActivityManager(  910): Killing 4296:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  910): Recipient 4296
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  910): killProcessQuiet, pid=3915
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 3915:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 3915
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1347): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  910): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4752 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "sms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1272): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "smsto"
I/Launcher( 1272): Deferring update until onResume
,D/Launcher( 1272): waitUntilResume // bindAppsUpdated
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,W/SystemReader( 1258): Cannot find nfc_is_upgrade_to_ar890, use default value instead
W/AccTypeManager( 1347): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1347): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,E/ExternalAccountType( 1347): Unsupported attribute readOnly
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "sms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,D/PhoneApp( 1239): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4752): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4752): MmsConfig.loadMmsSettings
,W/dalvikvm( 4752): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4752): VFY: unable to resolve instance field 36
,W/dalvikvm( 4752): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4752): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  910): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/ActivityManager(  910): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4775 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4752, uid=10111, userID:0
,W/Settings( 4752): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4752, uid=10111, userID:0
,D/MessageFrequencyProvider( 4775): onCreate
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4752, uid=10111, userID:0
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4752, uid=10111, userID:0
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4752, uid=10111, userID:0
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4752, uid=10111, userID:0
,V/GetPrviateResource( 4775): GetPrviateResource
,V/GetPrviateResource( 4775): GetPrviateResource
,D/MmsCustomizationProvider( 4775): query uri: content://htc-mms-customization/mms-ua/ua_string
D/PMS     (  910): acquireWL(42a21c88): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4752 10111 null
,D/MmsCustomizationProvider( 4775): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/[PluginManager]RegisterService( 1328): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1328): handle notify Blinkfeed plugin client changed
,I/IcingCorporaProvider( 2824): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/Babel   ( 4752): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4752): MmsConfig.loadFromDatabase
,D/PMS     (  910): acquireWL(43166bf8): PARTIAL_WAKE_LOCK  AsyncService 0x1 4080 10160 null
,I/ActivityManager(  910): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  910): acquireWL(4427bae8): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(4427bae8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(429efd38): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,I/dalvikvm-heap( 4080): Grow heap (frag case) to 15.208MB for 1821008-byte allocation
E/Babel   ( 4752): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4752): MmsConfig.loadFromResources
,E/Babel   ( 4752): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4752): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/ProviderInstaller( 4752): Installed default security provider GmsCore_OpenSSL
D/MessageCustFlag( 4775): sense_version=6.0
,D/BTAccessoryUtil( 4775): createReceiver
,D/BTAccessoryUtil( 4775): registerReceiver return intent = null
D/MessageCustFlag( 4775): sku_id=99
,W/SystemReader( 4775): Cannot find message_ambs_application_id, use default value instead
D/PMS     (  910): releaseWL(43166bf8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/PMS     (  910): releaseWL(42a21c88): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  910): Resuming delayed broadcast
D/Messaging( 4775): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4775): networkCode: 
D/MessageCustFlag( 4775): sku_id=99
D/MmsConfig( 4775): SIE smsPri: null
D/MmsConfig( 4775): networkCode: 
,D/HtcTelephonyCapability( 4775): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 4775): The project is not dual project , phone_feature_type_stand_by = 0
I/dalvikvm-heap( 4080): Grow heap (frag case) to 16.945MB for 1821008-byte allocation
,D/HtcBuildUtils( 4775): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4775): Cannot find qct_8960_interface, use default value instead
,D/Process (  910): killProcessQuiet, pid=4350
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  910): Killing 4350:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  910): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,W/PackageManager(  910): Unable to load service info ResolveInfo{4285b1f8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
I/ActivityManager(  910): Recipient 4350
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PackageBroadcastService( 2179): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 2179): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  910): Resuming delayed broadcast
I/Icing   ( 2179): updateResources: need to parse f{com.google.android.gms}
,D/RemoteDisplayProvider(  910): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  910): start
,I/GCoreNlp( 1222): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  910): applying state to connected service
D/PMS     (  910): acquireWL(439d28f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(439d28f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  910): applying state to connected service
,D/PMS     (  910): acquireWL(44260cd0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2824): UpdateCorporaTask done [took 427 ms] updated apps [took 427 ms] 
D/PMS     (  910): releaseWL(44260cd0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43163b18): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43163b18): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1272): loadItems() com.htc.launcher.pageview.WidgetManager@41f10cd8 +
,I/Prism.WidgetManager( 1272): onLoadItems() +
,I/Icing   ( 2179): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2179): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  910): releaseWL(429efd38): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1272): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1272): onLoadItems() -
,I/Prism.ItemManager( 1272): loadItems() com.htc.launcher.pageview.WidgetManager@41f10cd8 -
,D/PhoneApp( 1239): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1239): -- N1 =0
,D/PhoneApp( 1239): -- N2 =0
,D/PhoneApp( 1239): -- N3 =0
,D/Messaging( 4775): mNeedToUpdateDate2 start
,D/MmsConfig( 4775): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4775): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4775): 
D/MmsAsyncWorkHandler( 4775): HM tk = 20001
D/ReportIndicatorCache( 4775): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4775): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41e8d3a8
,I/Messaging( 4775): mccmnc> 
,D/DraftCache( 4775): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4775): [DraftCache/1] refresh
,D/MmsConfig( 4775): networkCode: 
D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/MmsSmsV2Provider( 1239):  phoneType = -1
,D/MmsSmsV2Provider( 1239): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 4775): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/MmsSmsV2Provider( 1239):  phoneType = -1
,D/MessageCustFlag( 4775): sense_version=6.0
D/MmsSmsV2Provider( 1239): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/PhoneStorageUtil( 4775): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4775): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4775): createReceiver
,D/Jerry   ( 4775): start to preload cursor >>>>>>>
,D/Messaging( 4775): mNeedToUpdateDate2: false
D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/MmsSmsV2Provider( 1239):  phoneType = -1
D/TelephUtils( 1239): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
V/MmsProvider( 1239): Update uri=content://mms, match=0
,V/MmsProvider( 1239): selection=st=129 AND m_type!=134
,D/Messaging( 4775): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4775): TransactionService is going to be woken up.
,V/TransactionService( 4775): 1-Creating TransactionService
V/TransactionService( 4775): onStartCommand: 1
,D/MmsSystemEventReceiver( 4775): unRegisterForConnectionStateChanges
V/TransactionService( 4775): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4775): Loading previous transactions.
D/Messaging( 4775): ViewCache CreatePreload
,D/Messaging( 4775): ViewCache CreatePreloadOnlyMultipleOpsList
,D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/Cust_MMSMS( 4775): _has_set_default_values_2=true
,D/AccFlag ( 1239): device_type: 1
D/TransactionService( 4775): Force set service start id to 1
V/TransactionService( 4775): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4775): unRegisterForConnectionStateChanges
,V/TransactionService( 4775): Destroying TransactionService
,D/TransactionService( 4775): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4775): 4-Handling incoming message: { when=-5ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/MsgPreferenceUtils( 4775): def_index: 0
D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/MmsSmsV2Provider( 1239):  phoneType = -1
,D/MmsSmsV2Provider( 1239): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/MsgPreferenceUtils( 4775): globalIndex = 1
,D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1239): sku_id=99
,D/DraftCache( 4775): [DraftCache/472] rebuildCache
D/MsgPreferenceUtils( 4775): phone state: true
D/MsgPreferenceUtils( 4775): sd state: false
,D/MsgPreferenceUtils( 4775): vIndex = 0
,D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/MmsSmsV2Provider( 1239):  phoneType = -1
,D/MmsSmsV2Provider( 1239): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 4775): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/Jerry   ( 1239): URI_DRAFT
,D/DraftCache( 4775): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 4775): [DraftCache/472] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4775): 
D/MmsAsyncWorkHandler( 4775): HM tk = 20002
,D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1239): sku_id=99
,D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1239): sku_id=99
,D/PMS     (  910): acquireWL(43b80488): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  910): sending alarm PendingIntent{43c969b8: PendingIntentRecord{4293eca0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=122711, Int=0
,D/PMS     (  910): acquireWL(446cda00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43b80488): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1366/10029)
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [11][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/PMS     (  910): acquireWL(44146420): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(44146420): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(446cda00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43b84898): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024692
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024830
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024904
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024918
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024936
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024947
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026329
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026341
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029154
,D/PMS     (  910): releaseWL(43b84898): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(445d58e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1366/10029)
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024692
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024830
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024904
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024918
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024936
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024947
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026329
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026341
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029154
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): acquireWL(43e352f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43c62e68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1222): Vacuum at: now=1453032813347 tag=VacuumService
,D/PMS     (  910): releaseWL(445d58e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43e352f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43a59070): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024692
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024830
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024904
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024918
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024936
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024947
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026329
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026341
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029154
,D/PMS     (  910): releaseWL(43a59070): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43c62e68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(44695270): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1366/10029)
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024692
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024830
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024904
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024918
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024936
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024947
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026329
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026341
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029154
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/PMS     (  910): releaseWL(44695270): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(4427c480): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024692
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024830
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024904
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024918
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024936
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024947
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026329
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026341
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029154
,D/PMS     (  910): releaseWL(4427c480): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(429fc890): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1366/10029)
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024692
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024830
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024904
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024918
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024936
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024947
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026329
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026341
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029154
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/PMS     (  910): releaseWL(429fc890): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(442692c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1366/10029)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024692
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024830
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024904
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024918
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024936
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024947
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026329
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026341
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029154
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): acquireWL(4299a588): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(4299a588): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(4461aa38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(442692c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(439ba6e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024692
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024830
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024904
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024918
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024936
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024947
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026329
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026341
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029154
,D/PMS     (  910): releaseWL(439ba6e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1222): Scheduling Phenotype for one-off execution 3015 seconds from now (1453032813909)
,D/GetConfigurationSnapshotOperation( 1222): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1222): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1222): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1222): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1222): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1222): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1222): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  910): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
W/dalvikvm( 1222): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1222): [NET] getaddrinfo-,err=8
,D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1222): [NET] getaddrinfo-, 1
,D/libc    ( 1222): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =2981 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 236
D/libc    (  364): [NET]res_nsend:resplen=87
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1222): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1222): [NET] getaddrinfo-,err=8,
D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1222): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  910): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=22 [9][2][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): releaseWL(4461aa38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(428b3228): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024692
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024830
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024904
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024918
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024936
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024947
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026329
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026341
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029154
,D/PMS     (  910): releaseWL(428b3228): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(440dbf78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1366/10029)
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024692
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024830
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024904
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024918
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024936
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024947
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026329
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026341
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029154
,D/PMS     (  910): releaseWL(440dbf78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/GAV4    ( 4752): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  910): acquireWL(4428d220): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): releaseWL(4428d220): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  910): acquireWL(429e5ff8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  910): sending alarm PendingIntent{4346a7d0: PendingIntentRecord{428859d8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=136604, Int=0
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1366/10029)
,D/PMS     (  910): releaseWL(429e5ff8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1328): service - mHandler: update timezone
,D/AutoSetting( 1520): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1520): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1520): service - onCreate()
D/AutoSetting( 1520): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1520): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/DotMatrix( 1560): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
D/DotMatrix( 1560): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,D/AutoSetting( 1520): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1520): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1520): service - mHandler: update timezone
,D/AutoSetting( 1520): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1520): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1520): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1520): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1560): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1560): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1117): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{4203c5e0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.htclocationservice 3 7 2 11
,D/AutoSetting( 1328): service - has update message, not stop
,D/AutoSetting( 1328): service - mHandler: update timezone
,D/AutoSetting( 1520): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1520): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1520): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1520): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/DotMatrix( 1560): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1560): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1520): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1520): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1520): service - mHandler: update timezone
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1520): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1520): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1520): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1520): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1560): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1560): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1117): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41ed0318 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.htclocationservice 3 7 3 11
,D/GpsLocationProvider(  910): ALARM_XTRA_TIMEOUT
D/PMS     (  910): acquireWL(435757c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
V/AlarmManager(  910): sending alarm PendingIntent{4236cbb0: PendingIntentRecord{421b39b0 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142383, Int=0
D/PMS     (  910): acquireWL(446a3c48): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
,D/PMS     (  910): releaseWL(435757c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/GpsLocationProvider(  910): [handleMessage] DOWNLOAD_XTRA_DATA
D/GpsLocationProvider(  910): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/libc    (  910): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-,err=8
D/libc    (  910): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  910): [NET] getaddrinfo-, 1
,D/libc    (  910): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =3c27 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  364): [NET]res_nsend:resplen=238
D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo_proxy-, success
I/global  (  910): call createSocket() return a new socket.
D/libc    (  910): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  910): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  910): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  910): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  910):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  910): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  910): releaseWL(446a3c48): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  910): acquireWL(439b1730): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{421e0af8: PendingIntentRecord{421ce720 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=149572, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(439b1730): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ContactMessageStore( 1239): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1239): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{429e8008 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  910): acquireWL(445b0950): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
I/BatteryService(  910): n_update end
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): releaseWL(445b0950): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1328): service - handleMessage() stop self
,D/AutoSetting( 1328): service - handleMessage() quit looper
,D/AutoSetting( 1328): service - onDestroy() END
,D/Process (  910): killProcessQuiet, pid=4382
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4382:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4382
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1520): service - handleMessage() stop self
,D/AutoSetting( 1520): service - onDestroy() END
,D/AutoSetting( 1520): service - handleMessage() quit looper
,D/Process (  910): killProcessQuiet, pid=4397
,I/ActivityManager(  910): Killing 4397:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  910): Recipient 4397
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  910): acquireWL(446bd1c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10027}
,V/AlarmManager(  910): sending alarm PendingIntent{43468cc0: PendingIntentRecord{446f2ce0 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=174216, Int=0
,D/PMS     (  910): releaseWL(446bd1c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1239): switchBindHtcMsgCursor: null
,D/PMS     (  910): acquireWL(43ac0e48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): releaseWL(43ac0e48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(436c7308): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{421e0af8: PendingIntentRecord{421ce720 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=209572, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(436c7308): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(4464a138): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4464a138): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  910): acquireWL(4462c918): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4462c918): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HtcPowerSaver(  910): updateBatteryInfo
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1560): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1560): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  910): acquireWL(439a6b98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{421e0af8: PendingIntentRecord{421ce720 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=269572, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(439a6b98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  910): acquireWL(43c61b28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43c61b28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 4459): --= Surplus to requirements =--
I/jxcore-log( 4459): 
I/jxcore-log( 4459): ****TEST TOOK:  ms ****
I/jxcore-log( 4459): 
,I/jxcore-log( 4459): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4459): 
,E/cutils-trace( 4873): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 4873): ====startRecUseTime====
D/htc.customization.log.level( 4873):  is 
,W/CustomizationLogLevel( 4873): Level value is invalid, use default level 2
,D/CustomizationManager( 4873):  Read ACC file spent 0.055 (s)
D/CIDMapFileReader( 4873): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4873): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4873): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4873): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4873): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4873): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4873): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4873): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4873): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 4873): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4873): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4873): Parsing tag category name = system
,I/CustomizationCIDLoader( 4873): Parsing tag category name = application
I/CustomizationCIDLoader( 4873): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4873): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4873): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4873): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4873): Parsing tag category name = Settings
D/CustomizationManager( 4873):  Read CID file spent 0.093 (s)
,D/CustomizationManager( 4873):  All configurations done spent 0.093 (s)
W/HtcNativeFlag( 4873): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4873): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4873): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 4873): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  910): deletePackageAsUser: pkg=com.test.thalitest, pid=4873, uid=2000 user=0
,I/ActivityManager(  910): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
,D/Process (  910): killProcessQuiet, pid=4459
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  910): Killing 4459:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
,W/ActivityManager(  910): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  910):   Force finishing activity ActivityRecord{427570f0 u0 com.test.thalitest/.MainActivity t2}
,W/asset   (  910): Copying FileAsset 0x69efee60 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,W/PackageSettings(  910): Skipping PackageSetting{425d45c8 com.example.hello/10397} due to missing metadata
,E/JavaBinder(  910): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  910): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 1209): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  910): Got RemoteException sending setActive(false) notification to pid 4459 uid 10389
I/ActivityManager(  910): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.test.thalitest
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1560): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
,D/DotMatrix( 1560): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1560): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
,D/AccTypeManager( 1347): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/GeofencerStateMachine( 1222): Ignoring removeGeofence because network location is disabled.
,D/VoicemailCleanupService( 1285): Cleaning up data for package: com.test.thalitest
D/PMS     (  910): acquireWL(42952978): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42952978): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  910): WIN DEATH: Window{42926c10 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  910): Client connection lost with reason: 4
W/SystemReader( 1258): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "sms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/InputMethodManagerService(  910): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "smsto"
,I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/Launcher( 1272): Deferring update until onResume
D/Launcher( 1272): waitUntilResume // bindAppsRemoved
,W/AccTypeManager( 1347): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1347): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mms"
,I/[PluginManager]RegisterService( 1328): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/[PluginManager]RegisterService( 1328): handle notify Blinkfeed plugin client changed
,D/Prism.PackageStateRece_( 1272): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "sms"
,E/ExternalAccountType( 1347): Unsupported attribute readOnly
,I/IcingCorporaProvider( 2824): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/ActivityManager(  910): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4888 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,D/PhoneApp( 1239): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,D/PMS     (  910): acquireWL(43e0e480): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43e0e480): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43d81120): PARTIAL_WAKE_LOCK  Icing 0x1 2179 10029 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2824): UpdateCorporaTask done [took 178 ms] updated apps [took 177 ms] 
,W/PackageManager(  910): Unable to load service info ResolveInfo{428e9b70 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,E/SQLiteDatabase( 4888): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4888): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4888): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4888): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4888): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4888): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4888): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4888): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4888): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4888): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4888): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4888): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4888): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4888): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4888): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4888): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4888): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4888): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4888): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4888): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4888): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4888): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4888): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4888): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4888): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4888): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4888): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4888): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4888): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4888): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4888): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4888): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4888): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4888): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4888): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4888): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4888): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4888): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4888): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4888): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4888): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4888): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4888): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4888): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4888): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4888): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4888): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4888): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4888): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4888): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4888): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4888): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4888): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4888): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4888): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4888): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4888): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4888): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4888): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4888): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4888): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4888): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4888): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4888): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4888): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4888): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4888): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4888): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4888): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4888): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4888): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4888): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4888): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4888): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4888): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4888): threadid=11: thread exiting with uncaught exception (group=0x41a4be30)
E/ActivityManager(  910): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4888): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4888): Process: com.google.android.apps.docs, PID: 4888
E/AndroidRuntime( 4888): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4888): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4888): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4888): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4888): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4888): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4888): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4888): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4888): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4888): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4888): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4888): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4888): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4888): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4888): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4888): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4888): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4888): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4888): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  910): Can't write: system_app_crash
E/DropBoxManagerService(  910): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
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
,E/SQLiteDatabase( 4888): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4888): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4888): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4888): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4888): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4888): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4888): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4888): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4888): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4888): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4888): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4888): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4888): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4888): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4888): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4888): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4888): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4888): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4888): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4888): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4888): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4888): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4888): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4888): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4888): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4888): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4888): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4888): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4888): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4888): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4888): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4888): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4888): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4888): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4888): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4888): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4888): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4888): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4888): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4888): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4888): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4888): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4888): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4888): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4888): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4888): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4888): Opened ClientFlag.db in read-only mode
D/Process ( 4888): killProcess, pid=4888
D/Process ( 4888): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  910): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4907 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  910): Recipient 4888
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Process com.google.android.apps.docs (pid 4888) has died.
,D/RemoteDisplayProvider(  910): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  910): start
,W/AtomicFile(  910): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  910): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,W/ContextImpl( 4907): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,E/SQLiteDatabase( 4907): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4907): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4907): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4907): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4907): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4907): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4907): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4907): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4907): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 4907): threadid=10: thread exiting with uncaught exception (group=0x41a4be30)
E/AndroidRuntime( 4907): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4907): Process: com.android.keychain, PID: 4907
E/AndroidRuntime( 4907): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4907): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4907): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4907): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4907): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4907): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4907): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4907): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4907): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4907): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4907): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4907): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4907): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4907): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4907): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4907): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4907): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4907): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ActivityManager(  910): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4920 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
,E/ActivityManager(  910): App crashed! Process: com.android.keychain
D/ErrorReport(  910): HtcErrorReportManager Begin---add error logs to dropbox
,D/Process ( 4907): killProcess, pid=4907
,D/Process ( 4907): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  910): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  910): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453032996909.dbox_tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager(  910): Recipient 4907
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Process com.android.keychain (pid 4907) has died.
,W/ActivityManager(  910): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
,D/AppTag  ( 4920): getInstance(Context context)
,D/AppTag  ( 4920): getInstance(Context context)
D/AppTag  ( 4920): onCreate()
,D/PMS     (  910): acquireWL(43e4b508): PARTIAL_WAKE_LOCK  AsyncService 0x1 4080 10160 null
,D/PMS     (  910): releaseWL(43e4b508): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/Process (  910): killProcessQuiet, pid=4045
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,W/dalvikvm( 4107): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
I/ActivityManager(  910): Killing 4045:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4045
,D/PackageBroadcastService( 2179): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/AccountUtils( 2179): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 2179): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2179): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 2179): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2179): Module APK com.google.android.play.games already loaded
I/ActivityManager(  910): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
,E/SQLiteLog( 2179): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 2179): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6e64d978
,W/dalvikvm( 2179): threadid=46: thread exiting with uncaught exception (group=0x41a4be30)
I/LocationSettingsChecker( 2179): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 2179): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 2179): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x65621e60
,E/DriveAsyncService( 2179): disk I/O error (code 3850)
E/DriveAsyncService( 2179): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2179): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2179): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2179): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2179): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2179): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2179): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2179): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2179): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2179): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2179): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2179): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2179): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2179): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2179): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2179): 	at java.lang.Thread.run(Thread.java:864)
E/AndroidRuntime( 2179): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2179): Process: com.google.android.gms, PID: 2179
E/AndroidRuntime( 2179): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2179): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2179): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2179): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2179): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2179): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2179): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2179): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2179): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2179): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2179): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2179): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2179): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2179): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2179): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2179): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2179): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2179): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2179): 	at java.lang.Thread.run(Thread.java:864)
,E/ActivityManager(  910): App crashed! Process: com.google.android.gms
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
,D/Process ( 2179): killProcess, pid=2179
,D/Process ( 2179): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  910): handleWLDeath(43d81120): PARTIAL_WAKE_LOCK  Icing 0x1
I/ActivityManager(  910): Recipient 2179
D/WifiService(  910): Client connection lost with reason: 4
,I/ActivityManager(  910): Process com.google.android.gms (pid 2179) has died.
,W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10999ms
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 10999ms
,W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20998ms
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20998ms
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20997ms
,I/ActivityManager(  910): Resuming delayed broadcast
,W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 20994ms
,W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 20994ms
,E/SQLiteLog( 1366): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,E/SQLiteDBG( 1366): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x63eb9008
,W/dalvikvm( 1366): threadid=1: thread exiting with uncaught exception (group=0x41a4be30)
,E/AndroidRuntime( 1366): FATAL EXCEPTION: main
E/AndroidRuntime( 1366): Process: com.google.process.gapps, PID: 1366
E/AndroidRuntime( 1366): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1366): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1366): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1366): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1366): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1366): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1366): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1366): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1366): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1366): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1366): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1366): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1366): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1366): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1366): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1366): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1366): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1366): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1366): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1366): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1366): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1366): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1366): 	... 10 more
,E/ActivityManager(  910): App crashed! Process: com.google.process.gapps
E/DropBoxManagerService(  910): Can't write: system_app_crash
E/DropBoxManagerService(  910): java.io.FileNotFoundException: /data/system/dropbox/drop144.tmp: open failed: EROFS (Read-only file system)
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
,D/Process ( 1366): killProcess, pid=1366
,D/Process ( 1366): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  910): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4952 uid=10098 gids={50098, 3003, 5012}
,I/DeviceManagement( 4952): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4952 dbg=false s=true
,I/DeviceManagement( 4952): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
,I/DeviceManagement( 4952): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]],
,I/DeviceManagement( 4952): WorkflowService: Starting workflow service
I/DeviceManagement( 4952): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41eac0b0] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4952): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4952): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
,I/DeviceManagement( 4952): PackageUpdateWorkflow: ==================================================
,I/DeviceManagement( 4952): ModelRegistry: Loading model meta data from resources...
,I/ActivityManager(  910): Recipient 1366
,D/WifiService(  910): Client connection lost with reason: 4
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DeviceManagement( 4952): BackgroundController: *** Processing package remove for appID=com.test.thalitest
,I/DeviceManagement( 4952): SessionStateController: Checking invariants...
,I/ActivityManager(  910): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4968 uid=10099 gids={50099, 3003, 5012}
,I/ActivityManager(  910): Process com.google.process.gapps (pid 1366) has died.
,W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 30819ms
,D/Documents( 4968): Loading roots for com.android.providers.downloads.documents
,E/SQLiteDatabase( 4968): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4968): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4968): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4968): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4968): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4968): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4968): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4968): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4968): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4968): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4968): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4968): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4968): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4968): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4968): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4968): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4968): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4968): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4968): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4968): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4968): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4968): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4968): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4968): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4968): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4968): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4968): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4968): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4968): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4968): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4968): 	at dalvik.system.NativeStart.main(Native Method)
,W/dalvikvm( 4968): threadid=1: thread exiting with uncaught exception (group=0x41a4be30)
,D/Documents( 4968): Loading roots for com.android.externalstorage.documents
E/AndroidRuntime( 4968): FATAL EXCEPTION: main
E/AndroidRuntime( 4968): Process: com.android.documentsui, PID: 4968
E/AndroidRuntime( 4968): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4968): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4968): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4968): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4968): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4968): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4968): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4968): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4968): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4968): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4968): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4968): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4968): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4968): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4968): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4968): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4968): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4968): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4968): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4968): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4968): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4968): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4968): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4968): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4968): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4968): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4968): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4968): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4968): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4968): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4968): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4968): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4968): 	... 10 more
,I/ActivityManager(  910): Start proc com.google.android.gms for broadcast com.google.android.gms/.nearby.settings.NearbyAppUninstallReceiver: pid=4981 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/Process (  910): killProcessQuiet, pid=4430
,I/ActivityManager(  910): Killing 4430:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,E/ActivityManager(  910): App crashed! Process: com.android.documentsui
D/ErrorReport(  910): HtcErrorReportManager Begin---add error logs to dropbox
,E/ErrorReport(  910): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  910): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453032997486.dbox_tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager(  910): Recipient 4430
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4994 uid=10023 gids={50023, 1028, 1015, 1023}
,D/Process ( 4968): killProcess, pid=4968
,D/Process ( 4968): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,D/Process (  910): killProcessQuiet, pid=4509
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
I/ActivityManager(  910): Killing 4509:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4968
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Process com.android.documentsui (pid 4968) has died.
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Recipient 4509
,D/WifiService(  910): Client connection lost with reason: 4
,E/SQLiteDatabase( 4952): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4952): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4952): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4952): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4952): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4952): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 4952): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 4952): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4952): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4952): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 4952): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 4952): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 4952): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 4952): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 4952): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4952): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4952): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4952): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 4952): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 4952): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 4952): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 4952): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 4952): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4952): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 4952): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 4952): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4952): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel,.java:176)
E/SQLiteDatabase( 4952): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 4952): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 4952): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4952): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4952): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4952): 	at java.lang.Thread.run(Thread.java:864)
I/DeviceManagement( 4952): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4952): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4952): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
,D/ExternalStorage( 4994): After updating volumes, found 1 active roots
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1272): loadItems() com.htc.launcher.pageview.WidgetManager@41f10cd8 +
,I/Prism.WidgetManager( 1272): onLoadItems() +
,W/dalvikvm( 4981): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,E/SQLiteDatabase( 4952): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4952): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4952): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4952): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4952): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4952): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 4952): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 4952): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 4952): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 4952): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 4952): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4952): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4952): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4952): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 4952): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 4952): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 4952): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
E/SQLiteDatabase( 4952): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
E/SQLiteDatabase( 4952): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 4952): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 4952): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4952): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4952): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4952): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/DeviceManagement( 4952): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@41eac0b0]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/DeviceManagement( 4952): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/DeviceManagement( 4952): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/DeviceManagement( 4952): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/DeviceManagement( 4952): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/DeviceManagement( 4952): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/DeviceManagement( 4952): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/DeviceManagement( 4952): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/DeviceManagement( 4952): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/DeviceManagement( 4952): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/DeviceManagement( 4952): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
W/DeviceManagement( 4952): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
W/DeviceManagement( 4952): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/DeviceManagement( 4952): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/DeviceManagement( 4952): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
W/DeviceManagement( 4952): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 4952): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 4952): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 4952): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 4952): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 4952): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 4952): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 4952): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 4952): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 4952): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 4952): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 4952): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 4952): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 4952): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 4952): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 4952): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 4952): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 4952): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 4952): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 4981): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,I/DeviceManagement( 4952): WorkflowService: Stopping workflow service
I/MultiDex( 4981): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4981): install
,I/MultiDex( 4981): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4981): loading existing secondary dex files
,I/MultiDex( 4981): load found 3 secondary dex files
,I/MultiDex( 4981): install done

```
