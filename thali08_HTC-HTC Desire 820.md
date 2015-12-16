#### Test 506502783fcf234_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  906): Waited long enough for: ServiceRecord{43fdcd20 u0 com.htc.htclocationservice/.AutoSettingService}
,--------- beginning of /dev/log/main
E/cutils-trace( 4403): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4403): ====startRecUseTime====
D/htc.customization.log.level( 4403):  is 
W/CustomizationLogLevel( 4403): Level value is invalid, use default level 2
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1133): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
D/CustomizationManager( 4403):  Read ACC file spent 0.051 (s)
D/CIDMapFileReader( 4403): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4403): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4403): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4403): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4403): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4403): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4403): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4403): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4403): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4403): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4403): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4403): Parsing tag category name = system
I/CustomizationCIDLoader( 4403): Parsing tag category name = application
I/CustomizationCIDLoader( 4403): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4403): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4403): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4403): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4403): Parsing tag category name = Settings
D/CustomizationManager( 4403):  Read CID file spent 0.090 (s)
D/CustomizationManager( 4403):  All configurations done spent 0.090 (s)
W/HtcNativeFlag( 4403): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4403): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4403): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4403): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  906): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  906): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4403
D/PMS     (  906): acquireHCC(425d76b8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 906 1000 null
D/PMS     (  906): acquireHCC(425c5ff0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 906 1000 null
W/asset   (  906): Copying FileAsset 0x62b7bfb8 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  906): @test_code: getHtcIntentFlag: 0 obj: 1129945824
I/FeedHostManager( 1270): [onPause]
I/FeedProviderManager( 1270): onPause
I/SocialFeedProvider( 1270): +onPause
I/SocialFeedProvider( 1270): -onPause
D/PMS     (  906): acquireWL(425baa30): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
I/FeedHostManager( 1270): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41f55168
I/ActivityManager(  906): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4414 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1270): [trimMemory] 20
W/asset   ( 4414): Copying FileAsset 0x5c790e28 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4414): Binding Chromium to main looper Looper (main, tid 1) {41b13518}
I/LibraryLoader( 4414): Expected native library version number "",actual native library version number ""
I/chromium( 4414): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4414): Initializing chromium process, renderers=0
D/PMS     (  906): acquireWL(423f5330): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  906): acquireWL(42393ec0): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  906): releaseWL(42393ec0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
W/System.err(  906): java.lang.Throwable: stack dump
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42379a98:true
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4414): 1102221376: getState(). Returning 12
I/Adreno-EGL( 4414): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4414): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4414): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4414): Local Branch: 
I/Adreno-EGL( 4414): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4414): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4414):                  aa63bbd948f41d15fc72f585e
W/chromium( 4414): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4414): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4414): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4414): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4414): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4414): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4414): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4414): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4414): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4414): CordovaWebView is running on device made by: HTC
,W/AwContents( 4414): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  906): Disable input method client, pid=1270
,W/ResourceType( 4414): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4414): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b5a6f0, mServedView=org.apache.cordova.engine.SystemWebView{41b20358 VFEDH.C. .F....I. 0,0-720,1134 #64}
,I/InputMethodManagerService(  906): Enable input method client, pid=4414
W/XT9_C   ( 1207): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1207): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1207): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1207): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,W/AwContents( 4414): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  906): Displayed com.test.thalitest/.MainActivity: +281ms
,D/PMS     (  906): releaseWL(425baa30): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4414): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4414): JniHelper::setJavaVM(0x415e8048), pthread_self() = 1663470512
,D/JX-Cordova( 4414): jxcore cordova android initializing
,I/dalvikvm-heap( 4414): Grow heap (frag case) to 11.516MB for 64402-byte allocation
,I/dalvikvm-heap( 4414): Grow heap (frag case) to 11.623MB for 144892-byte allocation
,I/dalvikvm-heap( 4414): Grow heap (frag case) to 11.738MB for 217334-byte allocation
,I/dalvikvm-heap( 4414): Grow heap (frag case) to 11.914MB for 325996-byte allocation
,I/dalvikvm-heap( 4414): Grow heap (frag case) to 12.189MB for 488990-byte allocation
,W/PluginManager( 4414): THREAD WARNING: exec() call to JXcore.isReady blocked the main thread for 25ms. Plugin should use CordovaInterface.getThreadPool().
,I/dalvikvm-heap( 4414): Grow heap (frag case) to 12.594MB for 733480-byte allocation
,I/dalvikvm-heap( 4414): Grow heap (frag case) to 14.041MB for 1650320-byte allocation
,I/dalvikvm-heap( 4414): Grow heap (frag case) to 15.456MB for 2475476-byte allocation
,D/PMS     (  906): acquireWL(42de0218): PARTIAL_WAKE_LOCK  Icing 0x1 2227 10028 null
,D/PMS     (  906): releaseWL(42de0218): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(42437ca8): PARTIAL_WAKE_LOCK  Icing 0x1 2227 10028 null
,I/dalvikvm-heap( 4414): Grow heap (frag case) to 17.516MB for 3713210-byte allocation
D/PMS     (  906): releaseWL(42437ca8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(420d0940): PARTIAL_WAKE_LOCK  Icing 0x1 2227 10028 null
,D/PMS     (  906): releaseWL(420d0940): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(42360988): PARTIAL_WAKE_LOCK  Icing 0x1 2227 10028 null
,D/PMS     (  906): releaseWL(42360988): PARTIAL_WAKE_LOCK  Icing 0x1 null
,W/CpuWake (  906): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  906): <<release mCpuPerf_Freq wakelock
,D/PMS     (  906): releaseHCC(425d76b8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  906): releaseHCC(425c5ff0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4414): Initializing JXcore engine
,W/jxcore-log( 4414): JXcore engine is ready
,W/jxcore-log( 4414): Starting JXcore engine
,W/jxcore-log( 4414): Platform android
W/jxcore-log( 4414): 
,W/jxcore-log( 4414): Process ARCH arm
W/jxcore-log( 4414): 
,I/SensorManager(  906): mEventCount = 750
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1133): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/jxcore-log( 4414): JXcore Cordova bridge is ready!
I/jxcore-log( 4414): 
,W/jxcore-log( 4414): JXcore engine is started
,I/chromium( 4414): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/Choreographer( 4414): Skipped 140 frames!  The application may be doing too much work on its main thread.
,D/PMS     (  906): releaseWL(423f5330): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/ActivityManager(  906): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4461 uid=10077 gids={50077}
D/PMS     (  906): acquireWL(4234b788): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10077}
,V/AlarmManager(  906): sending alarm PendingIntent{41edf998: PendingIntentRecord{41b0bf18 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1450238263622, Int=60000
,D/PMS     (  906): releaseWL(4234b788): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4461): SMSBackupAgentService started
,D/SMSBackup( 4461): Checking restore status
D/SMSBackup( 4461): Restore complete
,D/SMSBackup( 4461): cancelCheckAlarm
,D/SMSBackup( 4461): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  906): killProcessQuiet, pid=3280
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3280:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3280
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/jxcore-log( 4414): Toggling radios to true
I/jxcore-log( 4414): 
,D/BluetoothAdapter( 4414): enable(): BT is already enabled..!
,D/WifiManager( 4414): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
,W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  906): Settings:Agentname: wifi_on
,W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 2
W/Settings:Agent(  906): >> traceCallingStack()
W/Settings:Agent(  906): Process.myPid(): 906
,W/Settings:Agent(  906): Process.myTid(): 1472
W/Settings:Agent(  906): Process.myUid(): 1000
W/Settings:Agent(  906): 
W/Settings:Agent(  906): 
,W/System.err(  906): java.lang.Throwable: stack dump
,W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
,W/System.err(  906): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  906): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
,W/System.err(  906): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  906): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
,W/System.err(  906): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  906): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
,W/System.err(  906): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
D/WifiService(  906): New client listening to asynchronous messages
D/WifiService(  906): setWifiEnabled: true pid=4414, uid=10348
E/WifiService(  906): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  906): isSprintWifiRestricted(): false
I/WifiService(  906): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  906): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/System.err(  906): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  906): 
W/Settings:Agent(  906): << traceCallingStack(): 6(ms)
D/WifiManager( 4414): disconnect: Base Package Name=com.test.thalitest, uid=10348
D/WifiNative-wlan0(  906): doBoolean: DISCONNECT
D/WifiManager( 4414): reconnect: Base Package Name=com.test.thalitest, uid=10348
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1133): TDLS: Tear down peers
I/wpa_supplicant( 1133): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4414): Radios toggled
I/jxcore-log( 4414): 
D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4414): Got Device Bluetooth address: 80:01:84:8A:B3:68
I/jxcore-log( 4414): 
D/PMS     (  906): acquireWL(42526c48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,I/jxcore-log( 4414): Perf Test app loaded loaded
I/jxcore-log( 4414): 
D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
,I/Choreographer( 4414): Skipped 78 frames!  The application may be doing too much work on its main thread.
D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=61 rxSum=47} preTxRxSum={txSum=60 rxSum=46}
D/WifiDataStallTracker(  906): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  906): onDataStallAlarm: tag=19189 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=19190 delay=15s
V/AlarmManager(  906): sending alarm PendingIntent{4249ac68: PendingIntentRecord{4247b558 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=104509, Int=0
D/PMS     (  906): releaseWL(42526c48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4414): check test folder
I/jxcore-log( 4414): 
,I/jxcore-log( 4414): found test : ./testFindPeers.js
I/jxcore-log( 4414): 
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1133): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1133): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1133): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
,D/HTCRequest(  906): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  906): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
,D/WifiMonitor(  906): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1133): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1133): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1133): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1133): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1133): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1133): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1133): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1133): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1133): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1133): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb827fbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1133):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1133): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1133): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1133): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1133): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1133): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1133): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1133): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1133): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1133): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1133): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1133): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1133): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1133): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1133): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1133): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1133): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1133): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1133): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1133): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1133): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1133): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1133): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1133): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1133): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1133): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1133): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1133): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1133): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1133): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1133): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1133): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1133): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1133): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1133): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1133): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1133): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1133): Wireless event: cmd=0,x8b15 len=20
D/wpa_supplicant( 1133): nl80211: Event message available
D/wpa_supplicant( 1133): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1133): nl80211: Ignore disconnect event triggered during reassociation
D/WifiNative-wlan0(  906):    returned true
D/WifiPerfLock(  906): release()
D/WifiStateMachine(  906): PerfLock released for exiting ConnectedState
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1133): Power_Mode_Type mode = 0
I/wpa_supplicant( 1133): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 61
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1133): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  906):    returned true
D/ConnectivityService(  906): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  906): acquireWL(43f78048): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 906 1000 null
D/WifiP2pService(  906): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/DhcpStateMachine(  906): [RunningState] Stop DHCP
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
I/jxcore-log( 4414): found test : ./testSendData.js
I/jxcore-log( 4414): 
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  906): doBoolean: RECONNECT
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1133): Fast associate: Old scan results
I/wpa_supplicant( 1133): wpa_supplicant_scan enter
I/wpa_supplicant( 1133): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1133): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1133): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1133): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1133): nl80211: Event message available
,D/wpa_supplicant( 1133): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): Enter handleNetworkDisconnect
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=19190 mDataStallAlarmIntent=PendingIntent{42081820: PendingIntentRecord{4247b558 android broadcastIntent}}
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1133): Power_Mode_Type mode = 0
I/wpa_supplicant( 1133): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1133): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  906):    returned true
D/UsbnetStateTracker(  906): isAvailable+-
D/UsbnetStateTracker(  906): reconnect
,D/UsbnetStateTracker(  906): isAvailable+-
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1820/10178)
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  906): default: reconnect()
D/MDST    (  906): default: setTeardownRequested(false)
D/MDST    (  906): default: setEnableApn apnType =default , enable=true
,D/WISPrService( 4177): >>>>>WISPrService start isConnected = false<<<<<,
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  906): Exit handleNetworkDisconnect
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  906): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  906): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiService(  906): New client listening to asynchronous messages
,D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4177): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  906): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1820/10178)
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): handleConnectivityChange: resetting
,D/ConnectivityService(  906): resetConnections(wlan0, 3)
D/WISPrService( 4177): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 4177): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  364): [NET] entry_id:5   entry:0xb764a8e0  removed 
D/libc    (  364): [NET] entry_id:6   entry:0xb764b000  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb764efd8  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb764f108  removed 
D/libc    (  364): [NET] entry_id:7   entry:0xb764b1a8  removed 
D/libc    (  364): [NET] entry_id:3   entry:0xb764f2e0  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb764f410  removed 
D/libc    (  364): [NET] entry_id:8   entry:0xb764b328  removed 
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
D/PMS     (  906): acquireWL(4262f9c0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1367 10028 null
D/ConnectivityService(  906): flush DNS cache for net 1(wlan0)
D/PMS     (  906): acquireWL(44079018): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10028 null
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:1
D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  906): acquireWL(421c8f70): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): releaseWL(44079018): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  906): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  906): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1367/10028)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,D/WifiStateMachine(  906): startScan Pid: 906 Uid 1000
D/WifiNative-wlan0(  906): doBoolean: SCAN
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1133): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
D/PMS     (  906): releaseWL(421c8f70): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  906): reportInetCondition for net -1, percentage: 0 by  (1367/10028)
D/BatSI   (  906): WIFI scan started for: 650a0300 uid:1000
,D/PMS     (  906): releaseWL(4262f9c0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  906):    returned false
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1367/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1367/10028)
D/ConnectivityService(  906): mActiveDefaultNetwork: -1
D/ConnectivityService(  906): handleInetConditionChange: no active default network - ignore
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:1
,I/chromium( 4414): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: false
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
D/Tethering(  906): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/CaptivePortalTracker(  906): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/CaptivePortalTracker(  906): NoActiveNetworkState
,D/PMS     (  906): acquireWL(42decb10): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
V/Tethering(  906): bSetPropertyMultiRAB:false
D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  906): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  906): ipv4Default null
I/Tethering(  906): No IPv4 upstream interface, giving up.
,D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
,I/ConnectivityHelper( 1270): [onReceive] WIFI(1): DISCONNECTED
,I/NetworkMonitor( 3883): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1422/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1820/10178)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1881/1000)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3883/10154)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1270/10075)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4304/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4304/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1999/10021)
,I/ActivityManager(  906): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4484 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  906): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  906): releaseWL(42decb10): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ACRA    ( 4484): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4484): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4484): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4484): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4484): Preparing secondary program dexes.
V/DexLibLoader( 4484): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4484): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4484): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4484): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4484): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4484): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4484): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4484): Dex already copied
D/OdexVerifier( 4484): Odex verification is skipped.
,V/DexLibLoader( 4484): Creating class loader
,V/DexLibLoader( 4484): Finished creating class loader
V/DexLibLoader( 4484): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
,V/DexLibLoader( 4484): Dex already copied
D/OdexVerifier( 4484): Odex verification is skipped.
,V/DexLibLoader( 4484): Creating class loader
,V/DexLibLoader( 4484): Finished creating class loader
V/DexLibLoader( 4484): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4484): Dex already copied
D/OdexVerifier( 4484): Odex verification is skipped.
,V/DexLibLoader( 4484): Creating class loader
,V/DexLibLoader( 4484): Finished creating class loader
V/DexLibLoader( 4484): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
,V/DexLibLoader( 4484): Dex already copied
D/OdexVerifier( 4484): Odex verification is skipped.
,V/DexLibLoader( 4484): Creating class loader
,V/DexLibLoader( 4484): Finished creating class loader
,V/DexLibLoader( 4484): Verifying classes from secondary dexes.
,D/DexLibLoader( 4484): DexLibLoader.ensureDexLoaded took 23 ms
,W/dalvikvm( 4484): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4484): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4484): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4484): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4484): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4484): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4484): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4484): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4484): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1133): nl80211: Event message available
D/wpa_supplicant( 1133): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1133): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1133): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1133): nl80211: Survey data missing
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1133): Sorted scan results
I/wpa_supplicant( 1133): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 1133): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1133): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-51
I/wpa_supplicant( 1133): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-73
I/wpa_supplicant( 1133): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-78
I/wpa_supplicant( 1133): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-88
I/wpa_supplicant( 1133): [NULL] 0c:bd:51:2b:c1:25 freq=2437 level=-88
D/wpa_supplicant( 1133): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1133): Add randomness: count=8 entropy=0
D/wpa_supplicant( 1133): Add randomness: count=9 entropy=1
D/wpa_supplicant( 1133): Add randomness: count=10 entropy=2
D/wpa_supplicant( 1133): Add randomness: count=11 entropy=3
D/wpa_supplicant( 1133): Add randomness: count=12 entropy=4
D/wpa_supplicant( 1133): Add randomness: count=13 entropy=5
D/wpa_supplicant( 1133): Add randomness: count=14 entropy=6
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1133): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: AP 0c:bd:51:2b:c1:25 type 0 added
D/wpa_supplicant( 1133): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1133): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1133): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1133): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1133): WPS: AP[4] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1133): wpa_supplicant_pick_network+
I/wpa_supplicant( 1133): Selecting BSS from priority group 1
I/wpa_supplicant( 1133): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1133): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1133): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1133): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not availabl,e
D/wpa_supplicant( 1133):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1133):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-50
I/wpa_supplicant( 1133): Start print parameters
I/wpa_supplicant( 1133): wpa_s->wpa_state is 3
I/wpa_supplicant( 1133): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1133): isConcurrentMode() is 0
I/wpa_supplicant( 1133): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1133): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1133): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1133): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1133): wpa_s->reassociate is 1
I/wpa_supplicant( 1133): wpa_s->is_screen_on 1
I/wpa_supplicant( 1133): wpa_s->ifname wlan0
I/wpa_supplicant( 1133): End print parameters
I/wpa_supplicant( 1133): selected network = 1
D/wpa_supplicant( 1133): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb82814e8  current_ssid=0x0
D/wpa_supplicant( 1133): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1133): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1133): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1133): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1133): check if in concurrent case
I/wpa_supplicant( 1133): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1133): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1133): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1133): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1133): RSN: PMKSA cache search - network_ctx=0xb82814e8 try_opportunistic=0
D/wpa_supplicant( 1133): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1133): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1133): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1133): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1133): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1133): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1133): nl80211: Set mode ifindex 22 iftype 2 (STATION)
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1133): nl80211: Unsubscribe mgmt frames handle 0xb8280718 (mode change)
D/wpa_supplicant( 1133): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8280718
D/wpa_supplicant( 1133): nl80211: Register frame type=0xd0 nl_handle=0xb8280718
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1133): nl80211: Register frame type=0xd0 nl_handle=0xb8280718
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1133): nl80211: Register frame type=0xd0 nl_handle=0xb8280718
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1133): nl80211: Register frame type=0xd0 nl_handle=0xb8280718
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1133): nl80211: Register frame type=0xd0 nl_handle=0xb8280718
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1133): nl80211: Register frame type=0xd0 nl_handle=0xb8280718
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1133): nl80211: Register frame type=0xd0 nl_handle=0xb8280718
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1133): nl80211: Register frame type=0xd0 nl_handle=0xb8280718
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1133): nl80211: Register frame type=0xd0 nl_handle=0xb8280718
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1133): nl80211: Register frame type=0xd0 nl_handle=0xb8280718
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1133): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1133):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1133):   * freq=2412
D/wpa_supplicant( 1133):   * Auth Type 0
,D/wpa_supplicant( 1133):   * WPA Versions 0x2
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1133): nl80211: Connect request send successfully
D/wpa_supplicant( 1133): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1133): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1133): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1133): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1133): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1133): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1133): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1133): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1133): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: WFA subelement id=1 len=6
,D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1133): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1133): reply (907) for get BSS: id=0
I/wpa_supplicant( 1133): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1133): freq=5220
I/wpa_supplicant( 1133): level=-51
I/wpa_supplicant( 1133): tsf=0000000106721308
I/wpa_supplicant( 1133): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1133): ssid=NG7005g
I/wpa_supplicant( 1133): ====
I/wpa_supplicant( 1133): id=1
I/wpa_supplicant( 1133): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1133): freq=2412
I/wpa_supplicant( 1133): level=-50
I/wpa_supplicant( 1133): tsf=0000000106721297
I/wpa_supplicant( 1133): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1133): ssid=NG700
I/wpa_supplicant( 1133): ====
I/wpa_supplicant( 1133): id=2,
I/wpa_supplicant( 1133): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1133): freq=2412
I/wpa_supplicant( 1133): level=-73
I/wpa_supplicant( 1133): tsf=0000000106721338
I/wpa_supplicant( 1133): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1133): ssid=Gonzos
I/wpa_supplicant( 1133): ====
I/wpa_supplicant( 1133): id=3
I/wpa_supplicant( 1133): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1133): freq=2437
I/wpa_supplicant( 1133): level=-78
I/wpa_supplicant( 1133): tsf=0000000106721341
I/wpa_supplicant( 1133): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1133): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1133): ====
I/wpa_supplicant( 1133): id=4
I/wpa_supplicant( 1133): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1133): freq=2437
I/wpa_supplicant( 1133): level=-88
I/wpa_supplicant( 1133): tsf=0000000021061184
I/wpa_supplicant( 1133): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1133): ssid=UPC4688432
I/wpa_supplicant( 1133): ====
I/wpa_supplicant( 1133): id=5
I/wpa_supplicant( 1133): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1133): freq=2412
I/wpa_supplicant( 1133): level=-51
I/wpa_supplicant( 1133): tsf=0000000106721315
I/wpa_supplicant( 1133): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1133): ssid=01ABC
,I/wpa_supplicant( 1133): ====
I/wpa_supplicant( 1133): id=6
I/wpa_supplicant( 1133): bssid=0c:bd:51:2b:c1:25
I/wpa_supplicant( 1133): freq=2437
I/wpa_supplicant( 1133): level=-88
I/wpa_supplicant( 1133): tsf=0000000106721349
I/wpa_supplicant( 1133): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1133): ssid=PLAY-ONLINE_1167
I/wpa_supplicant( 1133): ####
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 5220, timestamp: 106721308, distance: ?(cm), distanceSd: ?(cm)
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (7) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 2412, timestamp: 106721297, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2412, timestamp: 106721338, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -78, frequency: 2437, timestamp: 106721341, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 21061184, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -51, frequency: 2412, timestamp: 106721315, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 6: scan result = SSID: PLAY-ONLINE_1167, BSSID: 0c:bd:51:2b:c1:25, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -88, frequency: 2437, timestamp: 106721349, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 7 to mScanResults
D/BatSI   (  906): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,E/FbInjectorInitializer( 4484): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/wpa_supplicant( 1133): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1133): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1133): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1133): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1133): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1133): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1133): nl80211: if_removed already cleared - ignore event
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1133): nl80211: Event message available
D/wpa_supplicant( 1133): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1133): nl80211: Connect event
D/wpa_supplicant( 1133): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1133): nl80211: Associated with c0:ff:d4:d3:aa:48
D/Tethering(  906): [isWifi] getHotspotEnabled: false
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1133): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1133): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1133): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1133): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1133): Add randomness: count=15 entropy=7
I/wpa_supplicant( 1133): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1133): TDLS: Remove peers on association
D/wpa_supplicant( 1133): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1133): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1133): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1133): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1133): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1133): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1133): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1133): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1133): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1133): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1133): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1133): EAPOL: enable timer tick
D/wpa_supplicant( 1133): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1133): htc_wext_set_keepalive +
I/wpa_supplicant( 1133): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1133): getPrivFuncNum +	
I/wpa_supplicant( 1133): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1133): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1133): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1133): State: ASSOCIATED -> 4WAY_HANDSHAKE
,D/wpa_supplicant( 1133): Get randomness: len=32 entropy=8
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,D/Tethering(  906): interfaceLinkStateChanged wlan0, true
D/Tethering(  906): interfaceStatusChanged wlan0, true
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  906): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  906): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  906): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  906): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  906): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  906): handleAssociatedWithEvent. bLFR =false
,D/WifiMonitor(  906): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  906): Enter handleAssociatedWithEvent
D/WifiStateMachine(  906): Associated
D/WifiStateMachine(  906): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  906): Exit handleAssociatedWithEvent
,D/WifiStateMachine(  906): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  906): This record is existed, only update it...
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
I/wpa_supplicant( 1133): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1133): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb82809f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 1133):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1133): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1133): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1133): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6ed0b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1133):    broadcast key
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 11
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1133): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
,E/wpa_supplicant( 1133): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1133): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1133): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/WifiMonitor(  906): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1133): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
,I/wpa_supplicant( 1133): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
E/wpa_supplicant( 1133): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1133): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1133): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1133): set send_ind_to_ndc = 0
I/wpa_supplicant( 1133): htc_wext_set_TX_TRACKING (1)+,
I/wpa_supplicant( 1133): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1133): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1133): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1133): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1133): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1133): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1133): EAPOL: SUPP_PAE entering state AUTHENTICATED
,D/wpa_supplicant( 1133): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1133): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1133): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1133): EAPOL authentication completed successfully
I/wpa_supplicant( 1133): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1133): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1133): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1133): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
D/Tethering(  906): interfaceStatusChanged wlan0, true
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  906): [isWifi] getHotspotEnabled: false
,D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED,
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/WifiStateMachine(  906): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  906): This record is existed, only update it...
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiApDatabaseHandler(  906): updateConnectedAP...
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WISPrService( 4177): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4177): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  906): Provision feature enable=false
,D/ConnectivityService(  906): mActiveDefaultNetwork: -1
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/DhcpStateMachine(  906): [StoppedState] Start DHCP
D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1133): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1133): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1133): Power_Mode_Type mode = 1
I/wpa_supplicant( 1133): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1133): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  906):    returned null
E/WifiStateMachine(  906): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1133): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  906):    returned null
D/WifiStateMachine(  906): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  906): acquireWL(440c0d50): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 906 1000 null
D/WifiStateMachine(  906): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  906): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42388708 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42388708 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:0
,W/fb4a(:<default>):StaticBindingVerifier( 4484): Verify
,D/WifiService(  906): New client listening to asynchronous messages
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4484/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4484): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4484): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4484): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  906): killProcessQuiet, pid=4222
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 4222:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,D/PMS     (  906): acquireWL(425ecb38): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2227 10028 null
I/ActivityManager(  906): Recipient 4222
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(430ceeb0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2227 10028 null
,D/PMS     (  906): releaseWL(425ecb38): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1367): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2227/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1367/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1367/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1367/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2227/10028)
,D/PMS     (  906): releaseWL(430ceeb0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/AutoSetting( 1405): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  906): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4513 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1405/10053)
,D/AutoSetting( 1405): Util - no network available!
,D/AutoSetting( 1405): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1405): service - mHandler: cancel location update
,D/AutoSetting( 1405): service -           changes count: 0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1405/10053)
,W/fb4a(:<default>):UserScope( 4484): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4484): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/MobileConnectivityChangeReceiver( 4513): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4513): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4513): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4513): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,W/fb4a(:<default>):UserScope( 4484): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/Process (  906): killProcessQuiet, pid=3863
I/ActivityManager(  906): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4527 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,I/ActivityManager(  906): Killing 3863:com.htc.mediamanager/u0a32 (adj 15): empty #17
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4513/10078)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4513/10078)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4513/10078)
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4484): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,I/ActivityManager(  906): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4544 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=4245
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 4245:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,E/dalvikvm( 4484): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4484): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
I/ActivityManager(  906): Recipient 4245
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  906): Client connection lost with reason: 4
,I/ActivityManager(  906): Recipient 3863
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4484): Grow heap (frag case) to 9.962MB for 84664-byte allocation
E/dalvikvm( 4484): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4484): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4484): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4484): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4484): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4484): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4484): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/dalvikvm( 4484): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4484): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/ContextImpl( 4544): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4544): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/dalvikvm( 4484): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
,W/dalvikvm( 4484): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/dalvikvm( 4484): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4484): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4484): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4484): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4484): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,W/GAV2    ( 4544): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4544): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4544): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4484): Grow heap (frag case) to 10.022MB for 39954-byte allocation
,I/dalvikvm-heap( 4484): Grow heap (frag case) to 10.098MB for 79892-byte allocation
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4544/10151)
,V/WebViewChromiumFactoryProvider( 4544): Binding Chromium to main looper Looper (main, tid 1) {41b18218}
,I/LibraryLoader( 4544): Expected native library version number "",actual native library version number ""
,I/chromium( 4544): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4544): Initializing chromium process, renderers=0
,D/PMS     (  906): acquireWL(43c37ee0): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,E/AudioManagerAndroid( 4544): BLUETOOTH permission is missing!
D/PMS     (  906): releaseWL(43c37ee0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/PMS     (  906): acquireWL(4400f088): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,I/Adreno-EGL( 4544): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4544): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4544): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4544): Local Branch: 
I/Adreno-EGL( 4544): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4544): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4544):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4544): Starting up...
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4544/10151)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4544/10151)
,I/dalvikvm-heap( 4484): Grow heap (frag case) to 10.281MB for 75760-byte allocation
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4153/10160)
,D/Process (  906): killProcessQuiet, pid=4025
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4153/10160)
I/ActivityManager(  906): Killing 4025:com.google.android.gm/u0a107 (adj 15): empty #17
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4484/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1820/10178)
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4360b4d0 u0 ReceiverList{4358b338 4484 com.facebook.katana/10026/u0 remote:4355f060}}
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4360b4d0 u0 ReceiverList{4358b338 4484 com.facebook.katana/10026/u0 remote:4355f060}}
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43c07128 u0 ReceiverList{43c070c8 4484 com.facebook.katana/10026/u0 remote:43b16c60}}
,D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1820/10178)
D/GCM     ( 1367): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4484/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4484/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4484/10026)
,D/PMS     (  906): acquireWL(440caac0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1422 10028 null
,D/PMS     (  906): releaseWL(440caac0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 4025
,D/GCoreFlp( 1422): Unknown pending intent to remove.
D/PMS     (  906): acquireWL(43b02da0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1422 10028 null
D/PMS     (  906): releaseWL(43b02da0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4484): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4484): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,D/wpa_supplicant( 1133): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1133): EAPOL: disable timer tick
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1133): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1133): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1133): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): handlePostDhcpSetup release wake lock during DHCP
D/WifiP2pService(  906): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  906): releaseWL(440c0d50): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1133): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): gateway: /192.168.1.1
,D/WifiNative-wlan0(  906): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1133): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  906): VerifyingLinkState enter
,D/WifiStateMachine(  906): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  906): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  906): VerifyingLinkState: enableIpv6
D/WIFI_ICON( 1116): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -50, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/WifiDataStallTracker(  906): startDataStallAlarm: tag=19192 delay=15s
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NetworkPolicy(  906): mWifiStateReceiver: meteredHint=false,EPS mode=false
,D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED connected
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1820/10178)
,D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  906): Provision feature enable=false
,D/WifiWatchdogStateMachine(  906): WAN detection
D/ConnectivityService(  906): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  906): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  906): default: teardown()
D/MDST    (  906): default: setTeardownRequested(true)
,D/MDST    (  906): default: setEnableApn apnType =default , enable=false
D/WISPrService( 4177): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  906): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WIFI_ICON( 1116): WifiActivity: 3
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/MDST    (  906): default: setTeardownRequested(true)
D/ConnectivityService(  906): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/WifiStateMachine(  906): syncGetConfiguredNetworks
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
E/ConnectivityService(  906): Unexpected mtu value: android.net.wifi.WifiStateTracker@4243e270
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=false resetMask=0
,D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  906): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  906): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  906): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
,I/QuickSettingWifi( 1116): receive.wifiConnect:true wifiAPname:NG700 elapse:0
D/WirelessDisplayService(  906): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  906):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  906): sendGeneralBroadcastDelayed, restrictEnable=false
D/PMS     (  906): acquireWL(42643dd0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4513/10078)
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/PMS     (  906): acquireWL(431c09c0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2227 10028 null
D/PMS     (  906): releaseWL(42643dd0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
D/PMS     (  906): acquireWL(43f60c98): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2227 10028 null
D/PMS     (  906): releaseWL(431c09c0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
I/CheckinService( 2227): Preparing to send checkin request
,I/EventLogService( 2227): Accumulating logs since 1450238214193
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2227/10028)
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,I/GoogleHttpClient( 2227): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2227): Using GMS GoogleHttpClient
,D/ConnectivityService(  906): mActiveDefaultNetwork: WIFI
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (2227/10028)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (2227/10028)
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,W/GLSUser ( 1367): GoogleAccountDataService.getToken()
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1367): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/CheckinRequestBuilder( 2227): awaiting user notification for token
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,D/DotMatrix( 1559): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1559): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41b13e48 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.google.android.gms 1 7 2 12
,I/ActivityManager(  906): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4617 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 4617): install
,I/MultiDex( 4617): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4617): loading existing secondary dex files
,I/MultiDex( 4617): load found 1 secondary dex files
,I/MultiDex( 4617): install done
,I/ProviderInstaller( 4617): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1367): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/Settings( 4617): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (4617/10028)
,I/jxcore-log( 4414): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 4414): 
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  906): releaseWL(43f78048): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  906): NetTransition Wakelock for ConnectedState released by timeout
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: true
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,V/Tethering(  906): bSetPropertyMultiRAB:false
D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,D/CaptivePortalTracker(  906): NoActiveNetworkState
I/Tethering(  906): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
,I/Tethering(  906): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  906): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  906): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  906): Found interface wlan0
,D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
I/acms    ( 1881): Checking Certificates
I/acms    ( 1881): Checking Developer Certificates
I/acms    ( 1881): Checking Application Certificates
I/acms    ( 1881): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1881): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
,I/acms    ( 1881): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1881): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1881): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1881): Updating next query delay: 75600000
I/mlserverapp( 1881): MirrorLink is never connected, don't setup ACMS programed checks
,I/mlserverapp( 1881): cancelACMSProgrammedChecks
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/PMS     (  906): acquireWL(435f61e8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1820/10178)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1422/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1881/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4304/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4513/10078)
,I/NetworkMonitor( 3883): type=WIFI subType= reason=null isConnected=true
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,I/ConnectivityHelper( 1270): [onReceive] WIFI(1): CONNECTED
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3883/10154)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.musicenhancer (3917/10051)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4484/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1270/10075)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4304/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4484/10026)
D/PMS     (  906): acquireWL(430189d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  906): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4484/10026)
D/PMS     (  906): releaseWL(430189d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  906): releaseWL(435f61e8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1999/10021)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/PMS     (  906): acquireWL(422ed830): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2227 10028 null
D/PMS     (  906): releaseWL(422ed830): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1367): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1367/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1367/10028)
D/libc    ( 1367): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1367): [NET] getaddrinfo-,err=8
D/libc    ( 1367): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1367): [NET] getaddrinfo-, 1
,D/libc    ( 1367): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =34c3 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1367/10028)
D/PMS     (  906): acquireWL(44057af0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1367 10028 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2227/10028)
,D/AutoSetting( 1405): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4513): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4513): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1405/10053)
,D/AutoSetting( 1405): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1405): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1405): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1405): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 1405): service - handleMessage() setting current location null
D/AutoSetting( 1405): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1405): service - onStartCommand() check timezone in 30000
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4544/10151)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1405/10053)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [2][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4153/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4153/10160)
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 214
D/libc    (  364): [NET]res_nsend:resplen=79
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1367): [NET] getaddrinfo_proxy-, success
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1820/10178)
,I/dalvikvm-heap( 4153): Grow heap (frag case) to 13.516MB for 1821008-byte allocation
,I/PMS     (  906): Going to sleep due to screen timeout...
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42118308
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Light sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42118308, eanble = 0, strlen(mName) = 59
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42370110
W/SensorService(  906): Listener[1] = com.htc.smartdim.sensor_eye@4236e340
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  906): mThumbnailWidth=360, mThumbnailHeight=640
V/LightsService(  906): setLight #2: color=#0
D/qdlights(  906): set_light_buttons_func: on=0 brightness=0
W/BatSI   (  906): Couldn't get kernel wake lock stats
V/LightsService(  906): setLight #0: color=#0
,D/WirelessDisplayService(  906): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  906): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,W/PMS     (  906): mWirelessDisplayManager is null
I/Adreno-EGL( 4617): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4617): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4617): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4617): Local Branch: 
I/Adreno-EGL( 4617): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4617): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4617):                  aa63bbd948f41d15fc72f585e
,D/libc    ( 1367): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1367): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1367/10028)
,D/PMS     (  906): acquireWL(43722178): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10028 null
,D/PMS     (  906): releaseWL(43722178): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/Adreno-EGL( 4617): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4617): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4617): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4617): Local Branch: 
I/Adreno-EGL( 4617): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4617): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4617):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4617): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4617): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4617): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4617): Local Branch: 
I/Adreno-EGL( 4617): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4617): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4617):                  aa63bbd948f41d15fc72f585e
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=0 [5][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiStateMachine(  906): BroadcastRSSIForIMS, newrssi =-51 , oldRssi= -200
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1133): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
D/WIFI_ICON( 1116): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/GCM     ( 1367): Connected
D/PMS     (  906): acquireWL(43083790): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1367 10028 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1367/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1367/10028)
D/PMS     (  906): releaseWL(44057af0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1367/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1367/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1367/10028)
D/PMS     (  906): releaseWL(43083790): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  906): acquireWL(433be738): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1367 10028 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1367/10028)
,D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1367/10028)
,D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
,D/GCM     ( 1367): Message class mpf
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1367/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1367/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1367/10028)
D/PMS     (  906): releaseWL(433be738): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  906): acquireWL(434538b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10028 null
D/PMS     (  906): releaseWL(434538b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/CheckinTask( 2227): Sending checkin request (8889 bytes)
D/libc    ( 2227): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2227): [NET] getaddrinfo-,err=8
D/libc    ( 2227): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2227): [NET] getaddrinfo-, 1
,D/libc    ( 2227): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =bd57 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 234
D/libc    (  364): [NET]res_nsend:resplen=84
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2227): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2227): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2227): [NET] getaddrinfo-,err=8
,D/SurfaceControl(  906): Excessive delay in blankDisplay() while turning screen off: 398ms
D/PMS     (  906): nativeSetInteractive:false
D/PMS     (  906): nativeSetInteractive:false done
D/PMS     (  906): nativeSetAutoSuspend:true
D/PMS     (  906): nativeSetAutoSuspend:true done
D/HABCtrl (  906): TPE algorithm. remove timeout.
D/PMS     (  906): OOBE c monitor 11
I/InputManager(  906): Cancel all due to getting PMS screen off broadcast
D/NfcService( 1255): ScreenObserver: OFF
,V/KeyguardServiceDelegate(  906): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@440ca810)
D/NfcService( 1255): applyRouting - 0
W/ResourceType( 4414): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4414): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41b20358 VFEDH.C. .F...... 0,0-720,1134 #64}
,D/NfcService( 1255): applyRouting -2
,I/InputMethodManagerService(  906): screenObserver, isScreenOn=false
I/InputMethodManagerService(  906): Disable input method client, pid=4414
D/PMN     (  906): wakingUp
D/PMS     (  906): acquireWL(42d31c28): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1255 1027 null
I/IntentController( 1116): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  906): **** SHOWN CALLED ****
D/WirelessDisplayService(  906): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
I/WindowManager(  906): No lock screen! windowToken=null
D/PMS     (  906): releaseWL(42d31c28): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  906): onScreenOn
,D/PMS     (  906): acquireWL(4251f258): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4251f258): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/MtpService( 1999): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 1999): [MTP][onReceive]-
,D/NfcService( 1255): applyRouting - 0
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/NfcService( 1255): applyRouting -2
,D/AutoSetting( 1405): receiver - intent: android.intent.action.USER_PRESENT
D/AlarmManager(  906): ACTION_SCREEN_ON
I/AlarmManager(  906): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done recovering
D/PMS     (  906): acquireWL(440523f8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1255 1027 null
I/AlarmManager(  906): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  906): releaseWL(440523f8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/AutoSetting( 1405): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/TetherSettings( 4177): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4177): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4177): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4177): Cust_ConnectToPC   : spcsc>false
D/        ( 4177): Cust_ConnectToPC   : IPT>true
D/        ( 4177): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 4177): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4177): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4177): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4177): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
I/PSReceiver( 4177): onReceive:android.intent.action.USER_PRESENT
,I/ClockThread( 1116): stop update clock
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=19193 delay=15s
,I/SmartNS_PSService( 4177): onReceive:android.intent.action.USER_PRESENT
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,W/Settings( 4177): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 4177): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
I/SmartNS_PSService( 4177):  defaultType:0
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=12 [16][2][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1133): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1133): SET_SCREEN_ON:On
I/wpa_supplicant( 1133): htc_wext_set_keepalive +
I/wpa_supplicant( 1133): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1133): getPrivFuncNum +	
I/wpa_supplicant( 1133): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1133): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1133): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1133): htc_wext_set_TX_TRACKING (1)+
,I/wpa_supplicant( 1133): htc_wext_set_TX_TRACKING - ret = 0
,D/WifiNative-wlan0(  906):    returned true
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
D/WIFI_ICON( 1116): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
D/WIFI_ICON( 1116): WifiActivity: 3
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4657 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/NetworkPolicy(  906): updateScreenOn: false
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4657): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1800): onScreenOn: false
D/PMS     (  906): acquireWL(4377a400): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1422 10028 null
,D/PMS     (  906): releaseWL(4377a400): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1800): onScreenOn: 1450238270644
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1800): onScreenOn: 1450238270644
,D/SmartSyncUtils( 4657): isEpsOn(), nState = 0
,D/PMS     (  906): acquireWL(44045960): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4657 1000 null
I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42370110
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42370110, eanble = 0, strlen(mName) = 91
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  906): Listener[0] = com.htc.smartdim.sensor_eye@4236e340
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  906): goingToSleep
D/PMS     (  906): acquireWL(4311a540): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 906 1000 null
,D/PMS     (  906): releaseWL(44045960): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,D/PMS     (  906): releaseWL(4400f088): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/AlarmManager(  906): ACTION_SCREEN_OFF
I/AlarmManager(  906): [AlarmQueuing] screen off now: 
I/AlarmManager(  906): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=19193 mDataStallAlarmIntent=PendingIntent{43bd3eb8: PendingIntentRecord{4247b558 android broadcastIntent}}
I/AlarmManager(  906): [AlarmQueuing] wifi connection: true
D/PMS     (  906): releaseWL(4311a540): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1133): SET_SCREEN_ON:Off
I/wpa_supplicant( 1133): htc_wext_set_keepalive +
I/wpa_supplicant( 1133): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1133): getPrivFuncNum +	
I/wpa_supplicant( 1133): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1133): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1133): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1133): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1133): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  906):    returned true
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  371): ParamSet string: screen_state=off
,D/PMS     (  906): acquireWL(43902f40): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 906 1000 null
,D/SmartSyncUtils( 4657): getMobilePolicyEnabled, result = true
,D/Process (  906): killProcessQuiet, pid=4274
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4484/10026)
I/ActivityManager(  906): Killing 4274:com.google.android.partnersetup/u0a31 (adj 15): empty #17
D/NetworkPolicy(  906): updateScreenOn: false
,D/ContactMessageStore( 1244): start background delete task...
D/PMS     (  906): acquireWL(4406aab0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10028 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4484/10026)
I/ActivityManager(  906): Recipient 4274
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ContactMessageStore( 1244): size: 0 , 0
,D/ContactMessageStore( 1244): Background delete complete
,D/wpa_supplicant( 1133): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(4406aab0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/PMS     (  906): releaseWL(43902f40): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
W/ContextImpl( 4657): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4657): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4657): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4657): getMobilePolicyEnabled, result = true
I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4236e340
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 1
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4236e340, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Proximity sensor
,W/SensorService(  906): pid=906, uid=1000
D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (2227/10028)
D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (2227/10028)
D/WifiService(  906): New client listening to asynchronous messages
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  906): Active sensors: size = 0
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4236e340, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4236e340
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,W/fb4a(:<default>):UserScope( 4484): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4484): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
E/ActivityThread(  906): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@41e16e08 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@41e16e08 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4484/10026)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/AutoSetting( 1405): service - mHandler: cancel location update
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,D/AutoSetting( 1405): service -           changes count: 0
,D/DotMatrix( 1559): [EventService] getTotalRam: 1873 Mb
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1800): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1800): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1800): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1800): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1800): onScreenOff
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/PMS     (  906): acquireWL(42c31af0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1422 10028 null
D/PMS     (  906): releaseWL(42c31af0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,W/GLSUser ( 1367): GoogleAccountDataService.getToken()
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4484/10026)
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1367): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1559): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1559): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 2227): awaiting user notification for token
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41c633a8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.google.android.gms 1 10 3 12
,I/CheckinTask( 2227): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2227): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2227/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2227/10028)
,D/PMS     (  906): releaseWL(43f60c98): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/GCM     ( 1367): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
E/ActivityThread( 2227): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41d042a8 that was originally bound here
E/ActivityThread( 2227): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41d042a8 that was originally bound here
E/ActivityThread( 2227): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2227): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2227): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2227): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2227): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2227): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2227): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2227): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2227): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2227): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2227): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2227): 	at bks.a(SourceFile:298)
E/ActivityThread( 2227): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2227): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2227): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2227): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1367): GCM config loaded
,E/fb4a(:<default>):LocalFbBroadcastManager( 4484): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4484/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4484/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4484/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4484/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4484/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4484/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4484/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4484/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4484/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4484/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4484/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4484/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4484/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4484/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4484/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4484/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4484/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4484/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4484/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4484/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4484/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4484/10026)
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =3ca +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  906): Find DNS Address www.htc.com/23.59.123.86
,D/WifiStateMachine(  906): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,I/GAV2    ( 4544): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  906): acquireWL(43fd5648): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1422 10028 null
,D/PMS     (  906): acquireWL(4403dc08): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1422 10028 null
,D/PMS     (  906): releaseWL(43fd5648): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  906): releaseWL(4403dc08): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/AutoSetting( 1501): service - handleMessage() stop self
,D/AutoSetting( 1501): service - onDestroy() END
,D/AutoSetting( 1501): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=4304
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4304:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4304
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  906): killProcessQuiet, pid=4327
,I/ActivityManager(  906): Killing 4327:com.htc.backup/1000 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 4327
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  906): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/PMS     (  906): acquireWL(4438f2d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41eb6b68: PendingIntentRecord{41eb32f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=119886, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false),
,D/PMS     (  906): releaseWL(4438f2d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(4352e640): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4352e640): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1405): service - mHandler: update timezone
,D/AutoSetting( 1501): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1501): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1501): service - onCreate()
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1501): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1501): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/DotMatrix( 1559): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1559): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1501): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1501): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1501): service - mHandler: update timezone
,D/AutoSetting( 1501): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1501): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1501): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1501): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1559): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1559): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1116): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41c3ea70 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.htc.htclocationservice 2 7 2 11
,D/GpsLocationProvider(  906): ALARM_XTRA_TIMEOUT
D/PMS     (  906): acquireWL(440abea0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{42505918: PendingIntentRecord{425088a8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=140689, Int=0
D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  906): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  906): acquireWL(42450a88): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
V/AlarmManager(  906): sending alarm PendingIntent{43613e58: PendingIntentRecord{41ddb050 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=140706, Int=0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1367/10028)
D/PMS     (  906): acquireWL(432da770): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10028 null
D/PMS     (  906): releaseWL(440abea0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
D/PMS     (  906): releaseWL(432da770): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =69b6 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE,
,D/AutoSetting( 1405): service - handleMessage() stop self
,D/AutoSetting( 1405): service - handleMessage() quit looper
,D/AutoSetting( 1405): service - onDestroy() END
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  364): [NET]res_nsend:resplen=238
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
I/global  (  906): call createSocket() return a new socket.
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  906): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  906): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  906): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  906):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  906): releaseWL(42450a88): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/Process (  906): killProcessQuiet, pid=3917
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3917:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3917
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{44020280 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  906): acquireWL(43bb1360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43bb1360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1501): service - handleMessage() stop self
,D/AutoSetting( 1501): service - onDestroy() END
,D/AutoSetting( 1501): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=4291
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4291:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 4291
,D/TelephonyReceiver( 1244): switchBindHtcMsgCursor: null
,D/PMS     (  906): acquireWL(435f7c20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41eb6b68: PendingIntentRecord{41eb32f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=179885, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(435f7c20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(435cc538): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(435cc538): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(43533028): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{43197fc8: PendingIntentRecord{42c469d0 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=227680, Int=0
,I/ActivityManager(  906): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4698 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  906): sending alarm PendingIntent{42529780: PendingIntentRecord{4245d768 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1450238380036, Int=10800000
,D/PMS     (  906): releaseWL(43533028): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.aurora (4698/10047)
,D/Process (  906): killProcessQuiet, pid=4345
,I/ActivityManager(  906): Killing 4345:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Recipient 4345
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2227/10028)
,D/PMS     (  906): acquireWL(4301bc78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{430b7be8: PendingIntentRecord{42c469d0 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=230582, Int=0
,D/PMS     (  906): releaseWL(4301bc78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(42f8e7c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41eb6b68: PendingIntentRecord{41eb32f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=239885, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42f8e7c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(42e3ce20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42e3ce20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(42de9668): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(42de9668): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42660d78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41eb6b68: PendingIntentRecord{41eb32f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=299885, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42660d78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(42658b78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42658b78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4414): Connected to the server!
I/jxcore-log( 4414): 
,I/chromium( 4414): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/PMS     (  906): acquireWL(4264e688): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(4264e688): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1116): closing low battery warning: level=100
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(425fcc98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41eb6b68: PendingIntentRecord{41eb32f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=359886, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(425fcc98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/GLSUser ( 1367): GoogleAccountDataService.getToken()
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1367): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1559): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1559): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1116): com.google.android.gms (false,0)
,W/GLSActivity( 1367): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1367): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1367): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1367): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1367): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1367): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1367): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1367): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 4115): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4115): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4115): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4115): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4115): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4115): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4115): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4115): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41dd99e0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.google.android.gms 2 14 3 12
,D/libc    ( 4115): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4115): [NET] getaddrinfo-,err=8
D/libc    ( 4115): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4115): [NET] getaddrinfo-, 1
,D/libc    ( 4115): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =fdec +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 107
D/libc    (  364): [NET]res_nsend:resplen=87
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4115): [NET] getaddrinfo_proxy-, success
I/global  ( 4115): call createSocket() return a new socket.
D/libc    ( 4115): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4115): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4115): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4115): [NET] getaddrinfo-,err=8
,D/PMS     (  906): acquireWL(41efd250): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(41efd250): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(41efa520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(41efa520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(41bbd1c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{4404d628: PendingIntentRecord{440d22b8 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=410239, Int=300000
,D/PMS     (  906): releaseWL(41bbd1c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(4268a260): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41eb6b68: PendingIntentRecord{41eb32f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=419885, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4268a260): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42431230): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42431230): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(42272d38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41eb6b68: PendingIntentRecord{41eb32f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=479886, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42272d38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42d8e560): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42d8e560): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(425394d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41eb6b68: PendingIntentRecord{41eb32f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=539885, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(425394d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(425fb010): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(425fb010): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42572e70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(42572e70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42668b68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41eb6b68: PendingIntentRecord{41eb32f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=599886, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42668b68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42404598): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42404598): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  350): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1244): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1244): mDeleteTask = null, bDeleting = false
,D/ContactMessageStore( 1244): start background delete task...
D/AccFlag ( 1244): sku_id=99
,D/ContactMessageStore( 1244): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1244): size: 0 , 0
,D/ContactMessageStore( 1244): Background delete complete
,D/PMS     (  906): acquireWL(41cb60b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41eb6b68: PendingIntentRecord{41eb32f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=659885, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(41cb60b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42585108): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42585108): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(41f73dc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{4404d628: PendingIntentRecord{440d22b8 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=710239, Int=300000
,D/PMS     (  906): releaseWL(41f73dc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/Process (  906): killProcessQuiet, pid=4361,
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 ,
I/ActivityManager(  906): Killing 4361:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4361
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(424dcfd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41eb6b68: PendingIntentRecord{41eb32f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=719885, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(424dcfd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4264c838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4264c838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42453748): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41eb6b68: PendingIntentRecord{41eb32f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=779885, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42453748): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4208af28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  906): sending alarm PendingIntent{41df5978: PendingIntentRecord{42448a28 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=784328, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{43c1f610: PendingIntentRecord{42643ad0 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450238917174, Int=1800000
,V/AlarmManager(  906): sending alarm PendingIntent{420ebf90: PendingIntentRecord{42641128 com.google.android.gms startService}}, i=com.google.android.gms.icing.INDEX_RECURRING_MAINTENANCE, t=0, cnt=1, w=1450238945913, Int=86400000
D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,D/PMS     (  906): acquireWL(43fbbe48): PARTIAL_WAKE_LOCK  Icing 0x1 2227 10028 null
,D/PMS     (  906): acquireWL(4262a558): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2227 10028 null
,D/PMS     (  906): releaseWL(4208af28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  906): acquireWL(440b0778): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2227 10028 null
,D/PMS     (  906): releaseWL(4262a558): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
I/EventLogService( 2227): Aggregate from 1450238268749 (log), 1450237117134 (data)
,D/PMS     (  906): releaseWL(440b0778): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,I/Icing   ( 2227): updateResources: need to parse gfv{com.google.android.gms}
,I/Icing   ( 2227): Performing maintenance usage 2126188 budget 4133628086 free 99.949% index free 99.904% purge? false target 1554411150
,D/PMS     (  906): releaseWL(43fbbe48): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(42f95c60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42f95c60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43bc9e78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41eb6b68: PendingIntentRecord{41eb32f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=839885, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43bc9e78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43c5d728): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43c5d728): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4311c670): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41eb6b68: PendingIntentRecord{41eb32f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=899885, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4311c670): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42648680): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42648680): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(436cd640): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41eb6b68: PendingIntentRecord{41eb32f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=959885, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(436cd640): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43633dd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43633dd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4408f2b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10028}
,V/AlarmManager(  906): sending alarm PendingIntent{43548478: PendingIntentRecord{41e75870 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1009977, Int=0
V/AlarmManager(  906): sending alarm PendingIntent{425d1ed0: PendingIntentRecord{425d4480 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450239100344, Int=900000
,V/AlarmManager(  906): sending alarm PendingIntent{42d83198: PendingIntentRecord{42d7b7e8 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450239170753, Int=0
,D/PMS     (  906): acquireWL(437da660): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1367 10028 null
,D/PMS     (  906): releaseWL(437da660): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,D/PMS     (  906): acquireWL(436eff58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10028 null
,D/PMS     (  906): releaseWL(436eff58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/ContextImpl( 4657): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4657): call getInstance()
,D/SmartSyncUtils( 4657): isEpsOn(), nState = 0
,D/PMS     (  906): releaseWL(4408f2b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PowerUsageList:PowerUsageHelper( 4657): MY_DEBUG = false
D/PMS     (  906): acquireWL(43134ab8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4657 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4657): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4657): [updateNmRange] USERNIGHT_TIMESTART = 18, USERNIGHT_TIMEEND = 23, nStart = 18, nEnd = 23, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4657): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4657): SettingOnTime = 1450303200000, randomSettingOnTime = 1450301756000
,D/SmartSyncScreenOnOffTimeReceiver( 4657): SettingOffTime = 1450285200000, randomSettingOffTime = 1450285385000
,D/SmartSyncScreenOnOffTimeReceiver( 4657): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4657): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4657): bNightModeTurnOffOnce = false
D/PMS     (  906): acquireWL(4359edf0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1367 10028 null
D/PMS     (  906): releaseWL(43134ab8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/GCM     ( 1367): Message class mow
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1367/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1367/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1367/10028)
,D/PMS     (  906): releaseWL(4359edf0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  906): acquireWL(42527680): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10028 null
,D/PMS     (  906): releaseWL(42527680): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=7 [255][20][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(43448350): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41eb6b68: PendingIntentRecord{41eb32f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1019886, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43448350): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42b99538): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42b99538): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(425f8c48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41eb6b68: PendingIntentRecord{41eb32f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1079885, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(425f8c48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(440d2590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(440d2590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(430c86d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41eb6b68: PendingIntentRecord{41eb32f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1139885, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(430c86d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42ffbe78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42ffbe78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(438f57a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41eb6b68: PendingIntentRecord{41eb32f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1199885, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(438f57a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(443cbd30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(443cbd30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  350): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(440c3e90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41eb6b68: PendingIntentRecord{41eb32f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1259886, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(440c3e90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(440a49d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(440a49d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4405b730): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41eb6b68: PendingIntentRecord{41eb32f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1319885, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4405b730): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4405b430): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4405b430): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4405ab00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41eb6b68: PendingIntentRecord{41eb32f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1379886, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4405ab00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(44047ef0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(44047ef0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(44046f60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41eb6b68: PendingIntentRecord{41eb32f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1439886, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(44046f60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(440135e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(440135e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(44010438): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41eb6b68: PendingIntentRecord{41eb32f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1499885, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(44010438): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(44000ed0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(44000ed0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43ff93a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41eb6b68: PendingIntentRecord{41eb32f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1559886, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43ff93a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43ff0ef0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43ff0ef0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43fee2b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41eb6b68: PendingIntentRecord{41eb32f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1619886, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43fee2b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43fe1ed8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43fe1ed8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43fbcff0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(43fbcff0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43b72788): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41eb6b68: PendingIntentRecord{41eb32f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1679886, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43b72788): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43b29e50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43b29e50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(436cc208): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(436cc208): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4368f410): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41eb6b68: PendingIntentRecord{41eb32f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1739885, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4368f410): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43671720): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43671720): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43558420): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41eb6b68: PendingIntentRecord{41eb32f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1799885, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43558420): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): acquireWL(43558120): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43558120): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  350): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(4262a3d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  906): sending alarm PendingIntent{41df5978: PendingIntentRecord{42448a28 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1505822, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{42260378: PendingIntentRecord{42516e78 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1820336, Int=1800000
,D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,I/ProcessStatsService(  906): Prepared write state in 47ms
,V/AlarmManager(  906): sending alarm PendingIntent{425d1ed0: PendingIntentRecord{425d4480 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450240000344, Int=900000
,I/ProcessStatsService(  906): Pruning old procstats: /data/system/procstats/state-2015-12-15-18-04-07.bin
,I/ProcessStatsService(  906): Prepared write state in 48ms
,D/PMS     (  906): acquireWL(42557488): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42557488): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,W/ContextImpl( 4657): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  906): releaseWL(4262a3d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): acquireWL(42b4a310): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41eb6b68: PendingIntentRecord{41eb32f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1859886, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42b4a310): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(430c33d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
I/BatteryService(  906): n_update end
D/PMS     (  906): releaseWL(430c33d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(44077fe8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(44077fe8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4751): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4751): ====startRecUseTime====
D/htc.customization.log.level( 4751):  is 
W/CustomizationLogLevel( 4751): Level value is invalid, use default level 2
D/CustomizationManager( 4751):  Read ACC file spent 0.123 (s)
D/CIDMapFileReader( 4751): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4751): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4751): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4751): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4751): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4751): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4751): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4751): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4751): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4751): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4751): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4751): Parsing tag category name = system
I/CustomizationCIDLoader( 4751): Parsing tag category name = application
I/CustomizationCIDLoader( 4751): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4751): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4751): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4751): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4751): Parsing tag category name = Settings
D/CustomizationManager( 4751):  Read CID file spent 0.180 (s)
D/CustomizationManager( 4751):  All configurations done spent 0.181 (s)
W/HtcNativeFlag( 4751): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4751): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4751): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4751): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  906): deletePackageAsUser: pkg=com.test.thalitest, pid=4751, uid=2000 user=0
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
D/Process (  906): killProcessQuiet, pid=4414
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  906): Killing 4414:com.test.thalitest/u0a348 (adj 0): stop com.test.thalitest
W/ActivityManager(  906): handleTopAppChanged(): The previous AP is died unexpectedly.
D/Process (  906): killProcessQuiet, pid=4544
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=4527
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=4513
I/ActivityManager(  906): Killing 4544:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1801s
I/ActivityManager(  906): Killing 4527:com.android.chrome/u0a96 (adj 15): empty for 1801s
I/ActivityManager(  906): Killing 4513:com.google.android.setupwizard/u0a78 (adj 15): empty for 1801s
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=3883
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=4461
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  906): Killing 3883:com.google.android.music:main/u0a154 (adj 15): empty for 1801s
I/ActivityManager(  906): Killing 4461:com.htc.mms.backupagent/u0a77 (adj 15): empty for 1807s
I/ActivityManager(  906): Killing 4115:com.android.vending/u0a73 (adj 15): empty for 1823s
D/Process (  906): killProcessQuiet, pid=4115
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=4376
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
W/asset   (  906): Copying FileAsset 0x62d56f08 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  906): Killing 4376:com.android.settings:remote/1000 (adj 15): empty for 1837s
I/ActivityManager(  906): Recipient 4527
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906):   Force finishing activity ActivityRecord{41f75288 u0 com.test.thalitest/.MainActivity t2}
I/ActivityManager(  906): Recipient 4513
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4376
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4461
I/ActivityManager(  906): Recipient 4115
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/InputDispatcher(  906): channel '425a5960 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  906): channel '425a5960 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
W/InputDispatcher(  906): Attempted to unregister already unregistered input channel '425a5960 com.test.thalitest.MainActivity (s)'
I/WindowManager(  906): WINDOW DIED Window{425a5960 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  906): Client connection lost with reason: 4
W/WindowManager(  906): Failed looking up window
W/WindowManager(  906): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@420a14a0 does not exist
W/WindowManager(  906): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8463)
W/WindowManager(  906): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8454)
W/WindowManager(  906): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1052)
W/WindowManager(  906): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/WindowManager(  906): 	at dalvik.system.NativeStart.run(Native Method)
I/WindowState(  906): WIN DEATH: null
W/PackageSettings(  906): Skipping PackageSetting{422da808 com.example.hello/10356} due to missing metadata
I/ActivityManager(  906): Recipient 4544
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3883
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  906): Client com.google.android.music (pid 3883): Died!
W/InputMethodManagerService(  906): Got RemoteException sending setActive(false) notification to pid 4414 uid 10348
W/Binder  ( 1207): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1207): java.lang.NullPointerException
W/Binder  ( 1207): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1207): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1207): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1207): 	at dalvik.system.NativeStart.run(Native Method)
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
D/DotMatrix( 1559): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1559): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1559): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver replacing:false
W/AccTypeManager( 1328): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1328): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/acms    ( 1881): Unregistering com.test.thalitest
E/acms    ( 1881): Could not unregister removed application com.test.thalitest
W/GeofencerStateMachine( 1422): Ignoring removeGeofence because network location is disabled.
D/PMS     (  906): acquireWL(427411a0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1422 10028 null
D/PMS     (  906): releaseWL(427411a0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/dalvikvm-heap( 4153): Grow heap (frag case) to 15.216MB for 1821008-byte allocation
D/VoicemailCleanupService( 1296): Cleaning up data for package: com.test.thalitest
W/SystemReader( 1255): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/AccTypeManager( 1328): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/Launcher( 1270): Deferring update until onResume
D/Launcher( 1270): waitUntilResume // bindAppsRemoved
I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
D/PackageBroadcastService( 2227): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
E/ExternalAccountType( 1328): Unsupported attribute readOnly
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/ActivityManager(  906): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4767 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
W/Parcel  ( 1255): Reading a NULL string not supported here.
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/MultiDex( 4767): install
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/ActivityManager(  906): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4782 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
D/PhoneApp( 1244): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/MultiDex( 4767): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PeopleContactsSync( 2227): CP2 sync disabled
I/MultiDex( 4767): loading existing secondary dex files
I/MultiDex( 4767): load found 1 secondary dex files
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2227, uid=10028, userID:0
I/MultiDex( 4767): install done
D/PMS     (  906): acquireWL(42106fa8): PARTIAL_WAKE_LOCK  Icing 0x1 2227 10028 null
I/Icing   ( 2227): doRemovePackageData com.test.thalitest
I/ProviderInstaller( 4767): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/MultiDex( 4782): install
I/MultiDex( 4782): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4782): loading existing secondary dex files
I/MultiDex( 4782): load found 1 secondary dex files
I/MultiDex( 4782): install done
D/PMS     (  906): releaseWL(42106fa8): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  906): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/ProviderInstaller( 4782): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  906): Resuming delayed broadcast
I/[PluginManager]RegisterService( 1405): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1405): handle notify Blinkfeed plugin client changed
I/ActivityManager(  906): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4804 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
D/Process (  906): killProcessQuiet, pid=4153
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4153:com.google.android.apps.plus/u0a160 (adj 15): empty for 1802s
I/ActivityManager(  906): Recipient 4153
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/SQLiteDatabase( 4767): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4767): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4767): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4767): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4767): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4767): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4767): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4767): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4767): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4767): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4767): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4767): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4767): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4767): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4767): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4767): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4767): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4767): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4767): threadid=12: thread exiting with uncaught exception (group=0x416e0e30)
E/ActivityManager(  906): App crashed! Process: com.google.android.gms.drive
E/AndroidRuntime( 4767): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4767): Process: com.google.android.gms.drive, PID: 4767
E/AndroidRuntime( 4767): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4767): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4767): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4767): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4767): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4767): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4767): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4767): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4767): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4767): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4767): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4767): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4767): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4767): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4767): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4767): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4767): 	at ctn.run(SourceFile:985)
D/Process ( 4767): killProcess, pid=4767
D/Process ( 4767): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
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
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4804, uid=10073, userID:0
D/Finsky  ( 4804): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (4804/10073)
I/ActivityManager(  906): Recipient 4767
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.google.android.gms.drive (pid 4767) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (4804/10073)
I/TrimMemoryManager( 1270): [trimMemory] 5
D/Finsky  ( 4804): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
D/PMS     (  906): acquireWL(425b0d18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10028}
V/AlarmManager(  906): sending alarm PendingIntent{43800678: PendingIntentRecord{41e75870 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1910736, Int=0
W/Settings( 4804): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 4804): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SQLiteDatabase( 4804): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 4804): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4804): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4804): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4804): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4804): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4804): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4804): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4804): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4804): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4804): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4804): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4804): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4804): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4804): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4804): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/SQLiteDatabase( 4804): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/SQLiteDatabase( 4804): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/SQLiteDatabase( 4804): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 4804): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 4804): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4804): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4804): threadid=25: thread exiting with uncaught exception (group=0x416e0e30)
E/AndroidRuntime( 4804): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime( 4804): Process: com.android.vending, PID: 4804
E/AndroidRuntime( 4804): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4804): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4804): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4804): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4804): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4804): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4804): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4804): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4804): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4804): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4804): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4804): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4804): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4804): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4804): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/AndroidRuntime( 4804): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/AndroidRuntime( 4804): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/AndroidRuntime( 4804): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4804): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4804): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4804): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  906): App crashed! Process: com.android.vending
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4804, uid=10073, userID:0
E/DropBoxManagerService(  906): Can't write: system_app_crash
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
I/ActivityManager(  906): Killing 4177:com.android.settings/1000 (adj 15): empty for 1802s
D/Process (  906): killProcessQuiet, pid=4177
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/Prism.PackageStateRece_( 1270): action: android.intent.action.PACKAGE_REMOVED
D/Process ( 4804): killProcess, pid=4804
I/ActivityManager(  906): Recipient 4177
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  906): Client connection lost with reason: 4
D/Process ( 4804): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.finsky.FinskyApp$CrashHandler.uncaughtException:284 java.lang.ThreadGroup.uncaughtException:693 
I/IcingCorporaProvider( 2895): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  906): Recipient 4804
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.android.vending (pid 4804) has died.
I/ActivityManager(  906): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4839 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/SQLiteLog( 2895): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2895): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x6366bf20
W/dalvikvm( 2895): threadid=14: thread exiting with uncaught exception (group=0x416e0e30)
E/ActivityManager(  906): App crashed! Process: com.google.android.googlequicksearchbox:search
E/AndroidRuntime( 2895): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2895): Process: com.google.android.googlequicksearchbox:search, PID: 2895
E/AndroidRuntime( 2895): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2895): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2895): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2895): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2895): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2895): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2895): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2895): 	at cid.d(PG:186)
E/AndroidRuntime( 2895): 	at clo.g(PG:594)
E/AndroidRuntime( 2895): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2895): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2895): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2895): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2895): 	at clr.tL(PG:827)
E/AndroidRuntime( 2895): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2895): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2895): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2895): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2895): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2895): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 2895): killProcess, pid=2895
E/DropBoxManagerService(  906): Can't write: system_app_crash
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
D/Process ( 2895): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 2895
D/MediaRouterService(  906): Client com.google.android.googlequicksearchbox (pid 2895): Died!
I/ActivityManager(  906): Process com.google.android.googlequicksearchbox:search (pid 2895) has died.
D/WifiService(  906): Client connection lost with reason: 4
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 11000ms
W/PackageManager(  906): Unable to load service info ResolveInfo{42626d30 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1270): loadItems() com.htc.launcher.pageview.WidgetManager@41ba3dd0 +
I/Prism.WidgetManager( 1270): onLoadItems() +
E/SQLiteDatabase( 4839): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4839): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4839): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4839): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4839): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4839): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4839): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4839): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4839): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4839): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4839): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4839): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4839): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4839): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4839): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4839): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4839): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4839): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4839): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4839): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4839): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4839): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4839): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4839): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4839): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4839): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4839): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4839): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4839): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4839): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4839): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4839): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4839): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4839): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4839): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4839): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4839): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4839): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4839): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4839): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4839): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4839): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4839): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4839): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4839): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4839): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4839): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4839): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4839): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4839): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4839): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4839): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4839): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4839): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4839): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4839): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4839): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4839): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4839): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4839): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4839): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4839): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4839): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4839): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4839): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4839): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4839): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4839): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4839): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4839): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4839): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4839): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4839): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4839): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4839): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4839): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4839): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4839): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4839): threadid=11: thread exiting with uncaught exception (group=0x416e0e30)
E/ActivityManager(  906): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4839): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4839): Process: com.google.android.apps.docs, PID: 4839
E/AndroidRuntime( 4839): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4839): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4839): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4839): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4839): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4839): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4839): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4839): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4839): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4839): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4839): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4839): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4839): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4839): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4839): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4839): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4839): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4839): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4839): 	at aho.run(AbstractDatabaseInstance.java:455)
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
D/Process ( 4839): killProcess, pid=4839
D/Process ( 4839): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  906): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4855 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  906): Recipient 4839
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.google.android.apps.docs (pid 4839) has died.

```
