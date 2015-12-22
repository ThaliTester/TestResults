#### Test 54312298239818e_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1158): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  908):    returned true
,E/cutils-trace( 4348): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4348): ====startRecUseTime====
D/htc.customization.log.level( 4348):  is 
W/CustomizationLogLevel( 4348): Level value is invalid, use default level 2
D/CustomizationManager( 4348):  Read ACC file spent 0.064 (s)
D/CIDMapFileReader( 4348): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4348): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4348): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4348): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4348): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4348): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4348): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4348): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4348): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4348): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4348): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4348): Parsing tag category name = system
I/CustomizationCIDLoader( 4348): Parsing tag category name = application
I/CustomizationCIDLoader( 4348): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4348): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4348): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4348): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4348): Parsing tag category name = Settings
D/CustomizationManager( 4348):  Read CID file spent 0.107 (s)
D/CustomizationManager( 4348):  All configurations done spent 0.107 (s)
W/HtcNativeFlag( 4348): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4348): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4348): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4348): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
W/CpuWake (  908): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  908): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  908): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  908): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  908): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  908): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  908): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4348
D/PMS     (  908): acquireHCC(42191798): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 908 1000 null
D/PMS     (  908): acquireHCC(42046f60): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 908 1000 null
W/asset   (  908): Copying FileAsset 0x62b09d78 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  908): @test_code: getHtcIntentFlag: 0 obj: 1109674744
D/PMS     (  908): acquireWL(41f20108): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 908 1000 null
I/FeedHostManager( 1270): [onPause]
I/FeedProviderManager( 1270): onPause
I/FeedHostManager( 1270): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@42258a18
I/SocialFeedProvider( 1270): +onPause
I/SocialFeedProvider( 1270): -onPause
I/ActivityManager(  908): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4359 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1270): [trimMemory] 20
W/asset   ( 4359): Copying FileAsset 0x5c6ed428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4359): Binding Chromium to main looper Looper (main, tid 1) {41a67760}
I/LibraryLoader( 4359): Expected native library version number "",actual native library version number ""
I/chromium( 4359): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4359): Initializing chromium process, renderers=0
W/System.err(  908): java.lang.Throwable: stack dump
D/BluetoothManagerService(  908): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  908): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42310668:true
W/System.err(  908): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  908): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  908): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  908): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  908): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4359): 1101533320: getState(). Returning 12
D/PMS     (  908): acquireWL(42414860): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
D/PMS     (  908): acquireWL(42333438): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
D/PMS     (  908): releaseWL(42414860): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4359): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4359): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4359): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4359): Local Branch: 
I/Adreno-EGL( 4359): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4359): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4359):                  aa63bbd948f41d15fc72f585e
W/chromium( 4359): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4359): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4359): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4359): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4359): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4359): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4359): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4359): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4359): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4359): CordovaWebView is running on device made by: HTC
,W/AwContents( 4359): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  908): Disable input method client, pid=1270
,W/ResourceType( 4359): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4359): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41ab2738, mServedView=org.apache.cordova.engine.SystemWebView{41a783a0 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/ActivityManager(  908): Displayed com.test.thalitest/.MainActivity: +291ms
W/XT9_C   ( 1209): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1209): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,W/AwContents( 4359): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  908): Enable input method client, pid=4359
D/PMS     (  908): releaseWL(41f20108): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/PMS     (  908): acquireWL(41a82050): PARTIAL_WAKE_LOCK  Icing 0x1 2250 10028 null
,D/PMS     (  908): releaseWL(41a82050): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  908): acquireWL(4247bd80): PARTIAL_WAKE_LOCK  Icing 0x1 2250 10028 null
,D/PMS     (  908): releaseWL(4247bd80): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  908): acquireWL(423018d8): PARTIAL_WAKE_LOCK  Icing 0x1 2250 10028 null
,D/PMS     (  908): releaseWL(423018d8): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/JsMessageQueue( 4359): Set native->JS mode to OnlineEventsBridgeMode
D/PMS     (  908): acquireWL(43141d88): PARTIAL_WAKE_LOCK  Icing 0x1 2250 10028 null
,D/PMS     (  908): releaseWL(43141d88): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/jxcore_app_log( 4359): JniHelper::setJavaVM(0x41544048), pthread_self() = 1661968944
,D/JX-Cordova( 4359): jxcore cordova android initializing
,I/dalvikvm-heap( 4359): Grow heap (frag case) to 11.546MB for 96598-byte allocation
,I/dalvikvm-heap( 4359): Grow heap (frag case) to 11.629MB for 144892-byte allocation
,W/PluginManager( 4359): THREAD WARNING: exec() call to JXcore.isReady blocked the main thread for 33ms. Plugin should use CordovaInterface.getThreadPool().
,I/dalvikvm-heap( 4359): Grow heap (frag case) to 11.745MB for 217334-byte allocation
,I/dalvikvm-heap( 4359): Grow heap (frag case) to 11.916MB for 325996-byte allocation
,I/dalvikvm-heap( 4359): Grow heap (frag case) to 12.167MB for 488990-byte allocation
,I/dalvikvm-heap( 4359): Grow heap (frag case) to 13.178MB for 1100216-byte allocation
,I/dalvikvm-heap( 4359): Grow heap (frag case) to 14.045MB for 1650320-byte allocation
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1158): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,I/dalvikvm-heap( 4359): Grow heap (frag case) to 15.435MB for 2475476-byte allocation
,W/CpuWake (  908): >>nativeReleaseCpuPerfWakeLock()
,W/CpuWake (  908): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  908): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  908): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  908): >>release mCpuPerf_Freq wakelock
D/PMS     (  908): releaseHCC(42191798): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,W/CpuWake (  908): <<release mCpuPerf_Freq wakelock
,D/PMS     (  908): releaseHCC(42046f60): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4359): Grow heap (frag case) to 17.444MB for 3713210-byte allocation
,W/jxcore-log( 4359): Initializing JXcore engine
,W/jxcore-log( 4359): JXcore engine is ready
I/ActivityManager(  908): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4407 uid=10077 gids={50077}
D/PMS     (  908): acquireWL(422f0388): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10077}
V/AlarmManager(  908): sending alarm PendingIntent{423a3968: PendingIntentRecord{423b7b98 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1450743025543, Int=60000
D/PMS     (  908): releaseWL(422f0388): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4407): SMSBackupAgentService started
,D/SMSBackup( 4407): Checking restore status
D/SMSBackup( 4407): Restore complete
,D/SMSBackup( 4407): cancelCheckAlarm
,D/SMSBackup( 4407): SMSBackupAgentService completed: completed in 0.0 seconds
,W/jxcore-log( 4359): Starting JXcore engine
,D/Process (  908): killProcessQuiet, pid=3378
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3378:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 3378
,W/jxcore-log( 4359): Platform android
W/jxcore-log( 4359): 
,W/jxcore-log( 4359): Process ARCH arm
W/jxcore-log( 4359): 
,D/PMS     (  908): releaseWL(42333438): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/WIFI_ICON( 1116): WifiActivity: 0
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/jxcore-log( 4359): JXcore Cordova bridge is ready!
I/jxcore-log( 4359): 
,W/jxcore-log( 4359): JXcore engine is started
,I/chromium( 4359): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/WifiDataStallTracker(  908): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  908): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  908): updateDataStallInfo: mDataStallTxRxSum={txSum=43 rxSum=33} preTxRxSum={txSum=42 rxSum=32}
D/WifiDataStallTracker(  908): updateDataStallInfo: IN/OUT
D/PMS     (  908): acquireWL(423cdea0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
V/AlarmManager(  908): sending alarm PendingIntent{423f8920: PendingIntentRecord{42490768 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=105716, Int=0
,D/PMS     (  908): releaseWL(423cdea0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/WifiDataStallTracker(  908): onDataStallAlarm: tag=20206 Sent 0 pkts since last received, < watchdogTrigger=5
D/WifiDataStallTracker(  908): startDataStallAlarm: tag=20207 delay=15s
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/jxcore-log( 4359): Toggling radios to true
I/jxcore-log( 4359): 
,D/BluetoothAdapter( 4359): enable(): BT is already enabled..!
,D/WifiManager( 4359): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
,W/HtcDLNAServiceManager(  908): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  908): Settings:Agentname: wifi_on
,W/HtcDLNAServiceManager(  908): Settings:Agentvalue: 2
W/Settings:Agent(  908): >> traceCallingStack()
W/Settings:Agent(  908): Process.myPid(): 908
,W/Settings:Agent(  908): Process.myTid(): 1730
W/Settings:Agent(  908): Process.myUid(): 1000
W/Settings:Agent(  908): 
,W/Settings:Agent(  908): 
,W/System.err(  908): java.lang.Throwable: stack dump
W/System.err(  908): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  908): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
D/WifiService(  908): setWifiEnabled: true pid=4359, uid=10348
E/WifiService(  908): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  908): isSprintWifiRestricted(): false
D/WifiService(  908): New client listening to asynchronous messages
I/WifiService(  908): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  908): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
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
W/Settings:Agent(  908): << traceCallingStack(): 6(ms)
D/WifiManager( 4359): disconnect: Base Package Name=com.test.thalitest, uid=10348
D/WifiNative-wlan0(  908): doBoolean: DISCONNECT
D/WifiManager( 4359): reconnect: Base Package Name=com.test.thalitest, uid=10348
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1158): TDLS: Tear down peers
I/wpa_supplicant( 1158): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4359): Radios toggled
I/jxcore-log( 4359): 
D/BluetoothManagerService(  908): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4359): Got Device Bluetooth address: 80:01:84:8A:B3:68
I/jxcore-log( 4359): 
I/jxcore-log( 4359): Perf Test app loaded loaded
I/jxcore-log( 4359): 
I/jxcore-log( 4359): check test folder
I/jxcore-log( 4359): 
I/jxcore-log( 4359): found test : ./testFindPeers.js
I/jxcore-log( 4359): 
,I/jxcore-log( 4359): found test : ./testSendData.js
I/jxcore-log( 4359): 
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1158): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1158): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1158): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  908): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  908): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1158): TDLS: Remove peers on disassociation
D/HTCRequest(  908): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  908): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1158): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  908): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  908): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/Tethering(  908): interfaceLinkStateChanged wlan0, false
,D/Tethering(  908): interfaceStatusChanged wlan0, false
D/Tethering(  908): [isWifi] getHotspotEnabled: false
E/wpa_supplicant( 1158): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1158): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1158): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1158): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1158): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1158): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1158): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1158): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb819fbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1158):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1158): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1158): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1158): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1158): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1158): htc_wext_set_TX_TRACKING (0)+
D/Tethering(  908): interfaceLinkStateChanged wlan0, false
D/Tethering(  908): interfaceStatusChanged wlan0, false
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
D/wpa_supplicant( 1158): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
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
,D/Tethering(  908): [isWifi] getHotspotEnabled: false,
,D/WifiNative-wlan0(  908):    returned true
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
,D/WifiPerfLock(  908): release()
,D/WifiStateMachine(  908): PerfLock released for exiting ConnectedState
,D/WifiNative-wlan0(  908): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1158): Power_Mode_Type mode = 0
I/wpa_supplicant( 1158): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  908):    returned true
,D/WifiNative-wlan0(  908): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1158): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  908):    returned true
,D/DhcpStateMachine(  908): [RunningState] Stop DHCP
D/ConnectivityService(  908): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  908): acquireWL(4243abd0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 908 1000 null
D/WifiP2pService(  908): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  908): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  908): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  908): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  908): doBoolean: RECONNECT
D/WifiDataStallTracker(  908): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  908): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/WifiDataStallTracker(  908): stopDataStallAlarm: current tag=20207 mDataStallAlarmIntent=PendingIntent{42538e00: PendingIntentRecord{42490768 android broadcastIntent}}
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1158): Fast associate: Old scan results
I/wpa_supplicant( 1158): wpa_supplicant_scan enter
I/wpa_supplicant( 1158): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1158): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1158): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1158): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1158): nl80211: Event message available
D/wpa_supplicant( 1158): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiNative-wlan0(  908):    returned true
D/WifiStateMachine(  908): Enter handleNetworkDisconnect
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/libc    (  908): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/libc    (  908): [NET] getaddrinfo-, SUCCESS
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/UsbnetStateTracker(  908): isAvailable+-
D/UsbnetStateTracker(  908): reconnect
D/UsbnetStateTracker(  908): isAvailable+-
,D/WifiNative-wlan0(  908): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1158): Power_Mode_Type mode = 0
I/wpa_supplicant( 1158): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  908):    returned true
D/WifiNative-wlan0(  908): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1158): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiStateTracker(  908): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  908): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  908): Provision feature enable=false
D/ConnectivityService(  908): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  908): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1876/10178)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  908): default: reconnect()
D/MDST    (  908): default: setTeardownRequested(false)
D/MDST    (  908): default: setEnableApn apnType =default , enable=true
D/WifiP2pService(  908): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  908): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  908):    returned true
D/WISPrService( 4144): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
I/jxcore-log( 4359): found test : ./testSendData2.js
I/jxcore-log( 4359): 
D/WISPrService( 4144): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  908): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  908): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  908): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiService(  908): New client listening to asynchronous messages
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  908): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  908): Exit handleNetworkDisconnect
E/jxcore  ( 4359): Error!: missing ) after argument list
E/jxcore  ( 4359): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
I/Choreographer( 4359): Skipped 82 frames!  The application may be doing too much work on its main thread.
D/WifiDataStallTracker(  908): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  908): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  908): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
W/ConnectivityService(  908): Exception trying to remove a route: java.lang.IllegalStateException: command '29 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 29 Failed to remove route from default table (No such process)'
D/ConnectivityService(  908): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  908): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  908): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  908): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WifiStateTracker(  908): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
I/chromium( 4359): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
W/ConnectivityService(  908): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  908): handleConnectivityChange: resetting
D/ConnectivityService(  908): resetConnections(wlan0, 3)
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/PMS     (  908): acquireWL(43e7f2e0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1365 10028 null
D/ConnectivityService(  908): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1876/10178)
D/WISPrService( 4144): >>>>>WISPrService start isConnected = false<<<<<
I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:1
D/libc    (  365): [NET] entry_id:5   entry:0xb7c64d60  removed 
D/libc    (  365): [NET] entry_id:4   entry:0xb7c606a0  removed 
D/libc    (  365): [NET] entry_id:2   entry:0xb7c60148  removed 
D/libc    (  365): [NET] entry_id:6   entry:0xb7c64c30  removed 
D/libc    (  365): [NET] entry_id:3   entry:0xb7c5ffd8  removed 
D/libc    (  365): [NET] entry_id:1   entry:0xb7c64f68  removed 
D/libc    (  365): *************************
D/libc    (  365): *** DNS CACHE FLUSHED ***
D/libc    (  365): *************************
D/PMS     (  908): acquireWL(43401428): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10028 null
,D/ConnectivityService(  908): flush DNS cache for net 1(wlan0)
D/WifiStateMachine(  908): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 4144): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/Nat464Xlat(  908): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  908): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/PMS     (  908): releaseWL(43401428): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  908): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  908): acquireWL(42560a88): PARTIAL_WAKE_LOCK  NetworkStats 0x1 908 1000 null
D/ConnectivityService(  908): reportInetCondition for net -1, percentage: 0 by  (1365/10028)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  908): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by  (908/1000)
D/PMS     (  908): releaseWL(43e7f2e0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/WirelessDisplayService(  908): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  908): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WifiStateMachine(  908): startScan Pid: 908 Uid 1000
,D/WifiNative-wlan0(  908): doBoolean: SCAN
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1158): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1365/10028)
,D/BatSI   (  908): WIFI scan started for: 650a0300 uid:1000
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/WifiNative-wlan0(  908):    returned false
,I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
,D/PMS     (  908): releaseWL(42560a88): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:1
,D/ConnectivityService(  908): mActiveDefaultNetwork: -1
,D/ConnectivityService(  908): handleInetConditionChange: no active default network - ignore
,I/SensorManager(  908): mEventCount = 1500
,D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  908): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  908): [AlarmQueuing] connectivity wifi: false
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by  (908/1000)
D/GpsLocationProvider(  908): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  908): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  908): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  908): ignore wifi update if we are not in OPENING or CLOSING
,D/CaptivePortalTracker(  908): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  908): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/PMS     (  908): acquireWL(425cc0f8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 908 1000 null
D/PMS     (  908): releaseWL(425cc0f8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1424/10028)
D/ConnectivityService(  908): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1876/10178)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.htc.launcher (1270/10075)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1919/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.docs (4247/10100)
D/Tethering(  908): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  908): bSetPropertyMultiRAB:false
,D/CaptivePortalTracker(  908): NoActiveNetworkState
,D/Tethering(  908): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  908): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
,I/Tethering(  908): ipv4Default null
I/Tethering(  908): No IPv4 upstream interface, giving up.
,D/Tethering(  908): TetherMasterSM: InitialState processMessage what=3
D/htcCheckinService(  908): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  908): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,I/ConnectivityHelper( 1270): [onReceive] WIFI(1): DISCONNECTED
,I/NetworkMonitor( 3857): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.google.android.music (3857/10154)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.docs (4247/10100)
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (2030/10021)
,I/ActivityManager(  908): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4430 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4430): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4430): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4430): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4430): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4430): Preparing secondary program dexes.
V/DexLibLoader( 4430): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4430): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4430): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
,V/DexLibLoader( 4430): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4430): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4430): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4430): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4430): Dex already copied
D/OdexVerifier( 4430): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4430): Creating class loader
,V/DexLibLoader( 4430): Finished creating class loader
V/DexLibLoader( 4430): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
,V/DexLibLoader( 4430): Dex already copied
D/OdexVerifier( 4430): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4430): Creating class loader
,V/DexLibLoader( 4430): Finished creating class loader
V/DexLibLoader( 4430): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4430): Dex already copied
D/OdexVerifier( 4430): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4430): Creating class loader
,V/DexLibLoader( 4430): Finished creating class loader
V/DexLibLoader( 4430): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4430): Dex already copied
D/OdexVerifier( 4430): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4430): Creating class loader
,V/DexLibLoader( 4430): Finished creating class loader
,V/DexLibLoader( 4430): Verifying classes from secondary dexes.
,D/DexLibLoader( 4430): DexLibLoader.ensureDexLoaded took 23 ms
,W/dalvikvm( 4430): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4430): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4430): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4430): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4430): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4430): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4430): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4430): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1158): nl80211: Event message available
D/wpa_supplicant( 1158): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1158): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1158): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1158): nl80211: Survey data missing
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1158): Sorted scan results
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1158): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-49
I/wpa_supplicant( 1158): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-49
I/wpa_supplicant( 1158): [NULL] fe:94:e3:11:35:3c freq=2462 level=-90
I/wpa_supplicant( 1158): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
I/wpa_supplicant( 1158): [NULL] fc:94:e3:11:35:3a freq=2462 level=-91
D/wpa_supplicant( 1158): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1158): Add randomness: count=5 entropy=0
D/wpa_supplicant( 1158): Add randomness: count=6 entropy=1
D/wpa_supplicant( 1158): Add randomness: count=7 entropy=2
D/wpa_supplicant( 1158): Add randomness: count=8 entropy=3
D/wpa_supplicant( 1158): Add randomness: count=9 entropy=4
D/wpa_supplicant( 1158): Add randomness: count=10 entropy=5
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
D/wpa_supplicant( 1158): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1158): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1158): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1158): wpa_supplicant_pick_network+
I/wpa_supplicant( 1158): Selecting BSS from priority group 1
I/wpa_supplicant( 1158): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1158): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1158): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1158): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1158):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1158):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-49
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
D/wpa_supplicant( 1158): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb81a14e8  current_ssid=0x0
D/wpa_,supplicant( 1158): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1158): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1158): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1158): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1158): check if in concurrent case
,I/wpa_supplicant( 1158): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1158): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1158): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1158): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1158): RSN: PMKSA cache search - network_ctx=0xb81a14e8 try_opportunistic=0
D/wpa_supplicant( 1158): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1158): RSN: No PMKSA cache entry found
D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
I/wpa_supplicant( 1158): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1158): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1158): netlink: Operstate: linkmode=-1, operstate=5
D/WifiNative-wlan0(  908): doString: LIST_DONGLES
D/wpa_supplicant( 1158): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1158): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1158): nl80211: Unsubscribe mgmt frames handle 0xb81a0718 (mode change)
D/wpa_supplicant( 1158): nl80211: Subscribe to mgmt frames with non-AP handle 0xb81a0718
D/wpa_supplicant( 1158): nl80211: Register frame type=0xd0 nl_handle=0xb81a0718
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1158): nl80211: Register frame type=0xd0 nl_handle=0xb81a0718
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1158): nl80211: Register frame type=0xd0 nl_handle=0xb81a0718
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1158): nl80211: Register frame type=0xd0 nl_handle=0xb81a0718
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1158): nl80211: Register frame type=0xd0 nl_handle=0xb81a0718
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1158): nl80211: Register frame type=0xd0 nl_handle=0xb81a0718
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1158): nl80211: Register frame type=0xd0 nl_handle=0xb81a0718
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1158): nl80211: Register frame type=0xd0 nl_handle=0xb81a0718
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1158): nl80211: Register frame type=0xd0 nl_handle=0xb81a0718
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1158): nl80211: Register frame type=0xd0 nl_handle=0xb81a0718
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1158): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1158):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1158):   * freq=2412
D/wpa_supplicant( 1158):   * Auth Type 0
D/wpa_supplicant( 1158):   * WPA Versions 0x2
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSID
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
D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/wpa_supplicant( 1158): EAPOL: External notification ,- portControl=Auto
D/wpa_supplicant( 1158): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1158): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  908): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1158): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1158): reply (764) for get BSS: id=0
I/wpa_supplicant( 1158): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1158): freq=5220
I/wpa_supplicant( 1158): level=-48
I/wpa_supplicant( 1158): tsf=0000000109201186
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=NG7005g
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=1
I/wpa_supplicant( 1158): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1158): freq=2412
I/wpa_supplicant( 1158): level=-49
I/wpa_supplicant( 1158): tsf=0000000109201204
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=NG700
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=2
I/wpa_supplicant( 1158): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1158): freq=2412
I/wpa_supplicant( 1158): level=-49
I/wpa_supplicant( 1158): tsf=0000000109201199
I/wpa_supplicant( 1158): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1158): ssid=01ABC
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=3
I/wpa_supplicant( 1158): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1158): freq=2462
I/wpa_supplicant( 1158): level=-90
I/wpa_supplicant( 1158): tsf=0000000109201207
I/wpa_supplicant( 1158): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1158): ssid=UPC Wi-Free
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=4
I/wpa_supplicant( 1158): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1158): freq=2437
I/wpa_supplicant( 1158): level=-90
I/wpa_supplicant( 1158): tsf=0000000109201211
I/wpa_supplicant( 1158): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1158): ssid=UPC4688432
I/wpa_supplicant( 1158): ====
I/wpa_supplicant( 1158): id=5
I/wpa_supplicant( 1158): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1158): freq=2462
I/wpa_supplicant( 1158): level=-91
I/wpa_supplicant( 1158): tsf=0000000109201215
I/wpa_supplicant( 1158): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1158): ssid=UPC0039325
I/wpa_supplicant( 1158): ####
W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  908): getDiscoveryDongleList
D/WifiStateMachine(  908): == begin of scan result ==
D/WifiStateMachine(  908): == (6) end of scan result ==
,D/WirelessDisplayService(  908): getDiscoveryDongleList
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/WifiStateMachine(  908): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 109201186, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  908): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 2412, timestamp: 109201204, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  908): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -49, frequency: 2412, timestamp: 109201199, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  908): 3: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 109201207, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  908): 4: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 109201211, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  908): 5: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 109201215, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  908): add 6 to mScanResults
D/BatSI   (  908): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  908): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,W/dalvikvm( 4430): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4430): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
D/wpa_supplicant( 1158): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1158): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1158): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 1158): Wireless event: cmd=0x8b15 len=20
D/Tethering(  908): interfaceLinkStateChanged wlan0, false
D/Tethering(  908): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1158): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1158): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1158): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1158): nl80211: Event message available
D/wpa_supplicant( 1158): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1158): nl80211: Connect event
D/Tethering(  908): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 1158): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1158): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1158): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1158): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1158): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1158): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1158): Add randomness: count=11 entropy=6
I/wpa_supplicant( 1158): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1158): TDLS: Remove peers on association
D/wpa_supplicant( 1158): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1158): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1158): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1158): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1158): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1158): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1158): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1158): EAPOL: Supplicant port status: Unauthorized
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1158): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1158): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1158): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1158): EAPOL: enable timer tick
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1158): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1158): htc_wext_set_keepalive +
I/wpa_supplicant( 1158): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1158): getPrivFuncNum +	
I/wpa_supplicant( 1158): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1158): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1158): htc_wext_set_keepalive - ret = 0
D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
I/wpa_supplicant( 1158): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1158): Get randomness: len=32 entropy=7
D/WifiMonitor(  908): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  908): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  908): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  908): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMon,itor(  908): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  908): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  908): Enter handleAssociatedWithEvent
D/WifiStateMachine(  908): Associated
D/WifiStateMachine(  908): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  908): Exit handleAssociatedWithEvent
D/Tethering(  908): interfaceLinkStateChanged wlan0, true
D/Tethering(  908): interfaceStatusChanged wlan0, true
D/Tethering(  908): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  908): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  908): updateConnectedAP...
,D/WifiApDatabaseHandler(  908): updateConnectedAP...
,D/WifiStateMachine(  908): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  908): isDuplicate in c0:ff:d4:d3:aa:48-0: true,
D/WifiStateMachine(  908): This record is existed, only update it...
D/WifiStateMachine(  908): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  908): updateConnectedAP...
,I/wpa_supplicant( 1158): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1158): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb81a09f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1158):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1158): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1158): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1158): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6ed1b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 1158):    broadcast key
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1158): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1158): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1158): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1158): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1158): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1158): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1158): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1158): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1158): netlink: Operstate: linkmode=-1, operstate=6
,I/wpa_supplicant( 1158): set send_ind_to_ndc = 0
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
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1158): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1158): EAPOL authentication completed successfully
I/wpa_supplicant( 1158): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1158): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1158): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1158): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
,D/WifiMonitor(  908): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/Tethering(  908): interfaceLinkStateChanged wlan0, true
D/Tethering(  908): interfaceStatusChanged wlan0, true
,D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  908): [isWifi] getHotspotEnabled: false
,D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/WifiStateMachine(  908): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  908): updateConnectedAP...
,D/WifiStateMachine(  908): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  908): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  908): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiApDatabaseHandler(  908): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  908): This record is existed, only update it...
,D/WifiStateMachine(  908): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiApDatabaseHandler(  908): updateConnectedAP...
,D/WifiDataStallTracker(  908): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  908): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  908): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  908): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  908): Provision feature enable=false
,D/ConnectivityService(  908): mActiveDefaultNetwork: -1
D/WISPrService( 4144): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4144): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  908): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  908): updateConnectedAP...
,D/DhcpStateMachine(  908): [StoppedState] Start DHCP
,D/WifiStateMachine(  908): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1158): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,D/WifiNative-wlan0(  908): doBoolean: DRIVER BTCOEXMODE 1
D/WifiStateMachine(  908): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  908): acquireWL(42ae9b78): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 908 1000 null
,D/WifiStateMachine(  908): handlePreDhcpSetup mBluetoothConnectionActive: false
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1158): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  908):    returned true
D/WifiNative-wlan0(  908): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1158): Power_Mode_Type mode = 1
I/wpa_supplicant( 1158): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  908):    returned true
D/WifiNative-wlan0(  908): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  908):    returned null
E/WifiStateMachine(  908): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  908): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  908):    returned null
D/WifiP2pService(  908): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@41b16fc8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  908): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@41b16fc8 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:0
,W/fb4a(:<default>):StaticBindingVerifier( 4430): Verify
,D/WifiService(  908): New client listening to asynchronous messages
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4430/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4430): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4430): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4430): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  908): killProcessQuiet, pid=4187
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  908): Killing 4187:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,D/PMS     (  908): acquireWL(43a0bb78): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2250 10028 null
,I/ActivityManager(  908): Recipient 4187
D/WifiService(  908): Client connection lost with reason: 4
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): acquireWL(43ef6a40): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2250 10028 null
,D/PMS     (  908): releaseWL(43a0bb78): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1365): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2250/10028)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2250/10028)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1365/10028)
,D/PMS     (  908): releaseWL(43ef6a40): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/AutoSetting( 1402): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.sense.hsp (1402/10053)
,I/ActivityManager(  908): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4459 uid=10078 gids={50078, 3003, 5012}
,D/AutoSetting( 1402): Util - no network available!
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.sense.hsp (1402/10053)
D/AutoSetting( 1402): service - onCreate()
D/AutoSetting( 1402): service - AddressCache: using context: com.htc.Weather
D/LocationManagerService(  908): request 424768c8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/AutoSetting( 1402): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/LocationManagerService(  908): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1402): service - mHandler: cancel location update
D/AutoSetting( 1402): service -           changes count: 0
,W/fb4a(:<default>):UserScope( 4430): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4430): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/MobileConnectivityChangeReceiver( 4459): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4459): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4459): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4459): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,W/fb4a(:<default>):UserScope( 4430): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/libc    (  908): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent DefaultState
,I/ActivityManager(  908): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4480 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.setupwizard (4459/10078)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.setupwizard (4459/10078)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.setupwizard (4459/10078)
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4430): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  908): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4512 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  908): killProcessQuiet, pid=3839
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Killing 3839:com.htc.mediamanager/u0a32 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3839
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4430): Grow heap (frag case) to 9.958MB for 84664-byte allocation
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4512): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4512): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,D/libc    (  908): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/libc    (  908): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/libc    (  908): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-, SUCCESS
D/libc    (  908): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,I/dalvikvm-heap( 4430): Grow heap (frag case) to 9.973MB for 28144-byte allocation
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  908): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1158): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1158): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4512): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/GAV2    ( 4512): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4512): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,W/Vold    (  355): Returning OperationFailed - no handler for errno 30
E/dalvikvm( 4430): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
W/dalvikvm( 4430): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  908):    returned true
D/WifiNative-wlan0(  908): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1158): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  908):    returned true
,D/WifiStateMachine(  908): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
E/dalvikvm( 4430): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4430): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
E/dalvikvm( 4430): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4430): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/dalvikvm( 4430): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4430): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4430): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
D/WifiP2pService(  908): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  908): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  908): releaseWL(42ae9b78): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
E/dalvikvm( 4430): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4430): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4430): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4430): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4430): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4430): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4430): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4430): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4430): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -49 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1158): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,D/WIFI_ICON( 1116): updateWifiState: RSSI_CHANGED -1 -> 3
D/WifiStateMachine(  908): gateway: /192.168.1.1
D/WifiNative-wlan0(  908): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1158): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  908):    returned true
D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  908): VerifyingLinkState enter
D/WifiStateMachine(  908): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  908): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  908): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  908): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -49, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  908): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  908): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiDataStallTracker(  908): startDataStallAlarm: tag=20209 delay=15s
,D/WISPrService( 4144): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/WifiWatchdogStateMachine(  908): WAN detection
V/NetworkPolicy(  908): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiStateTracker(  908): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  908): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  908): Provision feature enable=false
D/ConnectivityService(  908): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  908): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  908): default: teardown()
D/MDST    (  908): default: setTeardownRequested(true)
D/MDST    (  908): default: setEnableApn apnType =default , enable=false
D/libc    (  908): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
D/MDST    (  908): default: setTeardownRequested(true)
D/ConnectivityService(  908): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  908): Unexpected mtu value: android.net.wifi.WifiStateTracker@423a0b40
D/ConnectivityService(  908): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED connected
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  908): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
D/WifiStateMachine(  908): syncGetConfiguredNetworks
,I/dalvikvm-heap( 4430): Grow heap (frag case) to 10.047MB for 39954-byte allocation
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  365): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  908): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  908): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  908): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  908): handleConnectivityChange: resetting
D/Nat464Xlat(  908): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  908): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  908): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  908): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  908): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  908): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  908): acquireWL(432b1998): PARTIAL_WAKE_LOCK  NetworkStats 0x1 908 1000 null
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by  (908/1000)
D/WirelessDisplayService(  908): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  908):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,I/QuickSettingWifi( 1116): receive.wifiConnect:true wifiAPname:NG700 elapse:1
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.setupwizard (4459/10078)
,I/dalvikvm-heap( 4430): Grow heap (frag case) to 10.123MB for 79892-byte allocation
,I//system/bin/ip(  365): RTNETLINK answers: No such file or directory
,I/logwrapper(  365): /system/bin/ip terminated by exit(254)
D/PMS     (  908): acquireWL(43e71610): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2250 10028 null
D/PMS     (  908): acquireWL(4400b1d0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2250 10028 null
D/PMS     (  908): releaseWL(43e71610): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2250/10028)
,I/CheckinService( 2250): Preparing to send checkin request
,I/EventLogService( 2250): Accumulating logs since 1450742975157
,I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.magazines (4512/10151)
,V/WebViewChromiumFactoryProvider( 4512): Binding Chromium to main looper Looper (main, tid 1) {41a703b0}
,I/LibraryLoader( 4512): Expected native library version number "",actual native library version number ""
,I/chromium( 4512): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4512): Initializing chromium process, renderers=0
,D/ConnectivityService(  908): mActiveDefaultNetwork: WIFI
I/GoogleHttpClient( 2250): Falling back to old SSLCertificateSocketFactory
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
,D/PMS     (  908): releaseWL(432b1998): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/GoogleHttpClient( 2250): Using GMS GoogleHttpClient
D/PMS     (  908): acquireWL(436cf3f8): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
D/PMS     (  908): acquireWL(4377c600): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
,D/PMS     (  908): releaseWL(436cf3f8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,E/AudioManagerAndroid( 4512): BLUETOOTH permission is missing!
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  908): getNetworkInfo networkType=9 called by com.google.android.gms (2250/10028)
,D/ConnectivityService(  908): getNetworkInfo networkType=0 called by com.google.android.gms (2250/10028)
I/Adreno-EGL( 4512): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4512): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4512): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4512): Local Branch: 
I/Adreno-EGL( 4512): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4512): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4512):                  aa63bbd948f41d15fc72f585e
,W/GLSUser ( 1365): GoogleAccountDataService.getToken()
,I/NSApplication( 4512): Starting up...
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.magazines (4512/10151)
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1365): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,I/dalvikvm-heap( 4430): Grow heap (frag case) to 10.281MB for 75760-byte allocation
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.magazines (4512/10151)
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4430/10026)
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (4119/10160)
W/BroadcastQueue(  908): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{432c3260 u0 ReceiverList{432c3140 4430 com.facebook.katana/10026/u0 remote:432bab78}}
W/BroadcastQueue(  908): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{432c3260 u0 ReceiverList{432c3140 4430 com.facebook.katana/10026/u0 remote:432bab78}}
W/BroadcastQueue(  908): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43a0bef8 u0 ReceiverList{43808f08 4430 com.facebook.katana/10026/u0 remote:435db330}}
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (4119/10160)
,W/CheckinRequestBuilder( 2250): awaiting user notification for token
D/Process (  908): killProcessQuiet, pid=4217
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/DotMatrix( 1586): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1586): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1116): com.google.android.gms (false,0)
I/ActivityManager(  908): Killing 4217:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41c1f788 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.google.android.gms 1 8 3 12
D/ConnectivityService(  908): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1876/10178)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4430/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1876/10178)
,I/ActivityManager(  908): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4566 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/GCM     ( 1365): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4430/10026)
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4430/10026)
,D/wpa_supplicant( 1158): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1158): EAPOL: disable timer tick
,I/ActivityManager(  908): Recipient 4217
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): acquireWL(4403b5b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1424 10028 null
,D/ConnectivityService(  908): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1876/10178)
,D/PMS     (  908): releaseWL(4403b5b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/MultiDex( 4566): install
,I/MultiDex( 4566): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4566): loading existing secondary dex files
,I/MultiDex( 4566): load found 1 secondary dex files
,I/MultiDex( 4566): install done
,D/GCoreFlp( 1424): Unknown pending intent to remove.
,I/ProviderInstaller( 4566): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
D/PMS     (  908): acquireWL(43ffc148): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1424 10028 null
,D/PMS     (  908): releaseWL(43ffc148): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/GCM     ( 1365): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4430): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4430): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,I/Adreno-EGL( 4566): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4566): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4566): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4566): Local Branch: 
I/Adreno-EGL( 4566): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4566): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4566):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4566): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4566): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4566): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4566): Local Branch: 
I/Adreno-EGL( 4566): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4566): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4566):                  aa63bbd948f41d15fc72f585e
,D/WIFI_ICON( 1116): WifiActivity: 3
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  908): releaseWL(4243abd0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  908): NetTransition Wakelock for ConnectedState released by timeout
,V/Tethering(  908): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  908): [AlarmQueuing] connectivity wifi: true
,D/GpsLocationProvider(  908): [handleMessage] UPDATE_NETWORK_STATE
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/GpsLocationProvider(  908): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
V/Tethering(  908): bSetPropertyMultiRAB:false
D/GpsLocationProvider(  908): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  908): ignore wifi update if we are not in OPENING or CLOSING
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/Tethering(  908): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/Tethering(  908): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  908): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  908): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  908): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  908): Found interface wlan0
,D/Tethering(  908): TetherMasterSM: InitialState processMessage what=3
,I/ConnectivityHelper( 1270): [onReceive] WIFI(1): CONNECTED
,I/acms    ( 1919): Checking Certificates
I/acms    ( 1919): Checking Developer Certificates
I/acms    ( 1919): Checking Application Certificates
I/acms    ( 1919): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/NetworkMonitor( 3857): type=WIFI subType= reason=null isConnected=true
,I/acms    ( 1919): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1919): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
,I/acms    ( 1919): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
,D/CaptivePortalTracker(  908): NoActiveNetworkState
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1424/10028)
D/PMS     (  908): acquireWL(43a17050): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 908 1000 null
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/PMS     (  908): releaseWL(43a17050): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  908): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1876/10178)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.docs (4247/10100)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.setupwizard (4459/10078)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1919/1000)
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.google.android.music (3857/10154)
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.htc.launcher (1270/10075)
,I/acms    ( 1919): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
,D/htcCheckinService(  908): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  908): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
I/acms    ( 1919): Updating next query delay: 75600000
I/mlserverapp( 1919): MirrorLink is never connected, don't setup ACMS programed checks
,I/mlserverapp( 1919): cancelACMSProgrammedChecks
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  908): DelayedCaptiveCheckState
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.musicenhancer (3878/10051)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.docs (4247/10100)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4430/10026)
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4430/10026)
D/PMS     (  908): acquireWL(4365ba48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
D/ConnectivityService(  908): getActiveNetworkInfo called by  (2030/10021)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4430/10026)
,D/PMS     (  908): releaseWL(4365ba48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!,
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
,D/PMS     (  908): acquireWL(42328700): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2250 10028 null
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/PMS     (  908): releaseWL(42328700): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1365): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1365/10028)
D/libc    ( 1365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1365): [NET] getaddrinfo-,err=8
D/libc    ( 1365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1365): [NET] getaddrinfo-, 1
,D/libc    ( 1365): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =8e12 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/PMS     (  908): acquireWL(42523f40): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1365 10028 null
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2250/10028)
,D/AutoSetting( 1402): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4459): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4459): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.sense.hsp (1402/10053)
,D/AutoSetting( 1402): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1402): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1402): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1402): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 1402): service - handleMessage() setting current location null
D/AutoSetting( 1402): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1402): service - onStartCommand() check timezone in 30000
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.magazines (4512/10151)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.sense.hsp (1402/10053)
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [2][0][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (4119/10160)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (4119/10160)
D/ConnectivityService(  908): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1876/10178)
,I/dalvikvm-heap( 4119): Grow heap (frag case) to 13.500MB for 1821008-byte allocation
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 230
D/libc    (  365): [NET]res_nsend:resplen=79
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1365): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1365): [NET] getaddrinfo-,err=8
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1365/10028)
D/PMS     (  908): acquireWL(43f636c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10028 null
D/PMS     (  908): releaseWL(43f636c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (4566/10028)
,D/GCM     ( 1365): Connected
D/PMS     (  908): acquireWL(424c95b0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1365 10028 null
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1365/10028)
D/PMS     (  908): releaseWL(42523f40): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  908): reportInetCondition for net 1, percentage: 100 by  (1365/10028)
D/ConnectivityService(  908): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  908): handleInetConditionChange: starting a change hold
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1365/10028)
D/PMS     (  908): releaseWL(424c95b0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  908): acquireWL(422fa880): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1365 10028 null
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1365/10028)
,D/ConnectivityService(  908): reportInetCondition for net 1, percentage: 100 by  (1365/10028)
,D/ConnectivityService(  908): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/GCM     ( 1365): Message class mpf
D/ConnectivityService(  908): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  908): reportInetCondition for net 1, percentage: 100 by  (1365/10028)
D/ConnectivityService(  908): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  908): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1365/10028)
D/PMS     (  908): acquireWL(4224d528): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10028 null
D/PMS     (  908): releaseWL(422fa880): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  908): releaseWL(4224d528): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/Settings( 4566): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4566): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4566): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4566): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4566): Local Branch: 
I/Adreno-EGL( 4566): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4566): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4566):                  aa63bbd948f41d15fc72f585e
,I/PMS     (  908): Going to sleep due to screen timeout...
,I/ActivityManager(  908): mThumbnailWidth=360, mThumbnailHeight=640
I/SensorManager(  908): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421059d0
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  908): disable: get sensor name = CM36282 Light sensor
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 2
,W/SensorService(  908): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421059d0, eanble = 0, strlen(mName) = 59
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  908): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4202c800
W/SensorService(  908): Listener[1] = com.htc.smartdim.sensor_eye@41c39450
,W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/BatSI   (  908): Couldn't get kernel wake lock stats
V/LightsService(  908): setLight #2: color=#0
D/qdlights(  908): set_light_buttons_func: on=0 brightness=0
V/LightsService(  908): setLight #0: color=#0
,D/WirelessDisplayService(  908): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  908): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  908): mWirelessDisplayManager is null
,I/CheckinTask( 2250): Sending checkin request (8963 bytes)
D/libc    ( 2250): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2250): [NET] getaddrinfo-,err=8
D/libc    ( 2250): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2250): [NET] getaddrinfo-, 1
D/libc    ( 2250): [NET] getaddrinfo_proxy+
,D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =6532 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 244
D/libc    (  365): [NET]res_nsend:resplen=84
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2250): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2250): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2250): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  908): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  908): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/SurfaceControl(  908): Excessive delay in blankDisplay() while turning screen off: 377ms
D/PMS     (  908): nativeSetInteractive:false
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
D/PMS     (  908): nativeSetInteractive:false done
D/PMS     (  908): nativeSetAutoSuspend:true
D/PMS     (  908): nativeSetAutoSuspend:true done
D/HABCtrl (  908): TPE algorithm. remove timeout.
D/PMS     (  908): OOBE c monitor 11
I/InputManager(  908): Cancel all due to getting PMS screen off broadcast
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/NfcService( 1258): ScreenObserver: OFF
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/NfcService( 1258): applyRouting - 0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=4 [21][1][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
W/ResourceType( 4359): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4359): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41a783a0 VFEDH.C. .F...... 0,0-720,1134 #64}
I/InputMethodManagerService(  908): screenObserver, isScreenOn=false
I/InputMethodManagerService(  908): Disable input method client, pid=4359
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/NfcService( 1258): applyRouting -2
V/KeyguardServiceDelegate(  908): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@439871d0)
,I/IntentController( 1116): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  908): **** SHOWN CALLED ****
D/PMS     (  908): acquireWL(43451d78): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1258 1027 null
D/PMS     (  908): acquireWL(439fc1b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
D/PMS     (  908): releaseWL(43451d78): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  908): wakingUp
D/PMS     (  908): releaseWL(439fc1b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/WindowManager(  908): No lock screen! windowToken=null
D/PMN     (  908): onScreenOn
D/WirelessDisplayService(  908): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  908): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  908): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/MtpService( 2030): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2030): [MTP][onReceive]-
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/NfcService( 1258): applyRouting - 0
,D/NfcService( 1258): applyRouting -2
,D/AutoSetting( 1402): receiver - intent: android.intent.action.USER_PRESENT
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): acquireWL(435bdd10): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1258 1027 null
D/AlarmManager(  908): ACTION_SCREEN_ON
I/AlarmManager(  908): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  908): [AlarmQueuing] done recovering
I/AlarmManager(  908): [AlarmQueuing] recover EPS screen off blocked alarms
D/PMS     (  908): releaseWL(435bdd10): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,I/AlarmManager(  908): [AlarmQueuing] done EPS screen off alarm recovering
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  908): BroadcastReceiver::onReceive-
,D/AutoSetting( 1402): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/WirelessDisplayService(  908): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  908): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  908): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,I/ClockThread( 1116): stop update clock
V/NotificationService(  908): batLight: Full, plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c800
D/qdlights(  908): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,D/WifiDataStallTracker(  908): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  908): startDataStallAlarm: tag=20210 delay=15s
D/TetherSettings( 4144): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4144): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4144): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4144): Cust_ConnectToPC   : spcsc>false
D/        ( 4144): Cust_ConnectToPC   : IPT>true
,D/        ( 4144): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 4144): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
D/WifiNative-wlan0(  908): doBoolean: SET_SCREEN_ON 1
E/SmartNS_Utility( 4144): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4144): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4144): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiStateMachine(  908): BroadcastRSSIForIMS, newrssi =-50 , oldRssi= -200
I/PSReceiver( 4144): onReceive:android.intent.action.USER_PRESENT
D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1158): SET_SCREEN_ON:On
I/wpa_supplicant( 1158): htc_wext_set_keepalive +
I/wpa_supplicant( 1158): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1158): getPrivFuncNum +	
I/wpa_supplicant( 1158): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1158): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1158): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1158): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1158): htc_wext_set_TX_TRACKING - ret = 0
,D/WifiNative-wlan0(  908):    returned true
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1158): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,I/SmartNS_PSService( 4144): onReceive:android.intent.action.USER_PRESENT
D/WIFI_ICON( 1116): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
W/ContextImpl( 4144): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
W/Settings( 4144): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
I/SmartNS_PSService( 4144):  defaultType:0
,W/dalvikvm( 4359): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4359): threadid=1: thread exiting with uncaught exception (group=0x4163ce30)
,V/SRS_Proc(  373): ParamSet string: screen_state=on
V/NotificationService(  908): batLight: Full, plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c800
D/qdlights(  908): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/WirelessDisplayService(  908): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,E/ActivityManager(  908): App crashed! Process: com.test.thalitest
E/AndroidRuntime( 4359): FATAL EXCEPTION: main
E/AndroidRuntime( 4359): Process: com.test.thalitest, PID: 4359
E/AndroidRuntime( 4359): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4359): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4359): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4359): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4359): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4359): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4359): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4359): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4359): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4359): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4359): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4359): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4359): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4359): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4359): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4359): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4359): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4359): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4359): 	at dalvik.system.NativeStart.main(Native Method)
D/NetworkPolicy(  908): updateScreenOn: false
W/ActivityManager(  908):   Force finishing activity com.test.thalitest/.MainActivity
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
D/PMS     (  908): acquireWL(42f1bc70): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 908 1000 null
,W/asset   (  908): Copying FileAsset 0x62654700 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,I/ActivityManager(  908): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4613 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PMS     (  908): acquireWL(4351b870): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10028 null
,D/PMS     (  908): releaseWL(4351b870): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  908): acquireWL(435bea40): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1424 10028 null
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1848): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1848): onScreenOn: 1450743033050
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1848): onScreenOn: 1450743033050
D/PMS     (  908): releaseWL(435bea40): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/ConnectivityService(  908): getNetworkInfo networkType=9 called by com.google.android.gms (2250/10028)
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  908): getNetworkInfo networkType=0 called by com.google.android.gms (2250/10028)
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [1][0][0]
I/SensorManager(  908): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4202c800
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  908): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 2
W/SensorService(  908): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4202c800, eanble = 0, strlen(mName) = 91
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  908): Listener[0] = com.htc.smartdim.sensor_eye@41c39450
,W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  908): goingToSleep
D/PMS     (  908): acquireWL(42419f88): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 908 1000 null
D/PMS     (  908): releaseWL(42f1bc70): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,W/ContextImpl( 4613): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/AlarmManager(  908): ACTION_SCREEN_OFF
I/AlarmManager(  908): [AlarmQueuing] screen off now: 
I/AlarmManager(  908): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  908): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  908): stopDataStallAlarm: current tag=20210 mDataStallAlarmIntent=PendingIntent{43ef7618: PendingIntentRecord{42490768 android broadcastIntent}}
I/AlarmManager(  908): [AlarmQueuing] wifi connection: true
D/WifiNative-wlan0(  908): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1158): SET_SCREEN_ON:Off
I/wpa_supplicant( 1158): htc_wext_set_keepalive +
I/wpa_supplicant( 1158): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1158): getPrivFuncNum +	
I/wpa_supplicant( 1158): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1158): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1158): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1158): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1158): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  908):    returned true
D/WifiNative-wlan0(  908): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/SmartSyncUtils( 4613): isEpsOn(), nState = 0
,D/PMS     (  908): acquireWL(43fa7f00): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 908 1000 null
,V/SRS_Proc(  373): ParamSet string: screen_state=off
D/PMS     (  908): acquireWL(435d5078): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4613 1000 null
,D/wpa_supplicant( 1158): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  908):    returned true
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
D/NetworkPolicy(  908): updateScreenOn: false
D/PMS     (  908): releaseWL(43fa7f00): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/PMS     (  908): releaseWL(435d5078): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
,D/SmartSyncUtils( 4613): getMobilePolicyEnabled, result = true
W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,W/GLSUser ( 1365): GoogleAccountDataService.getToken()
,D/Process (  908): killProcessQuiet, pid=4247
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 4247:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1365): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,D/ContactMessageStore( 1244): start background delete task...
,W/ContextImpl( 4613): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/ContactMessageStore( 1244): size: 0 , 0
W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/ContactMessageStore( 1244): Background delete complete
D/SmartSyncUtils( 4613): isEpsOn(), nState = 0
D/SmartSyncUtils( 4613): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4613): getMobilePolicyEnabled, result = true
D/WifiService(  908): New client listening to asynchronous messages
I/SensorManager(  908): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41c39450
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  908): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 1
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41c39450, eanble = 0, strlen(mName) = 36
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  908): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 0
W/SensorService(  908): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41c39450, eanble = 0, strlen(mName) = 36
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  908): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41c39450
W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] getTotalRam: 1873 Mb
,W/CheckinRequestBuilder( 2250): awaiting user notification for token
E/ActivityThread(  908): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@424b6908 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  908): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@424b6908 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
D/DotMatrix( 1586): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1586): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1848): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1848): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1848): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1848): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1848): onScreenOff
D/PMS     (  908): acquireWL(4365ce40): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1424 10028 null
D/PMS     (  908): releaseWL(4365ce40): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/RemoteViews( 1116): com.google.android.gms (false,0)
D/AutoSetting( 1402): service - mHandler: cancel location update
D/AutoSetting( 1402): service -           changes count: 0
D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41da59c0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1116): com.google.android.gms 1 10 3 12
,I/CheckinTask( 2250): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2250): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2250/10028)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2250/10028)
,D/PMS     (  908): releaseWL(4400b1d0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
I/ActivityManager(  908): Recipient 4247
,D/GCM     ( 1365): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/ActivityThread( 2250): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41cf22d0 that was originally bound here
E/ActivityThread( 2250): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41cf22d0 that was originally bound here
E/ActivityThread( 2250): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2250): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2250): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2250): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2250): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2250): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2250): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2250): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2250): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2250): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2250): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2250): 	at bks.a(SourceFile:298)
E/ActivityThread( 2250): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2250): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2250): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2250): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1365): GCM config loaded
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4430/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4430/10026)
,W/ActivityManager(  908): Activity pause timeout for ActivityRecord{41ab65b8 u0 com.test.thalitest/.MainActivity t2 f}
,D/Process (  908): killProcessQuiet, pid=4270
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
I/ActivityManager(  908): Killing 4270:com.htc.backup/1000 (adj 15): empty #17
,W/fb4a(:<default>):UserScope( 4430): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4430): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 4270
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4430/10026)
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4430/10026)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4430): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4430/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4430/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4430/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4430/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4430/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4430/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4430/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4430/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4430/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4430/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4430/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4430/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4430/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4430/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4430/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4430/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4430/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4430/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4430/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4430/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4430/10026)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4430/10026)
,D/libc    (  908): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-,err=8
D/libc    (  908): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  908): [NET] getaddrinfo-, 1
,D/libc    (  908): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =2bd4 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE,
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  365): [NET]res_nsend:resplen=172
D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  908): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  908): Find DNS Address www.htc.com/104.81.130.175
,D/PMS     (  908): releaseWL(4377c600): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/WifiStateMachine(  908): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  908): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent DefaultState
,D/AutoSetting( 1519): service - handleMessage() stop self
,D/AutoSetting( 1519): service - onDestroy() END
,D/AutoSetting( 1519): service - handleMessage() quit looper
,D/Process (  908): killProcessQuiet, pid=4234
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 4234:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4234
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/GAV2    ( 4512): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  908): acquireWL(44005320): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1424 10028 null
,D/PMS     (  908): acquireWL(436dca00): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1424 10028 null
,D/PMS     (  908): releaseWL(44005320): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  908): releaseWL(436dca00): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/Process (  908): killProcessQuiet, pid=4288
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 4288:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4288
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ActivityManager(  908): Sleep timeout!  Sleeping now.
,D/PMS     (  908): releaseWL(42419f88): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/CaptivePortalTracker(  908): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  908): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  908): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,W/ActivityManager(  908): Activity destroy timeout for ActivityRecord{41ab65b8 u0 com.test.thalitest/.MainActivity t2 f}
,W/Atfwd_Sendcmd(  420): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  908): Waited long enough for: ServiceRecord{4259a838 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  908): acquireWL(4346e700): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  908): releaseWL(4346e700): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
,I/HtcPowerSaver(  908): >> updateStatus
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  420): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  908): acquireWL(4254f4f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  908): sending alarm PendingIntent{42284460: PendingIntentRecord{422e9930 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=139197, Int=0
,D/PMS     (  908): releaseWL(4254f4f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/AutoSetting( 1402): service - mHandler: update timezone
,D/AutoSetting( 1519): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  908): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1519): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1519): service - onCreate()
W/ActivityManager(  908): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found,
,D/AutoSetting( 1519): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1519): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/DotMatrix( 1586): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1586): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  908): batLight: Full, plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c800
D/qdlights(  908): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1519): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1519): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1519): service - mHandler: update timezone
,D/AutoSetting( 1519): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1519): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1519): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1519): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1586): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1586): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1116): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41e19248 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.htc.htclocationservice 2 8 2 11
,D/GpsLocationProvider(  908): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  908): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  908): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  908): acquireWL(431fbd60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
V/AlarmManager(  908): sending alarm PendingIntent{42457740: PendingIntentRecord{42365ef8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141814, Int=0
D/PMS     (  908): acquireWL(435950f8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 908 1000 null
V/AlarmManager(  908): sending alarm PendingIntent{42393fd0: PendingIntentRecord{423e0f60 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142411, Int=0
D/PMS     (  908): releaseWL(431fbd60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1365/10028)
D/PMS     (  908): acquireWL(439f7388): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10028 null
,D/libc    (  908): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-,err=8
D/libc    (  908): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  908): [NET] getaddrinfo-, 1
,D/libc    (  908): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =a032 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/PMS     (  908): releaseWL(439f7388): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/AutoSetting( 1402): service - handleMessage() stop self
,D/AutoSetting( 1402): service - onDestroy() END
,D/AutoSetting( 1402): service - handleMessage() quit looper
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  365): [NET]res_nsend:resplen=238
D/libc    (  365): [NET]res_queryN: exit 3, ancount=10
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  908): [NET] getaddrinfo_proxy-, success
I/global  (  908): call createSocket() return a new socket.
D/libc    (  908): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  908): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  908): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  908): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  908):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  908): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  908): releaseWL(435950f8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  420): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/Process (  908): killProcessQuiet, pid=3878
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3878:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3878
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Waited long enough for: ServiceRecord{42562a50 u0 com.htc.htclocationservice/.AutoSettingService}
,W/Atfwd_Sendcmd(  420): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1519): service - handleMessage() stop self
,D/AutoSetting( 1519): service - onDestroy() END
,D/AutoSetting( 1519): service - handleMessage() quit looper
,D/Process (  908): killProcessQuiet, pid=4304
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 4304:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4304
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): acquireWL(43b32160): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): releaseWL(43b32160): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1244): switchBindHtcMsgCursor: null
,D/PMS     (  908): acquireWL(437f5650): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
I/BatteryService(  908): n_update end
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): releaseWL(437f5650): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  420): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(435905d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42284460: PendingIntentRecord{422e9930 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=199197, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(435905d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43590530): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10026}
,V/AlarmManager(  908): sending alarm PendingIntent{435ac748: PendingIntentRecord{42828b80 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=230275, Int=0
,I/ActivityManager(  908): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4656 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  908): sending alarm PendingIntent{4253e070: PendingIntentRecord{42549ff8 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1450743141803, Int=10800000
,D/PMS     (  908): releaseWL(43590530): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.aurora (4656/10047)
,D/Process (  908): killProcessQuiet, pid=4319
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 4319:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4319
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2250/10028)
,D/PMS     (  908): acquireWL(43486e80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): releaseWL(43486e80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
,I/HtcPowerSaver(  908): >> updateStatus
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(4306a9a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10026}
,V/AlarmManager(  908): sending alarm PendingIntent{434ea298: PendingIntentRecord{42f33718 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=231965, Int=120000
,V/AlarmManager(  908): sending alarm PendingIntent{434049e0: PendingIntentRecord{42828b80 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=232279, Int=0
,D/PMS     (  908): releaseWL(4306a9a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/Atfwd_Sendcmd(  420): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  420): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  908): acquireWL(42fa4920): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
I/BatteryService(  908): n_update end
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): releaseWL(42fa4920): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  420): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  908): acquireWL(42623e70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42284460: PendingIntentRecord{422e9930 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=259197, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42623e70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  420): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  908): acquireWL(425fa310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): releaseWL(425fa310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null,
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  420): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(424f4190): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(424f4190): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(41fef000): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42284460: PendingIntentRecord{422e9930 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=319197, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(41fef000): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  420): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  908): acquireWL(41c36fd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
D/PMS     (  908): releaseWL(41c36fd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(4252fef0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10028}
,V/AlarmManager(  908): sending alarm PendingIntent{42fcf9b0: PendingIntentRecord{434bad88 com.google.android.gms broadcastIntent}}, i=null, t=1, cnt=1, w=1450743278797, Int=0
,D/PMS     (  908): releaseWL(4252fef0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,W/Uploader( 2250): No account for auth token provided
,D/libc    ( 2250): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 2250): [NET] getaddrinfo-,err=8
D/libc    ( 2250): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 2250): [NET] getaddrinfo-, 1
,D/libc    ( 2250): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =df76 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE,
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 11,
D/libc    (  365): [NET]res_nsend:resplen=87
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 2250): [NET] getaddrinfo_proxy-, success
I/global  ( 2250): call createSocket() return a new socket.
D/libc    ( 2250): [NET] getaddrinfo+,hn 14(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 2250): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 2250): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 2250): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2250/10028)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2250/10028)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2250/10028)
,W/Atfwd_Sendcmd(  420): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1365): GoogleAccountDataService.getToken()
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1365): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1586): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1586): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,W/GLSActivity( 1365): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1365): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1365): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1365): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1365): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1365): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1365): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1365): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41d1a838 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/PlayEventLogger( 4077): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4077): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4077): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4077): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4077): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4077): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4077): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4077): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews.Performance( 1116): com.google.android.gms 3 12 3 12
,D/libc    ( 4077): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4077): [NET] getaddrinfo-,err=8
D/libc    ( 4077): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4077): [NET] getaddrinfo-, 1
,D/libc    ( 4077): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =365c +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4077): [NET] getaddrinfo_proxy-, success
I/global  ( 4077): call createSocket() return a new socket.
D/libc    ( 4077): [NET] getaddrinfo+,hn 14(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4077): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4077): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4077): [NET] getaddrinfo-,err=8
,D/PMS     (  908): acquireWL(41f84e20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(41f84e20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): closing low battery warning: level=100
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  420): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  908): acquireWL(435825f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42284460: PendingIntentRecord{422e9930 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=379197, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(435825f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  420): AtCmdFwd service not published, waiting... retryCnt : 4
,D/Process ( 4359): killProcess, pid=4359
,D/Process ( 4359): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/InputMethodManagerService(  908): Disable input method client, pid=4359
,I/ActivityManager(  908): Recipient 4359
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Process com.test.thalitest (pid 4359) has died.
,W/InputDispatcher(  908): channel '42594120 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  908): channel '42594120 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  908): Attempted to unregister already unregistered input channel '42594120 com.test.thalitest.MainActivity (s)'
I/WindowState(  908): WIN DEATH: Window{42594120 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  908): Client connection lost with reason: 4
,I/WindowManager(  908): WINDOW DIED Window{42594120 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/PMS     (  908): acquireWL(422aafd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(422aafd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  420): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(4268c6e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
I/BatteryService(  908): n_update end
D/PMS     (  908): releaseWL(4268c6e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(42499748): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42284460: PendingIntentRecord{422e9930 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=439197, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42499748): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  420): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  908): acquireWL(4229ad08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): releaseWL(4229ad08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  420): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  908): acquireWL(424acb90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): releaseWL(424acb90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  420): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  908): acquireWL(42346ac0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42284460: PendingIntentRecord{422e9930 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=499198, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42346ac0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  420): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  908): acquireWL(430f8f70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10026}
,V/AlarmManager(  908): sending alarm PendingIntent{42ad71c8: PendingIntentRecord{42f33718 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=532287, Int=300000
,D/PMS     (  908): releaseWL(430f8f70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  908): acquireWL(424047d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
I/BatteryService(  908): n_update end
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  908): releaseWL(424047d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  420): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(433b7de8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/PMS     (  908): releaseWL(433b7de8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(43fce640): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42284460: PendingIntentRecord{422e9930 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=559197, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43fce640): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42b65030): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): releaseWL(42b65030): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
,I/HtcPowerSaver(  908): >> updateStatus
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(43645530): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): releaseWL(43645530): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory),
,D/PMS     (  908): acquireWL(43814c08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  908): sending alarm PendingIntent{42284460: PendingIntentRecord{422e9930 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=619198, Int=0
,D/PMS     (  908): releaseWL(43814c08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ContactMessageStore( 1244): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1244): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1244): sku_id=99
D/ContactMessageStore( 1244): start background delete task...
,D/ContactMessageStore( 1244): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1244): size: 0 , 0
,D/ContactMessageStore( 1244): Background delete complete
,D/PMS     (  908): acquireWL(43f81408): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1586): [EventService] reorderNotification, total:1
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
V/NotificationService(  908): batLight: plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c80000
D/qdlights(  908): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): releaseWL(43f81408): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  908): runPSCheck
,D/HeadsetPhoneState( 1614): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=98
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/ContextImpl( 4613): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:2 level:98 unsupport:false plugged:true
D/TetherSettings( 4144): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4144): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4144): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4144): Cust_ConnectToPC   : spcsc>false
D/        ( 4144): Cust_ConnectToPC   : IPT>true
,D/        ( 4144): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4144): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4144): Index of the first 1 = -1
W/ContextImpl( 4144): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/Settings( 4144): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 4144): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
E/SmartNS_Utility( 4144): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4144): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4144): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 4144): [ACC]android_networking:tethering_guard_support=false
,D/PMS     (  908): acquireWL(43385878): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43385878): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  908): updateBatteryInfo
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=98
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(434a5598): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42284460: PendingIntentRecord{422e9930 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=679197, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(434a5598): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(435bcd88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(435bcd88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(43070d50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42284460: PendingIntentRecord{422e9930 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=739197, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43070d50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(432992a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(432992a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(4256f5c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{424a2ab0: PendingIntentRecord{42469608 android broadcastIntent}}, i=com.htc.intent.action.UBLS_REGULAR_ALARM_INEXACT, t=3, cnt=1, w=727518, Int=0
,V/AlarmManager(  908): sending alarm PendingIntent{41d00ba0: PendingIntentRecord{423ab2f8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=785695, Int=0
,V/AlarmManager(  908): sending alarm PendingIntent{4355bcb0: PendingIntentRecord{43a0f838 com.htc.task broadcastIntent}}, i=com.htc.task.statistics, t=1, cnt=1, w=1450743647469, Int=0
,D/ConnectivityService(  908): Sampling interval elapsed, updating statistics ..
,I/ActivityManager(  908): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=4697 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  908): Done.
,D/ConnectivityService(  908): Setting timer for 720seconds
,D/PMS     (  908): acquireWL(43edf9f8): PARTIAL_WAKE_LOCK  HtcDeviceInfoWakeLock_5 0x1 908 1000 null
,D/PMS     (  908): releaseWL(43edf9f8): PARTIAL_WAKE_LOCK  HtcDeviceInfoWakeLock_5 0x1 null
,D/PMS     (  908): acquireWL(42838120): PARTIAL_WAKE_LOCK  HtcDeviceInfoWakeLock_5 0x1 908 1000 null
,D/PMS     (  908): releaseWL(42838120): PARTIAL_WAKE_LOCK  HtcDeviceInfoWakeLock_5 0x1 null
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.htc.server.ulog.EventLogStore.upload:130 com.htc.server.ulog.EventLogStore.onAlarmArrival:220 com.htc.server.ulog.AlarmScheduler$SchedulerBase$CallbackRunnable.run:155 android.os.Handler.handleCallback:733 
,D/PMS     (  908): releaseWL(4256f5c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10070}
,I/ActivityManager(  908): Start proc com.htc.reportagent for broadcast com.htc.reportagent/.receiver.ReportAgentReceiver: pid=4711 uid=10065 gids={50065, 3003, 5012, 1007, 1028, 1015}
,I/MyReportAgent( 4711): ReportAgentReceiver [onReceive] com.htc.intent.action.USER_PROFILING
,D/MyReportAgent( 4711): com.htc.intent.action.USER_PROFILING
,D/Process (  908): killProcessQuiet, pid=3989
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  908): Killing 3989:com.google.android.gm/u0a107 (adj 15): empty #17
,D/MyReportAgent( 4711): ReportService [##] onCreate(), this = com.htc.reportagent.ReportService@41a75450
D/MyReportAgent( 4711): ReportService [##] onStartCommand(), flags = 0, startId = 1, intent = Intent { act=com.htc.intent.action.USER_PROFILING flg=0x10 cmp=com.htc.reportagent/.ReportService (has extras) }, this = com.htc.reportagent.ReportService@41a75450
,D/MyReportAgent( 4711): ReportServiceHandler.onHandleIntent() intent is com.htc.intent.action.USER_PROFILING
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 3989
,D/UPolicy ( 4711): IUserBehaviorLoggingService reference is gotten !
,D/MyReportAgent( 4711): ReportUploader [onUpload] tag: HTC_ULOGDATA, time: 1450743706575 
,D/LocationManagerService(  908): getProviders()=[]
,D/LocationManagerService(  908): getProviders()=[passive]
,D/LocationManagerService(  908): getBestProvider(Criteria[power=NO_REQ acc=---], true)=passive
,D/LocationManagerService(  908): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  908): getProviders()=[]
D/LocationManagerService(  908): getProviders()=[passive]
,D/LocationManagerService(  908): getBestProvider(Criteria[power=NO_REQ acc=---], true)=passive
,D/LocationManagerService(  908): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/HandsetLogCreator( 4711): envelope SN: 116
,D/MyReportAgent( 4711): ReportUploader file size: 1162
,V/MyReportAgent( 4711): Utils getType(): 1, getSubtype: 0
,D/MyReportAgent( 4711): Utils isNetworkAllowed: true, isUSBNETTypeAccepted: true, isTypeWifiAccepted: true, isType2GAccepted: false, isTypeOthersAccepted: false, isUSBNETAllowed: false, isWifiAllowed: true, is2GAllowed: false, isOthersAllowed: false
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.reportagent (4711/10065)
D/ConnectivityService(  908): getNetworkInfo networkType=0 called by com.htc.reportagent (4711/10065)
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.htc.reportagent (4711/10065)
D/ConnectivityService(  908): getNetworkInfo networkType=55 called by com.htc.reportagent (4711/10065)
,D/Wakelock4Data( 4711): logPomeloSender_133.1KB to transmit,reason=send log to server.
D/PMS     (  908): acquireWL(43079390): PARTIAL_WAKE_LOCK  logPomeloSender_133 0x1 4711 10065 null
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.reportagent (4711/10065)
V/MyReportAgent( 4711): Utils getType(): 1, getSubtype: 0
D/MyReportAgent( 4711): Utils isNetworkAllowed: true, isUSBNETTypeAccepted: true, isTypeWifiAccepted: true, isType2GAccepted: false, isTypeOthersAccepted: false, isUSBNETAllowed: false, isWifiAllowed: true, is2GAllowed: false, isOthersAllowed: false
D/MyReportAgent( 4711): ReportUploader Uploaded file size: 1162
D/Pomelo  ( 4711): LogLib params context = android.app.Application@41a70160	isDebug = false	isEngineerROM = false
,D/PomeloConfig( 4711): LogLibStore has VERSIONKEY.
,D/PomeloConfig( 4711): LogLibStore version is 1.3
,D/PomeloConfig( 4711): loadFromPreference(), LogServer = https://pomelo.htcsense.com:443
,D/PomeloConfig( 4711): loadFromPreference(), PolicyServer = https://policylog.htcsense.com:443
,D/PomeloConfig( 4711): loadFromPreference(), RefreshInterval = 604800
,D/Pomelo  ( 4711): sendLogEnvelope envelope valid
,D/Pomelo  ( 4711): inBytes=[1162]
,D/Pomelo  ( 4711): outBytes.length=[691]
,D/libc    ( 4711): [NET] getaddrinfo+,hn 19(0x706f6d656c6f2e),sn(),family 0,flags 4
D/libc    ( 4711): [NET] getaddrinfo-,err=8
D/libc    ( 4711): [NET] getaddrinfo+,hn 19(0x706f6d656c6f2e),sn(),family 0,flags 1024
D/libc    ( 4711): [NET] getaddrinfo-, 1
D/libc    ( 4711): [NET] getaddrinfo_proxy+
,D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706f6d656c6f2e),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =4c5 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 719
D/libc    (  365): [NET]res_nsend:resplen=184
D/libc    (  365): [NET]res_queryN: exit 3, ancount=6
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4711): [NET] getaddrinfo_proxy-, success
I/global  ( 4711): call createSocket() return a new socket.
D/libc    ( 4711): [NET] getaddrinfo+,hn 15(0x3133302e323131),sn(),family 0,flags 4
,D/libc    ( 4711): [NET] getaddrinfo-, SUCCESS
,I/MyReportAgent( 4711): CSUploader returned value : 200 , TAG:HTC_ULOGDATA
D/ConnectivityService(  908): getNetworkInfo networkType=0 called by com.htc.reportagent (4711/10065)
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.htc.reportagent (4711/10065)
D/ConnectivityService(  908): getNetworkInfo networkType=55 called by com.htc.reportagent (4711/10065)
,D/PMS     (  908): releaseWL(43079390): PARTIAL_WAKE_LOCK  logPomeloSender_133 0x1 null
,V/MyReportAgent( 4711): Utils getType(): 1, getSubtype: 0
,D/MyReportAgent( 4711): Utils isNetworkAllowed: true, isUSBNETTypeAccepted: true, isTypeWifiAccepted: true, isType2GAccepted: false, isTypeOthersAccepted: false, isUSBNETAllowed: false, isWifiAllowed: true, is2GAllowed: false, isOthersAllowed: false
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.reportagent (4711/10065)
,D/MyReportAgent( 4711): ReportUploader Start upload resuming queue files. file count: 56
,D/MyReportAgent( 4711): ReportUploader resume file: 0000014ff6b9608e-HTC_ULOGDATA-USAGE-36bc5585-d263-4808-9e6c-c3332f52dfd5
,D/ConnectivityService(  908): getNetworkInfo networkType=0 called by com.htc.reportagent (4711/10065)
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.htc.reportagent (4711/10065)
,D/ConnectivityService(  908): getNetworkInfo networkType=55 called by com.htc.reportagent (4711/10065)
,D/Pomelo  ( 4711): LogLib params context = android.app.Application@41a70160	isDebug = false	isEngineerROM = false
D/PomeloConfig( 4711): LogLibStore has VERSIONKEY.
,D/PomeloConfig( 4711): LogLibStore version is 1.3
D/PomeloConfig( 4711): loadFromPreference(), LogServer = https://pomelo.htcsense.com:443
D/PomeloConfig( 4711): loadFromPreference(), PolicyServer = https://policylog.htcsense.com:443
D/PomeloConfig( 4711): loadFromPreference(), RefreshInterval = 604800
,D/Pomelo  ( 4711): sendLogEnvelope envelope valid
,D/Pomelo  ( 4711): inBytes=[767704]
,D/Pomelo  ( 4711): outBytes.length=[21029]
D/libc    ( 4711): [NET] getaddrinfo+,hn 19(0x706f6d656c6f2e),sn(),family 0,flags 4
D/libc    ( 4711): [NET] getaddrinfo-,err=8
D/libc    ( 4711): [NET] getaddrinfo+,hn 19(0x706f6d656c6f2e),sn(),family 0,flags 1024
D/libc    ( 4711): [NET] getaddrinfo-, 1
D/libc    ( 4711): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706f6d656c6f2e),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =915e +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET]res_queryN: exit 3, ancount=6
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4711): [NET] getaddrinfo_proxy-, success
I/global  ( 4711): call createSocket() return a new socket.
D/libc    ( 4711): [NET] getaddrinfo+,hn 15(0x3133302e323131),sn(),family 0,flags 4
,D/libc    ( 4711): [NET] getaddrinfo-, SUCCESS
,I/MyReportAgent( 4711): CSUploader returned value : 503 , TAG:HTC_ULOGDATA
D/ConnectivityService(  908): getNetworkInfo networkType=0 called by com.htc.reportagent (4711/10065)
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.htc.reportagent (4711/10065)
D/ConnectivityService(  908): getNetworkInfo networkType=55 called by com.htc.reportagent (4711/10065)
,D/MyReportAgent( 4711): break resuming queue files
,V/MyReportAgent( 4711): ReportServiceHandler register the PowerConnected Listener
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.htc.reportagent, clsName=com.htc.reportagent.receiver.PowerConnectedReceiver, state=1, flag=1, pid=4711, uid=10065, userID:0
,D/PMS     (  908): acquireWL(43e66b70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
I/BatteryService(  908): n_update end
,D/PowerUI ( 1116): closing low battery warning: level=98
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): releaseWL(43e66b70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:2 level:98 unsupport:false plugged:true
,D/MyReportAgent( 4711): ReportService [##] onDestroy(), this =com.htc.reportagent.ReportService@41a75450
,I/ActivityManager(  908): Killing 4077:com.android.vending/u0a73 (adj 15): empty #17
D/Process (  908): killProcessQuiet, pid=4077
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  908): Recipient 4077
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): acquireWL(4288a500): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42284460: PendingIntentRecord{422e9930 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=799197, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4288a500): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(4346b178): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): closing low battery warning: level=98
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): releaseWL(4346b178): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(433f0820): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42284460: PendingIntentRecord{422e9930 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=859197, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(433f0820): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(439f9eb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,I/BatteryService(  908): n_update end
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=99
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PMS     (  908): releaseWL(439f9eb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  908): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(4330c330): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4330c330): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(42b31bb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42284460: PendingIntentRecord{422e9930 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=919197, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42b31bb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43b85b30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43b85b30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(43109fa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42284460: PendingIntentRecord{422e9930 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=979197, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43109fa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42f58b00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10028}
,V/AlarmManager(  908): sending alarm PendingIntent{424fa640: PendingIntentRecord{4247df48 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1011433, Int=0
V/AlarmManager(  908): sending alarm PendingIntent{421917d8: PendingIntentRecord{425b3490 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450743862177, Int=900000
,V/AlarmManager(  908): sending alarm PendingIntent{42310f38: PendingIntentRecord{438146d0 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450743933178, Int=0
,D/PMS     (  908): acquireWL(4310d190): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1365 10028 null
,D/PMS     (  908): acquireWL(43fd9ff8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10028 null
,D/PMS     (  908): releaseWL(4310d190): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,W/ContextImpl( 4613): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4613): call getInstance()
,D/SmartSyncUtils( 4613): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4613): MY_DEBUG = false
D/PMS     (  908): releaseWL(43fd9ff8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/PMS     (  908): acquireWL(4349ba48): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4613 1000 null
D/PMS     (  908): releaseWL(42f58b00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 4613): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4613): [updateNmRange] USERNIGHT_TIMESTART = 20, USERNIGHT_TIMEEND = 23, nStart = 20, nEnd = 23, bNormalRange = true,
D/SmartSyncScreenOnOffTimeReceiver( 4613): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4613): SettingOnTime = 1450821600000, randomSettingOnTime = 1450818815000
,D/SmartSyncScreenOnOffTimeReceiver( 4613): SettingOffTime = 1450810800000, randomSettingOffTime = 1450812432000
,D/SmartSyncScreenOnOffTimeReceiver( 4613): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4613): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4613): bNightModeTurnOffOnce = false
W/BatSI   (  908): Couldn't get kernel wake lock stats
D/PMS     (  908): acquireWL(431fb508): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1365 10028 null
,D/PMS     (  908): releaseWL(4349ba48): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/GCM     ( 1365): Message class mow
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  908): reportInetCondition for net 1, percentage: 100 by  (1365/10028)
D/ConnectivityService(  908): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  908): handleInetConditionChange: starting a change hold
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1365/10028)
,D/PMS     (  908): acquireWL(439fb1d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10028 null
,D/PMS     (  908): releaseWL(431fb508): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  908): releaseWL(439fb1d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,D/ConnectivityService(  908): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  908): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=16 [183][31][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1158): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1158): nl80211: survey data missing!
E/wpa_supplicant( 1158): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1158): environment dirty rate=0 [0][0][0]
,D/PMS     (  908): acquireWL(4306c4f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4306c4f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(43439620): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42284460: PendingIntentRecord{422e9930 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1039197, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43439620): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43a16fb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HeadsetPhoneState( 1614): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
V/NotificationService(  908): batLight: Full, plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c800
D/qdlights(  908): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): releaseWL(43a16fb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,D/DotMatrix( 1586): [EventService] reorderNotification, total:0
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,W/ContextImpl( 4613): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,D/TetherSettings( 4144): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4144): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4144): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4144): Cust_ConnectToPC   : spcsc>false
D/        ( 4144): Cust_ConnectToPC   : IPT>true
D/        ( 4144): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4144): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4144): Index of the first 1 = -1
W/ContextImpl( 4144): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/Settings( 4144): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 4144): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4144): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4144): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,W/ContextImpl( 4144): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(4357eb38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4357eb38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(4356cb70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42284460: PendingIntentRecord{422e9930 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1099198, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4356cb70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(434e4550): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(434e4550): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(43451d28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42284460: PendingIntentRecord{422e9930 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1159197, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43451d28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43408198): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43408198): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  908): acquireWL(433f7960): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42284460: PendingIntentRecord{422e9930 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1219197, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(433f7960): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43348818): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43348818): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(432fb850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42284460: PendingIntentRecord{422e9930 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1279197, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(432fb850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(4323f028): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4323f028): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(4314da68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42284460: PendingIntentRecord{422e9930 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1339197, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4314da68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(4306db60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4306db60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(426780c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42284460: PendingIntentRecord{422e9930 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1399198, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(426780c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(424acfc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(424acfc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(42356008): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42284460: PendingIntentRecord{422e9930 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1459197, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42356008): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(41f04540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(41f04540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(41d81e70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42284460: PendingIntentRecord{422e9930 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1519197, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(41d81e70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(420272f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/PMS     (  908): releaseWL(420272f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(422996e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42284460: PendingIntentRecord{422e9930 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1579197, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(422996e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(41f58890): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(41f58890): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(41abce68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
D/PMS     (  908): releaseWL(41abce68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
,D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(422d7238): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42284460: PendingIntentRecord{422e9930 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1639197, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(422d7238): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43584e90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43584e90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(425e5578): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(425e5578): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(424bc908): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42284460: PendingIntentRecord{422e9930 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1699197, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(424bc908): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42080a40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PMS     (  908): releaseWL(42080a40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(41fc9fc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42284460: PendingIntentRecord{422e9930 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1759197, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(41fc9fc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42325f28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42325f28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
,I/HtcPowerSaver(  908): >> updateStatus
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1586): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1586): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,W/AppWidgetServiceImpl(  908): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,D/PMS     (  908): acquireWL(423ef038): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(423ef038): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  908): acquireWL(425bb220): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42284460: PendingIntentRecord{422e9930 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1819197, Int=0
,I/ProcessStatsService(  908): Prepared write state in 33ms
I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(425bb220): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  908): Pruning old procstats: /data/system/procstats/state-2015-12-21-05-06-33.bin
,D/ConnectivityService(  908): Sampling interval elapsed, updating statistics ..
,D/PMS     (  908): acquireWL(4254c0c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41d00ba0: PendingIntentRecord{423ab2f8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1505742, Int=0
,V/AlarmManager(  908): sending alarm PendingIntent{42328b70: PendingIntentRecord{424688d0 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1821301, Int=1800000
V/AlarmManager(  908): sending alarm PendingIntent{41ccdc18: PendingIntentRecord{4240ca80 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1843199, Int=0
,D/PMS     (  908): acquireWL(41a8d768): PARTIAL_WAKE_LOCK  NetworkStats 0x1 908 1000 null
,V/AlarmManager(  908): sending alarm PendingIntent{41f21d78: PendingIntentRecord{42467f00 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450744426895, Int=1800000
,V/AlarmManager(  908): sending alarm PendingIntent{421917d8: PendingIntentRecord{425b3490 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450744762177, Int=900000
,D/ConnectivityService(  908): Done.
,D/ConnectivityService(  908): Setting timer for 720seconds
,D/PMS     (  908): releaseWL(41a8d768): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/PMS     (  908): acquireWL(43b53b80): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 908 1000 null
,D/PMS     (  908): acquireWL(44036e88): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2250 10028 null
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,D/PMS     (  908): acquireWL(424ca758): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
,D/PMS     (  908): acquireWL(4253a6c0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2250 10028 null
,D/PMS     (  908): releaseWL(43b53b80): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  908): releaseWL(44036e88): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,D/PMS     (  908): releaseWL(424ca758): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/EventLogService( 2250): Aggregate from 1450743030903 (log), 1450742626841 (data)
W/ContextImpl( 4613): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  908): releaseWL(4254c0c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,D/PMS     (  908): releaseWL(4253a6c0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,D/PMS     (  908): acquireWL(43329810): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43329810): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(434bcff8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{42284460: PendingIntentRecord{422e9930 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1879197, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(434bcff8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42902f68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10028}
,V/AlarmManager(  908): sending alarm PendingIntent{4252c5f8: PendingIntentRecord{4247df48 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1912484, Int=0
,D/PMS     (  908): acquireWL(43fc16d0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1365 10028 null
,D/PMS     (  908): releaseWL(43fc16d0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,D/Process (  908): killProcessQuiet, pid=1402
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
,D/Process (  908): killProcessQuiet, pid=4119
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  908): Killing 1402:com.htc.sense.hsp/u0a53 (adj 15): empty for 1800s
D/PMS     (  908): acquireWL(43111ed8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10028 null
I/ActivityManager(  908): Killing 4119:com.google.android.apps.plus/u0a160 (adj 15): empty for 1801s
D/PMS     (  908): releaseWL(42902f68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
D/Process (  908): killProcessQuiet, pid=4512
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
,D/Process (  908): killProcessQuiet, pid=4480
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
D/Process (  908): killProcessQuiet, pid=4459
I/ActivityManager(  908): Killing 4512:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1801s
D/PMS     (  908): releaseWL(43111ed8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
I/ActivityManager(  908): Killing 4480:com.android.chrome/u0a96 (adj 15): empty for 1801s
,I/ActivityManager(  908): Killing 4459:com.google.android.setupwizard/u0a78 (adj 15): empty for 1801s
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
D/Process (  908): killProcessQuiet, pid=3857
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
,D/Process (  908): killProcessQuiet, pid=4407
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  908): Killing 3857:com.google.android.music:main/u0a154 (adj 15): empty for 1801s
I/ActivityManager(  908): Killing 4407:com.htc.mms.backupagent/u0a77 (adj 15): empty for 1807s
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 4480
I/ActivityManager(  908): Recipient 4407
I/ActivityManager(  908): Recipient 4459
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 3857
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  908): Client com.google.android.music (pid 3857): Died!
I/ActivityManager(  908): Recipient 1402
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 4512
I/ActivityManager(  908): Recipient 4119
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4757): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4757): ====startRecUseTime====
D/htc.customization.log.level( 4757):  is 
W/CustomizationLogLevel( 4757): Level value is invalid, use default level 2
D/CustomizationManager( 4757):  Read ACC file spent 0.103 (s)
D/CIDMapFileReader( 4757): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4757): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4757): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4757): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4757): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4757): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4757): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4757): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4757): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4757): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4757): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4757): Parsing tag category name = system
I/CustomizationCIDLoader( 4757): Parsing tag category name = application
I/CustomizationCIDLoader( 4757): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4757): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4757): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4757): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4757): Parsing tag category name = Settings
D/CustomizationManager( 4757):  Read CID file spent 0.158 (s)
D/CustomizationManager( 4757):  All configurations done spent 0.158 (s)
W/HtcNativeFlag( 4757): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4757): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4757): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4757): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  908): deletePackageAsUser: pkg=com.test.thalitest, pid=4757, uid=2000 user=0
I/ActivityManager(  908): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
W/asset   (  908): Copying FileAsset 0x69fcd7d0 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
W/PackageSettings(  908): Skipping PackageSetting{42158690 com.example.hello/10356} due to missing metadata
I/ActivityManager(  908): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
D/DotMatrix( 1586): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1586): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver replacing:false
I/acms    ( 1919): Unregistering com.test.thalitest
E/acms    ( 1919): Could not unregister removed application com.test.thalitest
D/DotMatrix( 1586): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1424): Ignoring removeGeofence because network location is disabled.
D/PMS     (  908): acquireWL(41d897c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1424 10028 null
D/PMS     (  908): releaseWL(41d897c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
W/AccTypeManager( 1328): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1328): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/VoicemailCleanupService( 1296): Cleaning up data for package: com.test.thalitest
I/Launcher( 1270): Deferring update until onResume
D/Launcher( 1270): waitUntilResume // bindAppsRemoved
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "sms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
D/AccTypeManager( 1328): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "smsto"
I/InputMethodManagerService(  908): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mmsto"
D/PackageBroadcastService( 2250): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
W/SystemReader( 1258): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "sms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/ActivityManager(  908): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4772 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
E/ExternalAccountType( 1328): Unsupported attribute readOnly
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "smsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/MultiDex( 4772): install
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mmsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/MultiDex( 4772): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4772): loading existing secondary dex files
I/MultiDex( 4772): load found 1 secondary dex files
I/MultiDex( 4772): install done
D/PhoneApp( 1244): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  908): Delaying start of: ServiceRecord{43764b08 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/ActivityManager(  908): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4791 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PeopleContactsSync( 2250): CP2 sync disabled
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2250, uid=10028, userID:0
D/PMS     (  908): acquireWL(422a3160): PARTIAL_WAKE_LOCK  Icing 0x1 2250 10028 null
I/Icing   ( 2250): doRemovePackageData com.test.thalitest
I/ProviderInstaller( 4772): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
E/Icing   ( 2250): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-1 for write failed: Read-only file system
E/Icing   ( 2250): Could not init tag ds.tag.corpusid-1
E/Icing   ( 2250): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-12 for write failed: Read-only file system
E/Icing   ( 2250): Could not init tag ds.tag.corpusid-12
E/Icing   ( 2250): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
E/Icing   ( 2250): Could not init tag ds.tag.deleted
E/Icing   ( 2250): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._i.e66c36715ed1937e for write failed: Read-only file system
E/Icing   ( 2250): Could not init tag ds.tag.user._i.e66c36715ed1937e
E/Icing   ( 2250): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._iim.c6e5dff4518fbbd9 for write failed: Read-only file system
E/Icing   ( 2250): Could not init tag ds.tag.user._iim.c6e5dff4518fbbd9
E/Icing   ( 2250): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_im.1f9d7d94f051768f for write failed: Read-only file system
E/Icing   ( 2250): Could not init tag ds.tag.user._io_im.1f9d7d94f051768f
E/Icing   ( 2250): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_unim.b8d0a49354216c2f for write failed: Read-only file system
E/Icing   ( 2250): Could not init tag ds.tag.user._io_unim.b8d0a49354216c2f
E/Icing   ( 2250): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._o.0f0f93445ed1937e for write failed: Read-only file system
E/Icing   ( 2250): Could not init tag ds.tag.user._o.0f0f93445ed1937e
E/Icing   ( 2250): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._sq_ig_i_person.df4a28e480c88f1e for write failed: Read-only file system
E/Icing   ( 2250): Could not init tag ds.tag.user._sq_ig_i_person.df4a28e480c88f1e
E/Icing   ( 2250): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._u.f26d6a3e5ed1937e for write failed: Read-only file system
E/Icing   ( 2250): Could not init tag ds.tag.user._u.f26d6a3e5ed1937e
E/Icing   ( 2250): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._us.da9dbfca5ed1937e for write failed: Read-only file system
E/Icing   ( 2250): Could not init tag ds.tag.user._us.da9dbfca5ed1937e
E/Icing   ( 2250): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
E/Icing   ( 2250): Writing status failed
D/PMS     (  908): releaseWL(422a3160): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  908): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4791): install
I/MultiDex( 4791): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4791): loading existing secondary dex files
I/MultiDex( 4791): load found 1 secondary dex files
E/SQLiteDatabase( 2250): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 2250): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2250): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2250): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2250): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2250): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2250): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2250): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2250): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2250): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2250): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2250): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2250): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2250): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2250): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2250): 	at bxi.delete(SourceFile:258)
E/SQLiteDatabase( 2250): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 2250): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/SQLiteDatabase( 2250): 	at aqn.a(SourceFile:27)
E/SQLiteDatabase( 2250): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/SQLiteDatabase( 2250): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2250): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2250): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2250): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/MultiDex( 4791): install done
E/ClearPendingStateOp( 2250): Runtime exception while performing operation
E/ClearPendingStateOp( 2250): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 2250): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 2250): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/ClearPendingStateOp( 2250): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/ClearPendingStateOp( 2250): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 2250): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 2250): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 2250): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/ClearPendingStateOp( 2250): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/ClearPendingStateOp( 2250): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/ClearPendingStateOp( 2250): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/ClearPendingStateOp( 2250): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/ClearPendingStateOp( 2250): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/ClearPendingStateOp( 2250): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/ClearPendingStateOp( 2250): 	at bxi.delete(SourceFile:258)
E/ClearPendingStateOp( 2250): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/ClearPendingStateOp( 2250): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/ClearPendingStateOp( 2250): 	at aqn.a(SourceFile:27)
E/ClearPendingStateOp( 2250): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/ClearPendingStateOp( 2250): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ClearPendingStateOp( 2250): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ClearPendingStateOp( 2250): 	at android.os.Looper.loop(Looper.java:157)
E/ClearPendingStateOp( 2250): 	at android.os.HandlerThread.run(HandlerThread.java:61)
F/ClearPendingStateOp( 2250): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 2250): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 2250): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 2250): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
F/ClearPendingStateOp( 2250): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
F/ClearPendingStateOp( 2250): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 2250): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 2250): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 2250): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
F/ClearPendingStateOp( 2250): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
F/ClearPendingStateOp( 2250): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
F/ClearPendingStateOp( 2250): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
F/ClearPendingStateOp( 2250): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
F/ClearPendingStateOp( 2250): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
F/ClearPendingStateOp( 2250): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
F/ClearPendingStateOp( 2250): 	at bxi.delete(SourceFile:258)
F/ClearPendingStateOp( 2250): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
F/ClearPendingStateOp( 2250): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
F/ClearPendingStateOp( 2250): 	at aqn.a(SourceFile:27)
F/ClearPendingStateOp( 2250): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
F/ClearPendingStateOp( 2250): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
F/ClearPendingStateOp( 2250): 	at android.os.Handler.dispatchMessage(Handler.java:102)
F/ClearPendingStateOp( 2250): 	at android.os.Looper.loop(Looper.java:157)
F/ClearPendingStateOp( 2250): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  908): Resuming delayed broadcast
E/SharedPreferencesImpl( 1209): Couldn't rename file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml to backup file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml.bak
E/DropBoxManagerService(  908): Can't write: system_app_wtf
E/DropBoxManagerService(  908): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
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
I/ProviderInstaller( 4791): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  908): Start proc com.htc.sense.hsp for broadcast com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver: pid=4809 uid=10053 gids={50053, 1023, 3003, 5012}
E/SQLiteDatabase( 4772): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4772): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4772): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4772): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4772): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4772): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4772): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4772): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4772): threadid=12: thread exiting with uncaught exception (group=0x4163ce30)
E/AndroidRuntime( 4772): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4772): Process: com.google.android.gms.drive, PID: 4772
E/AndroidRuntime( 4772): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4772): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4772): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4772): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4772): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4772): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4772): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4772): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4772): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4772): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4772): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4772): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4772): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4772): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4772): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4772): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4772): 	at ctn.run(SourceFile:985)
E/ActivityManager(  908): App crashed! Process: com.google.android.gms.drive
D/Process ( 4772): killProcess, pid=4772
D/Process ( 4772): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  908): Can't write: system_app_crash
E/DropBoxManagerService(  908): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  908): Recipient 4772
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Process com.google.android.gms.drive (pid 4772) has died.
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1270): loadItems() com.htc.launcher.pageview.WidgetManager@41afffb8 +
I/Prism.WidgetManager( 1270): onLoadItems() +
D/PluginProvider( 4809): PluginProvider onCreate
E/SQLiteDatabase( 4809): Failed to open database '/data/data/com.htc.sense.hsp/databases/registry.db'.
E/SQLiteDatabase( 4809): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4809): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4809): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4809): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4809): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4809): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4809): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4809): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4809): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4809): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4809): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4809): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4809): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4809): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4809): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.onCreate(Unknown Source)
E/SQLiteDatabase( 4809): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1609)
E/SQLiteDatabase( 4809): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1574)
E/SQLiteDatabase( 4809): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5394)
E/SQLiteDatabase( 4809): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4965)
E/SQLiteDatabase( 4809): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4902)
E/SQLiteDatabase( 4809): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4809): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4809): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4809): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4809): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4809): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4809): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4809): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4809): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4809): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4809): Couldn't open registry.db for writing (will try read-only):
E/SQLiteOpenHelper( 4809): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4809): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4809): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4809): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4809): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4809): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4809): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4809): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4809): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4809): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4809): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4809): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4809): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4809): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4809): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.onCreate(Unknown Source)
E/SQLiteOpenHelper( 4809): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1609)
E/SQLiteOpenHelper( 4809): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1574)
E/SQLiteOpenHelper( 4809): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5394)
E/SQLiteOpenHelper( 4809): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4965)
E/SQLiteOpenHelper( 4809): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4902)
E/SQLiteOpenHelper( 4809): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4809): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4809): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4809): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4809): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4809): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4809): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4809): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4809): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4809): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4809): Opened registry.db in read-only mode
D/PluginProvider( 4809): current plugin count: 19
D/HtcAppUPService( 4809): HtcUPDataProvider onCreate()
I/[PluginManager]RegisterService( 4809): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
W/[PluginManager]RegisterService( 4809): provider may killed!
W/[PluginManager]RegisterService( 4809): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/[PluginManager]RegisterService( 4809): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/[PluginManager]RegisterService( 4809): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/[PluginManager]RegisterService( 4809): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/[PluginManager]RegisterService( 4809): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/[PluginManager]RegisterService( 4809): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
W/[PluginManager]RegisterService( 4809): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:818)
W/[PluginManager]RegisterService( 4809): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:213)
W/[PluginManager]RegisterService( 4809): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/[PluginManager]RegisterService( 4809): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
W/[PluginManager]RegisterService( 4809): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/[PluginManager]RegisterService( 4809): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
W/[PluginManager]RegisterService( 4809): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 4809): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 4809): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 4809): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 4809): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/[PluginManager]RegisterService( 4809): handle notify Blinkfeed plugin client changed
I/ActivityManager(  908): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4825 uid=10073 gids={50073, 3003, 5012, 1028, 1015}

```
