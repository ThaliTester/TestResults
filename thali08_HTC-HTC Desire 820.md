#### Test 50650278bb431e6_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144,
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
E/cutils-trace( 4442): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4442): ====startRecUseTime====
D/htc.customization.log.level( 4442):  is 
W/CustomizationLogLevel( 4442): Level value is invalid, use default level 2
D/CustomizationManager( 4442):  Read ACC file spent 0.065 (s)
D/CIDMapFileReader( 4442): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4442): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4442): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4442): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4442): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4442): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4442): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4442): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4442): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4442): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4442): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4442): Parsing tag category name = system
I/CustomizationCIDLoader( 4442): Parsing tag category name = application
I/CustomizationCIDLoader( 4442): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4442): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4442): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4442): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4442): Parsing tag category name = Settings
D/CustomizationManager( 4442):  Read CID file spent 0.106 (s)
D/CustomizationManager( 4442):  All configurations done spent 0.106 (s)
W/HtcNativeFlag( 4442): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4442): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4442): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4442): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
W/CpuWake (  906): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  906): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4442
D/PMS     (  906): acquireHCC(432f0a68): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 906 1000 null
D/PMS     (  906): acquireHCC(432ba858): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 906 1000 null
W/asset   (  906): Copying FileAsset 0x62fe6ee0 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  906): @test_code: getHtcIntentFlag: 0 obj: 1132618800
I/FeedHostManager( 1277): [onPause]
I/FeedProviderManager( 1277): onPause
I/FeedHostManager( 1277): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41e01c68
D/PMS     (  906): acquireWL(43058720): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
I/SocialFeedProvider( 1277): +onPause
I/SocialFeedProvider( 1277): -onPause
I/ActivityManager(  906): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4453 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1277): [trimMemory] 20
W/asset   ( 4453): Copying FileAsset 0x5c86a568 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4453): Binding Chromium to main looper Looper (main, tid 1) {41ba5fc0}
I/LibraryLoader( 4453): Expected native library version number "",actual native library version number ""
I/chromium( 4453): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4453): Initializing chromium process, renderers=0
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  906): java.lang.Throwable: stack dump
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42ffa0b8:true
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/PMS     (  906): acquireWL(41cef4d8): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  906): acquireWL(41c062d0): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  906): releaseWL(41c062d0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothAdapter( 4453): 1102827392: getState(). Returning 12
I/Adreno-EGL( 4453): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4453): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4453): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4453): Local Branch: 
I/Adreno-EGL( 4453): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4453): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4453):                  aa63bbd948f41d15fc72f585e
W/chromium( 4453): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4453): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4453): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4453): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4453): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4453): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4453): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4453): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4453): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4453): CordovaWebView is running on device made by: HTC
,W/AwContents( 4453): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  906): Disable input method client, pid=1277
,W/ResourceType( 4453): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4453): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41bee630, mServedView=org.apache.cordova.engine.SystemWebView{41bb4298 VFEDH.C. .F....I. 0,0-720,1134 #64}
,I/InputMethodManagerService(  906): Enable input method client, pid=4453
W/XT9_C   ( 1210): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1210): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,W/AwContents( 4453): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  906): Displayed com.test.thalitest/.MainActivity: +294ms
,D/PMS     (  906): releaseWL(43058720): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4453): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4453): JniHelper::setJavaVM(0x41685010), pthread_self() = 1662780232
,D/JX-Cordova( 4453): jxcore cordova android initializing
,I/dalvikvm-heap( 4453): Grow heap (frag case) to 11.538MB for 96598-byte allocation
,I/dalvikvm-heap( 4453): Grow heap (frag case) to 11.621MB for 144892-byte allocation
,I/dalvikvm-heap( 4453): Grow heap (frag case) to 11.738MB for 217334-byte allocation
,I/dalvikvm-heap( 4453): Grow heap (frag case) to 11.914MB for 325996-byte allocation
,I/dalvikvm-heap( 4453): Grow heap (frag case) to 12.176MB for 488990-byte allocation
,I/dalvikvm-heap( 4453): Grow heap (frag case) to 13.174MB for 1100216-byte allocation
,D/PMS     (  906): acquireWL(42339408): PARTIAL_WAKE_LOCK  Icing 0x1 2870 10028 null
,D/PMS     (  906): releaseWL(42339408): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  906): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4499 uid=10077 gids={50077}
,D/PMS     (  906): acquireWL(42486e38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10077}
,V/AlarmManager(  906): sending alarm PendingIntent{421aa648: PendingIntentRecord{423c2e70 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1450653053178, Int=60000
,D/PMS     (  906): releaseWL(42486e38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/PMS     (  906): acquireWL(4216aa40): PARTIAL_WAKE_LOCK  Icing 0x1 2870 10028 null
,D/SMSBackup( 4499): SMSBackupAgentService started
,D/SMSBackup( 4499): Checking restore status
D/SMSBackup( 4499): Restore complete
,D/SMSBackup( 4499): cancelCheckAlarm
,D/PMS     (  906): releaseWL(4216aa40): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/SMSBackup( 4499): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  906): killProcessQuiet, pid=3555
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  906): acquireWL(4246bcf8): PARTIAL_WAKE_LOCK  Icing 0x1 2870 10028 null
I/ActivityManager(  906): Killing 3555:com.android.defcontainer/u0a19 (adj 15): empty #17
,D/PMS     (  906): releaseWL(4246bcf8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/dalvikvm-heap( 4453): Grow heap (frag case) to 14.087MB for 1650320-byte allocation
D/PMS     (  906): acquireWL(42466548): PARTIAL_WAKE_LOCK  Icing 0x1 2870 10028 null
,D/PMS     (  906): releaseWL(42466548): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  906): Recipient 3555
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4453): Grow heap (frag case) to 15.434MB for 2475476-byte allocation
,W/CpuWake (  906): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  906): <<release mCpuPerf_Freq wakelock
,D/PMS     (  906): releaseHCC(432f0a68): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  906): releaseHCC(432ba858): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/SensorManager(  906): mEventCount = 1350
,I/dalvikvm-heap( 4453): Grow heap (frag case) to 17.455MB for 3713210-byte allocation
,W/PluginManager( 4453): THREAD WARNING: exec() call to JXcore.isReady blocked the main thread for 30ms. Plugin should use CordovaInterface.getThreadPool().
,W/jxcore-log( 4453): Initializing JXcore engine
,W/jxcore-log( 4453): JXcore engine is ready
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,W/jxcore-log( 4453): Starting JXcore engine
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1167): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,W/jxcore-log( 4453): Platform android
W/jxcore-log( 4453): 
,W/jxcore-log( 4453): Process ARCH arm
W/jxcore-log( 4453): 
,D/PMS     (  906): releaseWL(41cef4d8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4453): JXcore Cordova bridge is ready!
I/jxcore-log( 4453): 
,W/jxcore-log( 4453): JXcore engine is started
,I/chromium( 4453): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=92 rxSum=91} preTxRxSum={txSum=91 rxSum=90}
D/WifiDataStallTracker(  906): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  906): onDataStallAlarm: tag=20779 Sent 0 pkts since last received, < watchdogTrigger=5
D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20780 delay=15s
D/PMS     (  906): acquireWL(42682bc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{42669f08: PendingIntentRecord{425d8908 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=103084, Int=0
D/PMS     (  906): releaseWL(42682bc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4453): Toggling radios to true
I/jxcore-log( 4453): 
,D/BluetoothAdapter( 4453): enable(): BT is already enabled..!
,D/WifiManager( 4453): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  906): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 2
W/Settings:Agent(  906): >> traceCallingStack()
W/Settings:Agent(  906): Process.myPid(): 906
W/Settings:Agent(  906): Process.myTid(): 1276
W/Settings:Agent(  906): Process.myUid(): 1000
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
,W/System.err(  906): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  906): 
W/Settings:Agent(  906): << traceCallingStack(): 1(ms)
,D/WifiManager( 4453): disconnect: Base Package Name=com.test.thalitest, uid=10348
D/WifiNative-wlan0(  906): doBoolean: DISCONNECT
D/WifiManager( 4453): reconnect: Base Package Name=com.test.thalitest, uid=10348
D/WifiService(  906): New client listening to asynchronous messages,
D/WifiService(  906): setWifiEnabled: true pid=4453, uid=10348
E/WifiService(  906): Invoking mWifiStateMachine.setWifiEnabled,
I/WifiService(  906): isSprintWifiRestricted(): false
I/WifiService(  906): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  906): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): TDLS: Tear down peers
I/wpa_supplicant( 1167): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4453): Radios toggled
I/jxcore-log( 4453): 
D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4453): Got Device Bluetooth address: 80:01:84:8A:B3:68
I/jxcore-log( 4453): 
I/jxcore-log( 4453): Perf Test app loaded loaded
I/jxcore-log( 4453): 
I/Choreographer( 4453): Skipped 79 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 4453): check test folder
I/jxcore-log( 4453): 
,I/jxcore-log( 4453): found test : ./testFindPeers.js
I/jxcore-log( 4453): 
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1167): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1167): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,I/wpa_supplicant( 1167): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1167): TDLS: Remove peers on disassociation
D/HTCRequest(  906): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  906): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1167): send_and_recv error -67 - cmd 12
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1167): send_and_recv error -67 - cmd 12
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  906): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1167): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1167): send_and_recv error -67 - cmd 12
D/HTCRequest(  906): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb7e4bbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1167):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1167): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1167): netlink: Operstate: linkmode=-1, operstate=5
D/HTCRequest(  906): WifiMonitor:getReasonFromEventString() 3
I/wpa_supplicant( 1167): htc_wext_set_TX_TRACKING (0)+
D/HTCRequest(  906): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1167): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1167): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1167): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1167): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  906): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1167): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1167): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1167): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( ,1167): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1167): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1167): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1167): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1167): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1167): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1167): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1167): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1167): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1167): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1167): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1167): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1167): nl80211: Ignore disconnect event triggered during reassociation
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  906): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
,D/WifiNative-wlan0(  906):    returned true
,D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
,D/WifiPerfLock(  906): release()
,D/WifiStateMachine(  906): PerfLock released for exiting ConnectedState
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1167): Power_Mode_Type mode = 0
I/wpa_supplicant( 1167): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  906):    returned true
D/ConnectivityService(  906): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  906): acquireWL(426de238): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 906 1000 null
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
I/jxcore-log( 4453): found test : ./testSendData.js
I/jxcore-log( 4453): 
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
D/DhcpStateMachine(  906): [RunningState] Stop DHCP
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  906): doBoolean: RECONNECT
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): Fast associate: Old scan results
I/wpa_supplicant( 1167): wpa_supplicant_scan enter
I/wpa_supplicant( 1167): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1167): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1167): wpa_supplicant_trigger_scan +
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 33
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
I/wpa_supplicant( 1167): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): Enter handleNetworkDisconnect
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=20780 mDataStallAlarmIntent=PendingIntent{425445d0: PendingIntentRecord{425d8908 android broadcastIntent}}
D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1167): Power_Mode_Type mode = 0
I/wpa_supplicant( 1167): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 61
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1167): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
D/UsbnetStateTracker(  906): isAvailable+-
D/UsbnetStateTracker(  906): reconnect
,D/UsbnetStateTracker(  906): isAvailable+-
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  906): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1826/10178)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  906): default: reconnect()
D/MDST    (  906): default: setTeardownRequested(false)
D/MDST    (  906): default: setEnableApn apnType =default , enable=true
,D/WifiStateMachine(  906): Exit handleNetworkDisconnect
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 3837): >>>>>WISPrService start isConnected = false<<<<<
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  906): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  906): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
,D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 3837): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiService(  906): New client listening to asynchronous messages
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  906): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1826/10178)
D/WISPrService( 3837): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3837): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,I/jxcore-log( 4453): found test : ./testSendData2.js
I/jxcore-log( 4453): 
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/ConnectivityService(  906): resetConnections(wlan0, 3)
D/libc    (  365): [NET] entry_id:5   entry:0xb79da110  removed 
D/libc    (  365): [NET] entry_id:7   entry:0xb79da6f0  removed 
D/libc    (  365): [NET] entry_id:6   entry:0xb79da818  removed 
D/libc    (  365): [NET] entry_id:4   entry:0xb79da310  removed 
D/libc    (  365): [NET] entry_id:2   entry:0xb79da248  removed 
D/libc    (  365): [NET] entry_id:8   entry:0xb79d9d90  removed 
D/libc    (  365): [NET] entry_id:3   entry:0xb79d9fd8  removed 
D/libc    (  365): [NET] entry_id:1   entry:0xb79da410  removed 
,D/libc    (  365): *************************
D/libc    (  365): *** DNS CACHE FLUSHED ***
D/libc    (  365): *************************
,E/jxcore  ( 4453): Error!: unlabeled break must be inside loop or switch
E/jxcore  ( 4453): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
,D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/PMS     (  906): acquireWL(42401938): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1379 10028 null
D/ConnectivityService(  906): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  906): acquireWL(42713e10): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
,D/ConnectivityService(  906): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:1
D/WifiStateMachine(  906): startScan Pid: 906 Uid 1000
,D/WifiNative-wlan0(  906): doBoolean: SCAN
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1167): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
I//system/bin/ip(  365): RTNETLINK answers: No such process
I/logwrapper(  365): /system/bin/ip terminated by exit(2)
,D/WifiNative-wlan0(  906):    returned false
,I/chromium( 4453): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/BatSI   (  906): WIFI scan started for: 650a0300 uid:1000
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:0
D/PMS     (  906): acquireWL(426189e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1379 10028 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1379/10028)
D/ConnectivityService(  906): reportInetCondition for net -1, percentage: 0 by  (1379/10028)
D/PMS     (  906): releaseWL(426189e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  906): mActiveDefaultNetwork: -1
D/ConnectivityService(  906): handleInetConditionChange: no active default network - ignore
D/PMS     (  906): releaseWL(42401938): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1379/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1379/10028)
,D/PMS     (  906): releaseWL(42713e10): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: false
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4343/10100)
,D/PMS     (  906): acquireWL(4422cb40): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  906): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
,D/Tethering(  906): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/CaptivePortalTracker(  906): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  906): NoActiveNetworkState,
D/PMS     (  906): releaseWL(4422cb40): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1884/1000)
,D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1826/10178)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1277/10075)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1475/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4343/10100)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3928/10154)
V/Tethering(  906): bSetPropertyMultiRAB:false
D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/ConnectivityHelper( 1277): [onReceive] WIFI(1): DISCONNECTED
,I/Tethering(  906): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  906): ipv4Default null
I/Tethering(  906): No IPv4 upstream interface, giving up.
D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
I/NetworkMonitor( 3928): type=WIFI subType= reason=null isConnected=false
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (2759/10021)
,I/ActivityManager(  906): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4524 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4524): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4524): Looking for error files in /data/data/com.facebook.katana/app_acra-reports,
,D/ACRA    ( 4524): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4524): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4524): Preparing secondary program dexes.
V/DexLibLoader( 4524): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4524): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4524): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
,V/DexLibLoader( 4524): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4524): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4524): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4524): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4524): Dex already copied
D/OdexVerifier( 4524): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4524): Creating class loader
,V/DexLibLoader( 4524): Finished creating class loader
V/DexLibLoader( 4524): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4524): Dex already copied
D/OdexVerifier( 4524): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4524): Creating class loader
,V/DexLibLoader( 4524): Finished creating class loader
V/DexLibLoader( 4524): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4524): Dex already copied
D/OdexVerifier( 4524): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4524): Creating class loader
,V/DexLibLoader( 4524): Finished creating class loader
V/DexLibLoader( 4524): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4524): Dex already copied
D/OdexVerifier( 4524): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4524): Creating class loader
,V/DexLibLoader( 4524): Finished creating class loader
,V/DexLibLoader( 4524): Verifying classes from secondary dexes.
,D/DexLibLoader( 4524): DexLibLoader.ensureDexLoaded took 24 ms
,W/dalvikvm( 4524): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4524): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4524): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4524): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4524): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4524): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4524): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4524): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1167): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1167): nl80211: Survey data missing
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1167): Sorted scan results
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1167): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1167): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1167): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-77
I/wpa_supplicant( 1167): [NULL] fe:94:e3:11:35:3c freq=2462 level=-87
I/wpa_supplicant( 1167): [NULL] fc:94:e3:11:35:3a freq=2462 level=-88
I/wpa_supplicant( 1167): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
D/wpa_supplicant( 1167): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1167): Add randomness: count=7 entropy=0
D/wpa_supplicant( 1167): Add randomness: count=8 entropy=1
D/wpa_supplicant( 1167): Add randomness: count=9 entropy=2
D/wpa_supplicant( 1167): Add randomness: count=10 entropy=3
D/wpa_supplicant( 1167): Add randomness: count=11 entropy=4
D/wpa_supplicant( 1167): Add randomness: count=12 entropy=5
D/wpa_supplicant( 1167): Add randomness: count=13 entropy=6
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1167): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1167): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1167): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1167): wpa_supplicant_pick_network+
I/wpa_supplicant( 1167): Selecting BSS from priority group 1
I/wpa_supplicant( 1167): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1167): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1167): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1167): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1167):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1167):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-50
I/wpa_supplicant( 1167): Start print parameters
I/wpa_supplicant( 1167): wpa_s->wpa_state is 3
I/wpa_supplicant( 1167): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1167): isConcurrentMode() is 0
I/wpa_supplicant( 1167): wpa,_s->br_mirror_status is 0
I/wpa_supplicant( 1167): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1167): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1167): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1167): wpa_s->reassociate is 1
I/wpa_supplicant( 1167): wpa_s->is_screen_on 1
I/wpa_supplicant( 1167): wpa_s->ifname wlan0
I/wpa_supplicant( 1167): End print parameters
I/wpa_supplicant( 1167): selected network = 1
D/wpa_supplicant( 1167): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb7e4d4e8  current_ssid=0x0
D/wpa_supplicant( 1167): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1167): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1167): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1167): check if in concurrent case
,I/wpa_supplicant( 1167): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz),
D/wpa_supplicant( 1167): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1167): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1167): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1167): RSN: PMKSA cache search - network_ctx=0xb7e4d4e8 try_opportunistic=0
D/wpa_supplicant( 1167): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1167): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1167): State: SCANNING -> ASSOCIATING,
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1167): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1167): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1167): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1167): nl80211: Unsubscribe mgmt frames handle 0xb7e4c718 (mode change)
D/wpa_supplicant( 1167): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7e4c718,
D/wpa_supplicant( 1167): nl80211: Register frame type=0xd0 nl_handle=0xb7e4c718
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1167): nl80211: Register frame type=0xd0 nl_handle=0xb7e4c718
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1167): nl80211: Register frame type=0xd0 nl_handle=0xb7e4c718
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1167): nl80211: Register frame type=0xd0 nl_handle=0xb7e4c718
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1167): nl80211: Register frame type=0xd0 nl_handle=0xb7e4c718
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1167): nl80211: Register frame type=0xd0 nl_handle=0xb7e4c718
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1167): nl80211: Register frame type=0xd0 nl_handle=0xb7e4c718
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1167): nl80211: Register frame type=0xd0 nl_handle=0xb7e4c718
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1167): nl80211: Register frame type=0xd0 nl_handle=0xb7e4c718
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1167): nl80211: Register frame type=0xd0 nl_handle=0xb7e4c718
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1167): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1167):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1167):   * freq=2412
D/wpa_supplicant( 1167):   * Auth Type 0
D/wpa_supplicant( 1167):   * WPA Versions 0x2
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1167): nl80211: Connect request send successfully
D/wpa_supplicant( 1167): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1167): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1167): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
W/dalvikvm( 4524): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1167): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1167): reply (906) for get BSS: id=0
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1167): freq=5220
I/wpa_supplicant( 1167): level=-48
I/wpa_supplicant( 1167): tsf=0000000106361289
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG7005g
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=1
I/wpa_supplicant( 1167): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-50
I/wpa_supplicant( 1167): tsf=0000000106361307
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=NG700
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=2
I/wpa_supplicant( 1167): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1167): freq=2437,
I/wpa_supplicant( 1167): level=-77
I/wpa_supplicant( 1167): tsf=0000000106361310
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1167): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=3
I/wpa_supplicant( 1167): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1167): freq=2462
I/wpa_supplicant( 1167): level=-88
I/wpa_supplicant( 1167): tsf=0000000106361317
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=UPC0039325
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=4
I/wpa_supplicant( 1167): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): freq=2412
I/wpa_supplicant( 1167): level=-50
I/wpa_supplicant( 1167): tsf=0000000106361302
I/wpa_supplicant( 1167): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1167): ssid=01ABC
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=5
,I/wpa_supplicant( 1167): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1167): freq=2462
I/wpa_supplicant( 1167): level=-87
I/wpa_supplicant( 1167): tsf=0000000106361314
I/wpa_supplicant( 1167): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1167): ssid=UPC Wi-Free
I/wpa_supplicant( 1167): ====
I/wpa_supplicant( 1167): id=6
I/wpa_supplicant( 1167): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1167): freq=2437
I/wpa_supplicant( 1167): level=-90
I/wpa_supplicant( 1167): tsf=0000000106361321
I/wpa_supplicant( 1167): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1167): ssid=UPC4688432
I/wpa_supplicant( 1167): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): == begin of scan result ==
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 106361289, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 2412, timestamp: 106361307, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -77, frequency: 2437, timestamp: 106361310, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 106361317, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -50, frequency: 2412, timestamp: 106361302, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -87, frequency: 2462, timestamp: 106361314, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 6: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 106361321, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 7 to mScanResults
D/BatSI   (  906): WIFI scan stopped for: 640a0300 uid:1000
,D/WifiStateMachine(  906): == (7) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,E/FbInjectorInitializer( 4524): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/wpa_supplicant( 1167): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1167): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1167): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1167): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1167): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1167): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1167): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1167): nl80211: Event message available
D/wpa_supplicant( 1167): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1167): nl80211: Connect event
D/wpa_supplicant( 1167): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1167): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1167): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1167): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1167): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1167): Add randomness: count=14 entropy=7
I/wpa_supplicant( 1167): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1167): TDLS: Remove peers on association
D/wpa_supplicant( 1167): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1167): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1167): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1167): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1167): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1167): EAPOL: enable timer tick
D/wpa_supplicant( 1167): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1167): htc_wext_set_keepalive +
I/wpa_supplicant( 1167): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1167): getPrivFuncNum +	
I/wpa_supplicant( 1167): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1167): htc_wext_set_keepalive fnum = 0x8bf6
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  906): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  906): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  906): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  906): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  906): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  906): handleAssociatedWithEvent. wifiSsid ='NG700' freq,=2412
D/WifiStateMachine(  906): Enter handleAssociatedWithEvent
D/WifiStateMachine(  906): Associated
D/WifiStateMachine(  906): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  906): Exit handleAssociatedWithEvent
I/wpa_supplicant( 1167): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1167): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1167): Get randomness: len=32 entropy=8
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  906): BSSID was changed, update WiFi database
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
D/Tethering(  906): interfaceStatusChanged wlan0, true
D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  906): This record is existed, only update it...
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/Tethering(  906): [isWifi] getHotspotEnabled: false
I/wpa_supplicant( 1167): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb7e4c9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1167):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1167): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1167): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f1cb4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1167):    broadcast key
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1167): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1167): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1167): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1167): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1167): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1167): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 1167): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1167): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1167): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1167): set send_ind_to_ndc = 0
I/wpa_supplicant( 1167): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1167): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1167): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1167): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1167): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1167): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1167): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1167): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1167): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1167): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1167): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1167): EAPOL authentication completed successfully
I/wpa_supplicant( 1167): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/WifiMonitor(  906): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1167): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1167): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1167): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
D/Tethering(  906): interfaceStatusChanged wlan0, true
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/WifiStateMachine(  906): fetchFrequency(), freq = 2412
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  906): This record is existed, only update it...
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  906): updateConnectedAP...
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): mActiveDefaultNetwork: -1
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/WISPrService( 3837): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 3837): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/DhcpStateMachine(  906): [StoppedState] Start DHCP
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): handlePreDhcpSetup Held wake lock during DHCP
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1167): Power_Mode_Type mode = 1
I/wpa_supplicant( 1167): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  906):    returned null
E/WifiStateMachine(  906): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/WifiNative-wlan0(  906):    returned null
D/PMS     (  906): acquireWL(44102358): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 906 1000 null
D/WifiStateMachine(  906): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@423efbd0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@423efbd0 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:1
,W/fb4a(:<default>):StaticBindingVerifier( 4524): Verify
,D/WifiService(  906): New client listening to asynchronous messages
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4524): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4524): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4524): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  906): killProcessQuiet, pid=4277
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 4277:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,D/PMS     (  906): acquireWL(4415aeb8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2870 10028 null
,I/ActivityManager(  906): Recipient 4277
D/PMS     (  906): acquireWL(4270db28): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2870 10028 null
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): releaseWL(4415aeb8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/WifiService(  906): Client connection lost with reason: 4
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2870/10028)
,D/GCM     ( 1379): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1379/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1379/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1379/10028)
,D/PMS     (  906): releaseWL(4270db28): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2870/10028)
,D/AutoSetting( 1434): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  906): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4553 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1434/10053)
,D/AutoSetting( 1434): Util - no network available!
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1434/10053)
D/AutoSetting( 1434): service - onCreate()
D/AutoSetting( 1434): service - AddressCache: using context: com.htc.Weather
D/LocationManagerService(  906): request 424ca590 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/LocationManagerService(  906): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1434): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1434): service - mHandler: cancel location update
D/AutoSetting( 1434): service -           changes count: 0
,W/fb4a(:<default>):UserScope( 4524): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4524): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4524): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4553): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4553): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4553): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4553): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  906): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4569 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4553/10078)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4553/10078)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4553/10078)
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4524): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  906): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4586 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=3889
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/ActivityManager(  906): Killing 3889:com.htc.mediamanager/u0a32 (adj 15): empty #17
E/dalvikvm( 4524): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
W/dalvikvm( 4524): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4524): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 4524): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4524): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 4524): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4524): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4524): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4524): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4524): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4524): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4524): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4524): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4524): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4524): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4524): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
,I/dalvikvm-heap( 4524): Grow heap (frag case) to 9.964MB for 84664-byte allocation
W/dalvikvm( 4524): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4524): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4586): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4586): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4586): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4586): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4586): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
I/ActivityManager(  906): Recipient 3889
,W/Vold    (  348): Returning OperationFailed - no handler for errno 30
I/dalvikvm-heap( 4524): Grow heap (frag case) to 9.990MB for 39954-byte allocation
,I/dalvikvm-heap( 4524): Grow heap (frag case) to 10.067MB for 79892-byte allocation
,I/dalvikvm-heap( 4524): Grow heap (frag case) to 10.093MB for 28144-byte allocation
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4586/10151)
,V/WebViewChromiumFactoryProvider( 4586): Binding Chromium to main looper Looper (main, tid 1) {41bac158}
,I/LibraryLoader( 4586): Expected native library version number "",actual native library version number ""
,I/chromium( 4586): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4586): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4586): BLUETOOTH permission is missing!
D/PMS     (  906): acquireWL(4410b778): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  906): acquireWL(429da928): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  906): releaseWL(429da928): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4586): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4586): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4586): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4586): Local Branch: 
I/Adreno-EGL( 4586): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4586): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4586):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4586): Starting up...
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4586/10151)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4586/10151)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4121/10160)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4121/10160)
,D/Process (  906): killProcessQuiet, pid=4311
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 4311:com.google.android.partnersetup/u0a31 (adj 15): empty #17
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1826/10178)
,I/dalvikvm-heap( 4524): Grow heap (frag case) to 10.281MB for 75760-byte allocation
,D/GCM     ( 1379): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1826/10178)
I/ActivityManager(  906): Recipient 4311
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
,W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43bc5880 u0 ReceiverList{43bc5760 4524 com.facebook.katana/10026/u0 remote:43b62558}}
,W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43bc5880 u0 ReceiverList{43bc5760 4524 com.facebook.katana/10026/u0 remote:43b62558}}
,W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{440e74a8 u0 ReceiverList{43ccb958 4524 com.facebook.katana/10026/u0 remote:44093888}}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
,D/PMS     (  906): acquireWL(431e90c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1475 10028 null
,D/PMS     (  906): releaseWL(431e90c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/GCoreFlp( 1475): Unknown pending intent to remove.
D/PMS     (  906): acquireWL(43c7ced8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1475 10028 null
D/PMS     (  906): releaseWL(43c7ced8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/wpa_supplicant( 1167): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1167): EAPOL: disable timer tick
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4524): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4524): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,I/PMS     (  906): Going to sleep due to screen timeout...
,I/ActivityManager(  906): mThumbnailWidth=360, mThumbnailHeight=640
I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@422683e8
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Light sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@422683e8, eanble = 0, strlen(mName) = 59
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42314930
W/SensorService(  906): Listener[1] = com.htc.smartdim.sensor_eye@41b9cc18
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
V/LightsService(  906): setLight #2: color=#0
D/qdlights(  906): set_light_buttons_func: on=0 brightness=0
V/LightsService(  906): setLight #0: color=#0
W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/WirelessDisplayService(  906): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  906): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  906): mWirelessDisplayManager is null
,D/SurfaceControl(  906): Excessive delay in blankDisplay() while turning screen off: 380ms
D/PMS     (  906): nativeSetInteractive:false
D/PMS     (  906): nativeSetInteractive:false done
D/PMS     (  906): nativeSetAutoSuspend:true
D/PMS     (  906): nativeSetAutoSuspend:true done
D/NfcService( 1260): ScreenObserver: OFF
,D/NfcService( 1260): applyRouting - 0
D/HABCtrl (  906): TPE algorithm. remove timeout.
D/PMS     (  906): OOBE c monitor 11
I/InputManager(  906): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  906): screenObserver, isScreenOn=false
,I/InputMethodManagerService(  906): Disable input method client, pid=4453
,V/KeyguardServiceDelegate(  906): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@426cfca0)
,D/NfcService( 1260): applyRouting -2
,V/KeyguardServiceDelegate(  906): **** SHOWN CALLED ****
D/PMN     (  906): wakingUp
D/PMS     (  906): acquireWL(44209710): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1260 1027 null
D/PMS     (  906): releaseWL(44209710): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/WindowManager(  906): No lock screen! windowToken=null
,D/PMS     (  906): acquireWL(431a8928): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/PMN     (  906): onScreenOn
V/AlarmManager(  906): sending alarm PendingIntent{4244a3a8: PendingIntentRecord{42449490 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=107999, Int=0
,W/ResourceType( 4453): No package identifier when getting name for resource number 0x00000064
I/IntentController( 1119): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,I/InputMethodManager( 4453): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41bb4298 VFEDH.C. .F...... 0,0-720,1134 #64}
D/PMS     (  906): acquireWL(4349d268): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,I/ClockThread( 1119): now=1450653060014 next=59986
D/WirelessDisplayService(  906): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): releaseWL(4349d268): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1571): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/MtpService( 2759): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/NfcService( 1260): applyRouting - 0
,D/MtpService( 2759): [MTP][onReceive]-
D/AutoSetting( 1434): receiver - intent: android.intent.action.USER_PRESENT
,D/NfcService( 1260): applyRouting -2
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
D/PMS     (  906): acquireWL(440d57b8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1260 1027 null
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  906): releaseWL(440d57b8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/AutoSetting( 1434): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_ON
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/TetherSettings( 3837): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3837): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3837): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3837): Cust_ConnectToPC   : spcsc>false
D/        ( 3837): Cust_ConnectToPC   : IPT>true
D/        ( 3837): Cust_ConnectToPC   : Singel_USB>false
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1167): SET_SCREEN_ON:On
I/wpa_supplicant( 1167): htc_wext_set_keepalive +
I/wpa_supplicant( 1167): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1167): getPrivFuncNum +	
W/Settings( 3837): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/wpa_supplicant( 1167): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1167): htc_wext_set_keepalive fnum = 0x8bf6
E/SmartNS_Utility( 3837): hasRemovableStorageSlot: true
I/wpa_supplicant( 1167): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1167): htc_wext_set_TX_TRACKING (1)+
D/SmartNS_Utility( 3837): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
I/wpa_supplicant( 1167): htc_wext_set_TX_TRACKING - ret = 0
D/SmartNS_NSReceiver( 3837): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/WifiNative-wlan0(  906):    returned true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=100 [1][1][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -49 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/AlarmManager(  906): ACTION_SCREEN_ON
I/AlarmManager(  906): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done recovering
I/AlarmManager(  906): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  906): [AlarmQueuing] done EPS screen off alarm recovering
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
I/PSReceiver( 3837): onReceive:android.intent.action.USER_PRESENT
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
I/SmartNS_PSService( 3837): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3837): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3837):  defaultType:0
,I/ClockThread( 1119): stop update clock
W/ContextImpl( 3837): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,V/SRS_Proc(  372): ParamSet string: screen_state=on
,D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
D/NetworkPolicy(  906): updateScreenOn: false
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4648 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1167): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1167): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1167): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/WifiP2pService(  906): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  906): releaseWL(44102358): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1167): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/DotMatrix( 1571): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/WifiStateMachine(  906): gateway: /192.168.1.1
,D/WifiNative-wlan0(  906): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
,D/WIFI_ICON( 1119): updateWifiState: RSSI_CHANGED -1 -> 3
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1167): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  906): VerifyingLinkState enter
D/WifiStateMachine(  906): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  906): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  906): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -50, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/PMS     (  906): acquireWL(434ac9f0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1475 10028 null
,D/PMS     (  906): releaseWL(434ac9f0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1799): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1799): onScreenOn: 1450653060272
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1799): onScreenOn: 1450653060272
,D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20782 delay=15s
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiWatchdogStateMachine(  906): WAN detection
V/NetworkPolicy(  906): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED connected
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  906): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  906): default: teardown()
D/MDST    (  906): default: setTeardownRequested(true)
D/MDST    (  906): default: setEnableApn apnType =default , enable=false
W/ContextImpl( 4648): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42314930
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42314930, eanble = 0, strlen(mName) = 91
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  906): Listener[0] = com.htc.smartdim.sensor_eye@41b9cc18
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/WISPrService( 3837): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/PMN     (  906): goingToSleep
D/MDST    (  906): default: setTeardownRequested(true)
,D/ConnectivityService(  906): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  906): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  906): syncGetConfiguredNetworks
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/PMS     (  906): acquireWL(43cec900): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 906 1000 null
E/ConnectivityService(  906): Unexpected mtu value: android.net.wifi.WifiStateTracker@424d3dc8
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/WIFI_ICON( 1119): WifiActivity: 3
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  906): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/SmartSyncUtils( 4648): isEpsOn(), nState = 0
D/ConnectivityService(  906): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/PMS     (  906): acquireWL(42b451a8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4648 1000 null
D/ConnectivityService(  906): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
,D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/libc    (  365): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
,I/QuickSettingWifi( 1119): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/PMS     (  906): releaseWL(43cec900): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/ConnectivityService(  906): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  906): acquireWL(427229f8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/WirelessDisplayService(  906): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  906):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4553/10078)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/PMS     (  906): releaseWL(431a8928): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  906): releaseWL(42b451a8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/AlarmManager(  906): ACTION_SCREEN_OFF
I/AlarmManager(  906): [AlarmQueuing] screen off now: 
I/AlarmManager(  906): [AlarmQueuing] data connection: true
,I/AlarmManager(  906): [AlarmQueuing] wifi connection: true
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL,
D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_OFF
D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=20782 mDataStallAlarmIntent=PendingIntent{41c36570: PendingIntentRecord{425d8908 android broadcastIntent}}
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 0
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1167): SET_SCREEN_ON:Off
I/wpa_supplicant( 1167): htc_wext_set_keepalive +
I/wpa_supplicant( 1167): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1167): getPrivFuncNum +	
I/wpa_supplicant( 1167): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1167): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1167): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1167): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1167): htc_wext_set_keepalive - ret = 0
D/PMS     (  906): releaseWL(427229f8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/PMS     (  906): acquireWL(440a9890): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 906 1000 null
D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 1
D/WifiNative-wlan0(  906):    returned true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
V/SRS_Proc(  372): ParamSet string: screen_state=off
,D/SmartSyncUtils( 4648): getMobilePolicyEnabled, result = true
,D/wpa_supplicant( 1167): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  906):    returned true
I//system/bin/ip(  365): RTNETLINK answers: No such file or directory
,I/logwrapper(  365): /system/bin/ip terminated by exit(254)
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  906): killProcessQuiet, pid=4343
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/ContactMessageStore( 1248): start background delete task...
D/PMS     (  906): releaseWL(440a9890): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
I/ActivityManager(  906): Killing 4343:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1826/10178)
D/ContactMessageStore( 1248): size: 0 , 0
D/ContactMessageStore( 1248): Background delete complete
,I/ActivityManager(  906): Recipient 4343
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
W/ContextImpl( 4648): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4648): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4648): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4648): isEpsOn(), nState = 0
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/WifiService(  906): New client listening to asynchronous messages
D/ConnectivityService(  906): mActiveDefaultNetwork: WIFI
D/NetworkPolicy(  906): updateScreenOn: false
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
D/DotMatrix( 1571): [EventService] getTotalRam: 1873 Mb
I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41b9cc18
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 1
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41b9cc18, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 0
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41b9cc18, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41b9cc18
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1799): onScreenOff.
D/PMS     (  906): acquireWL(43025f80): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1475 10028 null
D/PMS     (  906): releaseWL(43025f80): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1799): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1799): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1799): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1799): onScreenOff
D/AutoSetting( 1434): service - mHandler: cancel location update
,D/AutoSetting( 1434): service -           changes count: 0
E/ActivityThread(  906): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@421623a8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@421623a8 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/PMS     (  906): acquireWL(426c8290): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2870 10028 null
,D/PMS     (  906): acquireWL(43106b08): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2870 10028 null
,D/PMS     (  906): releaseWL(426c8290): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,I/CheckinService( 2870): Preparing to send checkin request
,I/EventLogService( 2870): Accumulating logs since 1450653002848
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2870/10028)
,I/GoogleHttpClient( 2870): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2870): Using GMS GoogleHttpClient
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (2870/10028)
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (2870/10028)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,W/GLSUser ( 1379): GoogleAccountDataService.getToken()
,W/GLSActivity( 1379): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1379): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1379): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1571): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1571): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 2870): awaiting user notification for token
,I/RemoteViews( 1119): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41bf3c28 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1119): com.google.android.gms 1 11 4 12
,I/ActivityManager(  906): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4695 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 4695): install
,I/MultiDex( 4695): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4695): loading existing secondary dex files
,I/MultiDex( 4695): load found 1 secondary dex files
,I/MultiDex( 4695): install done
,I/ProviderInstaller( 4695): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1379): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/dalvikvm( 4453): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4453): threadid=1: thread exiting with uncaught exception (group=0x41776e30)
,E/AndroidRuntime( 4453): FATAL EXCEPTION: main
E/AndroidRuntime( 4453): Process: com.test.thalitest, PID: 4453
E/AndroidRuntime( 4453): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4453): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4453): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4453): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4453): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4453): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4453): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4453): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4453): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4453): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4453): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4453): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4453): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4453): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4453): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4453): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4453): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4453): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4453): 	at dalvik.system.NativeStart.main(Native Method)
,E/ActivityManager(  906): App crashed! Process: com.test.thalitest
W/ActivityManager(  906):   Force finishing activity com.test.thalitest/.MainActivity
,D/Process (  906): killProcessQuiet, pid=4359
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
,I/ActivityManager(  906): Killing 4359:com.htc.backup/1000 (adj 15): empty #17
D/Process ( 4453): killProcess, pid=4453
D/Process ( 4453): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/ActivityManager(  906): Recipient 4359
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/InputDispatcher(  906): channel '424b4078 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  906): channel '424b4078 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  906): Attempted to unregister already unregistered input channel '424b4078 com.test.thalitest.MainActivity (s)'
,I/Adreno-EGL( 4695): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4695): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4695): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4695): Local Branch: 
I/Adreno-EGL( 4695): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4695): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4695):                  aa63bbd948f41d15fc72f585e
I/WindowManager(  906): WINDOW DIED Window{424b4078 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager(  906): Recipient 4453
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.test.thalitest (pid 4453) has died.
D/WifiService(  906): Client connection lost with reason: 4
,D/PMS     (  906): releaseWL(426de238): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  906): NetTransition Wakelock for ConnectedState released by timeout
,W/InputMethodManagerService(  906): Got RemoteException sending setActive(false) notification to pid 4453 uid 10348
,W/Binder  ( 1210): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1210): java.lang.NullPointerException
W/Binder  ( 1210): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1210): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1210): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1210): 	at dalvik.system.NativeStart.run(Native Method)
,I/Adreno-EGL( 4695): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4695): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4695): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4695): Local Branch: 
I/Adreno-EGL( 4695): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4695): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4695):                  aa63bbd948f41d15fc72f585e
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: true
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
V/Tethering(  906): bSetPropertyMultiRAB:false
,D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/Tethering(  906): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  906): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  906): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  906): ipv4Default 0.0.0.0/0 -> 192.168.1.1
,I/Tethering(  906): Found interface wlan0
,D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
,D/CaptivePortalTracker(  906): NoActiveNetworkState
I/acms    ( 1884): Checking Certificates
I/acms    ( 1884): Checking Developer Certificates
I/acms    ( 1884): Checking Application Certificates
I/acms    ( 1884): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
,I/acms    ( 1884): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1884): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1826/10178)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1884/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4553/10078)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.musicenhancer (3963/10051)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1277/10075)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1475/10028)
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
I/acms    ( 1884): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1884): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
I/acms    ( 1884): Updating next query delay: 75600000
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
I/mlserverapp( 1884): MirrorLink is never connected, don't setup ACMS programed checks
I/mlserverapp( 1884): cancelACMSProgrammedChecks
I/ConnectivityHelper( 1277): [onReceive] WIFI(1): CONNECTED
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [1][0][0]
,I/NetworkMonitor( 3928): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (4695/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
D/PMS     (  906): acquireWL(43d03d28): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3928/10154)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(43cd92e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  906): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(43cd92e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  906): releaseWL(43d03d28): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by  (2759/10021)
,D/PMS     (  906): acquireWL(437c0a20): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2870 10028 null
,D/PMS     (  906): releaseWL(437c0a20): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1379): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1379/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1379/10028)
D/libc    ( 1379): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1379): [NET] getaddrinfo-,err=8
D/libc    ( 1379): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1379): [NET] getaddrinfo-, 1
,D/libc    ( 1379): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =3767 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1379/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2870/10028)
D/PMS     (  906): acquireWL(41c9bd20): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1379 10028 null
,D/AutoSetting( 1434): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4553): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1434/10053)
D/MobileConnectivityChangeReceiver( 4553): onReceive CONNECTIVITY_CHANGE networkType=1
D/AutoSetting( 1434): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1434): service - onStartCommand() screen is off, don't request location
,D/AutoSetting( 1434): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1434): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1434/10053)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4586/10151)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [2][0][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4121/10160)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 218
D/libc    (  365): [NET]res_nsend:resplen=79
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1379): [NET] getaddrinfo_proxy-, success
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4121/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1826/10178)
,I/dalvikvm-heap( 4121): Grow heap (frag case) to 13.519MB for 1821008-byte allocation
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
,D/libc    ( 1379): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1379): [NET] getaddrinfo-,err=8
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1379/10028)
D/PMS     (  906): acquireWL(425a7bd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1379 10028 null
D/PMS     (  906): releaseWL(425a7bd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/fb4a(:<default>):UserScope( 4524): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4524): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=20 [5][1][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
,D/GCM     ( 1379): Connected
D/PMS     (  906): acquireWL(420f7c98): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1379 10028 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1379/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1379/10028)
D/PMS     (  906): releaseWL(41c9bd20): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1379/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1379/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1379/10028)
D/PMS     (  906): releaseWL(420f7c98): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  906): acquireWL(437e4630): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1379 10028 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1379/10028)
,D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1379/10028)
,D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/GCM     ( 1379): Message class mpf
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1379/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1379/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,E/fb4a(:<default>):LocalFbBroadcastManager( 4524): Called registerBroadcastReceiver twice.
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1379/10028)
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/PMS     (  906): releaseWL(437e4630): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  906): acquireWL(4263f2c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1379 10028 null
D/PMS     (  906): releaseWL(4263f2c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/Adreno-EGL( 4695): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4695): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4695): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4695): Local Branch: 
I/Adreno-EGL( 4695): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4695): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4695):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
,W/Settings( 4695): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4524/10026)
,I/CheckinTask( 2870): Sending checkin request (8968 bytes)
D/libc    ( 2870): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2870): [NET] getaddrinfo-,err=8
D/libc    ( 2870): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2870): [NET] getaddrinfo-, 1
,D/libc    ( 2870): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =5687 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 237
D/libc    (  365): [NET]res_nsend:resplen=84
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2870): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2870): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2870): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1167): environment dirty rate=25 [16][4][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): releaseWL(4410b778): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/WifiStateMachine(  906): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/PMS     (  906): acquireWL(44113708): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1379 10028 null
,D/PMS     (  906): releaseWL(44113708): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (2870/10028)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [2][0][0]
D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (2870/10028)
,W/GLSUser ( 1379): GoogleAccountDataService.getToken()
,W/GLSActivity( 1379): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1379): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1379): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1571): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,W/CheckinRequestBuilder( 2870): awaiting user notification for token
,D/DotMatrix( 1571): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1119): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41d654c0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1119): com.google.android.gms 1 10 3 12
,I/CheckinTask( 2870): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2870): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2870/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2870/10028)
,D/PMS     (  906): releaseWL(43106b08): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/GCM     ( 1379): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE,
E/ActivityThread( 2870): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41cf13e0 that was originally bound here
E/ActivityThread( 2870): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41cf13e0 that was originally bound here
E/ActivityThread( 2870): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2870): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2870): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2870): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2870): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2870): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2870): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2870): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2870): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2870): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2870): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2870): 	at bks.a(SourceFile:298)
E/ActivityThread( 2870): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2870): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2870): 	,at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2870): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1379): GCM config loaded
,D/AutoSetting( 1517): service - handleMessage() stop self
,D/AutoSetting( 1517): service - onDestroy() END
,D/AutoSetting( 1517): service - handleMessage() quit looper
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =c72d +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE,
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  365): [NET]res_nsend:resplen=172
D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  906): Find DNS Address www.htc.com/104.81.130.175,
,I/GAV2    ( 4586): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  906): acquireWL(43201ea8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1475 10028 null
,D/PMS     (  906): acquireWL(43c90b88): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1475 10028 null
,D/PMS     (  906): releaseWL(43201ea8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  906): releaseWL(43c90b88): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/ContactMessageStore( 1248): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1248): MSG_NOTIFY_CS_TO_SYNC <<
,D/Process (  906): killProcessQuiet, pid=4383
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4383:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4383
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  906): killProcessQuiet, pid=3963
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3963:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3963
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  906): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{4312cf18 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(4264f280): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4264f280): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1571): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1434): service - has update message, not stop
,D/AutoSetting( 1434): service - mHandler: update timezone
,D/AutoSetting( 1517): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1517): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1517): service - onCreate()
D/AutoSetting( 1517): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1517): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/DotMatrix( 1571): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1571): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AutoSetting( 1517): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1517): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1517): service - mHandler: update timezone
,D/AutoSetting( 1517): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1517): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1517): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1517): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1571): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1571): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/PhoneStatusBar( 1119): removeNotification.gc:51
,I/RemoteViews( 1119): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41ecdb78 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1119): com.htc.htclocationservice 2 5 2 11
,D/PMS     (  906): acquireWL(426b5df8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10028}
,V/AlarmManager(  906): sending alarm PendingIntent{440d3378: PendingIntentRecord{4255e6f0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=138472, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{41ed8a28: PendingIntentRecord{4253b8e8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142283, Int=0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1379/10028)
,D/PMS     (  906): acquireWL(42b8c558): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1379 10028 null
,D/PMS     (  906): releaseWL(42b8c558): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/GpsLocationProvider(  906): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  906): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  906): acquireWL(438227e0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/PMS     (  906): releaseWL(426b5df8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =7b46 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  365): [NET]res_nsend:resplen=238
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=10
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
I/global  (  906): call createSocket() return a new socket.
D/libc    (  906): [NET] getaddrinfo+,hn 14(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  906): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  906): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  906): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  906):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  906): releaseWL(438227e0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 3
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{440eca38 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  906): acquireWL(42535358): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4244a3a8: PendingIntentRecord{42449490 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=167999, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42535358): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(437e53c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(437e53c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1571): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 1434): service - handleMessage() stop self
,D/AutoSetting( 1434): service - handleMessage() quit looper
,D/AutoSetting( 1434): service - onDestroy() END
,D/AutoSetting( 1517): service - handleMessage() stop self
,D/AutoSetting( 1517): service - onDestroy() END
,D/AutoSetting( 1517): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=4399
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4399:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4399
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 4
,D/TelephonyReceiver( 1248): switchBindHtcMsgCursor: null
,D/PMS     (  906): acquireWL(426e8580): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(426e8580): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(4266c5d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{4247f858: PendingIntentRecord{426821b8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=227374, Int=0
,I/ActivityManager(  906): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4743 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  906): sending alarm PendingIntent{425d9268: PendingIntentRecord{425c0410 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1450653164898, Int=10800000
,D/PMS     (  906): releaseWL(4266c5d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.aurora (4743/10047)
,D/Process (  906): killProcessQuiet, pid=4414
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4414:com.android.settings:remote/1000 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 4414
,D/PMS     (  906): acquireWL(42b00f80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4244a3a8: PendingIntentRecord{42449490 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=228000, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42b00f80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43c7bca8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): acquireWL(425d0338): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{43d41158: PendingIntentRecord{432a7fd0 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=228032, Int=120000
,D/PMS     (  906): releaseWL(43c7bca8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1571): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
V/AlarmManager(  906): sending alarm PendingIntent{430e0da8: PendingIntentRecord{426821b8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=228355, Int=0
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,D/PMS     (  906): releaseWL(425d0338): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2870/10028)
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(4419f090): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4419f090): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(437ec660): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4244a3a8: PendingIntentRecord{42449490 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=287999, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(437ec660): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4255a2d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1571): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PMS     (  906): runPSCheck
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(4255a2d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(42a6a268): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): releaseWL(42a6a268): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1571): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43632330): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4244a3a8: PendingIntentRecord{42449490 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=347999, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43632330): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43be01b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1571): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
D/PMS     (  906): releaseWL(43be01b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(421adef8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10028}
,V/AlarmManager(  906): sending alarm PendingIntent{439953d0: PendingIntentRecord{43fd5738 com.google.android.gms broadcastIntent}}, i=null, t=1, cnt=1, w=1450653305790, Int=0
,D/PMS     (  906): releaseWL(421adef8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,W/Uploader( 2870): No account for auth token provided
,D/libc    ( 2870): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 2870): [NET] getaddrinfo-,err=8
D/libc    ( 2870): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 2870): [NET] getaddrinfo-, 1
,D/libc    ( 2870): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =6cb0 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 29
D/libc    (  365): [NET]res_nsend:resplen=87
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 2870): [NET] getaddrinfo_proxy-, success
I/global  ( 2870): call createSocket() return a new socket.
D/libc    ( 2870): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 2870): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 2870): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 2870): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2870/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2870/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2870/10028)
,W/GLSUser ( 1379): GoogleAccountDataService.getToken()
,W/GLSActivity( 1379): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1379): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1379): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1571): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1571): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1119): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41f32cc8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,W/GLSActivity( 1379): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1379): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1379): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1379): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1379): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1379): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1379): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1379): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews.Performance( 1119): com.google.android.gms 2 12 4 12
,E/PlayEventLogger( 4084): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4084): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4084): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4084): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4084): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4084): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4084): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4084): 	at dalvik.system.NativeStart.run(Native Method)
,D/libc    ( 4084): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4084): [NET] getaddrinfo-,err=8
D/libc    ( 4084): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4084): [NET] getaddrinfo-, 1
,D/libc    ( 4084): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =3a96 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4084): [NET] getaddrinfo_proxy-, success
I/global  ( 4084): call createSocket() return a new socket.
D/libc    ( 4084): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4084): [NET] getaddrinfo-, SUCCESS
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 2
,D/libc    ( 4084): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4084): [NET] getaddrinfo-,err=8
,D/PMS     (  906): acquireWL(43108958): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43108958): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
,D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/DotMatrix( 1571): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(44119780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4244a3a8: PendingIntentRecord{42449490 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=407999, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(44119780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(437a8658): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1571): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): releaseWL(437a8658): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(437406a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/PMS     (  906): releaseWL(437406a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1571): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(440fa928): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{4244a3a8: PendingIntentRecord{42449490 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=467999, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(440fa928): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(437a8a28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(437a8a28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(440ca050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(440ca050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HtcPowerSaver(  906): updateBatteryInfo
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1571): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/PowerUI ( 1119): closing low battery warning: level=100
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(43ce7e60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4244a3a8: PendingIntentRecord{42449490 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=527999, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43ce7e60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4271a1d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1571): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(4271a1d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  410): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(43188948): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
D/PMS     (  906): releaseWL(43188948): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1571): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(440f29a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{4244a3a8: PendingIntentRecord{42449490 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=587999, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(440f29a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(431ba3c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(431ba3c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1571): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1119): closing low battery warning: level=100
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43442258): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43442258): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  354): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1248): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1248): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1248): sku_id=99
D/ContactMessageStore( 1248): start background delete task...
,D/ContactMessageStore( 1248): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1248): size: 0 , 0
,D/ContactMessageStore( 1248): Background delete complete
,D/PMS     (  906): acquireWL(426c7240): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4244a3a8: PendingIntentRecord{42449490 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=647999, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(426c7240): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43725170): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  906): updateBatteryInfo
,D/PMS     (  906): releaseWL(43725170): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1571): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4410b850): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4410b850): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4340b558): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{44081fd0: PendingIntentRecord{432a7fd0 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=528378, Int=300000
,V/AlarmManager(  906): sending alarm PendingIntent{4385d398: PendingIntentRecord{4217fc10 com.android.vending startService}}, i=null, t=0, cnt=1, w=1450653645565, Int=0
,D/PMS     (  906): releaseWL(4340b558): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/GLSUser ( 1379): GoogleAccountDataService.getToken()
,W/GLSActivity( 1379): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1379): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1379): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1379): GoogleAccountDataService.getToken()
,W/GLSActivity( 1379): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1379): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1379): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4084): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4084): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,W/GLSUser ( 1379): GoogleAccountDataService.getToken()
,W/GLSActivity( 1379): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1379): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1379): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4084): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4084): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4084): [1] DailyHygiene.reschedule: Scheduling new run in 27 minutes (failures=2)
,D/PMS     (  906): acquireWL(425f13a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{4244a3a8: PendingIntentRecord{42449490 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=707999, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(425f13a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(440bc220): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10073}
,V/AlarmManager(  906): sending alarm PendingIntent{425d8c98: PendingIntentRecord{4392a618 com.android.vending startService}}, i=null, t=0, cnt=1, w=1450653660759, Int=0
,D/PMS     (  906): releaseWL(440bc220): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/Finsky  ( 4084): [1] 5.onFinished: Installation state replication succeeded.
,D/PMS     (  906): acquireWL(430d6740): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PMS     (  906): releaseWL(430d6740): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1571): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/Process (  906): killProcessQuiet, pid=4147
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4147:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4147
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(42ad8c30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): releaseWL(42ad8c30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1119): closing low battery warning: level=100
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1571): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43201c80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4244a3a8: PendingIntentRecord{42449490 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=767999, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43201c80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(426f43d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1571): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/PMS     (  906): releaseWL(426f43d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,D/PMS     (  906): acquireWL(430af518): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41e63a38: PendingIntentRecord{424de580 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=781712, Int=0
,D/PMS     (  906): releaseWL(430af518): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,D/PMS     (  906): acquireWL(42a5cd78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
,D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  906): releaseWL(42a5cd78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1571): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42b02b38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4244a3a8: PendingIntentRecord{42449490 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=828000, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42b02b38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(424eb878): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
V/NotificationService(  906): batLight: plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c80000
D/qdlights(  906): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/DotMatrix( 1571): [EventService] reorderNotification, total:1
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1571): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/HeadsetPhoneState( 1628): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=98
D/PMS     (  906): releaseWL(424eb878): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,W/ContextImpl( 4648): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
I/HtcPowerSaver(  906): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,D/TetherSettings( 3837): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 3837): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3837): Cust_ConnectToPC   : Modem_Link>false
,D/        ( 3837): Cust_ConnectToPC   : spcsc>false
D/        ( 3837): Cust_ConnectToPC   : IPT>true
,D/        ( 3837): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3837): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3837): Index of the first 1 = -1
W/Settings( 3837): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3837): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3837): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3837): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 3837): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,W/ContextImpl( 3837): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
D/SmartNS_Utility( 3837): [ACC]android_networking:tethering_guard_support=false
,I/BatteryController( 1119): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(44099758): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(44099758): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42162978): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4244a3a8: PendingIntentRecord{42449490 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=887999, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42162978): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(439f5260): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1571): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=98
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(439f5260): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(426fa848): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4244a3a8: PendingIntentRecord{42449490 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=947999, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(426fa848): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4346ef68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4346ef68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43bb73c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4244a3a8: PendingIntentRecord{42449490 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1007999, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43bb73c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(432821f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{425c3110: PendingIntentRecord{426df100 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450653885416, Int=900000
,V/AlarmManager(  906): sending alarm PendingIntent{42591170: PendingIntentRecord{436aba48 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450653960430, Int=0
,W/ContextImpl( 4648): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4648): call getInstance()
,D/SmartSyncUtils( 4648): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4648): MY_DEBUG = false
D/PMS     (  906): releaseWL(432821f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43708b78): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4648 1000 null
D/SmartSyncScreenOnOffTimeReceiver( 4648): [updateNmRange] bManual = false
D/SmartSyncScreenOnOffTimeReceiver( 4648): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 4648): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4648): SettingOnTime = 1450677600000, randomSettingOnTime = 1450677233000
D/SmartSyncScreenOnOffTimeReceiver( 4648): SettingOffTime = 1450656000000, randomSettingOffTime = 1450662325000
,D/SmartSyncScreenOnOffTimeReceiver( 4648): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4648): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4648): bNightModeTurnOffOnce = false
W/BatSI   (  906): Couldn't get kernel wake lock stats
D/PMS     (  906): releaseWL(43708b78): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): acquireWL(4271dbd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10028}
,V/AlarmManager(  906): sending alarm PendingIntent{42097480: PendingIntentRecord{41bef3b8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1009763, Int=0
,D/PMS     (  906): acquireWL(4262c0c0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1379 10028 null
,D/PMS     (  906): acquireWL(425e0da0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1379 10028 null
,D/PMS     (  906): releaseWL(4271dbd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  906): releaseWL(4262c0c0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,D/PMS     (  906): releaseWL(425e0da0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  906): acquireWL(4277f868): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1379 10028 null
,D/GCM     ( 1379): Message class mow
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1379/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1379/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1379/10028)
,D/PMS     (  906): releaseWL(4277f868): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  906): acquireWL(43ccf950): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1379 10028 null
,D/PMS     (  906): releaseWL(43ccf950): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=14 [142][21][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1167): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1167): nl80211: survey data missing!
E/wpa_supplicant( 1167): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1167): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(437fa380): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1571): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/PowerUI ( 1119): closing low battery warning: level=99
,D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(437fa380): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42551890): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42551890): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(440db030): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4244a3a8: PendingIntentRecord{42449490 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1067999, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(440db030): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(420c1cd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(420c1cd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(440ffa88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4244a3a8: PendingIntentRecord{42449490 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1127999, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(440ffa88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(426a0e50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(426a0e50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4418ba20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4244a3a8: PendingIntentRecord{42449490 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1187999, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4418ba20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43c6c780): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
,D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/BatteryService(  906): n_update end
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
,D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetPhoneState( 1628): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/DotMatrix( 1571): [EventService] reorderNotification, total:0
,D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1571): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  906): releaseWL(43c6c780): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/PowerUI ( 1119): closing low battery warning: level=100
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/ContextImpl( 4648): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,D/TetherSettings( 3837): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 3837): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3837): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3837): Cust_ConnectToPC   : spcsc>false
D/        ( 3837): Cust_ConnectToPC   : IPT>true
,D/        ( 3837): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3837): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3837): Index of the first 1 = -1
W/Settings( 3837): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3837): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3837): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3837): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 3837): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/ContextImpl( 3837): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42466830): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42466830): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,E/PNP_UPDATERD(  354): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(425cdd30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4244a3a8: PendingIntentRecord{42449490 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1247999, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(425cdd30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4268cad8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4268cad8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43497a70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4244a3a8: PendingIntentRecord{42449490 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1307999, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43497a70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4367f448): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4367f448): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(441a9e60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4244a3a8: PendingIntentRecord{42449490 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1367999, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(441a9e60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43060ba8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43060ba8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(426b9a50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{4244a3a8: PendingIntentRecord{42449490 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1427999, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(426b9a50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43a401e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43a401e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(437ef9c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4244a3a8: PendingIntentRecord{42449490 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1487999, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(437ef9c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(437de428): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(437de428): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4409c998): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{4244a3a8: PendingIntentRecord{42449490 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1547999, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4409c998): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43c75760): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43c75760): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(440d9300): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4244a3a8: PendingIntentRecord{42449490 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1607999, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(440d9300): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(440700c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(440700c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(437e36f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4244a3a8: PendingIntentRecord{42449490 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1667999, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(437e36f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(430dcf08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(430dcf08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42ebe4b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{4244a3a8: PendingIntentRecord{42449490 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1727999, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42ebe4b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(437fead8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(437fead8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4407c920): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{4244a3a8: PendingIntentRecord{42449490 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1787999, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4407c920): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): acquireWL(43155800): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  906): sending alarm PendingIntent{41e63a38: PendingIntentRecord{424de580 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1501736, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{41d99bc0: PendingIntentRecord{4253fd08 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1812002, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{427ac0d0: PendingIntentRecord{426a6068 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450654236191, Int=1800000
,D/PMS     (  906): acquireWL(434421c8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(43025c78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): acquireWL(43395ac8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2870 10028 null
D/PMS     (  906): releaseWL(434421c8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(43025c78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  906): releaseWL(43155800): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  906): acquireWL(4411bee8): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2870 10028 null
,D/PMS     (  906): releaseWL(43395ac8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
I/EventLogService( 2870): Aggregate from 1450653060500 (log), 1450652436132 (data)
,D/PMS     (  906): releaseWL(4411bee8): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,D/PMS     (  906): acquireWL(433a9780): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1571): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): releaseWL(433a9780): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  354): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(438fe2a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4244a3a8: PendingIntentRecord{42449490 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1847999, Int=0
,I/ProcessStatsService(  906): Prepared write state in 51ms
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(438fe2a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  906): Pruning old procstats: /data/system/procstats/state-2015-12-20-00-18-00.bin
,D/PMS     (  906): acquireWL(43708d80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
D/PMS     (  906): releaseWL(43708d80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1571): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1571): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/Process (  906): killProcessQuiet, pid=4328
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActiveServices.realStartServiceLocked:1454 
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/ActivityManager(  906): Killing 4328:com.htc.cs.dm/u0a98 (adj 15): empty for 1800s
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
I/ActivityManager(  906): Recipient 4328
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43c6b678): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/Process (  906): killProcessQuiet, pid=4499
V/AlarmManager(  906): sending alarm PendingIntent{4244a3a8: PendingIntentRecord{42449490 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1907999, Int=0
,I/ActivityManager(  906): Killing 4499:com.htc.mms.backupagent/u0a77 (adj 15): empty for 1806s
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,I/ActivityManager(  906): Recipient 4499
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): releaseWL(43c6b678): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1800000ms),D/PMS     (  906): acquireWL(4414ebb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{423fd5f0: PendingIntentRecord{42597870 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1821885, Int=1800000
D/PMS     (  906): acquireWL(4278b270): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
V/AlarmManager(  906): sending alarm PendingIntent{434d6b38: PendingIntentRecord{41bef3b8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1909875, Int=0
V/AlarmManager(  906): sending alarm PendingIntent{425c3110: PendingIntentRecord{426df100 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450654785416, Int=900000
D/PMS     (  906): releaseWL(4278b270): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/Process (  906): killProcessQuiet, pid=4586
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/Process (  906): killProcessQuiet, pid=4569
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/Process (  906): killProcessQuiet, pid=4553
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 4586:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1800s
I/ActivityManager(  906): Killing 4569:com.android.chrome/u0a96 (adj 15): empty for 1800s
I/ActivityManager(  906): Killing 4553:com.google.android.setupwizard/u0a78 (adj 15): empty for 1800s
I/ActivityManager(  906): Killing 1434:com.htc.sense.hsp/u0a53 (adj 15): empty for 1800s
D/Process (  906): killProcessQuiet, pid=1434
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/Process (  906): killProcessQuiet, pid=3928
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3928:com.google.android.music:main/u0a154 (adj 15): empty for 1800s
D/PMS     (  906): acquireWL(42c7f688): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1379 10028 null
D/PMS     (  906): releaseWL(42c7f688): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
D/PMS     (  906): acquireWL(43c285d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1379 10028 null
I/ActivityManager(  906): Recipient 4553
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ContextImpl( 4648): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  906): Recipient 4569
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  906): releaseWL(43c285d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
I/ActivityManager(  906): Recipient 3928
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  906): Client com.google.android.music (pid 3928): Died!
D/PMS     (  906): releaseWL(4414ebb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
W/BatSI   (  906): Couldn't get kernel wake lock stats
W/BatSI   (  906): Couldn't get kernel wake lock stats
I/ActivityManager(  906): Recipient 4586
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 1434
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/BatSI   (  906): Couldn't get kernel wake lock stats
E/cutils-trace( 4806): Error opening trace file: No such file or directory (2)
W/BatSI   (  906): Couldn't get kernel wake lock stats
D/CustomizationManager( 4806): ====startRecUseTime====
D/htc.customization.log.level( 4806):  is 
W/CustomizationLogLevel( 4806): Level value is invalid, use default level 2
D/CustomizationManager( 4806):  Read ACC file spent 0.127 (s)
D/CIDMapFileReader( 4806): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4806): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4806): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4806): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4806): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4806): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4806): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4806): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4806): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4806): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4806): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4806): Parsing tag category name = system
I/CustomizationCIDLoader( 4806): Parsing tag category name = application
I/CustomizationCIDLoader( 4806): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4806): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4806): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4806): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4806): Parsing tag category name = Settings
D/CustomizationManager( 4806):  Read CID file spent 0.184 (s)
D/CustomizationManager( 4806):  All configurations done spent 0.184 (s)
W/HtcNativeFlag( 4806): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4806): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4806): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4806): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  906): deletePackageAsUser: pkg=com.test.thalitest, pid=4806, uid=2000 user=0
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
W/asset   (  906): Copying FileAsset 0x62ade3e0 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
W/PackageSettings(  906): Skipping PackageSetting{422f7f50 com.example.hello/10356} due to missing metadata
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
D/DotMatrix( 1571): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1571): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1571): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver replacing:false
W/AccTypeManager( 1330): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1330): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/acms    ( 1884): Unregistering com.test.thalitest
E/acms    ( 1884): Could not unregister removed application com.test.thalitest
I/dalvikvm-heap( 4121): Grow heap (frag case) to 15.213MB for 1821008-byte allocation
W/GeofencerStateMachine( 1475): Ignoring removeGeofence because network location is disabled.
D/PMS     (  906): acquireWL(44105168): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1475 10028 null
I/Prism.ItemManager( 1277): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1277): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PMS     (  906): releaseWL(44105168): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/VoicemailCleanupService( 1303): Cleaning up data for package: com.test.thalitest
I/Launcher( 1277): Deferring update until onResume
D/Launcher( 1277): waitUntilResume // bindAppsRemoved
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
D/AccTypeManager( 1330): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
W/SystemReader( 1260): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/PackageBroadcastService( 2870): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/ActivityManager(  906): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4821 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/ActivityManager(  906): Delaying start of: ServiceRecord{44174b28 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/MultiDex( 4821): install
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
E/ExternalAccountType( 1330): Unsupported attribute readOnly
I/PeopleContactsSync( 2870): CP2 sync disabled
I/MultiDex( 4821): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/MultiDex( 4821): loading existing secondary dex files
I/MultiDex( 4821): load found 1 secondary dex files
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2870, uid=10028, userID:0
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
I/MultiDex( 4821): install done
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/Icing   ( 2870): doRemovePackageData com.test.thalitest
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1248 :
D/PMS     (  906): acquireWL(427a6830): PARTIAL_WAKE_LOCK  Icing 0x1 2870 10028 null
D/PhoneApp( 1248): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  906): releaseWL(427a6830): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  906): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4841 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/ProviderInstaller( 4821): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  906): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4841): install
I/MultiDex( 4841): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4841): loading existing secondary dex files
I/MultiDex( 4841): load found 1 secondary dex files
I/MultiDex( 4841): install done
I/ProviderInstaller( 4841): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  906): Resuming delayed broadcast
E/SQLiteDatabase( 2870): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 2870): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2870): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2870): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2870): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2870): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2870): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2870): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2870): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2870): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2870): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2870): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2870): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2870): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2870): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2870): 	at bxi.delete(SourceFile:258)
E/SQLiteDatabase( 2870): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 2870): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/SQLiteDatabase( 2870): 	at aqn.a(SourceFile:27)
E/SQLiteDatabase( 2870): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/SQLiteDatabase( 2870): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2870): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2870): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2870): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SharedPreferencesImpl( 1210): Couldn't rename file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml to backup file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml.bak
E/ClearPendingStateOp( 2870): Runtime exception while performing operation
E/ClearPendingStateOp( 2870): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 2870): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 2870): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/ClearPendingStateOp( 2870): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/ClearPendingStateOp( 2870): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 2870): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 2870): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 2870): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/ClearPendingStateOp( 2870): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/ClearPendingStateOp( 2870): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/ClearPendingStateOp( 2870): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/ClearPendingStateOp( 2870): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/ClearPendingStateOp( 2870): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/ClearPendingStateOp( 2870): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/ClearPendingStateOp( 2870): 	at bxi.delete(SourceFile:258)
E/ClearPendingStateOp( 2870): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/ClearPendingStateOp( 2870): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/ClearPendingStateOp( 2870): 	at aqn.a(SourceFile:27)
E/ClearPendingStateOp( 2870): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/ClearPendingStateOp( 2870): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ClearPendingStateOp( 2870): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ClearPendingStateOp( 2870): 	at android.os.Looper.loop(Looper.java:157)
E/ClearPendingStateOp( 2870): 	at android.os.HandlerThread.run(HandlerThread.java:61)
F/ClearPendingStateOp( 2870): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 2870): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 2870): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 2870): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
F/ClearPendingStateOp( 2870): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
F/ClearPendingStateOp( 2870): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 2870): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 2870): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 2870): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
F/ClearPendingStateOp( 2870): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
F/ClearPendingStateOp( 2870): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
F/ClearPendingStateOp( 2870): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
F/ClearPendingStateOp( 2870): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
F/ClearPendingStateOp( 2870): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
F/ClearPendingStateOp( 2870): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
F/ClearPendingStateOp( 2870): 	at bxi.delete(SourceFile:258)
F/ClearPendingStateOp( 2870): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
F/ClearPendingStateOp( 2870): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
F/ClearPendingStateOp( 2870): 	at aqn.a(SourceFile:27)
F/ClearPendingStateOp( 2870): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
F/ClearPendingStateOp( 2870): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
F/ClearPendingStateOp( 2870): 	at android.os.Handler.dispatchMessage(Handler.java:102)
F/ClearPendingStateOp( 2870): 	at android.os.Looper.loop(Looper.java:157)
F/ClearPendingStateOp( 2870): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  906): Start proc com.htc.sense.hsp for broadcast com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver: pid=4857 uid=10053 gids={50053, 1023, 3003, 5012}
D/Process (  906): killProcessQuiet, pid=4121
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4121:com.google.android.apps.plus/u0a160 (adj 15): empty for 1802s
E/DropBoxManagerService(  906): Can't write: system_app_wtf
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  906): Recipient 4121
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/SQLiteDatabase( 4821): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4821): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4821): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4821): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4821): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4821): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4821): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4821): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4821): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4821): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4821): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4821): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4821): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4821): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4821): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4821): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4821): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4821): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4821): threadid=12: thread exiting with uncaught exception (group=0x41776e30)
E/AndroidRuntime( 4821): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4821): Process: com.google.android.gms.drive, PID: 4821
E/AndroidRuntime( 4821): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4821): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4821): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4821): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4821): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4821): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4821): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4821): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4821): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4821): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4821): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4821): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4821): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4821): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4821): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4821): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4821): 	at ctn.run(SourceFile:985)
E/ActivityManager(  906): App crashed! Process: com.google.android.gms.drive
D/Process ( 4821): killProcess, pid=4821
D/Process ( 4821): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
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
I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/ActivityManager(  906): Recipient 4821
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.google.android.gms.drive (pid 4821) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
D/PluginProvider( 4857): PluginProvider onCreate
W/PackageManager(  906): Unable to load service info ResolveInfo{426b7828 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
E/SQLiteDatabase( 4857): Failed to open database '/data/data/com.htc.sense.hsp/databases/registry.db'.
E/SQLiteDatabase( 4857): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4857): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4857): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4857): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4857): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4857): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4857): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4857): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4857): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4857): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4857): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4857): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4857): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4857): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4857): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.onCreate(Unknown Source)
E/SQLiteDatabase( 4857): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1609)
E/SQLiteDatabase( 4857): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1574)
E/SQLiteDatabase( 4857): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5394)
E/SQLiteDatabase( 4857): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4965)
E/SQLiteDatabase( 4857): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4902)
E/SQLiteDatabase( 4857): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4857): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4857): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4857): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4857): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4857): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4857): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4857): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4857): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4857): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4857): Couldn't open registry.db for writing (will try read-only):
E/SQLiteOpenHelper( 4857): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4857): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4857): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4857): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4857): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4857): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4857): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4857): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4857): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4857): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4857): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4857): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4857): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4857): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4857): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.onCreate(Unknown Source)
E/SQLiteOpenHelper( 4857): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1609)
E/SQLiteOpenHelper( 4857): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1574)
E/SQLiteOpenHelper( 4857): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5394)
E/SQLiteOpenHelper( 4857): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4965)
E/SQLiteOpenHelper( 4857): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4902)
E/SQLiteOpenHelper( 4857): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4857): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4857): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4857): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4857): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4857): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4857): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4857): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4857): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4857): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4857): Opened registry.db in read-only mode
D/PluginProvider( 4857): current plugin count: 19
D/HtcAppUPService( 4857): HtcUPDataProvider onCreate()
I/[PluginManager]RegisterService( 4857): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
W/[PluginManager]RegisterService( 4857): provider may killed!
W/[PluginManager]RegisterService( 4857): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/[PluginManager]RegisterService( 4857): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/[PluginManager]RegisterService( 4857): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/[PluginManager]RegisterService( 4857): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/[PluginManager]RegisterService( 4857): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/[PluginManager]RegisterService( 4857): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
W/[PluginManager]RegisterService( 4857): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:818)
W/[PluginManager]RegisterService( 4857): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:213)
W/[PluginManager]RegisterService( 4857): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/[PluginManager]RegisterService( 4857): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
W/[PluginManager]RegisterService( 4857): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/[PluginManager]RegisterService( 4857): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
W/[PluginManager]RegisterService( 4857): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 4857): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 4857): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 4857): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 4857): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/[PluginManager]RegisterService( 4857): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1277): action: android.intent.action.PACKAGE_REMOVED
I/IcingCorporaProvider( 2948): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  906): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4874 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/SQLiteLog( 2948): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2948): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x5cab7978
W/dalvikvm( 2948): threadid=14: thread exiting with uncaught exception (group=0x41776e30)
E/ActivityManager(  906): App crashed! Process: com.google.android.googlequicksearchbox:search
D/Process ( 2948): killProcess, pid=2948
D/Process ( 2948): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/AndroidRuntime( 2948): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2948): Process: com.google.android.googlequicksearchbox:search, PID: 2948
E/AndroidRuntime( 2948): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2948): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2948): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2948): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2948): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2948): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2948): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2948): 	at cid.d(PG:186)
E/AndroidRuntime( 2948): 	at clo.g(PG:594)
E/AndroidRuntime( 2948): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2948): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2948): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2948): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2948): 	at clr.tL(PG:827)
E/AndroidRuntime( 2948): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2948): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2948): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2948): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2948): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2948): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop144.tmp: open failed: EROFS (Read-only file system)
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
I/Prism.ItemManager( 1277): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1277): loadItems() com.htc.launcher.pageview.WidgetManager@41c39e70 +
I/Prism.WidgetManager( 1277): onLoadItems() +
D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  906): start
W/AtomicFile(  906): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  906): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
I/ActivityManager(  906): Recipient 2948
I/ActivityManager(  906): Process com.google.android.googlequicksearchbox:search (pid 2948) has died.
D/MediaRouterService(  906): Client com.google.android.googlequicksearchbox (pid 2948): Died!
D/WifiService(  906): Client connection lost with reason: 4
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 10999ms
E/SQLiteDatabase( 4874): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4874): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4874): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4874): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4874): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4874): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4874): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4874): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4874): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4874): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4874): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4874): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4874): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4874): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4874): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4874): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4874): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4874): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4874): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4874): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4874): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4874): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4874): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4874): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4874): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4874): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4874): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4874): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4874): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4874): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4874): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4874): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4874): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4874): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4874): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4874): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4874): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4874): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4874): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4874): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4874): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4874): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4874): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4874): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4874): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4874): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4874): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4874): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4874): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4874): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4874): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4874): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4874): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4874): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4874): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4874): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4874): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4874): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4874): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4874): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4874): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4874): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4874): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4874): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4874): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4874): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4874): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4874): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4874): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4874): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4874): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4874): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4874): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4874): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4874): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4874): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4874): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4874): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4874): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4874): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4874): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4874): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4874): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4874): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4874): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4874): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4874): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4874): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4874): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4874): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4874): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4874): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4874): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4874): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4874): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4874): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4874): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4874): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4874): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4874): threadid=11: thread exiting with uncaught exception (group=0x41776e30)
E/ActivityManager(  906): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4874): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4874): Process: com.google.android.apps.docs, PID: 4874
E/AndroidRuntime( 4874): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4874): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4874): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4874): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4874): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4874): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4874): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4874): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4874): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4874): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4874): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4874): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4874): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4874): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4874): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4874): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4874): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4874): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4874): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop145.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  906): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4890 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process ( 4874): killProcess, pid=4874
D/Process ( 4874): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  906): Recipient 4874
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.google.android.apps.docs (pid 4874) has died.

```
