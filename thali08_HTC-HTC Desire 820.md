#### Test 50650278d6c551a_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  912): doBoolean: SignalStrength 97
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  912):    returned true
,E/cutils-trace( 4356): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4356): ====startRecUseTime====
D/htc.customization.log.level( 4356):  is 
W/CustomizationLogLevel( 4356): Level value is invalid, use default level 2
D/CustomizationManager( 4356):  Read ACC file spent 0.057 (s)
D/CIDMapFileReader( 4356): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4356): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4356): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4356): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4356): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4356): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4356): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4356): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4356): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4356): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4356): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4356): Parsing tag category name = system
I/CustomizationCIDLoader( 4356): Parsing tag category name = application
I/CustomizationCIDLoader( 4356): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4356): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4356): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4356): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4356): Parsing tag category name = Settings
D/CustomizationManager( 4356):  Read CID file spent 0.099 (s)
D/CustomizationManager( 4356):  All configurations done spent 0.099 (s)
W/HtcNativeFlag( 4356): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4356): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4356): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4356): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
W/CpuWake (  912): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  912): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  912): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  912): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  912): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  912): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  912): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4356
D/PMS     (  912): acquireHCC(435d7b80): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 912 1000 null
D/PMS     (  912): acquireHCC(435d5278): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 912 1000 null
W/asset   (  912): Copying FileAsset 0x6cd1f440 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  912): @test_code: getHtcIntentFlag: 0 obj: 1129376280
D/PMS     (  912): acquireWL(435d1d70): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 912 1000 null
I/FeedHostManager( 1274): [onPause]
I/FeedProviderManager( 1274): onPause
I/SocialFeedProvider( 1274): +onPause
I/SocialFeedProvider( 1274): -onPause
I/FeedHostManager( 1274): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c2c6f0
I/ActivityManager(  912): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4367 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1274): [trimMemory] 20
W/asset   ( 4367): Copying FileAsset 0x5c889428 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4367): Binding Chromium to main looper Looper (main, tid 1) {41b07668}
I/LibraryLoader( 4367): Expected native library version number "",actual native library version number ""
I/chromium( 4367): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4367): Initializing chromium process, renderers=0
W/System.err(  912): java.lang.Throwable: stack dump
W/System.err(  912): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  912): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  912): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  912): 	at android.os.Binder.execTransact(Binder.java:412)
D/BluetoothManagerService(  912): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  912): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  912): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@41d59280:true
D/BluetoothAdapter( 4367): 1102188696: getState(). Returning 12
D/PMS     (  912): acquireWL(41e03810): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  912): acquireWL(41da5950): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  912): releaseWL(41da5950): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4367): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4367): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4367): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4367): Local Branch: 
I/Adreno-EGL( 4367): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4367): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4367):                  aa63bbd948f41d15fc72f585e
W/chromium( 4367): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4367): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4367): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4367): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4367): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4367): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4367): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4367): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4367): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4367): CordovaWebView is running on device made by: HTC
,W/AwContents( 4367): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  912): Disable input method client, pid=1274
W/ResourceType( 4367): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4367): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b52748, mServedView=org.apache.cordova.engine.SystemWebView{41b183b0 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1212): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1212): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1212): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1212): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 4367): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  912): Displayed com.test.thalitest/.MainActivity: +285ms
I/InputMethodManagerService(  912): Enable input method client, pid=4367
D/PMS     (  912): releaseWL(435d1d70): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/JsMessageQueue( 4367): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 4367): JniHelper::setJavaVM(0x415e2048), pthread_self() = 1663075416
D/JX-Cordova( 4367): jxcore cordova android initializing
W/dalvikvm( 4367): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,I/dalvikvm-heap( 4367): Grow heap (frag case) to 11.521MB for 64402-byte allocation
,I/dalvikvm-heap( 4367): Grow heap (frag case) to 11.579MB for 96598-byte allocation
,I/dalvikvm-heap( 4367): Grow heap (frag case) to 11.649MB for 144892-byte allocation
,I/dalvikvm-heap( 4367): Grow heap (frag case) to 11.767MB for 217334-byte allocation
,D/PMS     (  912): acquireWL(42300a10): PARTIAL_WAKE_LOCK  Icing 0x1 1226 10028 null
,I/dalvikvm-heap( 4367): Grow heap (frag case) to 11.937MB for 325996-byte allocation
D/PMS     (  912): releaseWL(42300a10): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  912): acquireWL(42090d30): PARTIAL_WAKE_LOCK  Icing 0x1 1226 10028 null
,D/PMS     (  912): releaseWL(42090d30): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  912): acquireWL(4256f538): PARTIAL_WAKE_LOCK  Icing 0x1 1226 10028 null
,D/PMS     (  912): releaseWL(4256f538): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/dalvikvm-heap( 4367): Grow heap (frag case) to 12.616MB for 733480-byte allocation
,I/dalvikvm-heap( 4367): Grow heap (frag case) to 13.213MB for 1100216-byte allocation
,I/dalvikvm-heap( 4367): Grow heap (frag case) to 14.123MB for 1650320-byte allocation
,I/dalvikvm-heap( 4367): Grow heap (frag case) to 15.477MB for 2475476-byte allocation
,W/CpuWake (  912): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  912): <<nativeReleaseCpuPerfWakeLock()
,W/CpuWake (  912): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  912): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  912): >>release mCpuPerf_Freq wakelock
W/CpuWake (  912): <<release mCpuPerf_Freq wakelock
,D/PMS     (  912): releaseHCC(435d7b80): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  912): releaseHCC(435d5278): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,D/WIFI_ICON( 1119): WifiActivity: 0
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  912): doBoolean: SignalStrength 97
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  912):    returned true
,I/dalvikvm-heap( 4367): Grow heap (frag case) to 17.575MB for 3713210-byte allocation
,W/jxcore-log( 4367): Initializing JXcore engine
,W/jxcore-log( 4367): JXcore engine is ready
,W/jxcore-log( 4367): Starting JXcore engine
,I/SensorManager(  912): mEventCount = 1350
,I/ActivityManager(  912): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4416 uid=10077 gids={50077}
,D/PMS     (  912): acquireWL(42503c10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{10077}
,V/AlarmManager(  912): sending alarm PendingIntent{420b7080: PendingIntentRecord{4237e7f0 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1449754811782, Int=60000
,D/PMS     (  912): releaseWL(42503c10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4416): SMSBackupAgentService started
D/SMSBackup( 4416): Checking restore status
D/SMSBackup( 4416): Restore complete
D/SMSBackup( 4416): cancelCheckAlarm
D/SMSBackup( 4416): SMSBackupAgentService completed: completed in 0.0 seconds
D/Process (  912): killProcessQuiet, pid=3622
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  912): Killing 3622:com.htc.task/u0a70 (adj 15): empty #17
,W/jxcore-log( 4367): Platform android
W/jxcore-log( 4367): 
,W/jxcore-log( 4367): Process ARCH arm
W/jxcore-log( 4367): 
I/ActivityManager(  912): Recipient 3622
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  912): releaseWL(41e03810): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/WIFI_ICON( 1119): WifiActivity: 1
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  912): acquireWL(4231a7b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
D/WifiDataStallTracker(  912): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  912): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
V/AlarmManager(  912): sending alarm PendingIntent{42402120: PendingIntentRecord{4234fa40 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=105594, Int=0
D/WifiDataStallTracker(  912): updateDataStallInfo: mDataStallTxRxSum={txSum=107 rxSum=90} preTxRxSum={txSum=106 rxSum=89}
D/WifiDataStallTracker(  912): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  912): onDataStallAlarm: tag=20553 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  912): startDataStallAlarm: tag=20554 delay=15s
D/PMS     (  912): releaseWL(4231a7b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4367): JXcore Cordova bridge is ready!
I/jxcore-log( 4367): 
,W/jxcore-log( 4367): JXcore engine is started
,I/chromium( 4367): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4367): Toggling radios to true
I/jxcore-log( 4367): 
,D/BluetoothAdapter( 4367): enable(): BT is already enabled..!
,D/WifiManager( 4367): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
W/HtcDLNAServiceManager(  912): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  912): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  912): Settings:Agentvalue: 2
W/Settings:Agent(  912): >> traceCallingStack()
W/Settings:Agent(  912): Process.myPid(): 912
W/Settings:Agent(  912): Process.myTid(): 1350
W/Settings:Agent(  912): Process.myUid(): 1000
W/Settings:Agent(  912): 
W/Settings:Agent(  912): 
,W/System.err(  912): java.lang.Throwable: stack dump
W/System.err(  912): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  912): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  912): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  912): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  912): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  912): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  912): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  912): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  912): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  912): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  912): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  912): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  912): 
W/Settings:Agent(  912): << traceCallingStack(): 1(ms),
D/WifiManager( 4367): disconnect: Base Package Name=com.test.thalitest, uid=10348
D/WifiNative-wlan0(  912): doBoolean: DISCONNECT
,D/WifiManager( 4367): reconnect: Base Package Name=com.test.thalitest, uid=10348
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): TDLS: Tear down peers
,I/wpa_supplicant( 1162): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4367): Radios toggled
I/jxcore-log( 4367): 
,D/BluetoothManagerService(  912): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 4367): Got Device Bluetooth address: 80:01:84:8A:B3:68,
I/jxcore-log( 4367): 
D/WifiService(  912): New client listening to asynchronous messages
D/WifiService(  912): setWifiEnabled: true pid=4367, uid=10348
E/WifiService(  912): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  912): isSprintWifiRestricted(): false
I/WifiService(  912): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  912): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
I/jxcore-log( 4367): Perf Test app loaded loaded
I/jxcore-log( 4367): 
I/Choreographer( 4367): Skipped 78 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 4367): check test folder
I/jxcore-log( 4367): 
,I/jxcore-log( 4367): found test : ./testFindPeers.js
I/jxcore-log( 4367): 
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1162): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1162): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,I/wpa_supplicant( 1162): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  912): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  912): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1162): TDLS: Remove peers on disassociation
D/Tethering(  912): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/Tethering(  912): interfaceStatusChanged wlan0, false
E/wpa_supplicant( 1162): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1162): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/Tethering(  912): [isWifi] getHotspotEnabled: false
E/wpa_supplicant( 1162): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1162): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb776dbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1162):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1162): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1162): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1162): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1162): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1162): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1162): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1162): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1162): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1162): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1162): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1162): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1162): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/Tethering(  912): interfaceLinkStateChanged wlan0, false
D/Tethering(  912): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1162): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1162): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0,' added
D/wpa_supplicant( 1162): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1162): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1162): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1162): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1162): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1162): nl80211: Event message available
D/wpa_supplicant( 1162): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1162): nl80211: Ignore disconnect event triggered during reassociation
D/WifiNative-wlan0(  912):    returned true
D/WifiPerfLock(  912): release()
D/WifiStateMachine(  912): PerfLock released for exiting ConnectedState
D/Tethering(  912): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  912): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): Power_Mode_Type mode = 0
I/wpa_supplicant( 1162): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  912):    returned true
D/HTCRequest(  912): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  912): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  912): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  912): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/WifiNative-wlan0(  912): doBoolean: DRIVER BTCOEXMODE 2
D/HTCRequest(  912): WifiMonitor:getReasonFromEventString() 3
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/HTCRequest(  912): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/HTCRequest(  912): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  912): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  912): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0(  912):    returned true
D/HTCRequest(  912): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  912): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/ConnectivityService(  912): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  912): acquireWL(44003098): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 912 1000 null
D/WifiP2pService(  912): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  912): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  912): [RunningState] Stop DHCP
D/libc    (  912): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  912): [NET] getaddrinfo-, SUCCESS
I/jxcore-log( 4367): found test : ./testSendData.js
I/jxcore-log( 4367): 
D/WifiStateMachine(  912): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  912): doBoolean: RECONNECT
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): Fast associate: Old scan results
I/wpa_supplicant( 1162): wpa_supplicant_scan enter
I/wpa_supplicant( 1162): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1162): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1162): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1162): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1162): nl80211: Event message available
D/wpa_supplicant( 1162): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/libc    (  912): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  912): [NET] getaddrinfo-, SUCCESS
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  912): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiDataStallTracker(  912): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  912): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  912): stopDataStallAlarm: current tag=20554 mDataStallAlarmIntent=PendingIntent{424146f0: PendingIntentRecord{4234fa40 android broadcastIntent}}
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiMonitor(  912): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiNative-wlan0(  912):    returned true
,D/WifiStateMachine(  912): Enter handleNetworkDisconnect
,D/WifiNative-wlan0(  912): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): Power_Mode_Type mode = 0
I/wpa_supplicant( 1162): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 61
D/UsbnetStateTracker(  912): isAvailable+-
D/UsbnetStateTracker(  912): reconnect
D/UsbnetStateTracker(  912): isAvailable+-
,D/WifiNative-wlan0(  912):    returned true
,D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiStateTracker(  912): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  912): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  912): Provision feature enable=false
D/ConnectivityService(  912): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/ConnectivityService(  912): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  912): default: reconnect()
D/MDST    (  912): default: setTeardownRequested(false),
D/MDST    (  912): default: setEnableApn apnType =default , enable=true
D/WifiNative-wlan0(  912): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  912):    returned true
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 3808): >>>>>WISPrService start isConnected = false<<<<<
D/WifiP2pService(  912): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  912): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  912): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1862/10178)
D/ConnectivityService(  912): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  912): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  912): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  912): Exception trying to remove a route: java.lang.IllegalStateException: command '29 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 29 Failed to remove route from default table (No such process)'
D/ConnectivityService(  912): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  912): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/WISPrService( 3808): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  912): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  912): Exit handleNetworkDisconnect
,D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  912): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/WifiDataStallTracker(  912): onReceive: action=android.net.wifi.STATE_CHANGE
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/WifiDataStallTracker(  912): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiService(  912): New client listening to asynchronous messages
W/ConnectivityService(  912): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  912): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WifiStateTracker(  912): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/ConnectivityService(  912): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  912): handleConnectivityChange: resetting
D/ConnectivityService(  912): resetConnections(wlan0, 3)
D/libc    (  365): [NET] entry_id:5   entry:0xb7508f78  removed 
D/libc    (  365): [NET] entry_id:6   entry:0xb7509120  removed 
D/libc    (  365): [NET] entry_id:4   entry:0xb750d2a0  removed 
D/libc    (  365): [NET] entry_id:1   entry:0xb750d428  removed 
D/libc    (  365): [NET] entry_id:7   entry:0xb7509308  removed 
D/libc    (  365): [NET] entry_id:3   entry:0xb750cfd8  removed 
D/libc    (  365): [NET] entry_id:2   entry:0xb750d0f8  removed 
D/libc    (  365): [NET] entry_id:8   entry:0xb75094d0  removed 
,D/libc    (  365): *************************
D/libc    (  365): *** DNS CACHE FLUSHED ***
D/libc    (  365): *************************
D/PMS     (  912): acquireWL(424e81f0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1384 10028 null
D/ConnectivityService(  912): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1862/10178)
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/PMS     (  912): acquireWL(424b0f08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1384 10028 null
D/ConnectivityService(  912): flush DNS cache for net 1(wlan0)
,D/WISPrService( 3808): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  912): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 3808): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/Nat464Xlat(  912): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  912): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  912): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  912): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  912): releaseWL(424b0f08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  912): acquireWL(42da15b0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 912 1000 null
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:0
D/WirelessDisplayService(  912): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  912): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/ConnectivityService(  912): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  912): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  912): getNetworkInfo networkType=1 called by  (912/1000)
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1384/10028)
I//system/bin/ip(  365): RTNETLINK answers: No such process
I/logwrapper(  365): /system/bin/ip terminated by exit(2)
,D/WifiStateMachine(  912): startScan Pid: 912 Uid 1000
D/WifiNative-wlan0(  912): doBoolean: SCAN
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  912):    returned false
D/BatSI   (  912): WIFI scan started for: 650a0300 uid:1000
D/ConnectivityService(  912): reportInetCondition for net -1, percentage: 0 by  (1384/10028)
D/PMS     (  912): releaseWL(42da15b0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  912): releaseWL(424e81f0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1384/10028)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1384/10028)
D/ConnectivityService(  912): mActiveDefaultNetwork: -1
,D/ConnectivityService(  912): handleInetConditionChange: no active default network - ignore
I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:1
,I/chromium( 4367): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  912): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/AlarmManager(  912): [AlarmQueuing] connectivity wifi: false
,V/Tethering(  912): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/GpsLocationProvider(  912): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  912): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  912): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  912): ignore wifi update if we are not in OPENING or CLOSING
,D/CaptivePortalTracker(  912): DelayedCaptiveCheckState
D/ConnectivityService(  912): getNetworkInfo networkType=1 called by  (912/1000)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/PMS     (  912): acquireWL(4234e720): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 912 1000 null
D/PMS     (  912): releaseWL(4234e720): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1495/10028)
D/CaptivePortalTracker(  912): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  912): NoActiveNetworkState,
,I/ConnectivityHelper( 1274): [onReceive] WIFI(1): DISCONNECTED
D/Tethering(  912): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  912): bSetPropertyMultiRAB:false
D/ConnectivityService(  912): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1862/10178)
D/ConnectivityService(  912): getNetworkInfo networkType=1 called by com.htc.launcher (1274/10075)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1902/1000)
D/ConnectivityService(  912): getNetworkInfo networkType=1 called by com.google.android.music (3877/10154)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
I/NetworkMonitor( 3877): type=WIFI subType= reason=null isConnected=false
D/Tethering(  912): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  912): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  912): ipv4Default null
I/Tethering(  912): No IPv4 upstream interface, giving up.
D/Tethering(  912): TetherMasterSM: InitialState processMessage what=3
D/htcCheckinService(  912): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  912): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.docs (4258/10100)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.docs (4258/10100)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1995/10021)
,I/ActivityManager(  912): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4439 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4439): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4439): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4439): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4439): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4439): Preparing secondary program dexes.
V/DexLibLoader( 4439): Loaded 4 raw lines of metadata.
V/DexLibLoader( 4439): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
,V/DexLibLoader( 4439): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4439): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4439): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4439): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
,V/DexLibLoader( 4439): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4439): Dex already copied
D/OdexVerifier( 4439): Odex verification is skipped.
,V/DexLibLoader( 4439): Creating class loader
,V/DexLibLoader( 4439): Finished creating class loader
,V/DexLibLoader( 4439): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4439): Dex already copied
D/OdexVerifier( 4439): Odex verification is skipped.
,V/DexLibLoader( 4439): Creating class loader
V/DexLibLoader( 4439): Finished creating class loader
V/DexLibLoader( 4439): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4439): Dex already copied
D/OdexVerifier( 4439): Odex verification is skipped.
V/DexLibLoader( 4439): Creating class loader
V/DexLibLoader( 4439): Finished creating class loader
V/DexLibLoader( 4439): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4439): Dex already copied
D/OdexVerifier( 4439): Odex verification is skipped.
,V/DexLibLoader( 4439): Creating class loader
,V/DexLibLoader( 4439): Finished creating class loader
,V/DexLibLoader( 4439): Verifying classes from secondary dexes.
,D/DexLibLoader( 4439): DexLibLoader.ensureDexLoaded took 23 ms
,W/dalvikvm( 4439): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4439): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4439): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4439): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4439): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4439): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4439): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4439): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4439): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
D/wpa_supplicant( 1162): nl80211: Event message available
D/wpa_supplicant( 1162): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1162): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1162): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1162): nl80211: Survey data missing
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1162): Sorted scan results
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1162): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-46
I/wpa_supplicant( 1162): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-46
I/wpa_supplicant( 1162): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
I/wpa_supplicant( 1162): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-83
I/wpa_supplicant( 1162): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
D/wpa_supplicant( 1162): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1162): Add randomness: count=8 entropy=0
D/wpa_supplicant( 1162): Add randomness: count=9 entropy=1
D/wpa_supplicant( 1162): Add randomness: count=10 entropy=2
D/wpa_supplicant( 1162): Add randomness: count=11 entropy=3
D/wpa_supplicant( 1162): Add randomness: count=12 entropy=4
D/wpa_supplicant( 1162): Add randomness: count=13 entropy=5
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  912): doString: LIST_DONGLES
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1162): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1162): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1162): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1162): wpa_supplicant_pick_network+
I/wpa_supplicant( 1162): Selecting BSS from priority group 1
I/wpa_supplicant( 1162): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1162): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1162): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1162): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1162): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1162):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1162):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-46
I/wpa_supplicant( 1162): Start print parameters
I/wpa_supplicant( 1162): wpa_s->wpa_state is 3
I/wpa_supplicant( 1162): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1162): isConcurrentMode() is 0
I/wpa_supplicant( 1162): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1162): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1162): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1162): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1162): wpa_s->reassociate is 1
I/wpa_supplicant( 1162): wpa_s->is_screen_on 1
I/wpa_supplicant( 1162): wpa_s->ifname wlan0
I/wpa_supplicant( 1162): End print parameters
I/wpa_supplicant( 1162): selected network = 2
D/wpa_supplicant( 1162): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb776f4e8  current_ssid=0x0
D/wpa_supplicant( 1162): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1162): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1162): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1162): check if in concurrent case
,I/wpa_supplicant( 1162): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1162): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1162): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1162): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1162): RSN: PMKSA cache search - network_ctx=0xb776f4e8 try_opportunistic=0
D/wpa_supplicant( 1162): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1162): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1162): State: SCANNING -> ASSOCIATING
,D/wpa_supplicant( 1162): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1162): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1162): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1162): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1162): nl80211: Unsubscribe mgmt frames handle 0xb776e718 (mode change)
D/wpa_supplicant( 1162): nl80211: Subscribe to mgmt frames with non-AP handle 0xb776e718
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb776e718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb776e718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb776e718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb776e718
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb776e718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb776e718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb776e718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb776e718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb776e718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1162): nl80211: Register frame type=0xd0 nl_handle=0xb776e718
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1162): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1162):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1162):   * freq=2412
D/wpa_supplicant( 1162):   * Auth Type 0
D/wpa_supplicant( 1162):   * WPA Versions 0x2
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1162): nl80211: Connect request send successfully
D/wpa_supplicant( 1162): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  912): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  912): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  912): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1162): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1162): reply (778) for get BSS: id=0
I/wpa_supplicant( 1162): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1162): freq=5220
I/wpa_supplicant( 1162): level=-47
I/wpa_supplicant( 1162): tsf=0000000109401241
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=NG7005g
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=1
I/wpa_supplicant( 1162): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-46
I/wpa_supplicant( 1162): tsf=0000000109401255
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1162): ssid=01ABC
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=2
I/wpa_supplicant( 1162): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): freq=2412
I/wpa_supplicant( 1162): level=-46
I/wpa_supplicant( 1162): tsf=0000000109401259
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=NG700
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=3
I/wpa_supplicant( 1162): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1162): freq=2427
I/wpa_supplicant( 1162): level=-79
I/wpa_supplicant( 1162): tsf=0000000109401266
,I/wpa_supplicant( 1162): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1162): ssid=Gonzos
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=4
I/wpa_supplicant( 1162): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1162): freq=2437
I/wpa_supplicant( 1162): level=-83
I/wpa_supplicant( 1162): tsf=0000000109401270
I/wpa_supplicant( 1162): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1162): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1162): ====
I/wpa_supplicant( 1162): id=5
I/wpa_supplicant( 1162): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1162): freq=2437
I/wpa_supplicant( 1162): level=-93
I/wpa_supplicant( 1162): tsf=0000000109401274
I/wpa_supplicant( 1162): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1162): ssid=UPC4688432
I/wpa_supplicant( 1162): ####
D/WirelessDisplayService(  912): getDiscoveryDongleList
,D/WifiStateMachine(  912): == begin of scan result ==
,D/WifiStateMachine(  912): == (6) end of scan result ==
,D/WirelessDisplayService(  912): getDiscoveryDongleList
,W/ContextImpl(  912): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/WifiStateMachine(  912): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 109401241, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  912): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -46, frequency: 2412, timestamp: 109401255, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  912): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 2412, timestamp: 109401259, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  912): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 109401266, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  912): 4: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -83, frequency: 2437, timestamp: 109401270, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  912): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -93, frequency: 2437, timestamp: 109401274, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  912): add 6 to mScanResults
D/BatSI   (  912): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  912): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,E/FbInjectorInitializer( 4439): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/wpa_supplicant( 1162): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1162): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1162): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1162): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1162): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1162): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1162): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1162): nl80211: Event message available
D/wpa_supplicant( 1162): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1162): nl80211: Connect event
D/wpa_supplicant( 1162): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1162): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1162): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1162): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1162): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1162): Add randomness: count=14 entropy=6
I/wpa_supplicant( 1162): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1162): TDLS: Remove peers on association
D/wpa_supplicant( 1162): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1162): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1162): EAPOL: enable timer tick
D/wpa_supplicant( 1162): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1162): htc_wext_set_keepalive +
I/wpa_supplicant( 1162): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1162): getPrivFuncNum +	
I/wpa_supplicant( 1162): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1162): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1162): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1162): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1162): Get randomness: len=32 entropy=7
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  912): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  912): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  912): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  912): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  912): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  912): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  912): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  912): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  912): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  912): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  912): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  912): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  912): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  912): Enter handleAssociatedWithEvent
D/WifiStateMachine(  912): Associated
D/WifiStateMachine(  912): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  912): Exit handleAssociatedWithEvent
D/WifiStateMachine(  912): BSSID was changed, update WiFi database,
D/Tethering(  912): interfaceLinkStateChanged wlan0, false
D/Tethering(  912): interfaceStatusChanged wlan0, false
D/WifiApDatabaseHandler(  912): updateConnectedAP...
D/Tethering(  912): [isWifi] getHotspotEnabled: false
,D/WifiApDatabaseHandler(  912): updateConnectedAP...
D/Tethering(  912): interfaceLinkStateChanged wlan0, true
D/Tethering(  912): interfaceStatusChanged wlan0, true
,D/WifiStateMachine(  912): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/Tethering(  912): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  912): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  912): This record is existed, only update it...
,D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  912): updateConnectedAP...
I/wpa_supplicant( 1162): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb776e9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 1162):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1162): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1162): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f2db4a key_idx=1 set_tx=0 seq_len=6 key_len=16,
D/wpa_supplicant( 1162):    broadcast key
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1162): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1162): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1162): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1162): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1162): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
E/wpa_supplicant( 1162): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1162): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1162): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1162): set send_ind_to_ndc = 0
I/wpa_supplicant( 1162): htc_wext_set_TX_TRACKING (1)+
,I/wpa_supplicant( 1162): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1162): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1162): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1162): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1162): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1162): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1162): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1162): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1162): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1162): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1162): EAPOL authentication completed successfully
I/wpa_supplicant( 1162): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1162): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1162): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1162): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  912): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  912): interfaceLinkStateChanged wlan0, true
D/Tethering(  912): interfaceStatusChanged wlan0, true
D/Tethering(  912): [isWifi] getHotspotEnabled: false
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  912): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  912): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
,D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  912): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  912): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  912): updateConnectedAP...,
,D/WifiStateMachine(  912): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  912): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  912): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiApDatabaseHandler(  912): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  912): This record is existed, only update it...
,D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  912): updateConnectedAP...
,D/WifiDataStallTracker(  912): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  912): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  912): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  912): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  912): Provision feature enable=false
D/ConnectivityService(  912): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  912): updateConnectedAP...
D/WISPrService( 3808): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 3808): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/DhcpStateMachine(  912): [StoppedState] Start DHCP
D/WifiStateMachine(  912): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=50 [2][1][0]
D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  912): doBoolean: SignalStrength 97
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  912):    returned true
,D/WifiNative-wlan0(  912): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  912):    returned true
D/WifiNative-wlan0(  912): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): Power_Mode_Type mode = 1
I/wpa_supplicant( 1162): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  912):    returned true
D/WifiStateMachine(  912): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  912): acquireWL(43fb4180): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 912 1000 null
,D/WifiStateMachine(  912): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiNative-wlan0(  912): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  912):    returned null
E/WifiStateMachine(  912): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  912): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  912):    returned null,
D/WifiP2pService(  912): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@423aa998 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  912): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@423aa998 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:0
,W/fb4a(:<default>):StaticBindingVerifier( 4439): Verify
,D/WifiService(  912): New client listening to asynchronous messages
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4439/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4439): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4439): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4439): Grow heap (frag case) to 9.518MB for 73240-byte allocation
,D/Process (  912): killProcessQuiet, pid=3186
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  912): Killing 3186:com.android.defcontainer/u0a19 (adj 15): empty #17
,D/PMS     (  912): acquireWL(44007e10): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1226 10028 null
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  912): Recipient 3186
,D/PMS     (  912): acquireWL(4407c558): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1226 10028 null
,D/PMS     (  912): releaseWL(44007e10): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,D/GCM     ( 1384): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1384/10028)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1384/10028)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1384/10028)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,D/AutoSetting( 1403): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  912): releaseWL(4407c558): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,I/ActivityManager(  912): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4468 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.htc.sense.hsp (1403/10053)
,D/AutoSetting( 1403): Util - no network available!
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.htc.sense.hsp (1403/10053)
D/AutoSetting( 1403): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1403): service - mHandler: cancel location update
D/AutoSetting( 1403): service -           changes count: 0
,W/fb4a(:<default>):UserScope( 4439): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4439): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/MobileConnectivityChangeReceiver( 4468): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4468): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4468): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4468): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,W/fb4a(:<default>):UserScope( 4439): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/Process (  912): killProcessQuiet, pid=3858
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  912): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4482 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
I/ActivityManager(  912): Killing 3858:com.htc.mediamanager/u0a32 (adj 15): empty #17
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.setupwizard (4468/10078)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.setupwizard (4468/10078)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.setupwizard (4468/10078)
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4439): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  912): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4499 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  912): killProcessQuiet, pid=4201
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  912): Killing 4201:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,E/dalvikvm( 4439): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4439): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,E/dalvikvm( 4439): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4439): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4439): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4439): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4439): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4439): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4439): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4439): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4439): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4439): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4439): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4439): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4439): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4439): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4439): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4439): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
I/ActivityManager(  912): Recipient 4201
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  912): Client connection lost with reason: 4
I/ActivityManager(  912): Recipient 3858
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 4499): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,I/dalvikvm-heap( 4439): Grow heap (frag case) to 9.927MB for 39954-byte allocation
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4499): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAV2    ( 4499): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4499): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4499): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4439): Grow heap (frag case) to 10.003MB for 79892-byte allocation
,I/dalvikvm-heap( 4439): Grow heap (frag case) to 10.075MB for 84664-byte allocation
,I/dalvikvm-heap( 4439): Grow heap (frag case) to 10.102MB for 28144-byte allocation
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.magazines (4499/10151)
,V/WebViewChromiumFactoryProvider( 4499): Binding Chromium to main looper Looper (main, tid 1) {41b101c0}
,I/LibraryLoader( 4499): Expected native library version number "",actual native library version number ""
,I/chromium( 4499): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4499): Initializing chromium process, renderers=0
,D/PMS     (  912): acquireWL(4354b2f8): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,D/PMS     (  912): acquireWL(435c8518): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,E/AudioManagerAndroid( 4499): BLUETOOTH permission is missing!
D/PMS     (  912): releaseWL(435c8518): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4499): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4499): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4499): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4499): Local Branch: 
I/Adreno-EGL( 4499): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4499): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4499):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4499): Starting up...
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.magazines (4499/10151)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.magazines (4499/10151)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.plus (4135/10160)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.plus (4135/10160)
,D/Process (  912): killProcessQuiet, pid=4012
,I/ActivityManager(  912): Killing 4012:com.google.android.gm/u0a107 (adj 15): empty #17
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  912): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1862/10178)
,D/ConnectivityService(  912): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1862/10178)
I/dalvikvm-heap( 4439): Grow heap (frag case) to 10.289MB for 75760-byte allocation
D/GCM     ( 1384): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4439/10026)
,W/BroadcastQueue(  912): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43c2d6f0 u0 ReceiverList{43c2d5d0 4439 com.facebook.katana/10026/u0 remote:43c14f88}}
,W/BroadcastQueue(  912): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43c2d6f0 u0 ReceiverList{43c2d5d0 4439 com.facebook.katana/10026/u0 remote:43c14f88}}
,W/BroadcastQueue(  912): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{440649b8 u0 ReceiverList{4408bd90 4439 com.facebook.katana/10026/u0 remote:4408bcf0}}
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4439/10026)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4439/10026)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4439/10026)
,D/PMS     (  912): acquireWL(44002340): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1495 10028 null
,D/PMS     (  912): releaseWL(44002340): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/ActivityManager(  912): Recipient 4012
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/GCoreFlp( 1495): Unknown pending intent to remove.
D/PMS     (  912): acquireWL(435bb318): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1495 10028 null
D/PMS     (  912): releaseWL(435bb318): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4439): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4439): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,D/wpa_supplicant( 1162): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1162): EAPOL: disable timer tick
,D/libc    (  912): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  912): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  912): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  912): [NET] getaddrinfo-, SUCCESS
D/libc    (  912): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  912): [NET] getaddrinfo-, SUCCESS
D/libc    (  912): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  912): [NET] getaddrinfo-, SUCCESS
D/libc    (  912): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  912): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  912): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1162): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 61,
D/WifiNative-wlan0(  912):    returned true
,D/WifiNative-wlan0(  912): doBoolean: DRIVER BTCOEXMODE 2,
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12,
D/WifiNative-wlan0(  912):    returned true
D/WifiStateMachine(  912): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0,
D/WifiP2pService(  912): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  912): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  912): releaseWL(43fb4180): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5,
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=100 [1][1][0]
,D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative RSSI = -46 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  912): doBoolean: SignalStrength 97
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1162): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  912):    returned true
D/WifiStateMachine(  912): gateway: /192.168.1.1
,D/WifiNative-wlan0(  912): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  912):    returned true
,D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  912): VerifyingLinkState enter
D/WifiStateMachine(  912): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  912): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  912): VerifyingLinkState: enableIpv6
D/WIFI_ICON( 1119): updateWifiState: RSSI_CHANGED -1 -> 3
,D/WifiStateMachine(  912): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -46, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  912): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  912): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiDataStallTracker(  912): startDataStallAlarm: tag=20556 delay=15s
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
V/NetworkPolicy(  912): mWifiStateReceiver: meteredHint=false,EPS mode=false
,D/WISPrService( 3808): >>>>>WISPrService start isConnected = true<<<<<
,D/WifiWatchdogStateMachine(  912): WAN detection
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/WifiStateTracker(  912): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  912): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
,D/ConnectivityService(  912): Provision feature enable=false
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  912): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  912): syncGetConfiguredNetworks
D/ConnectivityService(  912): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  912): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  912): default: teardown()
D/ConnectivityService(  912): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1862/10178)
D/MDST    (  912): default: setTeardownRequested(true)
D/MDST    (  912): default: setEnableApn apnType =default , enable=false
D/MDST    (  912): default: setTeardownRequested(true)
D/ConnectivityService(  912): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED connected
D/libc    (  912): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  912): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WIFI_ICON( 1119): WifiActivity: 3
E/ConnectivityService(  912): Unexpected mtu value: android.net.wifi.WifiStateTracker@42437d40
D/ConnectivityService(  912): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/ConnectivityService(  912): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  912): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  365): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  912): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  912): handleConnectivityChange: resetting
D/Nat464Xlat(  912): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  912): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  912): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  912): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  912): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  912): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  912): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  912): acquireWL(425268e0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 912 1000 null
D/WirelessDisplayService(  912): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
D/WirelessDisplayService(  912):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
I/QuickSettingWifi( 1119): receive.wifiConnect:true wifiAPname:NG700 elapse:1
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  912): getNetworkInfo networkType=1 called by  (912/1000)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.setupwizard (4468/10078)
,D/PMS     (  912): acquireWL(4329cb10): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1226 10028 null
,D/PMS     (  912): acquireWL(435d6320): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1226 10028 null
,I//system/bin/ip(  365): RTNETLINK answers: No such file or directory
,I/logwrapper(  365): /system/bin/ip terminated by exit(254)
D/PMS     (  912): releaseWL(4329cb10): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,I/CheckinService( 1226): Preparing to send checkin request
,I/EventLogService( 1226): Accumulating logs since 1449754762253
,I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
,I/GoogleHttpClient( 1226): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1226): Using GMS GoogleHttpClient
,D/ConnectivityService(  912): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/PMS     (  912): releaseWL(425268e0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  912): getNetworkInfo networkType=9 called by com.google.android.gms (1226/10028)
D/ConnectivityService(  912): getNetworkInfo networkType=0 called by com.google.android.gms (1226/10028)
,W/GLSUser ( 1384): GoogleAccountDataService.getToken()
,W/GLSActivity( 1384): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1384): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1384): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1586): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1586): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1119): com.google.android.gms (false,0)
,W/CheckinRequestBuilder( 1226): awaiting user notification for token
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41e840c0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1119): com.google.android.gms 1 7 2 12
,I/ActivityManager(  912): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4574 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 4574): install
,I/MultiDex( 4574): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4574): loading existing secondary dex files
,I/MultiDex( 4574): load found 1 secondary dex files
,I/MultiDex( 4574): install done
,I/ProviderInstaller( 4574): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1384): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/PMS     (  912): Going to sleep due to screen timeout...
,I/SensorManager(  912): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421955e0
W/SensorService(  912): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  912): disable: get sensor name = CM36282 Light sensor
W/SensorService(  912): pid=912, uid=1000
,W/SensorService(  912): Active sensors: size = 2
W/SensorService(  912): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  912): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  912): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421955e0, eanble = 0, strlen(mName) = 59
W/SensorService(  912): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  912): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42341a40
W/SensorService(  912): Listener[1] = com.htc.smartdim.sensor_eye@41c7a750
,W/SensorService(  912): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  912): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  912): Couldn't get kernel wake lock stats
V/LightsService(  912): setLight #2: color=#0
D/qdlights(  912): set_light_buttons_func: on=0 brightness=0
V/LightsService(  912): setLight #0: color=#0
,D/WirelessDisplayService(  912): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  912): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  912): mWirelessDisplayManager is null
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (4574/10028)
,I/jxcore-log( 4367): BLE advertisement not supported: Build version is 19
I/jxcore-log( 4367): 
,D/SurfaceControl(  912): Excessive delay in blankDisplay() while turning screen off: 370ms
D/NfcService( 1259): ScreenObserver: OFF
,D/NfcService( 1259): applyRouting - 0
,V/KeyguardServiceDelegate(  912): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42255a68)
,D/NfcService( 1259): applyRouting -2
D/PMS     (  912): nativeSetInteractive:false
D/PMS     (  912): nativeSetInteractive:false done
D/PMS     (  912): nativeSetAutoSuspend:true
D/PMS     (  912): nativeSetAutoSuspend:true done
D/HABCtrl (  912): TPE algorithm. remove timeout.
D/PMS     (  912): OOBE c monitor 11
I/InputManager(  912): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  912): screenObserver, isScreenOn=false
I/InputMethodManagerService(  912): Disable input method client, pid=4367
D/PMN     (  912): wakingUp
D/PMS     (  912): acquireWL(42e61450): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1259 1027 null
,D/PMS     (  912): releaseWL(42e61450): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/KeyguardServiceDelegate(  912): **** SHOWN CALLED ****
I/WindowManager(  912): No lock screen! windowToken=null
,W/ResourceType( 4367): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4367): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41b183b0 VFEDH.C. .F...... 0,0-720,1134 #64}
,I/IntentController( 1119): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMN     (  912): onScreenOn
D/PMS     (  912): acquireWL(43e275a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
D/WirelessDisplayService(  912): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  912): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  912): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  912): releaseWL(43e275a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  912): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=100
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/MtpService( 1995): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  912): releaseWL(44003098): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
D/MtpService( 1995): [MTP][onReceive]-
,D/NfcService( 1259): applyRouting - 0
,D/AutoSetting( 1403): receiver - intent: android.intent.action.USER_PRESENT
,D/NfcService( 1259): applyRouting -2
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/ConnectivityService(  912): NetTransition Wakelock for ConnectedState released by timeout
D/AlarmManager(  912): ACTION_SCREEN_ON
I/AlarmManager(  912): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  912): [AlarmQueuing] done recovering
I/AlarmManager(  912): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  912): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  912): acquireWL(42dc7060): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1259 1027 null
D/PMS     (  912): releaseWL(42dc7060): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,D/TetherSettings( 3808): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/AutoSetting( 1403): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/        ( 3808): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3808): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3808): Cust_ConnectToPC   : spcsc>false
D/        ( 3808): Cust_ConnectToPC   : IPT>true
D/        ( 3808): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3808): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3808): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3808): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3808): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/WIFI_ICON( 1119): WifiActivity: 1
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  912): << updateStatus
,D/ConnectivityService(  912): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/PSReceiver( 3808): onReceive:android.intent.action.USER_PRESENT
D/WirelessDisplayService(  912): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  912): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  912): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiDataStallTracker(  912): onReceive: action=android.intent.action.SCREEN_ON
V/Tethering(  912): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/WifiDataStallTracker(  912): startDataStallAlarm: tag=20557 delay=15s
I/SmartNS_PSService( 3808): onReceive:android.intent.action.USER_PRESENT
,W/Settings( 3808): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3808):  defaultType:0
,I/ClockThread( 1119): stop update clock
V/NotificationService(  912): batLight: Full, plugged
V/LightsService(  912): setLight #8: color=#c8c800
D/qdlights(  912): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  912): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  912): setLight #8: color=#c800
D/qdlights(  912): set_color_led color=51200, mode=1, off_min=0, off_sec=0
W/ContextImpl( 3808): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/qdlights(  912): [LedInfo] has indicator attribute
D/qdlights(  912): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  912): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,V/Tethering(  912): bSetPropertyMultiRAB:false
,D/Tethering(  912): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,I/Tethering(  912): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
,I/Tethering(  912): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
I/AlarmManager(  912): [AlarmQueuing] connectivity wifi: true
D/ConnectivityService(  912): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1862/10178)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1902/1000)
D/ConnectivityService(  912): getNetworkInfo networkType=1 called by com.htc.launcher (1274/10075)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.docs (4258/10100)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1495/10028)
W/AppWidgetServiceImpl(  912): updateAppWidget failed! callbacks null
I/ConnectivityHelper( 1274): [onReceive] WIFI(1): CONNECTED
I/acms    ( 1902): Checking Certificates
I/acms    ( 1902): Checking Developer Certificates
I/Tethering(  912): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  912): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  912): Found interface wlan0
D/Tethering(  912): TetherMasterSM: InitialState processMessage what=3
,I/acms    ( 1902): Checking Application Certificates
I/acms    ( 1902): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1902): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
D/GpsLocationProvider(  912): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  912): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  912): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  912): ignore wifi update if we are not in OPENING or CLOSING
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
I/acms    ( 1902): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1902): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1902): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/NetworkMonitor( 3877): type=WIFI subType= reason=null isConnected=true
I/acms    ( 1902): Updating next query delay: 75600000
I/mlserverapp( 1902): MirrorLink is never connected, don't setup ACMS programed checks
,I/mlserverapp( 1902): cancelACMSProgrammedChecks
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  912): NoActiveNetworkState
D/ConnectivityService(  912): getNetworkInfo networkType=1 called by  (912/1000)
D/ConnectivityService(  912): getNetworkInfo networkType=1 called by com.google.android.music (3877/10154)
D/PMS     (  912): acquireWL(41b9d2d0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 912 1000 null
D/PMS     (  912): releaseWL(41b9d2d0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.setupwizard (4468/10078)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.htc.musicenhancer (3899/10051)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,D/CaptivePortalTracker(  912): DelayedCaptiveCheckState
D/htcCheckinService(  912): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  912): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,D/WifiNative-wlan0(  912): doBoolean: SET_SCREEN_ON 1
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4439/10026)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.docs (4258/10100)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/PMS     (  912): acquireWL(421969b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4439/10026)
D/PMS     (  912): releaseWL(421969b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4439/10026)
W/AppWidgetServiceImpl(  912): updateAppWidget failed! callbacks null
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,I/ActivityManager(  912): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4601 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
W/Settings( 4574): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiStateMachine(  912): BroadcastRSSIForIMS, newrssi =-47 , oldRssi= -200
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): SET_SCREEN_ON:On
I/wpa_supplicant( 1162): htc_wext_set_keepalive +
I/wpa_supplicant( 1162): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1162): getPrivFuncNum +	
I/wpa_supplicant( 1162): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1162): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1162): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1162): htc_wext_set_TX_TRACKING (1)+
,I/wpa_supplicant( 1162): htc_wext_set_TX_TRACKING - ret = 0
,D/WifiNative-wlan0(  912):    returned true
,D/WIFI_ICON( 1119): updateWifiState: RSSI_CHANGED 3 -> 3
,D/WifiNative-wlan0(  912): doBoolean: SignalStrength 97
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1162): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  912):    returned true
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1119): WifiActivity: 0
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
V/NotificationService(  912): batLight: Full, plugged
V/LightsService(  912): setLight #8: color=#c8c800
D/qdlights(  912): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  912): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  912): setLight #8: color=#c800
D/qdlights(  912): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/qdlights(  912): [LedInfo] has indicator attribute
D/qdlights(  912): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,V/SRS_Proc(  372): ParamSet string: screen_state=on
,D/qdlights(  912): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/WirelessDisplayService(  912): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
W/ContextImpl( 4601): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/NetworkPolicy(  912): updateScreenOn: false
,D/SmartSyncUtils( 4601): isEpsOn(), nState = 0
,D/PMS     (  912): acquireWL(436d0fe0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4601 1000 null
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/PMS     (  912): releaseWL(436d0fe0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4601): getMobilePolicyEnabled, result = true
W/ContextImpl(  912): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  912): killProcessQuiet, pid=4228
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  912): Killing 4228:com.google.android.partnersetup/u0a31 (adj 15): empty #17
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1995/10021)
,I/ActivityManager(  912): Recipient 4228
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  912): acquireWL(43121660): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1226 10028 null
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1822): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1822): onScreenOn: 1449754819368
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1822): onScreenOn: 1449754819368
D/PMS     (  912): acquireWL(43c19078): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1495 10028 null
D/PMS     (  912): releaseWL(43121660): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/PMS     (  912): releaseWL(43c19078): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/Adreno-EGL( 4574): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4574): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4574): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4574): Local Branch: 
I/Adreno-EGL( 4574): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4574): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4574):                  aa63bbd948f41d15fc72f585e
,I/SensorManager(  912): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42341a40
W/SensorService(  912): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  912): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  912): pid=912, uid=1000
W/SensorService(  912): Active sensors: size = 2
W/SensorService(  912): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  912): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  912): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42341a40, eanble = 0, strlen(mName) = 91
W/SensorService(  912): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  912): Listener[0] = com.htc.smartdim.sensor_eye@41c7a750
,W/SensorService(  912): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/GCM     ( 1384): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/PMN     (  912): goingToSleep
D/PMS     (  912): acquireWL(4404c2c8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 912 1000 null
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1384/10028)
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1384/10028)
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1384/10028)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,D/PMS     (  912): acquireWL(437a0358): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1384 10028 null
D/AlarmManager(  912): ACTION_SCREEN_OFF
D/libc    ( 1384): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1384): [NET] getaddrinfo-,err=8
D/libc    ( 1384): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1384): [NET] getaddrinfo-, 1
D/libc    ( 1384): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =5dec +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET] NOT IN CACHE
D/WifiDataStallTracker(  912): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  912): stopDataStallAlarm: current tag=20557 mDataStallAlarmIntent=PendingIntent{4214eb70: PendingIntentRecord{4234fa40 android broadcastIntent}}
,D/WifiNative-wlan0(  912): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1162): SET_SCREEN_ON:Off
I/wpa_supplicant( 1162): htc_wext_set_keepalive +
I/wpa_supplicant( 1162): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1162): getPrivFuncNum +	
I/wpa_supplicant( 1162): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1162): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1162): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1162): htc_wext_set_keepalive gateway addr = c0a80101
D/WifiNative-wlan0(  912): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 1162): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  912):    returned true
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
I/AlarmManager(  912): [AlarmQueuing] screen off now: 
I/AlarmManager(  912): [AlarmQueuing] data connection: true
I/AlarmManager(  912): [AlarmQueuing] wifi connection: true
D/PMS     (  912): releaseWL(4404c2c8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/PMS     (  912): acquireWL(43c09d50): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 912 1000 null
,V/SRS_Proc(  372): ParamSet string: screen_state=off
D/NetworkPolicy(  912): updateScreenOn: false
,D/AutoSetting( 1403): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/MobileConnectivityChangeReceiver( 4468): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4468): onReceive CONNECTIVITY_CHANGE networkType=1
,D/wpa_supplicant( 1162): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  912):    returned true
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/AutoSetting( 1403): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/ConnectivityService(  912): getActiveNetworkInfo called by com.htc.sense.hsp (1403/10053)
D/PMS     (  912): releaseWL(43c09d50): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.magazines (4499/10151)
D/AutoSetting( 1403): service - onStartCommand() screen is off, don't request location
,D/AutoSetting( 1403): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1403): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  912): getActiveNetworkInfo called by com.htc.sense.hsp (1403/10053)
,I/Adreno-EGL( 4574): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4574): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4574): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4574): Local Branch: 
I/Adreno-EGL( 4574): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4574): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4574):                  aa63bbd948f41d15fc72f585e
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.plus (4135/10160)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.plus (4135/10160)
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  912): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1862/10178)
,D/ContactMessageStore( 1248): start background delete task...
D/ContactMessageStore( 1248): size: 0 , 0
,D/ContactMessageStore( 1248): Background delete complete
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,I/Adreno-EGL( 4574): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4574): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4574): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4574): Local Branch: 
I/Adreno-EGL( 4574): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4574): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4574):                  aa63bbd948f41d15fc72f585e
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
,W/ContextImpl( 4601): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
I/SensorManager(  912): mEventCount = 1500
,D/SmartSyncUtils( 4601): isEpsOn(), nState = 0
D/AutoSetting( 1403): service - mHandler: cancel location update
,D/AutoSetting( 1403): service -           changes count: 0
,D/SmartSyncUtils( 4601): getMobilePolicyEnabled, result = true
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] getTotalRam: 1873 Mb
,D/SmartSyncUtils( 4601): isEpsOn(), nState = 0
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1822): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1822): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1822): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1822): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1822): onScreenOff
D/WifiService(  912): New client listening to asynchronous messages
D/PMS     (  912): acquireWL(43b47f60): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1495 10028 null
D/PMS     (  912): releaseWL(43b47f60): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,W/ContextImpl(  912): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,I/SensorManager(  912): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41c7a750
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4439/10026)
W/SensorService(  912): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  912): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  912): pid=912, uid=1000
W/SensorService(  912): Active sensors: size = 1
W/SensorService(  912): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  912): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41c7a750, eanble = 0, strlen(mName) = 36
W/SensorService(  912): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  912): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  912): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  912): disable: get sensor name = CM36282 Proximity sensor
,W/SensorService(  912): pid=912, uid=1000
W/SensorService(  912): Active sensors: size = 0
,W/SensorService(  912): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41c7a750, eanble = 0, strlen(mName) = 36
,W/SensorService(  912): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  912): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  912): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41c7a750
D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4439/10026)
,E/ActivityThread(  912): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@41cd85e8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  912): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@41cd85e8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  912): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  912): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  912): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  912): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  912): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  912): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  912): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  912): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  912): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  912): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  912): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  912): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  912): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  912): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  912): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  912): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  912): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  912): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  912): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  912): 	at dalvik.system.NativeStart.main(Native Method)
I/CheckinTask( 1226): Sending checkin request (8845 bytes)
D/libc    ( 1226): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1226): [NET] getaddrinfo-,err=8
D/libc    ( 1226): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1226): [NET] getaddrinfo-, 1
D/libc    ( 1226): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =a437 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 220
D/libc    (  365): [NET]res_nsend:resplen=79
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1384): [NET] getaddrinfo_proxy-, success
,W/fb4a(:<default>):UserScope( 4439): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4439): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4439/10026)
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 124
D/libc    (  365): [NET]res_nsend:resplen=84
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1226): [NET] getaddrinfo_proxy-, success
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=50 [2][1][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [1][0][0]
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4439/10026)
,D/libc    ( 1384): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1384): [NET] getaddrinfo-,err=8
D/libc    ( 1226): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1384/10028)
,D/PMS     (  912): acquireWL(43b507f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1384 10028 null
,D/libc    ( 1226): [NET] getaddrinfo-,err=8
D/PMS     (  912): releaseWL(43b507f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,E/fb4a(:<default>):LocalFbBroadcastManager( 4439): Called registerBroadcastReceiver twice.
,D/GCM     ( 1384): Connected
,D/PMS     (  912): acquireWL(42543b28): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1384 10028 null
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1384/10028)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1384/10028)
D/PMS     (  912): releaseWL(437a0358): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1384/10028)
D/ConnectivityService(  912): reportInetCondition for net 1, percentage: 100 by  (1384/10028)
D/ConnectivityService(  912): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  912): handleInetConditionChange: starting a change hold
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1384/10028)
D/PMS     (  912): releaseWL(42543b28): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  912): acquireWL(43b43850): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1384 10028 null
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1384/10028)
,D/ConnectivityService(  912): reportInetCondition for net 1, percentage: 100 by  (1384/10028)
D/ConnectivityService(  912): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/GCM     ( 1384): Message class mpf
D/ConnectivityService(  912): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1384/10028)
D/ConnectivityService(  912): reportInetCondition for net 1, percentage: 100 by  (1384/10028)
D/ConnectivityService(  912): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  912): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1384/10028)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4439/10026)
,D/PMS     (  912): releaseWL(43b43850): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4439/10026)
D/PMS     (  912): acquireWL(43c07ed8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1384 10028 null
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4439/10026)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4439/10026)
,D/PMS     (  912): releaseWL(43c07ed8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4439/10026)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4439/10026)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4439/10026)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4439/10026)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4439/10026)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4439/10026)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4439/10026)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4439/10026)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4439/10026)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4439/10026)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4439/10026)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4439/10026)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4439/10026)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4439/10026)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4439/10026)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4439/10026)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4439/10026)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4439/10026)
,D/PMS     (  912): releaseWL(4354b2f8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/PMS     (  912): acquireWL(425ede28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1384 10028 null
,D/PMS     (  912): releaseWL(425ede28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  912): getNetworkInfo networkType=9 called by com.google.android.gms (1226/10028)
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  912): getNetworkInfo networkType=0 called by com.google.android.gms (1226/10028)
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=5 [20][1][0]
,W/GLSUser ( 1384): GoogleAccountDataService.getToken()
,W/GLSActivity( 1384): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1384): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1384): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1586): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1586): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 1226): awaiting user notification for token
,I/RemoteViews( 1119): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41e1f110 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1119): com.google.android.gms 2 10 3 12
,I/CheckinTask( 1226): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 1226): Unable to close GMS GoogleHttpClient
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,D/GCM     ( 1384): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  912): releaseWL(435d6320): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 1226): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41d9b828 that was originally bound here
E/ActivityThread( 1226): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41d9b828 that was originally bound here
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
,I/GCM     ( 1384): GCM config loaded
,D/ConnectivityService(  912): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  912): sendGeneralBroadcast, restrictEnable=false
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  912): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
,E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1162): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1162): nl80211: survey data missing!
E/wpa_supplicant( 1162): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1162): environment dirty rate=0 [0][0][0]
,D/libc    (  912): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  912): [NET] getaddrinfo-,err=8
D/libc    (  912): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  912): [NET] getaddrinfo-, 1
,D/libc    (  912): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =2a9f +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 2
D/libc    (  365): [NET]res_nsend:resplen=172
D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  912): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  912): Find DNS Address www.htc.com/23.59.123.86
,I/GAV2    ( 4499): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  912): acquireWL(43bcb848): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1495 10028 null
,D/PMS     (  912): acquireWL(43c0e520): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1495 10028 null
,D/PMS     (  912): releaseWL(43bcb848): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  912): releaseWL(43c0e520): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/AutoSetting( 1512): service - handleMessage() stop self
,D/AutoSetting( 1512): service - onDestroy() END
,D/AutoSetting( 1512): service - handleMessage() quit looper
,D/Process (  912): killProcessQuiet, pid=4258
,I/ActivityManager(  912): Killing 4258:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/WifiStateMachine(  912): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  912): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  912): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent DefaultState
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  912): Recipient 4258
,D/Process (  912): killProcessQuiet, pid=4281
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  912): Killing 4281:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  912): Recipient 4281
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CaptivePortalTracker(  912): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  912): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  912): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  912): acquireWL(43fc4150): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/PMS     (  912): releaseWL(43fc4150): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): runPSCheck
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  912): << updateStatus
,W/AppWidgetServiceImpl(  912): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  912): acquireWL(43f4ea48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{423992f8: PendingIntentRecord{424d8d40 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142144, Int=0
,V/AlarmManager(  912): sending alarm PendingIntent{423a3240: PendingIntentRecord{42649168 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142757, Int=0
,D/AutoSetting( 1403): service - mHandler: update timezone
,D/AutoSetting( 1403): service - handleMessage() stop self
,D/GpsLocationProvider(  912): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  912): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  912): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  912): acquireWL(4355e140): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 912 1000 null
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1384/10028)
,D/AutoSetting( 1403): service - handleMessage() quit looper
,D/AutoSetting( 1403): service - onDestroy() END
,D/AutoSetting( 1512): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
D/libc    (  912): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  912): [NET] getaddrinfo-,err=8
D/libc    (  912): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  912): [NET] getaddrinfo-, 1
,D/libc    (  912): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/PMS     (  912): releaseWL(43f4ea48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  912): acquireWL(44050c20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1384 10028 null
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =d41e +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
W/ActivityManager(  912): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/PMS     (  912): releaseWL(44050c20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/AutoSetting( 1512): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1512): service - onCreate()
,W/ActivityManager(  912): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1512): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1512): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,V/NotificationService(  912): batLight: Full, plugged
V/LightsService(  912): setLight #8: color=#c8c800
D/qdlights(  912): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  912): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  912): setLight #8: color=#c800
D/qdlights(  912): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  912): [LedInfo] has indicator attribute
D/qdlights(  912): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  912): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/DotMatrix( 1586): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
D/AutoSetting( 1512): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1512): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1512): service - mHandler: update timezone
D/DotMatrix( 1586): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,D/AutoSetting( 1512): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1512): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1512): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1512): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1586): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1586): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1119): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41ca1900 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1119): com.htc.htclocationservice 2 6 2 11
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  365): [NET]res_nsend:resplen=243
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=10
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  912): [NET] getaddrinfo_proxy-, success
I/global  (  912): call createSocket() return a new socket.
D/libc    (  912): [NET] getaddrinfo+,hn 13(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  912): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  912): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  912): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  912): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  912):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  912): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  912): releaseWL(4355e140): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  912): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/Process (  912): killProcessQuiet, pid=3899
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  912): Killing 3899:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  912): Recipient 3899
,D/PMS     (  912): acquireWL(43ff4dc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{4232b9e0: PendingIntentRecord{42340d80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=153229, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(43ff4dc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ActivityManager(  912): Waited long enough for: ServiceRecord{43b4daa0 u0 com.htc.htclocationservice/.AutoSettingService}
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  912): acquireWL(43fcfeb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
,D/PowerUI ( 1119): closing low battery warning: level=100
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): runPSCheck
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/PMS     (  912): releaseWL(43fcfeb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,W/AppWidgetServiceImpl(  912): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 1512): service - handleMessage() stop self
,D/AutoSetting( 1512): service - onDestroy() END
,D/AutoSetting( 1512): service - handleMessage() quit looper
,D/Process (  912): killProcessQuiet, pid=4245
,I/ActivityManager(  912): Killing 4245:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  912): Recipient 4245
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TelephonyReceiver( 1248): switchBindHtcMsgCursor: null
,D/PMS     (  912): acquireWL(43bfbca8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  912): releaseWL(43bfbca8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,W/AppWidgetServiceImpl(  912): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  912): acquireWL(43bc97d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{4232b9e0: PendingIntentRecord{42340d80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=213228, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(43bc97d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(43ba0df8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{10026}
,V/AlarmManager(  912): sending alarm PendingIntent{43c2c810: PendingIntentRecord{429b54e0 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=230339, Int=0
,I/ActivityManager(  912): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4655 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  912): sending alarm PendingIntent{424fc408: PendingIntentRecord{424f5bd0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1449754928314, Int=10800000
,D/PMS     (  912): releaseWL(43ba0df8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.htc.aurora (4655/10047)
,D/Process (  912): killProcessQuiet, pid=4298
,I/ActivityManager(  912): Killing 4298:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  912): Recipient 4298
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,D/PMS     (  912): acquireWL(43b5c9c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(43b5c9c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,W/AppWidgetServiceImpl(  912): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(435c6c18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{10026}
,V/AlarmManager(  912): sending alarm PendingIntent{4241a960: PendingIntentRecord{43ba4f30 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=232236, Int=120000
,V/AlarmManager(  912): sending alarm PendingIntent{425032e8: PendingIntentRecord{429b54e0 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=232640, Int=0,
,D/PMS     (  912): releaseWL(435c6c18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  912): acquireWL(435c2d08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): releaseWL(435c2d08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,W/AppWidgetServiceImpl(  912): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  912): acquireWL(426533e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{4232b9e0: PendingIntentRecord{42340d80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=273228, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(426533e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  912): acquireWL(424d0858): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(424d0858): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  912): acquireWL(4237dc70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(4237dc70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  912): acquireWL(4201fab0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{4232b9e0: PendingIntentRecord{42340d80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=333228, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(4201fab0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}

```
