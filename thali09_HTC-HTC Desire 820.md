#### Test 50650278ec2c976_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1190): nl80211: survey data missing!
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1190): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1190): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  907):    returned true
E/cutils-trace( 4398): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4398): ====startRecUseTime====
D/htc.customization.log.level( 4398):  is 
W/CustomizationLogLevel( 4398): Level value is invalid, use default level 2
D/CustomizationManager( 4398):  Read ACC file spent 0.061 (s)
D/CIDMapFileReader( 4398): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4398): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4398): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4398): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4398): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4398): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4398): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4398): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4398): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4398): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4398): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4398): Parsing tag category name = system
I/CustomizationCIDLoader( 4398): Parsing tag category name = application
I/CustomizationCIDLoader( 4398): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4398): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4398): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4398): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4398): Parsing tag category name = Settings
D/CustomizationManager( 4398):  Read CID file spent 0.102 (s)
D/CustomizationManager( 4398):  All configurations done spent 0.102 (s)
W/HtcNativeFlag( 4398): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4398): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4398): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4398): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
W/CpuWake (  907): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  907): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4398
D/PMS     (  907): acquireHCC(42704940): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 907 1000 null
D/PMS     (  907): acquireHCC(43bf6610): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 907 1000 null
W/asset   (  907): Copying FileAsset 0x62c74c88 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  907): @test_code: getHtcIntentFlag: 0 obj: 1136452960
I/FeedHostManager( 1270): [onPause]
I/FeedProviderManager( 1270): onPause
I/FeedHostManager( 1270): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c9fad0
I/SocialFeedProvider( 1270): +onPause
D/PMS     (  907): acquireWL(436d19a0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
I/SocialFeedProvider( 1270): -onPause
I/ActivityManager(  907): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4409 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1270): [trimMemory] 20
W/asset   ( 4409): Copying FileAsset 0x5c7ac4d0 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4409): Binding Chromium to main looper Looper (main, tid 1) {41b31968}
I/LibraryLoader( 4409): Expected native library version number "",actual native library version number ""
I/chromium( 4409): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4409): Initializing chromium process, renderers=0
D/PMS     (  907): acquireWL(43ba6f30): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  907): acquireWL(42642e20): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  907): java.lang.Throwable: stack dump
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42698d80:true
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4409): 1102347752: getState(). Returning 12
D/PMS     (  907): releaseWL(43ba6f30): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4409): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4409): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4409): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4409): Local Branch: 
I/Adreno-EGL( 4409): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4409): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4409):                  aa63bbd948f41d15fc72f585e
W/chromium( 4409): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4409): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4409): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4409): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4409): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4409): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4409): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4409): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4409): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4409): CordovaWebView is running on device made by: HTC
,W/AwContents( 4409): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  907): Disable input method client, pid=1270
,W/ResourceType( 4409): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4409): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b79498, mServedView=org.apache.cordova.engine.SystemWebView{41b3f100 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1209): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1209): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  907): Enable input method client, pid=4409
,W/AwContents( 4409): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  907): Displayed com.test.thalitest/.MainActivity: +291ms
,D/PMS     (  907): releaseWL(436d19a0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4409): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4409): JniHelper::setJavaVM(0x4160c048), pthread_self() = 1557031640
,D/JX-Cordova( 4409): jxcore cordova android initializing
,W/dalvikvm( 4409): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,I/dalvikvm-heap( 4409): Grow heap (frag case) to 11.553MB for 96598-byte allocation
,I/dalvikvm-heap( 4409): Grow heap (frag case) to 11.632MB for 144892-byte allocation
,I/dalvikvm-heap( 4409): Grow heap (frag case) to 11.748MB for 217334-byte allocation
,I/dalvikvm-heap( 4409): Grow heap (frag case) to 11.923MB for 325996-byte allocation
,I/dalvikvm-heap( 4409): Grow heap (frag case) to 12.198MB for 488990-byte allocation
,I/dalvikvm-heap( 4409): Grow heap (frag case) to 13.205MB for 1100216-byte allocation
,I/SensorManager(  907): mEventCount = 900
,I/dalvikvm-heap( 4409): Grow heap (frag case) to 14.082MB for 1650320-byte allocation
,I/dalvikvm-heap( 4409): Grow heap (frag case) to 15.461MB for 2475476-byte allocation
,I/dalvikvm-heap( 4409): Grow heap (frag case) to 17.489MB for 3713210-byte allocation
,W/CpuWake (  907): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  907): <<release mCpuPerf_Freq wakelock
D/PMS     (  907): releaseHCC(42704940): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  907): releaseHCC(43bf6610): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4409): Initializing JXcore engine
,W/jxcore-log( 4409): JXcore engine is ready
,W/jxcore-log( 4409): Starting JXcore engine
,W/jxcore-log( 4409): Platform android
W/jxcore-log( 4409): 
,W/jxcore-log( 4409): Process ARCH arm
W/jxcore-log( 4409): 
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1190): nl80211: survey data missing!
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1190): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1190): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,I/jxcore-log( 4409): JXcore Cordova bridge is ready!
I/jxcore-log( 4409): 
,W/jxcore-log( 4409): JXcore engine is started
,I/Choreographer( 4409): Skipped 140 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4409): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PMS     (  907): releaseWL(42642e20): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/PMS     (  907): Going to sleep due to screen timeout...
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42105f60
,W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = CM36282 Light sensor
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42105f60, eanble = 0, strlen(mName) = 59
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  907): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42087a30
W/SensorService(  907): Listener[1] = com.htc.smartdim.sensor_eye@4276c438
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  907): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  907): Couldn't get kernel wake lock stats
V/LightsService(  907): setLight #2: color=#0
D/qdlights(  907): set_light_buttons_func: on=0 brightness=0
V/LightsService(  907): setLight #0: color=#0
,D/WirelessDisplayService(  907): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  907): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  907): mWirelessDisplayManager is null
,D/SurfaceControl(  907): Excessive delay in blankDisplay() while turning screen off: 314ms
D/PMS     (  907): nativeSetInteractive:false
D/PMS     (  907): nativeSetInteractive:false done
D/PMS     (  907): nativeSetAutoSuspend:true
D/PMS     (  907): nativeSetAutoSuspend:true done
D/HABCtrl (  907): TPE algorithm. remove timeout.
D/PMS     (  907): OOBE c monitor 11
I/InputManager(  907): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  907): screenObserver, isScreenOn=false
D/NfcService( 1254): ScreenObserver: OFF
,D/NfcService( 1254): applyRouting - 0
,D/NfcService( 1254): applyRouting -2
I/InputMethodManagerService(  907): Disable input method client, pid=4409
D/PMS     (  907): acquireWL(426e15f0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
D/PMS     (  907): releaseWL(426e15f0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/KeyguardServiceDelegate(  907): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42459e58)
,I/IntentController( 1115): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/WirelessDisplayService(  907): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMN     (  907): wakingUp
D/PMS     (  907): acquireWL(440eeed0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,V/KeyguardServiceDelegate(  907): **** SHOWN CALLED ****
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/jxcore-log( 4409): Toggling radios to true
I/jxcore-log( 4409): 
D/PMS     (  907): releaseWL(440eeed0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
I/WindowManager(  907): No lock screen! windowToken=null
D/PMN     (  907): onScreenOn
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
D/MtpService( 2710): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2710): [MTP][onReceive]-
D/BluetoothAdapter( 4409): enable(): BT is already enabled..!
D/AutoSetting( 1342): receiver - intent: android.intent.action.USER_PRESENT
,D/NfcService( 1254): applyRouting - 0
,D/NfcService( 1254): applyRouting -2
,D/WifiManager( 4409): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
D/PMS     (  907): acquireWL(426f6bb0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
D/PMS     (  907): releaseWL(426f6bb0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/WifiService(  907): setWifiEnabled: true pid=4409, uid=10389
E/WifiService(  907): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  907): New client listening to asynchronous messages
I/WifiService(  907): isSprintWifiRestricted(): false
I/WifiService(  907): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  907): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/HtcDLNAServiceManager(  907): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  907): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  907): Settings:Agentvalue: 2
W/Settings:Agent(  907): >> traceCallingStack()
W/Settings:Agent(  907): Process.myPid(): 907
W/Settings:Agent(  907): Process.myTid(): 1369
W/Settings:Agent(  907): Process.myUid(): 1000
W/Settings:Agent(  907): 
W/Settings:Agent(  907): 
W/System.err(  907): java.lang.Throwable: stack dump
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  907): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  907): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  907): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  907): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  907): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  907): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  907): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  907): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  907): 
W/Settings:Agent(  907): << traceCallingStack(): 5(ms)
D/WifiManager( 4409): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  907): doBoolean: DISCONNECT
D/WifiManager( 4409): reconnect: Base Package Name=com.test.thalitest, uid=10389
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1190): TDLS: Tear down peers
I/wpa_supplicant( 1190): wpa_driver_nl80211_disconnect(reason_code=3)
D/AutoSetting( 1342): service - onCreate()
,I/jxcore-log( 4409): Radios toggled
I/jxcore-log( 4409): 
D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/BluetoothManagerService(  907): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=20742 delay=15s
D/AutoSetting( 1342): service - AddressCache: using context: com.htc.Weather
,I/jxcore-log( 4409): Got Device Bluetooth address: B4:CE:F6:AB:A4:6A
I/jxcore-log( 4409): 
,D/AutoSetting( 1342): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 1
,I/jxcore-log( 4409): Perf Test app loaded loaded
I/jxcore-log( 4409): 
,D/LocationManagerService(  907): request 42620548 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AlarmManager(  907): ACTION_SCREEN_ON
I/AlarmManager(  907): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done recovering
I/AlarmManager(  907): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done EPS screen off alarm recovering
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024763
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025060
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025162
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025167
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025177
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026639
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026663
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029304
I/Choreographer( 4409): Skipped 78 frames!  The application may be doing too much work on its main thread.
D/TetherSettings( 4076): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4076): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4076): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4076): Cust_ConnectToPC   : spcsc>false
D/        ( 4076): Cust_ConnectToPC   : IPT>true
D/        ( 4076): Cust_ConnectToPC   : Singel_USB>false
I/ClockThread( 1115): stop update clock
D/LocationManagerService(  907): provider request: passive ProviderRequest[ON interval=0]
W/Settings( 4076): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/jxcore-log( 4409): check test folder
I/jxcore-log( 4409): 
E/SmartNS_Utility( 4076): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4076): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4076): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
I/jxcore-log( 4409): found test : ./testFindPeers.js
I/jxcore-log( 4409): 
,I/PSReceiver( 4076): onReceive:android.intent.action.USER_PRESENT
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/SmartNS_PSService( 4076): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4076): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4076):  defaultType:0
W/ContextImpl( 4076): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1190): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1190): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1190): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  907): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  907): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  907): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1190): TDLS: Remove peers on disassociation
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1190): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
E/wpa_supplicant( 1190): send_and_recv error -67 - cmd 12
D/WifiMonitor(  907): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1190): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1190): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1190): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1190): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1190): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1190): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1190): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8f88bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1190):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1190): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1190): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1190): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1190): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1190): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1190): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1190): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1190): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1190): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1190): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1190): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1190): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1190): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1190): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1190): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1190): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1190): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1190): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1190): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1190): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1190): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1190): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1190): htc_wext_set_TX_TRACKING (0),+
I/wpa_supplicant( 1190): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1190): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1190): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1190): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1190): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1190): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1190): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1190): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1190): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1190): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1190): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1190): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1190): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1190): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1190): nl80211: Event message available
D/wpa_supplicant( 1190): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1190): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/WifiNative-wlan0(  907):    returned true
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1190): SET_SCREEN_ON:On
I/wpa_supplicant( 1190): htc_wext_set_keepalive +
I/wpa_supplicant( 1190): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1190): getPrivFuncNum +	
I/wpa_supplicant( 1190): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1190): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1190): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1190): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1190): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  907):    returned true
D/WifiPerfLock(  907): release()
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/WifiStateMachine(  907): PerfLock released for exiting ConnectedState
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
D/Tethering(  907): [isWifi] getHotspotEnabled: false
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1190): Power_Mode_Type mode = 0
I/wpa_supplicant( 1190): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1190): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
D/ConnectivityService(  907): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  907): acquireWL(43729e18): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 907 1000 null
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 4409): found test : ./testSendData.js
I/jxcore-log( 4409): 
D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/DhcpStateMachine(  907): [RunningState] Stop DHCP
V/SRS_Proc(  372): ParamSet string: screen_state=on
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  907): doBoolean: RECONNECT
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1190): Fast associate: Old scan results
I/wpa_supplicant( 1190): wpa_supplicant_scan enter
I/wpa_supplicant( 1190): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1190): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1190): wpa_supplicant_trigger_scan +
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1190): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1190): nl80211: Event message available
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/wpa_supplicant( 1190): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): Enter handleNetworkDisconnect
D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=20742 mDataStallAlarmIntent=PendingIntent{442394b0: PendingIntentRecord{4254e010 android broadcastIntent}}
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024763
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025060
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025162
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025167
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025177
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026639
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026663
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029304
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1190): Power_Mode_Type mode = 0
I/wpa_supplicant( 1190): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1190): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/UsbnetStateTracker(  907): isAvailable+-
D/UsbnetStateTracker(  907): reconnect
D/UsbnetStateTracker(  907): isAvailable+-
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/WISPrService( 4076): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024763
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025060
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025162
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025167
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025177
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026639
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026663
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029304
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  907): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  907): Provision feature enable=false
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  907): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  907): default: reconnect()
D/MDST    (  907): default: setTeardownRequested(false)
D/MDST    (  907): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  907): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  907): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/WISPrService( 4076): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
V/NativeCrypto( 1372): Read error: ssl=0x6613f860: I/O error during system call, Connection timed out
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  907): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiService(  907): New client listening to asynchronous messages
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/ConnectivityService(  907): resetConnections(wlan0, 3)
D/PMS     (  907): acquireWL(439db9e8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
V/NativeCrypto( 1372): SSL shutdown failed: ssl=0x6613f860: I/O error during system call, Broken pipe
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024763
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025060
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025162
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025167
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025177
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026639
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026663
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029304
I/ActivityManager(  907): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4466 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1372/10029)
D/WifiStateMachine(  907): Exit handleNetworkDisconnect
D/libc    (  365): [NET] entry_id:3   entry:0xb8ec0db8  removed 
D/libc    (  365): [NET] entry_id:4   entry:0xb8ec0c88  removed 
D/libc    (  365): [NET] entry_id:5   entry:0xb8eb7c20  removed 
D/libc    (  365): [NET] entry_id:1   entry:0xb8ec0f70  removed 
D/libc    (  365): [NET] entry_id:6   entry:0xb8ebc380  removed 
D/libc    (  365): [NET] entry_id:2   entry:0xb8ebc458  removed 
D/libc    (  365): [NET] entry_id:7   entry:0xb8ec0e80  removed 
D/libc    (  365): *************************
D/libc    (  365): *** DNS CACHE FLUSHED ***
D/libc    (  365): *************************
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  907): flush DNS cache for net 1(wlan0)
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  907): reportInetCondition for net -1, percentage: 0 by  (1372/10029)
I//system/bin/ip(  365): RTNETLINK answers: No such process
I/logwrapper(  365): /system/bin/ip terminated by exit(2)
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  907): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/PMS     (  907): acquireWL(43c60748): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:0
,I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:1
,I/chromium( 4409): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/ResourceType( 4409): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4409): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41b3f100 VFEDH.C. .F....ID 0,0-720,1134 #64}
,D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WISPrService( 4076): >>>>>WISPrService start isConnected = false<<<<<
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
,D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 4076): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1372/10029)
D/ConnectivityService(  907): mActiveDefaultNetwork: -1
D/ConnectivityService(  907): handleInetConditionChange: no active default network - ignore
D/WifiStateMachine(  907): startScan Pid: 907 Uid 1000
D/WifiNative-wlan0(  907): doBoolean: SCAN
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1190): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  907):    returned false
D/PMS     (  907): releaseWL(439db9e8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/BatSI   (  907): WIFI scan started for: 450a0300 uid:1000
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1372/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1372/10029)
,D/PMS     (  907): releaseWL(43c60748): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,W/ContextImpl( 4466): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/NetworkPolicy(  907): updateScreenOn: false
,D/PMS     (  907): acquireWL(42684ef0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4466 1000 null
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  907): acquireWL(42ebd9b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42ebd9b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/SmartSyncUtils( 4466): isEpsOn(), nState = 0
,D/PMS     (  907): acquireWL(436cf470): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(436cf470): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1743): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1743): onScreenOn: 1450109356826
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1743): onScreenOn: 1450109356826
D/PMS     (  907): releaseWL(42684ef0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42087a30
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42087a30, eanble = 0, strlen(mName) = 91
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  907): Listener[0] = com.htc.smartdim.sensor_eye@4276c438
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  907): goingToSleep
,D/SmartSyncUtils( 4466): getMobilePolicyEnabled, result = true
D/PMS     (  907): acquireWL(439db428): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 907 1000 null
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  907): releaseWL(439db428): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/AlarmManager(  907): ACTION_SCREEN_OFF
I/AlarmManager(  907): [AlarmQueuing] screen off now: 
I/AlarmManager(  907): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=20743 mDataStallAlarmIntent=null
,D/WifiNative-wlan0(  907): doBoolean: SET pno 1
,D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1190): SET_SCREEN_ON:Off
I/wpa_supplicant( 1190): htc_wext_set_keepalive +
I/wpa_supplicant( 1190): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1190): getPrivFuncNum +	
I/wpa_supplicant( 1190): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1190): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1190): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 1190): get_ip_address source addr = 02000000
I/wpa_supplicant( 1190): htc_wext_set_keepalive gateway addr = 00000000
,I/wpa_supplicant( 1190): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  907):    returned true
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1190): CTRL_IFACE SET 'pno'='1'
I/AlarmManager(  907): [AlarmQueuing] wifi connection: true
,D/PMS     (  907): acquireWL(42c68060): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 907 1000 null
,V/SRS_Proc(  372): ParamSet string: screen_state=off
D/NetworkPolicy(  907): updateScreenOn: false
,W/ContextImpl( 4466): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/ContactMessageStore( 1238): start background delete task...
D/SmartSyncUtils( 4466): isEpsOn(), nState = 0
D/ContactMessageStore( 1238): size: 0 , 0
D/ContactMessageStore( 1238): Background delete complete
D/SmartSyncUtils( 4466): getMobilePolicyEnabled, result = true
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1190): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1190): nl80211: Event message available
D/wpa_supplicant( 1190): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1190): nl80211: Event message available
D/wpa_supplicant( 1190): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1190): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1190): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1190): nl80211: Survey data missing
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1190): Sorted scan results
I/wpa_supplicant( 1190): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-53
D/wpa_supplicant( 1190): BSS: last_scan_res_used=1/32 last_scan_full=0
D/wpa_supplicant( 1190): Add randomness: count=8 entropy=0
D/wpa_supplicant( 1190): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1190): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1190): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1190): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1190): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1190): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1190): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1190): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1190): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1190): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1190): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1190): WPS: AP[0] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1190): wpa_supplicant_pick_network+
I/wpa_supplicant( 1190): Selecting BSS from priority group 1
I/wpa_supplicant( 1190): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1190): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1190): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1190):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1190):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-53
I/wpa_supplicant( 1190): Start print parameters
I/wpa_supplicant( 1190): wpa_s->wpa_state is 3
I/wpa_supplicant( 1190): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1190): isConcurrentMode() is 0
I/wpa_supplicant( 1190): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1190): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1190): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1190): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1190): wpa_s->reassociate is 1
I/wpa_supplicant( 1190): wpa_s->is_screen_on 0
I/wpa_supplicant( 1190): wpa_s->ifname wlan0
I/wpa_supplicant( 1190): End print parameters
I/wpa_supplicant( 1190): selected network = 1
D/wpa_supplicant( 1190): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8f8a4e8  current_ssid=0x0
D/wpa_supplicant( 1190): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1190): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1190): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1190): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1,190): check if in concurrent case
I/wpa_supplicant( 1190): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiNative-wlan0(  907):    returned true
D/wpa_supplicant( 1190): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1190): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1190): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1190): RSN: PMKSA cache search - network_ctx=0xb8f8a4e8 try_opportunistic=0
D/wpa_supplicant( 1190): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1190): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1190): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1190): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1190): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1190): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1190): nl80211: Set mode ifindex 22 iftype 2 (STATION)
D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 1
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1190): nl80211: Unsubscribe mgmt frames handle 0xb8f89718 (mode change)
D/wpa_supplicant( 1190): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8f89718
D/wpa_supplicant( 1190): nl80211: Register frame type=0xd0 nl_handle=0xb8f89718
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=,
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1190): nl80211: Register frame type=0xd0 nl_handle=0xb8f89718
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1190): nl80211: Register frame type=0xd0 nl_handle=0xb8f89718,
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1190): nl80211: Register frame type=0xd0 nl_handle=0xb8f89718
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1190): nl80211: Register frame type=0xd0 nl_handle=0xb8f89718
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 58
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/wpa_supplicant( 1190): nl80211: Register frame type=0xd0 nl_handle=0xb8f89718
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1190): nl80211: Register frame type=0xd0 nl_handle=0xb8f89718
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1190): nl80211: Register frame type=0xd0 nl_handle=0xb8f89718
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1190): nl80211: Register frame type=0xd0 nl_handle=0xb8f89718
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1190): nl80211: Register frame type=0xd0 nl_handle=0xb8f89718
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1190): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1190):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1190):   * freq=2412
D/wpa_supplicant( 1190):   * Auth Type 0
D/wpa_supplicant( 1190):   * WPA Versions 0x2
D/WifiService(  907): New client listening to asynchronous messages
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024763
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025060
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025162
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025167
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025177
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026639
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026663
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029304
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1190): nl80211: Connect request send successfully
,D/wpa_supplicant( 1190): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1190): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1190): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1190): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1190): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1190): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1190): EAPOL: External notification - portControl=Auto
,D/wpa_supplicant( 1190): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1190): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1190): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: SET pno 1
D/SmartSyncUtils( 4466): isEpsOn(), nState = 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1190): CTRL_IFACE SET 'pno'='1'
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1190): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1190): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1190): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1190): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1190): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1190): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1190): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1190): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1190): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1190): reply (666) for get BSS: id=0
I/wpa_supplicant( 1190): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1190): freq=5220
I/wpa_supplicant( 1190): level=-49
I/wpa_supplicant( 1190): tsf=0000000022910131
I/wpa_supplicant( 1190): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1190): ssid=NG7005g
I/wpa_supplicant( 1190): ====,
I/wpa_supplicant( 1190): id=1
I/wpa_supplicant( 1190): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1190): freq=2412
I/wpa_supplicant( 1190): level=-53
I/wpa_supplicant( 1190): tsf=0000000104456780
I/wpa_supplicant( 1190): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1190): ssid=NG700
I/wpa_supplicant( 1190): ====
I/wpa_supplicant( 1190): id=2
I/wpa_supplicant( 1190): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1190): freq=2427
I/wpa_supplicant( 1190): level=-77
I/wpa_supplicant( 1190): tsf=0000000022910148
I/wpa_supplicant( 1190): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1190): ssid=Gonzos
I/wpa_supplicant( 1190): ====
,I/wpa_supplicant( 1190): id=3
I/wpa_supplicant( 1190): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1190): freq=2462
I/wpa_supplicant( 1190): level=-89
I/wpa_supplicant( 1190): tsf=0000000022910156
I/wpa_supplicant( 1190): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1190): ssid=UPC5999698
I/wpa_supplicant( 1190): ====
I/wpa_supplicant( 1190): id=4
I/wpa_supplicant( 1190): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1190): freq=2462
I/wpa_supplicant( 1190): level=-90
I/wpa_supplicant( 1190): tsf=0000000022910152
I/wpa_supplicant( 1190): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
,I/wpa_supplicant( 1190): ssid=UPC Wi-Free
I/wpa_supplicant( 1190): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/PMS     (  907): releaseWL(42c68060): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 22910131, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -53, frequency: 2412, timestamp: 104456780, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2427, timestamp: 22910148, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -89, frequency: 2462, timestamp: 22910156, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 22910152, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiManager( 1221): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WifiStateMachine(  907): add 5 to mScanResults
D/BatSI   (  907): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4276c438
,W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 1
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4276c438, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = CM36282 Proximity sensor
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 0
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4276c438, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4276c438
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] getTotalRam: 1873 Mb
E/ActivityThread(  907): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4276c980 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  907): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4276c980 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
D/PMS     (  907): acquireWL(437be598): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(437be598): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(43bf32e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43bf32e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1743): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1743): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1743): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1743): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1743): onScreenOff
,D/AutoSetting( 1342): service - mHandler: cancel location update
,D/AutoSetting( 1342): service -           changes count: 0
,D/wpa_supplicant( 1190): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1190): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1190): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1190): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1190): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1190): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1190): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1190): nl80211: Event message available
D/wpa_supplicant( 1190): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1190): nl80211: Connect event
D/wpa_supplicant( 1190): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1190): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1190): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1190): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1190): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1190): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1190): Add randomness: count=9 entropy=1
I/wpa_supplicant( 1190): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1190): TDLS: Remove peers on association
D/wpa_supplicant( 1190): EAPOL: External notification - portEnabled=0
,D/wpa_supplicant( 1190): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1190): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1190): EAPOL: External notification - portValid=0
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1190): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1190): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1190): EAPOL: External notification - EAP success=0
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1190): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1190): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1190): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1190): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1190): EAPOL: enable timer tick
,D/wpa_supplicant( 1190): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1190): htc_wext_set_keepalive +
I/wpa_supplicant( 1190): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1190): getPrivFuncNum +	
I/wpa_supplicant( 1190): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1190): htc_wext_set_keepalive fnum = 0x8bf6
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
I/wpa_supplicant( 1190): htc_wext_set_keepalive - ret = 0
D/WifiMonitor(  907): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  907): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  907): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  907): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  907): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  907): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  907): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  907): Enter handleAssociatedWithEvent
,D/WifiStateMachine(  907): Associated
D/WifiStateMachine(  907): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  907): Exit handleAssociatedWithEvent
I/wpa_supplicant( 1190): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1190): Get randomness: len=32 entropy=2
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  907): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
D/Tethering(  907): interfaceStatusChanged wlan0, true
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  907): This record is existed, only update it...
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,I/wpa_supplicant( 1190): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1190): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb8f899f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1190):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1190): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1190): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,D/wpa_supplicant( 1190): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f0eb4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1190):    broadcast key
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1190): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1190): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1190): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1190): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/wpa_supplicant( 1190): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 1190): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
E/wpa_supplicant( 1190): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1190): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1190): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1190): set send_ind_to_ndc = 0
,I/wpa_supplicant( 1190): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1190): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1190): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1190): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1190): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1190): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1190): EAP: EAP entering state DISABLED
,D/wpa_supplicant( 1190): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1190): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1190): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1190): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1190): EAPOL authentication completed successfully
I/wpa_supplicant( 1190): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
,E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1190): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1190): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1190): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
D/Tethering(  907): interfaceStatusChanged wlan0, true
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  907): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
,D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,D/WifiStateMachine(  907): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
,I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  907): This record is existed, only update it...,
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  907): Provision feature enable=false
,D/ConnectivityService(  907): mActiveDefaultNetwork: -1
D/WISPrService( 4076): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4076): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,D/WifiNative-wlan0(  907): doBoolean: SET pno 0
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1190): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1190): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1190): nl80211: Event message available
D/wpa_supplicant( 1190): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
,D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/DhcpStateMachine(  907): [StoppedState] Start DHCP
D/WifiStateMachine(  907): handlePreDhcpSetup Held wake lock during DHCP
,D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
,I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1190): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1190): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 1
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1190): Power_Mode_Type mode = 1
I/wpa_supplicant( 1190): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING GET
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1190): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  907):    returned null
E/WifiStateMachine(  907): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 1190): nl80211: Event message available
D/wpa_supplicant( 1190): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1190): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
,I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1190): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  907):    returned null,
D/PMS     (  907): acquireWL(426f3cb0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 907 1000 null
D/WifiStateMachine(  907): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42628828 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42628828 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:1
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  907): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4503 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
,D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  907): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTING DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
D/Tethering(  907): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  907): bSetPropertyMultiRAB:false
,D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  907): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  907): ipv4Default null
I/Tethering(  907): No IPv4 upstream interface, giving up.
D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
D/CaptivePortalTracker(  907): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  907): NoActiveNetworkState
D/PMS     (  907): acquireWL(437cce88): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/PMS     (  907): releaseWL(437cce88): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4259/10100)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
,I/ConnectivityHelper( 1270): [onReceive] WIFI(1): CONNECTING
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1270/10076)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1568/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4259/10100)
,D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024763
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025060
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025162
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025167
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025177
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026639
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026663
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029304
,I/MusicStore( 4503): Database version: 95
,W/ContextImpl( 4503): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4503): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4503): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4503): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4503): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4503, uid=10154, userID:0
,D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
,D/MediaRouterService(  907): Client com.google.android.music (pid 4503): Registered
,D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
,I/MediaRouter( 4503): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.music (4503/10154)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (2710/10021)
,I/ActivityManager(  907): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4523 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4503): getSelectedRoute
,I/NetworkMonitor( 4503): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (4503/10154)
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4503, uid=10154, userID:0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/ACRA    ( 4523): ACRA is enabled for com.facebook.katana, intializing...
,D/Process (  907): killProcessQuiet, pid=4194
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  907): acquireWL(44134988): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/PMS     (  907): releaseWL(44134988): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  907): Killing 4194:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/ACRA    ( 4523): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4523): Looking for error files in /data/data/com.facebook.katana/app_minidumps
I/ActivityManager(  907): Recipient 4194
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  907): Client connection lost with reason: 4
,W/SystemClassLoaderAdder( 4523): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4523): Preparing secondary program dexes.
V/DexLibLoader( 4523): Loaded 4 raw lines of metadata.
V/DexLibLoader( 4523): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4523): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4523): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4523): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4523): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4523): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4523): Dex already copied
D/OdexVerifier( 4523): Odex verification is skipped. OS version not supported.
V/DexLibLoader( 4523): Creating class loader
,V/DexLibLoader( 4523): Finished creating class loader
V/DexLibLoader( 4523): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4523): Dex already copied
D/OdexVerifier( 4523): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4523): Creating class loader
,V/DexLibLoader( 4523): Finished creating class loader
V/DexLibLoader( 4523): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4523): Dex already copied
D/OdexVerifier( 4523): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4523): Creating class loader
,V/DexLibLoader( 4523): Finished creating class loader
V/DexLibLoader( 4523): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4523): Dex already copied
D/OdexVerifier( 4523): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4523): Creating class loader
V/DexLibLoader( 4523): Finished creating class loader
,V/DexLibLoader( 4523): Verifying classes from secondary dexes.
D/wpa_supplicant( 1190): EAPOL: startWhen --> 0
D/wpa_supplicant( 1190): EAPOL: disable timer tick
,D/DexLibLoader( 4523): DexLibLoader.ensureDexLoaded took 13 ms,
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,W/dalvikvm( 4523): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4523): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4523): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4523): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4523): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4523): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4523): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1190): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1190): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1190): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1190): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  907): releaseWL(426f3cb0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1190): nl80211: survey data missing!
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1190): environment dirty rate=0 [3][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1190): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  907):    returned true
D/WIFI_ICON( 1115): updateWifiState: RSSI_CHANGED -1 -> 3
D/WifiStateMachine(  907): gateway: /192.168.1.1
D/WifiNative-wlan0(  907): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1190): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1190): htc_wext_set_keepalive +
I/wpa_supplicant( 1190): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1190): getPrivFuncNum +	
I/wpa_supplicant( 1190): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1190): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1190): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1190): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1190): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  907): VerifyingLinkState enter
D/WifiStateMachine(  907): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  907): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  907): VerifyingLinkState: enableIpv6
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -53, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/WifiWatchdogStateMachine(  907): WAN detection
,I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NetworkPolicy(  907): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  907): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  907): default: teardown()
D/MDST    (  907): default: setTeardownRequested(true)
D/MDST    (  907): default: setEnableApn apnType =default , enable=false
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WISPrService( 4076): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/MDST    (  907): default: setTeardownRequested(true)
D/ConnectivityService(  907): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  907): Unexpected mtu value: android.net.wifi.WifiStateTracker@424b9ba8
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=false resetMask=0
,E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1190): nl80211: survey data missing!
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1190): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  907): syncGetConfiguredNetworks
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  907): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  365): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  907): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  907): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
D/WirelessDisplayService(  907): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  907):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  907): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  907): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  907): acquireWL(424ca1e0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1190): nl80211: survey data missing!
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1190): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
,I/QuickSettingWifi( 1115): receive.wifiConnect:true wifiAPname:NG700 elapse:1
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1190): nl80211: survey data missing!
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1190): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(424ca1e0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I//system/bin/ip(  365): RTNETLINK answers: No such file or directory
,I/logwrapper(  365): /system/bin/ip terminated by exit(254)
,I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  907): mActiveDefaultNetwork: WIFI
,W/dalvikvm( 4523): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4523): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4523): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4523): Verify
,D/WifiService(  907): New client listening to asynchronous messages
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4523): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4523): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4523): Grow heap (frag case) to 9.511MB for 73240-byte allocation
,D/Process (  907): killProcessQuiet, pid=3810
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 3810:com.htc.mediamanager/u0a34 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3810
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1342): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  907): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4574 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1342/10055)
D/AutoSetting( 1342): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1342): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 1342): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1342): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1342/10055)
,W/fb4a(:<default>):UserScope( 4523): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4523): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4523): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4574): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4574): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4574): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4574): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  907): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4588 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=4013
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 4013:com.google.android.talk/u0a111 (adj 15): empty #17
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4574/10079)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4574/10079)
,D/PMS     (  907): acquireWL(421006c8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4574/10079)
,D/PMS     (  907): acquireWL(425b3a20): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2184): Checkin interval check for package: unspecified last checkin: 1450109308673 min interval config: 0 actual interval: 50828
D/PMS     (  907): releaseWL(421006c8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2184): Checking schedule, now: 1450109359508 next: 1450109338648
,I/CheckinService( 2184): active receiver: enabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2184, uid=10029, userID:0
,I/CheckinService( 2184): Preparing to send checkin request
,I/EventLogService( 2184): Accumulating logs since 1450109304955
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
,I/ActivityManager(  907): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4603 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=4227
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 4227:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4227
,E/dalvikvm( 4523): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4523): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4523): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4523): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4523): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4523): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/dalvikvm( 4523): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4523): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4523): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4523): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4523): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4523): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4523): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4523): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4523): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4523): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4523): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4523): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/CheckinRequestBuilder( 2184): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  907): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2184): Failed to find provider info for com.google.android.wearable.settings
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4603): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,I/dalvikvm-heap( 4523): Grow heap (frag case) to 9.922MB for 39954-byte allocation
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4603): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
I/ActivityManager(  907): Recipient 4013
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/GAV2    ( 4603): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4603): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,W/Vold    (  348): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4603): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/dalvikvm-heap( 4523): Grow heap (frag case) to 9.999MB for 79892-byte allocation
,I/dalvikvm-heap( 4523): Grow heap (frag case) to 10.062MB for 84664-byte allocation
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (2184/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1190): nl80211: survey data missing!
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1190): environment dirty rate=0 [0][0][0]
,I/dalvikvm-heap( 4523): Grow heap (frag case) to 10.088MB for 28144-byte allocation
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4603/10151)
,V/WebViewChromiumFactoryProvider( 4603): Binding Chromium to main looper Looper (main, tid 1) {41b38428}
,I/LibraryLoader( 4603): Expected native library version number "",actual native library version number ""
,I/chromium( 4603): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4603): Initializing chromium process, renderers=0
,D/PMS     (  907): acquireWL(426c0ad0): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,E/AudioManagerAndroid( 4603): BLUETOOTH permission is missing!
D/PMS     (  907): acquireWL(436ff148): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  907): releaseWL(426c0ad0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4603): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4603): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4603): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4603): Local Branch: 
I/Adreno-EGL( 4603): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4603): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4603):                  aa63bbd948f41d15fc72f585e
,D/PMS     (  907): releaseWL(43729e18): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  907): NetTransition Wakelock for ConnectedState released by timeout
,I/ActivityManager(  907): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4633 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/NSApplication( 4603): Starting up...,
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4603/10151)
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4603/10151)
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: true
,V/Tethering(  907): bSetPropertyMultiRAB:false
,D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,I/NetworkMonitor( 4503): type=WIFI subType= reason=null isConnected=true
,D/CaptivePortalTracker(  907): NoActiveNetworkState
I/Tethering(  907): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  907): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
,I/Tethering(  907): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
W/dalvikvm( 4633): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,I/Tethering(  907): ipv4Default 0.0.0.0/0 -> 192.168.1.1
,I/Tethering(  907): Found interface wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (4503/10154)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1568/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
D/AccTypeManager( 1321): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 4633): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4633): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4633): install
,I/MultiDex( 4633): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/dalvikvm-heap( 4523): Grow heap (frag case) to 10.276MB for 75760-byte allocation
,I/ConnectivityHelper( 1270): [onReceive] WIFI(1): CONNECTED
,I/MultiDex( 4633): loading existing secondary dex files
D/PMS     (  907): acquireWL(43cc59e8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4259/10100)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4574/10079)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1270/10076)
,I/MultiDex( 4633): load found 3 secondary dex files
,I/MultiDex( 4633): install done
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1190): nl80211: survey data missing!
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1190): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
W/AccTypeManager( 1321): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1321): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.musicenhancer (3865/10053)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1568/10029)
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1190): nl80211: survey data missing!
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1190): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4259/10100)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024763
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025060
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025162
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025167
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025177
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026639
W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43ce8fc0 u0 ReceiverList{43bdc3d8 4523 com.facebook.katana/10027/u0 remote:436749f8}}
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026663
W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43ce8fc0 u0 ReceiverList{43bdc3d8 4523 com.facebook.katana/10027/u0 remote:436749f8}}
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029304
D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  907): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1190): nl80211: survey data missing!
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1190): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(43c8df08): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42c68688 u0 ReceiverList{42c68628 4523 com.facebook.katana/10027/u0 remote:42537b40}}
D/PMS     (  907): releaseWL(43c8df08): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
D/PMS     (  907): releaseWL(43cc59e8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4053/10160)
,E/ExternalAccountType( 1321): Unsupported attribute readOnly
,D/Process (  907): killProcessQuiet, pid=4259
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1190): nl80211: survey data missing!
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1190): environment dirty rate=0 [0][0][0]
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4053/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
I/ActivityManager(  907): Killing 4259:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,W/dalvikvm( 4633): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024763
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025060
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025162
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025167
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025177
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026639
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026663
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029304
I/ActivityManager(  907): Recipient 4259
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/dalvikvm( 4633): VFY: unable to resolve instance field 36
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1190): nl80211: survey data missing!
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1190): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 4633): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1372/10029)
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1190): nl80211: survey data missing!
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1190): environment dirty rate=0 [0][0][0]
,V/JNIHelp ( 4633): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1190): nl80211: survey data missing!
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1190): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1372/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (2710/10021)
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1190): nl80211: survey data missing!
,E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1190): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1190): nl80211: survey data missing!
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1190): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1190): nl80211: survey data missing!
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1190): environment dirty rate=0 [0][0][0]
,D/AutoSetting( 1342): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/MobileConnectivityChangeReceiver( 4574): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4574): onReceive CONNECTIVITY_CHANGE networkType=1
D/PMS     (  907): acquireWL(433cb1a0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(433cb1a0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1342/10055)
D/AutoSetting( 1342): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1342): service - onStartCommand() screen is off, don't request location
,D/AutoSetting( 1342): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1342): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1342/10055)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4603/10151)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1190): nl80211: survey data missing!
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1190): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1190): nl80211: survey data missing!
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1190): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4053/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4053/10160)
D/PMS     (  907): acquireWL(442184e0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2184): Checkin interval check for package: unspecified last checkin: 1450109308673 min interval config: 0 actual interval: 51302
,I/dalvikvm-heap( 4053): Grow heap (frag case) to 13.501MB for 1821008-byte allocation
D/PMS     (  907): releaseWL(442184e0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2184, uid=10029, userID:0
I/ProviderInstaller( 4633): Installed default security provider GmsCore_OpenSSL
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1190): nl80211: survey data missing!
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1190): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1190): nl80211: survey data missing!
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1190): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1372/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1372/10029)
,W/dalvikvm( 4633): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4633): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4523): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/dalvikvm( 4633): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4633): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4633): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4633): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4633): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,W/Vold    (  348): Returning OperationFailed - no handler for errno 30
D/WearableService( 1221): callingUid 10029, callindPid: 1221
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/LocationInitializer( 2184): Restart initialization of location
,W/ContextImpl( 4523): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,W/Vold    (  348): Returning OperationFailed - no handler for errno 30
E/MDM     ( 1221): [114] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4523): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,W/GCoreFlp( 1221): No location to return for getLastLocation()
,W/FusedLocationProvider( 1221): location=null
D/PMS     (  907): acquireWL(42664748): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(42664748): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024763
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025060
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025162
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025167
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025177
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026639
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026663
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029304
,D/AuthorizationBluetoothService( 1372): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1372): Proximity feature is not enabled.
,I/WVCdm   (  372): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  372): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  372): CdmEngine::OpenSession
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
,D/NativeLibraryUtils( 4633): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  372): PrepareKeyRequest: nonce=2599206704
,I/WVCdm   (  372): CdmEngine::CloseSession
,W/Settings( 4633): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/WVCdm   (  372): CdmEngine::OpenSession
,I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  372): PrepareKeyRequest: nonce=1772111638
,I/WVCdm   (  372): CdmEngine::CloseSession
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
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (4633/10029)
,I/CheckinRequestBuilder( 2184): Classify the device as Phone.
,D/libc    ( 2184): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2184): [NET] getaddrinfo-,err=8
,D/libc    ( 2184): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2184): [NET] getaddrinfo-, 1
,D/libc    ( 2184): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =dbc1 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE,
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 293
D/libc    (  365): [NET]res_nsend:resplen=84
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2184): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2184): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2184): [NET] getaddrinfo-,err=8
,D/libc    ( 2184): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2184): [NET] getaddrinfo-,err=8
D/libc    ( 2184): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2184): [NET] getaddrinfo-,err=8
,I/jxcore-log( 4409): BLE advertisement not supported: Build version is 19
I/jxcore-log( 4409): 
,I/CheckinTask( 2184): Sending checkin request (12078 bytes)
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =dba5 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  365): [NET]res_nsend:resplen=172
D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  907): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  907): Find DNS Address www.htc.com/23.59.123.86
,I/CheckinRequestBuilder( 2184): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  907): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2184): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (2184/10029)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1190): nl80211: survey data missing!
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1190): environment dirty rate=0 [23][0][0]
,I/CheckinRequestBuilder( 2184): Classify the device as Phone.
,I/CheckinTask( 2184): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,I/CheckinService( 2184): Checking schedule, now: 1450109362300 next: 1450632299170
,I/CheckinService( 2184): active receiver: disabled
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2184, uid=10029, userID:0
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024763
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025060
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025162
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025167
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025177
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026639
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026663
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029304
,I/CheckinService( 2184): Checking schedule, now: 1450109362336 next: 1450632299170
,I/CheckinService( 2184): active receiver: disabled
,D/CheckinService( 2184): Recording last checkin time for package unspecified as 1450109362340
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2184, uid=10029, userID:0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024763
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025060
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025162
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025167
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025177
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026639
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026663
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029304
,W/fb4a(:<default>):UserScope( 4523): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/fb4a(:<default>):UserScope( 4523): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/PMS     (  907): releaseWL(425b3a20): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
D/PMS     (  907): acquireWL(441e3340): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1372/10029)
,D/libc    ( 1372): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1372): [NET] getaddrinfo-,err=8
D/libc    ( 1372): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1372): [NET] getaddrinfo-, 1
D/libc    ( 1372): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/GCM     ( 1372): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =7a25 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1190): nl80211: survey data missing!
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1190): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1190): nl80211: survey data missing!
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1190): environment dirty rate=0 [1][0][0]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 163
D/libc    (  365): [NET]res_nsend:resplen=79
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1372): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1372): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1372): [NET] getaddrinfo-,err=8
,D/libc    ( 1372): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1372): [NET] getaddrinfo-,err=8
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1372/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1372/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1372/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1372/10029)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4523): Called registerBroadcastReceiver twice.
,D/PMS     (  907): acquireWL(440d6590): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1372/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1372/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1372/10029)
,D/PMS     (  907): releaseWL(441e3340): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1372/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1372/10029)
,D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
,D/PMS     (  907): releaseWL(440d6590): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(440b0738): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1372/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1372/10029)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1372/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1372/10029)
,D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1372/10029)
,D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024763
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025060
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025162
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025167
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025177
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026639
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026663
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029304
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,D/PMS     (  907): releaseWL(440b0738): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4523/10027)
,D/PMS     (  907): releaseWL(436ff148): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/PMS     (  907): acquireWL(41cd9310): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4503 10154 null
,W/ContextImpl( 4503): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4503, uid=10154, userID:0
,I/MusicLeanback( 4503): Conditions not met for autocaching.
,I/MusicLeanback( 4503): Stop autocaching.
,W/ContextImpl( 4503): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/PMS     (  907): releaseWL(41cd9310): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1190): nl80211: survey data missing!
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1190): environment dirty rate=0 [8][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1190): nl80211: survey data missing!
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1190): environment dirty rate=0 [0][0][0]
,I/GAV2    ( 4603): Thread[GAThread,5,main]: No campaign data found.
,D/WifiStateMachine(  907): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,D/AutoSetting( 1507): service - handleMessage() stop self
,D/AutoSetting( 1507): service - onDestroy() END
,D/Process (  907): killProcessQuiet, pid=4282
,I/ActivityManager(  907): Killing 4282:com.htc.backup/1000 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/AutoSetting( 1507): service - handleMessage() quit looper
,I/ActivityManager(  907): Recipient 4282
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  907): killProcessQuiet, pid=4246
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4246:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4246
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1321): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1270): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/ActivityManager(  907): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4702 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
W/AccTypeManager( 1321): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1321): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/Launcher( 1270): Deferring update until onResume
,D/Launcher( 1270): waitUntilResume // bindAppsUpdated
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,W/SystemReader( 1254): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,E/ExternalAccountType( 1321): Unsupported attribute readOnly
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,D/PhoneApp( 1238): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4702): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4702): MmsConfig.loadMmsSettings
,W/dalvikvm( 4702): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4702): VFY: unable to resolve instance field 36
,W/dalvikvm( 4702): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4702): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  907): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
I/ActivityManager(  907): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4725 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4702, uid=10111, userID:0
,W/Settings( 4702): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4702, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4702, uid=10111, userID:0
,D/MessageFrequencyProvider( 4725): onCreate
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4702, uid=10111, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4702, uid=10111, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4702, uid=10111, userID:0
,D/MmsCustomizationProvider( 4725): query uri: content://htc-mms-customization/mms-ua/ua_string
,V/GetPrviateResource( 4725): GetPrviateResource
,V/GetPrviateResource( 4725): GetPrviateResource
D/PMS     (  907): acquireWL(426ebff0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4702 10111 null
,D/MmsCustomizationProvider( 4725): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/ActivityManager(  907): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 1342): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
I/[PluginManager]RegisterService( 1342): handle notify Blinkfeed plugin client changed
I/Babel   ( 4702): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4702): MmsConfig.loadFromDatabase
I/ActivityManager(  907): Resuming delayed broadcast
,I/IcingCorporaProvider( 2807): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
E/Babel   ( 4702): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4702): MmsConfig.loadFromResources
,D/Process (  907): killProcessQuiet, pid=3865
I/ActivityManager(  907): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/ActivityManager(  907): Killing 3865:com.htc.musicenhancer/u0a53 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
W/PackageManager(  907): Unable to load service info ResolveInfo{43696c18 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,E/Babel   ( 4702): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 4702): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/ActivityManager(  907): Recipient 3865
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  907): acquireWL(437d3f30): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(426ebff0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/Process (  907): killProcessQuiet, pid=4301
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ProviderInstaller( 4702): Installed default security provider GmsCore_OpenSSL
,D/MessageCustFlag( 4725): sense_version=6.0
,D/BTAccessoryUtil( 4725): createReceiver
,D/BTAccessoryUtil( 4725): registerReceiver return intent = null
,I/ActivityManager(  907): Killing 4301:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/MessageCustFlag( 4725): sku_id=99
,W/SystemReader( 4725): Cannot find message_ambs_application_id, use default value instead
,D/Messaging( 4725): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4725): networkCode: 
D/MessageCustFlag( 4725): sku_id=99
D/MmsConfig( 4725): SIE smsPri: null
,D/MmsConfig( 4725): networkCode: 
I/ActivityManager(  907): Recipient 4301
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/HtcTelephonyCapability( 4725): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 4725): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4725): getRATByHtcTelephonyCapability:1
W/SystemReader( 4725): Cannot find qct_8960_interface, use default value instead
,D/PMS     (  907): releaseWL(437d3f30): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.googlequicksearchbox/.GelStubAppWatcher
,D/PMS     (  907): acquireWL(437be118): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(437be118): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): acquireWL(434986f8): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/dalvikvm-heap( 4053): Grow heap (frag case) to 15.202MB for 1821008-byte allocation
D/PMS     (  907): acquireWL(426db0c8): PARTIAL_WAKE_LOCK  AsyncService 0x1 4053 10160 null
,D/PMS     (  907): releaseWL(434986f8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/dalvikvm-heap( 4053): Grow heap (frag case) to 16.937MB for 1821008-byte allocation
D/PMS     (  907): acquireWL(43c47468): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(426db0c8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  907): releaseWL(43c47468): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  907): acquireWL(437ea1c0): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(437ea1c0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,D/PMS     (  907): acquireWL(426879c8): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(426879c8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): acquireWL(42695430): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  907): start
,D/PackageBroadcastService( 2184): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2184): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  907): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/Icing   ( 2184): updateResources: need to parse f{com.google.android.gms}
,I/GCoreNlp( 1221): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  907): applying state to connected service
D/PMS     (  907): acquireWL(43c008a0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(43c008a0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2807): UpdateCorporaTask done [took 346 ms] updated apps [took 346 ms] 
I/ActivityManager(  907): Resuming delayed broadcast
,D/LocationProviderProxy(  907): applying state to connected service
D/PMS     (  907): acquireWL(4266c270): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(437298d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4266c270): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(437298d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43694f48): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43694f48): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1270): loadItems() com.htc.launcher.pageview.WidgetManager@41bc7bd0 +
,I/Prism.WidgetManager( 1270): onLoadItems() +
,I/Icing   ( 2184): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2184): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  907): releaseWL(42695430): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{4404f7f8 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,E/Prism.WidgetManager( 1270): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1270): onLoadItems() -
,I/Prism.ItemManager( 1270): loadItems() com.htc.launcher.pageview.WidgetManager@41bc7bd0 -
,D/PhoneApp( 1238): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1238): -- N1 =0
,D/PhoneApp( 1238): -- N2 =0
,D/PhoneApp( 1238): -- N3 =0
,D/Messaging( 4725): mNeedToUpdateDate2 start
,D/MmsConfig( 4725): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4725): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4725): 
D/MmsAsyncWorkHandler( 4725): HM tk = 20001
,D/ReportIndicatorCache( 4725): MSG_QUERY_REPORTS >>
D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 73
,D/MmsSmsV2Provider( 1238):  phoneType = -1
,D/MmsSmsV2Provider( 1238): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/SettingsManager( 4725): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41b445b0
,I/Messaging( 4725): mccmnc> 
D/DraftCache( 4725): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4725): [DraftCache/1] refresh
,D/MmsConfig( 4725): networkCode: 
,D/Messaging( 4725): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/MmsSmsV2Provider( 1238):  phoneType = -1
,D/MmsSmsV2Provider( 1238): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/PhoneStorageUtil( 4725): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4725): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4725): createReceiver
,D/Messaging( 4725): mNeedToUpdateDate2: false
,D/MessageCustFlag( 4725): sense_version=6.0
,D/Jerry   ( 4725): start to preload cursor >>>>>>>
,D/TelephUtils( 1238): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,V/MmsProvider( 1238): Update uri=content://mms, match=0
,V/MmsProvider( 1238): selection=st=129 AND m_type!=134
D/Messaging( 4725): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4725): TransactionService is going to be woken up.
,D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1238): sku_id=99
,V/TransactionService( 4725): 1-Creating TransactionService
V/TransactionService( 4725): onStartCommand: 1
,D/MmsSystemEventReceiver( 4725): unRegisterForConnectionStateChanges
V/TransactionService( 4725): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4725): Loading previous transactions.
,D/DraftCache( 4725): [DraftCache/472] rebuildCache
,D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/AccFlag ( 1238): device_type: 1
,D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/MmsSmsV2Provider( 1238):  phoneType = -1
D/TransactionService( 4725): Force set service start id to 1
V/TransactionService( 4725): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4725): unRegisterForConnectionStateChanges
,D/TransactionService( 4725): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4725): Destroying TransactionService
,V/TransactionService( 4725): 4-Handling incoming message: { when=0 what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/Jerry   ( 1238): URI_DRAFT
D/Messaging( 4725): ViewCache CreatePreload
,D/Messaging( 4725): ViewCache CreatePreloadOnlyMultipleOpsList
,D/DraftCache( 4725): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 4725): [DraftCache/472] rebuildCache time: 2
,D/Cust_MMSMS( 4725): _has_set_default_values_2=true
D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
D/MmsAsyncWorkHandler( 4725): 
D/MmsAsyncWorkHandler( 4725): HM tk = 20002
D/MmsSmsV2Provider( 1238):  phoneType = -1
,D/MmsSmsV2Provider( 1238): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
,D/AccFlag ( 1238): sku_id=99
,D/MsgPreferenceUtils( 4725): def_index: 0
,D/MsgPreferenceUtils( 4725): globalIndex = 1
,D/MsgPreferenceUtils( 4725): phone state: true,
D/MsgPreferenceUtils( 4725): sd state: false
D/MsgPreferenceUtils( 4725): vIndex = 0
D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/MmsSmsV2Provider( 1238):  phoneType = -1
,D/MmsSmsV2Provider( 1238): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/AccFlag ( 1238): sku_id=99
,D/Messaging( 4725): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,I/GAV4    ( 4702): Thread[GAThread,5,main]: No campaign data found.
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  907): acquireWL(42623f40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{42c54bd8: PendingIntentRecord{42755790 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=123562, Int=0
,D/PMS     (  907): acquireWL(440f8840): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{4372a448: PendingIntentRecord{424d0768 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450109376176, Int=1800000
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1372/10029)
D/PMS     (  907): acquireWL(42c7abc0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1190): nl80211: survey data missing!
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1190): environment dirty rate=0 [13][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(42623f40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(43c76a18): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(42c7abc0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1190): nl80211: survey data missing!
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1190): environment dirty rate=0 [0][0][0]
,I/EventLogService( 2184): Aggregate from 1450109359569 (log), 1450107576105 (data)
D/PMS     (  907): acquireWL(426f9f10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(426f9f10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(440f8840): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4266e560): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024763
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025060
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025162
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025167
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025177
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026639
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026663
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029304
,D/PMS     (  907): releaseWL(4266e560): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42eb3d60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1372/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024763
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025060
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025162
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025167
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025177
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026639
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026663
,E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1190): nl80211: survey data missing!
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1190): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029304
D/PMS     (  907): releaseWL(43c76a18): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024763
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025060
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025162
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025167
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025177
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026639
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026663
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029304
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1190): nl80211: survey data missing!
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1190): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(4319e218): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42c10d78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1221): Vacuum at: now=1450109376392 tag=VacuumService
,D/PMS     (  907): releaseWL(42eb3d60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4319e218): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43c388f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42c10d78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024763
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025060
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025162
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025167
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025172
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025177
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026639
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026663
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029304
,D/PMS     (  907): releaseWL(43c388f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4264b198): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024763
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025060
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025162
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025167
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025177
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026639
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026663
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029304
,D/PMS     (  907): releaseWL(4264b198): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43d276c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1372/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024763
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025060
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025162
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025167
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025177
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026639
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026663
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029304
,E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1190): nl80211: survey data missing!
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1190): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1190): nl80211: survey data missing!
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1190): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(43d276c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43d16318): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/PMS     (  907): releaseWL(43d16318): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(43a60940): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{425d1fb8: PendingIntentRecord{42706bf8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=134539, Int=0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1372/10029)
,D/PMS     (  907): releaseWL(43a60940): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42c81750): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1372/10029)
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1190): nl80211: survey data missing!
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1190): environment dirty rate=33 [3][1][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1190): nl80211: survey data missing!
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1190): environment dirty rate=0 [0][0][0]
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024763
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025060
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025162
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025167
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025177
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026639
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026663
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029304
,D/PMS     (  907): acquireWL(43670250): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43670250): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4426e3f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42c81750): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(44231938): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024763
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025060
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025162
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025167
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025177
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026639
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026663
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029304
,D/PMS     (  907): releaseWL(44231938): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
,E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1190): nl80211: survey data missing!
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1190): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1190): nl80211: survey data missing!
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1190): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1221): Scheduling Phenotype for one-off execution 4905 seconds from now (1450109387743)
,D/GetConfigurationSnapshotOperation( 1221): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1221): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1221): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1221): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1221): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1221): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1221): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  907): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
,E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1190): nl80211: survey data missing!
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1190): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1190): nl80211: survey data missing!
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1190): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
,W/dalvikvm( 1221): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1190): nl80211: survey data missing!
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1190): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1190): nl80211: survey data missing!
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1190): environment dirty rate=0 [0][0][0]
,D/libc    ( 1221): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1221): [NET] getaddrinfo-,err=8
D/libc    ( 1221): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1221): [NET] getaddrinfo-, 1
,D/libc    ( 1221): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =a4cd +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  365): [NET]res_nsend:resplen=87
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1221): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1221): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1221): [NET] getaddrinfo-,err=8
D/libc    ( 1221): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1221): [NET] getaddrinfo-,err=8
,D/PMS     (  907): releaseWL(4426e3f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43cb73c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024763
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025060
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025162
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025167
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025172
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025177
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026639
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026663
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029304
,D/PMS     (  907): releaseWL(43cb73c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(424a6cf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1372/10029)
I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1190): nl80211: survey data missing!
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1190): environment dirty rate=0 [8][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1190): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1190): nl80211: survey data missing!
E/wpa_supplicant( 1190): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1190): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024763
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025060
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025162
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025167
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025172
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025177
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026639
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026663
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029304
,D/PMS     (  907): releaseWL(424a6cf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1342): service - mHandler: update timezone
,D/AutoSetting( 1507): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1507): service - onCreate()
,D/AutoSetting( 1507): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1507): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/DotMatrix( 1558): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1558): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1507): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1507): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1507): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1507): service - mHandler: update timezone
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1507): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1507): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1507): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1507): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1558): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1558): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1115): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41ee2098 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.htc.htclocationservice 1 8 2 11
,D/AutoSetting( 1342): service - mHandler: update timezone
,D/AutoSetting( 1507): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1507): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
D/AutoSetting( 1507): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1507): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/DotMatrix( 1558): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1558): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1507): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1507): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1507): service - mHandler: update timezone
,D/AutoSetting( 1507): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1507): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1507): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1507): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1558): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1558): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1115): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41f06948 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.htc.htclocationservice 2 7 2 11
,D/AutoSetting( 1342): service - handleMessage() stop self
,D/AutoSetting( 1342): service - handleMessage() quit looper
,D/AutoSetting( 1342): service - onDestroy() END
,D/Process (  907): killProcessQuiet, pid=4333
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4333:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4333
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(425dc708): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41c514e8: PendingIntentRecord{41c4ab28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=147586, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(425dc708): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/ContactMessageStore( 1238): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1238): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{43c44830 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  907): acquireWL(4266e440): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
,D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(4266e440): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 1507): service - handleMessage() stop self
,D/AutoSetting( 1507): service - onDestroy() END
,D/AutoSetting( 1507): service - handleMessage() quit looper
,D/Process (  907): killProcessQuiet, pid=4349
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4349:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4349
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(425bcd38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10027}
,V/AlarmManager(  907): sending alarm PendingIntent{4272db28: PendingIntentRecord{4374d300 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=172954, Int=0
,D/PMS     (  907): releaseWL(425bcd38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1238): switchBindHtcMsgCursor: null
,D/PMS     (  907): acquireWL(41b2a0b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
I/BatteryService(  907): n_update end
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PMS     (  907): releaseWL(41b2a0b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(425745b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41c514e8: PendingIntentRecord{41c4ab28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=207585, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(425745b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42609ce8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42609ce8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): closing low battery warning: level=100
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(424ca500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(424ca500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  907): acquireWL(423d9748): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41c514e8: PendingIntentRecord{41c4ab28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=267586, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(423d9748): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(425a3098): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(425a3098): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(43363e18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(43363e18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(424ca878): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41c514e8: PendingIntentRecord{41c4ab28 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=327585, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(424ca878): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  907): killProcessQuiet, pid=3979
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3979:com.google.android.gm/u0a107 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3979
,D/PMS     (  907): acquireWL(4342fa30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4342fa30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1

```
