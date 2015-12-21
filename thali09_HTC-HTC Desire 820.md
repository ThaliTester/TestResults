#### Test 506502782e2cb10_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  908):    returned true
E/cutils-trace( 4408): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4408): ====startRecUseTime====
D/htc.customization.log.level( 4408):  is 
W/CustomizationLogLevel( 4408): Level value is invalid, use default level 2
D/CustomizationManager( 4408):  Read ACC file spent 0.050 (s)
D/CIDMapFileReader( 4408): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4408): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4408): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4408): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4408): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4408): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4408): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4408): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4408): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4408): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4408): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4408): Parsing tag category name = system
I/CustomizationCIDLoader( 4408): Parsing tag category name = application
I/CustomizationCIDLoader( 4408): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4408): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4408): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4408): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4408): Parsing tag category name = Settings
D/CustomizationManager( 4408):  Read CID file spent 0.088 (s)
D/CustomizationManager( 4408):  All configurations done spent 0.088 (s)
W/HtcNativeFlag( 4408): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4408): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4408): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4408): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
W/CpuWake (  908): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  908): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  908): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  908): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  908): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  908): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  908): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4408
D/PMS     (  908): acquireHCC(42fe2a40): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 908 1000 null
D/PMS     (  908): acquireHCC(42fe3578): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 908 1000 null
W/asset   (  908): Copying FileAsset 0x62b21450 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  908): @test_code: getHtcIntentFlag: 0 obj: 1123951592
I/FeedHostManager( 1270): [onPause]
I/FeedProviderManager( 1270): onPause
I/SocialFeedProvider( 1270): +onPause
I/SocialFeedProvider( 1270): -onPause
I/FeedHostManager( 1270): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c9c778
D/PMS     (  908): acquireWL(42fe5478): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 908 1000 null
I/ActivityManager(  908): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4419 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1270): [trimMemory] 20
W/asset   ( 4419): Copying FileAsset 0x5c7da428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4419): Binding Chromium to main looper Looper (main, tid 1) {41b60218}
I/LibraryLoader( 4419): Expected native library version number "",actual native library version number ""
I/chromium( 4419): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4419): Initializing chromium process, renderers=0
W/System.err(  908): java.lang.Throwable: stack dump
D/BluetoothManagerService(  908): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  908): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@41f67018:true
W/System.err(  908): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  908): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  908): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  908): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  908): 	at dalvik.system.NativeStart.run(Native Method)
D/PMS     (  908): acquireWL(42fed120): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  908): acquireWL(42fed770): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  908): releaseWL(42fed120): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothAdapter( 4419): 1102535760: getState(). Returning 12
I/Adreno-EGL( 4419): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4419): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4419): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4419): Local Branch: 
I/Adreno-EGL( 4419): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4419): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4419):                  aa63bbd948f41d15fc72f585e
,W/chromium( 4419): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/dalvikvm( 4419): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
,W/dalvikvm( 4419): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,W/dalvikvm( 4419): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4419): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 4419): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,W/dalvikvm( 4419): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4419): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,W/dalvikvm( 4419): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/SystemWebViewEngine( 4419): CordovaWebView is running on device made by: HTC
,W/AwContents( 4419): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  908): Disable input method client, pid=1270
,I/ActivityManager(  908): Displayed com.test.thalitest/.MainActivity: +355ms
W/ResourceType( 4419): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4419): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41ba7300, mServedView=org.apache.cordova.engine.SystemWebView{41b6cf68 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1209): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1209): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,W/AwContents( 4419): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  908): Enable input method client, pid=4419
D/PMS     (  908): releaseWL(42fe5478): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4419): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4419): JniHelper::setJavaVM(0x41631048), pthread_self() = 1662947600
,D/JX-Cordova( 4419): jxcore cordova android initializing
,I/dalvikvm-heap( 4419): Grow heap (frag case) to 11.600MB for 144892-byte allocation
,I/dalvikvm-heap( 4419): Grow heap (frag case) to 11.716MB for 217334-byte allocation
,I/dalvikvm-heap( 4419): Grow heap (frag case) to 11.893MB for 325996-byte allocation
,I/dalvikvm-heap( 4419): Grow heap (frag case) to 12.166MB for 488990-byte allocation
,I/dalvikvm-heap( 4419): Grow heap (frag case) to 12.573MB for 733480-byte allocation
,W/PluginManager( 4419): THREAD WARNING: exec() call to JXcore.isReady blocked the main thread for 23ms. Plugin should use CordovaInterface.getThreadPool().
,I/dalvikvm-heap( 4419): Grow heap (frag case) to 14.020MB for 1650320-byte allocation
,I/dalvikvm-heap( 4419): Grow heap (frag case) to 15.438MB for 2475476-byte allocation
,I/dalvikvm-heap( 4419): Grow heap (frag case) to 17.469MB for 3713210-byte allocation
,W/CpuWake (  908): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  908): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  908): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  908): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  908): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  908): <<release mCpuPerf_Freq wakelock
D/PMS     (  908): releaseHCC(42fe2a40): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  908): releaseHCC(42fe3578): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,D/WifiDataStallTracker(  908): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  908): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/PMS     (  908): acquireWL(442185a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
V/AlarmManager(  908): sending alarm PendingIntent{41fcc7d8: PendingIntentRecord{42606218 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=103635, Int=0
D/WifiDataStallTracker(  908): updateDataStallInfo: mDataStallTxRxSum={txSum=188 rxSum=187} preTxRxSum={txSum=188 rxSum=187}
D/WifiDataStallTracker(  908): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  908): onDataStallAlarm: tag=19547 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  908): startDataStallAlarm: tag=19548 delay=15s
D/PMS     (  908): releaseWL(442185a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/jxcore-log( 4419): Initializing JXcore engine
,W/jxcore-log( 4419): JXcore engine is ready
,W/jxcore-log( 4419): Starting JXcore engine
,W/jxcore-log( 4419): Platform android
W/jxcore-log( 4419): 
,W/jxcore-log( 4419): Process ARCH arm
W/jxcore-log( 4419): 
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 96
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,I/jxcore-log( 4419): JXcore Cordova bridge is ready!
I/jxcore-log( 4419): 
,W/jxcore-log( 4419): JXcore engine is started
,I/Choreographer( 4419): Skipped 140 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4419): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,D/PMS     (  908): releaseWL(42fed770): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/PMS     (  908): Going to sleep due to screen timeout...
,I/SensorManager(  908): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@422803c0
,W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  908): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 2
,W/SensorService(  908): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@422803c0, eanble = 0, strlen(mName) = 59
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  908): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41cea9d0
W/SensorService(  908): Listener[1] = com.htc.smartdim.sensor_eye@427debd0
,W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  908): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  908): Couldn't get kernel wake lock stats
V/LightsService(  908): setLight #2: color=#0
D/qdlights(  908): set_light_buttons_func: on=0 brightness=0
V/LightsService(  908): setLight #0: color=#0
,W/PMS     (  908): mWirelessDisplayManager is null
D/WirelessDisplayService(  908): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  908): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,I/jxcore-log( 4419): Toggling radios to true
I/jxcore-log( 4419): 
,D/BluetoothAdapter( 4419): enable(): BT is already enabled..!
,D/WifiManager( 4419): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
W/HtcDLNAServiceManager(  908): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  908): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  908): Settings:Agentvalue: 2
W/Settings:Agent(  908): >> traceCallingStack()
W/Settings:Agent(  908): Process.myPid(): 908
W/Settings:Agent(  908): Process.myTid(): 1384
W/Settings:Agent(  908): Process.myUid(): 1000
W/Settings:Agent(  908): 
W/Settings:Agent(  908): 
,W/System.err(  908): java.lang.Throwable: stack dump
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
W/System.err(  908): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  908): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  908): 
W/Settings:Agent(  908): << traceCallingStack(): 1(ms)
,D/WifiManager( 4419): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiManager( 4419): reconnect: Base Package Name=com.test.thalitest, uid=10389
,D/WifiNative-wlan0(  908): doBoolean: DISCONNECT
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): TDLS: Tear down peers
,I/wpa_supplicant( 1183): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4419): Radios toggled
I/jxcore-log( 4419): 
,D/BluetoothManagerService(  908): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiService(  908): New client listening to asynchronous messages
D/WifiService(  908): setWifiEnabled: true pid=4419, uid=10389
E/WifiService(  908): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  908): isSprintWifiRestricted(): false
I/WifiService(  908): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  908): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
I/jxcore-log( 4419): Got Device Bluetooth address: B4:CE:F6:AB:A4:6A
I/jxcore-log( 4419): 
I/jxcore-log( 4419): Perf Test app loaded loaded
I/jxcore-log( 4419): 
I/Choreographer( 4419): Skipped 78 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 4419): check test folder
I/jxcore-log( 4419): 
,I/jxcore-log( 4419): found test : ./testFindPeers.js
I/jxcore-log( 4419): 
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1183): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1183): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1183): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  908): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  908): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  908): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  908): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1183): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1183): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1183): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1183): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1183): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb74bbbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
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
D/wpa_supplicant( 1183): EAPOL: External notification - EA,P success=0
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1183): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1183): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1183): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1183): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1183): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1183): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1183): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1183): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1183): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1183): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1183): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1183): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0(  908):    returned true
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiPerfLock(  908): release()
D/WifiStateMachine(  908): PerfLock released for exiting ConnectedState
D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/Tethering(  908): interfaceLinkStateChanged wlan0, false
D/Tethering(  908): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  908): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/Tethering(  908): [isWifi] getHotspotEnabled: false
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1183): Power_Mode_Type mode = 0
I/wpa_supplicant( 1183): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 61
D/ConnectivityService(  908): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
,D/PMS     (  908): acquireWL(43034ca0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 908 1000 null
D/Tethering(  908): interfaceLinkStateChanged wlan0, false
D/Tethering(  908): interfaceStatusChanged wlan0, false
D/Tethering(  908): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  908):    returned true
D/WifiNative-wlan0(  908): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  908):    returned true
,I/jxcore-log( 4419): found test : ./testSendData.js
I/jxcore-log( 4419): 
D/libc    (  908): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/DhcpStateMachine(  908): [RunningState] Stop DHCP
D/WifiP2pService(  908): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  908): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023854
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023972
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024053
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024058
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024060
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024064
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025612
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025629
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028563
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029886
D/WifiStateMachine(  908): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  908): doBoolean: RECONNECT
D/WifiDataStallTracker(  908): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  908): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  908): stopDataStallAlarm: current tag=19548 mDataStallAlarmIntent=PendingIntent{425b7730: PendingIntentRecord{42606218 android broadcastIntent}}
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): Fast associate: Old scan results
I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
,D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiNative-wlan0(  908):    returned true
,D/WifiStateMachine(  908): Enter handleNetworkDisconnect
,D/WifiNative-wlan0(  908): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1183): Power_Mode_Type mode = 0
I/wpa_supplicant( 1183): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 61
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,D/WifiNative-wlan0(  908):    returned true
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023854
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023972
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024053
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024058
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024060
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024064
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025612
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025629
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028563
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029886
D/WifiStateTracker(  908): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  908): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  908): Provision feature enable=false
D/WifiP2pService(  908): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  908): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  908):    returned true
D/WISPrService( 3824): >>>>>WISPrService start isConnected = false<<<<<
,D/SurfaceControl(  908): Excessive delay in blankDisplay() while turning screen off: 314ms
D/UsbnetStateTracker(  908): isAvailable+-
D/UsbnetStateTracker(  908): reconnect
D/UsbnetStateTracker(  908): isAvailable+-
D/libc    (  908): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  908): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  908): Exit handleNetworkDisconnect
D/WifiP2pService(  908): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  908): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/PMS     (  908): nativeSetInteractive:false
D/PMS     (  908): nativeSetInteractive:false done
D/PMS     (  908): nativeSetAutoSuspend:true
D/MDST    (  908): default: reconnect()
D/MDST    (  908): default: setTeardownRequested(false)
D/MDST    (  908): default: setEnableApn apnType =default , enable=true
D/PMS     (  908): nativeSetAutoSuspend:true done
D/WifiService(  908): New client listening to asynchronous messages
D/WISPrService( 3824): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  908): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
I/InputManager(  908): Cancel all due to getting PMS screen off broadcast
D/ConnectivityService(  908): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  908): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  908): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/HABCtrl (  908): TPE algorithm. remove timeout.
D/PMS     (  908): OOBE c monitor 11
W/ConnectivityService(  908): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  908): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/NfcService( 1249): ScreenObserver: OFF
D/NfcService( 1249): applyRouting - 0
D/WifiDataStallTracker(  908): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  908): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
I/jxcore-log( 4419): found test : ./testSendData2.js
I/jxcore-log( 4419): 
D/NfcService( 1249): applyRouting -2
D/ConnectivityService(  908): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/PMS     (  908): acquireWL(430471a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
D/PMS     (  908): releaseWL(430471a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
W/ConnectivityService(  908): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  908): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
I/InputMethodManagerService(  908): screenObserver, isScreenOn=false
D/WifiStateTracker(  908): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/PMS     (  908): acquireWL(4304ab88): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1249 1027 null
D/WISPrService( 3824): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 3824): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  908): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,V/KeyguardServiceDelegate(  908): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@4304c350)
,E/jxcore  ( 4419): Error!: missing ) after argument list
E/jxcore  ( 4419): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
,V/NativeCrypto( 1367): Read error: ssl=0x66199330: I/O error during system call, Connection timed out
I/InputMethodManagerService(  908): Disable input method client, pid=4419
D/PMS     (  908): releaseWL(4304ab88): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  908): wakingUp
W/ConnectivityService(  908): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  908): handleConnectivityChange: resetting
D/ConnectivityService(  908): resetConnections(wlan0, 3)
D/PMS     (  908): acquireWL(4304d608): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
V/KeyguardServiceDelegate(  908): **** SHOWN CALLED ****
,V/NativeCrypto( 1367): SSL shutdown failed: ssl=0x66199330: I/O error during system call, Broken pipe
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:0
,I/chromium( 4419): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/WindowManager(  908): No lock screen! windowToken=null
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMN     (  908): onScreenOn
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023854
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023972
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024053
D/libc    (  363): [NET] entry_id:3   entry:0xb702c590  removed 
D/libc    (  363): [NET] entry_id:8   entry:0xb702c368  removed 
D/libc    (  363): [NET] entry_id:6   entry:0xb702c2b8  removed 
D/libc    (  363): [NET] entry_id:5   entry:0xb7027c20  removed 
D/libc    (  363): [NET] entry_id:7   entry:0xb702c1c8  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb7030f70  removed 
D/libc    (  363): [NET] entry_id:4   entry:0xb7030e40  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb702c458  removed 
D/libc    (  363): [NET] entry_id:9   entry:0xb7027af8  removed 
D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1581): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1581): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1581): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/WirelessDisplayService(  908): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  908): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  908): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
W/ResourceType( 4419): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4419): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41b6cf68 VFEDH.C. .F...... 0,0-720,1134 #64}
D/ConnectivityService(  908): flush DNS cache for net 1(wlan0)
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024058
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024060
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024064
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025612
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025629
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028563
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029886
D/Nat464Xlat(  908): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  908): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1367/10029)
D/ConnectivityService(  908): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  908): acquireWL(43056418): PARTIAL_WAKE_LOCK  NetworkStats 0x1 908 1000 null
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  908): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  908): reportInetCondition for net -1, percentage: 0 by  (1367/10029)
D/MtpService( 2344): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/NfcService( 1249): applyRouting - 0
,D/MtpService( 2344): [MTP][onReceive]-
,D/NfcService( 1249): applyRouting -2
I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:0
,D/AutoSetting( 1339): receiver - intent: android.intent.action.USER_PRESENT
D/WirelessDisplayService(  908): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  908): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1367/10029)
D/PMS     (  908): acquireWL(43060938): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1249 1027 null
D/PMS     (  908): releaseWL(4304d608): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(43060938): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1367/10029)
D/WirelessDisplayService(  908): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  908): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  908): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/TetherSettings( 3824): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3824): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3824): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3824): Cust_ConnectToPC   : spcsc>false
D/        ( 3824): Cust_ConnectToPC   : IPT>true
D/        ( 3824): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3824): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3824): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3824): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3824): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
V/NotificationService(  908): batLight: Full, plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c800
D/qdlights(  908): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/PMS     (  908): releaseWL(43056418): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/WifiStateMachine(  908): startScan Pid: 908 Uid 1000
D/WifiNative-wlan0(  908): doBoolean: SCAN
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1183): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiDataStallTracker(  908): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiNative-wlan0(  908): doBoolean: SET_SCREEN_ON 1
,D/WifiNative-wlan0(  908):    returned false
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  908): doBoolean: SET pno 0
I/wpa_supplicant( 1183): SET_SCREEN_ON:On
I/wpa_supplicant( 1183): htc_wext_set_keepalive +
I/wpa_supplicant( 1183): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1183): getPrivFuncNum +	
I/wpa_supplicant( 1183): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1183): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1183): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1183): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1183): htc_wext_set_TX_TRACKING - ret = 0
,D/WifiNative-wlan0(  908):    returned true
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): CTRL_IFACE SET 'pno'='0'
,I/wpa_supplicant( 1183): wpa_supplicant_scan enter
D/AutoSetting( 1339): service - onCreate()
,D/WifiNative-wlan0(  908):    returned true
D/ConnectivityService(  908): mActiveDefaultNetwork: -1
D/ConnectivityService(  908): handleInetConditionChange: no active default network - ignore
D/BatSI   (  908): WIFI scan started for: 450a0300 uid:1000
D/AlarmManager(  908): ACTION_SCREEN_ON
I/AlarmManager(  908): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  908): [AlarmQueuing] done recovering
I/AlarmManager(  908): [AlarmQueuing] recover EPS screen off blocked alarms
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1367/10029)
,I/AlarmManager(  908): [AlarmQueuing] done EPS screen off alarm recovering
,I/PSReceiver( 3824): onReceive:android.intent.action.USER_PRESENT
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,I/ClockThread( 1117): stop update clock
D/AutoSetting( 1339): service - AddressCache: using context: com.htc.Weather
I/SmartNS_PSService( 3824): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3824): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3824):  defaultType:0
,D/AutoSetting( 1339): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/LocationManagerService(  908): request 42628d08 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/LocationManagerService(  908): provider request: passive ProviderRequest[ON interval=0]
W/ContextImpl( 3824): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
V/NotificationService(  908): batLight: Full, plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c800
D/qdlights(  908): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/WirelessDisplayService(  908): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/NetworkPolicy(  908): updateScreenOn: false
,I/ActivityManager(  908): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4484 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1581): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  908): acquireWL(4307ffe0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(4307ffe0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): acquireWL(43080c58): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(43080c58): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1775): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1775): onScreenOn: 1450736054423
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1775): onScreenOn: 1450736054423
W/ContextImpl( 4484): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,I/SensorManager(  908): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41cea9d0
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  908): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 2
W/SensorService(  908): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41cea9d0, eanble = 0, strlen(mName) = 91
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  908): Listener[0] = com.htc.smartdim.sensor_eye@427debd0
,W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/SmartSyncUtils( 4484): isEpsOn(), nState = 0
D/PMN     (  908): goingToSleep
D/PMS     (  908): acquireWL(43083e88): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4484 1000 null
D/PMS     (  908): acquireWL(43084700): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 908 1000 null
,D/PMS     (  908): releaseWL(43083e88): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/AlarmManager(  908): ACTION_SCREEN_OFF
I/AlarmManager(  908): [AlarmQueuing] screen off now: 
I/AlarmManager(  908): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  908): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  908): stopDataStallAlarm: current tag=19549 mDataStallAlarmIntent=null
D/WifiNative-wlan0(  908): doBoolean: SET pno 1
,D/WifiNative-wlan0(  908): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): CTRL_IFACE SET 'pno'='1'
I/AlarmManager(  908): [AlarmQueuing] wifi connection: true
D/PMS     (  908): acquireWL(43089680): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 908 1000 null
D/PMS     (  908): releaseWL(43084700): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1183): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
D/wpa_supplicant( 1183): BSS: last_scan_res_used=1/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=5 entropy=0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 3
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 1
I/wpa_supplicant( 1183): wpa_s->is_screen_on 1
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): selected network = 1
D/wpa_supplicant( 1183): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb74bd4e8  current_ssid=0x0
D/wpa_supplicant( 1183): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1183): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1183): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1183): check if in concurrent case
,I/wpa_supplicant( 1183): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiNative-wlan0(  908):    returned true
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
,D/SmartSyncUtils( 4484): getMobilePolicyEnabled, result = true
D/wpa_supplicant( 1183): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1183): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1183): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1183): RSN: PMKSA cache search - network_ctx=0xb74bd4e8 try_opportunistic=0
D/wpa_supplicant( 1183): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1183): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1183): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1183): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1183): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1183): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1183): nl80211: Unsubscribe mgmt frames handle 0xb74bc718 (mode change)
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1183): nl80211: Subscribe to mgmt frames with non-AP handle 0xb74bc718
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb74bc718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb74bc718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb74bc718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb74bc718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb74bc718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb74bc718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb74bc718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb74bc718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb74bc718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb74bc718
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
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1183): SET_SCREEN_ON:Off
I/wpa_supplicant( 1183): htc_wext_set_keepalive +
I/wpa_supplicant( 1183): htc_wext_set_k,eepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1183): getPrivFuncNum +	
I/wpa_supplicant( 1183): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1183): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1183): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 1183): get_ip_address source addr = 02000000
I/wpa_supplicant( 1183): htc_wext_set_keepalive gateway addr = 00000000
I/wpa_supplicant( 1183): htc_wext_set_keepalive - ret = 0
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  908):    returned true
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023854
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023972
D/WifiNative-wlan0(  908): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  908):    returned true
D/WifiNative-wlan0(  908): doBoolean: SET pno 1
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): CTRL_IFACE SET 'pno'='1'
D/WifiNative-wlan0(  908):    returned true
D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  908): doString: LIST_DONGLES
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024053
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024058
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024060
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024064
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025612
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025629
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028563
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029886
W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  908): releaseWL(43089680): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
V/SRS_Proc(  371): ParamSet string: screen_state=off
D/WifiNative-wlan0(  908): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1183): reply (238) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-48
I/wpa_supplicant( 1183): tsf=0000000021669999
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=1
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-57
I/wpa_supplicant( 1183): tsf=0000000106303022
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ####
D/WirelessDisplayService(  908): getDiscoveryDongleList
D/WifiStateMachine(  908): == begin of scan result ==
D/WifiStateMachine(  908): == (2) end of scan result ==
D/WirelessDisplayService(  908): getDiscoveryDongleList
D/WifiManager( 1221): getScanResults enter 
D/WifiStateMachine(  908): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 21669999, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/WifiStateMachine(  908): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 106303022, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  908): add 2 to mScanResults
D/BatSI   (  908): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  908): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/NetworkPolicy(  908): updateScreenOn: false
D/WifiStateMachine(  908): == begin of scan result ==
D/WifiStateMachine(  908): == (2) end of scan result ==
,D/ContactMessageStore( 1236): start background delete task...
D/ContactMessageStore( 1236): size: 0 , 0
D/ContactMessageStore( 1236): Background delete complete
W/ContextImpl( 4484): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/SmartSyncUtils( 4484): isEpsOn(), nState = 0
D/SmartSyncUtils( 4484): getMobilePolicyEnabled, result = true
D/SmartSyncUtils( 4484): isEpsOn(), nState = 0
I/SensorManager(  908): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@427debd0
D/WifiService(  908): New client listening to asynchronous messages
W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  908): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 1
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@427debd0, eanble = 0, strlen(mName) = 36
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  908): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 0
W/SensorService(  908): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@427debd0, eanble = 0, strlen(mName) = 36
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  908): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@427debd0
E/ActivityThread(  908): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@427df118 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  908): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@427df118 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/DotMatrix( 1581): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1581): [EventService] getTotalRam: 1873 Mb
D/PMS     (  908): acquireWL(430aaa78): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1775): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1775): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1775): disableBatteryAlarm
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1775): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1775): onScreenOff
D/PMS     (  908): releaseWL(430aaa78): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): acquireWL(430ab830): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(430ab830): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/wpa_supplicant( 1183): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1183): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1183): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1183): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1183): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1183): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1183): nl80211: if_removed already cleared - ignore event
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
D/wpa_supplicant( 1183): Add randomness: count=6 entropy=1
I/wpa_supplicant( 1183): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1183): TDLS: Remove peers on association
D/wpa_supplicant( 1183): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
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
D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
I/wpa_supplicant( 1183): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1183): State: ASSOCIATED -> 4WAY_HANDSHAKE
,D/wpa_supplicant( 1183): Get randomness: len=32 entropy=2
D/Tethering(  908): interfaceLinkStateChanged wlan0, false
D/WifiMonitor(  908): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  908): interfaceStatusChanged wlan0, false
D/WifiMonitor(  908): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/Tethering(  908): [isWifi] getHotspotEnabled: false
D/HTCRequest(  908): WifiMonitor:getFreqFromEventString() 2412
D/Tethering(  908): interfaceLinkStateChanged wlan0, true
D/HTCRequest(  908): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/Tethering(  908): interfaceStatusChanged wlan0, true
D/Tethering(  908): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  908): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  908): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  908): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  908): Enter handleAssociatedWithEvent
D/WifiStateMachine(  908): Associated
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/AutoSetting( 1339): service - mHandler: cancel location update
D/AutoSetting( 1339): service -           changes count: 0
,I/wpa_supplicant( 1183): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb74bc9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1183):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1183): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1183): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6ed9b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1183):    broadcast key
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1183): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1183): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1183): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1183): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
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
D/WifiStateMachine(  908): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  908): Exit handleAssociatedWithEvent
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1183): EAPOL authentication completed successfully
I/wpa_supplicant( 1183): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1183): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1183): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1183): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiStateMachine(  908): BSSID was changed, update WiFi database
D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiApDatabaseHandler(  908): updateConnectedAP...
,D/WifiMonitor(  908): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/Tethering(  908): interfaceLinkStateChanged wlan0, true
D/Tethering(  908): interfaceStatusChanged wlan0, true
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/Tethering(  908): [isWifi] getHotspotEnabled: false
,D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/WifiApDatabaseHandler(  908): updateConnectedAP...
,D/WifiStateMachine(  908): WifiApDatabaseHandler, WiFi AP database Inserting ..,
D/WifiApDatabaseHandler(  908): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  908): This record is existed, only update it...
,D/WifiStateMachine(  908): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  908): updateConnectedAP...,
,D/WifiStateMachine(  908): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  908): updateConnectedAP...
,D/WifiStateMachine(  908): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  908): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  908): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  908): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  908): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiApDatabaseHandler(  908): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  908): This record is existed, only update it...
D/WifiStateTracker(  908): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,D/WifiStateMachine(  908): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  908): updateConnectedAP...
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  908): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  908): Provision feature enable=false
D/ConnectivityService(  908): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WifiStateMachine(  908): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  908): updateConnectedAP...
,D/WISPrService( 3824): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3824): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiNative-wlan0(  908): doBoolean: SET pno 0
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1183): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/WifiNative-wlan0(  908):    returned true
,D/DhcpStateMachine(  908): [StoppedState] Start DHCP
,D/WifiStateMachine(  908): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/WifiNative-wlan0(  908): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  908):    returned true
D/WifiNative-wlan0(  908): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  908):    returned true
,D/WifiNative-wlan0(  908): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1183): Power_Mode_Type mode = 1
I/wpa_supplicant( 1183): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  908):    returned true
,D/WifiNative-wlan0(  908): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  908):    returned null
E/WifiStateMachine(  908): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  908): doString: DRIVER WLS_BATCHING STOP
D/WifiStateMachine(  908): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  908): acquireWL(430c77f0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 908 1000 null
,D/WifiStateMachine(  908): handlePreDhcpSetup mBluetoothConnectionActive: false
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/wpa_supplicant( 1183): nl80211: Event message available
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/wpa_supplicant( 1183): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1183): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
,D/WifiNative-wlan0(  908):    returned null
D/WifiP2pService(  908): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42536f68 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  908): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42536f68 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
,D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  908): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  908): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  908): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4517 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by  (908/1000)
,D/GpsLocationProvider(  908): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  908): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTING DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  908): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  908): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  908): acquireWL(430d01c0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 908 1000 null
D/PMS     (  908): releaseWL(430d01c0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.backuptransport (1593/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2190/10029)
D/CaptivePortalTracker(  908): DelayedCaptiveCheckState
D/CaptivePortalTracker(  908): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  908): NoActiveNetworkState
,I/ConnectivityHelper( 1270): [onReceive] WIFI(1): CONNECTING
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.docs (4271/10100)
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.htc.launcher (1270/10076)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
D/Tethering(  908): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  908): bSetPropertyMultiRAB:false
,D/Tethering(  908): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  908): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
,I/Tethering(  908): ipv4Default null
,I/Tethering(  908): No IPv4 upstream interface, giving up.
,D/Tethering(  908): TetherMasterSM: InitialState processMessage what=3
D/htcCheckinService(  908): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  908): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2190/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.docs (4271/10100)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2190/10029)
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023854
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023972
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024053
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024058
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024060
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024064
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025612
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025629
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028563
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029886
,I/MusicStore( 4517): Database version: 95
,W/ContextImpl( 4517): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4517): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4517): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4517): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4517): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4517, uid=10154, userID:0
,D/WifiDisplayAdapter(  908): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  908):     Client/Owner: Client
D/WifiDisplayAdapter(  908):     GroupId: 
D/WifiDisplayAdapter(  908):     Passphrase: 
D/WifiDisplayAdapter(  908):     SessionId: 0
D/WifiDisplayAdapter(  908):     IP Address: }
,D/MediaRouterService(  908): Client com.google.android.music (pid 4517): Registered
,D/WifiDisplayAdapter(  908): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  908):     Client/Owner: Client
D/WifiDisplayAdapter(  908):     GroupId: 
D/WifiDisplayAdapter(  908):     Passphrase: 
D/WifiDisplayAdapter(  908):     SessionId: 0
D/WifiDisplayAdapter(  908):     IP Address: }
,I/MediaRouter( 4517): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (2344/10021)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.music (4517/10154)
,I/ActivityManager(  908): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4537 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4517): getSelectedRoute
D/wpa_supplicant( 1183): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1183): EAPOL: disable timer tick
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.google.android.music (4517/10154)
,I/NetworkMonitor( 4517): type=WIFI subType= reason=null isConnected=false
,D/ACRA    ( 4537): ACRA is enabled for com.facebook.katana, intializing...
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4517, uid=10154, userID:0
,D/Process (  908): killProcessQuiet, pid=3861
,D/ACRA    ( 4537): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4537): Looking for error files in /data/data/com.facebook.katana/app_minidumps
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/PMS     (  908): acquireWL(43bcca08): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
,D/PMS     (  908): releaseWL(43bcca08): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  908): Killing 3861:com.htc.mediamanager/u0a34 (adj 15): empty #17
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,W/SystemClassLoaderAdder( 4537): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4537): Preparing secondary program dexes.
V/DexLibLoader( 4537): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4537): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4537): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4537): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4537): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4537): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4537): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4537): Dex already copied
D/OdexVerifier( 4537): Odex verification is skipped.
,V/DexLibLoader( 4537): Creating class loader
,V/DexLibLoader( 4537): Finished creating class loader
V/DexLibLoader( 4537): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4537): Dex already copied
D/OdexVerifier( 4537): Odex verification is skipped.
,V/DexLibLoader( 4537): Creating class loader
,V/DexLibLoader( 4537): Finished creating class loader
V/DexLibLoader( 4537): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4537): Dex already copied
D/OdexVerifier( 4537): Odex verification is skipped.
,V/DexLibLoader( 4537): Creating class loader
,V/DexLibLoader( 4537): Finished creating class loader
V/DexLibLoader( 4537): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4537): Dex already copied
D/OdexVerifier( 4537): Odex verification is skipped.
,V/DexLibLoader( 4537): Creating class loader
,V/DexLibLoader( 4537): Finished creating class loader
,V/DexLibLoader( 4537): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4537): DexLibLoader.ensureDexLoaded took 22 ms
,I/ActivityManager(  908): Recipient 3861
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/libc    (  908): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  908): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/libc    (  908): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/libc    (  908): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/libc    (  908): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  908): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  908):    returned true
D/WifiNative-wlan0(  908): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1183): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1183): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,W/dalvikvm( 4537): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4537): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  908):    returned true
D/WifiNative-wlan0(  908): doBoolean: DRIVER BTCOEXMODE 2
W/dalvikvm( 4537): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  908):    returned true,
D/WifiStateMachine(  908): handlePostDhcpSetup release wake lock during DHCP
W/dalvikvm( 4537): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  908): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  908): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  908): releaseWL(430c77f0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null,
W/dalvikvm( 4537): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 4537): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 4537): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;,
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=33 [3][1][0]
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
,D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED -1 -> 3
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,D/WifiStateMachine(  908): gateway: /192.168.1.1
,D/WifiNative-wlan0(  908): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1183): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1183): htc_wext_set_keepalive +
I/wpa_supplicant( 1183): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1183): getPrivFuncNum +	
I/wpa_supplicant( 1183): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1183): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1183): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1183): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1183): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  908):    returned true
D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  908): VerifyingLinkState enter
D/WifiStateMachine(  908): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  908): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  908): VerifyingLinkState: enableIpv6
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  908): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -57, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  908): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  908): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  908): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,D/WifiWatchdogStateMachine(  908): WAN detection
,D/WISPrService( 3824): >>>>>WISPrService start isConnected = true<<<<<
V/NetworkPolicy(  908): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/ConnectivityService(  908): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  908): Provision feature enable=false
D/ConnectivityService(  908): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  908): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  908): default: teardown()
D/MDST    (  908): default: setTeardownRequested(true)
D/MDST    (  908): default: setEnableApn apnType =default , enable=false
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED connected
D/MDST    (  908): default: setTeardownRequested(true)
D/ConnectivityService(  908): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/libc    (  908): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [1][0][0]
,I/wpa_supplicant( 1183): Change stage from stage0 to stage3
,D/WifiStateMachine(  908): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  908): syncGetConfiguredNetworks
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/ConnectivityService(  908): Unexpected mtu value: android.net.wifi.WifiStateTracker@424df8e0
D/ConnectivityService(  908): handleConnectivityChange: netType=1 doReset=false resetMask=0
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
D/ConnectivityService(  908): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  908): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  908): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  908): handleConnectivityChange: resetting
D/Nat464Xlat(  908): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  908): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  908): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  908): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  908): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  908): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  908): acquireWL(43695728): PARTIAL_WAKE_LOCK  NetworkStats 0x1 908 1000 null
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by  (908/1000)
D/WirelessDisplayService(  908): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  908):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,I/QuickSettingWifi( 1117): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/PMS     (  908): releaseWL(43695728): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
I/logwrapper(  363): /system/bin/ip terminated by exit(254)
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  908): mActiveDefaultNetwork: WIFI
,W/dalvikvm( 4537): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4537): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4537): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4537): Verify
,D/WifiService(  908): New client listening to asynchronous messages
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4537/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4537): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4537): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4537): Grow heap (frag case) to 9.509MB for 73240-byte allocation
,D/Process (  908): killProcessQuiet, pid=4207
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  908): Killing 4207:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4207
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  908): Client connection lost with reason: 4
,D/AutoSetting( 1339): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  908): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4588 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.sense.hsp (1339/10055)
D/AutoSetting( 1339): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1339): service - onStartCommand() screen is off, don't request location
,D/AutoSetting( 1339): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1339): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.sense.hsp (1339/10055)
,W/fb4a(:<default>):UserScope( 4537): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4537): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
D/MobileConnectivityChangeReceiver( 4588): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4588): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4588): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4588): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,W/fb4a(:<default>):UserScope( 4537): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,I/ActivityManager(  908): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4602 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  908): killProcessQuiet, pid=4098
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Killing 4098:com.google.android.talk/u0a111 (adj 15): empty #17
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.setupwizard (4588/10079)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.setupwizard (4588/10079)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.setupwizard (4588/10079)
,D/PMS     (  908): acquireWL(43768510): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2190 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(432ac318): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2190 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2190): Checkin interval check for package: unspecified last checkin: 1450736004473 min interval config: 0 actual interval: 52786
D/PMS     (  908): releaseWL(43768510): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I/CheckinService( 2190): Checking schedule, now: 1450736057264 next: 1450736034443
,I/CheckinService( 2190): active receiver: enabled
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2190, uid=10029, userID:0
,I/CheckinService( 2190): Preparing to send checkin request
,I/EventLogService( 2190): Accumulating logs since 1450736000003
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2190/10029)
,E/dalvikvm( 4537): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4537): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4537): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4537): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4537): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4537): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4537): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4537): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4537): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4537): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4537): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4537): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4537): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4537): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4537): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4537): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4537): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125),
,W/dalvikvm( 4537): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/CheckinRequestBuilder( 2190): Checkin reason type: 8 attempt count: 1
,D/Process (  908): killProcessQuiet, pid=4239
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4617 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
I/ActivityManager(  908): Killing 4239:com.google.android.partnersetup/u0a32 (adj 15): empty #17
I/ActivityManager(  908): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2190): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  908): Recipient 4239
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4537): Grow heap (frag case) to 9.913MB for 39954-byte allocation
I/ActivityManager(  908): Recipient 4098
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4537): Grow heap (frag case) to 9.990MB for 79892-byte allocation
,D/PMS     (  908): releaseWL(43034ca0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,W/GAV2    ( 4617): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4617): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
D/ConnectivityService(  908): NetTransition Wakelock for ConnectedState released by timeout
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4617): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/dalvikvm-heap( 4537): Grow heap (frag case) to 10.061MB for 84664-byte allocation
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4617): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4617): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,V/Tethering(  908): mTetherableUsbRegexs:{(usb0)(ncm0)}
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  908): [AlarmQueuing] connectivity wifi: true
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,I/dalvikvm-heap( 4537): Grow heap (frag case) to 10.087MB for 28144-byte allocation
,D/CaptivePortalTracker(  908): NoActiveNetworkState
,V/Tethering(  908): bSetPropertyMultiRAB:false
,D/Tethering(  908): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/Tethering(  908): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  908): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  908): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  908): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  908): Found interface wlan0
,D/Tethering(  908): TetherMasterSM: InitialState processMessage what=3
,I/ConnectivityHelper( 1270): [onReceive] WIFI(1): CONNECTED
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by  (908/1000)
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.htc.launcher (1270/10076)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.setupwizard (4588/10079)
D/PMS     (  908): acquireWL(4417f988): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 908 1000 null
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.google.android.music (4517/10154)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.backuptransport (1593/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,I/NetworkMonitor( 4517): type=WIFI subType= reason=null isConnected=true
,D/AccTypeManager( 1326): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/CaptivePortalTracker(  908): DelayedCaptiveCheckState
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.docs (4271/10100)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023854
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023972
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.backuptransport (1593/10029)
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024053
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024058
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.musicenhancer (3906/10053)
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024060
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024064
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025612
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025629
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2190/10029)
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028563
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029886
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,D/htcCheckinService(  908): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  908): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
W/AccTypeManager( 1326): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1326): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/PMS     (  908): acquireWL(439dd348): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.docs (4271/10100)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2190/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2190/10029)
D/GpsLocationProvider(  908): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  908): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  908): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  908): ignore wifi update if we are not in OPENING or CLOSING
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  908): releaseWL(439dd348): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  908): releaseWL(4417f988): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/ExternalAccountType( 1326): Unsupported attribute readOnly
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  908): getNetworkInfo networkType=9 called by com.google.android.gms (2190/10029)
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,I/dalvikvm-heap( 4537): Grow heap (frag case) to 10.275MB for 75760-byte allocation
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2190/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.magazines (4617/10151)
,V/WebViewChromiumFactoryProvider( 4617): Binding Chromium to main looper Looper (main, tid 1) {41b5a7e0}
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
I/LibraryLoader( 4617): Expected native library version number "",actual native library version number ""
,I/chromium( 4617): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4617): Initializing chromium process, renderers=0
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/AudioManagerAndroid( 4617): BLUETOOTH permission is missing!
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4537/10027)
W/BroadcastQueue(  908): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42fb3a90 u0 ReceiverList{43049c98 4537 com.facebook.katana/10027/u0 remote:43036d10}}
W/BroadcastQueue(  908): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42fb3a90 u0 ReceiverList{43049c98 4537 com.facebook.katana/10027/u0 remote:43036d10}}
D/PMS     (  908): acquireWL(41d25098): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  908): acquireWL(431e6868): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  908): releaseWL(41d25098): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
W/BroadcastQueue(  908): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{426fe288 u0 ReceiverList{426fe228 4537 com.facebook.katana/10027/u0 remote:41eb3b20}}
,I/Adreno-EGL( 4617): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4617): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4617): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4617): Local Branch: 
I/Adreno-EGL( 4617): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4617): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4617):                  aa63bbd948f41d15fc72f585e
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023854
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023972
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024053
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024058
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024060
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024064
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025612
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025629
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028563
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029886
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4537/10027)
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4537/10027)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4537/10027)
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,I/NSApplication( 4617): Starting up...
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.magazines (4617/10151)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.magazines (4617/10151)
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,I/ActivityManager(  908): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4658 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (3597/10160)
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/Process (  908): killProcessQuiet, pid=4271
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/PMS     (  908): acquireWL(427647c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (3597/10160)
,I/ActivityManager(  908): Killing 4271:com.google.android.apps.docs/u0a100 (adj 15): empty #17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  908): releaseWL(427647c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  908): Recipient 4271
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2190/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2190/10029)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2190/10029)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
W/dalvikvm( 4658): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4658): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1367/10029)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
I/MultiDex( 4658): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4658): install
,I/MultiDex( 4658): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (2344/10021)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1367/10029)
,I/MultiDex( 4658): loading existing secondary dex files
,I/MultiDex( 4658): load found 3 secondary dex files
,I/MultiDex( 4658): install done
,W/dalvikvm( 4658): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4658): VFY: unable to resolve instance field 36
,W/dalvikvm( 4658): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4658): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4537): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4537): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4537): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,D/AutoSetting( 1339): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4588): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4588): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.sense.hsp (1339/10055)
,D/AutoSetting( 1339): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.magazines (4617/10151)
D/AutoSetting( 1339): service - onStartCommand() screen is off, don't request location
,I/ProviderInstaller( 4658): Installed default security provider GmsCore_OpenSSL
D/AutoSetting( 1339): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1339): service - onStartCommand() check timezone in 30000
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.sense.hsp (1339/10055)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (3597/10160)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (3597/10160)
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/PMS     (  908): acquireWL(43ef4ff8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2190 10029 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/CheckinService( 2190): Checkin interval check for package: unspecified last checkin: 1450736004473 min interval config: 0 actual interval: 53352
,W/dalvikvm( 4658): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4658): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/PMS     (  908): releaseWL(43ef4ff8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 4658): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4658): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4658): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4658): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4658): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2190, uid=10029, userID:0
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2190/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2190/10029)
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2190/10029)
,I/WVCdm   (  371): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  371): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1367/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1367/10029)
,D/WearableService( 1221): callingUid 10029, callindPid: 1221
,D/LocationInitializer( 2190): Restart initialization of location
,D/NativeLibraryUtils( 4658): Install completed successfully. count=14 extracted=0
,E/MDM     ( 1221): [119] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1367): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1367): Proximity feature is not enabled.
,D/WVCdm   (  371): PrepareKeyRequest: nonce=722088062
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  908): acquireWL(43b62f40): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
W/GCoreFlp( 1221): No location to return for getLastLocation()
,W/FusedLocationProvider( 1221): location=null
D/PMS     (  908): releaseWL(43b62f40): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023854
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023972
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024053
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024058
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024060
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024064
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025612
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025629
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028563
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029886
,I/WVCdm   (  371): CdmEngine::CloseSession
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  371): PrepareKeyRequest: nonce=562401084
,I/WVCdm   (  371): CdmEngine::CloseSession
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (4658/10029)
,I/Adreno-EGL( 4658): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4658): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4658): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4658): Local Branch: 
I/Adreno-EGL( 4658): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4658): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4658):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4658): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4658): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4658): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4658): Local Branch: 
I/Adreno-EGL( 4658): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4658): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4658):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4658): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4658): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4658): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4658): Local Branch: 
I/Adreno-EGL( 4658): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4658): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4658):                  aa63bbd948f41d15fc72f585e
,W/Settings( 4658): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinRequestBuilder( 2190): Classify the device as Phone.
,D/libc    ( 2190): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2190): [NET] getaddrinfo-,err=8
,D/libc    ( 2190): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2190): [NET] getaddrinfo-, 1
,D/libc    ( 2190): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =71fb +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,W/dalvikvm( 4419): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4419): threadid=1: thread exiting with uncaught exception (group=0x41729e30)
,E/AndroidRuntime( 4419): FATAL EXCEPTION: main
E/AndroidRuntime( 4419): Process: com.test.thalitest, PID: 4419
E/AndroidRuntime( 4419): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4419): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4419): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4419): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4419): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4419): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4419): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4419): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4419): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4419): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4419): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4419): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4419): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4419): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4419): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4419): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4419): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4419): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4419): 	at dalvik.system.NativeStart.main(Native Method)
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=84
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2190): [NET] getaddrinfo_proxy-, success
,E/ActivityManager(  908): App crashed! Process: com.test.thalitest
W/ActivityManager(  908):   Force finishing activity com.test.thalitest/.MainActivity
,D/Process (  908): killProcessQuiet, pid=4294
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
D/libc    ( 2190): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2190): [NET] getaddrinfo-,err=8
,I/ActivityManager(  908): Killing 4294:com.htc.backup/1000 (adj 15): empty #17
D/Process ( 4419): killProcess, pid=4419
D/Process ( 4419): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/ActivityManager(  908): Recipient 4294
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/libc    ( 2190): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2190): [NET] getaddrinfo-,err=8
D/libc    ( 2190): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2190): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2190): Sending checkin request (12196 bytes)
,E/JavaBinder(  908): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  908): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 1209): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  908): Got RemoteException sending setActive(false) notification to pid 4419 uid 10389
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 4419
,I/WindowState(  908): WIN DEATH: Window{424bf6b0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  908): Client connection lost with reason: 4
,I/ActivityManager(  908): Process com.test.thalitest (pid 4419) has died.
,D/libc    (  908): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-,err=8
D/libc    (  908): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  908): [NET] getaddrinfo-, 1
,D/libc    (  908): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =6ea1 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE,
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=172
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  908): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  908): Find DNS Address www.htc.com/104.81.130.175
,I/CheckinRequestBuilder( 2190): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  908): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2190): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  908): getNetworkInfo networkType=9 called by com.google.android.gms (2190/10029)
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2190/10029)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=11 [18][2][0]
,I/CheckinRequestBuilder( 2190): Classify the device as Phone.
,I/CheckinTask( 2190): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2190): Checking schedule, now: 1450736059977 next: 1451258996970
,I/CheckinService( 2190): active receiver: disabled
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2190, uid=10029, userID:0
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4537/10027)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023854
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023972
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024053
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024058
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024060
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024064
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4537/10027)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025612
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025629
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028563
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029886
I/CheckinService( 2190): Checking schedule, now: 1450736060004 next: 1451258996970
,I/CheckinService( 2190): active receiver: disabled
,D/CheckinService( 2190): Recording last checkin time for package unspecified as 1450736060010
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2190, uid=10029, userID:0
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023854
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023972
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024053
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024058
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024060
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024064
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025612
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025629
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028563
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029886
D/PMS     (  908): releaseWL(432ac318): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2190/10029)
,D/PMS     (  908): acquireWL(424e6f78): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,W/fb4a(:<default>):UserScope( 4537): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/GCM     ( 1367): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    ( 1367): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1367): [NET] getaddrinfo-,err=8
D/libc    ( 1367): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1367): [NET] getaddrinfo-, 1
D/libc    ( 1367): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
W/fb4a(:<default>):UserScope( 4537): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =d7dd +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1367/10029)
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4537/10027)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 252
D/libc    (  363): [NET]res_nsend:resplen=79
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1367): [NET] getaddrinfo_proxy-, success
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4537/10027)
,D/AutoSetting( 1513): service - handleMessage() stop self
,D/AutoSetting( 1513): service - onDestroy() END
,D/AutoSetting( 1513): service - handleMessage() quit looper
D/libc    ( 1367): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1367): [NET] getaddrinfo-,err=8
,D/libc    ( 1367): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1367): [NET] getaddrinfo-,err=8
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1367/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1367/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1367/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1367/10029)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4537): Called registerBroadcastReceiver twice.
,D/PMS     (  908): acquireWL(42cfd548): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1367/10029)
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1367/10029)
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1367/10029)
,D/PMS     (  908): releaseWL(424e6f78): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1367/10029)
,D/ConnectivityService(  908): reportInetCondition for net 1, percentage: 100 by  (1367/10029)
,D/ConnectivityService(  908): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  908): handleInetConditionChange: starting a change hold
,D/PMS     (  908): releaseWL(42cfd548): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(43768470): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1367/10029)
,D/ConnectivityService(  908): reportInetCondition for net 1, percentage: 100 by  (1367/10029)
D/ConnectivityService(  908): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  908): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1367/10029)
,D/ConnectivityService(  908): reportInetCondition for net 1, percentage: 100 by  (1367/10029)
D/ConnectivityService(  908): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  908): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1367/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023854
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023972
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024053
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024058
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024060
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024064
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025612
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025629
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028563
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029886
,D/PMS     (  908): releaseWL(43768470): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4537/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4537/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4537/10027)
,D/libc    ( 4537): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 4
D/libc    ( 4537): [NET] getaddrinfo-,err=8
D/libc    ( 4537): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 1024
D/libc    ( 4537): [NET] getaddrinfo-, 1
,D/libc    ( 4537): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =85fa +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 47
D/libc    (  363): [NET]res_nsend:resplen=74
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4537): [NET] getaddrinfo_proxy-, success
I/global  ( 4537): call createSocket() return a new socket.
D/libc    ( 4537): [NET] getaddrinfo+,hn 10(0x33312e31332e38),sn(),family 0,flags 4
,D/libc    ( 4537): [NET] getaddrinfo-, SUCCESS
,D/PMS     (  908): acquireWL(43778730): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4517 10154 null
,W/ContextImpl( 4517): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4517, uid=10154, userID:0
,I/MusicLeanback( 4517): Conditions not met for autocaching.
,I/MusicLeanback( 4517): Stop autocaching.
D/PMS     (  908): releaseWL(43778730): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,W/ContextImpl( 4517): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/libc    ( 4537): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 4
,D/libc    ( 4537): [NET] getaddrinfo-,err=8
D/PMS     (  908): releaseWL(431e6868): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/dalvikvm-heap( 4537): Grow heap (frag case) to 10.991MB for 32784-byte allocation
,D/PMS     (  908): acquireWL(43d13fc0): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 4537 10027 null
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4537/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4537/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4537/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4537/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4537/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4537/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4537/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4537/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4537/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4537/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4537/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4537/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4537/10027)
D/ConnectivityService(  908): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/ConnectivityService(  908): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4537/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4537/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4537/10027)
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4537/10027)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=12 [24][3][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4537/10027)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4537/10027)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4537/10027)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4537/10027)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4537/10027)
,D/WifiStateMachine(  908): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  908): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent DefaultState
,I/global  ( 4537): I/O error closing connection
I/global  ( 4537): java.net.SocketException: Socket is closed
I/global  ( 4537): 	at java.net.Socket.checkOpenAndCreate(Socket.java:672)
I/global  ( 4537): 	at java.net.Socket.getSoLinger(Socket.java:435)
I/global  ( 4537): 	at com.android.org.conscrypt.OpenSSLSocketImplWrapper.getSoLinger(OpenSSLSocketImplWrapper.java:156)
I/global  ( 4537): 	at org.apache.http.impl.conn.tsccm.AbstractConnPool.closeConnection(AbstractConnPool.java:328)
I/global  ( 4537): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteEntry(ConnPoolByRoute.java:530)
I/global  ( 4537): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteClosedConnections(ConnPoolByRoute.java:653)
I/global  ( 4537): 	at org.apache.http.impl.conn.tsccm.ThreadSafeClientConnManager.closeIdleConnections(ThreadSafeClientConnManager.java:295)
I/global  ( 4537): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager.b(FbClientConnManager.java:316)
I/global  ( 4537): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager$CloseIdleConnectionsRunnable.run(FbClientConnManager.java:327)
I/global  ( 4537): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
I/global  ( 4537): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
I/global  ( 4537): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
I/global  ( 4537): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
I/global  ( 4537): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
I/global  ( 4537): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
I/global  ( 4537): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
I/global  ( 4537): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
I/global  ( 4537): 	at java.lang.Thread.run(Thread.java:864)
,W/IdleConnectionHandler( 4537): Removing a connection that never existed!
D/PMS     (  908): releaseWL(43d13fc0): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 null
,I/GAV2    ( 4617): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  908): killProcessQuiet, pid=4312
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 4312:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4312
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  908): killProcessQuiet, pid=3906
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3906:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3906
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1326): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "sms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "smsto"
I/ActivityManager(  908): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4719 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
,I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1270): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "mms"
W/AccTypeManager( 1326): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1326): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/Launcher( 1270): Deferring update until onResume
,D/Launcher( 1270): waitUntilResume // bindAppsUpdated
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "mmsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
,W/SystemReader( 1249): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "sms"
,I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
,D/CaptivePortalTracker(  908): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  908): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  908): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "smsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
,E/ExternalAccountType( 1326): Unsupported attribute readOnly
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "mms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "mmsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
,D/PhoneApp( 1236): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4719): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4719): MmsConfig.loadMmsSettings
,W/dalvikvm( 4719): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4719): VFY: unable to resolve instance field 36
,W/dalvikvm( 4719): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4719): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4719, uid=10111, userID:0
,W/Settings( 4719): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  908): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4742 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4719, uid=10111, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4719, uid=10111, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4719, uid=10111, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4719, uid=10111, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4719, uid=10111, userID:0
,W/PackageManager(  908): Unable to load service info ResolveInfo{43627f48 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
D/PMS     (  908): acquireWL(430466a8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4719 10111 null
,D/MessageFrequencyProvider( 4742): onCreate
,V/GetPrviateResource( 4742): GetPrviateResource
D/MmsCustomizationProvider( 4742): query uri: content://htc-mms-customization/mms-ua/ua_string
,V/GetPrviateResource( 4742): GetPrviateResource
I/[PluginManager]RegisterService( 1339): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1339): handle notify Blinkfeed plugin client changed
I/ActivityManager(  908): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  908): Resuming delayed broadcast
,I/IcingCorporaProvider( 2859): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/MmsCustomizationProvider( 4742): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/ActivityManager(  908): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/PMS     (  908): releaseWL(430466a8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/Process (  908): killProcessQuiet, pid=4257
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/Babel   ( 4719): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4719): MmsConfig.loadFromDatabase
I/ActivityManager(  908): Killing 4257:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/PMS     (  908): acquireWL(427e84d0): PARTIAL_WAKE_LOCK  Icing 0x1 2190 10029 WorkSource{10029 com.google.android.gms}
,I/ProviderInstaller( 4719): Installed default security provider GmsCore_OpenSSL
D/PMS     (  908): releaseWL(427e84d0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  908): Resuming delayed broadcast
E/Babel   ( 4719): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4719): MmsConfig.loadFromResources
,E/Babel   ( 4719): canonicalizeMccMnc: invalid mccmnc nullnull
I/ActivityManager(  908): Recipient 4257
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  908): acquireWL(43629f58): PARTIAL_WAKE_LOCK  Icing 0x1 2190 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  908): Delay finish: com.google.android.googlequicksearchbox/.GelStubAppWatcher
I/Babel   ( 4719): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,D/MessageCustFlag( 4742): sense_version=6.0
,D/BTAccessoryUtil( 4742): createReceiver
,D/BTAccessoryUtil( 4742): registerReceiver return intent = null
D/MessageCustFlag( 4742): sku_id=99
,W/SystemReader( 4742): Cannot find message_ambs_application_id, use default value instead
,D/Messaging( 4742): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4742): networkCode: 
,D/MessageCustFlag( 4742): sku_id=99
D/MmsConfig( 4742): SIE smsPri: null
,D/MmsConfig( 4742): networkCode: 
,D/HtcTelephonyCapability( 4742): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 4742): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 4742): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4742): Cannot find qct_8960_interface, use default value instead
,D/PMS     (  908): releaseWL(43629f58): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  908): Resuming delayed broadcast
,D/PMS     (  908): acquireWL(440ee7b8): PARTIAL_WAKE_LOCK  Icing 0x1 2190 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  908): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  908): acquireWL(43073580): PARTIAL_WAKE_LOCK  AsyncService 0x1 3597 10160 null
,D/PMS     (  908): releaseWL(43073580): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  908): releaseWL(440ee7b8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  908): acquireWL(4388e9c8): PARTIAL_WAKE_LOCK  Icing 0x1 2190 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(4388e9c8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  908): Resuming delayed broadcast
,D/PMS     (  908): acquireWL(442d12d8): PARTIAL_WAKE_LOCK  Icing 0x1 2190 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  908): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,D/RemoteDisplayProvider(  908): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  908): start
,D/PMS     (  908): releaseWL(442d12d8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  908): Resuming delayed broadcast
,I/GCoreNlp( 1221): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/PMS     (  908): acquireWL(43283b80): PARTIAL_WAKE_LOCK  Icing 0x1 2190 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(43283b80): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  908): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
,I/ActivityManager(  908): Resuming delayed broadcast
,D/LocationProviderProxy(  908): applying state to connected service
D/PMS     (  908): acquireWL(442de318): PARTIAL_WAKE_LOCK  Icing 0x1 2190 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): acquireWL(442baba8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(442baba8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  908): applying state to connected service
D/PMS     (  908): releaseWL(442de318): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(4420db30): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(441bac00): PARTIAL_WAKE_LOCK  Icing 0x1 2190 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(4420db30): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(441bab60): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(441bac00): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(441bab60): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(4417fa50): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PackageBroadcastService( 2190): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/ActivityManager(  908): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/PMS     (  908): releaseWL(4417fa50): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(4417f8c0): PARTIAL_WAKE_LOCK  Icing 0x1 2190 10029 WorkSource{10029 com.google.android.gms}
I/PackageBroadcastService( 2190): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 2190): updateResources: need to parse f{com.google.android.gms}
,I/IcingCorporaProvider( 2859): UpdateCorporaTask done [took 549 ms] updated apps [took 549 ms] 
I/ActivityManager(  908): Resuming delayed broadcast
,I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1270): loadItems() com.htc.launcher.pageview.WidgetManager@41becc70 +
,I/Prism.WidgetManager( 1270): onLoadItems() +
,I/ActivityManager(  908): Waited long enough for: ServiceRecord{425d0e10 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,E/Prism.WidgetManager( 1270): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1270): onLoadItems() -
,I/Prism.ItemManager( 1270): loadItems() com.htc.launcher.pageview.WidgetManager@41becc70 -
,I/Icing   ( 2190): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2190): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  908): releaseWL(4417f8c0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PhoneApp( 1236): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1236): -- N1 =0
,D/PhoneApp( 1236): -- N2 =0
,D/PhoneApp( 1236): -- N3 =0
,D/Messaging( 4742): mNeedToUpdateDate2 start
,D/MmsConfig( 4742): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4742): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4742): 
D/MmsAsyncWorkHandler( 4742): HM tk = 20001
,D/ReportIndicatorCache( 4742): MSG_QUERY_REPORTS >>
D/TelephUtils( 1236): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/SettingsManager( 4742): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41b67260
D/MmsSmsV2Provider( 1236):  phoneType = -1
,D/MmsSmsV2Provider( 1236): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,I/Messaging( 4742): mccmnc> 
,D/DraftCache( 4742): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4742): [DraftCache/1] refresh
,D/MmsConfig( 4742): networkCode: 
,D/Messaging( 4742): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1236): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
,D/AccFlag ( 1236): sku_id=99
,D/TelephUtils( 1236): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/MmsSmsV2Provider( 1236):  phoneType = -1
,D/MmsSmsV2Provider( 1236): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/PhoneStorageUtil( 4742): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4742): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4742): createReceiver
,D/MessageCustFlag( 4742): sense_version=6.0
,D/DraftCache( 4742): [DraftCache/466] rebuildCache
,D/Jerry   ( 4742): start to preload cursor >>>>>>>
,D/Messaging( 4742): mNeedToUpdateDate2: false
,D/TelephUtils( 1236): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
V/MmsProvider( 1236): Update uri=content://mms, match=0
,V/MmsProvider( 1236): selection=st=129 AND m_type!=134
,D/TelephUtils( 1236): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/MmsSmsV2Provider( 1236):  phoneType = -1
,D/MmsSmsV2Provider( 1236): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/Messaging( 4742): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4742): TransactionService is going to be woken up.
,D/TelephUtils( 1236): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 68
,D/Jerry   ( 1236): URI_DRAFT
,V/TransactionService( 4742): 1-Creating TransactionService
V/TransactionService( 4742): onStartCommand: 1
,D/MmsSystemEventReceiver( 4742): unRegisterForConnectionStateChanges
V/TransactionService( 4742): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4742): Loading previous transactions.
D/DraftCache( 4742): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 4742): [DraftCache/466] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4742): 
D/MmsAsyncWorkHandler( 4742): HM tk = 20002
,D/TelephUtils( 1236): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
,D/MmsSmsV2Provider( 1236):  phoneType = -1
,D/TelephUtils( 1236): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1236): device_type: 1
,D/TransactionService( 4742): Force set service start id to 1
V/TransactionService( 4742): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4742): unRegisterForConnectionStateChanges
,D/TransactionService( 4742): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4742): Destroying TransactionService
D/TelephUtils( 1236): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,V/TransactionService( 4742): 4-Handling incoming message: { when=-2ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
D/MmsSmsV2Provider( 1236):  phoneType = -1
,D/MmsSmsV2Provider( 1236): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/Messaging( 4742): ViewCache CreatePreload
,D/Messaging( 4742): ViewCache CreatePreloadOnlyMultipleOpsList
,D/Messaging( 4742): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/TelephUtils( 1236): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1236): sku_id=99
,D/Cust_MMSMS( 4742): _has_set_default_values_2=true
,D/TelephUtils( 1236): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
,D/AccFlag ( 1236): sku_id=99
,D/MsgPreferenceUtils( 4742): def_index: 0
,D/MsgPreferenceUtils( 4742): globalIndex = 1
D/MsgPreferenceUtils( 4742): phone state: true
,D/MsgPreferenceUtils( 4742): sd state: false
,D/MsgPreferenceUtils( 4742): vIndex = 0
,D/PMS     (  908): acquireWL(42cb1b70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  908): sending alarm PendingIntent{42bf1f30: PendingIntentRecord{427d9f58 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=122372, Int=0
,D/PMS     (  908): releaseWL(42cb1b70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(426a0a98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1367/10029)
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=15 [13][2][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/PMS     (  908): acquireWL(42698388): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(42698388): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(426a0a98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(423e58b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023854
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023972
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024053
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024058
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024060
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024064
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025612
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025629
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028563
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029886
,D/PMS     (  908): releaseWL(423e58b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(424dc550): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1367/10029)
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023854
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023972
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024053
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024058
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024060
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024064
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025612
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025629
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028563
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029886
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/PMS     (  908): acquireWL(4267fde0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(42657bd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(424dc550): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(4267fde0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(43554490): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023854
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023972
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024053
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024058
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024060
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024064
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025612
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025629
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028563
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029886
,D/PMS     (  908): releaseWL(43554490): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1221): Vacuum at: now=1450736070832 tag=VacuumService
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  908): acquireWL(430c5e80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1367/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023854
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023972
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024053
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024058
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024060
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024064
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025612
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025629
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028563
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029886
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/PMS     (  908): releaseWL(430c5e80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(42657bd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(42602f18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023854
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023972
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024053
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024058
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024060
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024064
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025612
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025629
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028563
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029886
,D/PMS     (  908): releaseWL(42602f18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(4250b810): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1367/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023854
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023972
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024053
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024058
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024060
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024064
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025612
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025629
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028563
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029886
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  908): releaseWL(4250b810): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): acquireWL(43083968): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1367/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023854
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023972
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024053
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024058
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024060
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024064
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025612
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025629
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028563
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029886
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/PMS     (  908): acquireWL(42676488): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(42676488): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(424dd158): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(43083968): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(427e0e20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023854
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023972
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024053
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024058
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024060
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024064
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025612
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025629
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028563
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029886
,D/PMS     (  908): releaseWL(427e0e20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1221): Scheduling Phenotype for one-off execution 12126 seconds from now (1450736071388)
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
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL,
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/libc    ( 1221): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1221): [NET] getaddrinfo-,err=8
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/libc    ( 1221): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1221): [NET] getaddrinfo-, 1
,D/libc    ( 1221): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =604e +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 237
D/libc    (  363): [NET]res_nsend:resplen=87
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1221): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1221): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1221): [NET] getaddrinfo-,err=8
D/libc    ( 1221): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1221): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  908): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=8 [12][1][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  908): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  908): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [2][0][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/PMS     (  908): releaseWL(424dd158): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(42649298): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023854
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023972
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024053
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024058
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024060
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024064
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025612
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025629
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028563
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029886
,D/PMS     (  908): releaseWL(42649298): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(4269dfe8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1367/10029)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=50 [2][1][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023854
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023972
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024053
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024058
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024060
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024064
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025612
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025629
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028563
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029886
,D/PMS     (  908): releaseWL(4269dfe8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/GAV4    ( 4719): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  908): acquireWL(424b2470): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1581): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1581): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1581): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): releaseWL(424b2470): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  908): acquireWL(43d1cce8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  908): sending alarm PendingIntent{41f16068: PendingIntentRecord{427de918 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=136433, Int=0
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1367/10029)
,D/PMS     (  908): releaseWL(43d1cce8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1339): service - mHandler: update timezone
,D/AutoSetting( 1513): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  908): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1513): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1513): service - onCreate()
,D/AutoSetting( 1513): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,W/ActivityManager(  908): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1513): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/AutoSetting( 1513): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1513): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1513): service - mHandler: update timezone
V/NotificationService(  908): batLight: Full, plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c800
D/qdlights(  908): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/DotMatrix( 1581): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1581): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1513): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1513): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1513): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1513): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1581): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1581): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1117): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41ca7950 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.htclocationservice 3 6 2 11
,D/AutoSetting( 1339): service - mHandler: update timezone
,D/AutoSetting( 1513): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1513): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
D/AutoSetting( 1513): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1513): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
W/ActivityManager(  908): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  908): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/DotMatrix( 1581): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/AutoSetting( 1513): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1513): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1513): service - mHandler: update timezone
,D/DotMatrix( 1581): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  908): batLight: Full, plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c800
D/qdlights(  908): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1339): service - handleMessage() stop self
D/AutoSetting( 1513): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1513): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1339): service - onDestroy() END
,D/AutoSetting( 1339): service - handleMessage() quit looper
,D/AutoSetting( 1513): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1513): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1581): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true,
,D/DotMatrix( 1581): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1117): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41b87288 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.htclocationservice 3 8 2 11
,D/GpsLocationProvider(  908): ALARM_XTRA_TIMEOUT
D/PMS     (  908): acquireWL(43330b90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
V/AlarmManager(  908): sending alarm PendingIntent{4248c840: PendingIntentRecord{4248c7c0 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141032, Int=0
D/PMS     (  908): acquireWL(4384dc90): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 908 1000 null
D/GpsLocationProvider(  908): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  908): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  908): releaseWL(43330b90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  908): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-,err=8
D/libc    (  908): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  908): [NET] getaddrinfo-, 1
,D/libc    (  908): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =af93 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  363): [NET]res_nsend:resplen=238
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  908): [NET] getaddrinfo_proxy-, success
I/global  (  908): call createSocket() return a new socket.
D/libc    (  908): [NET] getaddrinfo+,hn 14(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  908): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  908): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  908): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  908):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  908): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  908): releaseWL(4384dc90): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/Process (  908): killProcessQuiet, pid=4343
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 4343:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4343
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): acquireWL(426c2bb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{4209d2c0: PendingIntentRecord{420738d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=151818, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(426c2bb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ContactMessageStore( 1236): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1236): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  908): Waited long enough for: ServiceRecord{426a2828 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  908): acquireWL(42535380): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42535380): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1581): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1581): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1581): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1513): service - handleMessage() stop self
,D/AutoSetting( 1513): service - onDestroy() END
,D/AutoSetting( 1513): service - handleMessage() quit looper
,D/Process (  908): killProcessQuiet, pid=4358
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 4358:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4358
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): acquireWL(440ac358): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10027}
,V/AlarmManager(  908): sending alarm PendingIntent{43c680f8: PendingIntentRecord{44045078 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=172175, Int=0
,D/PMS     (  908): releaseWL(440ac358): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1236): switchBindHtcMsgCursor: null
,D/PMS     (  908): acquireWL(436aa228): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(436aa228): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/DotMatrix( 1581): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1581): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1581): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(43884210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43884210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(4262a538): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{4209d2c0: PendingIntentRecord{420738d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=211818, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4262a538): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  908): acquireWL(435f04d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(435f04d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  908): acquireWL(43bde230): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{4209d2c0: PendingIntentRecord{420738d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=271819, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43bde230): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(42faa550): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42faa550): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(436ae318): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{4209d2c0: PendingIntentRecord{420738d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=331819, Int=0
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(436ae318): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  908): acquireWL(43bfe5d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43bfe5d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  908): acquireWL(426e1810): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{4209d2c0: PendingIntentRecord{420738d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=391819, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(426e1810): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(4377a600): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4377a600): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(441766f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/PMS     (  908): releaseWL(441766f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1581): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1581): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1581): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(43839e48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{4209d2c0: PendingIntentRecord{420738d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=451819, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43839e48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  908): acquireWL(426c2f60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(426c2f60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  908): acquireWL(43605e10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{4209d2c0: PendingIntentRecord{420738d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=511819, Int=0
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43605e10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(43d3e7e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43d3e7e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(4361fbb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{4209d2c0: PendingIntentRecord{420738d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=571819, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4361fbb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(441732a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(441732a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  908): acquireWL(42fb6ee8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42fb6ee8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,D/DotMatrix( 1581): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1581): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1581): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/ContactMessageStore( 1236): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1236): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1236): sku_id=99
D/ContactMessageStore( 1236): start background delete task...
,D/ContactMessageStore( 1236): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1236): size: 0 , 0
,D/ContactMessageStore( 1236): Background delete complete
,D/PMS     (  908): acquireWL(43bcccf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{4209d2c0: PendingIntentRecord{420738d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=631819, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43bcccf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  908): killProcessQuiet, pid=4075
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 4075:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4075
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): acquireWL(440f2e40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
D/PMS     (  908): releaseWL(440f2e40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  908): updateBatteryInfo
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,D/DotMatrix( 1581): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1581): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,D/DotMatrix( 1581): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(427e82e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): releaseWL(427e82e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
,I/HtcPowerSaver(  908): >> updateStatus
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1581): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1581): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1581): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(43040860): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  908): sending alarm PendingIntent{4209d2c0: PendingIntentRecord{420738d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=691819, Int=0
,D/PMS     (  908): releaseWL(43040860): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(442deac0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(442deac0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(43d76f18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{4209d2c0: PendingIntentRecord{420738d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=751818, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43d76f18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(431c4510): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(431c4510): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(43d3b990): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{4209d2c0: PendingIntentRecord{420738d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=811819, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43d3b990): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(442486d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(442486d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(43851a70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{4209d2c0: PendingIntentRecord{420738d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=871819, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43851a70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43efb458): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43efb458): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(426b6c88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{4209d2c0: PendingIntentRecord{420738d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=931819, Int=0
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(426b6c88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(427e2f70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(427e2f70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(427c80b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
V/AlarmManager(  908): sending alarm PendingIntent{4209d2c0: PendingIntentRecord{420738d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=991819, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(427c80b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  908): Sampling interval elapsed, updating statistics ..
,D/PMS     (  908): acquireWL(42fae698): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41debb70: PendingIntentRecord{424ea098 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=782559, Int=0
,D/ConnectivityService(  908): Done.
,D/ConnectivityService(  908): Setting timer for 720seconds
,I/ActivityManager(  908): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4841 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  908): sending alarm PendingIntent{423bbcc8: PendingIntentRecord{425e3628 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1450736159941, Int=10800000
,V/AlarmManager(  908): sending alarm PendingIntent{439d9ab0: PendingIntentRecord{425dd7e0 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450736877982, Int=1800000
,V/AlarmManager(  908): sending alarm PendingIntent{4264bf30: PendingIntentRecord{42673050 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450736880607, Int=900000
,V/AlarmManager(  908): sending alarm PendingIntent{41f29d50: PendingIntentRecord{4308a938 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450736954552, Int=0
,D/PMS     (  908): acquireWL(4404cce8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2190 10029 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4484): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  908): acquireWL(42fe6a68): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2190 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(4404cce8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,D/PowerUsageService( 4484): call getInstance()
,D/SmartSyncUtils( 4484): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4484): MY_DEBUG = false
,I/EventLogService( 2190): Aggregate from 1450736057301 (log), 1450735077925 (data)
,D/SmartSyncScreenOnOffTimeReceiver( 4484): [updateNmRange] bManual = false
D/PMS     (  908): releaseWL(42fae698): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(432ab870): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4484 1000 null
D/SmartSyncScreenOnOffTimeReceiver( 4484): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 4484): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4484): SettingOnTime = 1450764000000, randomSettingOnTime = 1450762899000
D/SmartSyncScreenOnOffTimeReceiver( 4484): SettingOffTime = 1450749600000, randomSettingOffTime = 1450751018000
,D/SmartSyncScreenOnOffTimeReceiver( 4484): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4484): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4484): bNightModeTurnOffOnce = false
W/BatSI   (  908): Couldn't get kernel wake lock stats
,D/PMS     (  908): releaseWL(432ab870): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.aurora (4841/10049)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023854
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023972
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024053
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024058
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024060
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024064
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025612
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025629
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028563
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029886
,D/PMS     (  908): releaseWL(42fe6a68): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023854
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023972
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024053
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024058
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024060
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024064
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025612
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025629
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028563
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029886
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,D/Process (  908): killProcessQuiet, pid=4390
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 4390:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4390
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): acquireWL(4240c748): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  908): sending alarm PendingIntent{43cbd5e0: PendingIntentRecord{426b01a0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1012147, Int=0
,D/PMS     (  908): acquireWL(41e2edc8): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(41e2edc8): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(4240c748): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(4303c690): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1367/10029)
,D/ConnectivityService(  908): reportInetCondition for net 1, percentage: 100 by  (1367/10029)
D/ConnectivityService(  908): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  908): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1367/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023854
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023972
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024053
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024058
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024060
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024064
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025612
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025629
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028563
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029886
,D/PMS     (  908): releaseWL(4303c690): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  908): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=5 [126][7][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/PMS     (  908): acquireWL(42500be8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42500be8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(423bb630): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{4209d2c0: PendingIntentRecord{420738d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1051818, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(423bb630): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(4205dc50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4205dc50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(41ba2690): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
V/AlarmManager(  908): sending alarm PendingIntent{4209d2c0: PendingIntentRecord{420738d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1111819, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(41ba2690): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(4361f140): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4361f140): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(4258bba8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{4209d2c0: PendingIntentRecord{420738d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1171819, Int=0
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4258bba8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(4221bce0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4221bce0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  908): acquireWL(42fea8f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
V/AlarmManager(  908): sending alarm PendingIntent{4209d2c0: PendingIntentRecord{420738d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1231819, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42fea8f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(438ccf30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(438ccf30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(426f4a68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{4209d2c0: PendingIntentRecord{420738d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1291819, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(426f4a68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(4247af38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4247af38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(4201a1a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{4209d2c0: PendingIntentRecord{420738d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1351819, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4201a1a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42776528): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42776528): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(43d31f88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{4209d2c0: PendingIntentRecord{420738d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1411819, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43d31f88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42694598): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42694598): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(425dc810): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{4209d2c0: PendingIntentRecord{420738d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1471819, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(425dc810): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42493728): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42493728): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(42450e30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{4209d2c0: PendingIntentRecord{420738d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1531818, Int=0
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42450e30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(41d5f910): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(41d5f910): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(432b80e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{4209d2c0: PendingIntentRecord{420738d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1591818, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(432b80e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(426caa80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,D/PMS     (  908): acquireWL(42686460): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 908 1000 null
V/AlarmManager(  908): sending alarm PendingIntent{41d31668: PendingIntentRecord{42550e18 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1627822, Int=0
D/PMS     (  908): releaseWL(426caa80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,D/PMS     (  908): acquireWL(42545f78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
,D/PMS     (  908): releaseWL(42686460): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  908): releaseWL(42545f78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  908): acquireWL(43bd1098): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43bd1098): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(424f6190): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{4209d2c0: PendingIntentRecord{420738d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1651818, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1270): Grow heap (frag case) to 12.652MB for 50416-byte allocation
D/PMS     (  908): releaseWL(424f6190): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42650a28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42650a28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(42f74f60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
V/AlarmManager(  908): sending alarm PendingIntent{4209d2c0: PendingIntentRecord{420738d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1711818, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42f74f60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(44057e70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(44057e70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(43cddaf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
V/AlarmManager(  908): sending alarm PendingIntent{4209d2c0: PendingIntentRecord{420738d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1771819, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43cddaf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,D/PMS     (  908): acquireWL(43ab7e10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43ab7e10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  908): acquireWL(42ed8130): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{4209d2c0: PendingIntentRecord{420738d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1831819, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
I/ProcessStatsService(  908): Prepared write state in 40ms
,D/PMS     (  908): releaseWL(42ed8130): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  908): Pruning old procstats: /data/system/procstats/state-2015-12-21-00-50-15.bin
,D/PMS     (  908): acquireWL(42c76fa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42c76fa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(437210c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
V/AlarmManager(  908): sending alarm PendingIntent{4209d2c0: PendingIntentRecord{420738d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1891819, Int=0
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(437210c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4867): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4867): ====startRecUseTime====
D/htc.customization.log.level( 4867):  is 
W/CustomizationLogLevel( 4867): Level value is invalid, use default level 2
D/CustomizationManager( 4867):  Read ACC file spent 0.128 (s)
D/CIDMapFileReader( 4867): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4867): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4867): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4867): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4867): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4867): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4867): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4867): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4867): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4867): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4867): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4867): Parsing tag category name = system
I/CustomizationCIDLoader( 4867): Parsing tag category name = application
I/CustomizationCIDLoader( 4867): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4867): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4867): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4867): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4867): Parsing tag category name = Settings
D/CustomizationManager( 4867):  Read CID file spent 0.187 (s)
D/CustomizationManager( 4867):  All configurations done spent 0.187 (s)
W/HtcNativeFlag( 4867): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4867): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4867): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4867): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  908): deletePackageAsUser: pkg=com.test.thalitest, pid=4867, uid=2000 user=0
I/ActivityManager(  908): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  908): killProcessQuiet, pid=4517
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  908): killProcessQuiet, pid=4617
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  908): Killing 4517:com.google.android.music:main/u0a154 (adj 15): empty for 1800s
I/ActivityManager(  908): Killing 4617:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1803s
D/Process (  908): killProcessQuiet, pid=4602
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  908): killProcessQuiet, pid=4588
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  908): Killing 4602:com.android.chrome/u0a96 (adj 15): empty for 1803s
I/ActivityManager(  908): Killing 4588:com.google.android.setupwizard/u0a79 (adj 15): empty for 1803s
I/ActivityManager(  908): Recipient 4617
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 4588
I/ActivityManager(  908): Recipient 4602
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/asset   (  908): Copying FileAsset 0x6ce27678 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
W/PackageSettings(  908): Skipping PackageSetting{42210dc8 com.example.hello/10397} due to missing metadata
I/ActivityManager(  908): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/ActivityManager(  908): Recipient 4517
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  908): Client com.google.android.music (pid 4517): Died!
D/DotMatrix( 1581): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1581): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1581): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
W/BroadcastQueue(  908): Failure sending broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
W/BroadcastQueue(  908): android.os.DeadObjectException
W/BroadcastQueue(  908): 	at android.os.BinderProxy.transact(Native Method)
W/BroadcastQueue(  908): 	at android.content.IIntentReceiver$Stub$Proxy.performReceive(IIntentReceiver.java:124)
W/BroadcastQueue(  908): 	at com.android.server.am.BroadcastQueue.performReceiveLocked(BroadcastQueue.java:457)
W/BroadcastQueue(  908): 	at com.android.server.am.BroadcastQueue.deliverToRegisteredReceiverLocked(BroadcastQueue.java:564)
W/BroadcastQueue(  908): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:636)
W/BroadcastQueue(  908): 	at com.android.server.am.BroadcastQueue$1.handleMessage(BroadcastQueue.java:147)
W/BroadcastQueue(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/BroadcastQueue(  908): 	at android.os.Looper.loop(Looper.java:157)
W/BroadcastQueue(  908): 	at com.android.server.am.ActivityManagerService$AThread.run(ActivityManagerService.java:2098)
D/AccTypeManager( 1326): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "sms"
D/PMS     (  908): acquireWL(438aadc8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
D/VoicemailCleanupService( 1300): Cleaning up data for package: com.test.thalitest
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/GeofencerStateMachine( 1221): Ignoring removeGeofence because network location is disabled.
W/SystemReader( 1249): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "smsto"
I/Launcher( 1270): Deferring update until onResume
D/Launcher( 1270): waitUntilResume // bindAppsRemoved
D/PMS     (  908): releaseWL(438aadc8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mmsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
I/[PluginManager]RegisterService( 1339): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1339): handle notify Blinkfeed plugin client changed
I/InputMethodManagerService(  908): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/Prism.PackageStateRece_( 1270): action: android.intent.action.PACKAGE_REMOVED
W/AccTypeManager( 1326): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1326): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "sms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "smsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
I/IcingCorporaProvider( 2859): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mmsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
D/PhoneApp( 1236): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  908): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4881 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/ExternalAccountType( 1326): Unsupported attribute readOnly
D/PMS     (  908): acquireWL(429be7b0): PARTIAL_WAKE_LOCK  Icing 0x1 2190 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2859): UpdateCorporaTask done [took 155 ms] updated apps [took 155 ms] 
W/PackageManager(  908): Unable to load service info ResolveInfo{41e57450 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
E/SQLiteDatabase( 4881): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4881): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4881): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4881): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4881): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4881): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4881): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4881): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4881): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4881): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4881): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4881): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4881): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4881): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4881): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4881): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4881): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4881): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4881): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4881): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4881): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4881): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4881): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4881): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4881): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4881): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4881): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4881): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4881): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4881): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4881): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4881): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4881): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4881): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4881): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4881): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4881): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4881): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4881): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4881): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4881): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4881): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4881): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4881): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4881): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4881): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4881): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4881): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4881): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4881): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4881): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4881): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4881): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4881): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4881): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4881): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4881): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4881): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4881): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4881): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4881): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4881): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4881): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4881): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4881): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4881): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4881): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4881): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4881): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4881): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4881): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4881): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4881): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4881): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4881): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4881): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4881): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4881): threadid=11: thread exiting with uncaught exception (group=0x41729e30)
E/ActivityManager(  908): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4881): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4881): Process: com.google.android.apps.docs, PID: 4881
E/AndroidRuntime( 4881): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4881): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4881): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4881): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4881): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4881): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4881): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4881): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4881): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4881): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4881): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4881): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4881): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4881): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4881): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4881): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4881): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4881): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4881): 	at aho.run(AbstractDatabaseInstance.java:455)
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
D/Process ( 4881): killProcess, pid=4881
D/Process ( 4881): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  908): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4899 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  908): Recipient 4881
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Process com.google.android.apps.docs (pid 4881) has died.
D/RemoteDisplayProvider(  908): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  908): start
W/AtomicFile(  908): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  908): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
W/ContextImpl( 4899): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 4899): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4899): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4899): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4899): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4899): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4899): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4899): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4899): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4899): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4899): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4899): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4899): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4899): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4899): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4899): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4899): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4899): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4899): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4899): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4899): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4899): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4899): threadid=10: thread exiting with uncaught exception (group=0x41729e30)
I/ActivityManager(  908): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4912 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/AndroidRuntime( 4899): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4899): Process: com.android.keychain, PID: 4899
E/AndroidRuntime( 4899): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4899): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4899): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4899): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4899): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4899): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4899): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4899): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4899): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4899): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4899): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4899): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4899): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4899): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4899): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4899): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4899): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4899): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4899): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4899): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  908): App crashed! Process: com.android.keychain
D/ErrorReport(  908): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4899): killProcess, pid=4899
D/Process ( 4899): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  908): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  908): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1450737862257.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  908): Recipient 4899
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Process com.android.keychain (pid 4899) has died.
W/ActivityManager(  908): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/AppTag  ( 4912): getInstance(Context context)
D/AppTag  ( 4912): getInstance(Context context)
D/AppTag  ( 4912): onCreate()
D/PMS     (  908): acquireWL(43638890): PARTIAL_WAKE_LOCK  AsyncService 0x1 3597 10160 null
D/PMS     (  908): releaseWL(43638890): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/dalvikvm( 4029): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 2190): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2190): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 2190): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2190): Module APK com.google.android.play.games already loaded
I/ActivityManager(  908): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
D/ChimeraCfgMgr( 2190): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2190): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 2190): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 2190): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 2190): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2190): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6ec47710
E/SQLiteDBG( 2190): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5cb0f248
W/dalvikvm( 2190): threadid=48: thread exiting with uncaught exception (group=0x41729e30)
E/DriveAsyncService( 2190): disk I/O error (code 3850)
E/DriveAsyncService( 2190): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2190): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2190): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2190): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2190): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2190): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2190): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2190): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2190): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2190): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2190): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2190): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2190): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2190): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2190): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2190): 	at java.lang.Thread.run(Thread.java:864)
E/ActivityManager(  908): App crashed! Process: com.google.android.gms
E/AndroidRuntime( 2190): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2190): Process: com.google.android.gms, PID: 2190
E/AndroidRuntime( 2190): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2190): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2190): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2190): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2190): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2190): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2190): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2190): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2190): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2190): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2190): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2190): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2190): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2190): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2190): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2190): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2190): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2190): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2190): 	at java.lang.Thread.run(Thread.java:864)
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
D/Process ( 2190): killProcess, pid=2190
E/SQLiteDatabase( 2190): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 2190): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2190): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2190): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2190): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2190): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2190): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2190): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2190): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2190): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2190): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2190): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2190): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2190): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2190): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2190): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2190): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 2190): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2190): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2190): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2190): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 2190): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/SQLiteDatabase( 2190): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 2190): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2190): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2190): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2190): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2190): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2190): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2190): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2190): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2190): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2190): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2190): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2190): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2190): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2190): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2190): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 2190): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 2190): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 2190): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 2190): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2190): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2190): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2190): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 2190): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 2190): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 2190): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 2190): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/PhenotypeInitializer( 2190): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/PhenotypeInitializer( 2190): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 2190): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 2190): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 2190): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/PhenotypeInitializer( 2190): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/PhenotypeInitializer( 2190): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/PhenotypeInitializer( 2190): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/PhenotypeInitializer( 2190): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2190): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2190): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 2190): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 2190): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 2190): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 2190): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 2190): 	at android.os.Looper.loop(Looper.java:157)
E/PhenotypeInitializer( 2190): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 2190
D/PMS     (  908): handleWLDeath(429be7b0): PARTIAL_WAKE_LOCK  Icing 0x1
I/ActivityManager(  908): Process com.google.android.gms (pid 2190) has died.
D/WifiService(  908): Client connection lost with reason: 4
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 10999ms
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 10996ms
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10995ms
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 10994ms
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20994ms
I/ActivityManager(  908): Resuming delayed broadcast
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20989ms
E/SQLiteLog( 1367): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1367): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x5cae0018
W/dalvikvm( 1367): threadid=1: thread exiting with uncaught exception (group=0x41729e30)
D/PMS     (  908): acquireWL(42593018): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
E/ActivityManager(  908): App crashed! Process: com.google.process.gapps
V/AlarmManager(  908): sending alarm PendingIntent{41debb70: PendingIntentRecord{424ea098 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1726399, Int=0
V/AlarmManager(  908): sending alarm PendingIntent{41fcdc38: PendingIntentRecord{42623540 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1820548, Int=1800000
V/AlarmManager(  908): sending alarm PendingIntent{4263de08: PendingIntentRecord{426d46f0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1848357, Int=0
E/AndroidRuntime( 1367): FATAL EXCEPTION: main
E/AndroidRuntime( 1367): Process: com.google.process.gapps, PID: 1367
E/AndroidRuntime( 1367): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1367): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1367): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1367): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1367): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1367): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1367): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1367): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1367): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1367): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1367): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1367): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1367): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1367): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1367): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1367): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1367): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1367): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1367): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1367): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1367): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1367): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1367): 	... 10 more
V/AlarmManager(  908): sending alarm PendingIntent{42629c48: PendingIntentRecord{426b01a0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1914478, Int=0
V/AlarmManager(  908): sending alarm PendingIntent{4264bf30: PendingIntentRecord{42673050 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450737780607, Int=900000
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
D/Process ( 1367): killProcess, pid=1367
D/Process ( 1367): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  908): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4942 uid=10098 gids={50098, 3003, 5012}
I/DeviceManagement( 4942): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4942 dbg=false s=true
I/DeviceManagement( 4942): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 4942): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 4942): WorkflowService: Starting workflow service
I/DeviceManagement( 4942): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b86e30] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4942): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4942): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 4942): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4942): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  908): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4956 uid=10099 gids={50099, 3003, 5012}
I/DeviceManagement( 4942): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 4942): SessionStateController: Checking invariants...
D/Documents( 4956): Loading roots for com.android.providers.downloads.documents
D/Documents( 4956): Loading roots for com.android.externalstorage.documents
E/SQLiteDatabase( 4956): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4956): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4956): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4956): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4956): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4956): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4956): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4956): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4956): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4956): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4956): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4956): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4956): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4956): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4956): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4956): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4956): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4956): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4956): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4956): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4956): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 4956): threadid=1: thread exiting with uncaught exception (group=0x41729e30)
E/AndroidRuntime( 4956): FATAL EXCEPTION: main
E/AndroidRuntime( 4956): Process: com.android.documentsui, PID: 4956
E/AndroidRuntime( 4956): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4956): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4956): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4956): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4956): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4956): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4956): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4956): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4956): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4956): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4956): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4956): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4956): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4956): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4956): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4956): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4956): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4956): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4956): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4956): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4956): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4956): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4956): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4956): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4956): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4956): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4956): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4956): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4956): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4956): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4956): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4956): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4956): 	... 10 more
I/ActivityManager(  908): Recipient 1367
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4970 uid=10023 gids={50023, 1028, 1015, 1023}
D/WifiService(  908): Client connection lost with reason: 4
E/ActivityManager(  908): App crashed! Process: com.android.documentsui
I/ActivityManager(  908): Start proc com.google.android.gms for broadcast com.google.android.gms/.nearby.settings.NearbyAppUninstallReceiver: pid=4982 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
D/ErrorReport(  908): HtcErrorReportManager Begin---add error logs to dropbox
E/ErrorReport(  908): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  908): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1450737862877.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  908): Pr,ocess com.google.process.gapps (pid 1367) has died.
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20741ms
D/Process ( 4956): killProcess, pid=4956
D/Process ( 4956): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/ExternalStorage( 4970): After updating volumes, found 1 active roots
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1270): loadItems() com.htc.launcher.pageview.WidgetManager@41becc70 +
I/Prism.WidgetManager( 1270): onLoadItems() +
E/SQLiteDatabase( 4942): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4942): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4942): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 4942): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 4942): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4942): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4942): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 4942): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 4942): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 4942): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 4942): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 4942): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4942): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4942): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4942): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 4942): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 4942): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 4942): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 4942): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 4942): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4942): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 4942): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 4942): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4942): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel.java:176)
E/SQLiteDatabase( 4942): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 4942): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 4942): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4942): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4942): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4942): 	at java.lang.Thread.run(Thread.java:864)
I/DeviceManagement( 4942): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4942): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4942): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
W/dalvikvm( 4982): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
E/SQLiteDatabase( 4942): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4942): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4942): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4942): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4942): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 4942): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 4942): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 4942): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 4942): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 4942): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4942): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4942): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4942): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 4942): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 4942): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 4942): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
E/SQLiteDatabase( 4942): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
E/SQLiteDatabase( 4942): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 4942): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 4942): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4942): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4942): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4942): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4982): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
W/DeviceManagement( 4942): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b86e30]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/DeviceManagement( 4942): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/DeviceManagement( 4942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/DeviceManagement( 4942): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/DeviceManagement( 4942): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/DeviceManagement( 4942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/DeviceManagement( 4942): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/DeviceManagement( 4942): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/DeviceManagement( 4942): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/DeviceManagement( 4942): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/DeviceManagement( 4942): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
W/DeviceManagement( 4942): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
W/DeviceManagement( 4942): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/DeviceManagement( 4942): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/DeviceManagement( 4942): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
W/DeviceManagement( 4942): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 4942): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 4942): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 4942): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 4942): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 4942): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 4942): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 4942): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 4942): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 4942): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 4942): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 4942): 	at com.htc.cs.dm.workflow.Packa
```
