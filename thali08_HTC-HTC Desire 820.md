#### Test 55742142a5c2fdb_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/WIFI_ICON( 1114): WifiActivity: 0
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1114): WifiActivity: 1
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
--------- beginning of /dev/log/main
E/cutils-trace( 4317): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4317): ====startRecUseTime====
D/htc.customization.log.level( 4317):  is 
W/CustomizationLogLevel( 4317): Level value is invalid, use default level 2
D/CustomizationManager( 4317):  Read ACC file spent 0.050 (s)
D/CIDMapFileReader( 4317): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4317): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4317): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4317): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4317): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4317): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4317): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4317): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4317): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4317): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4317): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4317): Parsing tag category name = system
I/CustomizationCIDLoader( 4317): Parsing tag category name = application
I/CustomizationCIDLoader( 4317): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4317): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4317): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4317): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4317): Parsing tag category name = Settings
D/CustomizationManager( 4317):  Read CID file spent 0.089 (s)
D/CustomizationManager( 4317):  All configurations done spent 0.089 (s)
W/HtcNativeFlag( 4317): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4317): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4317): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4317): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  903): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  903): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  903): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  903): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  903): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  903): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  903): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4317
D/PMS     (  903): acquireHCC(425a0860): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 903 1000 null
D/PMS     (  903): acquireHCC(42402ab8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 903 1000 null
W/asset   (  903): Copying FileAsset 0x6345c518 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  903): @test_code: getHtcIntentFlag: 0 obj: 1113705928
I/FeedHostManager( 1270): [onPause]
I/FeedProviderManager( 1270): onPause
I/SocialFeedProvider( 1270): +onPause
I/SocialFeedProvider( 1270): -onPause
I/FeedHostManager( 1270): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@42294d38
D/PMS     (  903): acquireWL(422b8d90): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 903 1000 null
I/ActivityManager(  903): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4328 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1270): [trimMemory] 20
W/asset   ( 4328): Copying FileAsset 0x5c8d9428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4328): Binding Chromium to main looper Looper (main, tid 1) {41b71548}
I/LibraryLoader( 4328): Expected native library version number "",actual native library version number ""
I/chromium( 4328): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4328): Initializing chromium process, renderers=0
D/PMS     (  903): acquireWL(4203eac8): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
W/System.err(  903): java.lang.Throwable: stack dump
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  903): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4269afd8:true
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  903): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  903): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4328): 1102606208: getState(). Returning 12
D/PMS     (  903): acquireWL(434a2f00): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  903): releaseWL(4203eac8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4328): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4328): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4328): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4328): Local Branch: 
I/Adreno-EGL( 4328): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4328): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4328):                  aa63bbd948f41d15fc72f585e
W/chromium( 4328): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4328): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4328): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4328): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4328): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4328): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4328): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4328): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4328): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4328): CordovaWebView is running on device made by: HTC
,W/AwContents( 4328): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  903): Disable input method client, pid=1270
,W/ResourceType( 4328): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4328): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41bb8630, mServedView=org.apache.cordova.engine.SystemWebView{41b7e298 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1208): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
,I/InputMethodManagerService(  903): Enable input method client, pid=4328
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1208): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,W/AwContents( 4328): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  903): Displayed com.test.thalitest/.MainActivity: +277ms
D/PMS     (  903): releaseWL(422b8d90): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4328): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4328): JniHelper::setJavaVM(0x41641048), pthread_self() = 1663514360
,D/JX-Cordova( 4328): jxcore cordova android initializing
,D/WIFI_ICON( 1114): WifiActivity: 0
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1158): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,I/dalvikvm-heap( 4328): Grow heap (frag case) to 11.593MB for 96598-byte allocation
,I/dalvikvm-heap( 4328): Grow heap (frag case) to 11.673MB for 144892-byte allocation
,I/dalvikvm-heap( 4328): Grow heap (frag case) to 11.789MB for 217334-byte allocation
,I/dalvikvm-heap( 4328): Grow heap (frag case) to 11.965MB for 325996-byte allocation
,I/dalvikvm-heap( 4328): Grow heap (frag case) to 12.240MB for 488990-byte allocation
,I/dalvikvm-heap( 4328): Grow heap (frag case) to 13.247MB for 1100216-byte allocation
,I/dalvikvm-heap( 4328): Grow heap (frag case) to 14.118MB for 1650320-byte allocation
,I/ActivityManager(  903): Waited long enough for: ServiceRecord{4412e700 u0 com.htc.htclocationservice/.AutoSettingService}
,I/dalvikvm-heap( 4328): Grow heap (frag case) to 15.489MB for 2475476-byte allocation
,I/dalvikvm-heap( 4328): Grow heap (frag case) to 17.498MB for 3713210-byte allocation
,W/jxcore-log( 4328): Initializing JXcore engine
,W/jxcore-log( 4328): JXcore engine is ready
,W/CpuWake (  903): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  903): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  903): >>release mCpuPerf_cpu_count wakelock
,W/CpuWake (  903): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  903): >>release mCpuPerf_Freq wakelock
,D/PMS     (  903): releaseHCC(425a0860): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,W/CpuWake (  903): <<release mCpuPerf_Freq wakelock
,D/PMS     (  903): releaseHCC(42402ab8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4328): Starting JXcore engine
,W/jxcore-log( 4328): Platform android
W/jxcore-log( 4328): 
,W/jxcore-log( 4328): Process ARCH arm
W/jxcore-log( 4328): 
,D/WIFI_ICON( 1114): WifiActivity: 1
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/jxcore-log( 4328): JXcore Cordova bridge is ready!
I/jxcore-log( 4328): 
,W/jxcore-log( 4328): JXcore engine is started
,I/Choreographer( 4328): Skipped 138 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4328): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PMS     (  903): releaseWL(434a2f00): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/WIFI_ICON( 1114): WifiActivity: 0
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/ActivityManager(  903): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4372 uid=10077 gids={50077}
,D/PMS     (  903): acquireWL(424f4870): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10077}
V/AlarmManager(  903): sending alarm PendingIntent{42551eb0: PendingIntentRecord{425138d8 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1452600966404, Int=60000
,D/PMS     (  903): releaseWL(424f4870): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,I/SensorManager(  903): mEventCount = 1350
,D/SMSBackup( 4372): SMSBackupAgentService started
,D/SMSBackup( 4372): Checking restore status
D/SMSBackup( 4372): Restore complete
,D/SMSBackup( 4372): cancelCheckAlarm
,D/SMSBackup( 4372): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  903): killProcessQuiet, pid=3594
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3594:com.htc.task/u0a70 (adj 15): empty #17
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1158): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,I/ActivityManager(  903): Recipient 3594
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  903): acquireWL(41f7f6a0): PARTIAL_WAKE_LOCK  Icing 0x1 2240 10028 null
,D/PMS     (  903): releaseWL(41f7f6a0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  903): acquireWL(42468e40): PARTIAL_WAKE_LOCK  Icing 0x1 2240 10028 null
,D/PMS     (  903): releaseWL(42468e40): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  903): acquireWL(423c16a0): PARTIAL_WAKE_LOCK  Icing 0x1 2240 10028 null
,D/PMS     (  903): releaseWL(423c16a0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  903): acquireWL(42566cf8): PARTIAL_WAKE_LOCK  Icing 0x1 2240 10028 null
,D/PMS     (  903): releaseWL(42566cf8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/jxcore-log( 4328): Toggling radios to true
I/jxcore-log( 4328): 
,D/BluetoothAdapter( 4328): enable(): BT is already enabled..!
,D/WifiManager( 4328): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
W/HtcDLNAServiceManager(  903): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  903): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  903): Settings:Agentvalue: 2
W/Settings:Agent(  903): >> traceCallingStack()
W/Settings:Agent(  903): Process.myPid(): 903
W/Settings:Agent(  903): Process.myTid(): 1350
W/Settings:Agent(  903): Process.myUid(): 1000
W/Settings:Agent(  903): 
W/Settings:Agent(  903): 
W/System.err(  903): java.lang.Throwable: stack dump
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  903): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  903): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  903): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  903): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  903): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  903): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  903): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  903): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
,W/System.err(  903): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  903): 
W/Settings:Agent(  903): << traceCallingStack(): 1(ms)
,D/WifiManager( 4328): disconnect: Base Package Name=com.test.thalitest, uid=10348
D/WifiNative-wlan0(  903): doBoolean: DISCONNECT
D/WifiManager( 4328): reconnect: Base Package Name=com.test.thalitest, uid=10348
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT",
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1158): TDLS: Tear down peers
,I/wpa_supplicant( 1158): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4328): Radios toggled
I/jxcore-log( 4328): 
,D/BluetoothManagerService(  903): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiService(  903): New client listening to asynchronous messages
D/WifiService(  903): setWifiEnabled: true pid=4328, uid=10348
E/WifiService(  903): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  903): isSprintWifiRestricted(): false
I/WifiService(  903): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  903): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
D/BluetoothManagerService(  903): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4328): Received device characteristics:
I/jxcore-log( 4328): Bluetooth address: 80:01:84:8A:B3:68
I/jxcore-log( 4328): Bluetooth name: HTC Desire 820
I/jxcore-log( 4328): Device name: HTC-HTC Desire 820
I/jxcore-log( 4328): 
I/jxcore-log( 4328): Perf Test app loaded loaded
I/jxcore-log( 4328): 
I/Choreographer( 4328): Skipped 94 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 4328): check test folder
I/jxcore-log( 4328): 
,I/jxcore-log( 4328): found test : ./testFindPeers.js
I/jxcore-log( 4328): 
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1158): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1158): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1158): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  903): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  903): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  903): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  903): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  903): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1158): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1158): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1158): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1158): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1158): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1158): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1158): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1158): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1158): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1158): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb81d4bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1158):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1158): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1158): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1158): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1158): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1158): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1158): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1158): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1158): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1158): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1158): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1158): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1158): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1158): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1158): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1158): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1158): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1158): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1158): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1158): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1158): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1158): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1158): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1158): htc_wext_set_TX_TRACKING (0),+
I/wpa_supplicant( 1158): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1158): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1158): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1158): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1158): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1158): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1158): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1158): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1158): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1158): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1158): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1158): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1158): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1158): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1158): nl80211: Event message available
D/wpa_supplicant( 1158): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1158): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/Tethering(  903): interfaceLinkStateChanged wlan0, false
D/Tethering(  903): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  903):    returned true
D/WifiPerfLock(  903): release()
,D/WifiStateMachine(  903): PerfLock released for exiting ConnectedState
I/jxcore-log( 4328): found test : ./testSendData.js
I/jxcore-log( 4328): 
,D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/ConnectivityService(  903): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
,D/PMS     (  903): acquireWL(426523d0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 903 1000 null
D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1158): Power_Mode_Type mode = 0
I/wpa_supplicant( 1158): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 61
D/Tethering(  903): interfaceLinkStateChanged wlan0, false
D/WifiNative-wlan0(  903):    returned true
D/Tethering(  903): interfaceStatusChanged wlan0, false
D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1158): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  903):    returned true
,D/libc    (  903): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/DhcpStateMachine(  903): [RunningState] Stop DHCP
D/WifiP2pService(  903): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  903): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  903): doBoolean: RECONNECT
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1158): Fast associate: Old scan results
I/wpa_supplicant( 1158): wpa_supplicant_scan enter
I/wpa_supplicant( 1158): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1158): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1158): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  903):    returned true
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiStateMachine(  903): Enter handleNetworkDisconnect
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1158): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1158): nl80211: Event message available
D/wpa_supplicant( 1158): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiDataStallTracker(  903): stopDataStallAlarm: current tag=20313 mDataStallAlarmIntent=PendingIntent{4242d100: PendingIntentRecord{42464388 android broadcastIntent}}
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  903): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  903): Provision feature enable=false
D/ConnectivityService(  903): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1158): Power_Mode_Type mode = 0
I/wpa_supplicant( 1158): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1158): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  903):    returned true
D/UsbnetStateTracker(  903): isAvailable+-
D/UsbnetStateTracker(  903): reconnect
,D/UsbnetStateTracker(  903): isAvailable+-
,D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WISPrService( 4105): >>>>>WISPrService start isConnected = false<<<<<
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiP2pService(  903): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1819/10178)
,D/WifiP2pService(  903): P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/MDST    (  903): default: reconnect()
D/MDST    (  903): default: setTeardownRequested(false)
D/MDST    (  903): default: setEnableApn apnType =default , enable=true
D/WifiStateMachine(  903): Exit handleNetworkDisconnect
,D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
D/WISPrService( 4105): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  903): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/ConnectivityService(  903): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  903): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  903): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/ConnectivityService(  903): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  903): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  903): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiService(  903): New client listening to asynchronous messages
W/ConnectivityService(  903): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
,D/ConnectivityService(  903): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4105): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4105): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  903): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ConnectivityService(  903): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  903): handleConnectivityChange: resetting
D/ConnectivityService(  903): resetConnections(wlan0, 3)
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1819/10178)
D/PMS     (  903): acquireWL(43671a70): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1361 10028 null
D/libc    (  363): [NET] entry_id:5   entry:0xb7343338  removed 
D/libc    (  363): [NET] entry_id:6   entry:0xb7343818  removed 
D/libc    (  363): [NET] entry_id:4   entry:0xb7342fd8  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb7343248  removed 
D/libc    (  363): [NET] entry_id:7   entry:0xb73436f0  removed 
D/libc    (  363): [NET] entry_id:3   entry:0xb7343128  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb7343410  removed 
D/libc    (  363): [NET] entry_id:8   entry:0xb7343590  removed 
,D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
D/ConnectivityService(  903): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  903): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  903): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  903): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  903): acquireWL(42c29d58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10028 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/PMS     (  903): acquireWL(423d8a18): PARTIAL_WAKE_LOCK  NetworkStats 0x1 903 1000 null
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
,D/ConnectivityService(  903): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/WirelessDisplayService(  903): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  903): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,D/WifiStateMachine(  903): startScan Pid: 903 Uid 1000
,D/WifiNative-wlan0(  903): doBoolean: SCAN
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1158): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  903):    returned false
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1361/10028)
D/PMS     (  903): releaseWL(42c29d58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  903): reportInetCondition for net -1, percentage: 0 by  (1361/10028)
D/BatSI   (  903): WIFI scan started for: 650a0300 uid:1000
,I/QuickSettingWifi( 1114): receive.wifiConnect:false wifiAPname:null elapse:1
D/PMS     (  903): releaseWL(43671a70): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1361/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1361/10028)
,D/ConnectivityService(  903): mActiveDefaultNetwork: -1
,D/ConnectivityService(  903): handleInetConditionChange: no active default network - ignore
,I/QuickSettingWifi( 1114): receive.wifiConnect:false wifiAPname:null elapse:1
D/PMS     (  903): releaseWL(423d8a18): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/chromium( 4328): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  903): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  903): [AlarmQueuing] connectivity wifi: false
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
,D/CaptivePortalTracker(  903): DelayedCaptiveCheckState
D/CaptivePortalTracker(  903): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  903): NoActiveNetworkState
D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,D/Tethering(  903): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/PMS     (  903): acquireWL(43ff0488): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 903 1000 null
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1863/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1819/10178)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1447/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.docs (4216/10100)
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,V/Tethering(  903): bSetPropertyMultiRAB:false
D/Tethering(  903): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/ConnectivityHelper( 1270): [onReceive] WIFI(1): DISCONNECTED
,I/NetworkMonitor( 3826): type=WIFI subType= reason=null isConnected=false
,I/Tethering(  903): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
,I/Tethering(  903): ipv4Default null
,I/Tethering(  903): No IPv4 upstream interface, giving up.
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.google.android.music (3826/10154)
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.htc.launcher (1270/10075)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.docs (4216/10100)
,D/Tethering(  903): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  903): getActiveNetworkInfo called by  (2021/10021)
,I/ActivityManager(  903): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4397 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/GpsLocationProvider(  903): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  903): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  903): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  903): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  903): releaseWL(43ff0488): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ACRA    ( 4397): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4397): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4397): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4397): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4397): Preparing secondary program dexes.
V/DexLibLoader( 4397): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4397): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4397): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4397): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4397): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4397): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4397): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4397): Dex already copied
D/OdexVerifier( 4397): Odex verification is skipped.
,V/DexLibLoader( 4397): Creating class loader
,V/DexLibLoader( 4397): Finished creating class loader
V/DexLibLoader( 4397): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
,V/DexLibLoader( 4397): Dex already copied
D/OdexVerifier( 4397): Odex verification is skipped.
,V/DexLibLoader( 4397): Creating class loader
,V/DexLibLoader( 4397): Finished creating class loader
V/DexLibLoader( 4397): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4397): Dex already copied
D/OdexVerifier( 4397): Odex verification is skipped.
,V/DexLibLoader( 4397): Creating class loader
,V/DexLibLoader( 4397): Finished creating class loader
V/DexLibLoader( 4397): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
,V/DexLibLoader( 4397): Dex already copied
D/OdexVerifier( 4397): Odex verification is skipped.
,V/DexLibLoader( 4397): Creating class loader
,V/DexLibLoader( 4397): Finished creating class loader
,V/DexLibLoader( 4397): Verifying classes from secondary dexes.
,D/DexLibLoader( 4397): DexLibLoader.ensureDexLoaded took 24 ms
,W/dalvikvm( 4397): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4397): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4397): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4397): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4397): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4397): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4397): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4397): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4397): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1158): nl80211: Event message available
D/wpa_supplicant( 1158): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1158): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1158): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1158): nl80211: Survey data missing
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1158): Sorted scan results
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-53
I/wpa_supplicant( 1158): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-53
I/wpa_supplicant( 1158): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-77
I/wpa_supplicant( 1158): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1158): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
D/wpa_supplicant( 1158): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1158): Add randomness: count=8 entropy=0
D/wpa_supplicant( 1158): Add randomness: count=9 entropy=1
D/wpa_supplicant( 1158): Add randomness: count=10 entropy=2
D/wpa_supplicant( 1158): Add randomness: count=11 entropy=3
D/wpa_supplicant( 1158): Add randomness: count=12 entropy=4
D/wpa_supplicant( 1158): Add randomness: count=13 entropy=5
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1158): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1158): wpa_supplicant_pick_network+
I/wpa_supplicant( 1158): Selecting BSS from priority group 1
I/wpa_supplicant( 1158): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1158): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1158): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1158): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1158):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1158):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-53
I/wpa_supplicant( 1158): Start print parameters
I/wpa_supplicant( 1158): wpa_s->wpa_state is 3
I/wpa_supplicant( 1158): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1158): isConcurrentMode() is 0
I/wpa_supplicant( 1158): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1158): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1158): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1158): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1158): wpa_s->reassociate is 1
I/wpa_supplicant( 1158): wpa_s->is_screen_on 1
I/wpa_supplicant( 1158): wpa_s->ifname wlan0
I/wpa_supplicant( 1158): End print parameters
I/wpa_supplicant( 1158): selected network = 1
D/wpa_supplicant( 1158): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb81d64e8  current_ssid=0x0
D/w,pa_supplicant( 1158): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1158): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1158): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1158): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1158): check if in concurrent case
,I/wpa_supplicant( 1158): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1158): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1158): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1158): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1158): RSN: PMKSA cache search - network_ctx=0xb81d64e8 try_opportunistic=0
D/wpa_supplicant( 1158): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1158): RSN: No PMKSA cache entry found,
I/wpa_supplicant( 1158): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1158): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1158): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1158): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1158): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1158): nl80211: Unsubscribe mgmt frames handle 0xb81d5718 (mode change)
D/wpa_supplicant( 1158): nl80211: Subscribe to mgmt frames with non-AP handle 0xb81d5718
D/wpa_supplicant( 1158): nl80211: Register frame type=0xd0 nl_handle=0xb81d5718
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1158): nl80211: Register frame type=0xd0 nl_handle=0xb81d5718
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 58,
D/wpa_supplicant( 1158): nl80211: Register frame type=0xd0 nl_handle=0xb81d5718
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1158): nl80211: Register frame type=0xd0 nl_handle=0xb81d5718
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1158): nl80211: Register frame type=0xd0 nl_handle=0xb81d5718
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1158): nl80211: Register frame type=0xd0 nl_handle=0xb81d5718
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1158): nl80211: Register frame type=0xd0 nl_handle=0xb81d5718
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1158): nl80211: Register frame type=0xd0 nl_handle=0xb81d5718
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1158): nl80211: Register frame type=0xd0 nl_handle=0xb81d5718
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1158): nl80211: Register frame type=0xd0 nl_handle=0xb81d5718
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1158): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1158):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1158):   * freq=2412
D/wpa_supplicant( 1158):   * Auth Type 0
D/wpa_supplicant( 1158):   * WPA Versions 0x2
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1158): nl80211: Connect request send successfully
D/wpa_supplicant( 1158): EAPOL: External notification - EAP success=0,
D/wpa_supplicant( 1158): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1158): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1158): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1158): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1158): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1158): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1158): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1158): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 18
,D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1158): reply (779) for get BSS: id=0
I/wpa_supplicant( 1158): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1158): freq=5220
I/wpa_supplicant( 1158): level=-47
I/wpa_supplicant( 1158): tsf=0000000107501201
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=NG7005g
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=1
I/wpa_supplicant( 1158): bssid=c0:ff:d4:d3:aa:48,
I/wpa_supplicant( 1158): freq=2412
I/wpa_supplicant( 1158): level=-53
I/wpa_supplicant( 1158): tsf=0000000107501221
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=NG700
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=2
I/wpa_supplicant( 1158): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1158): freq=2452
I/wpa_supplicant( 1158): level=-77
I/wpa_supplicant( 1158): tsf=0000000107501226
I/wpa_supplicant( 1158): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1158): ssid=Gonzos
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=3
I/wpa_supplicant( 1158): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1158): freq=2437
I/wpa_supplicant( 1158): level=-84
I/wpa_supplicant( 1158): tsf=0000000107501231
I/wpa_supplicant( 1158): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1158): ssid=UPC Wi-Free
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=4
I/wpa_supplicant( 1158): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1158): freq=2437
I/wpa_supplicant( 1158): level=-84
I/wpa_supplicant( 1158): tsf=0000000107501234
I/wpa_supplicant( 1158): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=UPC5999698
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=5
I/wpa_supplicant( 1158): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1158): freq=2412
I/wpa_supplicant( 1158): level=-53
I/wpa_supplicant( 1158): tsf=0000000107501215
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1158): ssid=01ABC
I/wpa_supplicant( 1158): ####
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiStateMachine(  903): == begin of scan result ==
,D/WifiStateMachine(  903): == (6) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 107501201, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -53, frequency: 2412, timestamp: 107501221, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2452, timestamp: 107501226, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -84, frequency: 2437, timestamp: 107501231, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -84, frequency: 2437, timestamp: 107501234, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 5: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -53, frequency: 2412, timestamp: 107501215, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): add 6 to mScanResults
D/BatSI   (  903): WIFI scan stopped for: 640a0300 uid:1000
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,E/FbInjectorInitializer( 4397): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.,
,D/wpa_supplicant( 1158): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
,D/wpa_supplicant( 1158): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1158): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1158): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1158): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1158): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1158): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1158): nl80211: Event message available
D/wpa_supplicant( 1158): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1158): nl80211: Connect event
D/Tethering(  903): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1158): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1158): nl80211: Associated with c0:ff:d4:d3:aa:48
D/Tethering(  903): interfaceStatusChanged wlan0, false
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1158): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1158): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1158): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1158): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1158): Add randomness: count=14 entropy=6
I/wpa_supplicant( 1158): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1158): TDLS: Remove peers on association
D/wpa_supplicant( 1158): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1158): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1158): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1158): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1158): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1158): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1158): EAPOL: External notification - EAP success=0
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1158): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1158): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1158): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1158): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1158): EAPOL: enable timer tick
D/wpa_supplicant( 1158): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1158): htc_wext_set_keepalive +
I/wpa_supplicant( 1158): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1158): getPrivFuncNum +	
I/wpa_supplicant( 1158): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1158): htc_wext_set_keepalive fnum = 0x8bf6
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
I/wpa_supplicant( 1158): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1158): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1158): Get randomness: len=32 entropy=7
D/WifiMonitor(  903): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  903): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/HTCRequest(  903): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  903): WifiMonitor:getFreqFromEventString() 2412
D/Tethering(  903): interfaceLinkStateChanged wlan0, true
D/Tethering(  903): interfaceStatusChanged wlan0, true
D/HTCRequest(  903): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  903): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  903): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  903): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  903): Enter handleAssociatedWithEvent
D/WifiStateMachine(  903): Associated
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700,
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiStateMachine(  903): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  903): Exit handleAssociatedWithEvent
D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  903): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  903): updateConnectedAP...
D/WifiApDatabaseHandler(  903): updateConnectedAP...
,D/WifiStateMachine(  903): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  903): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  903): This record is existed, only update it...
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  903): updateConnectedAP...
I/wpa_supplicant( 1158): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1158): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb81d59f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 1158):    addr=c0:ff:d4:d3:aa:48
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 11
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1158): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1158): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/wpa_supplicant( 1158): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6fa6b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 1158):    broadcast key
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1158): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1158): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1158): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1158): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1158): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
,I/wpa_supplicant( 1158): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  903): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1158): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1158): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1158): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1158): set send_ind_to_ndc = 0
I/wpa_supplicant( 1158): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1158): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1158): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1158): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1158): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1158): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1158): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1158): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1158): EAPOL: Supplicant port status: Authorized
,D/wpa_supplicant( 1158): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1158): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1158): EAPOL authentication completed successfully
I/wpa_supplicant( 1158): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1158): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1158): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1158): nl80211: if_removed already cleared - ignore event
,D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  903): interfaceLinkStateChanged wlan0, true
D/Tethering(  903): interfaceStatusChanged wlan0, true
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  903): [isWifi] getHotspotEnabled: false
,D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  903): updateConnectedAP...,
,D/WifiStateMachine(  903): fetchFrequency(), freq = 2412,
D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  903): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiApDatabaseHandler(  903): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiStateMachine(  903): This record is existed, only update it...
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  903): updateConnectedAP...
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  903): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  903): Provision feature enable=false
D/ConnectivityService(  903): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,W/fb4a(:<default>):StaticBindingVerifier( 4397): Verify
,D/WifiApDatabaseHandler(  903): updateConnectedAP...
,D/WISPrService( 4105): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4105): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/DhcpStateMachine(  903): [StoppedState] Start DHCP
D/WifiStateMachine(  903): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1158): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 1
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1158): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
,D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 1
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1158): Power_Mode_Type mode = 1
I/wpa_supplicant( 1158): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  903):    returned null
E/WifiStateMachine(  903): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  903): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  903):    returned null
D/WifiStateMachine(  903): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  903): acquireWL(43690ca0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 903 1000 null
D/WifiStateMachine(  903): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  903): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@424d4250 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@424d4250 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1114): receive.wifiConnect:false wifiAPname:null elapse:0
,D/WifiService(  903): New client listening to asynchronous messages
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4397/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4397): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4397): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4397): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  903): killProcessQuiet, pid=3169
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 ,
I/ActivityManager(  903): Killing 3169:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3169
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  903): acquireWL(436f5ee0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2240 10028 null
,D/PMS     (  903): acquireWL(43764990): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2240 10028 null
,D/PMS     (  903): releaseWL(436f5ee0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2240/10028)
,D/PMS     (  903): releaseWL(43764990): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/GCM     ( 1361): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1361/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1361/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1361/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2240/10028)
,D/AutoSetting( 1396): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  903): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4426 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1396/10053)
,D/AutoSetting( 1396): Util - no network available!
,D/AutoSetting( 1396): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1396): service - mHandler: cancel location update
,D/AutoSetting( 1396): service -           changes count: 0
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1396/10053)
,W/fb4a(:<default>):UserScope( 4397): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4397): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4397): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4426): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4426): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4426): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4426): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,D/Process (  903): killProcessQuiet, pid=3808
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4440 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
I/ActivityManager(  903): Killing 3808:com.htc.mediamanager/u0a32 (adj 15): empty #17
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4426/10078)
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4397): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4426/10078)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4426/10078)
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,E/dalvikvm( 4397): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4397): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4397): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4397): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4397): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4397): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4397): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4397): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4397): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4397): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4397): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4397): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4397): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4397): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4397): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4397): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4397): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4397): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/ActivityManager(  903): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4457 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  903): killProcessQuiet, pid=4158
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Killing 4158:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4158
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  903): Client connection lost with reason: 4
,I/dalvikvm-heap( 4397): Grow heap (frag case) to 9.917MB for 39954-byte allocation
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 3808
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4457): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,I/dalvikvm-heap( 4397): Grow heap (frag case) to 9.994MB for 79892-byte allocation
,W/ContextImpl( 4457): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4457): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4457): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4457): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4397): Grow heap (frag case) to 10.066MB for 84664-byte allocation
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (4457/10151)
,V/WebViewChromiumFactoryProvider( 4457): Binding Chromium to main looper Looper (main, tid 1) {41b6a588}
,I/LibraryLoader( 4457): Expected native library version number "",actual native library version number ""
,I/chromium( 4457): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4457): Initializing chromium process, renderers=0
,D/PMS     (  903): acquireWL(43206648): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
,D/PMS     (  903): acquireWL(43273fe8): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
,E/AudioManagerAndroid( 4457): BLUETOOTH permission is missing!
D/PMS     (  903): releaseWL(43206648): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4457): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4457): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4457): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4457): Local Branch: 
I/Adreno-EGL( 4457): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4457): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4457):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4457): Starting up...
,I/dalvikvm-heap( 4397): Grow heap (frag case) to 10.278MB for 75760-byte allocation
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (4457/10151)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (4457/10151)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4397/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (4084/10160)
,W/BroadcastQueue(  903): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4382e3f0 u0 ReceiverList{43829228 4397 com.facebook.katana/10026/u0 remote:4381bd00}}
,W/BroadcastQueue(  903): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4382e3f0 u0 ReceiverList{43829228 4397 com.facebook.katana/10026/u0 remote:4381bd00}}
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (4084/10160)
,W/BroadcastQueue(  903): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{44128388 u0 ReceiverList{44128328 4397 com.facebook.katana/10026/u0 remote:43d09cb8}}
,D/Process (  903): killProcessQuiet, pid=3930
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  903): Killing 3930:com.google.android.gm/u0a107 (adj 15): empty #17
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1819/10178)
,D/GCM     ( 1361): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1819/10178)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4397/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4397/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4397/10026)
,D/PMS     (  903): acquireWL(4350e650): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1447 10028 null
,D/PMS     (  903): releaseWL(4350e650): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/GCoreFlp( 1447): Unknown pending intent to remove.
D/PMS     (  903): acquireWL(440b87d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1447 10028 null
D/PMS     (  903): releaseWL(440b87d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4397): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4397): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  903): Recipient 3930
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/wpa_supplicant( 1158): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1158): EAPOL: disable timer tick
,D/libc    (  903): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  903): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/libc    (  903): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/libc    (  903): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/libc    (  903): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1158): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1158): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1158): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  903):    returned true
,D/WifiStateMachine(  903): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [1][0][0]
D/WifiP2pService(  903): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  903): releaseWL(43690ca0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1158): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
D/WifiStateMachine(  903): gateway: /192.168.1.1
,D/WifiNative-wlan0(  903): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1158): WiFi gateway: 0x101a8c0
D/WIFI_ICON( 1114): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiNative-wlan0(  903):    returned true
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  903): VerifyingLinkState enter
D/WifiStateMachine(  903): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  903): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  903): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -53, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,I/IntentController( 1114): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  903): startDataStallAlarm: tag=20315 delay=15s
,D/WifiWatchdogStateMachine(  903): WAN detection
V/NetworkPolicy(  903): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WIFI_ICON( 1114): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1819/10178)
D/ConnectivityService(  903): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  903): Provision feature enable=false
D/ConnectivityService(  903): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  903): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  903): default: teardown()
D/MDST    (  903): default: setTeardownRequested(true)
D/MDST    (  903): default: setEnableApn apnType =default , enable=false
,D/WIFI_ICON( 1114): WifiActivity: 3
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/MDST    (  903): default: setTeardownRequested(true)
,D/ConnectivityService(  903): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  903): Unexpected mtu value: android.net.wifi.WifiStateTracker@4249a100
,D/libc    (  903): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  903): handleConnectivityChange: netType=1 doReset=false resetMask=0
,D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  903): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  903): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  903): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  903): handleConnectivityChange: resetting
D/Nat464Xlat(  903): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  903): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/WirelessDisplayService(  903): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  903):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  903): sendGeneralBroadcastDelayed, restrictEnable=false
D/PMS     (  903): acquireWL(44078478): PARTIAL_WAKE_LOCK  NetworkStats 0x1 903 1000 null
D/ConnectivityService(  903): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  903): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
I/QuickSettingWifi( 1114): receive.wifiConnect:true wifiAPname:NG700 elapse:1
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4426/10078)
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
,D/PMS     (  903): releaseWL(44078478): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
I/logwrapper(  363): /system/bin/ip terminated by exit(254)
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  903): mActiveDefaultNetwork: WIFI
,D/WISPrService( 4105): >>>>>WISPrService start isConnected = true<<<<<
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  903): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  903): syncGetConfiguredNetworks
D/PMS     (  903): acquireWL(441564b8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2240 10028 null
I/CheckinService( 2240): Preparing to send checkin request
,I/EventLogService( 2240): Accumulating logs since 1452600918966
D/PMS     (  903): acquireWL(441406a0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2240 10028 null
D/PMS     (  903): releaseWL(441564b8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2240/10028)
,I/GoogleHttpClient( 2240): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2240): Using GMS GoogleHttpClient
,D/ConnectivityService(  903): getNetworkInfo networkType=9 called by com.google.android.gms (2240/10028)
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  903): getNetworkInfo networkType=0 called by com.google.android.gms (2240/10028)
,W/GLSUser ( 1361): GoogleAccountDataService.getToken()
,W/GLSActivity( 1361): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1361): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1361): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/CheckinRequestBuilder( 2240): awaiting user notification for token
,D/DotMatrix( 1563): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1563): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1114): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{41cb1c60 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1114): com.google.android.gms 2 7 3 12
,I/ActivityManager(  903): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4532 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 4532): install
,I/MultiDex( 4532): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4532): loading existing secondary dex files
,I/MultiDex( 4532): load found 1 secondary dex files
,I/MultiDex( 4532): install done
,I/ProviderInstaller( 4532): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1361): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (4532/10028)
,W/dalvikvm( 4328): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4328): threadid=1: thread exiting with uncaught exception (group=0x41739e30)
,E/ActivityManager(  903): App crashed! Process: com.test.thalitest
E/AndroidRuntime( 4328): FATAL EXCEPTION: main
E/AndroidRuntime( 4328): Process: com.test.thalitest, PID: 4328
E/AndroidRuntime( 4328): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4328): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4328): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4328): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4328): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4328): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4328): 	at io.jxcore.node.JXcoreExtension$4.Receiver(JXcoreExtension.java:112)
E/AndroidRuntime( 4328): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4328): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4328): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4328): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4328): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4328): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4328): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4328): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4328): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4328): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4328): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4328): 	at dalvik.system.NativeStart.main(Native Method)
W/ActivityManager(  903):   Force finishing activity com.test.thalitest/.MainActivity
I/ActivityManager(  903): mThumbnailWidth=360, mThumbnailHeight=640
,D/PMS     (  903): acquireWL(436ff730): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 903 1000 null
,W/asset   (  903): Copying FileAsset 0x631f5960 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,I/Adreno-EGL( 4532): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4532): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4532): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4532): Local Branch: 
I/Adreno-EGL( 4532): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4532): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4532):                  aa63bbd948f41d15fc72f585e
,D/WIFI_ICON( 1114): WifiActivity: 1
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  903): releaseWL(426523d0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  903): NetTransition Wakelock for ConnectedState released by timeout
,V/Tethering(  903): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  903): [AlarmQueuing] connectivity wifi: true
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1863/1000)
,D/CaptivePortalTracker(  903): NoActiveNetworkState
,I/acms    ( 1863): Checking Certificates
,V/Tethering(  903): bSetPropertyMultiRAB:false
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/Tethering(  903): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/Tethering(  903): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  903): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  903): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  903): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  903): Found interface wlan0
D/Tethering(  903): TetherMasterSM: InitialState processMessage what=3
,D/CaptivePortalTracker(  903): DelayedCaptiveCheckState
,I/ConnectivityHelper( 1270): [onReceive] WIFI(1): CONNECTED
D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
I/NetworkMonitor( 3826): type=WIFI subType= reason=null isConnected=true
I/acms    ( 1863): Checking Developer Certificates
I/acms    ( 1863): Checking Application Certificates
I/acms    ( 1863): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1863): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1863): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1863): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1863): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1863): Updating next query delay: 75600000
I/mlserverapp( 1863): MirrorLink is never connected, don't setup ACMS programed checks
,I/mlserverapp( 1863): cancelACMSProgrammedChecks
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1447/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1819/10178)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.docs (4216/10100)
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.htc.launcher (1270/10075)
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.google.android.music (3826/10154)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.musicenhancer (3850/10051)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4426/10078)
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/Adreno-EGL( 4532): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4532): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4532): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4532): Local Branch: 
I/Adreno-EGL( 4532): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4532): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4532):                  aa63bbd948f41d15fc72f585e
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.docs (4216/10100)
,D/PMS     (  903): acquireWL(430f4b78): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 903 1000 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(435976d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0,
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4397/10026)
D/PMS     (  903): releaseWL(435976d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/GpsLocationProvider(  903): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  903): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  903): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  903): ignore wifi update if we are not in OPENING or CLOSING
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  903): releaseWL(430f4b78): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4397/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (2021/10021)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4397/10026)
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,I/Adreno-EGL( 4532): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4532): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4532): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4532): Local Branch: 
I/Adreno-EGL( 4532): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4532): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4532):                  aa63bbd948f41d15fc72f585e
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  903): acquireWL(4328bb70): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2240 10028 null
,D/PMS     (  903): releaseWL(4328bb70): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/GCM     ( 1361): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1361/10028)
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiStateMachine(  903): BroadcastRSSIForIMS, newrssi =-53 , oldRssi= -200
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1158): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1361/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1361/10028)
D/WIFI_ICON( 1114): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/PMS     (  903): acquireWL(42172560): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1361 10028 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2240/10028)
D/libc    ( 1361): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1361): [NET] getaddrinfo-,err=8
D/libc    ( 1361): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1361): [NET] getaddrinfo-, 1
D/libc    ( 1361): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =2e68 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
,D/AutoSetting( 1396): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/MobileConnectivityChangeReceiver( 4426): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4426): onReceive CONNECTIVITY_CHANGE networkType=1
,W/Settings( 4532): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/AutoSetting( 1396): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4397/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1396/10053)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (4457/10151)
D/AutoSetting( 1396): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1396): service - requestNLP() NetworkLocationProvider not enabled
,D/AutoSetting( 1396): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 1396): service - handleMessage() setting current location null
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/AutoSetting( 1396): Util - check NLP state, Allowned:false, Enabled:false
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/AutoSetting( 1396): service - onStartCommand() check timezone in 30000
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=50 [2][1][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4397/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1396/10053)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (4084/10160)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (4084/10160)
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1819/10178)
,W/fb4a(:<default>):UserScope( 4397): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4397): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 88
D/libc    (  363): [NET]res_nsend:resplen=79
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/libc    ( 1361): [NET] getaddrinfo_proxy-, success
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4397/10026)
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [1][0][0]
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4397/10026)
,W/ActivityManager(  903): Activity pause timeout for ActivityRecord{41fb8510 u0 com.test.thalitest/.MainActivity t2 f}
,I/FeedHostManager( 1270): [onResume]
,I/FeedProviderManager( 1270): onResume
I/SocialFeedProvider( 1270): +onResume
I/SocialFeedProvider( 1270): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1270): -onResume
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.launcher (1270/10075)
,D/libc    ( 1361): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1361): [NET] getaddrinfo-,err=8
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1361/10028)
D/PMS     (  903): acquireWL(42658d10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10028 null
D/PMS     (  903): releaseWL(42658d10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  903): releaseWL(436ff730): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/Process (  903): killProcessQuiet, pid=4186
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
I/ActivityManager(  903): Killing 4186:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,E/fb4a(:<default>):LocalFbBroadcastManager( 4397): Called registerBroadcastReceiver twice.
,D/GCM     ( 1361): Connected
D/PMS     (  903): acquireWL(437af460): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1361 10028 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1361/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1361/10028)
D/PMS     (  903): releaseWL(42172560): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1361/10028)
D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1361/10028)
D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  903): handleInetConditionChange: starting a change hold
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1361/10028)
D/PMS     (  903): releaseWL(437af460): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  903): acquireWL(441282b8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1361 10028 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1361/10028)
,D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1361/10028)
D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/GCM     ( 1361): Message class mpf
D/ConnectivityService(  903): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4397/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1361/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4397/10026)
D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1361/10028)
D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  903): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1361/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4397/10026)
D/PMS     (  903): releaseWL(441282b8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
I/ActivityManager(  903): Recipient 4186
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  903): acquireWL(42675c80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10028 null
D/PMS     (  903): releaseWL(42675c80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/libc    ( 4397): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 4
,D/libc    ( 4397): [NET] getaddrinfo-,err=8
D/libc    ( 4397): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 1024
D/libc    ( 4397): [NET] getaddrinfo-, 1
D/libc    ( 4397): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =bbbd +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 40
D/libc    (  363): [NET]res_nsend:resplen=74
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4397): [NET] getaddrinfo_proxy-, success
I/global  ( 4397): call createSocket() return a new socket.
D/libc    ( 4397): [NET] getaddrinfo+,hn 10(0x33312e31332e38),sn(),family 0,flags 4
,D/libc    ( 4397): [NET] getaddrinfo-, SUCCESS
,I/CheckinTask( 2240): Sending checkin request (8968 bytes)
D/libc    ( 2240): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2240): [NET] getaddrinfo-,err=8
D/libc    ( 2240): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2240): [NET] getaddrinfo-, 1
,D/libc    ( 2240): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =b820 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 183
D/libc    (  363): [NET]res_nsend:resplen=84
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2240): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2240): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2240): [NET] getaddrinfo-,err=8
,D/libc    ( 4397): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 4
,D/libc    ( 4397): [NET] getaddrinfo-,err=8
,I/dalvikvm-heap( 4397): Grow heap (frag case) to 10.966MB for 32784-byte allocation
,I/dalvikvm-heap( 4397): Grow heap (frag case) to 10.996MB for 32784-byte allocation
,D/PMS     (  903): releaseWL(43273fe8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/PMS     (  903): Going to sleep due to screen timeout...
,D/WirelessDisplayService(  903): Screen File Receiver; callOnGoing: false, Screen On: false
I/SensorManager(  903): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421d42e8
,D/WirelessDisplayService(  903): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  903): disable: get sensor name = CM36282 Light sensor
W/SensorService(  903): pid=903, uid=1000
,W/SensorService(  903): Active sensors: size = 2
W/SensorService(  903): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  903): CM36282 Proximity sensor (handle=0x00000001, connections=1)
,W/SensorService(  903): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421d42e8, eanble = 0, strlen(mName) = 59
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 2
W/PMS     (  903): mWirelessDisplayManager is null
W/BatSI   (  903): Couldn't get kernel wake lock stats
W/SensorService(  903): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4204c060
W/SensorService(  903): Listener[1] = com.htc.smartdim.sensor_eye@420d2e98
,W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
V/LightsService(  903): setLight #2: color=#0
D/qdlights(  903): set_light_buttons_func: on=0 brightness=0
V/LightsService(  903): setLight #0: color=#0
,D/PMS     (  903): acquireWL(4367c3f8): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 4397 10026 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4397/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4397/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4397/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4397/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4397/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4397/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4397/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4397/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4397/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4397/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4397/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4397/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4397/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4397/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4397/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4397/10026)
,D/ConnectivityService(  903): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  903): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4397/10026)
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4397/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4397/10026)
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=11 [35][4][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4397/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4397/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4397/10026)
,D/WIFI_ICON( 1114): WifiActivity: 3
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  903): acquireWL(440f41a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10028 null
,D/PMS     (  903): releaseWL(440f41a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  903): getNetworkInfo networkType=9 called by com.google.android.gms (2240/10028)
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  903): getNetworkInfo networkType=0 called by com.google.android.gms (2240/10028)
,W/GLSUser ( 1361): GoogleAccountDataService.getToken()
,W/GLSActivity( 1361): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1361): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1361): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/CheckinRequestBuilder( 2240): awaiting user notification for token
,D/DotMatrix( 1563): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1563): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1114): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{41e201d8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1114): com.google.android.gms 4 7 2 12
,D/SurfaceControl(  903): Excessive delay in blankDisplay() while turning screen off: 374ms
D/PMS     (  903): nativeSetInteractive:false
D/PMS     (  903): nativeSetInteractive:false done
D/PMS     (  903): nativeSetAutoSuspend:true
D/PMS     (  903): nativeSetAutoSuspend:true done
D/HABCtrl (  903): TPE algorithm. remove timeout.
D/PMS     (  903): OOBE c monitor 11
,V/KeyguardServiceDelegate(  903): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@435e2620)
D/PMN     (  903): wakingUp
D/PMS     (  903): acquireWL(436496e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
,V/KeyguardServiceDelegate(  903): **** SHOWN CALLED ****
D/NfcService( 1255): ScreenObserver: OFF
,D/NfcService( 1255): applyRouting - 0
,D/NfcService( 1255): applyRouting -2
,I/IntentController( 1114): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
I/WindowManager(  903): No lock screen! windowToken=null
D/PMS     (  903): releaseWL(436496e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/InputMethodManagerService(  903): screenObserver, isScreenOn=false
I/InputManager(  903): Cancel all due to getting PMS screen off broadcast
D/PMS     (  903): acquireWL(4412d5a0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1255 1027 null
I/InputMethodManagerService(  903): Disable input method client, pid=4328
D/PMS     (  903): releaseWL(4412d5a0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  903): onScreenOn
,D/AlarmManager(  903): ACTION_SCREEN_ON
I/AlarmManager(  903): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  903): [AlarmQueuing] done recovering
I/AlarmManager(  903): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  903): [AlarmQueuing] done EPS screen off alarm recovering
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
,D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NfcService( 1255): applyRouting - 0
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/MtpService( 2021): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/MtpService( 2021): [MTP][onReceive]-
D/AutoSetting( 1396): receiver - intent: android.intent.action.USER_PRESENT
D/UsbnetService(  903): onReceive BATTERY_CHANGED
,D/NfcService( 1255): applyRouting -2
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,D/WirelessDisplayService(  903): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/PMS     (  903): acquireWL(426931a0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1255 1027 null
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PMS     (  903): releaseWL(426931a0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
D/WirelessDisplayService(  903): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  903): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/AutoSetting( 1396): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,I/CheckinTask( 2240): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2240): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2240/10028)
D/WirelessDisplayService(  903): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  903): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  903): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiDataStallTracker(  903): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  903): startDataStallAlarm: tag=20316 delay=15s
,I/ClockThread( 1114): stop update clock
V/NotificationService(  903): batLight: Full, plugged
V/LightsService(  903): setLight #8: color=#c8c800
D/qdlights(  903): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  903): setLight #8: color=#c800
D/qdlights(  903): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
D/WifiNative-wlan0(  903): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
I/wpa_supplicant( 1158): SET_SCREEN_ON:On
I/wpa_supplicant( 1158): htc_wext_set_keepalive +
I/wpa_supplicant( 1158): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1158): getPrivFuncNum +	
I/wpa_supplicant( 1158): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1158): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1158): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1158): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1158): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  903):    returned true
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/TetherSettings( 4105): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4105): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4105): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4105): Cust_ConnectToPC   : spcsc>false
D/        ( 4105): Cust_ConnectToPC   : IPT>true
D/        ( 4105): Cust_ConnectToPC   : Singel_USB>false
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
,W/Settings( 4105): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
V/NotificationService(  903): batLight: Full, plugged
V/LightsService(  903): setLight #8: color=#c8c800
D/qdlights(  903): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  903): setLight #8: color=#c800
D/qdlights(  903): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
E/SmartNS_Utility( 4105): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4105): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4105): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,V/SRS_Proc(  370): ParamSet string: screen_state=on
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1158): WiFioffload: SignalStrength: =97
,D/WirelessDisplayService(  903): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
I/PSReceiver( 4105): onReceive:android.intent.action.USER_PRESENT
,D/WifiNative-wlan0(  903):    returned true
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
D/WIFI_ICON( 1114): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2240/10028)
W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
W/ContextImpl( 4105): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,D/NetworkPolicy(  903): updateScreenOn: false
I/SmartNS_PSService( 4105): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4105): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 4105):  defaultType:0
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/PMS     (  903): releaseWL(441406a0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 2240): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41e4e950 that was originally bound here
E/ActivityThread( 2240): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41e4e950 that was originally bound here
E/ActivityThread( 2240): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2240): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2240): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2240): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2240): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2240): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2240): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2240): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2240): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2240): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2240): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2240): 	at bks.a(SourceFile:298)
E/ActivityThread( 2240): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2240): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2240): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2240): 	at java.lang.Thread.run(Thread.java:864)
,I/ActivityManager(  903): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4582 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  903): acquireWL(43743758): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1447 10028 null
,D/PMS     (  903): releaseWL(43743758): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1795): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1795): onScreenOn: 1452600973911
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1795): onScreenOn: 1452600973911
,I/SensorManager(  903): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4204c060
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  903): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 2
W/SensorService(  903): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  903): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  903): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4204c060, eanble = 0, strlen(mName) = 91
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  903): Listener[0] = com.htc.smartdim.sensor_eye@420d2e98
,W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  903): goingToSleep
D/PMS     (  903): acquireWL(43c66038): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 903 1000 null
,I/FeedHostManager( 1270): [onPause]
,I/FeedProviderManager( 1270): onPause
,I/FeedHostManager( 1270): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@42294d38
I/SocialFeedProvider( 1270): +onPause
,I/SocialFeedProvider( 1270): -onPause
,D/AlarmManager(  903): ACTION_SCREEN_OFF
,W/ContextImpl( 4582): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
I/AlarmManager(  903): [AlarmQueuing] screen off now: 
I/AlarmManager(  903): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  903): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  903): stopDataStallAlarm: current tag=20316 mDataStallAlarmIntent=PendingIntent{42df9e18: PendingIntentRecord{42464388 android broadcastIntent}}
I/AlarmManager(  903): [AlarmQueuing] wifi connection: true
D/WifiNative-wlan0(  903): doBoolean: SET_SCREEN_ON 0
D/WifiNative-wlan0(  903): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1158): SET_SCREEN_ON:Off
I/wpa_supplicant( 1158): htc_wext_set_keepalive +
I/wpa_supplicant( 1158): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1158): getPrivFuncNum +	
I/wpa_supplicant( 1158): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1158): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1158): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1158): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1158): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  903):    returned true
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  903): acquireWL(43bdcc38): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 903 1000 null
D/PMS     (  903): releaseWL(43c66038): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,V/SRS_Proc(  370): ParamSet string: screen_state=off
,D/SmartSyncUtils( 4582): isEpsOn(), nState = 0
D/NetworkPolicy(  903): updateScreenOn: false
D/PMS     (  903): acquireWL(4387aab0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4582 1000 null
,D/wpa_supplicant( 1158): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  903): releaseWL(43bdcc38): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
,D/SmartSyncUtils( 4582): getMobilePolicyEnabled, result = true
D/PMS     (  903): releaseWL(4387aab0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/Process (  903): killProcessQuiet, pid=4216
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/GCM     ( 1361): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  903): Killing 4216:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,D/ContactMessageStore( 1244): start background delete task...
,I/GCM     ( 1361): GCM config loaded
D/ContactMessageStore( 1244): size: 0 , 0
,D/ContactMessageStore( 1244): Background delete complete
,D/AutoSetting( 1396): service - mHandler: cancel location update
,D/AutoSetting( 1396): service -           changes count: 0
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] getTotalRam: 1873 Mb
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1795): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1795): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1795): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1795): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1795): onScreenOff
D/PMS     (  903): acquireWL(437cd0c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1447 10028 null
D/PMS     (  903): releaseWL(437cd0c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
W/ContextImpl( 4582): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4582): isEpsOn(), nState = 0
D/SmartSyncUtils( 4582): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4582): getMobilePolicyEnabled, result = true
I/SensorManager(  903): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@420d2e98
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  903): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 1
W/SensorService(  903): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  903): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@420d2e98, eanble = 0, strlen(mName) = 36
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  903): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 0
W/SensorService(  903): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@420d2e98, eanble = 0, strlen(mName) = 36
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  903): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@420d2e98
D/WifiService(  903): New client listening to asynchronous messages
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,E/ActivityThread(  903): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@424e20c8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  903): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@424e20c8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  903): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  903): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  903): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  903): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  903): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  903): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  903): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  903): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  903): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  903): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  903): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  903): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  903): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  903): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  903): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  903): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  903): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  903): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  903): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  903): 	at dalvik.system.NativeStart.main(Native Method)
I/ActivityManager(  903): Recipient 4216
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/libc    (  903): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-,err=8
D/libc    (  903): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  903): [NET] getaddrinfo-, 1
,D/libc    (  903): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =4fee +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19,
D/libc    (  363): [NET]res_nsend:resplen=172
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
,D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  903): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  903): Find DNS Address www.htc.com/104.81.130.175,
,I/global  ( 4397): I/O error closing connection
I/global  ( 4397): java.net.SocketException: Socket is closed
I/global  ( 4397): 	at java.net.Socket.checkOpenAndCreate(Socket.java:672)
I/global  ( 4397): 	at java.net.Socket.getSoLinger(Socket.java:435)
I/global  ( 4397): 	at com.android.org.conscrypt.OpenSSLSocketImplWrapper.getSoLinger(OpenSSLSocketImplWrapper.java:156)
I/global  ( 4397): 	at org.apache.http.impl.conn.tsccm.AbstractConnPool.closeConnection(AbstractConnPool.java:328)
I/global  ( 4397): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteEntry(ConnPoolByRoute.java:530)
I/global  ( 4397): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteClosedConnections(ConnPoolByRoute.java:653)
I/global  ( 4397): 	at org.apache.http.impl.conn.tsccm.ThreadSafeClientConnManager.closeIdleConnections(ThreadSafeClientConnManager.java:295)
I/global  ( 4397): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager.b(FbClientConnManager.java:316)
I/global  ( 4397): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager$CloseIdleConnectionsRunnable.run(FbClientConnManager.java:327)
I/global  ( 4397): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
I/global  ( 4397): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
I/global  ( 4397): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
I/global  ( 4397): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
I/global  ( 4397): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
I/global  ( 4397): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
I/global  ( 4397): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
I/global  ( 4397): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
I/global  ( 4397): 	at java.lang.Thread.run(Thread.java:864)
,W/IdleConnectionHandler( 4397): Removing a connection that never existed!
,I/GAV2    ( 4457): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  903): acquireWL(44177ea8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1447 10028 null
,D/PMS     (  903): acquireWL(44170518): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1447 10028 null
,D/PMS     (  903): releaseWL(44177ea8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  903): releaseWL(44170518): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/WifiStateMachine(  903): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  903): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
,D/PMS     (  903): releaseWL(4367c3f8): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 null
,D/Process (  903): killProcessQuiet, pid=4240
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4240:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4240
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1505): service - handleMessage() stop self
,D/AutoSetting( 1505): service - onDestroy() END
,D/AutoSetting( 1505): service - handleMessage() quit looper
,D/Process (  903): killProcessQuiet, pid=4203
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4203:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4203
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4397/10026)
,I/dalvikvm-heap( 4397): Grow heap (frag case) to 11.031MB for 38744-byte allocation
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4397/10026)
,I/dalvikvm-heap( 4397): Grow heap (frag case) to 11.055MB for 40676-byte allocation
,I/dalvikvm-heap( 4397): Grow heap (frag case) to 11.075MB for 52192-byte allocation
D/libc    ( 4397): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
D/libc    ( 4397): [NET] getaddrinfo-,err=8
D/libc    ( 4397): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    ( 4397): [NET] getaddrinfo-, 1
,D/libc    ( 4397): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =e8af +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE,
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59,
D/libc    (  363): [NET]res_nsend:resplen=93
D/libc    (  363): [NET]res_queryN: exit 3, ancount=3,
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4397): [NET] getaddrinfo_proxy-, success
I/global  ( 4397): call createSocket() return a new socket.
D/libc    ( 4397): [NET] getaddrinfo+,hn 11(0x33312e31332e38),sn(),family 0,flags 4,
,D/libc    ( 4397): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 4397): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
,D/libc    ( 4397): [NET] getaddrinfo-,err=8
,D/PMS     (  903): acquireWL(43cc0e48): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 4397 10026 null
,I/global  ( 4397): I/O error closing connection
I/global  ( 4397): java.net.SocketException: Socket is closed
I/global  ( 4397): 	at java.net.Socket.checkOpenAndCreate(Socket.java:672)
I/global  ( 4397): 	at java.net.Socket.getSoLinger(Socket.java:435)
I/global  ( 4397): 	at com.android.org.conscrypt.OpenSSLSocketImplWrapper.getSoLinger(OpenSSLSocketImplWrapper.java:156)
I/global  ( 4397): 	at org.apache.http.impl.conn.tsccm.AbstractConnPool.closeConnection(AbstractConnPool.java:328)
I/global  ( 4397): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteEntry(ConnPoolByRoute.java:530)
I/global  ( 4397): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteClosedConnections(ConnPoolByRoute.java:653)
I/global  ( 4397): 	at org.apache.http.impl.conn.tsccm.ThreadSafeClientConnManager.closeIdleConnections(ThreadSafeClientConnManager.java:295)
I/global  ( 4397): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager.b(FbClientConnManager.java:316)
I/global  ( 4397): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager$CloseIdleConnectionsRunnable.run(FbClientConnManager.java:327)
I/global  ( 4397): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
I/global  ( 4397): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
I/global  ( 4397): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
I/global  ( 4397): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
I/global  ( 4397): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
I/global  ( 4397): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
I/global  ( 4397): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
I/global  ( 4397): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
I/global  ( 4397): 	at java.lang.Thread.run(Thread.java:864)
,W/IdleConnectionHandler( 4397): Removing a connection that never existed!
D/PMS     (  903): releaseWL(43cc0e48): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 null
,D/CaptivePortalTracker(  903): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  903): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  903): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,W/ActivityManager(  903): Activity destroy timeout for ActivityRecord{41fb8510 u0 com.test.thalitest/.MainActivity t2 f}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  903): acquireWL(43bdf968): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryService(  903): n_update end
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): releaseWL(43bdf968): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1396): service - mHandler: update timezone
,D/AutoSetting( 1505): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  903): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1505): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1505): service - onCreate()
W/ActivityManager(  903): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1505): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1505): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/DotMatrix( 1563): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1563): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  903): batLight: Full, plugged
V/LightsService(  903): setLight #8: color=#c8c800
D/qdlights(  903): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  903): setLight #8: color=#c800
D/qdlights(  903): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1505): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1505): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1505): service - mHandler: update timezone
,D/AutoSetting( 1505): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1505): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1505): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1505): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1563): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1563): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1114): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{41cbc2b0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1114): com.htc.htclocationservice 3 7 3 11
,D/GpsLocationProvider(  903): ALARM_XTRA_TIMEOUT
D/PMS     (  903): acquireWL(43705e88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
V/AlarmManager(  903): sending alarm PendingIntent{4254e058: PendingIntentRecord{4253a2a8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141922, Int=0
D/GpsLocationProvider(  903): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  903): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  903): acquireWL(43703f58): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 903 1000 null
V/AlarmManager(  903): sending alarm PendingIntent{438005c0: PendingIntentRecord{4246e590 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142275, Int=0
D/PMS     (  903): releaseWL(43705e88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1361/10028)
,D/PMS     (  903): acquireWL(436a4eb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10028 null
D/libc    (  903): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-,err=8
D/libc    (  903): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  903): [NET] getaddrinfo-, 1
D/libc    (  903): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =5b2c +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/PMS     (  903): releaseWL(436a4eb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/AutoSetting( 1396): service - handleMessage() stop self
,D/AutoSetting( 1396): service - onDestroy() END
,D/AutoSetting( 1396): service - handleMessage() quit looper
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  363): [NET]res_nsend:resplen=243
D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  903): [NET] getaddrinfo_proxy-, success
I/global  (  903): call createSocket() return a new socket.
D/libc    (  903): [NET] getaddrinfo+,hn 14(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  903): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  903): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  903): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  903):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  903): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  903): releaseWL(43703f58): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/Process (  903): killProcessQuiet, pid=3850
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3850:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3850
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,I/ActivityManager(  903): Waited long enough for: ServiceRecord{43718f90 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  903): acquireWL(424326f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41c03ad0: PendingIntentRecord{423b1410 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=158210, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(424326f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1505): service - handleMessage() stop self
,D/AutoSetting( 1505): service - onDestroy() END
,D/AutoSetting( 1505): service - handleMessage() quit looper
,D/Process (  903): killProcessQuiet, pid=4258
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4258:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4258
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  903): acquireWL(41dc43b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(41dc43b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1244): switchBindHtcMsgCursor: null
,D/PMS     (  903): acquireWL(42a53aa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): releaseWL(42a53aa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1114): closing low battery warning: level=100
,D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  903): acquireWL(426face8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,V/AlarmManager(  903): sending alarm PendingIntent{41c03ad0: PendingIntentRecord{423b1410 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=218209, Int=0
,D/PMS     (  903): releaseWL(426face8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(4241b808): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10026}
,V/AlarmManager(  903): sending alarm PendingIntent{43764500: PendingIntentRecord{43cd6138 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=228422, Int=0
,I/ActivityManager(  903): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4624 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  903): sending alarm PendingIntent{41c54808: PendingIntentRecord{42531ac0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452601083483, Int=10800000
,D/PMS     (  903): releaseWL(4241b808): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.aurora (4624/10047)
,I/ActivityManager(  903): Killing 4275:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  903): killProcessQuiet, pid=4275
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  903): Recipient 4275
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2240/10028)
,D/PMS     (  903): acquireWL(4267fe70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10026}
,V/AlarmManager(  903): sending alarm PendingIntent{42001a40: PendingIntentRecord{43cd6138 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=232159, Int=0
,D/PMS     (  903): releaseWL(4267fe70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  903): acquireWL(42544440): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): releaseWL(42544440): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  903): acquireWL(4257baf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
D/PMS     (  903): releaseWL(4257baf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  903): acquireWL(424e5c90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41c03ad0: PendingIntentRecord{423b1410 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=278210, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(424e5c90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  903): acquireWL(426e9f78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(426e9f78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  903): updateBatteryInfo
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  903): acquireWL(426c0c80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/PMS     (  903): releaseWL(426c0c80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/UsbnetService(  903): onReceive BATTERY_CHANGED
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1114): closing low battery warning: level=100
,D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(42407390): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
V/AlarmManager(  903): sending alarm PendingIntent{41c03ad0: PendingIntentRecord{423b1410 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=338210, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42407390): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  903): acquireWL(425dd708): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
,I/HtcPowerSaver(  903): >> updateStatus
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  903): releaseWL(425dd708): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1361): GoogleAccountDataService.getToken()
,W/GLSActivity( 1361): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1361): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1361): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1563): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1563): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1361): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1361): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1361): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1361): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1361): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1361): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1361): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1361): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews( 1114): com.google.android.gms (false,0)
,E/PlayEventLogger( 4046): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4046): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4046): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4046): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4046): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4046): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4046): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4046): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{41ed62b8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1114): com.google.android.gms 6 10 3 12
,D/libc    ( 4046): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4046): [NET] getaddrinfo-,err=8
D/libc    ( 4046): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4046): [NET] getaddrinfo-, 1
,D/libc    ( 4046): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =5ee3 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=87
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
,D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4046): [NET] getaddrinfo_proxy-, success
I/global  ( 4046): call createSocket() return a new socket.
D/libc    ( 4046): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4046): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4046): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4046): [NET] getaddrinfo-,err=8
,D/PMS     (  903): acquireWL(4268b8b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(4268b8b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  903): acquireWL(425e1090): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41c03ad0: PendingIntentRecord{423b1410 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=398209, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(425e1090): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process ( 4328): killProcess, pid=4328
,D/Process ( 4328): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/InputMethodManagerService(  903): Disable input method client, pid=4328
,I/ActivityManager(  903): Recipient 4328
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Process com.test.thalitest (pid 4328) has died.
,I/WindowState(  903): WIN DEATH: Window{42364508 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  903): Client connection lost with reason: 4
,D/PMS     (  903): acquireWL(426af980): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): releaseWL(426af980): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
,I/HtcPowerSaver(  903): >> updateStatus
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  903): acquireWL(42cbe3a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/PMS     (  903): releaseWL(42cbe3a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(432ff4f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41c03ad0: PendingIntentRecord{423b1410 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=458210, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(432ff4f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  903): acquireWL(43711688): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
,D/PMS     (  903): releaseWL(43711688): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  903): acquireWL(437fcd80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
V/AlarmManager(  903): sending alarm PendingIntent{41c03ad0: PendingIntentRecord{423b1410 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=518209, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(437fcd80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(436ef680): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10026}
,V/AlarmManager(  903): sending alarm PendingIntent{4412d860: PendingIntentRecord{4368d170 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=411832, Int=300000
,V/AlarmManager(  903): sending alarm PendingIntent{42f22f08: PendingIntentRecord{426f6a28 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1452601391889, Int=1800000
,D/PMS     (  903): acquireWL(440f6b78): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2240 10028 null
,D/PMS     (  903): releaseWL(436ef680): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  903): acquireWL(4412f380): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2240 10028 null
,I/EventLogService( 2240): Aggregate from 1452600971498 (log), 1452599591846 (data)
D/PMS     (  903): releaseWL(440f6b78): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,D/PMS     (  903): releaseWL(4412f380): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,D/PMS     (  903): acquireWL(437b3298): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  903): releaseWL(437b3298): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
,I/HtcPowerSaver(  903): >> updateStatus
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  903): acquireWL(4360b6d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(4360b6d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(439921b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41c03ad0: PendingIntentRecord{423b1410 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=578209, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(439921b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(436b67b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): releaseWL(436b67b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43242200): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
D/PMS     (  903): releaseWL(43242200): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
,D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1244): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1244): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1244): sku_id=99
D/ContactMessageStore( 1244): start background delete task...
,D/ContactMessageStore( 1244): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1244): size: 0 , 0
,D/ContactMessageStore( 1244): Background delete complete
,D/PMS     (  903): acquireWL(44136ff0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41c03ad0: PendingIntentRecord{423b1410 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=638210, Int=0
I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(44136ff0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43246850): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): releaseWL(43246850): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(441334a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(441334a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  903): updateBatteryInfo
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(437fef80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41c03ad0: PendingIntentRecord{423b1410 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=698209, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(437fef80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(437ca308): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1114): closing low battery warning: level=100
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PMS     (  903): releaseWL(437ca308): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(4382f888): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(4382f888): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(4415aae0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41c03ad0: PendingIntentRecord{423b1410 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=758209, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(4415aae0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(42dc1248): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42dc1248): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
,D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(42883578): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10026}
,V/AlarmManager(  903): sending alarm PendingIntent{4412d860: PendingIntentRecord{4368d170 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=711832, Int=300000
,V/AlarmManager(  903): sending alarm PendingIntent{41e269b8: PendingIntentRecord{424a48b8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=787395, Int=0
,D/ConnectivityService(  903): Sampling interval elapsed, updating statistics ..
,D/PMS     (  903): releaseWL(42883578): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  903): Done.
,D/ConnectivityService(  903): Setting timer for 720seconds
,D/PMS     (  903): acquireWL(4368a5d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(4368a5d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
,I/HtcPowerSaver(  903): >> updateStatus
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(436a0e88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41c03ad0: PendingIntentRecord{423b1410 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=818209, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(436a0e88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(4395a290): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): releaseWL(4395a290): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(4326fce8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): releaseWL(4326fce8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43846ca8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41c03ad0: PendingIntentRecord{423b1410 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=878209, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43846ca8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(437cd2e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PMS     (  903): releaseWL(437cd2e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43024890): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  903): releaseWL(43024890): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(437708a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
V/AlarmManager(  903): sending alarm PendingIntent{41c03ad0: PendingIntentRecord{423b1410 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=938209, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(437708a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(42636a68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
D/PMS     (  903): releaseWL(42636a68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(437c8010): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41c03ad0: PendingIntentRecord{423b1410 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=998209, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(437c8010): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(435f5de0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10028}
,V/AlarmManager(  903): sending alarm PendingIntent{440dc160: PendingIntentRecord{4257a8c8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1010988, Int=0
D/PMS     (  903): acquireWL(437d6b58): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1361 10028 null
,V/AlarmManager(  903): sending alarm PendingIntent{42711d40: PendingIntentRecord{42651ae0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452601803823, Int=900000
,V/AlarmManager(  903): sending alarm PendingIntent{424e0e30: PendingIntentRecord{438001a8 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1452601874079, Int=0
,D/PMS     (  903): releaseWL(437d6b58): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,D/PMS     (  903): acquireWL(436fed00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10028 null
W/ContextImpl( 4582): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  903): releaseWL(436fed00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PowerUsageService( 4582): call getInstance()
,D/SmartSyncUtils( 4582): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4582): MY_DEBUG = false
D/PMS     (  903): releaseWL(435f5de0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(437c66f8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4582 1000 null
D/SmartSyncScreenOnOffTimeReceiver( 4582): [updateNmRange] bManual = false
D/SmartSyncScreenOnOffTimeReceiver( 4582): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 2, nStart = 1, nEnd = 2, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 4582): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4582): SettingOnTime = 1452646800000, randomSettingOnTime = 1452644247000
D/SmartSyncScreenOnOffTimeReceiver( 4582): SettingOffTime = 1452643200000, randomSettingOffTime = 1452643472000
D/SmartSyncScreenOnOffTimeReceiver( 4582): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4582): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4582): bNightModeTurnOffOnce = false
W/BatSI   (  903): Couldn't get kernel wake lock stats
D/PMS     (  903): releaseWL(437c66f8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,D/PMS     (  903): acquireWL(43680d38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): releaseWL(43680d38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(4323c4b8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1361 10028 null,
,D/GCM     ( 1361): Message class mow
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1361/10028)
D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1361/10028)
D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  903): handleInetConditionChange: starting a change hold
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1361/10028)
,D/PMS     (  903): releaseWL(4323c4b8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  903): acquireWL(430425b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10028 null
,D/PMS     (  903): releaseWL(430425b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  903): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
D/ConnectivityService(  903): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=8 [161][13][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
,D/PMS     (  903): acquireWL(428793b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/PMS     (  903): releaseWL(428793b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  903): updateBatteryInfo
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
,I/HtcPowerSaver(  903): >> updateStatus
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(42528a08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41c03ad0: PendingIntentRecord{423b1410 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1058209, Int=0
I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42528a08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(424a6168): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
I/BatteryService(  903): n_update end
D/PMS     (  903): releaseWL(424a6168): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(41f2a920): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  903): releaseWL(41f2a920): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(423de7f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41c03ad0: PendingIntentRecord{423b1410 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1118209, Int=0
I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(423de7f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(41ffc5c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(41ffc5c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(42482798): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  903): sending alarm PendingIntent{41c03ad0: PendingIntentRecord{423b1410 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1178209, Int=0
,D/PMS     (  903): releaseWL(42482798): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(42386290): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42386290): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(4268c5d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): releaseWL(4268c5d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  903): acquireWL(437051f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41c03ad0: PendingIntentRecord{423b1410 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1238210, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(437051f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(4264ca20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PMS     (  903): releaseWL(4264ca20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(426a0038): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): releaseWL(426a0038): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1114): closing low battery warning: level=100
,D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(41e833b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
V/AlarmManager(  903): sending alarm PendingIntent{41c03ad0: PendingIntentRecord{423b1410 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1298210, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(41e833b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(426a0998): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(426a0998): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(424c3eb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(424c3eb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43c548c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41c03ad0: PendingIntentRecord{423b1410 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1358209, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43c548c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(426c7228): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): releaseWL(426c7228): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(42369d28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): releaseWL(42369d28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
,I/HtcPowerSaver(  903): >> updateStatus
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(425fd638): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41c03ad0: PendingIntentRecord{423b1410 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1418209, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(425fd638): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43aedd00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43aedd00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  903): updateBatteryInfo
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): runPSCheck
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(440f4150): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/PMS     (  903): releaseWL(440f4150): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  903): updateBatteryInfo
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43009648): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
V/AlarmManager(  903): sending alarm PendingIntent{41c03ad0: PendingIntentRecord{423b1410 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1478210, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43009648): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(44146998): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): releaseWL(44146998): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(424eb008): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41dc2758: PendingIntentRecord{42506000 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1502211, Int=0
,D/PMS     (  903): acquireWL(44141418): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 903 1000 null
,D/PMS     (  903): releaseWL(424eb008): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(42e015c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
,D/PMS     (  903): releaseWL(44141418): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  903): releaseWL(42e015c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  903): acquireWL(425cc520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  903): n_update end
D/PowerUI ( 1114): closing low battery warning: level=100
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): releaseWL(425cc520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(4297d6b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41c03ad0: PendingIntentRecord{423b1410 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1538209, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(4297d6b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(426b2ba0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(426b2ba0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  903): updateBatteryInfo
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
,D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(4395a3f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/PMS     (  903): releaseWL(4395a3f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43677030): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
V/AlarmManager(  903): sending alarm PendingIntent{41c03ad0: PendingIntentRecord{423b1410 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1598210, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43677030): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(438a6190): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(438a6190): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HtcPowerSaver(  903): updateBatteryInfo
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(437ca238): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): releaseWL(437ca238): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  903): updateBatteryInfo
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(436f5700): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41c03ad0: PendingIntentRecord{423b1410 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1658210, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(436f5700): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(44153230): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(44153230): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(435c42e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(435c42e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  903): updateBatteryInfo
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(4245d0a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41c03ad0: PendingIntentRecord{423b1410 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1718209, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(4245d0a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(4384ea00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
,D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
I/BatteryService(  903): n_update end
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/PMS     (  903): releaseWL(4384ea00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(4328c788): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(4328c788): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(43136dd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41c03ad0: PendingIntentRecord{423b1410 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1778209, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43136dd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43876688): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PowerUI ( 1114): closing low battery warning: level=98
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
V/NotificationService(  903): batLight: plugged
V/LightsService(  903): setLight #8: color=#c8c800
D/qdlights(  903): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  903): setLight #8: color=#c80000
D/qdlights(  903): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute
D/DotMatrix( 1563): [EventService] reorderNotification, total:1
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/HeadsetPhoneState( 1619): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/HtcPowerSaver(  903): updateBatteryInfo
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/PMS     (  903): releaseWL(43876688): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
,I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/ContextImpl( 4582): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:2 level:98 unsupport:false plugged:true
D/TetherSettings( 4105): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4105): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4105): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4105): Cust_ConnectToPC   : spcsc>false
D/        ( 4105): Cust_ConnectToPC   : IPT>true
,D/        ( 4105): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4105): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4105): Index of the first 1 = -1
W/ContextImpl( 4105): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/Settings( 4105): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4105): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4105): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4105): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 4105): [ACC]android_networking:tethering_guard_support=false
W/ContextImpl( 4105): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,D/PMS     (  903): acquireWL(437d2fb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(437d2fb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  903): updateBatteryInfo
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1114): closing low battery warning: level=98
,D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(440bee88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1114): closing low battery warning: level=98
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PMS     (  903): releaseWL(440bee88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  903): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:2 level:98 unsupport:false plugged:true
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  903): acquireWL(4389a438): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41c03ad0: PendingIntentRecord{423b1410 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1838209, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
I/ProcessStatsService(  903): Prepared write state in 38ms
,D/PMS     (  903): releaseWL(4389a438): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  903): Pruning old procstats: /data/system/procstats/state-2016-01-11-16-25-11.bin
,D/PMS     (  903): acquireWL(435aa7b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
V/AlarmManager(  903): sending alarm PendingIntent{41e269b8: PendingIntentRecord{424a48b8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1507430, Int=0
D/ConnectivityService(  903): Sampling interval elapsed, updating statistics ..
V/AlarmManager(  903): sending alarm PendingIntent{423e9b88: PendingIntentRecord{425623a0 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1821433, Int=1800000
D/PMS     (  903): acquireWL(426ad620): PARTIAL_WAKE_LOCK  NetworkStats 0x1 903 1000 null
,V/AlarmManager(  903): sending alarm PendingIntent{42711d40: PendingIntentRecord{42651ae0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452602703823, Int=900000
,D/ConnectivityService(  903): Done.
,D/ConnectivityService(  903): Setting timer for 720seconds
,D/PMS     (  903): releaseWL(426ad620): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,W/ContextImpl( 4582): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  903): releaseWL(435aa7b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,D/PMS     (  903): acquireWL(440ddf78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PowerUI ( 1114): closing low battery warning: level=98
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1563): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1563): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  903): releaseWL(440ddf78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1114): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43bad028): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41c03ad0: PendingIntentRecord{423b1410 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1898209, Int=0
,D/Process (  903): killProcessQuiet, pid=4046
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.trimApplications:17252 
,D/Process (  903): killProcessQuiet, pid=4289
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Killing 4046:com.android.vending/u0a73 (adj 15): empty for 1806s
,I/ActivityManager(  903): Killing 4289:com.android.settings:remote/1000 (adj 15): empty for 1819s
I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,I/ActivityManager(  903): Recipient 4289
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  903): releaseWL(43bad028): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ActivityManager(  903): Recipient 4046
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4707): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4707): ====startRecUseTime====
D/htc.customization.log.level( 4707):  is 
W/CustomizationLogLevel( 4707): Level value is invalid, use default level 2
D/CustomizationManager( 4707):  Read ACC file spent 0.108 (s)
D/CIDMapFileReader( 4707): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4707): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4707): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4707): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4707): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4707): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4707): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4707): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4707): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4707): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4707): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4707): Parsing tag category name = system
I/CustomizationCIDLoader( 4707): Parsing tag category name = application
I/CustomizationCIDLoader( 4707): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4707): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4707): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4707): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4707): Parsing tag category name = Settings
D/CustomizationManager( 4707):  Read CID file spent 0.164 (s)
D/CustomizationManager( 4707):  All configurations done spent 0.164 (s)
W/HtcNativeFlag( 4707): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4707): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4707): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4707): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  903): deletePackageAsUser: pkg=com.test.thalitest, pid=4707, uid=2000 user=0
I/ActivityManager(  903): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
D/Process (  903): killProcessQuiet, pid=4457
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  903): Killing 4457:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1801s
D/Process (  903): killProcessQuiet, pid=4440
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  903): killProcessQuiet, pid=4426
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  903): killProcessQuiet, pid=3826
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  903): Killing 4440:com.android.chrome/u0a96 (adj 15): empty for 1801s
I/ActivityManager(  903): Killing 4426:com.google.android.setupwizard/u0a78 (adj 15): empty for 1801s
I/ActivityManager(  903): Killing 3826:com.google.android.music:main/u0a154 (adj 15): empty for 1801s
D/Process (  903): killProcessQuiet, pid=4372
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  903): Killing 4372:com.htc.mms.backupagent/u0a77 (adj 15): empty for 1807s
I/ActivityManager(  903): Recipient 4440
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 4372
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  903): Client com.google.android.music (pid 3826): Died!
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/asset   (  903): Copying FileAsset 0x627e1058 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  903): Recipient 3826
I/ActivityManager(  903): Recipient 4457
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 4426
W/PackageSettings(  903): Skipping PackageSetting{422853e8 com.example.hello/10356} due to missing metadata
I/ActivityManager(  903): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1563): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1563): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1563): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/acms    ( 1863): Unregistering com.test.thalitest
E/acms    ( 1863): Could not unregister removed application com.test.thalitest
W/GeofencerStateMachine( 1447): Ignoring removeGeofence because network location is disabled.
W/AccTypeManager( 1335): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1335): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  903): acquireWL(425f0aa8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1447 10028 null
D/PMS     (  903): releaseWL(425f0aa8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/dalvikvm-heap( 4084): Grow heap (frag case) to 13.520MB for 1821008-byte allocation
W/SystemReader( 1255): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/VoicemailCleanupService( 1282): Cleaning up data for package: com.test.thalitest
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "sms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/AccTypeManager( 1335): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "smsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/Launcher( 1270): Deferring update until onResume
D/Launcher( 1270): waitUntilResume // bindAppsRemoved
D/PackageBroadcastService( 2240): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/ActivityManager(  903): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4721 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mmsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
E/ExternalAccountType( 1335): Unsupported attribute readOnly
I/PackageManager(  903):   Scheme: "sms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/InputMethodManagerService(  903): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "smsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/ActivityManager(  903): Delaying start of: ServiceRecord{440fdb58 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/ActivityManager(  903): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4736 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/MultiDex( 4721): install
I/MultiDex( 4721): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mmsto"
I/MultiDex( 4721): loading existing secondary dex files
I/MultiDex( 4721): load found 1 secondary dex files
I/MultiDex( 4721): install done
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
D/PhoneApp( 1244): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/PeopleContactsSync( 2240): CP2 sync disabled
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2240, uid=10028, userID:0
D/PMS     (  903): acquireWL(43848798): PARTIAL_WAKE_LOCK  Icing 0x1 2240 10028 null
I/Icing   ( 2240): doRemovePackageData com.test.thalitest
I/ProviderInstaller( 4721): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/MultiDex( 4736): install
I/MultiDex( 4736): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4736): loading existing secondary dex files
I/MultiDex( 4736): load found 1 secondary dex files
I/MultiDex( 4736): install done
D/PMS     (  903): releaseWL(43848798): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ProviderInstaller( 4736): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
W/SQLiteConnectionPool( 2240): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/metrics.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
W/SQLiteConnectionPool( 2240): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/help_responses.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/ActivityManager(  903): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
W/SQLiteConnectionPool( 2240): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/history_query.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/ActivityManager(  903): Resuming delayed broadcast
I/[PluginManager]RegisterService( 1396): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/ActivityManager(  903): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 1396): handle notify Blinkfeed plugin client changed
I/ActivityManager(  903): Resuming delayed broadcast
I/ActivityManager(  903): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4756 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
D/Process (  903): killProcessQuiet, pid=4084
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4084:com.google.android.apps.plus/u0a160 (adj 15): empty for 1801s
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4756, uid=10073, userID:0
D/Finsky  ( 4756): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
I/ActivityManager(  903): Recipient 4084
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  903): getAllNetworkInfo called by com.android.vending (4756/10073)
D/ConnectivityService(  903): getAllNetworkInfo called by com.android.vending (4756/10073)
D/Finsky  ( 4756): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
W/Settings( 4756): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 4756): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4756, uid=10073, userID:0
W/PackageManager(  903): Unable to load service info ResolveInfo{436e7ff8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  903): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  903): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  903): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  903): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  903): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  903): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  903): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  903): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  903): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  903): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  903): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  903): 	at dalvik.system.NativeStart.main(Native Method)
D/Prism.PackageStateRece_( 1270): action: android.intent.action.PACKAGE_REMOVED
D/Finsky  ( 4756): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4756): [1] 2.run: Finished loading 1 libraries.
I/IcingCorporaProvider( 2892): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  903): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4796 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
D/Finsky  ( 4756): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Finsky  ( 4756): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
D/PMS     (  903): acquireWL(42473170): PARTIAL_WAKE_LOCK  Icing 0x1 2240 10028 null
W/ContextImpl( 4721): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.gms/files
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (4721/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (4721/10028)
E/SQLiteLog( 2892): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2892): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x64452030
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (4721/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (4721/10028)
E/IcingCorporaProvider( 2892): Exception thrown from notifyTableChanged
E/IcingCorporaProvider( 2892): java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2892): 	at apg.a(PG:301)
E/IcingCorporaProvider( 2892): 	at apg.c(PG:222)
E/IcingCorporaProvider( 2892): 	at clo.b(PG:660)
E/IcingCorporaProvider( 2892): 	at clo.a(PG:651)
E/IcingCorporaProvider( 2892): 	at clo.g(PG:597)
E/IcingCorporaProvider( 2892): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/IcingCorporaProvider( 2892): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/IcingCorporaProvider( 2892): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/IcingCorporaProvider( 2892): 	at clp.Rl(PG:910)
E/IcingCorporaProvider( 2892): 	at clr.tL(PG:827)
E/IcingCorporaProvider( 2892): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/IcingCorporaProvider( 2892): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/IcingCorporaProvider( 2892): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/IcingCorporaProvider( 2892): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/IcingCorporaProvider( 2892): 	at android.os.Looper.loop(Looper.java:157)
E/IcingCorporaProvider( 2892): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/IcingCorporaProvider( 2892): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2892): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/IcingCorporaProvider( 2892): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/IcingCorporaProvider( 2892): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/IcingCorporaProvider( 2892): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/IcingCorporaProvider( 2892): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/IcingCorporaProvider( 2892): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/IcingCorporaProvider( 2892): 	at apa.a(PG:382)
E/IcingCorporaProvider( 2892): 	at apg.i(PG:325)
E/IcingCorporaProvider( 2892): 	at aph.call(PG:215)
E/IcingCorporaProvider( 2892): 	at apg.a(PG:299)
E/IcingCorporaProvider( 2892): 	... 15 more
W/IcingCorporaProvider( 2892): notifyTableChanged failed.
W/IcingCorporaProvider( 2892): Table change notification failed for TableStorageSpec[applications]
I/IcingCorporaProvider( 2892): UpdateCorporaTask done [took 148 ms] updated apps [took 148 ms] 
D/PMS     (  903): releaseWL(42473170): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/RemoteDisplayProvider(  903): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  903): start
W/AtomicFile(  903): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  903): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
E/SQLiteDatabase( 4796): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4796): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4796): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4796): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4796): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4796): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4796): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4796): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4796): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4796): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4796): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4796): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4796): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4796): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4796): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4796): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4796): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4796): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4796): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4796): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4796): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4796): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4796): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4796): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4796): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4796): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4796): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4796): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4796): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4796): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4796): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4796): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4796): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4796): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4796): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4796): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4796): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4796): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4796): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4796): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4796): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4796): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4796): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4796): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4796): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4796): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4796): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4796): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4796): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4796): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4796): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4796): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4796): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4796): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4796): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4796): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4796): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4796): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4796): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4796): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4796): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4796): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4796): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4796): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4796): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4796): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4796): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4796): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4796): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4796): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4796): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4796): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4796): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4796): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4796): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4796): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4796): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4796): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4796): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4796): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4796): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4796): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4796): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4796): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4796): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4796): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4796): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4796): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4796): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4796): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4796): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4796): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4796): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4796): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4796): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4796): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4796): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4796): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4796): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4796): threadid=11: thread exiting with uncaught exception (group=0x41739e30)
E/ActivityManager(  903): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4796): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4796): Process: com.google.android.apps.docs, PID: 4796
E/AndroidRuntime( 4796): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4796): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4796): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4796): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4796): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4796): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4796): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4796): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4796): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4796): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4796): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4796): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4796): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4796): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4796): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4796): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4796): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4796): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4796): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  903): Can't write: system_app_crash
E/DropBoxManagerService(  903): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  903): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  903): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  903): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  903): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  903): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  903): 	... 5 more
D/Process ( 4796): killProcess, pid=4796
D/Process ( 4796): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  903): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4817 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  903): Recipient 4796
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Process com.google.android.apps.docs (pid 4796) has died.
W/ContextImpl( 4817): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 4817): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4817): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4817): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4817): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4817): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4817): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4817): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4817): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4817): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4817): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4817): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4817): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4817): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4817): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4817): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4817): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4817): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4817): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4817): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4817): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4817): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4817): threadid=10: thread exiting with uncaught exception (group=0x41739e30)
I/ActivityManager(  903): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4830 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/ActivityManager(  903): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4817): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4817): Process: com.android.keychain, PID: 4817
E/AndroidRuntime( 4817): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4817): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4817): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4817): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4817): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4817): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4817): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4817): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4817): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4817): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4817): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4817): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4817): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4817): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4817): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4817): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4817): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4817): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4817): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4817): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  903): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4817): killProcess, pid=4817
D/Process ( 4817): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  903): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  903): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452602775363.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  903): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  903): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  903): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  903): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  903): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  903): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  903): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  903): 	... 4 more
I/ActivityManager(  903): Recipient 4817
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Process com.android.keychain (pid 4817) has died.
W/ActivityManager(  903): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/AppTag  ( 4830): getInstance(Context context)
D/AppTag  ( 4830): getInstance(Context context)
D/AppTag  ( 4830): onCreate()
I/ActivityManager(  903): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4845 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1270): loadItems() com.htc.launcher.pageview.WidgetManager@41bfcd98 +
I/Prism.WidgetManager( 1270): onLoadItems() +
E/SQLiteDatabase( 4845): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
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
E/SQLiteDatabase( 4845): 	at dek.getWritableDatabase(PG:48)
E/SQLiteDatabase( 4845): 	at del.a(PG:264)
E/SQLiteDatabase( 4845): 	at eeq.run(PG:187)
E/SQLiteDatabase( 4845): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteDatabase( 4845): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
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
E/SQLiteDatabase( 4845): 	at dek.getWritableDatabase(PG:51)
E/SQLiteDatabase( 4845): 	at del.a(PG:264)
E/SQLiteDatabase( 4845): 	at eeq.run(PG:187)
E/SQLiteDatabase( 4845): 	at java.lang.Thread.run(Thread.java:864)
I/ActivityManager(  903): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4864 uid=10098 gids={50098, 3003, 5012}
E/EsApplication( 4845): Failed app initialization
E/EsApplication( 4845): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/EsApplication( 4845): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/EsApplication( 4845): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/EsApplication( 4845): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/EsApplication( 4845): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/EsApplication( 4845): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/EsApplication( 4845): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/EsApplication( 4845): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/EsApplication( 4845): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/EsApplication( 4845): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/EsApplication( 4845): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/EsApplication( 4845): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/EsApplication( 4845): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/EsApplication( 4845): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/EsApplication( 4845): 	at dek.getWritableDatabase(PG:51)
E/EsApplication( 4845): 	at del.a(PG:264)
E/EsApplication( 4845): 	at eeq.run(PG:187)
E/EsApplication( 4845): 	at java.lang.Thread.run(Thread.java:864)
D/PMS     (  903): acquireWL(437b27b0): PARTIAL_WAKE_LOCK  AsyncService 0x1 4845 10160 null
D/PMS     (  903): releaseWL(437b27b0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/PMS     (  903): acquireWL(436476f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10073}
V/AlarmManager(  903): sending alarm PendingIntent{424b62e0: PendingIntentRecord{425526b8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452602775662, Int=0
D/PMS     (  903): releaseWL(436476f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
E/RollingFileStream( 4756): Could not create a temp file with prefix: "eventlog.store" and suffix: ".log" in dir: "/data/data/com.android.vending/cache/logs/com.google.thalitester%40gmail.com".
I/DeviceManagement( 4864): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4864 dbg=false s=true
I/DeviceManagement( 4864): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 4864): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 4864): WorkflowService: Starting workflow service
I/DeviceManagement( 4864): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b99f58] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4864): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4864): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 4864): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4864): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  903): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4881 uid=10099 gids={50099, 3003, 5012}
I/DeviceManagement( 4864): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 4864): SessionStateController: Checking invariants...
W/GLSUser ( 1361): GoogleAccountDataService.getToken()
W/GLSActivity( 1361): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1361): GLS error: BadAuthentication thalitester@gmail.com androidmarket
W/GLSActivity( 1361): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/Documents( 4881): Loading roots for com.android.providers.downloads.documents
D/Documents( 4881): Loading roots for com.android.externalstorage.documents
E/SQLiteDatabase( 4881): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
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
E/SQLiteDatabase( 4881): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4881): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4881): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4881): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4881): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4881): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4881): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4881): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4881): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4881): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4881): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4881): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4881): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4881): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4881): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4881): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 4881): threadid=1: thread exiting with uncaught exception (group=0x41739e30)
E/AndroidRuntime( 4881): FATAL EXCEPTION: main
E/AndroidRuntime( 4881): Process: com.android.documentsui, PID: 4881
E/AndroidRuntime( 4881): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4881): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4881): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4881): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4881): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4881): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4881): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4881): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4881): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4881): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4881): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4881): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4881): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
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
E/AndroidRuntime( 4881): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4881): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4881): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4881): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4881): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4881): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4881): 	... 10 more
I/ActivityManager(  903): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4895 uid=10023 gids={50023, 1028, 1015, 1023}
E/ActivityManager(  903): App crashed! Process: com.android.documentsui
D/ErrorReport(  903): HtcErrorReportManager Begin---add error logs to dropbox
D/GCM     ( 1361): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/Process ( 4881): killProcess, pid=4881
E/ErrorReport(  903): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  903): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452602775817.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  903): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  903): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  903): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  903): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  903): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  903): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  903): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  903): 	... 4 more
D/Process ( 4881): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/GCM     ( 1361): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
W/GLSUser ( 1361): GoogleAccountDataService.getToken()
D/ExternalStorage( 4895): After updating volumes, found 1 active roots
E/JavaBinder(  903): !!! FAILED BINDER TRANSACTION !!!
W/ContentService(  903): Found dead observer, removing
W/GLSActivity( 1361): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1361): GLS error: BadAuthentication thalitester@gmail.com androidmarket
I/ActivityManager(  903): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=4912 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
W/GLSActivity( 1361): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION

```
