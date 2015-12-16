#### Test 50650278b44f053_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1158): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
,E/cutils-trace( 4378): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4378): ====startRecUseTime====
D/htc.customization.log.level( 4378):  is 
W/CustomizationLogLevel( 4378): Level value is invalid, use default level 2
D/CustomizationManager( 4378):  Read ACC file spent 0.050 (s)
D/CIDMapFileReader( 4378): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4378): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4378): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4378): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4378): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4378): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4378): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4378): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4378): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4378): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4378): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4378): Parsing tag category name = system
I/CustomizationCIDLoader( 4378): Parsing tag category name = application
I/CustomizationCIDLoader( 4378): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4378): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4378): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4378): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4378): Parsing tag category name = Settings
D/CustomizationManager( 4378):  Read CID file spent 0.089 (s)
D/CustomizationManager( 4378):  All configurations done spent 0.089 (s)
W/HtcNativeFlag( 4378): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4378): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4378): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4378): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
W/CpuWake (  906): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  906): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4378
D/PMS     (  906): acquireHCC(425bb978): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 906 1000 null
D/PMS     (  906): acquireHCC(425a6cd8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 906 1000 null
W/asset   (  906): Copying FileAsset 0x62aeb558 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  906): @test_code: getHtcIntentFlag: 0 obj: 1123703448
I/FeedHostManager( 1270): [onPause]
I/FeedProviderManager( 1270): onPause
I/FeedHostManager( 1270): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41b34948
I/SocialFeedProvider( 1270): +onPause
I/SocialFeedProvider( 1270): -onPause
D/PMS     (  906): acquireWL(42589768): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
I/ActivityManager(  906): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4389 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1270): [trimMemory] 20
W/asset   ( 4389): Copying FileAsset 0x5c717428 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4389): Binding Chromium to main looper Looper (main, tid 1) {41a9fd70}
I/LibraryLoader( 4389): Expected native library version number "",actual native library version number ""
I/chromium( 4389): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4389): Initializing chromium process, renderers=0
D/PMS     (  906): acquireWL(42497ad8): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
D/PMS     (  906): acquireWL(42458938): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  906): java.lang.Throwable: stack dump
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@423fa570:true
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4389): 1101750464: getState(). Returning 12
D/PMS     (  906): releaseWL(42497ad8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4389): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4389): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4389): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4389): Local Branch: 
I/Adreno-EGL( 4389): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4389): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4389):                  aa63bbd948f41d15fc72f585e
W/chromium( 4389): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4389): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4389): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4389): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4389): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4389): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4389): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4389): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4389): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4389): CordovaWebView is running on device made by: HTC
,W/AwContents( 4389): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  906): Disable input method client, pid=1270
,W/ResourceType( 4389): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4389): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41ae7770, mServedView=org.apache.cordova.engine.SystemWebView{41aad3d8 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1210): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1210): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,I/InputMethodManagerService(  906): Enable input method client, pid=4389
W/AwContents( 4389): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  906): Displayed com.test.thalitest/.MainActivity: +274ms
D/PMS     (  906): releaseWL(42589768): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4389): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4389): JniHelper::setJavaVM(0x41577048), pthread_self() = 1662163544
,D/JX-Cordova( 4389): jxcore cordova android initializing
,D/PMS     (  906): acquireWL(42c88eb8): PARTIAL_WAKE_LOCK  Icing 0x1 2226 10028 null
,D/PMS     (  906): releaseWL(42c88eb8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(42c89160): PARTIAL_WAKE_LOCK  Icing 0x1 2226 10028 null
,D/PMS     (  906): releaseWL(42c89160): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(420db578): PARTIAL_WAKE_LOCK  Icing 0x1 2226 10028 null
,D/PMS     (  906): releaseWL(420db578): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(425ad1f0): PARTIAL_WAKE_LOCK  Icing 0x1 2226 10028 null
,D/PMS     (  906): releaseWL(425ad1f0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/dalvikvm-heap( 4389): Grow heap (frag case) to 11.579MB for 96598-byte allocation
,I/dalvikvm-heap( 4389): Grow heap (frag case) to 11.630MB for 144892-byte allocation
,I/dalvikvm-heap( 4389): Grow heap (frag case) to 11.739MB for 217334-byte allocation
,I/dalvikvm-heap( 4389): Grow heap (frag case) to 11.915MB for 325996-byte allocation
,I/dalvikvm-heap( 4389): Grow heap (frag case) to 12.189MB for 488990-byte allocation
,I/dalvikvm-heap( 4389): Grow heap (frag case) to 13.196MB for 1100216-byte allocation
,I/dalvikvm-heap( 4389): Grow heap (frag case) to 14.073MB for 1650320-byte allocation
,I/dalvikvm-heap( 4389): Grow heap (frag case) to 15.454MB for 2475476-byte allocation
,I/ActivityManager(  906): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4437 uid=10077 gids={50077}
,D/PMS     (  906): acquireWL(41caaaf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10077}
V/AlarmManager(  906): sending alarm PendingIntent{4249b138: PendingIntentRecord{422e67c8 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1450287759483, Int=60000
,D/PMS     (  906): releaseWL(41caaaf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4437): SMSBackupAgentService started
,D/SMSBackup( 4437): Checking restore status
D/SMSBackup( 4437): Restore complete
,D/SMSBackup( 4437): cancelCheckAlarm
,D/SMSBackup( 4437): SMSBackupAgentService completed: completed in 0.0 seconds
D/Process (  906): killProcessQuiet, pid=3230
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3230:com.android.defcontainer/u0a19 (adj 15): empty #17
I/ActivityManager(  906): Recipient 3230
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4389): Grow heap (frag case) to 17.500MB for 3713210-byte allocation
,W/jxcore-log( 4389): Initializing JXcore engine
,W/jxcore-log( 4389): JXcore engine is ready
,W/jxcore-log( 4389): Starting JXcore engine
,W/CpuWake (  906): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  906): <<release mCpuPerf_Freq wakelock
D/PMS     (  906): releaseHCC(425bb978): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  906): releaseHCC(425a6cd8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1158): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,W/jxcore-log( 4389): Platform android
W/jxcore-log( 4389): 
,W/jxcore-log( 4389): Process ARCH arm
W/jxcore-log( 4389): 
,I/jxcore-log( 4389): JXcore Cordova bridge is ready!
I/jxcore-log( 4389): 
,W/jxcore-log( 4389): JXcore engine is started
,I/chromium( 4389): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/WIFI_ICON( 1119): WifiActivity: 0
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  906): releaseWL(42458938): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/PMS     (  906): acquireWL(420e62f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4249a9e0: PendingIntentRecord{4242d618 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=105638, Int=0
D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=69 rxSum=56} preTxRxSum={txSum=68 rxSum=55}
D/WifiDataStallTracker(  906): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  906): onDataStallAlarm: tag=20115 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20116 delay=15s
D/PMS     (  906): releaseWL(420e62f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WIFI_ICON( 1119): WifiActivity: 1
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/jxcore-log( 4389): Toggling radios to true
I/jxcore-log( 4389): 
,D/BluetoothAdapter( 4389): enable(): BT is already enabled..!
,D/WifiManager( 4389): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  906): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 2
W/Settings:Agent(  906): >> traceCallingStack()
W/Settings:Agent(  906): Process.myPid(): 906
W/Settings:Agent(  906): Process.myTid(): 1268
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
W/Settings:Agent(  906): << traceCallingStack(): 0(ms)
D/WifiService(  906): New client listening to asynchronous messages
D/WifiService(  906): setWifiEnabled: true pid=4389, uid=10348
E/WifiService(  906): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  906): isSprintWifiRestricted(): false
I/WifiService(  906): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  906): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
D/WifiManager( 4389): disconnect: Base Package Name=com.test.thalitest, uid=10348
D/WifiManager( 4389): reconnect: Base Package Name=com.test.thalitest, uid=10348
D/WifiNative-wlan0(  906): doBoolean: DISCONNECT
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1158): TDLS: Tear down peers
I/wpa_supplicant( 1158): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4389): Radios toggled
I/jxcore-log( 4389): 
D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4389): Got Device Bluetooth address: 80:01:84:8A:B3:68
I/jxcore-log( 4389): 
I/jxcore-log( 4389): Perf Test app loaded loaded
I/jxcore-log( 4389): 
I/Choreographer( 4389): Skipped 78 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 4389): check test folder
I/jxcore-log( 4389): 
,I/jxcore-log( 4389): found test : ./testFindPeers.js
I/jxcore-log( 4389): 
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1158): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1158): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1158): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  906): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  906): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  906): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1158): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1158): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1158): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1158): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1158): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1158): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1158): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1158): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
,E/wpa_supplicant( 1158): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1158): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb7fa7bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
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
I/wpa_supplicant( 1158): htc_wext_set_TX_TRACKING (0)+
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
D/WifiNative-wlan0(  906):    returned true
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/WifiPerfLock(  906): release()
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  906): PerfLock released for exiting ConnectedState
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:h,andleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1158): Power_Mode_Type mode = 0
I/wpa_supplicant( 1158): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  906):    returned true
,I/jxcore-log( 4389): found test : ./testSendData.js
I/jxcore-log( 4389): 
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1158): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  906):    returned true
D/ConnectivityService(  906): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  906): acquireWL(434ff490): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 906 1000 null
D/WifiP2pService(  906): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/DhcpStateMachine(  906): [RunningState] Stop DHCP
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  906): doBoolean: RECONNECT
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1158): Fast associate: Old scan results
I/wpa_supplicant( 1158): wpa_supplicant_scan enter
I/wpa_supplicant( 1158): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1158): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1158): wpa_supplicant_trigger_scan +
D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1158): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1158): nl80211: Event message available
D/wpa_supplicant( 1158): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): Enter handleNetworkDisconnect
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=20116 mDataStallAlarmIntent=PendingIntent{4253c6b0: PendingIntentRecord{4242d618 android broadcastIntent}}
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  906): Provision feature enable=false
,D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1158): Power_Mode_Type mode = 0
I/wpa_supplicant( 1158): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 61
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,D/WifiNative-wlan0(  906):    returned true
D/UsbnetStateTracker(  906): isAvailable+-
D/UsbnetStateTracker(  906): reconnect
,D/UsbnetStateTracker(  906): isAvailable+-
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1158): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  906):    returned true
D/ConnectivityService(  906): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  906): default: reconnect()
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/MDST    (  906): default: setTeardownRequested(false)
D/MDST    (  906): default: setEnableApn apnType =default , enable=true
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1834/10178)
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  906): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  906): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '28 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 28 Failed to remove route from default table (No such process)'
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WISPrService( 4166): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  906): Exit handleNetworkDisconnect
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WISPrService( 4166): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  906): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  906): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/ConnectivityService(  906): resetConnections(wlan0, 3)
D/WISPrService( 4166): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/libc    (  364): [NET] entry_id:5   entry:0xb792d028  removed 
D/libc    (  364): [NET] entry_id:6   entry:0xb792d818  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb792d2d8  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb792d108  removed 
D/libc    (  364): [NET] entry_id:7   entry:0xb792d718  removed 
D/libc    (  364): [NET] entry_id:3   entry:0xb792d1d0  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb792d410  removed 
D/libc    (  364): [NET] entry_id:8   entry:0xb792cd90  removed 
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
D/WifiService(  906): New client listening to asynchronous messages
D/PMS     (  906): acquireWL(43fc2e90): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1370 10028 null
D/ConnectivityService(  906): flush DNS cache for net 1(wlan0)
,D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1834/10178)
D/WISPrService( 4166): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  906): acquireWL(43a472a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10028 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10028)
D/PMS     (  906): acquireWL(4253d8f8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  906): reportInetCondition for net -1, percentage: 0 by  (1370/10028)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/PMS     (  906): releaseWL(43fc2e90): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  906): releaseWL(43a472a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
,D/ConnectivityService(  906): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/WifiStateMachine(  906): startScan Pid: 906 Uid 1000
,D/WifiNative-wlan0(  906): doBoolean: SCAN
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1158): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  906):    returned false
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:0
I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10028)
D/BatSI   (  906): WIFI scan started for: 650a0300 uid:1000
D/PMS     (  906): releaseWL(4253d8f8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  906): mActiveDefaultNetwork: -1
,D/ConnectivityService(  906): handleInetConditionChange: no active default network - ignore
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:1
,I/chromium( 4389): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: false
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
D/CaptivePortalTracker(  906): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  906): NoActiveNetworkState
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  906): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42392f70): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/PMS     (  906): releaseWL(42392f70): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/ConnectivityHelper( 1270): [onReceive] WIFI(1): DISCONNECTED
,D/Tethering(  906): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  906): bSetPropertyMultiRAB:false
D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
,I/NetworkMonitor( 3890): type=WIFI subType= reason=null isConnected=false
I/Tethering(  906): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  906): ipv4Default null
I/Tethering(  906): No IPv4 upstream interface, giving up.
,D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1443/10028)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1270/10075)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1872/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1834/10178)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3890/10154)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4280/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4280/10100)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1999/10021)
,I/ActivityManager(  906): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4460 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4460): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4460): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4460): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4460): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4460): Preparing secondary program dexes.
V/DexLibLoader( 4460): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4460): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4460): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
,V/DexLibLoader( 4460): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4460): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4460): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4460): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4460): Dex already copied
D/OdexVerifier( 4460): Odex verification is skipped.
,V/DexLibLoader( 4460): Creating class loader
,V/DexLibLoader( 4460): Finished creating class loader
V/DexLibLoader( 4460): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4460): Dex already copied
D/OdexVerifier( 4460): Odex verification is skipped.
,V/DexLibLoader( 4460): Creating class loader
,V/DexLibLoader( 4460): Finished creating class loader
V/DexLibLoader( 4460): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4460): Dex already copied
D/OdexVerifier( 4460): Odex verification is skipped.
,V/DexLibLoader( 4460): Creating class loader
,V/DexLibLoader( 4460): Finished creating class loader
V/DexLibLoader( 4460): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
,V/DexLibLoader( 4460): Dex already copied
D/OdexVerifier( 4460): Odex verification is skipped.
,V/DexLibLoader( 4460): Creating class loader
,V/DexLibLoader( 4460): Finished creating class loader
,V/DexLibLoader( 4460): Verifying classes from secondary dexes.
,D/DexLibLoader( 4460): DexLibLoader.ensureDexLoaded took 22 ms
,W/dalvikvm( 4460): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4460): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4460): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4460): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4460): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4460): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4460): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4460): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4460): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1158): nl80211: Event message available
D/wpa_supplicant( 1158): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1158): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1158): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1158): nl80211: Survey data missing
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1158): Sorted scan results
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1158): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1158): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
I/wpa_supplicant( 1158): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-80
I/wpa_supplicant( 1158): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-87
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
D/wpa_supplicant( 1158): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1158): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1158): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1158): wpa_supplicant_pick_network+
I/wpa_supplicant( 1158): Selecting BSS from priority group 1
I/wpa_supplicant( 1158): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1158): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1158): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1158): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1158):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1158):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1158): Start print parameters
I/wpa_supplicant( 1158): wpa_s->wpa_state is 3
I/wpa_supplicant( 1158): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1158): isConcurrentMode() is 0
I/wpa_supplicant( 1158): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1158): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1158): wpa_s->bt_a2dp_status is, 0
I/wpa_supplicant( 1158): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1158): wpa_s->reassociate is 1
I/wpa_supplicant( 1158): wpa_s->is_screen_on 1
I/wpa_supplicant( 1158): wpa_s->ifname wlan0
I/wpa_supplicant( 1158): End print parameters
I/wpa_supplicant( 1158): selected network = 1
D/wpa_supplicant( 1158): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb7fa94e8  current_ssid=0x0
D/wpa_supplicant( 1158): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1158): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1158): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1158): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1158): check if in concurrent case
I/wpa_supplicant( 1158): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1158): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1158): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1158): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1158): RSN: PMKSA cache search - network_ctx=0xb7fa94e8 try_opportunistic=0
D/wpa_supplicant( 1158): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1158): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1158): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1158): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1158): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1158): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1158): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1158): nl80211: Unsubscribe mgmt frames handle 0xb7fa8718 (mode change)
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1158): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7fa8718
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1158): nl80211: Register frame type=0xd0 nl_handle=0xb7fa8718
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1158): nl80211: Register frame type=0xd0 nl_handle=0xb7fa8718
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1158): nl80211: Register frame type=0xd0 nl_handle=0xb7fa8718
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1158): nl80211: Register frame type=0xd0 nl_handle=0xb7fa8718
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1158): nl80211: Register frame type=0xd0 nl_handle=0xb7fa8718
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1158): nl80211: Register frame type=0xd0 nl_handle=0xb7fa8718
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1158): nl80211: Register frame type=0xd0 nl_handle=0xb7fa8718
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 58
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/wpa_supplicant( 1158): nl80211: Register frame type=0xd0 nl_handle=0xb7fa8718
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1158): nl80211: Register frame type=0xd0 nl_handle=0xb7fa8718
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1158): nl80211: Register frame type=0xd0 nl_handle=0xb7fa8718
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1158): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1158):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1158):   * freq=2412
,D/wpa_supplicant( 1158):   * Auth Type 0
D/wpa_supplicant( 1158):   * WPA Versions 0x2
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1158): nl80211: Connect request send successfully
D/wpa_supplicant( 1158): EAPOL: External notification - EAP success=0
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
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1158): reply (778) for get BSS: id=0
I/wpa_supplicant( 1158): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1158): freq=5220
I/wpa_supplicant( 1158): level=-48
I/wpa_supplicant( 1158): tsf=0000000108881246
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=NG7005g
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=1
I/wpa_supplicant( 1158): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1158): freq=2412
I/wpa_supplicant( 1158): level=-54
I/wpa_supplicant( 1158): tsf=0000000108881264
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=NG700
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=2
I/wpa_supplicant( 1158): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1158): freq=2427
I/wpa_supplicant( 1158): level=-72
I/wpa_supplicant( 1158): tsf=0000000108881269
I/wpa_supplicant( 1158): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1158): ssid=Gonzos
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=3
I/wpa_supplicant( 1158): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1158): freq=2437
I/wpa_supplicant( 1158): level=-80
I/wpa_supplicant( 1158): tsf=0000000108881273
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1158): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=4
I/wpa_supplicant( 1158): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1158): freq=2437
I/wpa_supplicant( 1158): level=-87
I/wpa_supplicant( 1158): tsf=0000000108881276
I/wpa_supplicant( 1158): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=UPC4688432
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=5
I/wpa_supplicant( 1158): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1158): freq=2412
I/wpa_supplicant( 1158): level=-54
I/wpa_supplicant( 1158): tsf=0000000108881259
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1158): ssid=01ABC
I/wpa_supplicant( 1158): ####
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 108881246, distance: ?(cm), distanceSd: ?(cm)
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,E/FbInjectorInitializer( 4460): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (6) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 108881264, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2427, timestamp: 108881269, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -80, frequency: 2437, timestamp: 108881273, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -87, frequency: 2437, timestamp: 108881276, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 108881259, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 6 to mScanResults
D/BatSI   (  906): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/wpa_supplicant( 1158): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1158): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1158): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 1158): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1158): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1158): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1158): nl80211: if_removed already cleared - ignore event
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1158): nl80211: Event message available
D/wpa_supplicant( 1158): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1158): nl80211: Connect event
D/wpa_supplicant( 1158): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1158): nl80211: Associated with c0:ff:d4:d3:aa:48
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
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1158): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1158): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1158): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1158): EAPOL: External notification - EAP success=0
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
I/wpa_supplicant( 1158): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1158): State: ASSOCIATED -> 4WAY_HANDSHAKE
,D/wpa_supplicant( 1158): Get randomness: len=32 entropy=7
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/Tethering(  906): [isWifi] getHotspotEnabled: false,
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  906): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  906): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
D/HTCRequest(  906): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  906): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  906): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  906): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  906): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  906): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  906): Enter handleAssociatedWithEvent
D/WifiStateMachine(  906): Associated
D/WifiStateMachine(  906): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  906): Exit handleAssociatedWithEvent
D/Tethering(  906): interfaceStatusChanged wlan0, true
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  906): [isWifi] getHotspotEnabled: false
,D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
,D/WifiStateMachine(  906): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
I/wpa_supplicant( 1158): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1158): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb7fa89f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 1158):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1158): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1158): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1158): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f86b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1158):    broadcast key
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1158): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1158): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1158): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1158): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1158): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,I/wpa_supplicant( 1158): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  906): This record is existed, only update it...
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
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
D/wpa_supplicant( 1158): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1158): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1158): EAPOL authentication completed successfully
I/wpa_supplicant( 1158): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1158): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1158): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1158): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  906): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
D/Tethering(  906): interfaceStatusChanged wlan0, true
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,W/fb4a(:<default>):StaticBindingVerifier( 4460): Verify
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/WifiStateMachine(  906): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  906): This record is existed, only update it...
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  906): updateConnectedAP...
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/WISPrService( 4166): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4166): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/DhcpStateMachine(  906): [StoppedState] Start DHCP
,D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=50 [2][1][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1158): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1158): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1158): Power_Mode_Type mode = 1
I/wpa_supplicant( 1158): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1158): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  906):    returned null
E/WifiStateMachine(  906): Unexpected BatchedScanResults :null,
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): wpa_driver_nl80211_driver_cmd: failed to issue private commands,
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  906):    returned null
,D/WifiStateMachine(  906): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  906): acquireWL(42535f28): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 906 1000 null
D/WifiStateMachine(  906): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@424d6b68 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@424d6b68 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:1
,D/WifiService(  906): New client listening to asynchronous messages
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4460): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4460): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4460): Grow heap (frag case) to 9.509MB for 73240-byte allocation
,D/Process (  906): killProcessQuiet, pid=3873
,I/ActivityManager(  906): Killing 3873:com.htc.mediamanager/u0a32 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/PMS     (  906): acquireWL(42fef4a8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2226 10028 null
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3873
,D/PMS     (  906): acquireWL(430e7d08): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2226 10028 null
,D/PMS     (  906): releaseWL(42fef4a8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1370): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2226/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10028)
D/PMS     (  906): releaseWL(430e7d08): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2226/10028)
,D/AutoSetting( 1418): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  906): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4488 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1418/10053)
,D/AutoSetting( 1418): Util - no network available!
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1418/10053)
D/AutoSetting( 1418): service - onCreate()
D/AutoSetting( 1418): service - AddressCache: using context: com.htc.Weather
D/LocationManagerService(  906): request 42430bc0 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/LocationManagerService(  906): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1418): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1418): service - mHandler: cancel location update
D/AutoSetting( 1418): service -           changes count: 0
,W/fb4a(:<default>):UserScope( 4460): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4460): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/MobileConnectivityChangeReceiver( 4488): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4488): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4488): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4488): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,W/fb4a(:<default>):UserScope( 4460): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,I/ActivityManager(  906): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4505 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4488/10078)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4488/10078)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4488/10078)
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4460): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  906): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4522 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,I/ActivityManager(  906): Killing 4219:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/Process (  906): killProcessQuiet, pid=4219
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/ActivityManager(  906): Recipient 4219
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  906): Client connection lost with reason: 4
,I/dalvikvm-heap( 4460): Grow heap (frag case) to 9.958MB for 84664-byte allocation
E/dalvikvm( 4460): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4460): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,E/dalvikvm( 4460): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4460): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4522): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4522): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4522): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4522): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,I/dalvikvm-heap( 4460): Grow heap (frag case) to 9.974MB for 28144-byte allocation
E/dalvikvm( 4460): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4460): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,W/ContextImpl( 4522): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,E/dalvikvm( 4460): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4460): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/dalvikvm( 4460): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4460): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4460): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4460): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4460): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4460): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4460): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4460): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4460): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4460): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/dalvikvm-heap( 4460): Grow heap (frag case) to 10.039MB for 39954-byte allocation
,I/dalvikvm-heap( 4460): Grow heap (frag case) to 10.115MB for 79892-byte allocation
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4522/10151)
,V/WebViewChromiumFactoryProvider( 4522): Binding Chromium to main looper Looper (main, tid 1) {41aa5420}
,I/LibraryLoader( 4522): Expected native library version number "",actual native library version number ""
,I/chromium( 4522): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4522): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4522): BLUETOOTH permission is missing!
D/PMS     (  906): acquireWL(43fc0bc0): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
D/PMS     (  906): acquireWL(4424d888): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
D/PMS     (  906): releaseWL(43fc0bc0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4522): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4522): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4522): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4522): Local Branch: 
I/Adreno-EGL( 4522): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4522): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4522):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4522): Starting up...
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4522/10151)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4522/10151)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4143/10160)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4143/10160)
,D/Process (  906): killProcessQuiet, pid=4000
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 4000:com.google.android.gm/u0a107 (adj 15): empty #17
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1834/10178)
,I/dalvikvm-heap( 4460): Grow heap (frag case) to 10.281MB for 75760-byte allocation
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1834/10178)
,D/GCM     ( 1370): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{430f6538 u0 ReceiverList{430f6438 4460 com.facebook.katana/10026/u0 remote:430e3a60}}
,W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{430f6538 u0 ReceiverList{430f6438 4460 com.facebook.katana/10026/u0 remote:430e3a60}}
,W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4366d598 u0 ReceiverList{4366d538 4460 com.facebook.katana/10026/u0 remote:435c55e0}}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/PMS     (  906): acquireWL(44034858): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1443 10028 null
,D/PMS     (  906): releaseWL(44034858): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/ActivityManager(  906): Recipient 4000
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/GCoreFlp( 1443): Unknown pending intent to remove.
D/PMS     (  906): acquireWL(43752a30): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1443 10028 null
D/PMS     (  906): releaseWL(43752a30): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4460): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4460): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,D/wpa_supplicant( 1158): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1158): EAPOL: disable timer tick
,I/SensorManager(  906): mEventCount = 1050
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1158): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1158): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0,
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
D/WifiP2pService(  906): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1158): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): handlePostDhcpSetup release wake lock during DHCP
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(42535f28): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1158): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
D/WIFI_ICON( 1119): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  906): gateway: /192.168.1.1
D/WifiNative-wlan0(  906): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1158): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  906): VerifyingLinkState enter
D/WifiStateMachine(  906): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  906): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  906): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -54, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20118 delay=15s
V/NetworkPolicy(  906): mWifiStateReceiver: meteredHint=false,EPS mode=false
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1834/10178)
,D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
,D/ConnectivityService(  906): Provision feature enable=false
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED connected
D/ConnectivityService(  906): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
,D/WifiWatchdogStateMachine(  906): WAN detection
,D/WISPrService( 4166): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  906): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
V/ConnectivityService(  906): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  906): default: teardown()
D/MDST    (  906): default: setTeardownRequested(true)
D/MDST    (  906): default: setEnableApn apnType =default , enable=false
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/MDST    (  906): default: setTeardownRequested(true)
,D/ConnectivityService(  906): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
,D/WifiStateMachine(  906): syncGetConfiguredNetworks
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
E/ConnectivityService(  906): Unexpected mtu value: android.net.wifi.WifiStateTracker@423cca18
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=false resetMask=0
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
D/WIFI_ICON( 1119): WifiActivity: 3
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/ConnectivityService(  906): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  906): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
D/WirelessDisplayService(  906): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/WirelessDisplayService(  906):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/PMS     (  906): acquireWL(43599340): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4488/10078)
,I/QuickSettingWifi( 1119): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/PMS     (  906): acquireWL(43592350): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2226 10028 null
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
D/PMS     (  906): acquireWL(43735e08): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2226 10028 null
D/PMS     (  906): releaseWL(43592350): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2226/10028)
,I/CheckinService( 2226): Preparing to send checkin request
,I/EventLogService( 2226): Accumulating logs since 1450287710332
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,I/GoogleHttpClient( 2226): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2226): Using GMS GoogleHttpClient
I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@420e8590
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = CM36282 Light sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@420e8590, eanble = 0, strlen(mName) = 59
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@422e69a0
W/SensorService(  906): Listener[1] = com.htc.smartdim.sensor_eye@41ca7e48
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/PMS     (  906): Going to sleep due to screen timeout...
I/ActivityManager(  906): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  906): Couldn't get kernel wake lock stats
V/LightsService(  906): setLight #2: color=#0
D/qdlights(  906): set_light_buttons_func: on=0 brightness=0
V/LightsService(  906): setLight #0: color=#0
D/ConnectivityService(  906): mActiveDefaultNetwork: WIFI
,D/WirelessDisplayService(  906): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  906): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
W/PMS     (  906): mWirelessDisplayManager is null
,D/PMS     (  906): releaseWL(43599340): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (2226/10028)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (2226/10028)
,W/GLSUser ( 1370): GoogleAccountDataService.getToken()
,W/GLSActivity( 1370): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1370): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1370): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/CheckinRequestBuilder( 2226): awaiting user notification for token
,D/DotMatrix( 1566): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1119): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41aaccd8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1119): com.google.android.gms 1 6 3 12
,D/SurfaceControl(  906): Excessive delay in blankDisplay() while turning screen off: 390ms
D/PMS     (  906): nativeSetInteractive:false
D/PMS     (  906): nativeSetInteractive:false done
D/PMS     (  906): nativeSetAutoSuspend:true
D/PMS     (  906): nativeSetAutoSuspend:true done
,D/HABCtrl (  906): TPE algorithm. remove timeout.
,D/PMS     (  906): OOBE c monitor 11
,I/InputManager(  906): Cancel all due to getting PMS screen off broadcast
,I/InputMethodManagerService(  906): screenObserver, isScreenOn=false
,I/IntentController( 1119): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/NfcService( 1255): ScreenObserver: OFF
V/KeyguardServiceDelegate(  906): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43fa7180)
,D/NfcService( 1255): applyRouting - 0
W/ResourceType( 4389): No package identifier when getting name for resource number 0x00000064
V/KeyguardServiceDelegate(  906): **** SHOWN CALLED ****
,I/InputMethodManager( 4389): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41aad3d8 VFEDH.C. .F...... 0,0-720,1134 #64}
I/InputMethodManagerService(  906): Disable input method client, pid=4389
D/PMN     (  906): wakingUp
I/WindowManager(  906): No lock screen! windowToken=null
,D/PMS     (  906): acquireWL(43fd9460): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1255 1027 null
,D/NfcService( 1255): applyRouting -2
D/PMS     (  906): releaseWL(43fd9460): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/PMN     (  906): onScreenOn
,D/PMS     (  906): acquireWL(440718e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/WirelessDisplayService(  906): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  906): releaseWL(440718e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/MtpService( 1999): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 1999): [MTP][onReceive]-
,D/HtcPowerSaver(  906): updateBatteryInfo
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NfcService( 1255): applyRouting - 0
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/AutoSetting( 1418): receiver - intent: android.intent.action.USER_PRESENT
,D/NfcService( 1255): applyRouting -2
D/PMS     (  906): acquireWL(43c57ab0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1255 1027 null
D/AlarmManager(  906): ACTION_SCREEN_ON
I/AlarmManager(  906): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done recovering
I/AlarmManager(  906): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  906): releaseWL(43c57ab0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PowerUI ( 1119): closing low battery warning: level=97
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 97, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/ActivityManager(  906): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4603 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/ClockThread( 1119): stop update clock
,D/AutoSetting( 1418): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  906): BroadcastReceiver::onReceive+
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
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
I/HtcPowerSaver(  906): updateStatus (8000,97,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20119 delay=15s
,D/TetherSettings( 4166): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4166): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4166): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4166): Cust_ConnectToPC   : spcsc>false
D/        ( 4166): Cust_ConnectToPC   : IPT>true
,D/        ( 4166): Cust_ConnectToPC   : Singel_USB>false
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1158): SET_SCREEN_ON:On
I/wpa_supplicant( 1158): htc_wext_set_keepalive +
I/wpa_supplicant( 1158): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1158): getPrivFuncNum +	
I/wpa_supplicant( 1158): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1158): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1158): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1158): htc_wext_set_TX_TRACKING (1)+
,I/wpa_supplicant( 1158): htc_wext_set_TX_TRACKING - ret = 0
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
D/WifiNative-wlan0(  906):    returned true
I/BatteryController( 1119): status:2 level:97 unsupport:false plugged:true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,W/Settings( 4166): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 4166): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4166): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4166): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 4166): onReceive:android.intent.action.USER_PRESENT
D/WIFI_ICON( 1119): WifiActivity: 0
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
V/NotificationService(  906): batLight: plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c80000
D/qdlights(  906): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,W/ContextImpl( 4166): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
V/SRS_Proc(  373): ParamSet string: screen_state=on
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
I/SmartNS_PSService( 4166): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4166): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 4166):  defaultType:0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiStateMachine(  906): BroadcastRSSIForIMS, newrssi =-54 , oldRssi= -200
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1158): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
I/MultiDex( 4603): install
,I/MultiDex( 4603): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4603): loading existing secondary dex files
D/WIFI_ICON( 1119): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/NetworkPolicy(  906): updateScreenOn: false
I/MultiDex( 4603): load found 1 secondary dex files
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
I/MultiDex( 4603): install done
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
,I/jxcore-log( 4389): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 4389): 
I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4620 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ProviderInstaller( 4603): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1801): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1801): onScreenOn: 1450287767093
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1801): onScreenOn: 1450287767093
D/PMS     (  906): acquireWL(4346fd88): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1443 10028 null
D/PMS     (  906): releaseWL(4346fd88): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
W/ContextImpl( 4620): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@422e69a0
,W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@422e69a0, eanble = 0, strlen(mName) = 91
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  906): Listener[0] = com.htc.smartdim.sensor_eye@41ca7e48
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  906): goingToSleep
D/PMS     (  906): acquireWL(43bc61c0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 906 1000 null
,D/PMS     (  906): acquireWL(433313b8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4620 1000 null
,D/SmartSyncUtils( 4620): isEpsOn(), nState = 0
,D/PMS     (  906): releaseWL(433313b8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/AlarmManager(  906): ACTION_SCREEN_OFF
I/AlarmManager(  906): [AlarmQueuing] screen off now: 
I/AlarmManager(  906): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_OFF,
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=20119 mDataStallAlarmIntent=PendingIntent{4232c308: PendingIntentRecord{4242d618 android broadcastIntent}}
I/AlarmManager(  906): [AlarmQueuing] wifi connection: true
D/PMS     (  906): releaseWL(43bc61c0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 0
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
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
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(43b04980): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 906 1000 null
,V/SRS_Proc(  373): ParamSet string: screen_state=off
,D/SmartSyncUtils( 4620): getMobilePolicyEnabled, result = true
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 ,
,D/Process (  906): killProcessQuiet, pid=4250
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/GCM     ( 1370): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  906): Killing 4250:com.google.android.partnersetup/u0a31 (adj 15): empty #17
D/NetworkPolicy(  906): updateScreenOn: false
,D/ContactMessageStore( 1245): start background delete task...
,D/wpa_supplicant( 1158): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  906):    returned true
D/ContactMessageStore( 1245): size: 0 , 0
,D/ContactMessageStore( 1245): Background delete complete
,D/PMS     (  906): releaseWL(43b04980): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
,D/SmartSyncUtils( 4620): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4620): getMobilePolicyEnabled, result = true
W/ContextImpl( 4620): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/WifiService(  906): New client listening to asynchronous messages
D/SmartSyncUtils( 4620): isEpsOn(), nState = 0
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1566): [EventService] getTotalRam: 1873 Mb
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1801): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1801): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1801): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1801): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1801): onScreenOff
D/PMS     (  906): acquireWL(43aae938): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1443 10028 null
,D/PMS     (  906): releaseWL(43aae938): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/AutoSetting( 1418): service - mHandler: cancel location update
D/AutoSetting( 1418): service -           changes count: 0
,I/ActivityManager(  906): Recipient 4250
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41ca7e48
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 1
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41ca7e48, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 0
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41ca7e48, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41ca7e48
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
E/ActivityThread(  906): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@41ff8fc0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@41ff8fc0 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/PMS     (  906): releaseWL(434ff490): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  906): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: true
,V/Tethering(  906): bSetPropertyMultiRAB:false
,D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,D/CaptivePortalTracker(  906): NoActiveNetworkState
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,I/ConnectivityHelper( 1270): [onReceive] WIFI(1): CONNECTED
,I/NetworkMonitor( 3890): type=WIFI subType= reason=null isConnected=true
I/Tethering(  906): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  906): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  906): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  906): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  906): Found interface wlan0
,D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/PMS     (  906): acquireWL(43f8fc68): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1270/10075)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1443/10028)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3890/10154)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4280/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1872/1000)
I/acms    ( 1872): Checking Certificates
I/acms    ( 1872): Checking Developer Certificates
I/acms    ( 1872): Checking Application Certificates
I/acms    ( 1872): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
,I/acms    ( 1872): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1872): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1872): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1872): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1872): Updating next query delay: 75600000
,I/mlserverapp( 1872): MirrorLink is never connected, don't setup ACMS programed checks
,I/mlserverapp( 1872): cancelACMSProgrammedChecks
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.musicenhancer (3912/10051)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1834/10178)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4488/10078)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(435ba280): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4280/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  906): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(435ba280): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  906): releaseWL(43f8fc68): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1999/10021)
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(43034e18): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2226 10028 null
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(43034e18): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1370): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10028)
D/libc    ( 1370): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1370): [NET] getaddrinfo-,err=8
D/libc    ( 1370): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1370): [NET] getaddrinfo-, 1
,D/libc    ( 1370): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =2067 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2226/10028)
D/PMS     (  906): acquireWL(42cdb460): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1370 10028 null
,D/AutoSetting( 1418): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4488): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4488): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1418): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1418): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 1418): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1418): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1418/10053)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1418/10053)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4522/10151)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (4603/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4143/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4143/10160)
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 209
D/libc    (  364): [NET]res_nsend:resplen=79
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1370): [NET] getaddrinfo_proxy-, success
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1834/10178)
,I/dalvikvm-heap( 4143): Grow heap (frag case) to 13.516MB for 1821008-byte allocation
,W/fb4a(:<default>):UserScope( 4460): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4460): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [1][0][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/libc    ( 1370): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1370): [NET] getaddrinfo-,err=8
,I/Adreno-EGL( 4603): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4603): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4603): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4603): Local Branch: 
I/Adreno-EGL( 4603): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4603): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4603):                  aa63bbd948f41d15fc72f585e
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10028)
,D/PMS     (  906): acquireWL(4405aad0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10028 null
,D/PMS     (  906): releaseWL(4405aad0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/Settings( 4603): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/fb4a(:<default>):LocalFbBroadcastManager( 4460): Called registerBroadcastReceiver twice.
,D/GCM     ( 1370): Connected
,D/PMS     (  906): acquireWL(440538e8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1370 10028 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10028)
D/PMS     (  906): releaseWL(42cdb460): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1370/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10028)
D/PMS     (  906): releaseWL(440538e8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  906): acquireWL(440028f0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1370 10028 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10028)
,D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1370/10028)
,D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/GCM     ( 1370): Message class mpf
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1370/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10028)
D/PMS     (  906): releaseWL(440028f0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  906): acquireWL(43fd7d78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10028 null
D/PMS     (  906): releaseWL(43fd7d78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4460/10026)
,D/PMS     (  906): releaseWL(4424d888): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4603): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4603): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4603): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4603): Local Branch: 
I/Adreno-EGL( 4603): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4603): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4603):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4603): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4603): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4603): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4603): Local Branch: 
I/Adreno-EGL( 4603): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4603): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4603):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [5][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
,I/CheckinTask( 2226): Sending checkin request (9007 bytes)
D/libc    ( 2226): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2226): [NET] getaddrinfo-,err=8
D/libc    ( 2226): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2226): [NET] getaddrinfo-, 1
D/libc    ( 2226): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =f42e +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 38
D/libc    (  364): [NET]res_nsend:resplen=84
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2226): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2226): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2226): [NET] getaddrinfo-,err=8
,D/PMS     (  906): acquireWL(43aa2b38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10028 null
,D/PMS     (  906): releaseWL(43aa2b38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (2226/10028)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (2226/10028)
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=5 [17][1][0]
,W/GLSUser ( 1370): GoogleAccountDataService.getToken()
,W/GLSActivity( 1370): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1370): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1370): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/CheckinRequestBuilder( 2226): awaiting user notification for token
,D/DotMatrix( 1566): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1119): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41bf2718 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
,I/RemoteViews.Performance( 1119): com.google.android.gms 1 12 3 12
D/libc    (  364): [NET] +++++ res_nsend xid =460c +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,I/CheckinTask( 2226): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2226): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2226/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2226/10028)
,D/GCM     ( 1370): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  906): releaseWL(43735e08): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 2226): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41b55578 that was originally bound here
E/ActivityThread( 2226): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41b55578 that was originally bound here
E/ActivityThread( 2226): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2226): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2226): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2226): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2226): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2226): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2226): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2226): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2226): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2226): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2226): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2226): 	at bks.a(SourceFile:298)
E/ActivityThread( 2226): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2226): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2226): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2226): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1370): GCM config loaded
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
D/WifiWatchdogStateMachine(  906): Find DNS Address www.htc.com/23.59.123.86
,I/GAV2    ( 4522): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  906): acquireWL(44057b68): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1443 10028 null
,D/PMS     (  906): acquireWL(4387cc60): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1443 10028 null
D/WifiStateMachine(  906): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
D/PMS     (  906): releaseWL(44057b68): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/PMS     (  906): releaseWL(4387cc60): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/AutoSetting( 1511): service - handleMessage() stop self
,D/AutoSetting( 1511): service - onDestroy() END
,D/AutoSetting( 1511): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=4280
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4280:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4280
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  906): killProcessQuiet, pid=4303
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4303:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4303
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  906): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{44035f00 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  906): acquireWL(42362758): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
V/AlarmManager(  906): sending alarm PendingIntent{41bf3388: PendingIntentRecord{41bbc798 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=124652, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42362758): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4203f198): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/BatteryService(  906): n_update end
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(4203f198): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1119): closing low battery warning: level=97
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 97, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,97,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:2 level:97 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(437d0208): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{424699c8: PendingIntentRecord{4246c3d8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141578, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{421244c0: PendingIntentRecord{424a1b68 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141908, Int=0
,D/GpsLocationProvider(  906): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  906): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  906): acquireWL(425486d0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10028)
D/PMS     (  906): releaseWL(437d0208): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
D/PMS     (  906): acquireWL(4248ae40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10028 null
,D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =3008 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/PMS     (  906): releaseWL(4248ae40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/AutoSetting( 1418): service - mHandler: update timezone
,D/AutoSetting( 1418): service - handleMessage() stop self
,D/AutoSetting( 1418): service - handleMessage() quit looper
D/AutoSetting( 1511): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1418): service - onDestroy() END
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/Process (  906): killProcessQuiet, pid=3912
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3912:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,D/AutoSetting( 1511): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1511): service - onCreate()
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
I/ActivityManager(  906): Recipient 3912
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1511): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1511): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
V/NotificationService(  906): batLight: plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c80000
D/qdlights(  906): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
,D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/DotMatrix( 1566): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1511): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1511): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1511): service - mHandler: update timezone
,D/AutoSetting( 1511): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1511): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1511): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1511): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1566): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1119): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41e2d5a8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1119): com.htc.htclocationservice 2 6 2 11
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  364): [NET]res_nsend:resplen=238
D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
I/global  (  906): call createSocket() return a new socket.
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  906): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  906): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  906): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  906):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  906): releaseWL(425486d0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{435c7b60 u0 com.htc.htclocationservice/.AutoSettingService}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(43fd91b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): releaseWL(43fd91b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1119): closing low battery warning: level=98
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:2 level:98 unsupport:false plugged:true
,D/AutoSetting( 1511): service - handleMessage() stop self
,D/AutoSetting( 1511): service - onDestroy() END
,D/AutoSetting( 1511): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=4267
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4267:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4267
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TelephonyReceiver( 1245): switchBindHtcMsgCursor: null
,D/PMS     (  906): acquireWL(422b1118): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bf3388: PendingIntentRecord{41bbc798 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=184652, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(422b1118): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42f41358): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42f41358): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(43fbf190): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{42244088: PendingIntentRecord{4323fdf0 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=229738, Int=0
,I/ActivityManager(  906): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4678 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  906): sending alarm PendingIntent{42554a50: PendingIntentRecord{42457558 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1450287876107, Int=10800000
,D/PMS     (  906): releaseWL(43fbf190): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.aurora (4678/10047)
,D/Process (  906): killProcessQuiet, pid=4321
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4321:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4321
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(4360b838): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{42befda0: PendingIntentRecord{4303a168 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=231523, Int=120000
,V/AlarmManager(  906): sending alarm PendingIntent{4245a9d8: PendingIntentRecord{4323fdf0 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=231786, Int=0
,D/PMS     (  906): releaseWL(4360b838): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2226/10028)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(43f0a880): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bf3388: PendingIntentRecord{41bbc798 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=244652, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): releaseWL(43f0a880): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4257fc18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4257fc18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(43868090): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bf3388: PendingIntentRecord{41bbc798 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=304652, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43868090): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(42595198): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42595198): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(434911b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(434911b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1119): closing low battery warning: level=98
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:2 level:98 unsupport:false plugged:true
,I/jxcore-log( 4389): Connected to the server!
I/jxcore-log( 4389): 
,I/chromium( 4389): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(4404d2f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bf3388: PendingIntentRecord{41bbc798 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=364653, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4404d2f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/GLSUser ( 1370): GoogleAccountDataService.getToken()
,W/GLSActivity( 1370): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1370): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1370): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSActivity( 1370): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1370): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1370): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1370): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1370): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1370): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1370): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1370): 	at dalvik.system.NativeStart.run(Native Method)
,D/DotMatrix( 1566): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,I/RemoteViews( 1119): com.google.android.gms (false,0)
,D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41e236e8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/PlayEventLogger( 4108): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4108): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4108): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4108): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4108): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4108): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4108): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4108): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews.Performance( 1119): com.google.android.gms 3 11 4 12
,D/libc    ( 4108): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4108): [NET] getaddrinfo-,err=8
D/libc    ( 4108): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4108): [NET] getaddrinfo-, 1
,D/libc    ( 4108): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =e1e9 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 33
D/libc    (  364): [NET]res_nsend:resplen=87
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4108): [NET] getaddrinfo_proxy-, success
I/global  ( 4108): call createSocket() return a new socket.
D/libc    ( 4108): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4108): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4108): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4108): [NET] getaddrinfo-,err=8
,D/PMS     (  906): acquireWL(430149b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(430149b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 4389): --- start :testFindPeers.js---
I/jxcore-log( 4389): 
,I/jxcore-log( 4389): testFindPeers created [object Object]
I/jxcore-log( 4389): 
,I/jxcore-log( 4389): serverPort is 8876
I/jxcore-log( 4389): 
W/dalvikvm( 4389): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4389): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4389): threadid=1: thread exiting with uncaught exception (group=0x4166fe30)
E/AndroidRuntime( 4389): FATAL EXCEPTION: main
E/AndroidRuntime( 4389): Process: com.test.thalitest, PID: 4389
E/AndroidRuntime( 4389): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4389): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:134)
E/AndroidRuntime( 4389): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:133)
E/AndroidRuntime( 4389): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:183)
E/AndroidRuntime( 4389): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:95)
E/AndroidRuntime( 4389): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:92)
E/AndroidRuntime( 4389): 	at io.jxcore.node.JXcoreExtension$5.Receiver(JXcoreExtension.java:155)
E/AndroidRuntime( 4389): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4389): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4389): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4389): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4389): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4389): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4389): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4389): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4389): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4389): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4389): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4389): 	at dalvik.system.NativeStart.main(Native Method)
,E/ActivityManager(  906): App crashed! Process: com.test.thalitest
W/ActivityManager(  906):   Force finishing activity com.test.thalitest/.MainActivity
,D/Process (  906): killProcessQuiet, pid=4337,
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
,I/ActivityManager(  906): Killing 4337:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process ( 4389): killProcess, pid=4389
D/Process ( 4389): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,W/InputDispatcher(  906): channel '423b7e68 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  906): channel '423b7e68 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  906): Attempted to unregister already unregistered input channel '423b7e68 com.test.thalitest.MainActivity (s)'
I/WindowManager(  906): WINDOW DIED Window{423b7e68 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager(  906): Recipient 4389
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.test.thalitest (pid 4389) has died.
D/WifiService(  906): Client connection lost with reason: 4
W/WindowManager(  906): Failed looking up window
W/WindowManager(  906): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@42325e40 does not exist
W/WindowManager(  906): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8463)
W/WindowManager(  906): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8454)
W/WindowManager(  906): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1052)
W/WindowManager(  906): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/WindowManager(  906): 	at dalvik.system.NativeStart.run(Native Method)
I/WindowState(  906): WIN DEATH: null
,I/ActivityManager(  906): Recipient 4337
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/InputMethodManagerService(  906): Got RemoteException sending setActive(false) notification to pid 4389 uid 10348
,W/Binder  ( 1210): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1210): java.lang.NullPointerException
W/Binder  ( 1210): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1210): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1210): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1210): 	at dalvik.system.NativeStart.run(Native Method)
,D/PMS     (  906): acquireWL(43afdbd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43afdbd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1119): closing low battery warning: level=99
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:2 level:99 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(4239cb28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bf3388: PendingIntentRecord{41bbc798 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=424652, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4239cb28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42359678): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42359678): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
D/PowerUI ( 1119): closing low battery warning: level=99
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:2 level:99 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(41f9cb68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bf3388: PendingIntentRecord{41bbc798 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=484652, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(41f9cb68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42487f40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42487f40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=99
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:2 level:99 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(430409f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{43570fc0: PendingIntentRecord{4303a168 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=531793, Int=300000
,D/PMS     (  906): releaseWL(430409f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(43fdfea0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bf3388: PendingIntentRecord{41bbc798 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=544652, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43fdfea0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43f66f70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43f66f70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42e850f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
V/NotificationService(  906): batLight: Full, plugged
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,V/LightsService(  906): setLight #8: color=#c8c800
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HeadsetPhoneState( 1589): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/HtcPowerSaver(  906): updateBatteryInfo
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/PMS     (  906): releaseWL(42e850f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1566): [EventService] reorderNotification, total:0
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/ContextImpl( 4620): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
D/TetherSettings( 4166): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4166): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4166): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4166): Cust_ConnectToPC   : spcsc>false
D/        ( 4166): Cust_ConnectToPC   : IPT>true
D/        ( 4166): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 4166): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4166): Index of the first 1 = -1
W/ContextImpl( 4166): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 4166): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 4166): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4166): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4166): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
W/ContextImpl( 4166): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,D/SmartNS_Utility( 4166): [ACC]android_networking:tethering_guard_support=false
,D/PMS     (  906): acquireWL(43f90828): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bf3388: PendingIntentRecord{41bbc798 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=604652, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43f90828): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(430a0958): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(430a0958): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  350): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1245): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1245): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1245): sku_id=99
D/ContactMessageStore( 1245): start background delete task...
,D/ContactMessageStore( 1245): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1245): size: 0 , 0
,D/ContactMessageStore( 1245): Background delete complete
,D/PMS     (  906): acquireWL(43ef7368): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bf3388: PendingIntentRecord{41bbc798 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=664652, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43ef7368): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43fd53f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43fd53f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42595888): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42595888): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42b34700): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{41bf3388: PendingIntentRecord{41bbc798 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=724652, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42b34700): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43b1da30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43b1da30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4341b468): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bf3388: PendingIntentRecord{41bbc798 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=784652, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4341b468): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43c0cfd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43c0cfd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(421257e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bf3388: PendingIntentRecord{41bbc798 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=844652, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(421257e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(433d0180): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(433d0180): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43c291d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bf3388: PendingIntentRecord{41bbc798 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=904653, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43c291d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(438f0780): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(438f0780): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(428df578): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
V/AlarmManager(  906): sending alarm PendingIntent{41d46e28: PendingIntentRecord{423d71d0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=785548, Int=0
V/AlarmManager(  906): sending alarm PendingIntent{4303ee30: PendingIntentRecord{422dd788 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450288092442, Int=1800000
,V/AlarmManager(  906): sending alarm PendingIntent{421441a0: PendingIntentRecord{4213c3b0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450288596444, Int=900000
,D/PMS     (  906): acquireWL(43fbe550): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2226 10028 null
,D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,W/ContextImpl( 4620): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  906): acquireWL(42a43ae8): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2226 10028 null
,I/EventLogService( 2226): Aggregate from 1450287766383 (log), 1450286292308 (data)
D/PMS     (  906): releaseWL(43fbe550): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,D/PowerUsageService( 4620): call getInstance()
,D/PowerUsageList:PowerUsageHelper( 4620): MY_DEBUG = false
D/PMS     (  906): releaseWL(428df578): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): releaseWL(42a43ae8): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): acquireWL(435961c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bf3388: PendingIntentRecord{41bbc798 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=964652, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(435961c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43584258): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43584258): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43541df0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/SmartSyncUtils( 4620): isEpsOn(), nState = 0
V/AlarmManager(  906): sending alarm PendingIntent{42136ae0: PendingIntentRecord{43b47620 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450288667218, Int=0
,D/SmartSyncScreenOnOffTimeReceiver( 4620): [updateNmRange] bManual = false
D/PMS     (  906): acquireWL(434d73e0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4620 1000 null
,D/PMS     (  906): releaseWL(43541df0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/SmartSyncScreenOnOffTimeReceiver( 4620): [updateNmRange] USERNIGHT_TIMESTART = 18, USERNIGHT_TIMEEND = 23, nStart = 18, nEnd = 23, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 4620): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4620): SettingOnTime = 1450303200000, randomSettingOnTime = 1450300626000
D/SmartSyncScreenOnOffTimeReceiver( 4620): SettingOffTime = 1450371600000, randomSettingOffTime = 1450378003000
D/SmartSyncScreenOnOffTimeReceiver( 4620): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4620): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 4620): bNightModeTurnOffOnce = false
,D/PMS     (  906): acquireWL(4349f2b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41dffec8: PendingIntentRecord{43fc6e60 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_OFF_NETWORK_BY_CHECK, t=0, cnt=1, w=1450288667244, Int=0
,W/ContextImpl( 4620): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  906): releaseWL(434d73e0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4620): getMobilePolicyEnabled, result = true
,D/SmartSyncDataLinkTurnOffService( 4620): turnOffMobile bPolicyEnabled = true
,D/WifiStateMachine(  906): WiFiDisplay: getWifidisplayApEnabled=false
,D/SmartSyncUtils( 4620): isWifiHotSpotEnabled = false
,D/SmartSyncDataLinkTurnOffService( 4620): turnOffMobile bCheckMobileData = false
D/LocationManagerService(  906): getProviders()=[gps, network]
,D/LocationManagerService(  906): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
,D/LocationManagerService(  906): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/PMS     (  906): releaseWL(4349f2b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/SmartSyncDataLinkTurnOffService( 4620): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
D/SmartSyncUtils( 4620): isCharging status = 5
,D/SmartSyncDataLinkTurnOffService( 4620): turnOffWifi ui setting = true
,D/WifiStateMachine(  906): WiFiDisplay: getWifidisplayApEnabled=false
,D/SmartSyncUtils( 4620): isWifiHotSpotEnabled = false
D/SmartSyncUtils( 4620): isWifiCallingOn, bOn = false
,D/SmartSyncDataLinkTurnOffService( 4620): turnOffWifi bCheckWifiData = true
,D/SmartSyncDataLinkTurnOffService( 4620): turnOffWifi bWifiConnected = true
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.htcpowermanager (4620/1000)
,D/PMS     (  906): acquireWL(433f1560): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10028}
V/AlarmManager(  906): sending alarm PendingIntent{430e9378: PendingIntentRecord{424a3460 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1012428, Int=0
,D/PMS     (  906): acquireWL(43271348): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1370 10028 null
,D/PMS     (  906): releaseWL(43271348): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,D/PMS     (  906): acquireWL(430ef510): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10028 null
,D/PMS     (  906): releaseWL(433f1560): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  906): releaseWL(430ef510): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  906): acquireWL(430adf88): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1370 10028 null
,D/GCM     ( 1370): Message class mow
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1370/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1370/10028)
,D/PMS     (  906): releaseWL(430adf88): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  906): acquireWL(42cb7428): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1370 10028 null
,D/PMS     (  906): releaseWL(42cb7428): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=7 [209][16][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(425cb2a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bf3388: PendingIntentRecord{41bbc798 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1024652, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(425cb2a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(425ac430): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(425ac430): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4256f070): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{41bf3388: PendingIntentRecord{41bbc798 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1084652, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4256f070): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42552280): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42552280): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42502850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{41bf3388: PendingIntentRecord{41bbc798 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1144653, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42502850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42492098): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42492098): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4242a910): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41de8288: PendingIntentRecord{43fdd520 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_OFF_WIFI_RETRY, t=0, cnt=1, w=1450288847311, Int=0
,W/ContextImpl( 4620): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  906): releaseWL(4242a910): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/SmartSyncDataLinkTurnOffService( 4620): turnOffWifi ui setting = true
,D/WifiStateMachine(  906): WiFiDisplay: getWifidisplayApEnabled=false
D/SmartSyncUtils( 4620): isWifiHotSpotEnabled = false
,D/SmartSyncUtils( 4620): isWifiCallingOn, bOn = false
,D/SmartSyncDataLinkTurnOffService( 4620): turnOffWifi bCheckWifiData = false
,D/SmartSyncDataLinkTurnOffService( 4620): turnOffWifi bWifiConnected = true
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.htcpowermanager (4620/1000)
D/LocationManagerService(  906): getProviders()=[gps, network]
D/LocationManagerService(  906): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
D/LocationManagerService(  906): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/SmartSyncDataLinkTurnOffService( 4620): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
D/SmartSyncUtils( 4620): isCharging status = 5
,D/PMS     (  906): acquireWL(42021888): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bf3388: PendingIntentRecord{41bbc798 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1204652, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42021888): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4233da28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4233da28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  350): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(41e9cfd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bf3388: PendingIntentRecord{41bbc798 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1264652, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(41e9cfd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(422b5560): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(422b5560): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(420e5658): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{41bf3388: PendingIntentRecord{41bbc798 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1324652, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(420e5658): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(41d74288): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(41d74288): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(423f2e68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bf3388: PendingIntentRecord{41bbc798 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1384652, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(423f2e68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(422ef130): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(422ef130): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(41fdcd50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bf3388: PendingIntentRecord{41bbc798 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1444653, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(41fdcd50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(44041050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(44041050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4358f8a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{41bf3388: PendingIntentRecord{41bbc798 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1504652, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4358f8a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(425948c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(425948c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(423b2560): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bf3388: PendingIntentRecord{41bbc798 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1564652, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(423b2560): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(41cb8f38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(41cb8f38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43fb2390): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{41bf3388: PendingIntentRecord{41bbc798 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1624653, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43fb2390): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42f3f618): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42f3f618): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42590850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bf3388: PendingIntentRecord{41bbc798 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1684652, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42590850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(423808e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(423808e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(420edbf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{41bf3388: PendingIntentRecord{41bbc798 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1744652, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(420edbf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43c23400): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43c23400): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43589c70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43589c70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): acquireWL(429454f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41bf3388: PendingIntentRecord{41bbc798 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1804653, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(429454f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(44010e58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(44010e58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  350): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(425e0378): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{41bf3388: PendingIntentRecord{41bbc798 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1864652, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
I/ProcessStatsService(  906): Prepared write state in 28ms
,D/PMS     (  906): releaseWL(425e0378): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  906): Pruning old procstats: /data/system/procstats/state-2015-12-16-04-01-37.bin
,D/PMS     (  906): acquireWL(42575a30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42575a30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1119): closing low battery warning: level=100
D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4739): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4739): ====startRecUseTime====
D/htc.customization.log.level( 4739):  is 
W/CustomizationLogLevel( 4739): Level value is invalid, use default level 2
D/CustomizationManager( 4739):  Read ACC file spent 0.109 (s)
D/CIDMapFileReader( 4739): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4739): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4739): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4739): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4739): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4739): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4739): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4739): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4739): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4739): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4739): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4739): Parsing tag category name = system
I/CustomizationCIDLoader( 4739): Parsing tag category name = application
I/CustomizationCIDLoader( 4739): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4739): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4739): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4739): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4739): Parsing tag category name = Settings
D/CustomizationManager( 4739):  Read CID file spent 0.166 (s)
D/CustomizationManager( 4739):  All configurations done spent 0.166 (s)
W/HtcNativeFlag( 4739): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4739): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4739): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4739): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  906): deletePackageAsUser: pkg=com.test.thalitest, pid=4739, uid=2000 user=0
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
D/Process (  906): killProcessQuiet, pid=4505
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=4488
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=1418
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=3890
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  906): Killing 4505:com.android.chrome/u0a96 (adj 15): empty for 1801s
I/ActivityManager(  906): Killing 4488:com.google.android.setupwizard/u0a78 (adj 15): empty for 1801s
I/ActivityManager(  906): Killing 1418:com.htc.sense.hsp/u0a53 (adj 15): empty for 1801s
I/ActivityManager(  906): Killing 3890:com.google.android.music:main/u0a154 (adj 15): empty for 1801s
D/Process (  906): killProcessQuiet, pid=4437
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=4108
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=4352
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  906): Killing 4437:com.htc.mms.backupagent/u0a77 (adj 15): empty for 1809s
I/ActivityManager(  906): Killing 4108:com.android.vending/u0a73 (adj 15): empty for 1824s
I/ActivityManager(  906): Killing 4352:com.android.settings:remote/1000 (adj 15): empty for 1837s
I/ActivityManager(  906): Recipient 4437
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/asset   (  906): Copying FileAsset 0x6ee65da0 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  906): Recipient 4505
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 1418
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3890
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  906): Client com.google.android.music (pid 3890): Died!
I/ActivityManager(  906): Recipient 4488
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/PackageSettings(  906): Skipping PackageSetting{422393d8 com.example.hello/10356} due to missing metadata
I/ActivityManager(  906): Recipient 4352
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4108
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
I/dalvikvm-heap( 4143): Grow heap (frag case) to 15.216MB for 1821008-byte allocation
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1566): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
I/acms    ( 1872): Unregistering com.test.thalitest
D/DotMatrix( 1566): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
E/acms    ( 1872): Could not unregister removed application com.test.thalitest
D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver replacing:false
D/PMS     (  906): acquireWL(42ccd190): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1443 10028 null
W/GeofencerStateMachine( 1443): Ignoring removeGeofence because network location is disabled.
W/AccTypeManager( 1341): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1341): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  906): releaseWL(42ccd190): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/VoicemailCleanupService( 1299): Cleaning up data for package: com.test.thalitest
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/Launcher( 1270): Deferring update until onResume
D/Launcher( 1270): waitUntilResume // bindAppsRemoved
D/AccTypeManager( 1341): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
D/PackageBroadcastService( 2226): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
W/SystemReader( 1255): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/ActivityManager(  906): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/ActivityManager(  906): Delaying start of: ServiceRecord{43599df0 u0 com.google.android.gms/.wearable.service.WearableControlService}
E/ExternalAccountType( 1341): Unsupported attribute readOnly
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PeopleContactsSync( 2226): CP2 sync disabled
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2226, uid=10028, userID:0
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
D/PMS     (  906): acquireWL(43fbcf18): PARTIAL_WAKE_LOCK  Icing 0x1 2226 10028 null
I/Icing   ( 2226): doRemovePackageData com.test.thalitest
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/ActivityManager(  906): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4757 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
D/PhoneApp( 1245): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  906): releaseWL(43fbcf18): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4769 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/MultiDex( 4757): install
I/MultiDex( 4757): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4769): install
I/MultiDex( 4769): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4757): loading existing secondary dex files
I/MultiDex( 4757): load found 1 secondary dex files
I/MultiDex( 4757): install done
I/MultiDex( 4769): loading existing secondary dex files
I/MultiDex( 4769): load found 1 secondary dex files
I/MultiDex( 4769): install done
I/ProviderInstaller( 4757): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ProviderInstaller( 4769): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
D/Process (  906): killProcessQuiet, pid=4522
I/ActivityManager(  906): Killing 4522:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1802s
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Recipient 4522
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Start proc com.htc.sense.hsp for broadcast com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver: pid=4789 uid=10053 gids={50053, 1023, 3003, 5012}
E/SQLiteDatabase( 4769): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4769): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4769): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4769): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4769): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4769): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4769): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4769): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4769): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4769): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4769): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4769): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4769): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4769): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4769): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4769): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4769): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4769): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4769): threadid=12: thread exiting with uncaught exception (group=0x4166fe30)
E/ActivityManager(  906): App crashed! Process: com.google.android.gms.drive
E/AndroidRuntime( 4769): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4769): Process: com.google.android.gms.drive, PID: 4769
E/AndroidRuntime( 4769): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4769): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4769): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4769): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4769): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4769): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4769): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4769): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4769): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4769): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4769): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4769): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4769): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4769): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4769): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4769): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4769): 	at ctn.run(SourceFile:985)
D/Process ( 4769): killProcess, pid=4769
D/Process ( 4769): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
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
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4769
I/ActivityManager(  906): Process com.google.android.gms.drive (pid 4769) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
D/PluginProvider( 4789): PluginProvider onCreate
E/SQLiteDatabase( 4789): Failed to open database '/data/data/com.htc.sense.hsp/databases/registry.db'.
E/SQLiteDatabase( 4789): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4789): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4789): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4789): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4789): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4789): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4789): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4789): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4789): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4789): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4789): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4789): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4789): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4789): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4789): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.onCreate(Unknown Source)
E/SQLiteDatabase( 4789): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1609)
E/SQLiteDatabase( 4789): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1574)
E/SQLiteDatabase( 4789): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5394)
E/SQLiteDatabase( 4789): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4965)
E/SQLiteDatabase( 4789): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4902)
E/SQLiteDatabase( 4789): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4789): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4789): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4789): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4789): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4789): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4789): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4789): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4789): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4789): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4789): Couldn't open registry.db for writing (will try read-only):
E/SQLiteOpenHelper( 4789): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4789): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4789): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4789): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4789): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4789): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4789): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4789): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4789): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4789): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4789): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4789): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4789): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4789): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4789): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.onCreate(Unknown Source)
E/SQLiteOpenHelper( 4789): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1609)
E/SQLiteOpenHelper( 4789): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1574)
E/SQLiteOpenHelper( 4789): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5394)
E/SQLiteOpenHelper( 4789): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4965)
E/SQLiteOpenHelper( 4789): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4902)
E/SQLiteOpenHelper( 4789): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4789): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4789): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4789): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4789): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4789): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4789): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4789): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4789): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4789): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4789): Opened registry.db in read-only mode
D/PluginProvider( 4789): current plugin count: 19
D/HtcAppUPService( 4789): HtcUPDataProvider onCreate()
I/[PluginManager]RegisterService( 4789): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
W/[PluginManager]RegisterService( 4789): provider may killed!
W/[PluginManager]RegisterService( 4789): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/[PluginManager]RegisterService( 4789): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/[PluginManager]RegisterService( 4789): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/[PluginManager]RegisterService( 4789): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/[PluginManager]RegisterService( 4789): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/[PluginManager]RegisterService( 4789): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
W/[PluginManager]RegisterService( 4789): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:818)
W/[PluginManager]RegisterService( 4789): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:213)
W/[PluginManager]RegisterService( 4789): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/[PluginManager]RegisterService( 4789): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
W/[PluginManager]RegisterService( 4789): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/[PluginManager]RegisterService( 4789): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
W/[PluginManager]RegisterService( 4789): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 4789): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 4789): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 4789): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 4789): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/[PluginManager]RegisterService( 4789): handle notify Blinkfeed plugin client changed
I/ActivityManager(  906): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4806 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
D/Process (  906): killProcessQuiet, pid=4143
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4143:com.google.android.apps.plus/u0a160 (adj 15): empty for 1802s
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4143
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4806, uid=10073, userID:0
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1270): loadItems() com.htc.launcher.pageview.WidgetManager@41b32d30 +
I/Prism.WidgetManager( 1270): onLoadItems() +
D/Finsky  ( 4806): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (4806/10073)
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (4806/10073)
D/Finsky  ( 4806): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
D/PMS     (  906): acquireWL(42454938): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{41d46e28: PendingIntentRecord{423d71d0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1661125, Int=0
W/Settings( 4806): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 4806): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SQLiteDatabase( 4806): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 4806): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4806): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4806): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4806): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4806): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4806): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4806): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4806): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4806): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4806): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4806): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4806): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4806): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4806): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4806): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/SQLiteDatabase( 4806): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/SQLiteDatabase( 4806): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/SQLiteDatabase( 4806): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 4806): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 4806): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4806): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4806): threadid=25: thread exiting with uncaught exception (group=0x4166fe30)
E/ActivityManager(  906): App crashed! Process: com.android.vending
E/AndroidRuntime( 4806): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime( 4806): Process: com.android.vending, PID: 4806
E/AndroidRuntime( 4806): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4806): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4806): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4806): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4806): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4806): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4806): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4806): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4806): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4806): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4806): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4806): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4806): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4806): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4806): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/AndroidRuntime( 4806): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/AndroidRuntime( 4806): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/AndroidRuntime( 4806): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4806): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4806): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4806): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4806, uid=10073, userID:0
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
D/Prism.PackageStateRece_( 1270): action: android.intent.action.PACKAGE_REMOVED
D/Process ( 4806): killProcess, pid=4806
D/Process ( 4806): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.finsky.FinskyApp$CrashHandler.uncaughtException:284 java.lang.ThreadGroup.uncaughtException:693 
I/IcingCorporaProvider( 2898): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  906): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4839 uid=10100 gids={50100, 3003, 5012, 1028, 1015}

```
