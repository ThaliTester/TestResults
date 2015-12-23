#### Test 54312298af2c956_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  906): Waited long enough for: ServiceRecord{42e7e0d0 u0 com.htc.htclocationservice/.AutoSettingService}
,--------- beginning of /dev/log/main
E/cutils-trace( 4384): Error opening trace file: No such file or directory (2)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/WIFI_ICON( 1116): WifiActivity: 0
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
D/CustomizationManager( 4384): ====startRecUseTime====
D/htc.customization.log.level( 4384):  is 
W/CustomizationLogLevel( 4384): Level value is invalid, use default level 2
D/CustomizationManager( 4384):  Read ACC file spent 0.051 (s)
D/CIDMapFileReader( 4384): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4384): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4384): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4384): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4384): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4384): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4384): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4384): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4384): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4384): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4384): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4384): Parsing tag category name = system
I/CustomizationCIDLoader( 4384): Parsing tag category name = application
I/CustomizationCIDLoader( 4384): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4384): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4384): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4384): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4384): Parsing tag category name = Settings
D/CustomizationManager( 4384):  Read CID file spent 0.090 (s)
D/CustomizationManager( 4384):  All configurations done spent 0.090 (s)
W/HtcNativeFlag( 4384): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4384): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4384): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4384): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  906): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  906): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4384
D/PMS     (  906): acquireHCC(42551890): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 906 1000 null
D/PMS     (  906): acquireHCC(424e4a68): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 906 1000 null
W/asset   (  906): Copying FileAsset 0x67656978 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  906): @test_code: getHtcIntentFlag: 0 obj: 1113057432
I/FeedHostManager( 1271): [onPause]
I/FeedProviderManager( 1271): onPause
I/FeedHostManager( 1271): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41e143a8
I/SocialFeedProvider( 1271): +onPause
D/PMS     (  906): acquireWL(423dc900): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
I/SocialFeedProvider( 1271): -onPause
I/ActivityManager(  906): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4395 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1271): [trimMemory] 20
W/asset   ( 4395): Copying FileAsset 0x5c7e1428 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4395): Binding Chromium to main looper Looper (main, tid 1) {41b602f0}
I/LibraryLoader( 4395): Expected native library version number "",actual native library version number ""
I/chromium( 4395): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4395): Initializing chromium process, renderers=0
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  906): java.lang.Throwable: stack dump
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4247cee8:true
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4395): 1102545280: getState(). Returning 12
D/PMS     (  906): acquireWL(4237f110): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  906): acquireWL(41b6c660): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  906): releaseWL(4237f110): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4395): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4395): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4395): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4395): Local Branch: 
I/Adreno-EGL( 4395): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4395): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4395):                  aa63bbd948f41d15fc72f585e
W/chromium( 4395): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4395): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4395): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4395): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4395): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4395): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4395): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4395): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4395): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4395): CordovaWebView is running on device made by: HTC
,W/AwContents( 4395): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  906): Disable input method client, pid=1271
,W/ResourceType( 4395): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4395): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41ba9830, mServedView=org.apache.cordova.engine.SystemWebView{41b6f498 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1207): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1207): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1207): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1207): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,I/InputMethodManagerService(  906): Enable input method client, pid=4395
W/AwContents( 4395): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  906): Displayed com.test.thalitest/.MainActivity: +265ms
,D/PMS     (  906): releaseWL(423dc900): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4395): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4395): JniHelper::setJavaVM(0x41638048), pthread_self() = 1663004552
,D/JX-Cordova( 4395): jxcore cordova android initializing
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/dalvikvm-heap( 4395): Grow heap (frag case) to 11.550MB for 96598-byte allocation
,I/dalvikvm-heap( 4395): Grow heap (frag case) to 11.630MB for 144892-byte allocation
,I/dalvikvm-heap( 4395): Grow heap (frag case) to 11.746MB for 217334-byte allocation
,I/dalvikvm-heap( 4395): Grow heap (frag case) to 11.922MB for 325996-byte allocation
,I/dalvikvm-heap( 4395): Grow heap (frag case) to 12.197MB for 488990-byte allocation
,I/dalvikvm-heap( 4395): Grow heap (frag case) to 13.204MB for 1100216-byte allocation
,I/dalvikvm-heap( 4395): Grow heap (frag case) to 14.084MB for 1650320-byte allocation
,W/PluginManager( 4395): THREAD WARNING: exec() call to JXcore.isReady blocked the main thread for 26ms. Plugin should use CordovaInterface.getThreadPool().
,I/dalvikvm-heap( 4395): Grow heap (frag case) to 15.463MB for 2475476-byte allocation
,D/WIFI_ICON( 1116): WifiActivity: 0
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/dalvikvm-heap( 4395): Grow heap (frag case) to 17.502MB for 3713210-byte allocation
,W/jxcore-log( 4395): Initializing JXcore engine
,W/jxcore-log( 4395): JXcore engine is ready
,W/CpuWake (  906): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  906): <<release mCpuPerf_Freq wakelock
D/PMS     (  906): releaseHCC(42551890): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  906): releaseHCC(424e4a68): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4395): Starting JXcore engine
D/PMS     (  906): acquireWL(42096010): PARTIAL_WAKE_LOCK  Icing 0x1 1226 10028 null
,D/PMS     (  906): releaseWL(42096010): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(425a0b20): PARTIAL_WAKE_LOCK  Icing 0x1 1226 10028 null
,D/PMS     (  906): releaseWL(425a0b20): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(420cd000): PARTIAL_WAKE_LOCK  Icing 0x1 1226 10028 null
,D/PMS     (  906): releaseWL(420cd000): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(425b2620): PARTIAL_WAKE_LOCK  Icing 0x1 1226 10028 null
,D/PMS     (  906): releaseWL(425b2620): PARTIAL_WAKE_LOCK  Icing 0x1 null
,W/jxcore-log( 4395): Platform android
W/jxcore-log( 4395): 
,W/jxcore-log( 4395): Process ARCH arm
W/jxcore-log( 4395): 
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/SensorManager(  906): mEventCount = 1350
,I/jxcore-log( 4395): JXcore Cordova bridge is ready!
I/jxcore-log( 4395): 
,W/jxcore-log( 4395): JXcore engine is started
,I/chromium( 4395): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PMS     (  906): releaseWL(41b6c660): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/ActivityManager(  906): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4443 uid=10077 gids={50077}
,D/PMS     (  906): acquireWL(426c3e50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10077}
,V/AlarmManager(  906): sending alarm PendingIntent{426a5070: PendingIntentRecord{4207efc8 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1450836486320, Int=60000
,D/PMS     (  906): releaseWL(426c3e50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4443): SMSBackupAgentService started
,D/SMSBackup( 4443): Checking restore status
D/SMSBackup( 4443): Restore complete
,D/SMSBackup( 4443): cancelCheckAlarm
,D/SMSBackup( 4443): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  906): killProcessQuiet, pid=3156
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3156:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3156
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/PMS     (  906): acquireWL(4405f8e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=55 rxSum=42} preTxRxSum={txSum=53 rxSum=40}
D/WifiDataStallTracker(  906): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  906): onDataStallAlarm: tag=19517 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=19518 delay=15s
V/AlarmManager(  906): sending alarm PendingIntent{4255f698: PendingIntentRecord{425ca158 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=104938, Int=0
D/PMS     (  906): releaseWL(4405f8e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4395): Toggling radios to true
I/jxcore-log( 4395): 
,D/BluetoothAdapter( 4395): enable(): BT is already enabled..!
,D/WifiManager( 4395): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  906): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 2
W/Settings:Agent(  906): >> traceCallingStack()
W/Settings:Agent(  906): Process.myPid(): 906
W/Settings:Agent(  906): Process.myTid(): 1101
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
W/System.err(  906): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  906): 
,W/Settings:Agent(  906): << traceCallingStack(): 1(ms)
D/WifiManager( 4395): disconnect: Base Package Name=com.test.thalitest, uid=10348
D/WifiNative-wlan0(  906): doBoolean: DISCONNECT
,D/WifiManager( 4395): reconnect: Base Package Name=com.test.thalitest, uid=10348
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1156): TDLS: Tear down peers
,I/wpa_supplicant( 1156): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4395): Radios toggled
I/jxcore-log( 4395): 
,D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiService(  906): New client listening to asynchronous messages
D/WifiService(  906): setWifiEnabled: true pid=4395, uid=10348
E/WifiService(  906): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  906): isSprintWifiRestricted(): false
I/WifiService(  906): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  906): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
I/jxcore-log( 4395): Got Device Bluetooth address: 80:01:84:8A:B3:68
I/jxcore-log( 4395): 
I/jxcore-log( 4395): Perf Test app loaded loaded
I/jxcore-log( 4395): 
I/jxcore-log( 4395): check test folder
I/jxcore-log( 4395): 
I/jxcore-log( 4395): found test : ./testFindPeers.js
I/jxcore-log( 4395): 
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1156): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1156): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1156): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  906): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  906): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
,D/HTCRequest(  906): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1156): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1156): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
E/wpa_supplicant( 1156): send_and_recv error -67 - cmd 12
D/WifiMonitor(  906): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1156): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/Tethering(  906): [isWifi] getHotspotEnabled: false
E/wpa_supplicant( 1156): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1156): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1156): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1156): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1156): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1156): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb84b9bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1156):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1156): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1156): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1156): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1156): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1156): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1156): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1156): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1156): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1156): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1156): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1156): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1156): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1156): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1156): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1156): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1156): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1156): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1156): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1156): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 18
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1156): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1156): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1156): netlink: Operstate: linkmode=-1, operstate=5
D/Tethering(  906): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1156): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1156): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1156): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1156): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1156): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1156): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1156): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1156): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 18
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 1156): RTM_NEWLINK: operstate=0 ifi_flags=0x1,003 ([UP])
D/wpa_supplicant( 1156): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1156): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1156): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1156): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1156): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1156): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1156): nl80211: Event message available
D/wpa_supplicant( 1156): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1156): nl80211: Ignore disconnect event triggered during reassociation
D/WifiNative-wlan0(  906):    returned true
I/jxcore-log( 4395): found test : ./testSendData.js
I/jxcore-log( 4395): 
D/WifiPerfLock(  906): release()
D/WifiStateMachine(  906): PerfLock released for exiting ConnectedState
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1156): Power_Mode_Type mode = 0
I/wpa_supplicant( 1156): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 61
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0(  906):    returned true
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  906): acquireWL(424a4210): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 906 1000 null
D/wpa_supplicant( 1156): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  906):    returned true
,D/DhcpStateMachine(  906): [RunningState] Stop DHCP
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiNative-wlan0(  906): doBoolean: RECONNECT
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1156): Fast associate: Old scan results
D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=19518 mDataStallAlarmIntent=PendingIntent{43ff33f8: PendingIntentRecord{425ca158 android broadcastIntent}}
I/wpa_supplicant( 1156): wpa_supplicant_scan enter
I/wpa_supplicant( 1156): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1156): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1156): wpa_supplicant_trigger_scan +
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiP2pService(  906): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID,
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 33
,I/wpa_supplicant( 1156): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1156): nl80211: Event message available
D/wpa_supplicant( 1156): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): Enter handleNetworkDisconnect
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0,
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1156): Power_Mode_Type mode = 0
I/wpa_supplicant( 1156): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1156): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  906):    returned true
,D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  906): Provision feature enable=false
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  906): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1844/10178)
D/WifiP2pService(  906): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/UsbnetStateTracker(  906): isAvailable+-
D/UsbnetStateTracker(  906): reconnect
D/UsbnetStateTracker(  906): isAvailable+-
,D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WISPrService( 4181): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  906): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  906): default: reconnect()
D/MDST    (  906): default: setTeardownRequested(false)
D/MDST    (  906): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  906): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  906): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WISPrService( 4181): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  906): Exit handleNetworkDisconnect
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
D/ConnectivityService(  906): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  906): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiService(  906): New client listening to asynchronous messages
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): handleConnectivityChange: resetting
,D/ConnectivityService(  906): resetConnections(wlan0, 3)
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/PMS     (  906): acquireWL(41f97db8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1366 10028 null
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,I/jxcore-log( 4395): found test : ./testSendData2.js
I/jxcore-log( 4395): 
D/libc    (  364): [NET] entry_id:5   entry:0xb8b1ffd8  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb8b20310  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb8b20428  removed 
D/libc    (  364): [NET] entry_id:6   entry:0xb8b20240  removed 
D/libc    (  364): [NET] entry_id:3   entry:0xb8b200e8  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb8b250b0  removed 
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
,D/WISPrService( 4181): >>>>>WISPrService start isConnected = false<<<<<
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1844/10178)
D/ConnectivityService(  906): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
,D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 4181): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:1
,D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WifiStateMachine(  906): startScan Pid: 906 Uid 1000
D/PMS     (  906): acquireWL(43232330): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  906): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/PMS     (  906): acquireWL(436fbb30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10028 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1366/10028)
D/ConnectivityService(  906): reportInetCondition for net -1, percentage: 0 by  (1366/10028)
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,D/WifiNative-wlan0(  906): doBoolean: SCAN
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
D/PMS     (  906): releaseWL(41f97db8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1366/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1366/10028)
D/PMS     (  906): releaseWL(436fbb30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/BatSI   (  906): WIFI scan started for: 650a0300 uid:1000
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1156): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  906):    returned false
D/PMS     (  906): releaseWL(43232330): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  906): mActiveDefaultNetwork: -1
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:0
D/ConnectivityService(  906): handleInetConditionChange: no active default network - ignore
,I/Choreographer( 4395): Skipped 88 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4395): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: false
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
D/PMS     (  906): acquireWL(4405a678): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/GpsLocationProvider(  906): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
D/Tethering(  906): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  906): bSetPropertyMultiRAB:false
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
D/CaptivePortalTracker(  906): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false,
D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
D/CaptivePortalTracker(  906): NoActiveNetworkState,
I/Tethering(  906): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  906): ipv4Default null,
I/Tethering(  906): No IPv4 upstream interface, giving up.
,D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
,I/NetworkMonitor( 3844): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): releaseWL(4405a678): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1887/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1404/10028)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1271/10075)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3844/10154)
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4285/10100)
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,I/ConnectivityHelper( 1271): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1844/10178)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4285/10100)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (2422/10021)
,I/ActivityManager(  906): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4467 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4467): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4467): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4467): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4467): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4467): Preparing secondary program dexes.
V/DexLibLoader( 4467): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4467): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4467): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4467): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4467): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4467): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
,V/DexLibLoader( 4467): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4467): Dex already copied
D/OdexVerifier( 4467): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4467): Creating class loader
,V/DexLibLoader( 4467): Finished creating class loader
V/DexLibLoader( 4467): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4467): Dex already copied
D/OdexVerifier( 4467): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4467): Creating class loader
,V/DexLibLoader( 4467): Finished creating class loader
V/DexLibLoader( 4467): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4467): Dex already copied
D/OdexVerifier( 4467): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4467): Creating class loader
,V/DexLibLoader( 4467): Finished creating class loader
V/DexLibLoader( 4467): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar,
V/DexLibLoader( 4467): Dex already copied
D/OdexVerifier( 4467): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4467): Creating class loader
V/DexLibLoader( 4467): Finished creating class loader,
,V/DexLibLoader( 4467): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4467): DexLibLoader.ensureDexLoaded took 24 ms
,W/dalvikvm( 4467): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4467): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4467): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4467): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4467): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4467): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4467): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4467): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1156): nl80211: Event message available
D/wpa_supplicant( 1156): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1156): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1156): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1156): nl80211: Survey data missing
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1156): Sorted scan results
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-47
I/wpa_supplicant( 1156): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1156): [NULL] fc:94:e3:11:35:3a freq=2462 level=-87
I/wpa_supplicant( 1156): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-88
I/wpa_supplicant( 1156): [NULL] fe:94:e3:11:35:3c freq=2462 level=-88
D/wpa_supplicant( 1156): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1156): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1156): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1156): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1156): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1156): Add randomness: count=10 entropy=4
D/wpa_supplicant( 1156): Add randomness: count=11 entropy=5
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1156): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1156): wpa_supplicant_pick_network+
I/wpa_supplicant( 1156): Selecting BSS from priority group 1
I/wpa_supplicant( 1156): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1156): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1156): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1156): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1156):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1156):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-47
I/wpa_supplicant( 1156): Start print parameters
I/wpa_supplicant( 1156): wpa_s->wpa_state is 3
I/wpa_supplicant( 1156): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1156): isConcurrentMode() is 0
I/wpa_supplicant( 1156): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1156): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1156): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1156): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1156): wpa_s->reassociate is 1
I/wpa_supplicant( 1156): wpa_s->is_screen_on 1
I/wpa_supplicant( 1156): wpa_s->ifname wlan0
I/wpa_supplicant( 1156): End print parameters
I/wpa_supplicant( 1156): selected network = 1
D/wpa_supplicant( 1156): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb84bb4e8  current_ssid=0x0
D/wpa,_supplicant( 1156): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1156): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1156): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1156): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1156): check if in concurrent case
,I/wpa_supplicant( 1156): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1156): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1156): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1156): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1156): RSN: PMKSA cache search - network_ctx=0xb84bb4e8 try_opportunistic=0
D/wpa_supplicant( 1156): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1156): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1156): State: SCANNING -> ASSOCIATING
W/dalvikvm( 4467): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
D/wpa_supplicant( 1156): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1156): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1156): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1156): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1156): nl80211: Unsubscribe mgmt frames handle 0xb84ba718 (mode change)
D/wpa_supplicant( 1156): nl80211: Subscribe to mgmt frames with non-AP handle 0xb84ba718
D/wpa_supplicant( 1156): nl80211: Register frame type=0xd0 nl_handle=0xb84ba718
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1156): nl80211: Register frame type=0xd0 nl_handle=0xb84ba718
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1156): nl80211: Register frame type=0xd0 nl_handle=0xb84ba718
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1156): nl80211: Register frame type=0xd0 nl_handle=0xb84ba718
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1156): nl80211: Register frame type=0xd0 nl_handle=0xb84ba718
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1156): nl80211: Register frame type=0xd0 nl_handle=0xb84ba718
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1156): nl80211: Register frame type=0xd0 nl_handle=0xb84ba718
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1156): nl80211: Register frame type=0xd0 nl_handle=0xb84ba718
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1156): nl80211: Register frame type=0xd0 nl_handle=0xb84ba718
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1156): nl80211: Register frame type=0xd0 nl_handle=0xb84ba718
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1156): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1156):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1156):   * freq=2412
D/wpa_supplicant( 1156):   * Auth Type 0
D/wpa_supplicant( 1156):   * WPA Versions 0x2
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1156): nl80211: Connect request send successfully
D/wpa_supplicant( 1156): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1156): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1156): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1156): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1156): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1156): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1156): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1156): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1156): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 18
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES,
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0,
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
,D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1156): reply (764) for get BSS: id=0
I/wpa_supplicant( 1156): bssid=c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1156): freq=5220
I/wpa_supplicant( 1156): level=-48
I/wpa_supplicant( 1156): tsf=0000000107341216
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=NG7005g
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=1
I/wpa_supplicant( 1156): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-47
I/wpa_supplicant( 1156): tsf=0000000107341233
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=NG700
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=2
I/wpa_supplicant( 1156): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1156): freq=2437
I/wpa_supplicant( 1156): level=-88
I/wpa_supplicant( 1156): tsf=0000000107341245
I/wpa_supplicant( 1156): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=UPC4688432
I/wpa_supplicant( 1156): ====
,I/wpa_supplicant( 1156): id=3
I/wpa_supplicant( 1156): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-48
I/wpa_supplicant( 1156): tsf=0000000107341228
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1156): ssid=01ABC
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=4
I/wpa_supplicant( 1156): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1156): freq=2462
I/wpa_supplicant( 1156): level=-87
I/wpa_supplicant( 1156): tsf=0000000107341241
I/wpa_supplicant( 1156): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1156): ssid=UPC0039325
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=5
I/wpa_supplicant( 1156): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1156): freq=2462
I/wpa_supplicant( 1156): level=-88
I/wpa_supplicant( 1156): tsf=0000000107341238
I/wpa_supplicant( 1156): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1156): ssid=UPC Wi-Free
I/wpa_supplicant( 1156): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (6) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 107341216, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 2412, timestamp: 107341233, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -88, frequency: 2437, timestamp: 107341245, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -48, frequency: 2412, timestamp: 107341228, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -87, frequency: 2462, timestamp: 107341241, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 107341238, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 6 to mScanResults
D/BatSI   (  906): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,E/FbInjectorInitializer( 4467): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/wpa_supplicant( 1156): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1156): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1156): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 1156): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1156): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1156): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1156): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1156): nl80211: Event message available
D/wpa_supplicant( 1156): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1156): nl80211: Connect event
D/wpa_supplicant( 1156): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1156): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1156): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1156): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1156): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1156): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1156): Add randomness: count=12 entropy=6
I/wpa_supplicant( 1156): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1156): TDLS: Remove peers on association
D/wpa_supplicant( 1156): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1156): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1156): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1156): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1156): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1156): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1156): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1156): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1156): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1156): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1156): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1156): EAPOL: enable timer tick
D/wpa_supplicant( 1156): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1156): htc_wext_set_keepalive +
I/wpa_supplicant( 1156): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1156): getPrivFuncNum +	
I/wpa_supplicant( 1156): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1156): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1156): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1156): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1156): Get randomness: len=32 entropy=7
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  906): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  906): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  906): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/WifiMonitor(  906): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  906): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  906): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  906): Enter handleAssociatedWithEvent
,D/WifiStateMachine(  906): Associated
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  906): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  906): Exit handleAssociatedWithEvent
,D/Tethering(  906): interfaceLinkStateChanged wlan0, true
D/WifiStateMachine(  906): BSSID was changed, update WiFi database
D/Tethering(  906): interfaceStatusChanged wlan0, true
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
I/wpa_supplicant( 1156): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1156): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb84ba9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1156):    addr=c0:ff:d4:d3:aa:48
D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1156): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1156): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1156): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f14b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1156):    broadcast key
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 11
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1156): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1156): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1156): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1156): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1156): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
I/wpa_supplicant( 1156): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  906): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1156): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1156): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1156): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1156): set send_ind_to_ndc = 0
I/wpa_supplicant( 1156): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1156): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1156): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1156): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1156): EAPOL: SUPP_PAE entering state AUTHENTICATING
,D/wpa_supplicant( 1156): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1156): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1156): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1156): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1156): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1156): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1156): EAPOL authentication completed successfully
I/wpa_supplicant( 1156): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1156): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1156): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1156): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  906): This record is existed, only update it...
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
,D/Tethering(  906): interfaceStatusChanged wlan0, true
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/WifiStateMachine(  906): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiStateMachine(  906): This record is existed, only update it...
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/WISPrService( 4181): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4181): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/DhcpStateMachine(  906): [StoppedState] Start DHCP
D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1156): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1156): Power_Mode_Type mode = 1
I/wpa_supplicant( 1156): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  906):    returned null
E/WifiStateMachine(  906): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING STOP
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  906):    returned null
D/WifiStateMachine(  906): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  906): acquireWL(42a0be68): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 906 1000 null
D/WifiStateMachine(  906): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  906): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42554190 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-3ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42554190 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:0
,W/fb4a(:<default>):StaticBindingVerifier( 4467): Verify
,D/WifiService(  906): New client listening to asynchronous messages
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4467): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4467): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4467): Grow heap (frag case) to 9.511MB for 73240-byte allocation
,D/Process (  906): killProcessQuiet, pid=4226
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 4226:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,D/PMS     (  906): acquireWL(435e91f8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1226 10028 null
,I/ActivityManager(  906): Recipient 4226
D/WifiService(  906): Client connection lost with reason: 4
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(4401cf30): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1226 10028 null
,D/PMS     (  906): releaseWL(435e91f8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1366): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1366/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1366/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1366/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,D/PMS     (  906): releaseWL(4401cf30): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/AutoSetting( 1434): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  906): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4496 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1434/10053)
,D/AutoSetting( 1434): Util - no network available!
,D/AutoSetting( 1434): service - onCreate()
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1434/10053)
D/AutoSetting( 1434): service - AddressCache: using context: com.htc.Weather
D/LocationManagerService(  906): request 42616870 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/LocationManagerService(  906): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1434): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1434): service - mHandler: cancel location update
D/AutoSetting( 1434): service -           changes count: 0
,W/fb4a(:<default>):UserScope( 4467): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4467): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/MobileConnectivityChangeReceiver( 4496): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4496): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4496): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4496): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,W/fb4a(:<default>):UserScope( 4467): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,I/ActivityManager(  906): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4512 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4496/10078)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4496/10078)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4496/10078)
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4467): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  906): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4529 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=3827
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/ActivityManager(  906): Killing 3827:com.htc.mediamanager/u0a32 (adj 15): empty #17
E/dalvikvm( 4467): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
W/dalvikvm( 4467): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4467): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 4467): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4467): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 4467): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4467): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4467): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4467): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4467): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4467): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/dalvikvm( 4467): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4467): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4467): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4467): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4467): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4467): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4467): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
I/ActivityManager(  906): Recipient 3827
,I/dalvikvm-heap( 4467): Grow heap (frag case) to 9.924MB for 39954-byte allocation
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4529): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4529): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4529): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4529): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4529): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/dalvikvm-heap( 4467): Grow heap (frag case) to 10.000MB for 79892-byte allocation
,I/dalvikvm-heap( 4467): Grow heap (frag case) to 10.067MB for 84664-byte allocation
,I/dalvikvm-heap( 4467): Grow heap (frag case) to 10.094MB for 28144-byte allocation
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4529/10151)
,V/WebViewChromiumFactoryProvider( 4529): Binding Chromium to main looper Looper (main, tid 1) {41b67360}
,I/LibraryLoader( 4529): Expected native library version number "",actual native library version number ""
,I/chromium( 4529): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4529): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4529): BLUETOOTH permission is missing!
D/PMS     (  906): acquireWL(44054e50): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  906): acquireWL(425eda80): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  906): releaseWL(44054e50): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4529): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4529): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4529): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4529): Local Branch: 
I/Adreno-EGL( 4529): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4529): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4529):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4529): Starting up...
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4529/10151)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4529/10151)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4156/10160)
,I/dalvikvm-heap( 4467): Grow heap (frag case) to 10.281MB for 75760-byte allocation
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4156/10160)
,D/Process (  906): killProcessQuiet, pid=4000
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 4000:com.google.android.gm/u0a107 (adj 15): empty #17
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1844/10178)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1844/10178)
,D/GCM     ( 1366): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43183bc0 u0 ReceiverList{43183aa0 4467 com.facebook.katana/10026/u0 remote:43174728}}
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43183bc0 u0 ReceiverList{43183aa0 4467 com.facebook.katana/10026/u0 remote:43174728}}
,W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{436523b8 u0 ReceiverList{43652358 4467 com.facebook.katana/10026/u0 remote:43516430}}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/PMS     (  906): acquireWL(43cb5ef0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1404 10028 null
,D/PMS     (  906): releaseWL(43cb5ef0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  906): acquireWL(4315ee88): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1404 10028 null
D/GCoreFlp( 1404): Unknown pending intent to remove.
D/wpa_supplicant( 1156): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1156): EAPOL: disable timer tick
D/PMS     (  906): releaseWL(4315ee88): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/ActivityManager(  906): Recipient 4000
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4467): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4467): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
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
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1156): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1156): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/WifiP2pService(  906): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1156): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): handlePostDhcpSetup release wake lock during DHCP
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(42a0be68): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WIFI_ICON( 1116): updateWifiState: RSSI_CHANGED -1 -> 3
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): gateway: /192.168.1.1
,D/WifiNative-wlan0(  906): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1156): WiFi gateway: 0x101a8c0
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  906): VerifyingLinkState enter
D/WifiStateMachine(  906): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  906): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  906): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -47, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/WifiDataStallTracker(  906): startDataStallAlarm: tag=19520 delay=15s
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiWatchdogStateMachine(  906): WAN detection
V/NetworkPolicy(  906): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  906): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  906): default: teardown()
D/MDST    (  906): default: setTeardownRequested(true)
,D/MDST    (  906): default: setEnableApn apnType =default , enable=false
D/WISPrService( 4181): >>>>>WISPrService start isConnected = true<<<<<
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/MDST    (  906): default: setTeardownRequested(true)
D/ConnectivityService(  906): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1844/10178)
E/ConnectivityService(  906): Unexpected mtu value: android.net.wifi.WifiStateTracker@42490d18
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=false resetMask=0
,D/WIFI_ICON( 1116): WifiActivity: 1
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  906): syncGetConfiguredNetworks
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/ConnectivityService(  906): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  906): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  906): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  906): sendGeneralBroadcastDelayed, restrictEnable=false
,D/PMS     (  906): acquireWL(4319faa8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
,I/QuickSettingWifi( 1116): receive.wifiConnect:true wifiAPname:NG700 elapse:2
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4496/10078)
,D/WirelessDisplayService(  906): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,D/WirelessDisplayService(  906):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [3][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/PMS     (  906): acquireWL(43218b20): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1226 10028 null
D/PMS     (  906): releaseWL(4319faa8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  906): acquireWL(42646a98): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1226 10028 null
D/PMS     (  906): releaseWL(43218b20): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
,I/CheckinService( 1226): Preparing to send checkin request
,I/EventLogService( 1226): Accumulating logs since 1450836436447
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
I/GoogleHttpClient( 1226): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1226): Using GMS GoogleHttpClient
,D/ConnectivityService(  906): mActiveDefaultNetwork: WIFI
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (1226/10028)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (1226/10028)
,W/GLSUser ( 1366): GoogleAccountDataService.getToken()
,W/GLSActivity( 1366): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1366): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1366): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1604): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1604): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 1226): awaiting user notification for token
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41b88768 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.google.android.gms 1 8 2 12
,I/ActivityManager(  906): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4606 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 4606): install
,I/MultiDex( 4606): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4606): loading existing secondary dex files
,I/MultiDex( 4606): load found 1 secondary dex files
,I/MultiDex( 4606): install done
,I/ProviderInstaller( 4606): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1366): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/dalvikvm( 4395): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4395): threadid=1: thread exiting with uncaught exception (group=0x41730e30)
,E/ActivityManager(  906): App crashed! Process: com.test.thalitest
E/AndroidRuntime( 4395): FATAL EXCEPTION: main
E/AndroidRuntime( 4395): Process: com.test.thalitest, PID: 4395
E/AndroidRuntime( 4395): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4395): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4395): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4395): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4395): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4395): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4395): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4395): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4395): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4395): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4395): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4395): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4395): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4395): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4395): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4395): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4395): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4395): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4395): 	at dalvik.system.NativeStart.main(Native Method)
W/ActivityManager(  906):   Force finishing activity com.test.thalitest/.MainActivity
I/ActivityManager(  906): mThumbnailWidth=360, mThumbnailHeight=640
,D/PMS     (  906): acquireWL(43508078): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
,W/asset   (  906): Copying FileAsset 0x6b4084c0 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,I/PMS     (  906): Going to sleep due to screen timeout...
,W/PMS     (  906): mWirelessDisplayManager is null
,D/WirelessDisplayService(  906): Screen File Receiver; callOnGoing: false, Screen On: false
I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421f9fe8
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,W/SensorService(  906): disable: get sensor name = CM36282 Light sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421f9fe8, eanble = 0, strlen(mName) = 59
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4211f738
W/SensorService(  906): Listener[1] = com.htc.smartdim.sensor_eye@42392130
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/BatSI   (  906): Couldn't get kernel wake lock stats
V/LightsService(  906): setLight #2: color=#0
D/qdlights(  906): set_light_buttons_func: on=0 brightness=0
V/LightsService(  906): setLight #0: color=#0
,I/Adreno-EGL( 4606): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4606): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4606): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4606): Local Branch: 
I/Adreno-EGL( 4606): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4606): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4606):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4606): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4606): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4606): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4606): Local Branch: 
I/Adreno-EGL( 4606): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4606): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4606):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (4606/10028)
,D/WIFI_ICON( 1116): WifiActivity: 3
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  906): releaseWL(424a4210): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  906): NetTransition Wakelock for ConnectedState released by timeout
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  906): bSetPropertyMultiRAB:false
,D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/acms    ( 1887): Checking Certificates
I/acms    ( 1887): Checking Developer Certificates
I/acms    ( 1887): Checking Application Certificates
I/acms    ( 1887): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1887): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
,I/acms    ( 1887): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1887): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1887): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1887): Updating next query delay: 75600000
I/mlserverapp( 1887): MirrorLink is never connected, don't setup ACMS programed checks
I/mlserverapp( 1887): cancelACMSProgrammedChecks
D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  906): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: true
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1887/1000)
D/PMS     (  906): acquireWL(42d14178): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3844/10154)
D/PMS     (  906): releaseWL(42d14178): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
I/NetworkMonitor( 3844): type=WIFI subType= reason=null isConnected=true
I/Tethering(  906): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  906): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  906): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  906): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  906): Found interface wlan0
D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
I/ConnectivityHelper( 1271): [onReceive] WIFI(1): CONNECTED
D/CaptivePortalTracker(  906): NoActiveNetworkState
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4496/10078)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1271/10075)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1844/10178)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4285/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1404/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.musicenhancer (3878/10051)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4285/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42503178): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (2422/10021)
D/PMS     (  906): releaseWL(42503178): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(43af0488): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1226 10028 null
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(43af0488): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiStateMachine(  906): BroadcastRSSIForIMS, newrssi =-48 , oldRssi= -200
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
,D/GCM     ( 1366): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/WIFI_ICON( 1116): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1366/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1366/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1366/10028)
,D/libc    ( 1366): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1366): [NET] getaddrinfo-,err=8
D/libc    ( 1366): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1366): [NET] getaddrinfo-, 1
,D/libc    ( 1366): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =58e7 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/AutoSetting( 1434): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/PMS     (  906): acquireWL(426d0fd8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1366 10028 null
D/MobileConnectivityChangeReceiver( 4496): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4496): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1434): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1434): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 1434): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1434): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1434/10053)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4529/10151)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1434/10053)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4156/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4156/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1844/10178)
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 217
D/libc    (  364): [NET]res_nsend:resplen=79
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1366): [NET] getaddrinfo_proxy-, success
,W/ActivityManager(  906): Activity pause timeout for ActivityRecord{41f9f710 u0 com.test.thalitest/.MainActivity t2 f}
,D/libc    ( 1366): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1366): [NET] getaddrinfo-,err=8
,D/SurfaceControl(  906): Excessive delay in blankDisplay() while turning screen off: 392ms
D/PMS     (  906): nativeSetInteractive:false
D/PMS     (  906): nativeSetInteractive:false done
D/PMS     (  906): nativeSetAutoSuspend:true
D/PMS     (  906): nativeSetAutoSuspend:true done
,D/PMS     (  906): acquireWL(430cab28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(430cab28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HABCtrl (  906): TPE algorithm. remove timeout.
,D/PMS     (  906): OOBE c monitor 11
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1366/10028)
I/InputMethodManagerService(  906): screenObserver, isScreenOn=false
,I/InputMethodManagerService(  906): Disable input method client, pid=4395
,D/NfcService( 1255): ScreenObserver: OFF
,D/NfcService( 1255): applyRouting - 0
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=99
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/NfcService( 1255): applyRouting -2
D/DotMatrix( 1604): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1604): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,V/KeyguardServiceDelegate(  906): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@424f6ff8)
D/PMS     (  906): acquireWL(43d27868): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10028 null
D/PMS     (  906): acquireWL(43f998a8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1255 1027 null
D/PMS     (  906): releaseWL(43d27868): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/PMS     (  906): releaseWL(43f998a8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/KeyguardServiceDelegate(  906): **** SHOWN CALLED ****
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMN     (  906): wakingUp
I/WindowManager(  906): No lock screen! windowToken=null
I/InputManager(  906): Cancel all due to getting PMS screen off broadcast
D/PMN     (  906): onScreenOn
,I/IntentController( 1116): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
I/FeedHostManager( 1271): [onResume]
I/FeedProviderManager( 1271): onResume
I/SocialFeedProvider( 1271): +onResume
I/SocialFeedProvider( 1271): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1271): -onResume
D/WirelessDisplayService(  906): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.launcher (1271/10075)
I/HtcPowerSaver(  906): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
D/NfcService( 1255): applyRouting - 0
,D/MtpService( 2422): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2422): [MTP][onReceive]-
D/NfcService( 1255): applyRouting -2
,D/AutoSetting( 1434): receiver - intent: android.intent.action.USER_PRESENT
D/AlarmManager(  906): ACTION_SCREEN_ON
I/AlarmManager(  906): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done recovering
I/AlarmManager(  906): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  906): acquireWL(4263d010): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1255 1027 null
D/PMS     (  906): releaseWL(4263d010): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/NotificationService(  906): batLight: plugged
V/LightsService(  906): setLight #8: color=#c8c800
,D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c80000
D/qdlights(  906): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
,D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=19521 delay=15s
,I/BatteryController( 1116): status:2 level:99 unsupport:false plugged:true
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1156): SET_SCREEN_ON:On
I/wpa_supplicant( 1156): htc_wext_set_keepalive +
I/wpa_supplicant( 1156): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1156): getPrivFuncNum +	
I/wpa_supplicant( 1156): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1156): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1156): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1156): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1156): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  906):    returned true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
,D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AutoSetting( 1434): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [6][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/WifiNative-wlan0(  906):    returned true
,D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
V/NotificationService(  906): batLight: plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c80000
D/qdlights(  906): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WIFI_ICON( 1116): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
D/TetherSettings( 4181): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4181): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4181): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4181): Cust_ConnectToPC   : spcsc>false
D/        ( 4181): Cust_ConnectToPC   : IPT>true
D/        ( 4181): Cust_ConnectToPC   : Singel_USB>false
,I/ClockThread( 1116): stop update clock
,D/NetworkPolicy(  906): updateScreenOn: false
W/Settings( 4181): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
E/SmartNS_Utility( 4181): hasRemovableStorageSlot: true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/SmartNS_Utility( 4181): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4181): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [1][0][0]
,D/GCM     ( 1366): Connected
,I/PSReceiver( 4181): onReceive:android.intent.action.USER_PRESENT
D/PMS     (  906): acquireWL(431a0580): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1366 10028 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1366/10028)
W/ContextImpl( 4181): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/SmartNS_PSService( 4181): onReceive:android.intent.action.USER_PRESENT
,W/Settings( 4181): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4181):  defaultType:0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1366/10028)
D/PMS     (  906): releaseWL(426d0fd8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1366/10028)
D/PMS     (  906): releaseWL(43508078): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1366/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1366/10028)
D/PMS     (  906): releaseWL(431a0580): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  906): acquireWL(431744c0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1366 10028 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,W/fb4a(:<default>):UserScope( 4467): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4467): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4650 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  906): killProcessQuiet, pid=4255
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
,D/DotMatrix( 1604): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/ActivityManager(  906): Killing 4255:com.google.android.partnersetup/u0a31 (adj 15): empty #17
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1366/10028)
,I/Adreno-EGL( 4606): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4606): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4606): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4606): Local Branch: 
I/Adreno-EGL( 4606): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4606): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4606):                  aa63bbd948f41d15fc72f585e
,W/Settings( 4606): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/ActivityManager(  906): Recipient 4255
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1366/10028)
,D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/GCM     ( 1366): Message class mpf
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=100 [1][1][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1366/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1366/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/PMS     (  906): acquireWL(431ae608): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1404 10028 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1366/10028)
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1803): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1803): onScreenOn: 1450836493236
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1803): onScreenOn: 1450836493236
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(431ae608): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4211f738
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4211f738, eanble = 0, strlen(mName) = 91
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  906): Listener[0] = com.htc.smartdim.sensor_eye@42392130
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMS     (  906): releaseWL(431744c0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
W/ContextImpl( 4650): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  906): acquireWL(440a5de8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10028 null
D/PMN     (  906): goingToSleep
I/FeedHostManager( 1271): [onPause]
I/FeedProviderManager( 1271): onPause
I/SocialFeedProvider( 1271): +onPause
I/SocialFeedProvider( 1271): -onPause
D/PMS     (  906): releaseWL(440a5de8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  906): acquireWL(43fdff80): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 906 1000 null
I/FeedHostManager( 1271): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41e143a8
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/SmartSyncUtils( 4650): isEpsOn(), nState = 0
D/PMS     (  906): releaseWL(43fdff80): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/AlarmManager(  906): ACTION_SCREEN_OFF
I/AlarmManager(  906): [AlarmQueuing] screen off now: 
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=19521 mDataStallAlarmIntent=PendingIntent{42398e30: PendingIntentRecord{425ca158 android broadcastIntent}}
I/AlarmManager(  906): [AlarmQueuing] data connection: true
I/AlarmManager(  906): [AlarmQueuing] wifi connection: true
D/PMS     (  906): acquireWL(4404b2a8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4650 1000 null
,D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1156): SET_SCREEN_ON:Off
I/wpa_supplicant( 1156): htc_wext_set_keepalive +
I/wpa_supplicant( 1156): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1156): getPrivFuncNum +	
I/wpa_supplicant( 1156): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1156): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1156): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1156): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1156): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  906):    returned true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  371): ParamSet string: screen_state=off
D/PMS     (  906): acquireWL(4375ce38): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 906 1000 null
,D/PMS     (  906): releaseWL(4404b2a8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/NetworkPolicy(  906): updateScreenOn: false
D/wpa_supplicant( 1156): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/ContactMessageStore( 1242): start background delete task...
D/ContactMessageStore( 1242): size: 0 , 0
,D/ContactMessageStore( 1242): Background delete complete
,D/PMS     (  906): releaseWL(4375ce38): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/SmartSyncUtils( 4650): getMobilePolicyEnabled, result = true
,D/Process (  906): killProcessQuiet, pid=4285
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4285:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/SmartSyncUtils( 4650): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4650): getMobilePolicyEnabled, result = true
D/SmartSyncUtils( 4650): isEpsOn(), nState = 0
,I/CheckinTask( 1226): Sending checkin request (9007 bytes)
W/ContextImpl( 4650): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/libc    ( 1226): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1226): [NET] getaddrinfo-,err=8
D/libc    ( 1226): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1226): [NET] getaddrinfo-, 1
,D/libc    ( 1226): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =19c9 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/WifiService(  906): New client listening to asynchronous messages
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42392130
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 1
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42392130, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 0
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42392130, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42392130
,D/DotMatrix( 1604): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,D/DotMatrix( 1604): [EventService] getTotalRam: 1873 Mb
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1803): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1803): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1803): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1803): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1803): onScreenOff
E/ActivityThread(  906): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4260d750 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4260d750 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
D/PMS     (  906): acquireWL(4325cb50): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1404 10028 null
,D/PMS     (  906): releaseWL(4325cb50): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 232
D/libc    (  364): [NET]res_nsend:resplen=84
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1226): [NET] getaddrinfo_proxy-, success
D/AutoSetting( 1434): service - mHandler: cancel location update
D/AutoSetting( 1434): service -           changes count: 0
,D/PMS     (  906): releaseWL(425eda80): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/ActivityManager(  906): Recipient 4285
,E/fb4a(:<default>):LocalFbBroadcastManager( 4467): Called registerBroadcastReceiver twice.
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/libc    ( 1226): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1226): [NET] getaddrinfo-,err=8
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=27 [11][3][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4467/10026)
,D/WifiStateMachine(  906): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/PMS     (  906): acquireWL(4319ae90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10028 null
,D/PMS     (  906): releaseWL(4319ae90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null,
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (1226/10028)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=9 [11][1][0]
D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (1226/10028)
,W/GLSUser ( 1366): GoogleAccountDataService.getToken()
,W/GLSActivity( 1366): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1366): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1366): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/CheckinRequestBuilder( 1226): awaiting user notification for token
D/DotMatrix( 1604): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1604): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41c19ef8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.google.android.gms 0 11 4 12
,I/CheckinTask( 1226): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 1226): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,D/GCM     ( 1366): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/PMS     (  906): releaseWL(42646a98): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =9a00 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
E/ActivityThread( 1226): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41ce0618 that was originally bound here
E/ActivityThread( 1226): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41ce0618 that was originally bound here
E/ActivityThread( 1226): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 1226): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 1226): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 1226): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 1226): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 1226): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 1226): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 1226): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 1226): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 1226): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 1226): 	at bkt.a(SourceFile:226)
E/ActivityThread( 1226): 	at bks.a(SourceFile:298)
E/ActivityThread( 1226): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 1226): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 1226): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1226): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1366): GCM config loaded
,D/ContactMessageStore( 1242): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1242): MSG_NOTIFY_CS_TO_SYNC <<
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  906): Find DNS Address www.htc.com/104.81.130.175,
,I/GAV2    ( 4529): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  906): acquireWL(43f9a368): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1404 10028 null
,D/PMS     (  906): acquireWL(44021af0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1404 10028 null
,D/PMS     (  906): releaseWL(43f9a368): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  906): releaseWL(44021af0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/AutoSetting( 1504): service - handleMessage() stop self
,D/AutoSetting( 1504): service - onDestroy() END
,D/AutoSetting( 1504): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=4308
I/ActivityManager(  906): Killing 4308:com.htc.backup/1000 (adj 15): empty #17
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Recipient 4308
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  906): killProcessQuiet, pid=4272
,I/ActivityManager(  906): Killing 4272:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Recipient 4272
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  906): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,W/ActivityManager(  906): Activity destroy timeout for ActivityRecord{41f9f710 u0 com.test.thalitest/.MainActivity t2 f}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{43f99660 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  906): acquireWL(43cd6ff0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1604): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1604): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=99
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(43cd6ff0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:2 level:99 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1434): service - mHandler: update timezone
,D/AutoSetting( 1504): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1504): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1504): service - onCreate()
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1504): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1504): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
V/NotificationService(  906): batLight: plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c80000
D/qdlights(  906): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
,D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/DotMatrix( 1604): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
D/DotMatrix( 1604): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1504): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1504): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1504): service - mHandler: update timezone
,D/AutoSetting( 1504): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1504): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1504): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1504): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1604): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1604): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/PhoneStatusBar( 1116): removeNotification.gc:59
,I/RemoteViews( 1116): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41f485d8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.htc.htclocationservice 2 7 2 11
,D/GpsLocationProvider(  906): ALARM_XTRA_TIMEOUT
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  906): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  906): acquireWL(42e87c00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{424eed30: PendingIntentRecord{424edfd0 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=140978, Int=0
D/PMS     (  906): acquireWL(42e83f68): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
V/AlarmManager(  906): sending alarm PendingIntent{4350a468: PendingIntentRecord{424dbe48 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141241, Int=0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1366/10028)
,D/PMS     (  906): releaseWL(42e87c00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  906): acquireWL(4243c550): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10028 null
,D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =49aa +++++,
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/PMS     (  906): releaseWL(4243c550): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/AutoSetting( 1434): service - handleMessage() stop self
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  364): [NET]res_nsend:resplen=243
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo_proxy-, success
I/global  (  906): call createSocket() return a new socket.
D/libc    (  906): [NET] getaddrinfo+,hn 14(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/AutoSetting( 1434): service - handleMessage() quit looper
,D/AutoSetting( 1434): service - onDestroy() END
,D/GpsLocationProvider(  906): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  906): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  906): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  906):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  906): acquireWL(420aaec8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(420aaec8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,D/PowerUI ( 1116): closing low battery warning: level=99
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1604): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1604): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  906): releaseWL(42e83f68): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/Process (  906): killProcessQuiet, pid=3878
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3878:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3878
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{43f99b38 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  906): acquireWL(42443328): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423c6770: PendingIntentRecord{423c59e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=157835, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42443328): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1504): service - handleMessage() stop self
,D/AutoSetting( 1504): service - onDestroy() END
,D/AutoSetting( 1504): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=4326
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4326:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4326
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TelephonyReceiver( 1242): switchBindHtcMsgCursor: null
,D/PMS     (  906): acquireWL(42462300): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42462300): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,D/PowerUI ( 1116): closing low battery warning: level=99
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,D/DotMatrix( 1604): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1604): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/HtcPowerSaver(  906): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:2 level:99 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(426ab6b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/HeadsetPhoneState( 1663): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): releaseWL(426ab6b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1604): [EventService] reorderNotification, total:0
D/DotMatrix( 1604): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1604): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1604): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/ContextImpl( 4650): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 4181): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4181): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4181): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4181): Cust_ConnectToPC   : spcsc>false
D/        ( 4181): Cust_ConnectToPC   : IPT>true
D/        ( 4181): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 4181): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4181): Index of the first 1 = -1
W/Settings( 4181): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4181): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4181): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4181): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 4181): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
W/ContextImpl( 4181): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,D/SmartNS_Utility( 4181): [ACC]android_networking:tethering_guard_support=false
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42a388e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423c6770: PendingIntentRecord{423c59e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=217835, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42a388e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(426ce9d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{436ff8d0: PendingIntentRecord{42742548 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=228394, Int=0
,I/ActivityManager(  906): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4695 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  906): sending alarm PendingIntent{41f665a0: PendingIntentRecord{42620f88 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1450836602390, Int=10800000
,D/PMS     (  906): releaseWL(426ce9d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.aurora (4695/10047)
,D/Process (  906): killProcessQuiet, pid=4342
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4342:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4342
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,D/PMS     (  906): acquireWL(43c3d3d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{43ff5c08: PendingIntentRecord{42742548 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=231108, Int=0
,D/PMS     (  906): releaseWL(43c3d3d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(43483eb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43483eb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(44022ba0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423c6770: PendingIntentRecord{423c59e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=277836, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(44022ba0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000},
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(4355bbd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4355bbd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(426c3278): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423c6770: PendingIntentRecord{423c59e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=337835, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(426c3278): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1366): GoogleAccountDataService.getToken()
,W/GLSActivity( 1366): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1366): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1366): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1604): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1604): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,W/GLSActivity( 1366): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1366): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1366): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1366): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1366): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1366): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1366): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1366): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41d0c5e0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.google.android.gms 2 18 4 12
,E/PlayEventLogger( 4117): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4117): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4117): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4117): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4117): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4117): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4117): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4117): 	at dalvik.system.NativeStart.run(Native Method)
,D/libc    ( 4117): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4117): [NET] getaddrinfo-,err=8
D/libc    ( 4117): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4117): [NET] getaddrinfo-, 1
,D/libc    ( 4117): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =d864 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE,
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 29
D/libc    (  364): [NET]res_nsend:resplen=87
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
,D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4117): [NET] getaddrinfo_proxy-, success
I/global  ( 4117): call createSocket() return a new socket.
D/libc    ( 4117): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4117): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 4117): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4117): [NET] getaddrinfo-,err=8
,D/PMS     (  906): acquireWL(43467fa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43467fa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(426423b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423c6770: PendingIntentRecord{423c59e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=397835, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(426423b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process ( 4395): killProcess, pid=4395
,D/Process ( 4395): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/InputMethodManagerService(  906): Disable input method client, pid=4395
,W/InputDispatcher(  906): channel '423a3c30 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  906): channel '423a3c30 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  906): Attempted to unregister already unregistered input channel '423a3c30 com.test.thalitest.MainActivity (s)'
I/WindowManager(  906): WINDOW DIED Window{423a3c30 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager(  906): Recipient 4395
I/ActivityManager(  906): Process com.test.thalitest (pid 4395) has died.
D/WifiService(  906): Client connection lost with reason: 4
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/WindowManager(  906): Failed looking up window
W/WindowManager(  906): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@42e85fc8 does not exist
W/WindowManager(  906): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8463)
W/WindowManager(  906): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8454)
W/WindowManager(  906): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1052)
W/WindowManager(  906): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/WindowManager(  906): 	at dalvik.system.NativeStart.run(Native Method)
,I/WindowState(  906): WIN DEATH: null
,D/PMS     (  906): acquireWL(43cb64f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{431a7c50: PendingIntentRecord{4319f648 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=410789, Int=300000
,V/AlarmManager(  906): sending alarm PendingIntent{42d52f58: PendingIntentRecord{4381d828 com.google.android.gms broadcastIntent}}, i=null, t=1, cnt=1, w=1450836739934, Int=0
,D/PMS     (  906): releaseWL(43cb64f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,W/Uploader( 1226): No account for auth token provided
,D/libc    ( 1226): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1226): [NET] getaddrinfo-,err=8
D/libc    ( 1226): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1226): [NET] getaddrinfo-, 1
,D/libc    ( 1226): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =a791 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1226): [NET] getaddrinfo_proxy-, success
I/global  ( 1226): call createSocket() return a new socket.
D/libc    ( 1226): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 1226): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 1226): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1226): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(42035c40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42035c40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(425977a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423c6770: PendingIntentRecord{423c59e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=457835, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(425977a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(43afd938): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43afd938): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(425f60e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423c6770: PendingIntentRecord{423c59e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=517835, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(425f60e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(425fb898): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(425fb898): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42633688): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1604): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1604): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1604): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(42633688): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43502760): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423c6770: PendingIntentRecord{423c59e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=577836, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43502760): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(431f6318): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(431f6318): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  351): inotify_add_watch failed. (No such file or directory),
,D/ContactMessageStore( 1242): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1242): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1242): sku_id=99
D/ContactMessageStore( 1242): start background delete task...
,D/ContactMessageStore( 1242): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1242): size: 0 , 0
,D/ContactMessageStore( 1242): Background delete complete,
,D/PMS     (  906): acquireWL(43fb1ec0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423c6770: PendingIntentRecord{423c59e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=637835, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43fb1ec0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(44021990): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(44021990): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(440254a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423c6770: PendingIntentRecord{423c59e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=697835, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(440254a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43fd3b58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{431a7c50: PendingIntentRecord{4319f648 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=710789, Int=300000
,D/PMS     (  906): releaseWL(43fd3b58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  906): acquireWL(43fc5390): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43fc5390): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(430ea660): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423c6770: PendingIntentRecord{423c59e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=757836, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(430ea660): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,D/PMS     (  906): acquireWL(43522440): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41e54280: PendingIntentRecord{4249b4d0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=785343, Int=0
,D/PMS     (  906): releaseWL(43522440): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,D/PMS     (  906): acquireWL(4326e478): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4326e478): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43814b20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423c6770: PendingIntentRecord{423c59e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=817835, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43814b20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(41e781b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(41e781b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4261d480): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423c6770: PendingIntentRecord{423c59e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=877835, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4261d480): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42df5738): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42df5738): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43ffdfd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423c6770: PendingIntentRecord{423c59e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=937835, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43ffdfd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42a3a8b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42a3a8b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(431a0100): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423c6770: PendingIntentRecord{423c59e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=997836, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(431a0100): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(434f2c30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10028}
,V/AlarmManager(  906): sending alarm PendingIntent{431b0848: PendingIntentRecord{424dc838 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1011077, Int=0
,D/PMS     (  906): acquireWL(43fbe558): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1366 10028 null
,V/AlarmManager(  906): sending alarm PendingIntent{42606ad0: PendingIntentRecord{425e5ed8 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450837322852, Int=900000
,V/AlarmManager(  906): sending alarm PendingIntent{41c16d78: PendingIntentRecord{4357f698 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450837393371, Int=0
,D/PMS     (  906): releaseWL(43fbe558): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,W/ContextImpl( 4650): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  906): acquireWL(437a7120): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10028 null
,D/PowerUsageService( 4650): call getInstance()
,D/SmartSyncUtils( 4650): isEpsOn(), nState = 0
,D/PMS     (  906): releaseWL(437a7120): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PowerUsageList:PowerUsageHelper( 4650): MY_DEBUG = false
D/PMS     (  906): releaseWL(434f2c30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4350a2f0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4650 1000 null
D/SmartSyncScreenOnOffTimeReceiver( 4650): [updateNmRange] bManual = false
D/SmartSyncScreenOnOffTimeReceiver( 4650): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 2, nStart = 1, nEnd = 2, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 4650): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4650): SettingOnTime = 1450918800000, randomSettingOnTime = 1450918322000
,D/SmartSyncScreenOnOffTimeReceiver( 4650): SettingOffTime = 1450915200000, randomSettingOffTime = 1450918008000
,D/SmartSyncScreenOnOffTimeReceiver( 4650): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4650): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4650): bNightModeTurnOffOnce = false
D/PMS     (  906): acquireWL(43f99f90): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1366 10028 null
D/PMS     (  906): releaseWL(4350a2f0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/GCM     ( 1366): Message class mow
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1366/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1366/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1366/10028)
,D/PMS     (  906): releaseWL(43f99f90): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  906): acquireWL(425888a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10028 null
,D/PMS     (  906): releaseWL(425888a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=11 [143][16][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0],
,D/PMS     (  906): acquireWL(446b2080): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/DotMatrix( 1604): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1604): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1604): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): releaseWL(446b2080): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43c5cdc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423c6770: PendingIntentRecord{423c59e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1057835, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43c5cdc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43c4ab48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
,D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,I/BatteryService(  906): n_update end
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1604): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1604): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1604): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): releaseWL(43c4ab48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4354cae0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423c6770: PendingIntentRecord{423c59e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1117835, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4354cae0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43533290): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/DotMatrix( 1604): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1604): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1604): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): releaseWL(43533290): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4323f0d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423c6770: PendingIntentRecord{423c59e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1177835, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4323f0d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4323edd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/BatteryService(  906): n_update end
D/PMS     (  906): releaseWL(4323edd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
,D/PMS     (  906): runPSCheck
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1604): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1604): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1604): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  351): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(43124f00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423c6770: PendingIntentRecord{423c59e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1237836, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43124f00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43124c00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/BatteryService(  906): n_update end
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1604): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1604): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1604): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(43124c00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): closing low battery warning: level=100
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(426d4728): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(426d4728): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4250a948): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423c6770: PendingIntentRecord{423c59e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1297835, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4250a948): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(41e97560): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(41e97560): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42545228): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423c6770: PendingIntentRecord{423c59e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1357836, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42545228): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(423c6f10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(423c6f10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(41f95dd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423c6770: PendingIntentRecord{423c59e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1417835, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(41f95dd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000},
,D/PMS     (  906): acquireWL(425975e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(425975e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(424ed078): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423c6770: PendingIntentRecord{423c59e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1477835, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(424ed078): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(423b1920): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(423b1920): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4207f9f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423c6770: PendingIntentRecord{423c59e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1537835, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4207f9f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(41b76508): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): onReceive BATTERY_CHANGED
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1604): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1604): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1604): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(41b76508): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(424096a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  906): sending alarm PendingIntent{423c6770: PendingIntentRecord{423c59e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1597835, Int=0
,D/PMS     (  906): releaseWL(424096a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(41f91188): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(41f91188): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42e68c58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423c6770: PendingIntentRecord{423c59e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1657836, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42e68c58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42586ff0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42586ff0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(423b1540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(423b1540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,D/PowerUI ( 1116): closing low battery warning: level=100
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1604): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1604): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1604): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4409f070): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423c6770: PendingIntentRecord{423c59e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1717836, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4409f070): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43b30fb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(43b30fb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1604): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1604): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1604): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(425388c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(425388c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(423e5b38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423c6770: PendingIntentRecord{423c59e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1777837, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(423e5b38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): acquireWL(43b7bd08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43b7bd08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  351): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(41e8a918): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423c6770: PendingIntentRecord{423c59e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1837835, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,I/ProcessStatsService(  906): Prepared write state in 26ms
,I/ProcessStatsService(  906): Prepared write state in 33ms,
,D/PMS     (  906): releaseWL(41e8a918): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  906): Pruning old procstats: /data/system/procstats/state-2015-12-22-02-21-40.bin
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,D/PMS     (  906): acquireWL(42606bc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41e54280: PendingIntentRecord{4249b4d0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1505371, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{423a1bd8: PendingIntentRecord{4255e818 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1820693, Int=1800000
D/PMS     (  906): acquireWL(4262efa8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
V/AlarmManager(  906): sending alarm PendingIntent{4370ec40: PendingIntentRecord{41cc6000 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450837667084, Int=1800000
,V/AlarmManager(  906): sending alarm PendingIntent{42606ad0: PendingIntentRecord{425e5ed8 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450838222852, Int=900000
,D/ConnectivityService(  906): Done.
D/ConnectivityService(  906): Setting timer for 720seconds
,D/PMS     (  906): releaseWL(4262efa8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/PMS     (  906): acquireWL(425f5910): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1226 10028 null
,D/PMS     (  906): acquireWL(4207f0a8): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1226 10028 null
,D/PMS     (  906): releaseWL(425f5910): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,I/EventLogService( 1226): Aggregate from 1450836491681 (log), 1450835867032 (data)
W/ContextImpl( 4650): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  906): releaseWL(42606bc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): releaseWL(4207f0a8): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): acquireWL(426c7898): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(426c7898): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43919d10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423c6770: PendingIntentRecord{423c59e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1897835, Int=0
,D/Process (  906): killProcessQuiet, pid=4117
,I/ActivityManager(  906): Killing 4117:com.android.vending/u0a73 (adj 15): empty for 1809s
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.trimApplications:17252 
,D/Process (  906): killProcessQuiet, pid=4358
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 4358:com.android.settings:remote/1000 (adj 15): empty for 1822s
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,I/ActivityManager(  906): Recipient 4358
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): releaseWL(43919d10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ActivityManager(  906): Recipient 4117
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(426e9d48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10028}
,V/AlarmManager(  906): sending alarm PendingIntent{43fe6800: PendingIntentRecord{424dc838 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1911319, Int=0
,D/PMS     (  906): acquireWL(43fe3900): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1366 10028 null
,D/PMS     (  906): releaseWL(43fe3900): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,D/Process (  906): killProcessQuiet, pid=4529
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  906): Killing 4529:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1800s
D/PMS     (  906): releaseWL(426e9d48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
D/PMS     (  906): acquireWL(43aecca0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10028 null
,D/Process (  906): killProcessQuiet, pid=4512
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
,D/Process (  906): killProcessQuiet, pid=4496
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  906): Killing 4512:com.android.chrome/u0a96 (adj 15): empty for 1800s
I/ActivityManager(  906): Killing 4496:com.google.android.setupwizard/u0a78 (adj 15): empty for 1800s
D/PMS     (  906): releaseWL(43aecca0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/Process (  906): killProcessQuiet, pid=3844
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
,D/Process (  906): killProcessQuiet, pid=4443
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  906): Killing 3844:com.google.android.music:main/u0a154 (adj 15): empty for 1800s
I/ActivityManager(  906): Killing 4443:com.htc.mms.backupagent/u0a77 (adj 15): empty for 1807s
,I/ActivityManager(  906): Recipient 4496
,TIME-OUT KILL (timeout was 1800000ms),I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4443
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4512
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  906): Client com.google.android.music (pid 3844): Died!
I/ActivityManager(  906): Recipient 3844
I/ActivityManager(  906): Recipient 4529
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/GCM     ( 1366): Message class mow
D/PMS     (  906): acquireWL(43559db8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1366 10028 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1366/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1366/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1366/10028)
D/PMS     (  906): releaseWL(43559db8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  906): acquireWL(43290790): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10028 null
D/PMS     (  906): releaseWL(43290790): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
E/cutils-trace( 4743): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4743): ====startRecUseTime====
D/htc.customization.log.level( 4743):  is 
W/CustomizationLogLevel( 4743): Level value is invalid, use default level 2
D/CustomizationManager( 4743):  Read ACC file spent 0.104 (s)
D/CIDMapFileReader( 4743): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4743): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4743): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4743): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4743): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4743): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4743): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4743): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4743): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4743): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4743): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4743): Parsing tag category name = system
I/CustomizationCIDLoader( 4743): Parsing tag category name = application
I/CustomizationCIDLoader( 4743): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4743): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4743): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4743): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4743): Parsing tag category name = Settings
D/CustomizationManager( 4743):  Read CID file spent 0.157 (s)
D/CustomizationManager( 4743):  All configurations done spent 0.157 (s)
W/HtcNativeFlag( 4743): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4743): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4743): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4743): Fail to get flag for type 'language', use default value: -1
D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=5 [68][3][1]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/PackageManager(  906): deletePackageAsUser: pkg=com.test.thalitest, pid=4743, uid=2000 user=0
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
W/asset   (  906): Copying FileAsset 0x627fa780 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
W/PackageSettings(  906): Skipping PackageSetting{42261e70 com.example.hello/10356} due to missing metadata
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1604): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1604): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1604): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1404): Ignoring removeGeofence because network location is disabled.
I/acms    ( 1887): Unregistering com.test.thalitest
E/acms    ( 1887): Could not unregister removed application com.test.thalitest
W/AccTypeManager( 1330): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1330): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  906): acquireWL(44693330): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1404 10028 null
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/dalvikvm-heap( 4156): Grow heap (frag case) to 13.520MB for 1821008-byte allocation
D/PMS     (  906): releaseWL(44693330): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/Launcher( 1271): Deferring update until onResume
D/Launcher( 1271): waitUntilResume // bindAppsRemoved
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
D/VoicemailCleanupService( 1296): Cleaning up data for package: com.test.thalitest
D/AccTypeManager( 1330): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
W/SystemReader( 1255): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
D/PackageBroadcastService( 1226): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/ActivityManager(  906): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4757 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
E/ExternalAccountType( 1330): Unsupported attribute readOnly
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/PhoneApp( 1242): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  906): Delaying start of: ServiceRecord{4264a688 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/MultiDex( 4757): install
I/MultiDex( 4757): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PeopleContactsSync( 1226): CP2 sync disabled
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1226, uid=10028, userID:0
I/MultiDex( 4757): loading existing secondary dex files
I/MultiDex( 4757): load found 1 secondary dex files
I/MultiDex( 4757): install done
I/Icing   ( 1226): doRemovePackageData com.test.thalitest
D/PMS     (  906): acquireWL(4263a1e0): PARTIAL_WAKE_LOCK  Icing 0x1 1226 10028 null
D/PMS     (  906): releaseWL(4263a1e0): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  906): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4775 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/ProviderInstaller( 4757): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  906): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4775): install
I/MultiDex( 4775): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/ActivityManager(  906): Resuming delayed broadcast
I/MultiDex( 4775): loading existing secondary dex files
I/MultiDex( 4775): load found 1 secondary dex files
I/MultiDex( 4775): install done
E/SharedPreferencesImpl( 1207): Couldn't rename file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml to backup file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml.bak
I/ActivityManager(  906): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 1434): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
E/SQLiteLog( 1434): (3850) statement aborts at 44: [UPDATE plugin SET removed=? WHERE package_id IN ( SELECT _id FROM plugin_pkg WHERE package=? )] disk I/O error
E/SQLiteDBG( 1434): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/user/0/com.htc.sense.hsp/databases/registry.db, handle = 0x5ca6cbf8
I/ProviderInstaller( 4775): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
W/[PluginManager]RegisterService( 1434): provider may killed!
W/[PluginManager]RegisterService( 1434): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/[PluginManager]RegisterService( 1434): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/[PluginManager]RegisterService( 1434): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
W/[PluginManager]RegisterService( 1434): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
W/[PluginManager]RegisterService( 1434): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/[PluginManager]RegisterService( 1434): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
W/[PluginManager]RegisterService( 1434): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
W/[PluginManager]RegisterService( 1434): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
W/[PluginManager]RegisterService( 1434): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/[PluginManager]RegisterService( 1434): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
W/[PluginManager]RegisterService( 1434): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 1434): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 1434): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 1434): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 1434): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/[PluginManager]RegisterService( 1434): handle notify Blinkfeed plugin client changed
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4794 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
D/Process (  906): killProcessQuiet, pid=4156
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4156:com.google.android.apps.plus/u0a160 (adj 15): empty for 1802s
I/ActivityManager(  906): Recipient 4156
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/SQLiteDatabase( 4757): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4757): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4757): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4757): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4757): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4757): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4757): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4757): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4757): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4757): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4757): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4757): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4757): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4757): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4757): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4757): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4757): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4757): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4757): threadid=12: thread exiting with uncaught exception (group=0x41730e30)
E/ActivityManager(  906): App crashed! Process: com.google.android.gms.drive
E/AndroidRuntime( 4757): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4757): Process: com.google.android.gms.drive, PID: 4757
E/AndroidRuntime( 4757): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4757): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4757): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4757): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4757): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4757): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4757): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4757): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4757): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4757): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4757): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4757): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4757): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4757): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4757): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4757): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4757): 	at ctn.run(SourceFile:985)
D/Process ( 4757): killProcess, pid=4757
D/Process ( 4757): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
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
I/ActivityManager(  906): Recipient 4757
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.google.android.gms.drive (pid 4757) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4794, uid=10073, userID:0
D/Finsky  ( 4794): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (4794/10073)
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (4794/10073)
W/PackageManager(  906): Unable to load service info ResolveInfo{42639208 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
D/Finsky  ( 4794): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
W/Settings( 4794): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 4794): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SQLiteDatabase( 4794): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 4794): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4794): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4794): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4794): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4794): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4794): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4794): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4794): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4794): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4794): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4794): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4794): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4794): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4794): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4794): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/SQLiteDatabase( 4794): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/SQLiteDatabase( 4794): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/SQLiteDatabase( 4794): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 4794): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 4794): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4794): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4794): threadid=25: thread exiting with uncaught exception (group=0x41730e30)
E/AndroidRuntime( 4794): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime( 4794): Process: com.android.vending, PID: 4794
E/AndroidRuntime( 4794): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4794): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4794): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4794): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4794): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4794): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4794): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4794): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4794): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4794): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4794): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4794): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4794): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4794): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4794): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/AndroidRuntime( 4794): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/AndroidRuntime( 4794): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/AndroidRuntime( 4794): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4794): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4794): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4794): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  906): App crashed! Process: com.android.vending
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4794, uid=10073, userID:0
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
D/Prism.PackageStateRece_( 1271): action: android.intent.action.PACKAGE_REMOVED
D/Process ( 4794): killProcess, pid=4794
D/Process ( 4794): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.finsky.FinskyApp$CrashHandler.uncaughtException:284 java.lang.ThreadGroup.uncaughtException:693 
I/IcingCorporaProvider( 2869): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  906): Recipient 4794
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4829 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/ActivityManager(  906): Process com.android.vending (pid 4794) has died.
I/TrimMemoryManager( 1271): [trimMemory] 5
E/SQLiteLog( 2869): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2869): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x6392ffc0
W/dalvikvm( 2869): threadid=14: thread exiting with uncaught exception (group=0x41730e30)
E/ActivityManager(  906): App crashed! Process: com.google.android.googlequicksearchbox:search
D/Process ( 2869): killProcess, pid=2869
D/Process ( 2869): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/AndroidRuntime( 2869): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2869): Process: com.google.android.googlequicksearchbox:search, PID: 2869
E/AndroidRuntime( 2869): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2869): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2869): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2869): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2869): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2869): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2869): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2869): 	at cid.d(PG:186)
E/AndroidRuntime( 2869): 	at clo.g(PG:594)
E/AndroidRuntime( 2869): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2869): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2869): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2869): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2869): 	at clr.tL(PG:827)
E/AndroidRuntime( 2869): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2869): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2869): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2869): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
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
I/ActivityManager(  906): Recipient 2869
I/ActivityManager(  906): Process com.google.android.googlequicksearchbox:search (pid 2869) has died.
D/WifiService(  906): Client connection lost with reason: 4
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 1000ms
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
D/MediaRouterService(  906): Client com.google.android.googlequicksearchbox (pid 2869): Died!
D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  906): start
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1271): loadItems() com.htc.launcher.pageview.WidgetManager@41bf3dd0 +
I/Prism.WidgetManager( 1271): onLoadItems() +
E/SQLiteDatabase( 4829): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4829): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4829): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4829): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4829): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4829): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4829): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4829): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4829): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4829): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4829): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4829): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4829): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4829): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4829): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4829): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4829): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4829): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4829): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4829): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4829): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4829): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4829): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4829): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4829): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4829): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4829): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4829): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4829): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4829): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4829): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4829): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4829): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4829): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4829): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4829): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4829): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4829): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4829): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4829): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4829): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4829): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4829): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4829): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4829): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4829): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4829): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4829): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4829): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4829): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4829): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4829): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4829): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4829): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4829): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4829): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4829): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4829): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4829): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4829): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4829): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4829): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4829): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4829): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4829): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4829): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4829): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4829): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4829): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4829): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4829): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4829): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4829): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4829): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4829): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4829): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4829): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4829): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4829): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4829): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4829): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4829): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4829): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4829): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4829): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4829): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4829): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4829): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4829): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4829): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4829): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4829): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4829): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4829): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4829): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4829): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4829): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4829): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4829): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4829): threadid=11: thread exiting with uncaught exception (group=0x41730e30)
E/ActivityManager(  906): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4829): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4829): Process: com.google.android.apps.docs, PID: 4829
E/AndroidRuntime( 4829): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4829): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4829): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4829): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4829): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4829): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4829): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4829): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4829): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4829): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4829): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4829): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4829): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4829): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4829): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4829): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4829): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4829): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4829): 	at aho.run(AbstractDatabaseInstance.java:455)
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
I/ActivityManager(  906): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4845 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process ( 4829): killProcess, pid=4829
D/Process ( 4829): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  906): Recipient 4829
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.google.android.apps.docs (pid 4829) has died.
W/ContextImpl( 4845): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 4845): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4845): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4845): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4845): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4845): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4845): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4845): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4845): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4845): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4845): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4845): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4845): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4845): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4845): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4845): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4845): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4845): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4845): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4845): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4845): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4845): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4845): threadid=10: thread exiting with uncaught exception (group=0x41730e30)
E/ActivityManager(  906): App crashed! Process: com.android.keychain
I/ActivityManager(  906): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4859 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/AndroidRuntime( 4845): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4845): Process: com.android.keychain, PID: 4845
E/AndroidRuntime( 4845): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4845): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4845): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4845): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4845): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4845): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4845): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4845): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4845): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4845): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4845): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4845): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4845): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4845): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4845): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4845): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4845): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4845): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4845): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4845): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1450838296397.dbox_tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 4845): killProcess, pid=4845
D/Process ( 4845): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  906): Recipient 4845
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.android.keychain (pid 4845) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10598ms
D/AppTag  ( 4859): getInstance(Context context)
D/AppTag  ( 4859): getInstance(Context context)
D/AppTag  ( 4859): onCreate()
I/ActivityManager(  906): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4874 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
D/PMS     (  906): acquireWL(42ff2438): PARTIAL_WAKE_LOCK  AsyncService 0x1 4874 10160 null

```
