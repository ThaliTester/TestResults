#### Test 50650278d1b06e8_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  910): Waited long enough for: ServiceRecord{4443dd68 u0 com.htc.htclocationservice/.AutoSettingService}
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  910):    returned true
,E/cutils-trace( 4382): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4382): ====startRecUseTime====
D/htc.customization.log.level( 4382):  is 
W/CustomizationLogLevel( 4382): Level value is invalid, use default level 2
D/CustomizationManager( 4382):  Read ACC file spent 0.050 (s)
D/CIDMapFileReader( 4382): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4382): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4382): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4382): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4382): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4382): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4382): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4382): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4382): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4382): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4382): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4382): Parsing tag category name = system
I/CustomizationCIDLoader( 4382): Parsing tag category name = application
I/CustomizationCIDLoader( 4382): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4382): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4382): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4382): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4382): Parsing tag category name = Settings
D/CustomizationManager( 4382):  Read CID file spent 0.088 (s)
D/CustomizationManager( 4382):  All configurations done spent 0.088 (s)
W/HtcNativeFlag( 4382): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4382): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4382): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4382): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  910): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  910): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  910): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  910): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  910): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  910): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  910): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4382
D/PMS     (  910): acquireHCC(424f68a0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 910 1000 null
D/PMS     (  910): acquireHCC(42438b30): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 910 1000 null
I/Intent  (  910): @test_code: getHtcIntentFlag: 0 obj: 1114201328
I/FeedHostManager( 1272): [onPause]
I/FeedProviderManager( 1272): onPause
I/FeedHostManager( 1272): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41d31668
I/SocialFeedProvider( 1272): +onPause
I/SocialFeedProvider( 1272): -onPause
D/PMS     (  910): acquireWL(421293a0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 910 1000 null
I/ActivityManager(  910): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4393 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1272): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 4393): Binding Chromium to main looper Looper (main, tid 1) {41b23f18}
I/LibraryLoader( 4393): Expected native library version number "",actual native library version number ""
I/chromium( 4393): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4393): Initializing chromium process, renderers=0
D/PMS     (  910): acquireWL(42cfc150): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
W/System.err(  910): java.lang.Throwable: stack dump
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  910): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/BluetoothManagerService(  910): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@423c8b18:true
W/System.err(  910): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  910): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  910): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  910): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4393): 1102290832: getState(). Returning 12
D/PMS     (  910): acquireWL(42cfc578): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  910): releaseWL(42cfc578): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4393): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4393): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4393): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4393): Local Branch: 
I/Adreno-EGL( 4393): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4393): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4393):                  aa63bbd948f41d15fc72f585e
W/chromium( 4393): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4393): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4393): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4393): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4393): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4393): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4393): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4393): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4393): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4393): CordovaWebView is running on device made by: HTC
,W/AwContents( 4393): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  910): Disable input method client, pid=1272
,I/InputMethodManagerService(  910): Enable input method client, pid=4393
W/ResourceType( 4393): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4393): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b6b640, mServedView=org.apache.cordova.engine.SystemWebView{41b312a8 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1210): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1210): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,W/AwContents( 4393): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  910): Displayed com.test.thalitest/.MainActivity: +272ms
,D/PMS     (  910): releaseWL(421293a0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4393): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4393): JniHelper::setJavaVM(0x415f9048), pthread_self() = 1663384552
D/JX-Cordova( 4393): jxcore cordova android initializing
,D/PMS     (  910): acquireWL(41e4a580): PARTIAL_WAKE_LOCK  Icing 0x1 2228 10028 null
,D/PMS     (  910): releaseWL(41e4a580): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  910): acquireWL(424a1c60): PARTIAL_WAKE_LOCK  Icing 0x1 2228 10028 null
,D/PMS     (  910): releaseWL(424a1c60): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  910): acquireWL(41f1ec98): PARTIAL_WAKE_LOCK  Icing 0x1 2228 10028 null
,D/PMS     (  910): releaseWL(41f1ec98): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  910): acquireWL(424ec948): PARTIAL_WAKE_LOCK  Icing 0x1 2228 10028 null
,D/PMS     (  910): releaseWL(424ec948): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/dalvikvm-heap( 4393): Grow heap (frag case) to 11.564MB for 96598-byte allocation
,I/dalvikvm-heap( 4393): Grow heap (frag case) to 11.613MB for 144892-byte allocation
,I/dalvikvm-heap( 4393): Grow heap (frag case) to 11.725MB for 217334-byte allocation
,I/dalvikvm-heap( 4393): Grow heap (frag case) to 11.901MB for 325996-byte allocation
,I/dalvikvm-heap( 4393): Grow heap (frag case) to 12.175MB for 488990-byte allocation
,I/dalvikvm-heap( 4393): Grow heap (frag case) to 13.182MB for 1100216-byte allocation
,I/dalvikvm-heap( 4393): Grow heap (frag case) to 14.060MB for 1650320-byte allocation
,I/dalvikvm-heap( 4393): Grow heap (frag case) to 15.443MB for 2475476-byte allocation
,I/dalvikvm-heap( 4393): Grow heap (frag case) to 17.439MB for 3713210-byte allocation
,I/ActivityManager(  910): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4441 uid=10077 gids={50077}
,D/PMS     (  910): acquireWL(43047d90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10077}
,V/AlarmManager(  910): sending alarm PendingIntent{42657de0: PendingIntentRecord{426b1980 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1450655510501, Int=60000
,D/PMS     (  910): releaseWL(43047d90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4441): SMSBackupAgentService started
,D/SMSBackup( 4441): Checking restore status
D/SMSBackup( 4441): Restore complete
,D/SMSBackup( 4441): cancelCheckAlarm
,D/SMSBackup( 4441): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  910): killProcessQuiet, pid=3253
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 3253:com.android.defcontainer/u0a19 (adj 15): empty #17
,W/jxcore-log( 4393): Initializing JXcore engine
,W/jxcore-log( 4393): JXcore engine is ready
,W/jxcore-log( 4393): Starting JXcore engine
W/CpuWake (  910): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  910): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  910): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  910): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  910): >>release mCpuPerf_Freq wakelock
W/CpuWake (  910): <<release mCpuPerf_Freq wakelock
D/PMS     (  910): releaseHCC(424f68a0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
D/PMS     (  910): releaseHCC(42438b30): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/ActivityManager(  910): Recipient 3253
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1155): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
,W/jxcore-log( 4393): Platform android
W/jxcore-log( 4393): 
,W/jxcore-log( 4393): Process ARCH arm
W/jxcore-log( 4393): 
,I/jxcore-log( 4393): JXcore Cordova bridge is ready!
I/jxcore-log( 4393): 
,W/jxcore-log( 4393): JXcore engine is started
,I/chromium( 4393): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PMS     (  910): releaseWL(42cfc150): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/WifiDataStallTracker(  910): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  910): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/PMS     (  910): acquireWL(43f6bed8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
V/AlarmManager(  910): sending alarm PendingIntent{424fd640: PendingIntentRecord{425b2128 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=105736, Int=0
D/WifiDataStallTracker(  910): updateDataStallInfo: mDataStallTxRxSum={txSum=56 rxSum=43} preTxRxSum={txSum=55 rxSum=42}
D/WifiDataStallTracker(  910): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  910): onDataStallAlarm: tag=20059 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  910): startDataStallAlarm: tag=20060 delay=15s
D/PMS     (  910): releaseWL(43f6bed8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4393): Toggling radios to true
I/jxcore-log( 4393): 
,D/BluetoothAdapter( 4393): enable(): BT is already enabled..!
,D/WifiManager( 4393): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
,W/HtcDLNAServiceManager(  910): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  910): Settings:Agentname: wifi_on
D/WifiService(  910): setWifiEnabled: true pid=4393, uid=10348
E/WifiService(  910): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  910): isSprintWifiRestricted(): false
I/WifiService(  910): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  910): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/HtcDLNAServiceManager(  910): Settings:Agentvalue: 2
W/Settings:Agent(  910): >> traceCallingStack()
,W/Settings:Agent(  910): Process.myPid(): 910
W/Settings:Agent(  910): Process.myTid(): 1295
,W/Settings:Agent(  910): Process.myUid(): 1000
W/Settings:Agent(  910): 
W/Settings:Agent(  910): 
,W/System.err(  910): java.lang.Throwable: stack dump
,W/System.err(  910): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  910): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  910): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  910): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
,W/System.err(  910): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  910): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  910): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  910): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  910): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  910): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  910): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  910): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  910): 
,W/Settings:Agent(  910): << traceCallingStack(): 4(ms)
,D/WifiManager( 4393): disconnect: Base Package Name=com.test.thalitest, uid=10348
D/WifiNative-wlan0(  910): doBoolean: DISCONNECT
D/WifiManager( 4393): reconnect: Base Package Name=com.test.thalitest, uid=10348
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): TDLS: Tear down peers
I/wpa_supplicant( 1155): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4393): Radios toggled
I/jxcore-log( 4393): 
,D/BluetoothManagerService(  910): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/WifiService(  910): New client listening to asynchronous messages
I/jxcore-log( 4393): Got Device Bluetooth address: 80:01:84:8A:B3:68
I/jxcore-log( 4393): 
I/jxcore-log( 4393): Perf Test app loaded loaded
I/jxcore-log( 4393): 
I/Choreographer( 4393): Skipped 79 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 4393): check test folder
I/jxcore-log( 4393): 
,I/jxcore-log( 4393): found test : ./testFindPeers.js
I/jxcore-log( 4393): 
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1155): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1155): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1155): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  910): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  910): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  910): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1155): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1155): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1155): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1155): send_and_recv error -67 - cmd 12
,D/wpa_supplicant( 1155): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1155): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb7590bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1155):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1155): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1155): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1155): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1155): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1155): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1155): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1155): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1155): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1155): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1155): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1155): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1155): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1155): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1155): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1155): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1155): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1155): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1155): nl80211: Ignore disconnect event triggered during reassociation
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  910):    returned true
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDN,G700
D/WifiPerfLock(  910): release()
D/WifiStateMachine(  910): PerfLock released for exiting ConnectedState
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0,
D/Tethering(  910): interfaceLinkStateChanged wlan0, false,
,D/Tethering(  910): interfaceStatusChanged wlan0, false
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1155): Power_Mode_Type mode = 0
I/wpa_supplicant( 1155): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
D/ConnectivityService(  910): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  910): acquireWL(4256cee0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 910 1000 null
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  910):    returned true
D/DhcpStateMachine(  910): [RunningState] Stop DHCP
D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiNative-wlan0(  910): doBoolean: RECONNECT
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): Fast associate: Old scan results
I/wpa_supplicant( 1155): wpa_supplicant_scan enter
I/wpa_supplicant( 1155): State: DISCONNECTED -> SCANNING
I/jxcore-log( 4393): found test : ./testSendData.js
I/jxcore-log( 4393): 
I/wpa_supplicant( 1155): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1155): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 33
,I/wpa_supplicant( 1155): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiP2pService(  910): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  910): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiDataStallTracker(  910): stopDataStallAlarm: current tag=20060 mDataStallAlarmIntent=PendingIntent{42686510: PendingIntentRecord{425b2128 android broadcastIntent}}
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiNative-wlan0(  910):    returned true
,D/WifiStateMachine(  910): Enter handleNetworkDisconnect
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1155): Power_Mode_Type mode = 0
I/wpa_supplicant( 1155): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0,
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  910):    returned true
D/UsbnetStateTracker(  910): isAvailable+-
D/UsbnetStateTracker(  910): reconnect
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
D/UsbnetStateTracker(  910): isAvailable+-
,D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  910): Provision feature enable=false
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/ConnectivityService(  910): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  910): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1858/10178)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  910):    returned true
,D/WISPrService( 4171): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): Exit handleNetworkDisconnect
D/WifiP2pService(  910): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/MDST    (  910): default: reconnect()
D/MDST    (  910): default: setTeardownRequested(false)
D/MDST    (  910): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  910): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  910): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  910): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
,D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4171): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  910): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WifiService(  910): New client listening to asynchronous messages
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/libc    (  364): [NET] entry_id:5   entry:0xb7760818  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb77602d8  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb7760108  removed 
D/libc    (  364): [NET] entry_id:6   entry:0xb7760760  removed 
D/libc    (  364): [NET] entry_id:3   entry:0xb77601d0  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb7760410  removed 
D/libc    (  364): [NET] entry_id:7   entry:0xb77608e0  removed 
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
,D/WISPrService( 4171): >>>>>WISPrService start isConnected = false<<<<<
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): handleConnectivityChange: resetting
D/ConnectivityService(  910): resetConnections(wlan0, 3)
D/ConnectivityService(  910): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1858/10178)
D/PMS     (  910): acquireWL(4256a820): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1368 10028 null
D/ConnectivityService(  910): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  910): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  910): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/WISPrService( 4171): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/WirelessDisplayService(  910): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  910): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WifiStateMachine(  910): startScan Pid: 910 Uid 1000
,D/WifiNative-wlan0(  910): doBoolean: SCAN
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
D/ConnectivityService(  910): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  910): acquireWL(426b74b8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  910): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
,D/BatSI   (  910): WIFI scan started for: 650a0300 uid:1000
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1155): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
I/jxcore-log( 4393): found test : ./testSendData2.js
I/jxcore-log( 4393): 
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/WifiNative-wlan0(  910):    returned false
I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:1
I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,E/jxcore  ( 4393): Error!: unlabeled break must be inside loop or switch
E/jxcore  ( 4393): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
D/PMS     (  910): acquireWL(425c9cc0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1368 10028 null
D/PMS     (  910): releaseWL(426b74b8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/chromium( 4393): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
D/ConnectivityService(  910): reportInetCondition for net -1, percentage: 0 by  (1368/10028)
D/PMS     (  910): releaseWL(425c9cc0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/PMS     (  910): releaseWL(4256a820): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:0
D/ConnectivityService(  910): mActiveDefaultNetwork: -1
D/ConnectivityService(  910): handleInetConditionChange: no active default network - ignore
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  910): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  910): [AlarmQueuing] connectivity wifi: false
,D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
,D/GpsLocationProvider(  910): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  910): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,D/GpsLocationProvider(  910): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  910): ignore wifi update if we are not in OPENING or CLOSING
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1901/1000)
D/PMS     (  910): acquireWL(43efe300): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/PMS     (  910): releaseWL(43efe300): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.google.android.music (3860/10154)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1471/10028)
D/CaptivePortalTracker(  910): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/CaptivePortalTracker(  910): NoActiveNetworkState
,I/NetworkMonitor( 3860): type=WIFI subType= reason=null isConnected=false
,I/ConnectivityHelper( 1272): [onReceive] WIFI(1): DISCONNECTED
D/Tethering(  910): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  910): bSetPropertyMultiRAB:false
D/Tethering(  910): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  910): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
,I/Tethering(  910): ipv4Default null
D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
I/Tethering(  910): No IPv4 upstream interface, giving up.
D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (4283/10100)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.launcher (1272/10075)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1858/10178)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (4283/10100)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/Tethering(  910): TetherMasterSM: InitialState processMessage what=3
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (2441/10021)
,I/ActivityManager(  910): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4463 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4463): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4463): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4463): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4463): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4463): Preparing secondary program dexes.
V/DexLibLoader( 4463): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4463): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4463): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4463): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4463): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4463): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4463): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4463): Dex already copied
D/OdexVerifier( 4463): Odex verification is skipped.
,V/DexLibLoader( 4463): Creating class loader,
,V/DexLibLoader( 4463): Finished creating class loader
V/DexLibLoader( 4463): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4463): Dex already copied
D/OdexVerifier( 4463): Odex verification is skipped.
,V/DexLibLoader( 4463): Creating class loader
,V/DexLibLoader( 4463): Finished creating class loader
V/DexLibLoader( 4463): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4463): Dex already copied
D/OdexVerifier( 4463): Odex verification is skipped.
,V/DexLibLoader( 4463): Creating class loader,
V/DexLibLoader( 4463): Finished creating class loader
V/DexLibLoader( 4463): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar,
V/DexLibLoader( 4463): Dex already copied
D/OdexVerifier( 4463): Odex verification is skipped.
,V/DexLibLoader( 4463): Creating class loader
V/DexLibLoader( 4463): Finished creating class loader
,V/DexLibLoader( 4463): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4463): DexLibLoader.ensureDexLoaded took 19 ms
,W/dalvikvm( 4463): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4463): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4463): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4463): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4463): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4463): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4463): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4463): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4463): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1155): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1155): nl80211: Survey data missing
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1155): Sorted scan results
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1155): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1155): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1155): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-76
I/wpa_supplicant( 1155): [NULL] fc:94:e3:11:35:3a freq=2462 level=-88
I/wpa_supplicant( 1155): [NULL] fe:94:e3:11:35:3c freq=2462 level=-88
I/wpa_supplicant( 1155): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
D/wpa_supplicant( 1155): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1155): Add randomness: count=8 entropy=0
D/wpa_supplicant( 1155): Add randomness: count=9 entropy=1
D/wpa_supplicant( 1155): Add randomness: count=10 entropy=2
D/wpa_supplicant( 1155): Add randomness: count=11 entropy=3
D/wpa_supplicant( 1155): Add randomness: count=12 entropy=4
D/wpa_supplicant( 1155): Add randomness: count=13 entropy=5
D/wpa_supplicant( 1155): Add randomness: count=14 entropy=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  910): doString: LIST_DONGLES
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1155): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1155): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1155): wpa_supplicant_pick_network+
I/wpa_supplicant( 1155): Selecting BSS from priority group 1
I/wpa_supplicant( 1155): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1155): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1155): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1155): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1155):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1155):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-50
I/wpa_supp,licant( 1155): Start print parameters
I/wpa_supplicant( 1155): wpa_s->wpa_state is 3
I/wpa_supplicant( 1155): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1155): isConcurrentMode() is 0
I/wpa_supplicant( 1155): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1155): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1155): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1155): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1155): wpa_s->reassociate is 1
I/wpa_supplicant( 1155): wpa_s->is_screen_on 1
I/wpa_supplicant( 1155): wpa_s->ifname wlan0
I/wpa_supplicant( 1155): End print parameters
I/wpa_supplicant( 1155): selected network = 1
D/wpa_supplicant( 1155): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb75924e8  current_ssid=0x0
D/wpa_supplicant( 1155): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1155): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1155): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1155): check if in concurrent case
I/wpa_supplicant( 1155): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1155): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1155): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1155): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1155): RSN: PMKSA cache search - network_ctx=0xb75924e8 try_opportunistic=0
D/wpa_supplicant( 1155): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1155): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1155): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1155): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1155): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1155): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1155): nl80211: Unsubscribe mgmt frames handle 0xb7591718 (mode change)
D/wpa_supplicant( 1155): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7591718
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb7591718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb7591718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb7591718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb7591718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb7591718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb7591718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb7591718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb7591718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb7591718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Register frame type=0xd0 nl_handle=0xb7591718
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1155): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1155):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1155):   * freq=2412
D/wpa_supplicant( 1155):   * Auth Type 0
D/wpa_supplicant( 1155):   * WPA Versions 0x2
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1155): nl80211: Connect request send successfully
D/wpa_supplicant( 1155): ,EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  910): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1155): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1155): reply (906) for get BSS: id=0
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1155): freq=5220
I/wpa_supplicant( 1155): level=-48
I/wpa_supplicant( 1155): tsf=0000000108851124
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG7005g
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=1
I/wpa_supplicant( 1155): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-50
I/wpa_supplicant( 1155): tsf=0000000108851141
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=NG700
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=2
I/wpa_supplicant( 1155): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-76
I/wpa_supplicant( 1155): tsf=0000000108851144
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1155): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=3
I/wpa_supplicant( 1155): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1155): freq=2462
I/wpa_supplicant( 1155): level=-88
I/wpa_supplicant( 1155): tsf=0000000108851151
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC0039325
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=4
I/wpa_supplicant( 1155): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1155): freq=2462
I/wpa_supplicant( 1155): level=-88
I/wpa_supplicant( 1155): tsf=0000000108851147
I/wpa_supplicant( 1155): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1155): ssid=UPC Wi-Free
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=5
I/wpa_supplicant( 1155): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): freq=2412
I/wpa_supplicant( 1155): level=-50
I/wpa_supplicant( 1155): tsf=0000000108851136
I/wpa_supplicant( 1155): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1155): ssid=01ABC
I/wpa_supplicant( 1155): ====
I/wpa_supplicant( 1155): id=6
I/wpa_supplicant( 1155): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1155): freq=2437
I/wpa_supplicant( 1155): level=-90
I/wpa_supplicant( 1155): tsf=0000000108851154
I/wpa_supplicant( 1155): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1155): ssid=UPC4688432
I/wpa_supplicant( 1155): ####
W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  910): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 108851124, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 2412, timestamp: 108851141, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 2: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -76, frequency: 2437, timestamp: 108851144, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 108851151, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 4: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 108851147, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 5: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -50, frequency: 2412, timestamp: 108851136, distance: ?(cm), distanceSd: ?(cm)
D/WirelessDisplayService(  910): getDiscoveryDongleList
D/WifiStateMachine(  910): == begin of scan result ==
D/WifiStateMachine(  910): == (7) end of scan result ==
D/WirelessDisplayService(  910): getDiscoveryDongleList
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/WifiStateMachine(  910): 6: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 108851154, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): add 7 to mScanResults
D/BatSI   (  910): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  910): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,E/FbInjectorInitializer( 4463): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/wpa_supplicant( 1155): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1155): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1155): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 1155): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1155): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1155): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1155): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1155): nl80211: Event message available
D/wpa_supplicant( 1155): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1155): nl80211: Connect event
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1155): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1155): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1155): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1155): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1155): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1155): Add randomness: count=15 entropy=7
I/wpa_supplicant( 1155): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1155): TDLS: Remove peers on association
D/wpa_supplicant( 1155): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/Tethering(  910): [isWifi] getHotspotEnabled: false
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1155): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1155): EAPOL: enable timer tick
D/wpa_supplicant( 1155): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1155): htc_wext_set_keepalive +
I/wpa_supplicant( 1155): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1155): getPrivFuncNum +	
I/wpa_supplicant( 1155): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1155): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1155): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1155): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1155): Get randomness: len=32 entropy=8
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  910): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  910): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  910): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  910): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMon,itor(  910): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  910): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  910): Enter handleAssociatedWithEvent
D/WifiStateMachine(  910): Associated
D/WifiStateMachine(  910): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  910): Exit handleAssociatedWithEvent
D/WifiStateMachine(  910): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/Tethering(  910): interfaceLinkStateChanged wlan0, true
D/Tethering(  910): interfaceStatusChanged wlan0, true
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/WifiStateMachine(  910): WifiApDatabaseHandler, WiFi AP database Inserting ..,
D/WifiApDatabaseHandler(  910): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  910): This record is existed, only update it...
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
I/wpa_supplicant( 1155): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb75919f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1155):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1155): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1155): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6ecfb4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1155):    broadcast key
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1155): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1155): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1155): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1155): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
,I/wpa_supplicant( 1155): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1155): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1155): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1155): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1155): set send_ind_to_ndc = 0
I/wpa_supplicant( 1155): htc_wext_set_TX_TRACKING (1)+
,I/wpa_supplicant( 1155): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1155): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1155): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1155): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1155): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1155): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1155): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1155): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1155): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1155): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1155): EAPOL authentication completed successfully
I/wpa_supplicant( 1155): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1155): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1155): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1155): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  910): interfaceLinkStateChanged wlan0, true
D/Tethering(  910): interfaceStatusChanged wlan0, true
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
,D/WifiMonitor(  910): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...,
,D/WifiStateMachine(  910): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  910): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiApDatabaseHandler(  910): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  910): This record is existed, only update it...
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  910): Provision feature enable=false
D/ConnectivityService(  910): mActiveDefaultNetwork: -1
,D/WISPrService( 4171): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4171): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/DhcpStateMachine(  910): [StoppedState] Start DHCP
D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1155): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1155): Power_Mode_Type mode = 1
,I/wpa_supplicant( 1155): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  910):    returned null
E/WifiStateMachine(  910): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  910):    returned null,
D/WifiStateMachine(  910): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  910): acquireWL(440bbbb0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 910 1000 null
,D/WifiStateMachine(  910): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  910): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42508d30 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42508d30 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:0
,W/fb4a(:<default>):StaticBindingVerifier( 4463): Verify
,D/WifiService(  910): New client listening to asynchronous messages
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4463/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4463): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4463): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4463): Grow heap (frag case) to 9.517MB for 73240-byte allocation
,D/Process (  910): killProcessQuiet, pid=4222
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  910): Killing 4222:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,D/PMS     (  910): acquireWL(43611238): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2228 10028 null
,D/PMS     (  910): acquireWL(43b86e70): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2228 10028 null
,D/PMS     (  910): releaseWL(43611238): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1368): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2228/10028)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2228/10028)
,D/PMS     (  910): releaseWL(43b86e70): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/AutoSetting( 1422): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  910): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4492 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1422/10053)
,D/AutoSetting( 1422): Util - no network available!
,D/AutoSetting( 1422): service - onCreate()
,D/AutoSetting( 1422): service - AddressCache: using context: com.htc.Weather
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1422/10053)
D/AutoSetting( 1422): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/LocationManagerService(  910): request 41ce99e8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/LocationManagerService(  910): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1422): service - mHandler: cancel location update
D/AutoSetting( 1422): service -           changes count: 0
,I/ActivityManager(  910): Recipient 4222
D/WifiService(  910): Client connection lost with reason: 4
,W/fb4a(:<default>):UserScope( 4463): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4463): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MobileConnectivityChangeReceiver( 4492): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4492): onReceive CONNECTIVITY_CHANGE networkType=1
,W/fb4a(:<default>):UserScope( 4463): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
E/PhoneMonitor( 4492): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4492): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  910): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4508 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4492/10078)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4492/10078)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4492/10078)
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4463): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,I/ActivityManager(  910): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4525 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  910): killProcessQuiet, pid=3839
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  910): Killing 3839:com.htc.mediamanager/u0a32 (adj 15): empty #17
,E/dalvikvm( 4463): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4463): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4463): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4463): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4463): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4463): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4463): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4463): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4463): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4463): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4463): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4463): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4463): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4463): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4463): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4463): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4463): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4463): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/dalvikvm-heap( 4463): Grow heap (frag case) to 9.928MB for 39954-byte allocation
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4525): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4525): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/ActivityManager(  910): Recipient 3839
,W/GAV2    ( 4525): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4525): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4525): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
I/dalvikvm-heap( 4463): Grow heap (frag case) to 10.004MB for 79892-byte allocation
,I/dalvikvm-heap( 4463): Grow heap (frag case) to 10.075MB for 84664-byte allocation
,I/dalvikvm-heap( 4463): Grow heap (frag case) to 10.101MB for 28144-byte allocation
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4525/10151)
,V/WebViewChromiumFactoryProvider( 4525): Binding Chromium to main looper Looper (main, tid 1) {41b29170}
,I/LibraryLoader( 4525): Expected native library version number "",actual native library version number ""
,I/chromium( 4525): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4525): Initializing chromium process, renderers=0
,D/PMS     (  910): acquireWL(43fe87b8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,D/PMS     (  910): acquireWL(4401e1a8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,E/AudioManagerAndroid( 4525): BLUETOOTH permission is missing!
D/PMS     (  910): releaseWL(4401e1a8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4525): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4525): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4525): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4525): Local Branch: 
I/Adreno-EGL( 4525): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4525): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4525):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4525): Starting up...
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4525/10151)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4525/10151)
,I/dalvikvm-heap( 4463): Grow heap (frag case) to 10.289MB for 75760-byte allocation
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (4148/10160)
,D/Process (  910): killProcessQuiet, pid=4021
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (4148/10160)
I/ActivityManager(  910): Killing 4021:com.google.android.gm/u0a107 (adj 15): empty #17
D/ConnectivityService(  910): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1858/10178)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4463/10026)
,D/GCM     ( 1368): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43b7eb40 u0 ReceiverList{43acd3c8 4463 com.facebook.katana/10026/u0 remote:43ab7360}}
W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43b7eb40 u0 ReceiverList{43acd3c8 4463 com.facebook.katana/10026/u0 remote:43ab7360}}
D/ConnectivityService(  910): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1858/10178)
W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{430dfd98 u0 ReceiverList{430dfd38 4463 com.facebook.katana/10026/u0 remote:440ae270}}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4463/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4463/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4463/10026)
,D/PMS     (  910): acquireWL(436f0e48): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1471 10028 null
,D/PMS     (  910): releaseWL(436f0e48): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/SensorManager(  910): mEventCount = 1050
,D/GCoreFlp( 1471): Unknown pending intent to remove.
D/PMS     (  910): acquireWL(430e6c18): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1471 10028 null
D/PMS     (  910): releaseWL(430e6c18): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/ActivityManager(  910): Recipient 4021
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4463): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/wpa_supplicant( 1155): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1155): EAPOL: disable timer tick
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4463): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1155): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1155): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/WifiP2pService(  910): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  910): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  910):    returned true
,D/WifiStateMachine(  910): handlePostDhcpSetup release wake lock during DHCP
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): releaseWL(440bbbb0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1155): WiFioffload: SignalStrength: =97
D/WIFI_ICON( 1116): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): gateway: /192.168.1.1
D/WifiNative-wlan0(  910): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1155): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  910): VerifyingLinkState enter
D/WifiStateMachine(  910): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  910): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  910): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -50, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
,V/NetworkPolicy(  910): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/WifiDataStallTracker(  910): startDataStallAlarm: tag=20062 delay=15s
,D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,D/ConnectivityService(  910): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1858/10178)
D/ConnectivityService(  910): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
,D/ConnectivityService(  910): Provision feature enable=false
,D/WifiWatchdogStateMachine(  910): WAN detection
D/ConnectivityService(  910): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  910): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  910): default: teardown()
D/MDST    (  910): default: setTeardownRequested(true)
D/MDST    (  910): default: setEnableApn apnType =default , enable=false
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WISPrService( 4171): >>>>>WISPrService start isConnected = true<<<<<
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/MDST    (  910): default: setTeardownRequested(true)
D/ConnectivityService(  910): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
,D/WIFI_ICON( 1116): WifiActivity: 3
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [1][0][0]
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/WifiStateMachine(  910): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): syncGetConfiguredNetworks
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/ConnectivityService(  910): Unexpected mtu value: android.net.wifi.WifiStateTracker@42453c38
D/ConnectivityService(  910): handleConnectivityChange: netType=1 doReset=false resetMask=0
,D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
,I/QuickSettingWifi( 1116): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/ConnectivityService(  910): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  910): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  910): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  910): handleConnectivityChange: resetting
D/Nat464Xlat(  910): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  910): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
,D/WirelessDisplayService(  910): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/WirelessDisplayService(  910):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  910): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  910): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  910): acquireWL(4405a120): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
D/ConnectivityService(  910): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4492/10078)
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/PMS     (  910): acquireWL(43076008): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2228 10028 null
D/PMS     (  910): releaseWL(4405a120): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  910): acquireWL(43718e70): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2228 10028 null
D/PMS     (  910): releaseWL(43076008): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2228/10028)
I/CheckinService( 2228): Preparing to send checkin request
I/EventLogService( 2228): Accumulating logs since 1450655462186
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,I/GoogleHttpClient( 2228): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2228): Using GMS GoogleHttpClient
,D/ConnectivityService(  910): mActiveDefaultNetwork: WIFI
,D/ConnectivityService(  910): getNetworkInfo networkType=9 called by com.google.android.gms (2228/10028)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getNetworkInfo networkType=0 called by com.google.android.gms (2228/10028)
,W/GLSUser ( 1368): GoogleAccountDataService.getToken()
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1368): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/CheckinRequestBuilder( 2228): awaiting user notification for token
,D/DotMatrix( 1574): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1574): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41c6eb80 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.google.android.gms 2 6 2 12
,I/ActivityManager(  910): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4600 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 4600): install
,I/MultiDex( 4600): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4600): loading existing secondary dex files
,I/MultiDex( 4600): load found 1 secondary dex files
,I/MultiDex( 4600): install done
,I/ProviderInstaller( 4600): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1368): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/dalvikvm( 4393): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4393): threadid=1: thread exiting with uncaught exception (group=0x416f1e30)
,E/ActivityManager(  910): App crashed! Process: com.test.thalitest
E/AndroidRuntime( 4393): FATAL EXCEPTION: main
E/AndroidRuntime( 4393): Process: com.test.thalitest, PID: 4393
E/AndroidRuntime( 4393): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4393): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4393): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4393): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4393): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4393): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4393): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4393): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4393): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4393): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4393): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4393): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4393): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4393): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4393): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4393): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4393): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4393): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4393): 	at dalvik.system.NativeStart.main(Native Method)
W/ActivityManager(  910):   Force finishing activity com.test.thalitest/.MainActivity
I/ActivityManager(  910): mThumbnailWidth=360, mThumbnailHeight=640
,D/PMS     (  910): acquireWL(438ed3d0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 910 1000 null
,I/PMS     (  910): Going to sleep due to screen timeout...
,I/SensorManager(  910): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42402750
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  910): disable: get sensor name = CM36282 Light sensor
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 2
W/SensorService(  910): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42402750, eanble = 0, strlen(mName) = 59
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  910): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42380200
W/SensorService(  910): Listener[1] = com.htc.smartdim.sensor_eye@425ceb40
,W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/WirelessDisplayService(  910): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  910): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  910): mWirelessDisplayManager is null
W/BatSI   (  910): Couldn't get kernel wake lock stats
V/LightsService(  910): setLight #2: color=#0
D/qdlights(  910): set_light_buttons_func: on=0 brightness=0
V/LightsService(  910): setLight #0: color=#0
,I/Adreno-EGL( 4600): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4600): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4600): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4600): Local Branch: 
I/Adreno-EGL( 4600): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4600): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4600):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4600): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4600): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4600): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4600): Local Branch: 
I/Adreno-EGL( 4600): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4600): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4600):                  aa63bbd948f41d15fc72f585e
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (4600/10028)
,D/PMS     (  910): releaseWL(4256cee0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  910): NetTransition Wakelock for ConnectedState released by timeout
,V/Tethering(  910): mTetherableUsbRegexs:{(usb0)(ncm0)}
,V/Tethering(  910): bSetPropertyMultiRAB:false
,D/Tethering(  910): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,I/Tethering(  910): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
,I/Tethering(  910): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  910): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
,I/Tethering(  910): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  910): Found interface wlan0
,D/Tethering(  910): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiStateMachine(  910): BroadcastRSSIForIMS, newrssi =-50 , oldRssi= -200
,D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1155): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
,D/SurfaceControl(  910): Excessive delay in blankDisplay() while turning screen off: 389ms
,V/KeyguardServiceDelegate(  910): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@425477f8)
,D/NfcService( 1256): ScreenObserver: OFF
D/NfcService( 1256): applyRouting - 0
D/PMS     (  910): nativeSetInteractive:false
D/PMS     (  910): nativeSetInteractive:false done
D/PMS     (  910): nativeSetAutoSuspend:true
D/PMS     (  910): nativeSetAutoSuspend:true done
D/HABCtrl (  910): TPE algorithm. remove timeout.
D/PMS     (  910): OOBE c monitor 11
D/PMN     (  910): wakingUp
I/InputMethodManagerService(  910): screenObserver, isScreenOn=false
I/InputMethodManagerService(  910): Disable input method client, pid=4393
,V/KeyguardServiceDelegate(  910): **** SHOWN CALLED ****
,D/NfcService( 1256): applyRouting -2
I/WindowManager(  910): No lock screen! windowToken=null
D/PMS     (  910): acquireWL(4217faa0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
D/PMS     (  910): releaseWL(4217faa0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  910): onScreenOn
D/PMS     (  910): acquireWL(425b10f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/AlarmManager(  910): [AlarmQueuing] connectivity wifi: true
I/BatteryService(  910): n_update end
D/PMS     (  910): releaseWL(425b10f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/WIFI_ICON( 1116): updateWifiState: RSSI_CHANGED 3 -> 3
,I/ConnectivityHelper( 1272): [onReceive] WIFI(1): CONNECTED
I/acms    ( 1901): Checking Certificates
I/acms    ( 1901): Checking Developer Certificates
I/acms    ( 1901): Checking Application Certificates
I/acms    ( 1901): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1901): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1901): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/NetworkMonitor( 3860): type=WIFI subType= reason=null isConnected=true
I/acms    ( 1901): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1901): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1901): Updating next query delay: 75600000
I/mlserverapp( 1901): MirrorLink is never connected, don't setup ACMS programed checks
,I/mlserverapp( 1901): cancelACMSProgrammedChecks
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1858/10178)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.launcher (1272/10075)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.google.android.music (3860/10154)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1901/1000)
W/ActivityManager(  910): Activity pause timeout for ActivityRecord{42331e28 u0 com.test.thalitest/.MainActivity t2 f}
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.musicenhancer (3913/10051)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (4283/10100)
D/CaptivePortalTracker(  910): NoActiveNetworkState
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): acquireWL(430f4310): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1471/10028)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
I/FeedHostManager( 1272): [onResume]
I/FeedProviderManager( 1272): onResume
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
I/SocialFeedProvider( 1272): +onResume
I/SocialFeedProvider( 1272): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1272): -onResume
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/NfcService( 1256): applyRouting - 0
D/MtpService( 2441): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4492/10078)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (4283/10100)
D/PMS     (  910): acquireWL(43216298): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/MtpService( 2441): [MTP][onReceive]-
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NfcService( 1256): applyRouting -2
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/GpsLocationProvider(  910): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  910): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  910): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  910): ignore wifi update if we are not in OPENING or CLOSING
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): acquireWL(4241f3b8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
D/PMS     (  910): releaseWL(4241f3b8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMS     (  910): releaseWL(43216298): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  910): releaseWL(430f4310): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/WirelessDisplayService(  910): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
D/WirelessDisplayService(  910): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  910): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4463/10026)
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.launcher (1272/10075)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4463/10026)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (2441/10021)
I/InputManager(  910): Cancel all due to getting PMS screen off broadcast
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  910): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  910): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  910): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4463/10026)
I/IntentController( 1116): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/WifiDataStallTracker(  910): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  910): startDataStallAlarm: tag=20063 delay=15s
,D/WifiNative-wlan0(  910): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1155): SET_SCREEN_ON:On
I/wpa_supplicant( 1155): htc_wext_set_keepalive +
I/wpa_supplicant( 1155): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1155): getPrivFuncNum +	
I/wpa_supplicant( 1155): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1155): htc_wext_set_keepalive fnum = 0x8bf6
D/AlarmManager(  910): ACTION_SCREEN_ON
I/AlarmManager(  910): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  910): [AlarmQueuing] done recovering
I/AlarmManager(  910): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  910): [AlarmQueuing] done EPS screen off alarm recovering
,D/PMS     (  910): acquireWL(4264a238): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2228 10028 null
I/wpa_supplicant( 1155): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1155): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1155): htc_wext_set_TX_TRACKING - ret = 0
,D/WifiNative-wlan0(  910):    returned true
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
D/PMS     (  910): releaseWL(4264a238): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/WIFI_ICON( 1116): WifiActivity: 0
V/NotificationService(  910): batLight: Full, plugged
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/SRS_Proc(  371): ParamSet string: screen_state=on
D/WirelessDisplayService(  910): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,D/GCM     ( 1368): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1155): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
,I/ClockThread( 1116): stop update clock
D/libc    ( 1368): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1368): [NET] getaddrinfo-,err=8
D/libc    ( 1368): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1368): [NET] getaddrinfo-, 1
,D/libc    ( 1368): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =9d17 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
D/PMS     (  910): releaseWL(438ed3d0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/WIFI_ICON( 1116): updateWifiState: RSSI_CHANGED 3 -> 3
D/PMS     (  910): acquireWL(43f68f50): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1368 10028 null
D/NetworkPolicy(  910): updateScreenOn: false
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/libc    ( 1368): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1368): [NET] getaddrinfo-,err=8
D/libc    ( 1368): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1368): [NET] getaddrinfo-, 1
,D/libc    ( 1368): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
,D/libc    (  364): [NET] +++++ res_nsend xid =96cb +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): acquireWL(43f68f50): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1368 10028 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2228/10028)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4463/10026)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4463/10026)
,D/AutoSetting( 1422): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/MobileConnectivityChangeReceiver( 4492): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4492): onReceive CONNECTIVITY_CHANGE networkType=1
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1422/10053)
,D/AutoSetting( 1422): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1422): service - onStartCommand() screen is off, don't request location
,D/AutoSetting( 1422): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1422): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4525/10151)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1422/10053)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [3][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 219
D/libc    (  364): [NET]res_nsend:resplen=79
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/libc    ( 1368): [NET] getaddrinfo_proxy-, success
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (4148/10160)
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,W/fb4a(:<default>):UserScope( 4463): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/Process (  910): killProcessQuiet, pid=4253
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/libc    (  364): [NET]res_nsend:resplen=79
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1368): [NET] getaddrinfo_proxy-, success
,W/fb4a(:<default>):UserScope( 4463): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1820): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1820): onScreenOn: 1450655518538
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1820): onScreenOn: 1450655518538
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (4148/10160)
I/ActivityManager(  910): Killing 4253:com.google.android.partnersetup/u0a31 (adj 15): empty #17
D/PMS     (  910): acquireWL(43c5a0b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1471 10028 null
D/PMS     (  910): releaseWL(43c5a0b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/AutoSetting( 1422): receiver - intent: android.intent.action.USER_PRESENT
D/ConnectivityService(  910): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1858/10178)
I/ActivityManager(  910): Recipient 4253
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/SensorManager(  910): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42380200
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  910): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 2
W/SensorService(  910): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42380200, eanble = 0, strlen(mName) = 91
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  910): Listener[0] = com.htc.smartdim.sensor_eye@425ceb40
,W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/AutoSetting( 1422): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4463/10026)
D/PMN     (  910): goingToSleep
,D/PMS     (  910): acquireWL(440bc5e8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 910 1000 null
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
I/FeedHostManager( 1272): [onPause]
I/FeedProviderManager( 1272): onPause
I/FeedHostManager( 1272): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41d31668
I/SocialFeedProvider( 1272): +onPause
I/SocialFeedProvider( 1272): -onPause
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=50 [2][1][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/TetherSettings( 4171): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4171): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4171): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4171): Cust_ConnectToPC   : spcsc>false
D/        ( 4171): Cust_ConnectToPC   : IPT>true
,D/        ( 4171): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 4171): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/WifiDataStallTracker(  910): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  910): stopDataStallAlarm: current tag=20063 mDataStallAlarmIntent=PendingIntent{44091ac8: PendingIntentRecord{425b2128 android broadcastIntent}}
D/AlarmManager(  910): ACTION_SCREEN_OFF
I/AlarmManager(  910): [AlarmQueuing] screen off now: 
I/AlarmManager(  910): [AlarmQueuing] data connection: true
I/AlarmManager(  910): [AlarmQueuing] wifi connection: true
,D/PMS     (  910): releaseWL(440bc5e8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
E/SmartNS_Utility( 4171): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4171): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4171): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/WifiNative-wlan0(  910): doBoolean: DRIVER SETSUSPENDMODE 1
D/WifiNative-wlan0(  910): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,I/PSReceiver( 4171): onReceive:android.intent.action.USER_PRESENT
,I/SmartNS_PSService( 4171): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4171): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4171):  defaultType:0
D/PMS     (  910): acquireWL(431bfce0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 910 1000 null
W/ContextImpl( 4171): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,D/wpa_supplicant( 1155): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  910):    returned true
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1155): SET_SCREEN_ON:Off
I/wpa_supplicant( 1155): htc_wext_set_keepalive +
I/wpa_supplicant( 1155): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1155): getPrivFuncNum +	
I/wpa_supplicant( 1155): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1155): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1155): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1155): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1155): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  910):    returned true
,V/SRS_Proc(  371): ParamSet string: screen_state=off
D/PMS     (  910): releaseWL(431bfce0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4463/10026)
,I/ActivityManager(  910): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4643 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/Adreno-EGL( 4600): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4600): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4600): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4600): Local Branch: 
I/Adreno-EGL( 4600): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4600): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4600):                  aa63bbd948f41d15fc72f585e
,D/NetworkPolicy(  910): updateScreenOn: false
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
W/Settings( 4600): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/ContactMessageStore( 1245): start background delete task...
D/ContactMessageStore( 1245): size: 0 , 0
,D/ContactMessageStore( 1245): Background delete complete
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [4][0][0]
,W/ContextImpl( 4643): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4643): isEpsOn(), nState = 0
,I/PhoneStatusBar( 1116): removeHeadsNotification.gc: 51
D/PMS     (  910): acquireWL(4401b028): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4643 1000 null
,D/PMS     (  910): releaseWL(4401b028): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4643): getMobilePolicyEnabled, result = true
W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  910): killProcessQuiet, pid=4283
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4283:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] getTotalRam: 1873 Mb
,W/ContextImpl( 4643): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  910): acquireWL(4372ee30): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1471 10028 null
,I/ActivityManager(  910): Recipient 4283
,D/SmartSyncUtils( 4643): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4643): getMobilePolicyEnabled, result = true
D/libc    ( 1368): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/PMS     (  910): releaseWL(4372ee30): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/libc    ( 1368): [NET] getaddrinfo-,err=8
D/SmartSyncUtils( 4643): isEpsOn(), nState = 0
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1820): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1820): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1820): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1820): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1820): onScreenOff
,I/CheckinTask( 2228): Sending checkin request (8970 bytes)
D/libc    ( 2228): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2228): [NET] getaddrinfo-,err=8
D/libc    ( 2228): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2228): [NET] getaddrinfo-, 1
,D/libc    ( 2228): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =a4b7 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/WifiService(  910): New client listening to asynchronous messages
,D/AutoSetting( 1422): service - mHandler: cancel location update
,D/AutoSetting( 1422): service -           changes count: 0
I/SensorManager(  910): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@425ceb40
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  910): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 1
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@425ceb40, eanble = 0, strlen(mName) = 36
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  910): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 0
W/SensorService(  910): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@425ceb40, eanble = 0, strlen(mName) = 36
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  910): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@425ceb40
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  910): acquireWL(4402ad88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1368 10028 null
D/PMS     (  910): releaseWL(4402ad88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
E/ActivityThread(  910): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@426120e0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  910): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@426120e0 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,E/fb4a(:<default>):LocalFbBroadcastManager( 4463): Called registerBroadcastReceiver twice.
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 252
D/libc    (  364): [NET]res_nsend:resplen=84
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2228): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2228): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2228): [NET] getaddrinfo-,err=8
,D/libc    ( 1368): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1368): [NET] getaddrinfo-,err=8
,D/GCM     ( 1368): Connected
D/PMS     (  910): acquireWL(431daa30): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1368 10028 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
D/PMS     (  910): acquireWL(43d97538): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1368 10028 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
D/PMS     (  910): releaseWL(43d97538): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/PMS     (  910): releaseWL(43f68f50): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1368/10028)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  910): handleInetConditionChange: starting a change hold
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
D/PMS     (  910): releaseWL(431daa30): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  910): acquireWL(43bdcbd0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1368 10028 null
D/PMS     (  910): releaseWL(43fe87b8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4463/10026)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4463/10026)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4463/10026)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4463/10026)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4463/10026)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4463/10026)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4463/10026)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4463/10026)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4463/10026)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4463/10026)
,D/GCM     ( 1368): Message class mpf
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4463/10026)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4463/10026)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4463/10026)
D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1368/10028)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4463/10026)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4463/10026)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1368/10028)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4463/10026)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4463/10026)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4463/10026)
D/PMS     (  910): releaseWL(43bdcbd0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4463/10026)
D/PMS     (  910): acquireWL(43720b90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1368 10028 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4463/10026)
D/PMS     (  910): acquireWL(440a4fe0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1368 10028 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4463/10026)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4463/10026)
D/PMS     (  910): releaseWL(43720b90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 0 by  (1368/10028)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=0,mActiveDefaultNetwork=1
D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
D/PMS     (  910): releaseWL(440a4fe0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  910): acquireWL(435ba068): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1368 10028 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
D/PMS     (  910): releaseWL(435ba068): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 0 by  (1368/10028)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=0,mActiveDefaultNetwork=1
D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
,D/ContactMessageStore( 1245): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1245): MSG_NOTIFY_CS_TO_SYNC <<
,D/PMS     (  910): acquireWL(43c41080): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1368 10028 null
,D/PMS     (  910): releaseWL(43c41080): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  910): getNetworkInfo networkType=9 called by com.google.android.gms (2228/10028)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=12 [31][4][0]
D/ConnectivityService(  910): getNetworkInfo networkType=0 called by com.google.android.gms (2228/10028)
,W/GLSUser ( 1368): GoogleAccountDataService.getToken()
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1368): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1574): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1574): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 2228): awaiting user notification for token
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41eb7c10 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.google.android.gms 2 10 3 12
,I/CheckinTask( 2228): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2228): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  910): handleInetConditionHoldEnd: net=1, condition=0, published condition=0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2228/10028)
D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2228/10028)
,D/GCM     ( 1368): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  910): releaseWL(43718e70): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 2228): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41c0d768 that was originally bound here
E/ActivityThread( 2228): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41c0d768 that was originally bound here
E/ActivityThread( 2228): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2228): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2228): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2228): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2228): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2228): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2228): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2228): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2228): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2228): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2228): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2228): 	at bks.a(SourceFile:298)
E/ActivityThread( 2228): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2228): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2228): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2228): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1368): GCM config loaded
D/libc    ( 1368): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1368): [NET] getaddrinfo-,err=8
D/libc    ( 1368): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1368): [NET] getaddrinfo-, 1
,D/libc    ( 1368): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =53bc +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1368): [NET] getaddrinfo_proxy-, success
D/PMS     (  910): acquireWL(4369f2e0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1368 10028 null
,D/libc    ( 1368): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1368): [NET] getaddrinfo-,err=8
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
D/PMS     (  910): acquireWL(4431f0f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1368 10028 null
D/PMS     (  910): releaseWL(4431f0f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/WifiStateMachine(  910): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  910): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,D/PMS     (  910): acquireWL(44083ee0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42228ec0: PendingIntentRecord{41fa2958 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=113801, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(44083ee0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-,err=8
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  910): [NET] getaddrinfo-, 1
,D/libc    (  910): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =4c92 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE,
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19,
D/libc    (  364): [NET]res_nsend:resplen=172
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
,D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  910): Find DNS Address www.htc.com/104.81.130.175,
,I/GAV2    ( 4525): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  910): acquireWL(44077cc0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1471 10028 null
,D/PMS     (  910): acquireWL(44073a98): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1471 10028 null
,D/PMS     (  910): releaseWL(44077cc0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  910): releaseWL(44073a98): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/AutoSetting( 1519): service - handleMessage() stop self
,D/AutoSetting( 1519): service - onDestroy() END
,D/Process (  910): killProcessQuiet, pid=4306
,I/ActivityManager(  910): Killing 4306:com.htc.backup/1000 (adj 15): empty #17
D/AutoSetting( 1519): service - handleMessage() quit looper
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  910): Recipient 4306
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  910): killProcessQuiet, pid=4324
,I/ActivityManager(  910): Killing 4324:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  910): Recipient 4324
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  910): releaseWL(4369f2e0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  910): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,W/ActivityManager(  910): Activity destroy timeout for ActivityRecord{42331e28 u0 com.test.thalitest/.MainActivity t2 f}
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{44080f50 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  910): acquireWL(43b12ea0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): releaseWL(43b12ea0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(4308e8c8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1368 10028 null
,D/libc    ( 1368): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1368): [NET] getaddrinfo-,err=8
D/libc    ( 1368): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1368): [NET] getaddrinfo-, 1
,D/libc    ( 1368): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =9d5a +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1368): [NET] getaddrinfo_proxy-, success,
D/PMS     (  910): acquireWL(430560d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1368 10028 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
D/PMS     (  910): releaseWL(430560d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/libc    ( 1368): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4,
,D/libc    ( 1368): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
,D/PMS     (  910): acquireWL(42ec3e30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1368 10028 null
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 0 by  (1368/10028)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=0,mActiveDefaultNetwork=1
,D/ConnectivityService(  910): handleInetConditionChange: starting a change hold
,D/PMS     (  910): releaseWL(42ec3e30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  910): releaseWL(4308e8c8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1368/10028)
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 2
,D/ConnectivityService(  910): handleInetConditionHoldEnd: net=1, condition=0, published condition=0
,D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=3 [26][1][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1155): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1155): nl80211: survey data missing!
E/wpa_supplicant( 1155): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1155): environment dirty rate=0 [0][0][0]
,D/AutoSetting( 1422): service - mHandler: update timezone
,D/AutoSetting( 1519): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1519): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1519): service - onCreate()
W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1519): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1519): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/DotMatrix( 1574): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
D/DotMatrix( 1574): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,D/AutoSetting( 1519): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1519): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1519): service - mHandler: update timezone
,D/AutoSetting( 1519): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1519): service - processTimeZoneID() system nitz is valid: false (false)
,D/PMS     (  910): acquireWL(42cdfac0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42cdfac0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/AutoSetting( 1519): service - processTimeZoneID() single-timezone, pop up dialog
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/AutoSetting( 1519): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,D/PowerUI ( 1116): closing low battery warning: level=100
,D/DotMatrix( 1574): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1574): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/RemoteViews( 1116): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41ee9508 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.htc.htclocationservice 2 8 2 11
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(41c8aba0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
V/AlarmManager(  910): sending alarm PendingIntent{424e9c90: PendingIntentRecord{4239bbe8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141607, Int=0
,V/AlarmManager(  910): sending alarm PendingIntent{4237de98: PendingIntentRecord{41e5ef20 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142657, Int=0
,D/AutoSetting( 1422): service - handleMessage() stop self
,D/AutoSetting( 1422): service - handleMessage() quit looper
,D/AutoSetting( 1422): service - onDestroy() END
,D/GpsLocationProvider(  910): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  910): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  910): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  910): acquireWL(4262cc28): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/PMS     (  910): releaseWL(41c8aba0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/libc    (  910): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-,err=8
D/libc    (  910): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  910): [NET] getaddrinfo-, 1
,D/libc    (  910): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =23ef +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE,
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59,
D/libc    (  364): [NET]res_nsend:resplen=243
D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo_proxy-, success
I/global  (  910): call createSocket() return a new socket.
D/libc    (  910): [NET] getaddrinfo+,hn 14(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  910): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  910): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  910): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  910):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  910): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  910): releaseWL(4262cc28): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/Process (  910): killProcessQuiet, pid=3913
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 3913:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 3
,I/ActivityManager(  910): Recipient 3913
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{43b86ef0 u0 com.htc.htclocationservice/.AutoSettingService}
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1519): service - handleMessage() stop self
,D/AutoSetting( 1519): service - onDestroy() END
,D/AutoSetting( 1519): service - handleMessage() quit looper
,D/Process (  910): killProcessQuiet, pid=4270
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4270:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4270
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  910): acquireWL(437905f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42228ec0: PendingIntentRecord{41fa2958 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=173801, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(437905f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/TelephonyReceiver( 1245): switchBindHtcMsgCursor: null
,D/PMS     (  910): acquireWL(42608a00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42608a00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(439b0188): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10026}
,V/AlarmManager(  910): sending alarm PendingIntent{43735498: PendingIntentRecord{4399da78 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=229860, Int=0
,I/ActivityManager(  910): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4691 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  910): sending alarm PendingIntent{42554b80: PendingIntentRecord{4251ced0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1450655626952, Int=10800000
,D/PMS     (  910): releaseWL(439b0188): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.aurora (4691/10047)
,I/ActivityManager(  910): Killing 4342:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  910): killProcessQuiet, pid=4342
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  910): Recipient 4342
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2228/10028)
,D/PMS     (  910): acquireWL(43c3d460): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10026}
,V/AlarmManager(  910): sending alarm PendingIntent{4251f8b0: PendingIntentRecord{4399da78 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=232370, Int=0
,D/PMS     (  910): releaseWL(43c3d460): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  910): acquireWL(436f37b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42228ec0: PendingIntentRecord{41fa2958 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=233801, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(436f37b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  910): acquireWL(440a7938): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(440a7938): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  910): acquireWL(4308e5a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4308e5a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): closing low battery warning: level=100
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  910): acquireWL(426137d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42228ec0: PendingIntentRecord{41fa2958 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=293801, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(426137d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(43053e28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43053e28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  910): acquireWL(4246acd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42228ec0: PendingIntentRecord{41fa2958 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=353801, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(4246acd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1368): GoogleAccountDataService.getToken()
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1368): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1368): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1574): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1574): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,W/GLSActivity( 1368): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1368): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1368): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1368): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1368): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1368): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1368): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1368): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41f070e8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/PlayEventLogger( 4110): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4110): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4110): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4110): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4110): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4110): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4110): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4110): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews.Performance( 1116): com.google.android.gms 2 13 3 12
,D/libc    ( 4110): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4110): [NET] getaddrinfo-,err=8
D/libc    ( 4110): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4110): [NET] getaddrinfo-, 1
,D/libc    ( 4110): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =83fd +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE,
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 90
D/libc    (  364): [NET]res_nsend:resplen=87
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4110): [NET] getaddrinfo_proxy-, success
I/global  ( 4110): call createSocket() return a new socket.
D/libc    ( 4110): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4110): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4110): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4110): [NET] getaddrinfo-,err=8
,D/PMS     (  910): acquireWL(43ba3e10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43ba3e10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 4
,D/Process ( 4393): killProcess, pid=4393
,D/Process ( 4393): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/InputMethodManagerService(  910): Disable input method client, pid=4393
,W/InputDispatcher(  910): channel '423c2ee8 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  910): channel '423c2ee8 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
I/ActivityManager(  910): Recipient 4393
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  910): Client connection lost with reason: 4
,W/InputDispatcher(  910): Attempted to unregister already unregistered input channel '423c2ee8 com.test.thalitest.MainActivity (s)'
I/WindowState(  910): WIN DEATH: Window{423c2ee8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager(  910): Process com.test.thalitest (pid 4393) has died.
,I/WindowManager(  910): WINDOW DIED Window{423c2ee8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/PMS     (  910): acquireWL(43513a78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10026}
,V/AlarmManager(  910): sending alarm PendingIntent{43b33ed8: PendingIntentRecord{440c6210 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=412225, Int=300000
,D/PMS     (  910): releaseWL(43513a78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  910): acquireWL(439a6610): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42228ec0: PendingIntentRecord{41fa2958 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=413801, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(439a6610): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(4402b3e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4402b3e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(4261c378): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
D/UsbnetService(  910): BroadcastReceiver::onReceive+
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PMS     (  910): releaseWL(4261c378): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  910): acquireWL(425d3e60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42228ec0: PendingIntentRecord{41fa2958 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=473802, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(425d3e60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  910): acquireWL(4328ff08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4328ff08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  910): acquireWL(44062198): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(44062198): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  910): acquireWL(439081d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42228ec0: PendingIntentRecord{41fa2958 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=533801, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(439081d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  407): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(4369b438): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4369b438): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(440e6470): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42228ec0: PendingIntentRecord{41fa2958 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=593801, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false),
,D/PMS     (  910): releaseWL(440e6470): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000},
,D/PMS     (  910): acquireWL(43c48680): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43c48680): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  350): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1245): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1245): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1245): sku_id=99
D/ContactMessageStore( 1245): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1245): start background delete task...
D/ContactMessageStore( 1245): size: 0 , 0
,D/ContactMessageStore( 1245): Background delete complete
,D/PMS     (  910): acquireWL(425ad528): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42228ec0: PendingIntentRecord{41fa2958 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=653802, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(425ad528): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(440e8758): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(440e8758): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(4369b540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): releaseWL(4369b540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(4369bc48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10026}
,V/AlarmManager(  910): sending alarm PendingIntent{43b33ed8: PendingIntentRecord{440c6210 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=712225, Int=300000
,D/PMS     (  910): releaseWL(4369bc48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  910): acquireWL(4368a7c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42228ec0: PendingIntentRecord{41fa2958 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=713801, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(4368a7c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(434f95b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PowerUI ( 1116): closing low battery warning: level=100
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): releaseWL(434f95b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(44034e68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42228ec0: PendingIntentRecord{41fa2958 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=773801, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(44034e68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42d01840): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,D/ConnectivityService(  910): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  910): sending alarm PendingIntent{41e08458: PendingIntentRecord{4245e3f0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=786278, Int=0
,D/PMS     (  910): releaseWL(42d01840): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  910): Done.
,D/ConnectivityService(  910): Setting timer for 720seconds
,D/PMS     (  910): acquireWL(42d22ed8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): releaseWL(42d22ed8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1116): closing low battery warning: level=100
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43bef248): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43bef248): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43e37968): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,I/BatteryService(  910): n_update end
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): releaseWL(43e37968): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,W/ContextImpl( 4643): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,D/TetherSettings( 4171): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4171): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4171): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4171): Cust_ConnectToPC   : spcsc>false
D/        ( 4171): Cust_ConnectToPC   : IPT>true
,D/        ( 4171): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4171): project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4171): Index of the first 1 = 3
W/Settings( 4171): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4171): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4171): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4171): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 4171): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,W/ContextImpl( 4171): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
D/SmartNS_Utility( 4171): [ACC]android_networking:tethering_guard_support=false
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(431dbbf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42228ec0: PendingIntentRecord{41fa2958 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=833801, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(431dbbf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(436fd9f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(436fd9f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(44036df8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): releaseWL(44036df8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(4294a658): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42228ec0: PendingIntentRecord{41fa2958 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=893801, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(4294a658): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(44115908): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(44115908): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,D/PowerUI ( 1116): closing low battery warning: level=100
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(44079b58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(44079b58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(432a2fa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42228ec0: PendingIntentRecord{41fa2958 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=953801, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(432a2fa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(44093538): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(44093538): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43b4ff68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43b4ff68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(4369d930): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42461d00: PendingIntentRecord{41f31c68 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450656347298, Int=900000
,V/AlarmManager(  910): sending alarm PendingIntent{42356a08: PendingIntentRecord{4369d788 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450656418851, Int=0
,W/ContextImpl( 4643): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4643): call getInstance()
,D/SmartSyncUtils( 4643): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4643): MY_DEBUG = false
D/PMS     (  910): acquireWL(440a4d10): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4643 1000 null
D/PMS     (  910): releaseWL(4369d930): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 4643): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4643): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4643): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4643): SettingOnTime = 1450677600000, randomSettingOnTime = 1450674022000
,D/SmartSyncScreenOnOffTimeReceiver( 4643): SettingOffTime = 1450742400000, randomSettingOffTime = 1450743144000
,D/SmartSyncScreenOnOffTimeReceiver( 4643): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4643): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4643): bNightModeTurnOffOnce = false
D/PMS     (  910): acquireWL(429de2f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
V/AlarmManager(  910): sending alarm PendingIntent{423a2dc8: PendingIntentRecord{4407c3b8 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_OFF_NETWORK_BY_CHECK, t=0, cnt=1, w=1450656418911, Int=0
,D/PMS     (  910): releaseWL(440a4d10): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl( 4643): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,D/SmartSyncUtils( 4643): getMobilePolicyEnabled, result = true
,D/SmartSyncDataLinkTurnOffService( 4643): turnOffMobile bPolicyEnabled = true
,D/WifiStateMachine(  910): WiFiDisplay: getWifidisplayApEnabled=false
,D/SmartSyncUtils( 4643): isWifiHotSpotEnabled = false
,D/SmartSyncDataLinkTurnOffService( 4643): turnOffMobile bCheckMobileData = false
,D/LocationManagerService(  910): getProviders()=[gps, network]
,D/LocationManagerService(  910): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
,D/PMS     (  910): releaseWL(429de2f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/LocationManagerService(  910): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/SmartSyncDataLinkTurnOffService( 4643): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
D/SmartSyncUtils( 4643): isCharging status = 5
D/SmartSyncDataLinkTurnOffService( 4643): turnOffWifi ui setting = true
D/WifiStateMachine(  910): WiFiDisplay: getWifidisplayApEnabled=false
D/SmartSyncUtils( 4643): isWifiHotSpotEnabled = false
,D/SmartSyncUtils( 4643): isWifiCallingOn, bOn = false
,D/SmartSyncDataLinkTurnOffService( 4643): turnOffWifi bCheckWifiData = true
,D/SmartSyncDataLinkTurnOffService( 4643): turnOffWifi bWifiConnected = true
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.htcpowermanager (4643/1000)
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,D/PMS     (  910): acquireWL(440c05f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42228ec0: PendingIntentRecord{41fa2958 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1013801, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(440c05f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(440b80c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(440b80c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(44052510): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/UsbnetService(  910): onReceive BATTERY_CHANGED
,I/BatteryService(  910): n_update end
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): releaseWL(44052510): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/PowerUI ( 1116): closing low battery warning: level=100
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43fe5930): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42228ec0: PendingIntentRecord{41fa2958 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1073801, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43fe5930): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43fe10e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43fe10e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43b7d4f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42228ec0: PendingIntentRecord{41fa2958 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1133801, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43b7d4f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(437ec158): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/BatteryService(  910): n_update end
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): releaseWL(437ec158): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(42380150): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  910): updateBatteryInfo
,D/PMS     (  910): releaseWL(42380150): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(41e70030): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{4235d4c8: PendingIntentRecord{426657b0 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_OFF_WIFI_RETRY, t=0, cnt=1, w=1450656598985, Int=0
,W/ContextImpl( 4643): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  910): releaseWL(41e70030): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/SmartSyncDataLinkTurnOffService( 4643): turnOffWifi ui setting = true
,D/WifiStateMachine(  910): WiFiDisplay: getWifidisplayApEnabled=false
D/SmartSyncUtils( 4643): isWifiHotSpotEnabled = false
,D/SmartSyncUtils( 4643): isWifiCallingOn, bOn = false
,D/SmartSyncDataLinkTurnOffService( 4643): turnOffWifi bCheckWifiData = false
,D/SmartSyncDataLinkTurnOffService( 4643): turnOffWifi bWifiConnected = true
D/LocationManagerService(  910): getProviders()=[gps, network]
,D/LocationManagerService(  910): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
,D/LocationManagerService(  910): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.htcpowermanager (4643/1000)
,D/SmartSyncDataLinkTurnOffService( 4643): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
D/SmartSyncUtils( 4643): isCharging status = 5
,D/PMS     (  910): acquireWL(41ee4b88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42228ec0: PendingIntentRecord{41fa2958 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1193801, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(41ee4b88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(41c06948): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(41c06948): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
,I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  350): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  910): acquireWL(41c4e530): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(41c4e530): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(42291390): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42228ec0: PendingIntentRecord{41fa2958 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1253801, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42291390): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43712ed0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43712ed0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
,D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(42611b70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): releaseWL(42611b70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(425a8be0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42228ec0: PendingIntentRecord{41fa2958 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1313802, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(425a8be0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(41e192a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
I/BatteryService(  910): n_update end
D/PowerUI ( 1116): closing low battery warning: level=100
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PMS     (  910): releaseWL(41e192a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(425cd478): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(425cd478): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(42663ac8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42228ec0: PendingIntentRecord{41fa2958 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1373801, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42663ac8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(424652f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): releaseWL(424652f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
,D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
,D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  910): >> updateStatus
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(42575cd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
I/BatteryService(  910): n_update end
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): releaseWL(42575cd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(42665f90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42228ec0: PendingIntentRecord{41fa2958 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1433801, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42665f90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42550140): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42550140): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(424780c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): releaseWL(424780c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(42362668): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42228ec0: PendingIntentRecord{41fa2958 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1493801, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42362668): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42686798): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42686798): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
,D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(42584790): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42584790): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(425f1b78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42228ec0: PendingIntentRecord{41fa2958 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1553802, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(425f1b78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43650310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43650310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(424ffdb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): releaseWL(424ffdb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(4371cc80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  910): sending alarm PendingIntent{42228ec0: PendingIntentRecord{41fa2958 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1613801, Int=0
,D/PMS     (  910): releaseWL(4371cc80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42369758): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42369758): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(426abe70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(426abe70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(4255b7d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42228ec0: PendingIntentRecord{41fa2958 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1673801, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(4255b7d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43fc5ca0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43fc5ca0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(4371f6b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4371f6b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(425f64c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42228ec0: PendingIntentRecord{41fa2958 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1733802, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(425f64c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(4330bf70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4330bf70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(44078040): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(44078040): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(42655280): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42228ec0: PendingIntentRecord{41fa2958 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1793801, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42655280): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,D/PMS     (  910): acquireWL(42592cf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): releaseWL(42592cf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  350): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  910): acquireWL(423a5eb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(423a5eb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/ConnectivityService(  910): Sampling interval elapsed, updating statistics ..
,D/PMS     (  910): acquireWL(438108c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{41e08458: PendingIntentRecord{4245e3f0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1506301, Int=0
,D/ConnectivityService(  910): Done.
,D/ConnectivityService(  910): Setting timer for 720seconds
,I/ProcessStatsService(  910): Prepared write state in 37ms
,V/AlarmManager(  910): sending alarm PendingIntent{41bf61f8: PendingIntentRecord{423b5260 android broadcastIntent}}, i=com.htc.intent.action.UBLS_REGULAR_ALARM_INEXACT, t=3, cnt=1, w=1651176, Int=0
V/AlarmManager(  910): sending alarm PendingIntent{4236a680: PendingIntentRecord{42521d50 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1821252, Int=1800000
,V/AlarmManager(  910): sending alarm PendingIntent{436f80d8: PendingIntentRecord{426335f0 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450656564109, Int=1800000
V/AlarmManager(  910): sending alarm PendingIntent{434eb518: PendingIntentRecord{434fa368 com.htc.task broadcastIntent}}, i=com.htc.task.statistics, t=1, cnt=1, w=1450657057446, Int=0
,V/AlarmManager(  910): sending alarm PendingIntent{42461d00: PendingIntentRecord{41f31c68 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450657247298, Int=900000
,I/ProcessStatsService(  910): Pruning old procstats: /data/system/procstats/state-2015-12-20-03-39-37.bin
,I/ProcessStatsService(  910): Prepared write state in 20ms
,D/PMS     (  910): acquireWL(44087e10): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
,D/PMS     (  910): acquireWL(42654978): PARTIAL_WAKE_LOCK  HtcDeviceInfoWakeLock_5 0x1 910 1000 null
,D/PMS     (  910): releaseWL(44087e10): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/PMS     (  910): acquireWL(43291d50): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2228 10028 null
,D/PMS     (  910): releaseWL(42654978): PARTIAL_WAKE_LOCK  HtcDeviceInfoWakeLock_5 0x1 null
,D/PMS     (  910): acquireWL(42d22fd8): PARTIAL_WAKE_LOCK  HtcDeviceInfoWakeLock_5 0x1 910 1000 null
D/PMS     (  910): acquireWL(43462178): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2228 10028 null
,I/EventLogService( 2228): Aggregate from 1450655517211 (log), 1450654764052 (data)
D/PMS     (  910): releaseWL(43291d50): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
D/PMS     (  910): releaseWL(42d22fd8): PARTIAL_WAKE_LOCK  HtcDeviceInfoWakeLock_5 0x1 null
,I/ActivityManager(  910): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=4763 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.htc.server.ulog.EventLogStore.upload:130 com.htc.server.ulog.EventLogStore.onAlarmArrival:220 com.htc.server.ulog.AlarmScheduler$SchedulerBase$CallbackRunnable.run:155 android.os.Handler.handleCallback:733 
,D/PMS     (  910): releaseWL(43462178): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,W/ContextImpl( 4643): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  910): releaseWL(438108c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,I/ActivityManager(  910): Start proc com.htc.reportagent for broadcast com.htc.reportagent/.receiver.ReportAgentReceiver: pid=4778 uid=10065 gids={50065, 3003, 5012, 1007, 1028, 1015}
,I/MyReportAgent( 4778): ReportAgentReceiver [onReceive] com.htc.intent.action.USER_PROFILING
,D/MyReportAgent( 4778): com.htc.intent.action.USER_PROFILING
,D/MyReportAgent( 4778): ReportService [##] onCreate(), this = com.htc.reportagent.ReportService@41b2e480
D/MyReportAgent( 4778): ReportService [##] onStartCommand(), flags = 0, startId = 1, intent = Intent { act=com.htc.intent.action.USER_PROFILING flg=0x10 cmp=com.htc.reportagent/.ReportService (has extras) }, this = com.htc.reportagent.ReportService@41b2e480
,D/MyReportAgent( 4778): ReportServiceHandler.onHandleIntent() intent is com.htc.intent.action.USER_PROFILING
W/BatSI   (  910): Couldn't get kernel wake lock stats
,D/UPolicy ( 4778): IUserBehaviorLoggingService reference is gotten !
,D/MyReportAgent( 4778): ReportUploader [onUpload] tag: HTC_ULOGDATA, time: 1450657247398 
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,D/LocationManagerService(  910): getProviders()=[]
,D/LocationManagerService(  910): getProviders()=[passive]
,D/LocationManagerService(  910): getBestProvider(Criteria[power=NO_REQ acc=---], true)=passive
,D/LocationManagerService(  910): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  910): getProviders()=[]
D/LocationManagerService(  910): getProviders()=[passive]
,D/LocationManagerService(  910): getBestProvider(Criteria[power=NO_REQ acc=---], true)=passive
,D/LocationManagerService(  910): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/HandsetLogCreator( 4778): envelope SN: 115
,D/MyReportAgent( 4778): ReportUploader file size: 1370
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.reportagent (4778/10065)
V/MyReportAgent( 4778): Utils getType(): 1, getSubtype: 0
,D/MyReportAgent( 4778): Utils isNetworkAllowed: true, isUSBNETTypeAccepted: true, isTypeWifiAccepted: true, isType2GAccepted: false, isTypeOthersAccepted: false, isUSBNETAllowed: false, isWifiAllowed: true, is2GAllowed: false, isOthersAllowed: false
D/ConnectivityService(  910): getNetworkInfo networkType=0 called by com.htc.reportagent (4778/10065)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.reportagent (4778/10065)
D/ConnectivityService(  910): getNetworkInfo networkType=55 called by com.htc.reportagent (4778/10065)
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,D/Wakelock4Data( 4778): logPomeloSender_133.1KB to transmit,reason=send log to server.
V/MyReportAgent( 4778): Utils getType(): 1, getSubtype: 0
D/MyReportAgent( 4778): Utils isNetworkAllowed: true, isUSBNETTypeAccepted: true, isTypeWifiAccepted: true, isType2GAccepted: false, isTypeOthersAccepted: false, isUSBNETAllowed: false, isWifiAllowed: true, is2GAllowed: false, isOthersAllowed: false
,D/MyReportAgent( 4778): ReportUploader Uploaded file size: 1370
,D/Pomelo  ( 4778): LogLib params context = android.app.Application@41b29028	isDebug = false	isEngineerROM = false
D/PomeloConfig( 4778): LogLibStore has VERSIONKEY.
,D/PomeloConfig( 4778): LogLibStore version is 1.3
D/PMS     (  910): acquireWL(440e2e80): PARTIAL_WAKE_LOCK  logPomeloSender_133 0x1 4778 10065 null
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.reportagent (4778/10065)
D/PomeloConfig( 4778): loadFromPreference(), LogServer = https://pomelo.htcsense.com:443
D/PomeloConfig( 4778): loadFromPreference(), PolicyServer = https://policylog.htcsense.com:443
D/PomeloConfig( 4778): loadFromPreference(), RefreshInterval = 604800
D/Pomelo  ( 4778): sendLogEnvelope envelope valid
D/Pomelo  ( 4778): inBytes=[1370]
D/Pomelo  ( 4778): outBytes.length=[714]
,D/libc    ( 4778): [NET] getaddrinfo+,hn 19(0x706f6d656c6f2e),sn(),family 0,flags 4
D/libc    ( 4778): [NET] getaddrinfo-,err=8
D/libc    ( 4778): [NET] getaddrinfo+,hn 19(0x706f6d656c6f2e),sn(),family 0,flags 1024
D/libc    ( 4778): [NET] getaddrinfo-, 1
,D/libc    ( 4778): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706f6d656c6f2e),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =c0bb +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/Process (  910): killProcessQuiet, pid=4356
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4356:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4356
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 2655
D/libc    (  364): [NET]res_nsend:resplen=184
D/libc    (  364): [NET]res_queryN: exit 3, ancount=6
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4778): [NET] getaddrinfo_proxy-, success
I/global  ( 4778): call createSocket() return a new socket.
D/libc    ( 4778): [NET] getaddrinfo+,hn 15(0x3133302e323131),sn(),family 0,flags 4
,D/libc    ( 4778): [NET] getaddrinfo-, SUCCESS,
,I/MyReportAgent( 4778): CSUploader returned value : 200 , TAG:HTC_ULOGDATA
D/ConnectivityService(  910): getNetworkInfo networkType=0 called by com.htc.reportagent (4778/10065)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.reportagent (4778/10065)
D/ConnectivityService(  910): getNetworkInfo networkType=55 called by com.htc.reportagent (4778/10065)
,D/PMS     (  910): releaseWL(440e2e80): PARTIAL_WAKE_LOCK  logPomeloSender_133 0x1 null
,V/MyReportAgent( 4778): Utils getType(): 1, getSubtype: 0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.reportagent (4778/10065)
D/MyReportAgent( 4778): Utils isNetworkAllowed: true, isUSBNETTypeAccepted: true, isTypeWifiAccepted: true, isType2GAccepted: false, isTypeOthersAccepted: false, isUSBNETAllowed: false, isWifiAllowed: true, is2GAllowed: false, isOthersAllowed: false
,D/MyReportAgent( 4778): ReportUploader Start upload resuming queue files. file count: 56
,D/MyReportAgent( 4778): ReportUploader resume file: 0000014ff6b9608e-HTC_ULOGDATA-USAGE-36bc5585-d263-4808-9e6c-c3332f52dfd5
,D/ConnectivityService(  910): getNetworkInfo networkType=0 called by com.htc.reportagent (4778/10065)
,D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.reportagent (4778/10065)
,D/ConnectivityService(  910): getNetworkInfo networkType=55 called by com.htc.reportagent (4778/10065)
,D/Pomelo  ( 4778): LogLib params context = android.app.Application@41b29028	isDebug = false	isEngineerROM = false
D/PomeloConfig( 4778): LogLibStore has VERSIONKEY.
,D/PomeloConfig( 4778): LogLibStore version is 1.3
D/PomeloConfig( 4778): loadFromPreference(), LogServer = https://pomelo.htcsense.com:443
D/PomeloConfig( 4778): loadFromPreference(), PolicyServer = https://policylog.htcsense.com:443
,D/PomeloConfig( 4778): loadFromPreference(), RefreshInterval = 604800
,D/Pomelo  ( 4778): sendLogEnvelope envelope valid
,D/Pomelo  ( 4778): inBytes=[767704]
,D/Pomelo  ( 4778): outBytes.length=[21029]
D/libc    ( 4778): [NET] getaddrinfo+,hn 19(0x706f6d656c6f2e),sn(),family 0,flags 4
D/libc    ( 4778): [NET] getaddrinfo-,err=8
D/libc    ( 4778): [NET] getaddrinfo+,hn 19(0x706f6d656c6f2e),sn(),family 0,flags 1024
D/libc    ( 4778): [NET] getaddrinfo-, 1
D/libc    ( 4778): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706f6d656c6f2e),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =2c67 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=6
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4778): [NET] getaddrinfo_proxy-, success
I/global  ( 4778): call createSocket() return a new socket.
D/libc    ( 4778): [NET] getaddrinfo+,hn 15(0x3133302e323131),sn(),family 0,flags 4
,D/libc    ( 4778): [NET] getaddrinfo-, SUCCESS,
,I/MyReportAgent( 4778): CSUploader returned value : 503 , TAG:HTC_ULOGDATA
D/ConnectivityService(  910): getNetworkInfo networkType=0 called by com.htc.reportagent (4778/10065)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.reportagent (4778/10065)
D/ConnectivityService(  910): getNetworkInfo networkType=55 called by com.htc.reportagent (4778/10065)
,D/MyReportAgent( 4778): break resuming queue files
,V/MyReportAgent( 4778): ReportServiceHandler register the PowerConnected Listener
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.htc.reportagent, clsName=com.htc.reportagent.receiver.PowerConnectedReceiver, state=1, flag=1, pid=4778, uid=10065, userID:0
,D/PMS     (  910): acquireWL(4407eaa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42228ec0: PendingIntentRecord{41fa2958 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1853801, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(4407eaa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/MyReportAgent( 4778): ReportService [##] onDestroy(), this =com.htc.reportagent.ReportService@41b2e480
,D/Process (  910): killProcessQuiet, pid=4110
,I/ActivityManager(  910): Killing 4110:com.android.vending/u0a73 (adj 15): empty #17
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  910): Recipient 4110
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  910): acquireWL(44071cb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(44071cb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,D/HtcPowerSaver(  910): updateBatteryInfo
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1574): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1574): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,W/AppWidgetServiceImpl(  910): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4799): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4799): ====startRecUseTime====
D/htc.customization.log.level( 4799):  is 
W/CustomizationLogLevel( 4799): Level value is invalid, use default level 2
D/CustomizationManager( 4799):  Read ACC file spent 0.122 (s)
D/CIDMapFileReader( 4799): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4799): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4799): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4799): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4799): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4799): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4799): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4799): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4799): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4799): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4799): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4799): Parsing tag category name = system
I/CustomizationCIDLoader( 4799): Parsing tag category name = application
I/CustomizationCIDLoader( 4799): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4799): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4799): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4799): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4799): Parsing tag category name = Settings
D/CustomizationManager( 4799):  Read CID file spent 0.176 (s)
D/CustomizationManager( 4799):  All configurations done spent 0.176 (s)
W/HtcNativeFlag( 4799): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4799): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4799): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4799): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  910): deletePackageAsUser: pkg=com.test.thalitest, pid=4799, uid=2000 user=0
D/Process (  910): killProcessQuiet, pid=1422
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  910): killProcessQuiet, pid=4148
I/ActivityManager(  910): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
I/ActivityManager(  910): Killing 1422:com.htc.sense.hsp/u0a53 (adj 15): empty for 1801s
I/ActivityManager(  910): Killing 4148:com.google.android.apps.plus/u0a160 (adj 15): empty for 1801s
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  910): killProcessQuiet, pid=4525
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  910): killProcessQuiet, pid=4508
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  910): killProcessQuiet, pid=4492
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  910): Killing 4525:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1801s
I/ActivityManager(  910): Killing 4508:com.android.chrome/u0a96 (adj 15): empty for 1801s
I/ActivityManager(  910): Killing 4492:com.google.android.setupwizard/u0a78 (adj 15): empty for 1801s
D/Process (  910): killProcessQuiet, pid=3860
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  910): killProcessQuiet, pid=4441
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  910): Killing 3860:com.google.android.music:main/u0a154 (adj 15): empty for 1801s
I/ActivityManager(  910): Killing 4441:com.htc.mms.backupagent/u0a77 (adj 15): empty for 1809s
I/ActivityManager(  910): Recipient 4148
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Recipient 4492
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Recipient 1422
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Recipient 4525
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Recipient 4508
I/ActivityManager(  910): Recipient 4441
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/PackageSettings(  910): Skipping PackageSetting{422fa850 com.example.hello/10356} due to missing metadata
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Recipient 3860
D/MediaRouterService(  910): Client com.google.android.music (pid 3860): Died!
D/PMS     (  910): acquireWL(42463f70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
I/ActivityManager(  910): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
V/AlarmManager(  910): sending alarm PendingIntent{42228ec0: PendingIntentRecord{41fa2958 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1913801, Int=0
I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
D/DotMatrix( 1574): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1574): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1574): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/acms    ( 1901): Unregistering com.test.thalitest
E/acms    ( 1901): Could not unregister removed application com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver replacing:false
D/PMS     (  910): acquireWL(425f68b0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1471 10028 null
W/GeofencerStateMachine( 1471): Ignoring removeGeofence because network location is disabled.
D/PMS     (  910): releaseWL(425f68b0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "sms"
W/AccTypeManager( 1332): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1332): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
D/VoicemailCleanupService( 1297): Cleaning up data for package: com.test.thalitest
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
W/SystemReader( 1256): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mms"
I/Launcher( 1272): Deferring update until onResume
D/Launcher( 1272): waitUntilResume // bindAppsRemoved
D/AccTypeManager( 1332): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "sms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
D/PackageBroadcastService( 2228): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
E/ExternalAccountType( 1332): Unsupported attribute readOnly
I/ActivityManager(  910): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4813 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/InputMethodManagerService(  910): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
D/PhoneApp( 1245): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  910): Delaying start of: ServiceRecord{43c5a138 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PeopleContactsSync( 2228): CP2 sync disabled
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2228, uid=10028, userID:0
D/PMS     (  910): acquireWL(43fa1130): PARTIAL_WAKE_LOCK  Icing 0x1 2228 10028 null
I/Icing   ( 2228): doRemovePackageData com.test.thalitest
I/MultiDex( 4813): install
I/MultiDex( 4813): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4813): loading existing secondary dex files
I/MultiDex( 4813): load found 1 secondary dex files
D/PMS     (  910): releaseWL(43fa1130): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/MultiDex( 4813): install done
I/ActivityManager(  910): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4830 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/ProviderInstaller( 4813): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  910): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4830): install
I/MultiDex( 4830): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4830): loading existing secondary dex files
I/MultiDex( 4830): load found 1 secondary dex files
I/MultiDex( 4830): install done
I/ProviderInstaller( 4830): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  910): Resuming delayed broadcast
I/ActivityManager(  910): Start proc com.htc.sense.hsp for broadcast com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver: pid=4848 uid=10053 gids={50053, 1023, 3003, 5012}
W/FileUtils( 1210): Failed to chmod(/data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml): libcore.io.ErrnoException: chmod failed: EROFS (Read-only file system)
E/SQLiteDatabase( 4813): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4813): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4813): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4813): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4813): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4813): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4813): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4813): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4813): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4813): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4813): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4813): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4813): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4813): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4813): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4813): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4813): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4813): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4813): threadid=12: thread exiting with uncaught exception (group=0x416f1e30)
E/AndroidRuntime( 4813): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4813): Process: com.google.android.gms.drive, PID: 4813
E/AndroidRuntime( 4813): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4813): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4813): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4813): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4813): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4813): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4813): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4813): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4813): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4813): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4813): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4813): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4813): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4813): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4813): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4813): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4813): 	at ctn.run(SourceFile:985)
E/ActivityManager(  910): App crashed! Process: com.google.android.gms.drive
D/Process ( 4813): killProcess, pid=4813
D/Process ( 4813): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  910): Can't write: system_app_crash
E/DropBoxManagerService(  910): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  910): Recipient 4813
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Process com.google.android.gms.drive (pid 4813) has died.
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
D/PluginProvider( 4848): PluginProvider onCreate
E/SQLiteDatabase( 4848): Failed to open database '/data/data/com.htc.sense.hsp/databases/registry.db'.
E/SQLiteDatabase( 4848): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4848): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4848): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4848): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.onCreate(Unknown Source)
E/SQLiteDatabase( 4848): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1609)
E/SQLiteDatabase( 4848): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1574)
E/SQLiteDatabase( 4848): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5394)
E/SQLiteDatabase( 4848): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4965)
E/SQLiteDatabase( 4848): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4902)
E/SQLiteDatabase( 4848): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4848): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4848): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4848): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4848): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4848): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4848): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4848): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4848): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4848): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4848): Couldn't open registry.db for writing (will try read-only):
E/SQLiteOpenHelper( 4848): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4848): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4848): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4848): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4848): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4848): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4848): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4848): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4848): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4848): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4848): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4848): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4848): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4848): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4848): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.onCreate(Unknown Source)
E/SQLiteOpenHelper( 4848): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1609)
E/SQLiteOpenHelper( 4848): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1574)
E/SQLiteOpenHelper( 4848): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5394)
E/SQLiteOpenHelper( 4848): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4965)
E/SQLiteOpenHelper( 4848): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4902)
E/SQLiteOpenHelper( 4848): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4848): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4848): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4848): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4848): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4848): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4848): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4848): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4848): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4848): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4848): Opened registry.db in read-only mode
D/PluginProvider( 4848): current plugin count: 19
D/HtcAppUPService( 4848): HtcUPDataProvider onCreate()
I/[PluginManager]RegisterService( 4848): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
W/[PluginManager]RegisterService( 4848): provider may killed!
W/[PluginManager]RegisterService( 4848): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/[PluginManager]RegisterService( 4848): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/[PluginManager]RegisterService( 4848): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/[PluginManager]RegisterService( 4848): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/[PluginManager]RegisterService( 4848): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/[PluginManager]RegisterService( 4848): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
W/[PluginManager]RegisterService( 4848): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:818)
W/[PluginManager]RegisterService( 4848): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:213)
W/[PluginManager]RegisterService( 4848): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/[PluginManager]RegisterService( 4848): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
W/[PluginManager]RegisterService( 4848): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/[PluginManager]RegisterService( 4848): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
W/[PluginManager]RegisterService( 4848): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 4848): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 4848): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 4848): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 4848): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/PackageManager(  910): Unable to load service info ResolveInfo{41deeed8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
I/[PluginManager]RegisterService( 4848): handle notify Blinkfeed plugin client changed
I/ActivityManager(  910): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4865 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4865, uid=10073, userID:0
D/Finsky  ( 4865): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  910): getAllNetworkInfo called by com.android.vending (4865/10073)
D/ConnectivityService(  910): getAllNetworkInfo called by com.android.vending (4865/10073)
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1272): loadItems() com.htc.launcher.pageview.WidgetManager@41bb6d30 +
I/Prism.WidgetManager( 1272): onLoadItems() +
D/Finsky  ( 4865): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
D/RemoteDisplayProvider(  910): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  910): start
D/PMS     (  910): releaseWL(42463f70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
W/Settings( 4865): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 4865): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SQLiteDatabase( 4865): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 4865): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4865): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4865): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4865): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4865): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/SQLiteDatabase( 4865): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/SQLiteDatabase( 4865): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/SQLiteDatabase( 4865): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 4865): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 4865): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4865): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4865): threadid=25: thread exiting with uncaught exception (group=0x416f1e30)
E/ActivityManager(  910): App crashed! Process: com.android.vending
E/AndroidRuntime( 4865): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime( 4865): Process: com.android.vending, PID: 4865
E/AndroidRuntime( 4865): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4865): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4865): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4865): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4865): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4865): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4865): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4865): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4865): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4865): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4865): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4865): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4865): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4865): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4865): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/AndroidRuntime( 4865): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/AndroidRuntime( 4865): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/AndroidRuntime( 4865): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4865): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4865): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4865): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4865, uid=10073, userID:0
W/AtomicFile(  910): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
D/Process ( 4865): killProcess, pid=4865
D/Process ( 4865): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.finsky.FinskyApp$CrashHandler.uncaughtException:284 java.lang.ThreadGroup.uncaughtException:693 
D/Prism.PackageStateRece_( 1272): action: android.intent.action.PACKAGE_REMOVED
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
W/AppWidgetServiceImpl(  910): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
I/IcingCorporaProvider( 2887): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  910): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4898 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/SQLiteLog( 2887): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2887): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x5c9c9fd0
W/dalvikvm( 2887): threadid=14: thread exiting with uncaught exception (group=0x416f1e30)
E/ActivityManager(  910): App crashed! Process: com.google.android.googlequicksearchbox:search
D/Process ( 2887): killProcess, pid=2887
E/AndroidRuntime( 2887): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2887): Process: com.google.android.googlequicksearchbox:search, PID: 2887
E/AndroidRuntime( 2887): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2887): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2887): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2887): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2887): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2887): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2887): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2887): 	at cid.d(PG:186)
E/AndroidRuntime( 2887): 	at clo.g(PG:594)
E/AndroidRuntime( 2887): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2887): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2887): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2887): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2887): 	at clr.tL(PG:827)
E/AndroidRuntime( 2887): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2887): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2887): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2887): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2887): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2887): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  910): Recipient 4865
I/ActivityManager(  910): Process com.android.vending (pid 4865) has died.
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
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
D/Process ( 2887): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 

```
