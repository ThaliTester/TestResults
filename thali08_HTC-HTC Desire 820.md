#### Test 5507315224df3aa_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/SensorManager(  904): mEventCount = 1050
,E/cutils-trace( 4766): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4766): ====startRecUseTime====
D/htc.customization.log.level( 4766):  is 
W/CustomizationLogLevel( 4766): Level value is invalid, use default level 2
D/CustomizationManager( 4766):  Read ACC file spent 0.056 (s)
D/CIDMapFileReader( 4766): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4766): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4766): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4766): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4766): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4766): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4766): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4766): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4766): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4766): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4766): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4766): Parsing tag category name = system
I/CustomizationCIDLoader( 4766): Parsing tag category name = application
I/CustomizationCIDLoader( 4766): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4766): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4766): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4766): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4766): Parsing tag category name = Settings
D/CustomizationManager( 4766):  Read CID file spent 0.096 (s)
D/CustomizationManager( 4766):  All configurations done spent 0.096 (s)
W/HtcNativeFlag( 4766): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4766): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4766): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4766): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
W/CpuWake (  904): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  904): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  904): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  904): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  904): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  904): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  904): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4766
D/PMS     (  904): acquireHCC(426bdd98): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 904 1000 null
D/PMS     (  904): acquireHCC(425be020): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 904 1000 null
W/asset   (  904): Copying FileAsset 0x6cab6510 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  904): @test_code: getHtcIntentFlag: 0 obj: 1115442056
D/PMS     (  904): acquireWL(4238ecb8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 904 1000 null
I/FeedHostManager( 1270): [onPause]
I/FeedProviderManager( 1270): onPause
I/FeedHostManager( 1270): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41cc1d30
I/SocialFeedProvider( 1270): +onPause
I/SocialFeedProvider( 1270): -onPause
I/ActivityManager(  904): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4777 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1270): [trimMemory] 20
W/asset   ( 4777): Copying FileAsset 0x5c8f0428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4777): Binding Chromium to main looper Looper (main, tid 1) {41b5c418}
I/LibraryLoader( 4777): Expected native library version number "",actual native library version number ""
I/chromium( 4777): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4777): Initializing chromium process, renderers=0
D/BluetoothManagerService(  904): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  904): java.lang.Throwable: stack dump
D/BluetoothManagerService(  904): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@422bf560:true
W/System.err(  904): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  904): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  904): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  904): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  904): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4777): 1102520368: getState(). Returning 12
D/PMS     (  904): acquireWL(4350c8e8): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  904): acquireWL(42685928): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  904): releaseWL(4350c8e8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4777): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4777): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4777): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4777): Local Branch: 
I/Adreno-EGL( 4777): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4777): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4777):                  aa63bbd948f41d15fc72f585e
W/chromium( 4777): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4777): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4777): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4777): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4777): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4777): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4777): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4777): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4777): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4777): CordovaWebView is running on device made by: HTC
,W/AwContents( 4777): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  904): Disable input method client, pid=1270
W/ResourceType( 4777): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4777): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41ba36e0, mServedView=org.apache.cordova.engine.SystemWebView{41b69348 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/ActivityManager(  904): Displayed com.test.thalitest/.MainActivity: +294ms
W/AwContents( 4777): nativeOnDraw failed; clearing to background color.
W/XT9_C   ( 1209): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1209): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  904): Enable input method client, pid=4777
D/PMS     (  904): releaseWL(4238ecb8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/JsMessageQueue( 4777): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 4777): JniHelper::setJavaVM(0x41631048), pthread_self() = 1663868152
D/JX-Cordova( 4777): jxcore cordova android initializing
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  904):    returned true
,I/dalvikvm-heap( 4777): Grow heap (frag case) to 11.636MB for 96598-byte allocation
,I/dalvikvm-heap( 4777): Grow heap (frag case) to 11.720MB for 144892-byte allocation
,I/dalvikvm-heap( 4777): Grow heap (frag case) to 11.836MB for 217334-byte allocation
,I/dalvikvm-heap( 4777): Grow heap (frag case) to 12.013MB for 325996-byte allocation
,I/dalvikvm-heap( 4777): Grow heap (frag case) to 12.282MB for 488990-byte allocation
,I/dalvikvm-heap( 4777): Grow heap (frag case) to 13.278MB for 1100216-byte allocation
,I/dalvikvm-heap( 4777): Grow heap (frag case) to 14.192MB for 1650320-byte allocation
,I/dalvikvm-heap( 4777): Grow heap (frag case) to 15.555MB for 2475476-byte allocation
,W/CpuWake (  904): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  904): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  904): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  904): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  904): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  904): <<release mCpuPerf_Freq wakelock
D/PMS     (  904): releaseHCC(426bdd98): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  904): releaseHCC(425be020): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4777): Grow heap (frag case) to 17.640MB for 3713210-byte allocation
,W/jxcore-log( 4777): Initializing JXcore engine
,W/jxcore-log( 4777): JXcore engine is ready
,W/jxcore-log( 4777): Starting JXcore engine
,W/jxcore-log( 4777): Platform android
W/jxcore-log( 4777): 
,W/jxcore-log( 4777): Process ARCH arm
W/jxcore-log( 4777): 
,I/jxcore-log( 4777): JXcore Cordova bridge is ready!
I/jxcore-log( 4777): 
,W/jxcore-log( 4777): JXcore engine is started
D/PMS     (  904): releaseWL(42685928): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/chromium( 4777): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/WIFI_ICON( 1118): WifiActivity: 0
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
,D/PMS     (  904): acquireWL(440e8f00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41e2ca80: PendingIntentRecord{424f5588 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=102416, Int=0
,D/PMS     (  904): acquireWL(4411c190): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 904 1000 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): releaseWL(440e8f00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42581d48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/PMS     (  904): releaseWL(4411c190): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  904): releaseWL(42581d48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  904): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4821 uid=10077 gids={50077}
D/PMS     (  904): acquireWL(4377e0b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10077}
,V/AlarmManager(  904): sending alarm PendingIntent{4283edd8: PendingIntentRecord{425a6b50 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1452008696627, Int=60000
,D/PMS     (  904): releaseWL(4377e0b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/PMS     (  904): acquireWL(42546808): PARTIAL_WAKE_LOCK  Icing 0x1 2225 10028 null
,D/WIFI_ICON( 1118): WifiActivity: 1
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  904): releaseWL(42546808): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/SMSBackup( 4821): SMSBackupAgentService started
D/SMSBackup( 4821): Checking restore status
D/SMSBackup( 4821): Restore complete
D/SMSBackup( 4821): cancelCheckAlarm
,D/SMSBackup( 4821): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  904): killProcessQuiet, pid=3984
,I/ActivityManager(  904): Killing 3984:com.htc.task/u0a70 (adj 15): empty #17
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  904): acquireWL(4263c9e0): PARTIAL_WAKE_LOCK  Icing 0x1 2225 10028 null
,D/PMS     (  904): releaseWL(4263c9e0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(42690d68): PARTIAL_WAKE_LOCK  Icing 0x1 2225 10028 null
,D/PMS     (  904): releaseWL(42690d68): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(42560870): PARTIAL_WAKE_LOCK  Icing 0x1 2225 10028 null
,D/PMS     (  904): releaseWL(42560870): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 3984
,I/jxcore-log( 4777): Toggling radios to true
I/jxcore-log( 4777): 
,D/BluetoothAdapter( 4777): enable(): BT is already enabled..!
,D/WifiManager( 4777): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
W/HtcDLNAServiceManager(  904): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  904): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  904): Settings:Agentvalue: 2
W/Settings:Agent(  904): >> traceCallingStack()
W/Settings:Agent(  904): Process.myPid(): 904
W/Settings:Agent(  904): Process.myTid(): 1354
W/Settings:Agent(  904): Process.myUid(): 1000
W/Settings:Agent(  904): 
W/Settings:Agent(  904): 
W/System.err(  904): java.lang.Throwable: stack dump
W/System.err(  904): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  904): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  904): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  904): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  904): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  904): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  904): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  904): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  904): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  904): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  904): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  904): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  904): 
W/Settings:Agent(  904): << traceCallingStack(): 1(ms)
D/WifiService(  904): New client listening to asynchronous messages
D/WifiService(  904): setWifiEnabled: true pid=4777, uid=10348
E/WifiService(  904): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  904): isSprintWifiRestricted(): false
I/WifiService(  904): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  904): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
D/WifiManager( 4777): disconnect: Base Package Name=com.test.thalitest, uid=10348
D/WifiNative-wlan0(  904): doBoolean: DISCONNECT
D/WifiManager( 4777): reconnect: Base Package Name=com.test.thalitest, uid=10348
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): TDLS: Tear down peers
I/wpa_supplicant( 1178): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4777): Radios toggled
I/jxcore-log( 4777): 
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4777): Received device characteristics:
I/jxcore-log( 4777): Bluetooth address: 80:01:84:8A:B3:68
I/jxcore-log( 4777): Bluetooth name: HTC Desire 820
I/jxcore-log( 4777): Device name: HTC-HTC Desire 820
I/jxcore-log( 4777): 
I/jxcore-log( 4777): Perf Test app loaded loaded
I/jxcore-log( 4777): 
I/jxcore-log( 4777): check test folder
I/jxcore-log( 4777): 
I/jxcore-log( 4777): found test : ./testFindPeers.js
I/jxcore-log( 4777): 
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1178): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1178): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1178): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  904): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  904): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/wpa_supplicant( 1178): TDLS: Remove peers on disassociation
D/HTCRequest(  904): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1178): send_and_recv error -67 - cmd 12
D/HTCRequest(  904): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1178): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  904): WifiMonitor:getReasonFromEventString() 3
E/wpa_supplicant( 1178): send_and_recv error -67 - cmd 12
D/HTCRequest(  904): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1178): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb841dbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1178):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1178): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1178): netlink: Operstate: linkmode=-1, operstate=5
,I/wpa_supplicant( 1178): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1178): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1178): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1178): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1178): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1178): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1178): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1178): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1178): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1178): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1178): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1178): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1178): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1178): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1178): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1178): nl80211: Ignore disconnect event triggered during reassociation
D/WifiNative-wlan0(  904):    returned true
D/Tethering(  904): interfaceLinkStateChanged wlan0, false
D/Tethering(  904): interfaceStatusChanged wlan0, false
D/WifiPerfLock(  904): release()
D/WifiStateMachine(  904): PerfLock released for exiting ConnectedState
D/Tethering(  904): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  904): doBoolean: DRIVER POWERMODE 0
D/HTCRequest(  904): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/Tethering(  904): interfaceLinkStateChanged wlan0, false
D/Tethering(  904): interfaceStatusChanged wlan0, false
I/jxcore-log( 4777): found test : ./testSendData.js
I/jxcore-log( 4777): 
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/HTCRequest(  904): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  904): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1178): Power_Mode_Type mode = 0
I/wpa_supplicant( 1178): Set p,ower mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 61
D/Tethering(  904): [isWifi] getHotspotEnabled: false
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doBoolean: DRIVER BTCOEXMODE 2
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  904):    returned true
D/ConnectivityService(  904): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  904): acquireWL(423f2f38): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 904 1000 null
D/WifiP2pService(  904): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  904): [RunningState] Stop DHCP
D/libc    (  904): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  904): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  904): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  904): doBoolean: RECONNECT
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): Fast associate: Old scan results
I/wpa_supplicant( 1178): wpa_supplicant_scan enter
I/wpa_supplicant( 1178): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1178): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1178): wpa_supplicant_trigger_scan +
D/WifiDataStallTracker(  904): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0(  904):    returned true
D/WifiDataStallTracker(  904): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1178): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiStateMachine(  904): Enter handleNetworkDisconnect
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiDataStallTracker(  904): stopDataStallAlarm: current tag=20594 mDataStallAlarmIntent=PendingIntent{4256d710: PendingIntentRecord{42521308 android broadcastIntent}}
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiNative-wlan0(  904): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1178): Power_Mode_Type mode = 0
I/wpa_supplicant( 1178): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  904):    returned true
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  904): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  904): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  904): Provision feature enable=false
D/ConnectivityService(  904): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WifiP2pService(  904): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  904): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 4146): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  904): Exit handleNetworkDisconnect
D/UsbnetStateTracker(  904): isAvailable+-
D/WifiDataStallTracker(  904): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  904): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/UsbnetStateTracker(  904): reconnect
D/UsbnetStateTracker(  904): isAvailable+-
D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent DefaultState
D/WISPrService( 4146): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  904): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1795/10178)
D/WifiStateTracker(  904): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/MDST    (  904): default: reconnect()
D/MDST    (  904): default: setTeardownRequested(false)
D/MDST    (  904): default: setEnableApn apnType =default , enable=true
D/WifiService(  904): New client listening to asynchronous messages
D/ConnectivityService(  904): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  904): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
,D/ConnectivityService(  904): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  360): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  360): [NET] getaddrinfo-, SUCCESS
D/libc    (  360): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  360): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  904): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/libc    (  360): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  360): [NET] getaddrinfo-, SUCCESS
D/libc    (  360): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  360): [NET] getaddrinfo-, SUCCESS
W/ConnectivityService(  904): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  904): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  904): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  904): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1795/10178)
W/ConnectivityService(  904): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/WISPrService( 4146): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  360): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  360): [NET] getaddrinfo-, SUCCESS
D/libc    (  360): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  360): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  904): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/WISPrService( 4146): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  904): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ConnectivityService(  904): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  904): handleConnectivityChange: resetting
D/ConnectivityService(  904): resetConnections(wlan0, 3)
D/PMS     (  904): acquireWL(43772030): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1502 10028 null
D/libc    (  360): [NET] entry_id:8   entry:0xb8d7d530  removed 
D/libc    (  360): [NET] entry_id:7   entry:0xb8d78378  removed 
D/libc    (  360): [NET] entry_id:11   entry:0xb8d786f0  removed 
D/libc    (  360): [NET] entry_id:10   entry:0xb8d77f20  removed 
D/libc    (  360): [NET] entry_id:6   entry:0xb8d78200  removed 
D/libc    (  360): [NET] entry_id:9   entry:0xb8d77d90  removed 
D/libc    (  360): [NET] entry_id:4   entry:0xb8d782c8  removed 
D/libc    (  360): [NET] entry_id:2   entry:0xb8d78108  removed 
D/libc    (  360): [NET] entry_id:5   entry:0xb8d78818  removed 
D/libc    (  360): [NET] entry_id:12   entry:0xb8d77e58  removed 
D/libc    (  360): [NET] entry_id:3   entry:0xb8d77fd8  removed 
D/libc    (  360): [NET] entry_id:1   entry:0xb8d78410  removed 
D/libc    (  360): [NET] entry_id:13   entry:0xb8d78d98  removed 
D/libc    (  360): *************************
D/libc    (  360): *** DNS CACHE FLUSHED ***
D/libc    (  360): *************************
D/PMS     (  904): acquireWL(426a0910): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1502 10028 null
D/ConnectivityService(  904): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  904): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  904): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1502/10028)
D/ConnectivityService(  904): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  904): acquireWL(43d10e08): PARTIAL_WAKE_LOCK  NetworkStats 0x1 904 1000 null
D/ConnectivityService(  904): reportInetCondition for net -1, percentage: 0 by  (1502/10028)
D/PMS     (  904): releaseWL(426a0910): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/PMS     (  904): releaseWL(43772030): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/WirelessDisplayService(  904): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  904): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/WifiStateMachine(  904): startScan Pid: 904 Uid 1000
D/WifiNative-wlan0(  904): doBoolean: SCAN
I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:1
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1178): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/WifiNative-wlan0(  904):    returned false
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by  (904/1000)
D/ConnectivityService(  904): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  904): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/BatSI   (  904): WIFI scan started for: 650a0300 uid:1000
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1502/10028)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1502/10028)
I//system/bin/ip(  360): RTNETLINK answers: No such process
,I/logwrapper(  360): /system/bin/ip terminated by exit(2)
,I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:0
D/PMS     (  904): releaseWL(43d10e08): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  904): mActiveDefaultNetwork: -1
D/ConnectivityService(  904): handleInetConditionChange: no active default network - ignore
,I/Choreographer( 4777): Skipped 89 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4777): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  904): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  904): [AlarmQueuing] connectivity wifi: false
,D/ConnectivityService(  904): getNetworkInfo networkType=1 called by  (904/1000)
,D/Tethering(  904): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  904): bSetPropertyMultiRAB:false
D/Tethering(  904): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  904): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  904): ipv4Default null
I/Tethering(  904): No IPv4 upstream interface, giving up.
,D/Tethering(  904): TetherMasterSM: InitialState processMessage what=3,
D/CaptivePortalTracker(  904): DelayedCaptiveCheckState
D/CaptivePortalTracker(  904): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false,
,D/CaptivePortalTracker(  904): NoActiveNetworkState
,I/ConnectivityHelper( 1270): [onReceive] WIFI(1): DISCONNECTED
,I/NetworkMonitor( 4242): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000),
D/PMS     (  904): acquireWL(43d36830): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 904 1000 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1795/10178)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1533/10028)
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by com.htc.launcher (1270/10075)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1853/1000)
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by com.google.android.music (4242/10154)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.docs (4602/10100)
D/htcCheckinService(  904): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  904): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.docs (4602/10100)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (2929/10021)
,I/ActivityManager(  904): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4847 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4847): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4847): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4847): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4847): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4847): Preparing secondary program dexes.
V/DexLibLoader( 4847): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4847): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4847): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4847): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4847): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4847): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4847): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4847): Dex already copied
D/OdexVerifier( 4847): Odex verification is skipped.
,V/DexLibLoader( 4847): Creating class loader
,V/DexLibLoader( 4847): Finished creating class loader
V/DexLibLoader( 4847): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4847): Dex already copied
D/OdexVerifier( 4847): Odex verification is skipped.
,V/DexLibLoader( 4847): Creating class loader
,V/DexLibLoader( 4847): Finished creating class loader
V/DexLibLoader( 4847): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4847): Dex already copied
D/OdexVerifier( 4847): Odex verification is skipped.
,V/DexLibLoader( 4847): Creating class loader
,V/DexLibLoader( 4847): Finished creating class loader
V/DexLibLoader( 4847): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4847): Dex already copied
D/OdexVerifier( 4847): Odex verification is skipped.
,V/DexLibLoader( 4847): Creating class loader
,V/DexLibLoader( 4847): Finished creating class loader
,V/DexLibLoader( 4847): Verifying classes from secondary dexes.
,D/DexLibLoader( 4847): DexLibLoader.ensureDexLoaded took 19 ms
,D/GpsLocationProvider(  904): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  904): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  904): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  904): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  904): releaseWL(43d36830): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/dalvikvm( 4847): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4847): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4847): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4847): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4847): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4847): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4847): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1178): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1178): nl80211: Survey data missing
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1178): Sorted scan results
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1178): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1178): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-52
I/wpa_supplicant( 1178): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-74
I/wpa_supplicant( 1178): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-75
I/wpa_supplicant( 1178): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-83
I/wpa_supplicant( 1178): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1178): [NULL] 06:7c:34:38:27:cc freq=2462 level=-89
I/wpa_supplicant( 1178): [NULL] 64:7c:34:38:27:cc freq=2462 level=-89
D/wpa_supplicant( 1178): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1178): Add randomness: count=10 entropy=0
D/wpa_supplicant( 1178): Add randomness: count=11 entropy=1
D/wpa_supplicant( 1178): Add randomness: count=12 entropy=2
D/wpa_supplicant( 1178): Add randomness: count=13 entropy=3
D/wpa_supplicant( 1178): Add randomness: count=14 entropy=4
D/wpa_supplicant( 1178): Add randomness: count=15 entropy=5
D/wpa_supplicant( 1178): Add randomness: count=16 entropy=6
D/wpa_supplicant( 1178): Add randomness: count=17 entropy=7
D/wpa_supplicant( 1178): Add randomness: count=18 entropy=8
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  904): doString: LIST_DONGLES
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1178): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: AP 64:7c:34:38:27:cc type 0 added
D/wpa_supplicant( 1178): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1178): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1178): wpa_supplicant_pick_network+
I/wpa_supplicant( 1178): Selecting BSS from priority group 1
I/wpa_supplicant( 1178): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1178): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1178): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1178): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1178): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1178):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1178):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-52
I/wpa_supplicant( 1178): Start print parameters
I/wpa_supplicant( 1178): wpa_s->wpa_state is 3
I/wpa_supplicant( 1178): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1178): isConcurrentMode() is 0
I/wpa_supplicant( 1178): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1178): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1178): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1178): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1178): wpa_s->reassociate is 1
I/wpa_supplicant( 1178): wpa_s->is_screen_on 1
I/wpa_supplicant( 1178): wpa_s->ifname wlan0
I/wpa_supplicant( 1178): End print parameters
I/wpa_supplicant( 1178): selected network = 2
D/wpa_supplicant( 1178): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb841f4e8  current_ssid=0x0
D/wpa_supplicant( 1178): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1178): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1178): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1178): check if in concurrent case
,I/wpa_supplicant( 1178): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1178): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1178): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1178): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1178): RSN: PMKSA cache search - network_ctx=0xb841f4e8 try_opportunistic=0
D/wpa_supplicant( 1178): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1178): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1178): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1178): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1178): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1178): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1178): nl80211: Unsubscribe mgmt frames handle 0xb841e718 (mode change)
D/wpa_supplicant( 1178): nl80211: Subscribe to mgmt frames with non-AP handle 0xb841e718
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb841e718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb841e718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb841e718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb841e718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb841e718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb841e718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb841e718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb841e718
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb841e718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Register frame type=0xd0 nl_handle=0xb841e718
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1178): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1178):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1178):   * freq=2412
D/wpa_supplicant( 1178):   * Auth Type 0
D/wpa_supplicant( 1178):   * WPA Versions 0x2
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1178): nl80211: Connect request send successfully
D/wpa_supplicant( 1178): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
W/dalvikvm( 4847): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  904): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1178): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1178): reply (1211) for get BSS: id=0
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1178): freq=5220
I/wpa_supplicant( 1178): level=-48
I/wpa_supplicant( 1178): tsf=0000000105101293
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG7005g
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=1
I/wpa_supplicant( 1178): bssid=c2:ff:d4:d3:aa:48
,I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-52
I/wpa_supplicant( 1178): tsf=0000000105101306
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1178): ssid=01ABC
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=2
I/wpa_supplicant( 1178): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-52
I/wpa_supplicant( 1178): tsf=0000000105101309
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=NG700
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=3
I/wpa_supplicant( 1178): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1178): freq=2412
I/wpa_supplicant( 1178): level=-74
I/wpa_supplicant( 1178): tsf=0000000105101313
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=Gonzos
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=4
I/wpa_supplicant( 1178): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1178): freq=2437
I/wpa_supplicant( 1178): level=-75
I/wpa_supplicant( 1178): tsf=0000000105101316
I/wpa_supplicant( 1178): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1178): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=5
I/wpa_supplicant( 1178): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1178): freq=2437
I/wpa_supplicant( 1178): level=-83
I/wpa_supplicant( 1178): tsf=0000000105101323
I/wpa_supplicant( 1178): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1178): ssid=UPC5999698
I/wpa_supplicant( 1178): ====,
I/wpa_supplicant( 1178): id=6
I/wpa_supplicant( 1178): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1178): freq=2437
I/wpa_supplicant( 1178): level=-84
I/wpa_supplicant( 1178): tsf=0000000105101320
I/wpa_supplicant( 1178): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1178): ssid=UPC Wi-Free
I/wpa_supplicant( 1178): ====
I/wpa_supplicant( 1178): id=7
I/wpa_supplicant( 1178): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1178): freq=2462
I/wpa_supplicant( 1178): level=-89
I/wpa_supplicant( 1178): tsf=0000000105101327
I/wpa_supplicant( 1178): flags=
W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/WirelessDisplayService(  904): getDiscoveryDongleList
,D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
,D/WifiStateMachine(  904): == begin of scan result ==
,D/WifiStateMachine(  904): == (9) end of scan result ==
,D/WirelessDisplayService(  904): getDiscoveryDongleList
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/WifiStateMachine(  904): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 105101293, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -52, frequency: 2412, timestamp: 105101306, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -52, frequency: 2412, timestamp: 105101309, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2412, timestamp: 105101313, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 4: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -75, frequency: 2437, timestamp: 105101316, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -83, frequency: 2437, timestamp: 105101323, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 6: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -84, frequency: 2437, timestamp: 105101320, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 7: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 105101327, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 8: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -89, frequency: 2462, timestamp: 105101331, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): add 9 to mScanResults
D/BatSI   (  904): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  904): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,W/dalvikvm( 4847): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1178): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
,D/wpa_supplicant( 1178): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1178): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1178): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1178): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1178): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1178): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1178): nl80211: Event message available
D/wpa_supplicant( 1178): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1178): nl80211: Connect event
D/Tethering(  904): interfaceLinkStateChanged wlan0, false
D/Tethering(  904): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1178): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1178): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1178): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1178): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1178): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1178): Add randomness: count=19 entropy=9
I/wpa_supplicant( 1178): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1178): TDLS: Remove peers on association
D/wpa_supplicant( 1178): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1178): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1178): EAPOL: enable timer tick
D/wpa_supplicant( 1178): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1178): htc_wext_set_keepalive +
I/wpa_supplicant( 1178): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1178): getPrivFuncNum +	
I/wpa_supplicant( 1178): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1178): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1178): htc_wext_set_keepalive - ret = 0
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
I/wpa_supplicant( 1178): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1178): Get randomness: len=32 entropy=10
D/WifiMonitor(  904): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  904): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  904): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412,
D/WifiMonitor(  904): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  904): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  904): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  904): Enter handleAssociatedWithEvent
D/WifiStateMachine(  904): Associated
D/WifiStateMachine(  904): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  904): Exit handleAssociatedWithEvent
D/WifiStateMachine(  904): BSSID was changed, update WiFi database
D/Tethering(  904): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  904): updateConnectedAP...
,D/Tethering(  904): interfaceLinkStateChanged wlan0, true
D/Tethering(  904): interfaceStatusChanged wlan0, true
D/WifiApDatabaseHandler(  904): updateConnectedAP...
D/Tethering(  904): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  904): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  904): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  904): This record is existed, only update it...
D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  904): updateConnectedAP...
I/wpa_supplicant( 1178): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb841e9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 1178):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1178): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1178): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6ee1b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1178):    broadcast key
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1178): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1178): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1178): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1178): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1178): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
,D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 1178): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1178): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1178): netlink: Operstate: linkmode=-1, operstate=6
D/WifiMonitor(  904): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1178): set send_ind_to_ndc = 0
I/wpa_supplicant( 1178): htc_wext_set_TX_TRACKING (1)+
,I/wpa_supplicant( 1178): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1178): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1178): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1178): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1178): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1178): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1178): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1178): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1178): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1178): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1178): EAPOL authentication completed successfully
I/wpa_supplicant( 1178): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1178): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1178): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1178): nl80211: if_removed already cleared - ignore event
D/Tethering(  904): interfaceLinkStateChanged wlan0, true
D/Tethering(  904): interfaceStatusChanged wlan0, true
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/Tethering(  904): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  904): updateConnectedAP...
,E/FbInjectorInitializer( 4847): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/WifiStateMachine(  904): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  904): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  904): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  904): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  904): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiApDatabaseHandler(  904): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  904): This record is existed, only update it...
D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  904): updateConnectedAP...
,I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WISPrService( 4146): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateTracker(  904): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  904): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  904): Provision feature enable=false
D/ConnectivityService(  904): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WISPrService( 4146): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  904): updateConnectedAP...
,D/DhcpStateMachine(  904): [StoppedState] Start DHCP
D/WifiStateMachine(  904): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1178): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
,D/WifiNative-wlan0(  904): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1178): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
,D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doBoolean: DRIVER POWERMODE 1
D/WifiStateMachine(  904): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  904): acquireWL(424b7108): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 904 1000 null
,D/WifiStateMachine(  904): handlePreDhcpSetup mBluetoothConnectionActive: false
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1178): Power_Mode_Type mode = 1
I/wpa_supplicant( 1178): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  904):    returned null
E/WifiStateMachine(  904): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  904): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  904):    returned null
D/WifiP2pService(  904): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42570fa8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42570fa8 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:0
,W/fb4a(:<default>):StaticBindingVerifier( 4847): Verify
,D/WifiService(  904): New client listening to asynchronous messages
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4847): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4847): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4847): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  904): killProcessQuiet, pid=4618
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  904): Killing 4618:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,D/PMS     (  904): acquireWL(4216c600): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2225 10028 null
,D/PMS     (  904): acquireWL(4204d818): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2225 10028 null
,D/PMS     (  904): releaseWL(4216c600): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2225/10028)
,D/GCM     ( 1502): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1502/10028)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1502/10028)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1502/10028)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2225/10028)
D/PMS     (  904): releaseWL(4204d818): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/AutoSetting( 1481): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  904): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4877 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.sense.hsp (1481/10053)
,D/AutoSetting( 1481): Util - no network available!
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.sense.hsp (1481/10053)
D/AutoSetting( 1481): service - onCreate()
D/AutoSetting( 1481): service - AddressCache: using context: com.htc.Weather
D/AutoSetting( 1481): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/LocationManagerService(  904): request 42465148 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/LocationManagerService(  904): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1481): service - mHandler: cancel location update
D/AutoSetting( 1481): service -           changes count: 0
,I/ActivityManager(  904): Recipient 4618
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  904): Client connection lost with reason: 4
,W/fb4a(:<default>):UserScope( 4847): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4847): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
D/MobileConnectivityChangeReceiver( 4877): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4877): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4877): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4877): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,W/fb4a(:<default>):UserScope( 4847): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
I/ActivityManager(  904): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4893 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.setupwizard (4877/10078)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.setupwizard (4877/10078)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.setupwizard (4877/10078)
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4847): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  904): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4910 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  904): killProcessQuiet, pid=4225
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  904): Killing 4225:com.htc.mediamanager/u0a32 (adj 15): empty #17
,E/dalvikvm( 4847): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4847): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4847): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4847): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4847): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4847): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4847): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4847): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,I/ActivityManager(  904): Recipient 4225
,I/dalvikvm-heap( 4847): Grow heap (frag case) to 9.963MB for 84664-byte allocation
,W/dalvikvm( 4847): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4847): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4847): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4847): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/dalvikvm( 4847): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4847): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4910): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4910): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4910): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4910): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4910): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/dalvikvm-heap( 4847): Grow heap (frag case) to 9.977MB for 28144-byte allocation
E/dalvikvm( 4847): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4847): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4847): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4847): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4847): Grow heap (frag case) to 10.017MB for 39954-byte allocation
,I/dalvikvm-heap( 4847): Grow heap (frag case) to 10.092MB for 79892-byte allocation
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.magazines (4910/10151)
,V/WebViewChromiumFactoryProvider( 4910): Binding Chromium to main looper Looper (main, tid 1) {41b61110}
,I/LibraryLoader( 4910): Expected native library version number "",actual native library version number ""
,I/chromium( 4910): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4910): Initializing chromium process, renderers=0
,D/PMS     (  904): acquireWL(44103120): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
,E/AudioManagerAndroid( 4910): BLUETOOTH permission is missing!
D/PMS     (  904): acquireWL(426fdbd8): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  904): releaseWL(426fdbd8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4910): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4910): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4910): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4910): Local Branch: 
I/Adreno-EGL( 4910): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4910): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4910):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4910): Starting up...
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.magazines (4910/10151)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.magazines (4910/10151)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.plus (3923/10160)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.plus (3923/10160)
,D/Process (  904): killProcessQuiet, pid=4660
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  904): Killing 4660:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 4660
,I/dalvikvm-heap( 4847): Grow heap (frag case) to 10.280MB for 75760-byte allocation
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
D/PMS     (  904): acquireWL(424fe2d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
D/ConnectivityService(  904): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1795/10178)
V/AlarmManager(  904): sending alarm PendingIntent{423974d0: PendingIntentRecord{423e3038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=106061, Int=0
D/ConnectivityService(  904): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1795/10178)
,D/GCM     ( 1502): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
D/PMS     (  904): releaseWL(424fe2d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
W/BroadcastQueue(  904): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42562b80 u0 ReceiverList{4254cae8 4847 com.facebook.katana/10026/u0 remote:42411fc0}}
W/BroadcastQueue(  904): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42562b80 u0 ReceiverList{4254cae8 4847 com.facebook.katana/10026/u0 remote:42411fc0}}
W/BroadcastQueue(  904): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4306e810 u0 ReceiverList{42eddb68 4847 com.facebook.katana/10026/u0 remote:42c73180}}
,I/ClockThread( 1118): now=1452008700026 next=59974
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
,D/PMS     (  904): acquireWL(42607918): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1533 10028 null
,D/PMS     (  904): releaseWL(42607918): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/GCoreFlp( 1533): Unknown pending intent to remove.
D/PMS     (  904): acquireWL(44159df8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1533 10028 null
D/PMS     (  904): releaseWL(44159df8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/wpa_supplicant( 1178): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1178): EAPOL: disable timer tick
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4847): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4847): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,D/libc    (  904): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  904): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
D/libc    (  904): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
D/libc    (  904): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-, SUCCESS
D/libc    (  904): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  904): doBoolean: DRIVER POWERMODE 0,
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1178): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1178): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0,
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 61,
,D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0,
D/wpa_supplicant( 1178): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12,
D/WifiNative-wlan0(  904):    returned true
D/WifiStateMachine(  904): handlePostDhcpSetup release wake lock during DHCP,
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  904): releaseWL(424b7108): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiP2pService(  904): InactiveState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): P2pEnabledState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WIFI_ICON( 1118): updateWifiState: RSSI_CHANGED -1 -> 3
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1178): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  904): gateway: /192.168.1.1
D/WifiNative-wlan0(  904): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1178): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  904):    returned true
D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  904): VerifyingLinkState enter
D/WifiStateMachine(  904): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  904): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  904): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  904): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -52, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  904): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  904): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  904): startDataStallAlarm: tag=20596 delay=15s
,I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NetworkPolicy(  904): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiWatchdogStateMachine(  904): WAN detection
,D/WISPrService( 4146): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/WifiStateTracker(  904): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  904): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  904): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1795/10178)
D/ConnectivityService(  904): Provision feature enable=false
D/ConnectivityService(  904): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  904): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  904): default: teardown()
D/MDST    (  904): default: setTeardownRequested(true)
D/MDST    (  904): default: setEnableApn apnType =default , enable=false
D/libc    (  904): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  904): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  904): syncGetConfiguredNetworks
D/MDST    (  904): default: setTeardownRequested(true)
D/ConnectivityService(  904): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  904): Unexpected mtu value: android.net.wifi.WifiStateTracker@42489648
D/ConnectivityService(  904): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/WIFI_ICON( 1118): WifiActivity: 3
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/libc    (  360): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  360): [NET] getaddrinfo-, SUCCESS
D/libc    (  360): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  360): [NET] getaddrinfo-, SUCCESS
D/libc    (  360): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  360): [NET] getaddrinfo-, SUCCESS
D/libc    (  360): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  360): [NET] getaddrinfo-, SUCCESS
D/libc    (  360): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  360): [NET] getaddrinfo-, SUCCESS
D/libc    (  360): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  360): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  904): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  904): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  904): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,D/libc    (  360): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  904): handleConnectivityChange: resetting
D/Nat464Xlat(  904): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  904): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  904): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  904): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  904): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  904): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  904): acquireWL(425f2078): PARTIAL_WAKE_LOCK  NetworkStats 0x1 904 1000 null
D/WirelessDisplayService(  904): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  904):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=100 [1][1][0]
,I/QuickSettingWifi( 1118): receive.wifiConnect:true wifiAPname:NG700 elapse:0
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by  (904/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.setupwizard (4877/10078)
D/PMS     (  904): acquireWL(43832180): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2225 10028 null
,I//system/bin/ip(  360): RTNETLINK answers: No such file or directory
,I/logwrapper(  360): /system/bin/ip terminated by exit(254)
D/PMS     (  904): acquireWL(43bb7908): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2225 10028 null
D/PMS     (  904): releaseWL(43832180): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2225/10028)
I/CheckinService( 2225): Preparing to send checkin request
I/EventLogService( 2225): Accumulating logs since 1452008645391
,I//system/bin/ip(  360): RTNETLINK answers: No such process
,I/logwrapper(  360): /system/bin/ip terminated by exit(2)
,I/GoogleHttpClient( 2225): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2225): Using GMS GoogleHttpClient
D/ConnectivityService(  904): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  904): releaseWL(425f2078): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  904): getNetworkInfo networkType=9 called by com.google.android.gms (2225/10028)
D/ConnectivityService(  904): getNetworkInfo networkType=0 called by com.google.android.gms (2225/10028)
,W/GLSUser ( 1502): GoogleAccountDataService.getToken()
,W/GLSActivity( 1502): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1502): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1502): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1545): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1545): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1118): com.google.android.gms (false,0)
,W/CheckinRequestBuilder( 2225): awaiting user notification for token
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{41ba3a40 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1118): com.google.android.gms 1 8 2 12
,I/ActivityManager(  904): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4984 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 4984): install
,I/MultiDex( 4984): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4984): loading existing secondary dex files
,I/MultiDex( 4984): load found 1 secondary dex files
,I/MultiDex( 4984): install done,
,I/ProviderInstaller( 4984): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1502): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/Adreno-EGL( 4984): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4984): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4984): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4984): Local Branch: 
I/Adreno-EGL( 4984): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4984): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4984):                  aa63bbd948f41d15fc72f585e
,D/WIFI_ICON( 1118): WifiActivity: 1
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  904): releaseWL(423f2f38): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  904): NetTransition Wakelock for ConnectedState released by timeout
,V/Tethering(  904): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  904): [AlarmQueuing] connectivity wifi: true
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
D/GpsLocationProvider(  904): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  904): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  904): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  904): ignore wifi update if we are not in OPENING or CLOSING
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
V/Tethering(  904): bSetPropertyMultiRAB:false
D/Tethering(  904): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,D/CaptivePortalTracker(  904): NoActiveNetworkState
,I/Tethering(  904): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
,I/Tethering(  904): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  904): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  904): ipv4Default 0.0.0.0/0 -> 192.168.1.1
,I/Tethering(  904): Found interface wlan0
,D/Tethering(  904): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by  (904/1000)
D/PMS     (  904): acquireWL(438271c0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 904 1000 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/PMS     (  904): releaseWL(438271c0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  904): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1795/10178)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1533/10028)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1853/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1533/10028)
I/acms    ( 1853): Checking Certificates
I/acms    ( 1853): Checking Developer Certificates
I/acms    ( 1853): Checking Application Certificates
I/acms    ( 1853): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1853): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1853): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1853): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1853): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1853): Updating next query delay: 75600000
I/mlserverapp( 1853): MirrorLink is never connected, don't setup ACMS programed checks
I/mlserverapp( 1853): cancelACMSProgrammedChecks
,D/CaptivePortalTracker(  904): DelayedCaptiveCheckState
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/AccTypeManager( 1323): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/AccTypeManager( 1323): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ConnectivityHelper( 1270): [onReceive] WIFI(1): CONNECTED
D/htcCheckinService(  904): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  904): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/PMS     (  904): acquireWL(4382b458): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.setupwizard (4877/10078)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.docs (4602/10100)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by com.google.android.music (4242/10154)
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by com.htc.launcher (1270/10075)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.musicenhancer (4276/10051)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.docs (4602/10100)
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,I/NetworkMonitor( 4242): type=WIFI subType= reason=null isConnected=true
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
D/PMS     (  904): releaseWL(4382b458): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
,D/AccTypeManager( 1323): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  904): getActiveNetworkInfo called by  (2929/10021)
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  904): acquireWL(431e7940): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2225 10028 null
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/PMS     (  904): releaseWL(431e7940): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,E/ExternalAccountType( 1323): Unsupported attribute readOnly
,D/GCM     ( 1502): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1502/10028)
,W/dalvikvm( 4777): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4777): threadid=1: thread exiting with uncaught exception (group=0x41729e30)
D/libc    ( 1502): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1502): [NET] getaddrinfo-,err=8
D/libc    ( 1502): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1502): [NET] getaddrinfo-, 1
D/libc    ( 1502): [NET] getaddrinfo_proxy+
D/libc    (  360): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
,D/libc    (  360): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  360): [NET] +++++ res_nsend xid =192 +++++
D/libc    (  360): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  360): [NET] NOT IN CACHE
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1502/10028)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1502/10028)
D/PMS     (  904): acquireWL(4319d498): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1502 10028 null
,E/AndroidRuntime( 4777): FATAL EXCEPTION: main
E/AndroidRuntime( 4777): Process: com.test.thalitest, PID: 4777
E/AndroidRuntime( 4777): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4777): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4777): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4777): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4777): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4777): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4777): 	at io.jxcore.node.JXcoreExtension$4.Receiver(JXcoreExtension.java:112)
E/AndroidRuntime( 4777): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4777): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4777): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4777): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4777): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4777): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4777): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4777): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4777): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4777): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4777): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4777): 	at dalvik.system.NativeStart.main(Native Method)
,E/ActivityManager(  904): App crashed! Process: com.test.thalitest
,D/libc    ( 1502): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1502): [NET] getaddrinfo-,err=8
D/libc    ( 1502): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1502): [NET] getaddrinfo-, 1
,D/libc    ( 1502): [NET] getaddrinfo_proxy+
D/libc    (  360): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  360): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  360): [NET] +++++ res_nsend xid =b2f5 +++++
D/libc    (  360): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  360): [NET] NOT IN CACHE
D/PMS     (  904): acquireWL(4319d498): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1502 10028 null
W/ActivityManager(  904):   Force finishing activity com.test.thalitest/.MainActivity
I/ActivityManager(  904): mThumbnailWidth=360, mThumbnailHeight=640
,D/PMS     (  904): acquireWL(4413dc60): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 904 1000 null
,W/asset   (  904): Copying FileAsset 0x63e81c00 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1502/10028)
,D/libc    (  360): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 243
D/libc    (  360): [NET]res_nsend:resplen=79
D/libc    (  360): [NET]res_queryN: exit 3, ancount=2
D/libc    (  360): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  360): [NET] getaddrinfo-, SUCCESS
D/libc    (  360): [NET]res_nsend:resplen=79
,D/libc    (  360): [NET]res_queryN: exit 3, ancount=2
D/libc    (  360): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  360): [NET] getaddrinfo-, SUCCESS
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2225/10028)
D/libc    ( 1502): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1502): [NET] getaddrinfo_proxy-, success
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1502/10028)
,D/AutoSetting( 1481): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4877): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4877): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1481): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1481): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1481): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1481): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 1481): service - handleMessage() setting current location null
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.sense.hsp (1481/10053)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.magazines (4910/10151)
D/AutoSetting( 1481): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1481): service - onStartCommand() check timezone in 30000
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [5][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.sense.hsp (1481/10053)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.plus (3923/10160)
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.plus (3923/10160)
D/ConnectivityService(  904): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1795/10178)
,D/libc    ( 1502): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1502): [NET] getaddrinfo-,err=8
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1502/10028)
D/PMS     (  904): acquireWL(44139dd0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1502 10028 null
D/PMS     (  904): releaseWL(44139dd0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/Settings( 4984): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4984): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4984): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4984): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4984): Local Branch: 
I/Adreno-EGL( 4984): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4984): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4984):                  aa63bbd948f41d15fc72f585e
,D/libc    ( 1502): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1502): [NET] getaddrinfo-,err=8
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1502/10028)
D/PMS     (  904): acquireWL(4407ce30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1502 10028 null
D/PMS     (  904): releaseWL(4407ce30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/Adreno-EGL( 4984): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4984): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4984): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4984): Local Branch: 
I/Adreno-EGL( 4984): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4984): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4984):                  aa63bbd948f41d15fc72f585e
,D/GCM     ( 1502): Connected
D/PMS     (  904): acquireWL(4419d2f8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1502 10028 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1502/10028)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1502/10028)
D/PMS     (  904): releaseWL(4319d498): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1502/10028)
D/ConnectivityService(  904): reportInetCondition for net 1, percentage: 100 by  (1502/10028)
D/ConnectivityService(  904): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  904): handleInetConditionChange: starting a change hold
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1502/10028)
D/PMS     (  904): releaseWL(4419d2f8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  904): acquireWL(437695b8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1502 10028 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1502/10028)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1502/10028)
D/ConnectivityService(  904): reportInetCondition for net 1, percentage: 0 by  (1502/10028)
D/ConnectivityService(  904): handleInetConditionChange: net=1, condition=0,mActiveDefaultNetwork=1
D/ConnectivityService(  904): handleInetConditionChange: currently in hold - not setting new end evt
D/PMS     (  904): releaseWL(437695b8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  904): acquireWL(425f3dc0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1502 10028 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1502/10028)
D/ConnectivityService(  904): reportInetCondition for net 1, percentage: 0 by  (1502/10028)
D/PMS     (  904): releaseWL(425f3dc0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  904): handleInetConditionChange: net=1, condition=0,mActiveDefaultNetwork=1
D/ConnectivityService(  904): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1502/10028)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1502/10028)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (4984/10028)
,I/CheckinTask( 2225): Sending checkin request (9013 bytes)
,D/libc    ( 2225): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2225): [NET] getaddrinfo-,err=8
D/libc    ( 2225): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2225): [NET] getaddrinfo-, 1
D/libc    ( 2225): [NET] getaddrinfo_proxy+
D/libc    (  360): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  360): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  360): [NET] +++++ res_nsend xid =309b +++++
D/libc    (  360): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  360): [NET] NOT IN CACHE
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/libc    (  360): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 233
D/libc    (  360): [NET]res_nsend:resplen=84
D/libc    (  360): [NET]res_queryN: exit 3, ancount=2
D/libc    (  360): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  360): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2225): [NET] getaddrinfo_proxy-, success
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=5 [18][1][0]
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiStateMachine(  904): BroadcastRSSIForIMS, newrssi =-53 , oldRssi= -200
D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1178): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
D/WIFI_ICON( 1118): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/libc    ( 2225): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2225): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
,W/fb4a(:<default>):UserScope( 4847): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4847): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [8][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
,W/ActivityManager(  904): Activity pause timeout for ActivityRecord{41b69c68 u0 com.test.thalitest/.MainActivity t2 f}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
,I/FeedHostManager( 1270): [onResume]
,I/FeedProviderManager( 1270): onResume
I/SocialFeedProvider( 1270): +onResume
I/SocialFeedProvider( 1270): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1270): -onResume
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.launcher (1270/10075)
,D/PMS     (  904): releaseWL(4413dc60): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/Process (  904): killProcessQuiet, pid=4602
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
I/ActivityManager(  904): Killing 4602:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/PMS     (  904): Going to sleep due to screen timeout...
,D/WirelessDisplayService(  904): Screen File Receiver; callOnGoing: false, Screen On: false
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42190b60
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  904): disable: get sensor name = CM36282 Light sensor
,W/PMS     (  904): mWirelessDisplayManager is null
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 2
W/SensorService(  904): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42190b60, eanble = 0, strlen(mName) = 59
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  904): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@422c3af8
W/SensorService(  904): Listener[1] = com.htc.smartdim.sensor_eye@41c02498
W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/WirelessDisplayService(  904): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/BatSI   (  904): Couldn't get kernel wake lock stats
I/ActivityManager(  904): Recipient 4602
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
V/LightsService(  904): setLight #2: color=#0
D/qdlights(  904): set_light_buttons_func: on=0 brightness=0
V/LightsService(  904): setLight #0: color=#0
,D/ConnectivityService(  904): handleInetConditionHoldEnd: net=1, condition=0, published condition=0
,D/ConnectivityService(  904): sendGeneralBroadcast, restrictEnable=false
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=25 [4][1][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
,D/WIFI_ICON( 1118): WifiActivity: 3
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/SurfaceControl(  904): Excessive delay in blankDisplay() while turning screen off: 374ms
,D/PMS     (  904): nativeSetInteractive:false
D/PMS     (  904): nativeSetInteractive:false done
D/PMS     (  904): nativeSetAutoSuspend:true
,D/PMS     (  904): nativeSetAutoSuspend:true done
,D/HABCtrl (  904): TPE algorithm. remove timeout.
,D/PMS     (  904): OOBE c monitor 11
,V/KeyguardServiceDelegate(  904): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@433e4c70)
E/fb4a(:<default>):LocalFbBroadcastManager( 4847): Called registerBroadcastReceiver twice.
I/InputMethodManagerService(  904): screenObserver, isScreenOn=false
I/InputMethodManagerService(  904): Disable input method client, pid=4777
,D/PMN     (  904): wakingUp
D/NfcService( 1256): ScreenObserver: OFF
D/NfcService( 1256): applyRouting - 0
,V/KeyguardServiceDelegate(  904): **** SHOWN CALLED ****
,D/NfcService( 1256): applyRouting -2
D/PMS     (  904): acquireWL(4411fdc0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
I/WindowManager(  904): No lock screen! windowToken=null
D/PMS     (  904): acquireWL(42515538): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
D/PMS     (  904): releaseWL(4411fdc0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  904): onScreenOn
D/PMS     (  904): releaseWL(42515538): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/InputManager(  904): Cancel all due to getting PMS screen off broadcast
,D/HtcPowerSaver(  904): updateBatteryInfo
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  904): acquireWL(437ea638): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1502 10028 null
D/PowerUI ( 1118): closing low battery warning: level=99
,D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1545): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/MtpService( 2929): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2929): [MTP][onReceive]-
D/NfcService( 1256): applyRouting - 0
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
,D/NfcService( 1256): applyRouting -2
,D/AutoSetting( 1481): receiver - intent: android.intent.action.USER_PRESENT
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PMS     (  904): acquireWL(42646998): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
D/PMS     (  904): releaseWL(42646998): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/WirelessDisplayService(  904): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  904): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  904): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  904): releaseWL(437ea638): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/PMS     (  904): releaseWL(44103120): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/HtcPowerSaver(  904): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
D/AutoSetting( 1481): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,I/IntentController( 1118): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/WirelessDisplayService(  904): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  904): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  904): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/TetherSettings( 4146): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4146): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4146): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4146): Cust_ConnectToPC   : spcsc>false
D/        ( 4146): Cust_ConnectToPC   : IPT>true
D/        ( 4146): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 4146): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4146): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4146): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4146): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
V/NotificationService(  904): batLight: plugged
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c80000
D/qdlights(  904): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,I/PSReceiver( 4146): onReceive:android.intent.action.USER_PRESENT
W/ContextImpl( 4146): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/AlarmManager(  904): ACTION_SCREEN_ON
I/AlarmManager(  904): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  904): [AlarmQueuing] done recovering
I/AlarmManager(  904): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  904): [AlarmQueuing] done EPS screen off alarm recovering
I/SmartNS_PSService( 4146): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4146): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 4146):  defaultType:0
D/WifiDataStallTracker(  904): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  904): startDataStallAlarm: tag=20597 delay=15s
,I/BatteryController( 1118): status:2 level:99 unsupport:false plugged:true
D/ConnectivityService(  904): getNetworkInfo networkType=9 called by com.google.android.gms (2225/10028)
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  904): doBoolean: SET_SCREEN_ON 1
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [2][0][0]
D/ConnectivityService(  904): getNetworkInfo networkType=0 called by com.google.android.gms (2225/10028)
W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/ClockThread( 1118): stop update clock
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1178): SET_SCREEN_ON:On
I/wpa_supplicant( 1178): htc_wext_set_keepalive +
I/wpa_supplicant( 1178): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1178): getPrivFuncNum +	
I/wpa_supplicant( 1178): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1178): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1178): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1178): htc_wext_set_TX_TRACKING (1)+
,I/wpa_supplicant( 1178): htc_wext_set_TX_TRACKING - ret = 0
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,D/WifiNative-wlan0(  904):    returned true
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
I/ActivityManager(  904): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=5030 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1178): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
D/WIFI_ICON( 1118): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
V/NotificationService(  904): batLight: plugged
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c80000
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
D/qdlights(  904): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,V/SRS_Proc(  370): ParamSet string: screen_state=on
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
,D/WirelessDisplayService(  904): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false,
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
D/NetworkPolicy(  904): updateScreenOn: false
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
,W/ContextImpl( 5030): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
,D/PMS     (  904): acquireWL(4406c6b0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5030 1000 null
,D/SmartSyncUtils( 5030): isEpsOn(), nState = 0
,W/GLSUser ( 1502): GoogleAccountDataService.getToken()
,D/DotMatrix( 1545): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1767): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1767): onScreenOn: 1452008703195
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1767): onScreenOn: 1452008703195
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
D/PMS     (  904): acquireWL(43d52140): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1533 10028 null
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
D/PMS     (  904): releaseWL(43d52140): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@422c3af8
,W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  904): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 2
W/SensorService(  904): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@422c3af8, eanble = 0, strlen(mName) = 91
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  904): Listener[0] = com.htc.smartdim.sensor_eye@41c02498
,W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
D/PMS     (  904): releaseWL(4406c6b0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
D/PMN     (  904): goingToSleep
W/GLSActivity( 1502): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1502): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
I/FeedHostManager( 1270): [onPause]
,I/FeedProviderManager( 1270): onPause
I/FeedHostManager( 1270): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41cc1d30
I/SocialFeedProvider( 1270): +onPause
,I/SocialFeedProvider( 1270): -onPause
D/PMS     (  904): acquireWL(43c38f60): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 904 1000 null
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
,W/GLSActivity( 1502): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  904): releaseWL(43c38f60): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/AlarmManager(  904): ACTION_SCREEN_OFF
I/AlarmManager(  904): [AlarmQueuing] screen off now: 
D/WifiDataStallTracker(  904): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  904): stopDataStallAlarm: current tag=20597 mDataStallAlarmIntent=PendingIntent{43d2e688: PendingIntentRecord{42a5c580 android broadcastIntent}}
,D/WifiNative-wlan0(  904): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1178): SET_SCREEN_ON:Off
I/wpa_supplicant( 1178): htc_wext_set_keepalive +
I/wpa_supplicant( 1178): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1178): getPrivFuncNum +	
I/wpa_supplicant( 1178): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1178): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1178): get_ip_address source addr = c0a80176
D/WifiNative-wlan0(  904): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 1178): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1178): htc_wext_set_keepalive - ret = 0
,D/SmartSyncUtils( 5030): getMobilePolicyEnabled, result = true
D/WifiNative-wlan0(  904):    returned true
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
I/AlarmManager(  904): [AlarmQueuing] data connection: true
I/AlarmManager(  904): [AlarmQueuing] wifi connection: true
D/PMS     (  904): acquireWL(41f67388): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 904 1000 null
,D/Process (  904): killProcessQuiet, pid=4690
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,W/CheckinRequestBuilder( 2225): awaiting user notification for token
,I/ActivityManager(  904): Killing 4690:com.htc.backup/1000 (adj 15): empty #17
D/DotMatrix( 1545): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1545): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/wpa_supplicant( 1178): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  904):    returned true
,V/SRS_Proc(  370): ParamSet string: screen_state=off
,I/RemoteViews( 1118): com.google.android.gms (false,0)
W/ContextImpl( 5030): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  904): releaseWL(41f67388): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
I/ActivityManager(  904): Recipient 4690
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{41cabd90 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/SmartSyncUtils( 5030): isEpsOn(), nState = 0
,D/SmartSyncUtils( 5030): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 5030): isEpsOn(), nState = 0
,I/RemoteViews.Performance( 1118): com.google.android.gms 1 9 3 12
D/WifiService(  904): New client listening to asynchronous messages
,D/NetworkPolicy(  904): updateScreenOn: false
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ContactMessageStore( 1245): start background delete task...
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/ContactMessageStore( 1245): size: 0 , 0
,D/ContactMessageStore( 1245): Background delete complete
,I/CheckinTask( 2225): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2225): Unable to close GMS GoogleHttpClient
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2225/10028)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2225/10028)
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41c02498
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  904): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 1
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41c02498, eanble = 0, strlen(mName) = 36
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  904): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 0
W/SensorService(  904): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41c02498, eanble = 0, strlen(mName) = 36
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41c02498
W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  904): releaseWL(43bb7908): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 2225): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41bea6a0 that was originally bound here
E/ActivityThread( 2225): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41bea6a0 that was originally bound here
E/ActivityThread( 2225): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2225): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2225): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2225): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2225): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2225): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2225): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2225): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2225): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2225): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2225): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2225): 	at bks.a(SourceFile:298)
E/ActivityThread( 2225): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2225): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2225): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2225): 	at java.lang.Thread.run(Thread.java:864)
,D/GCM     ( 1502): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
E/ActivityThread(  904): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42559878 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  904): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42559878 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  904): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  904): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  904): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  904): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  904): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  904): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  904): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  904): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  904): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  904): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  904): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  904): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  904): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  904): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  904): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  904): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  904): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  904): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  904): 	at dalvik.system.NativeStart.main(Native Method)
,D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1545): [EventService] getTotalRam: 1873 Mb
,I/GCM     ( 1502): GCM config loaded
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1767): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1767): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1767): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1767): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1767): onScreenOff
D/libc    ( 1502): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1502): [NET] getaddrinfo-,err=8
D/libc    ( 1502): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1502): [NET] getaddrinfo-, 1
,D/libc    ( 1502): [NET] getaddrinfo_proxy+
D/libc    (  360): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/PMS     (  904): acquireWL(42535300): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1533 10028 null
D/PMS     (  904): releaseWL(42535300): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/PMS     (  904): acquireWL(422f9e88): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1502 10028 null
D/libc    (  360): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  360): [NET] +++++ res_nsend xid =a652 +++++
D/libc    (  360): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  360): [NET]res_queryN: exit 3, ancount=2
D/libc    (  360): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  360): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1502): [NET] getaddrinfo_proxy-, success
,D/AutoSetting( 1481): service - mHandler: cancel location update
,D/AutoSetting( 1481): service -           changes count: 0
,D/libc    ( 1502): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1502): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1502/10028)
,D/PMS     (  904): acquireWL(4238a280): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1502 10028 null
,D/PMS     (  904): releaseWL(4238a280): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/libc    (  904): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-,err=8
D/libc    (  904): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  904): [NET] getaddrinfo-, 1
,D/libc    (  904): [NET] getaddrinfo_proxy+
D/libc    (  360): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
,D/libc    (  360): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  360): [NET] +++++ res_nsend xid =4806 +++++
D/libc    (  360): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  360): [NET] NOT IN CACHE,
,D/libc    (  360): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19,
D/libc    (  360): [NET]res_nsend:resplen=172,
D/libc    (  360): [NET]res_queryN: exit 3, ancount=4
D/libc    (  360): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  360): [NET] getaddrinfo-, SUCCESS
D/libc    (  904): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  904): Find DNS Address www.htc.com/104.81.130.175,
,I/GAV2    ( 4910): Thread[GAThread,5,main]: No campaign data found.
,D/WifiStateMachine(  904): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  904): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent DefaultState
,D/PMS     (  904): acquireWL(42709918): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1533 10028 null
,D/PMS     (  904): acquireWL(426369f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1533 10028 null
,D/PMS     (  904): releaseWL(42709918): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  904): releaseWL(426369f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/AutoSetting( 1465): service - handleMessage() stop self
,D/AutoSetting( 1465): service - onDestroy() END
,D/AutoSetting( 1465): service - handleMessage() quit looper
,D/Process (  904): killProcessQuiet, pid=4677
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4677:com.htc.cs.dm/u0a98 (adj 15): empty #17,
,I/ActivityManager(  904): Recipient 4677
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  904): killProcessQuiet, pid=4707
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4707:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 4707
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ContactMessageStore( 1245): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1245): MSG_NOTIFY_CS_TO_SYNC <<
,D/PMS     (  904): releaseWL(422f9e88): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
,I/dalvikvm-heap( 4847): Grow heap (frag case) to 11.015MB for 36988-byte allocation
,I/dalvikvm-heap( 4847): Grow heap (frag case) to 11.042MB for 55478-byte allocation
,I/dalvikvm-heap( 4847): Grow heap (frag case) to 11.059MB for 54576-byte allocation
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
,I/dalvikvm-heap( 4847): Grow heap (frag case) to 11.111MB for 82886-byte allocation
,I/dalvikvm-heap( 4847): Grow heap (frag case) to 11.110MB for 55816-byte allocation
,I/dalvikvm-heap( 4847): Grow heap (frag case) to 11.145MB for 72402-byte allocation
,D/libc    ( 4847): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
D/libc    ( 4847): [NET] getaddrinfo-,err=8
D/libc    ( 4847): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    ( 4847): [NET] getaddrinfo-, 1
,D/libc    ( 4847): [NET] getaddrinfo_proxy+
D/libc    (  360): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    (  360): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  360): [NET] +++++ res_nsend xid =8a6e +++++
D/libc    (  360): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  360): [NET] NOT IN CACHE
,D/libc    (  360): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 36
D/libc    (  360): [NET]res_nsend:resplen=93
D/libc    (  360): [NET]res_queryN: exit 3, ancount=3
D/libc    (  360): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  360): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4847): [NET] getaddrinfo_proxy-, success
I/global  ( 4847): call createSocket() return a new socket.
D/libc    ( 4847): [NET] getaddrinfo+,hn 11(0x33312e31332e38),sn(),family 0,flags 4
,D/libc    ( 4847): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4847): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
,D/libc    ( 4847): [NET] getaddrinfo-,err=8
,D/PMS     (  904): acquireWL(4261f830): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 4847 10026 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
,D/CaptivePortalTracker(  904): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  904): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  904): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,W/ActivityManager(  904): Activity destroy timeout for ActivityRecord{41b69c68 u0 com.test.thalitest/.MainActivity t2 f}
,I/global  ( 4847): I/O error closing connection
I/global  ( 4847): java.net.SocketException: Socket is closed
I/global  ( 4847): 	at java.net.Socket.checkOpenAndCreate(Socket.java:672)
I/global  ( 4847): 	at java.net.Socket.getSoLinger(Socket.java:435)
I/global  ( 4847): 	at com.android.org.conscrypt.OpenSSLSocketImplWrapper.getSoLinger(OpenSSLSocketImplWrapper.java:156)
I/global  ( 4847): 	at org.apache.http.impl.conn.tsccm.AbstractConnPool.closeConnection(AbstractConnPool.java:328)
I/global  ( 4847): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteEntry(ConnPoolByRoute.java:530)
I/global  ( 4847): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteClosedConnections(ConnPoolByRoute.java:653)
I/global  ( 4847): 	at org.apache.http.impl.conn.tsccm.ThreadSafeClientConnManager.closeIdleConnections(ThreadSafeClientConnManager.java:295)
I/global  ( 4847): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager.b(FbClientConnManager.java:316)
I/global  ( 4847): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager$CloseIdleConnectionsRunnable.run(FbClientConnManager.java:327)
I/global  ( 4847): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
I/global  ( 4847): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
I/global  ( 4847): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
I/global  ( 4847): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
I/global  ( 4847): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
I/global  ( 4847): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
I/global  ( 4847): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
I/global  ( 4847): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
I/global  ( 4847): 	at java.lang.Thread.run(Thread.java:864)
,W/IdleConnectionHandler( 4847): Removing a connection that never existed!
D/PMS     (  904): releaseWL(4261f830): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 null
,I/ActivityManager(  904): Waited long enough for: ServiceRecord{42f0b6d0 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  904): acquireWL(44109f00): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1502 10028 null
D/libc    ( 1502): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1502): [NET] getaddrinfo-,err=8
D/libc    ( 1502): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1502): [NET] getaddrinfo-, 1
,D/libc    ( 1502): [NET] getaddrinfo_proxy+
D/libc    (  360): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  360): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  360): [NET] +++++ res_nsend xid =df35 +++++
,D/libc    (  360): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  360): [NET]res_queryN: exit 3, ancount=2
D/libc    (  360): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  360): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1502): [NET] getaddrinfo_proxy-, success
D/PMS     (  904): acquireWL(4362f468): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1502 10028 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1502/10028)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1502/10028)
D/PMS     (  904): releaseWL(4362f468): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/libc    ( 1502): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1502): [NET] getaddrinfo-,err=8
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1502/10028)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1502/10028)
D/PMS     (  904): acquireWL(437b3ab0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1502 10028 null
D/PMS     (  904): releaseWL(437b3ab0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  904): reportInetCondition for net 1, percentage: 0 by  (1502/10028)
D/ConnectivityService(  904): handleInetConditionChange: net=1, condition=0,mActiveDefaultNetwork=1
D/ConnectivityService(  904): handleInetConditionChange: starting a change hold
D/PMS     (  904): releaseWL(44109f00): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1502/10028)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1502/10028)
,D/PMS     (  904): acquireWL(42581d38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1545): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  904): releaseWL(42581d38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=99
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42ab44b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42ab44b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=99
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1545): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:2 level:99 unsupport:false plugged:true
,D/ConnectivityService(  904): handleInetConditionHoldEnd: net=1, condition=0, published condition=0
,D/ConnectivityService(  904): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=12 [72][9][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=0 [0][0][0]
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1481): service - mHandler: update timezone
,D/AutoSetting( 1465): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  904): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1465): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  904): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1465): service - onCreate()
D/AutoSetting( 1465): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1465): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
V/NotificationService(  904): batLight: plugged
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c80000
D/qdlights(  904): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
,D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3,
D/DotMatrix( 1545): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1545): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1465): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1465): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1465): service - mHandler: update timezone
,D/AutoSetting( 1465): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1465): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1465): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1465): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1545): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1545): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1118): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{41d18160 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1118): com.htc.htclocationservice 1 8 2 11
,D/AutoSetting( 1481): service - handleMessage() stop self
,D/AutoSetting( 1481): service - onDestroy() END
,D/AutoSetting( 1481): service - handleMessage() quit looper
,D/PMS     (  904): acquireWL(43cc7018): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10028}
,V/AlarmManager(  904): sending alarm PendingIntent{43d0e9a0: PendingIntentRecord{42655d60 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=139431, Int=0
,V/AlarmManager(  904): sending alarm PendingIntent{4242d8f0: PendingIntentRecord{4242d870 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142121, Int=0
,D/GpsLocationProvider(  904): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  904): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  904): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  904): acquireWL(4269b6b8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 904 1000 null
D/PMS     (  904): releaseWL(43cc7018): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  904): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-,err=8
D/libc    (  904): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  904): [NET] getaddrinfo-, 1
,D/libc    (  904): [NET] getaddrinfo_proxy+
D/libc    (  360): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  360): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  360): [NET] +++++ res_nsend xid =a25 +++++
D/libc    (  360): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  360): [NET] NOT IN CACHE
,D/libc    (  360): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  360): [NET]res_nsend:resplen=238
D/libc    (  360): [NET]res_queryN: exit 3, ancount=10
D/libc    (  360): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  360): [NET] getaddrinfo-, SUCCESS
D/libc    (  904): [NET] getaddrinfo_proxy-, success
I/global  (  904): call createSocket() return a new socket.
D/libc    (  904): [NET] getaddrinfo+,hn 12(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  904): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  904): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  904): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  904):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  904): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/Process (  904): killProcessQuiet, pid=4276
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4276:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 4276
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  904): releaseWL(4269b6b8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/ActivityManager(  904): Waited long enough for: ServiceRecord{423c43a8 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  904): acquireWL(423546f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{423974d0: PendingIntentRecord{423e3038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=166061, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(423546f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/AutoSetting( 1465): service - handleMessage() stop self
,D/AutoSetting( 1465): service - onDestroy() END
,D/AutoSetting( 1465): service - handleMessage() quit looper
,D/Process (  904): killProcessQuiet, pid=4168
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4168:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 4168
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/TelephonyReceiver( 1245): switchBindHtcMsgCursor: null
,D/PMS     (  904): acquireWL(41b50848): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/PMS     (  904): releaseWL(41b50848): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1545): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=99
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(4309c7f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): releaseWL(4309c7f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HeadsetPhoneState( 1570): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HtcPowerSaver(  904): updateBatteryInfo
V/NotificationService(  904): batLight: Full, plugged
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c800
D/qdlights(  904): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
,I/HtcPowerSaver(  904): >> updateStatus
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1545): [EventService] reorderNotification, total:0
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1545): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
W/ContextImpl( 5030): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,D/TetherSettings( 4146): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 4146): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4146): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4146): Cust_ConnectToPC   : spcsc>false
D/        ( 4146): Cust_ConnectToPC   : IPT>true
,D/        ( 4146): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4146): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4146): Index of the first 1 = -1
W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
W/ContextImpl( 4146): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/Settings( 4146): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4146): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4146): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4146): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 4146): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,D/SmartNS_Utility( 4146): [ACC]android_networking:tethering_guard_support=false
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(440f8308): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{423974d0: PendingIntentRecord{423e3038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=226061, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(440f8308): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(4401b690): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10026}
,V/AlarmManager(  904): sending alarm PendingIntent{43620438: PendingIntentRecord{428288f8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=226106, Int=0
,I/ActivityManager(  904): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=5083 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  904): sending alarm PendingIntent{4248b4e0: PendingIntentRecord{4257b788 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452008807068, Int=10800000
,D/PMS     (  904): releaseWL(4401b690): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.aurora (5083/10047)
,D/Process (  904): killProcessQuiet, pid=4726
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4726:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 4726
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2225/10028)
,W/GA-SERVICE( 2225): Thread[Thread-188,5,main]: hit:_gmsv=1-5089038&ul=en-gb&sr=720x1184&ht=1452008628985&a=1118118847&sc=start&AppUID=10151&aid=com.google.android.apps.magazines&cid=555235a2-953e-473b-8151-55e062e9c995&av=3.2.1&cd16=Ignoring+sync+request+for+non-current+account&v=1&t=appview&an=Google+Play+Newsstand&cd11=false&tid=UA-32428711-6&_u=.nOQKSTB&_v=ma1b6&cd=Debug&qt=192993&z=111
,W/GA-SERVICE( 2225): Thread[Thread-188,5,main]: hit:_gmsv=1-5089038&ev=0&ul=en-gb&sr=720x1184&ht=1452008628986&a=1051320804&AppUID=10151&aid=com.google.android.apps.magazines&ea=Sync+Skipped&cid=555235a2-953e-473b-8151-55e062e9c995&av=3.2.1&ec=Debug&v=1&t=event&el=&an=Google+Play+Newsstand&tid=UA-32428711-6&_u=.C&_v=ma1b6&cd=Debug&qt=192992&z=112
,D/libc    ( 2225): [NET] getaddrinfo+,hn 24(0x73736c2e676f6f),sn(),family 0,flags 4
,D/libc    ( 2225): [NET] getaddrinfo-,err=8
D/libc    ( 2225): [NET] getaddrinfo+,hn 24(0x73736c2e676f6f),sn(),family 0,flags 1024
D/libc    ( 2225): [NET] getaddrinfo-, 1
,D/libc    ( 2225): [NET] getaddrinfo_proxy+
D/libc    (  360): [NET] getaddrinfo+,hn 24(0x73736c2e676f6f),sn(),family 0,flags 1024
D/libc    (  360): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  360): [NET] +++++ res_nsend xid =c08b +++++
D/libc    (  360): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  360): [NET] NOT IN CACHE
,D/libc    (  360): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  360): [NET]res_nsend:resplen=102
D/libc    (  360): [NET]res_queryN: exit 3, ancount=2
D/libc    (  360): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  360): [NET] getaddrinfo-, SUCCESS
D/libc    ( 2225): [NET] getaddrinfo_proxy-, success
I/global  ( 2225): call createSocket() return a new socket.
,D/libc    ( 2225): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 2225): [NET] getaddrinfo-, SUCCESS
,D/PMS     (  904): acquireWL(431169d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10026}
,V/AlarmManager(  904): sending alarm PendingIntent{4401b7f0: PendingIntentRecord{428288f8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=229288, Int=0
,D/PMS     (  904): releaseWL(431169d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  904): acquireWL(440ef410): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(440ef410): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  904): acquireWL(4319d2a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
V/AlarmManager(  904): sending alarm PendingIntent{423974d0: PendingIntentRecord{423e3038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=286061, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4319d2a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(42828b18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42828b18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(440a6f88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{423974d0: PendingIntentRecord{423e3038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=346062, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(440a6f88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1502): GoogleAccountDataService.getToken()
,W/GLSActivity( 1502): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1502): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1502): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1545): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1545): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1118): com.google.android.gms (false,0)
,W/GLSActivity( 1502): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1502): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1502): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1502): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1502): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1502): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1502): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1502): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{41eff678 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/PlayEventLogger( 4446): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4446): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4446): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4446): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4446): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4446): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4446): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4446): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews.Performance( 1118): com.google.android.gms 2 18 6 12
,D/libc    ( 4446): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4446): [NET] getaddrinfo-,err=8
D/libc    ( 4446): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4446): [NET] getaddrinfo-, 1
,D/libc    ( 4446): [NET] getaddrinfo_proxy+
D/libc    (  360): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  360): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  360): [NET] +++++ res_nsend xid =2973 +++++
D/libc    (  360): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  360): [NET] NOT IN CACHE
,D/libc    (  360): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 61
D/libc    (  360): [NET]res_nsend:resplen=87
D/libc    (  360): [NET]res_queryN: exit 3, ancount=2
D/libc    (  360): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  360): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4446): [NET] getaddrinfo_proxy-, success
I/global  ( 4446): call createSocket() return a new socket.
D/libc    ( 4446): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4446): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4446): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4446): [NET] getaddrinfo-,err=8
,D/PMS     (  904): acquireWL(4389bd78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4389bd78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  904): acquireWL(4380ad20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{423974d0: PendingIntentRecord{423e3038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=406061, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4380ad20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process ( 4777): killProcess, pid=4777
,D/Process ( 4777): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/InputMethodManagerService(  904): Disable input method client, pid=4777
,I/ActivityManager(  904): Recipient 4777
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Process com.test.thalitest (pid 4777) has died.
I/WindowState(  904): WIN DEATH: Window{423eff10 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  904): Client connection lost with reason: 4
,D/PMS     (  904): acquireWL(42628e58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10026}
,V/AlarmManager(  904): sending alarm PendingIntent{423f29a8: PendingIntentRecord{42570d20 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=409030, Int=300000
,D/PMS     (  904): releaseWL(42628e58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(430aba70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(430aba70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(43bb1fa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{423974d0: PendingIntentRecord{423e3038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=466061, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43bb1fa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  904): acquireWL(4385a078): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4385a078): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  904): acquireWL(429dadf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{423974d0: PendingIntentRecord{423e3038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=526062, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(429dadf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(4406e948): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4406e948): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(42650e28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
V/AlarmManager(  904): sending alarm PendingIntent{423974d0: PendingIntentRecord{423e3038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=586061, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42650e28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(4380afa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4380afa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  350): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1245): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1245): mDeleteTask = null, bDeleting = false
D/ContactMessageStore( 1245): start background delete task...
D/AccFlag ( 1245): sku_id=99
,D/ContactMessageStore( 1245): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1245): size: 0 , 0
,D/ContactMessageStore( 1245): Background delete complete
,D/PMS     (  904): acquireWL(43f23758): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{423974d0: PendingIntentRecord{423e3038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=646061, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43f23758): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(438256c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(438256c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(426f9a78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10073}
,V/AlarmManager(  904): sending alarm PendingIntent{44087f98: PendingIntentRecord{426ad088 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452009282117, Int=0
,D/PMS     (  904): releaseWL(426f9a78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,W/GLSUser ( 1502): GoogleAccountDataService.getToken()
,W/GLSActivity( 1502): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1502): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1502): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1502): GoogleAccountDataService.getToken()
,W/GLSActivity( 1502): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1502): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1502): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4446): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4446): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,W/GLSUser ( 1502): GoogleAccountDataService.getToken()
,W/GLSActivity( 1502): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1502): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1502): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4446): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4446): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4446): [1] DailyHygiene.reschedule: Scheduling new run in 32 minutes (failures=2)
,D/PMS     (  904): acquireWL(43567680): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10073}
,V/AlarmManager(  904): sending alarm PendingIntent{42586d38: PendingIntentRecord{43a991b8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452009297350, Int=0
,D/PMS     (  904): releaseWL(43567680): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/Finsky  ( 4446): [1] 5.onFinished: Installation state replication succeeded.
,D/PMS     (  904): acquireWL(43072450): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{423974d0: PendingIntentRecord{423e3038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=706061, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43072450): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42ab5000): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10026}
,V/AlarmManager(  904): sending alarm PendingIntent{423f29a8: PendingIntentRecord{42570d20 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=709030, Int=300000
,D/PMS     (  904): releaseWL(42ab5000): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  904): acquireWL(42aa5a58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42aa5a58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(44079948): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(44079948): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
,I/HtcPowerSaver(  904): >> updateStatus
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1545): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43131888): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{423974d0: PendingIntentRecord{423e3038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=766061, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43131888): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43149bc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
V/AlarmManager(  904): sending alarm PendingIntent{41e67408: PendingIntentRecord{42493e00 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=791706, Int=0
D/ConnectivityService(  904): Sampling interval elapsed, updating statistics ..
,D/PMS     (  904): releaseWL(43149bc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  904): Done.
,D/ConnectivityService(  904): Setting timer for 720seconds
,D/PMS     (  904): acquireWL(4406eff8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4406eff8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(4419cd58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{423974d0: PendingIntentRecord{423e3038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=826061, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4419cd58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42649cb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42649cb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(426ec148): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{423974d0: PendingIntentRecord{423e3038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=886061, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(426ec148): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(440d93f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(440d93f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(4288d508): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{423974d0: PendingIntentRecord{423e3038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=946061, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4288d508): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(440dd790): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(440dd790): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(44158d88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{423974d0: PendingIntentRecord{423e3038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1006062, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(44158d88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(441a60f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{426774e0: PendingIntentRecord{4283ff18 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452009527745, Int=900000
,V/AlarmManager(  904): sending alarm PendingIntent{42399ad8: PendingIntentRecord{42533a98 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1452009603278, Int=0
,W/ContextImpl( 5030): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 5030): call getInstance()
,D/SmartSyncUtils( 5030): isEpsOn(), nState = 0
D/PMS     (  904): acquireWL(43132df0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5030 1000 null
,D/PowerUsageList:PowerUsageHelper( 5030): MY_DEBUG = false
,D/SmartSyncScreenOnOffTimeReceiver( 5030): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 5030): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 2, nStart = 1, nEnd = 2, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 5030): AlarmOnTime = -1
,D/PMS     (  904): releaseWL(441a60f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/SmartSyncScreenOnOffTimeReceiver( 5030): SettingOnTime = 1452042000000, randomSettingOnTime = 1452040120000
D/SmartSyncScreenOnOffTimeReceiver( 5030): SettingOffTime = 1452038400000, randomSettingOffTime = 1452038839000
D/SmartSyncScreenOnOffTimeReceiver( 5030): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 5030): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 5030): bNightModeTurnOffOnce = false
D/PMS     (  904): releaseWL(43132df0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,D/PMS     (  904): acquireWL(423d1e88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(423d1e88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(43ccfd88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
V/AlarmManager(  904): sending alarm PendingIntent{423974d0: PendingIntentRecord{423e3038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1066061, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43ccfd88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(41ff5c30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(41ff5c30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(441bd450): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{423974d0: PendingIntentRecord{423e3038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1126061, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(441bd450): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42548338): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42548338): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(43094ed8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{423974d0: PendingIntentRecord{423e3038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1186061, Int=0
I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43094ed8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(4384d238): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4384d238): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  350): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  904): acquireWL(42398e20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
V/AlarmManager(  904): sending alarm PendingIntent{423974d0: PendingIntentRecord{423e3038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1246061, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42398e20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42701938): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42701938): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
,D/libc    ( 4847): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 4
D/libc    ( 4847): [NET] getaddrinfo-,err=8
D/libc    ( 4847): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 1024
D/libc    ( 4847): [NET] getaddrinfo-, 1
,D/libc    ( 4847): [NET] getaddrinfo_proxy+
D/libc    (  360): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 1024
D/libc    (  360): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  360): [NET] +++++ res_nsend xid =c60c +++++
D/libc    (  360): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  360): [NET] NOT IN CACHE
,D/libc    (  360): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 43
,D/libc    (  360): [NET]res_nsend:resplen=74
D/libc    (  360): [NET]res_queryN: exit 3, ancount=2
,D/libc    (  360): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  360): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4847): [NET] getaddrinfo_proxy-, success
,I/global  ( 4847): call createSocket() return a new socket.
D/libc    ( 4847): [NET] getaddrinfo+,hn 10(0x33312e31332e38),sn(),family 0,flags 4
,D/libc    ( 4847): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4847): [NET] getaddrinfo+,hn 16(0x6170692e666163),sn(),family 0,flags 4
,D/libc    ( 4847): [NET] getaddrinfo-,err=8
,D/PMS     (  904): acquireWL(4211b328): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 4847 10026 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4847/10026)
,I/global  ( 4847): I/O error closing connection
I/global  ( 4847): java.net.SocketException: Socket is closed
I/global  ( 4847): 	at java.net.Socket.checkOpenAndCreate(Socket.java:672)
I/global  ( 4847): 	at java.net.Socket.getSoLinger(Socket.java:435)
I/global  ( 4847): 	at com.android.org.conscrypt.OpenSSLSocketImplWrapper.getSoLinger(OpenSSLSocketImplWrapper.java:156)
I/global  ( 4847): 	at org.apache.http.impl.conn.tsccm.AbstractConnPool.closeConnection(AbstractConnPool.java:328)
I/global  ( 4847): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteEntry(ConnPoolByRoute.java:530)
I/global  ( 4847): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteClosedConnections(ConnPoolByRoute.java:653)
I/global  ( 4847): 	at org.apache.http.impl.conn.tsccm.ThreadSafeClientConnManager.closeIdleConnections(ThreadSafeClientConnManager.java:295)
I/global  ( 4847): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager.b(FbClientConnManager.java:316)
I/global  ( 4847): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager$CloseIdleConnectionsRunnable.run(FbClientConnManager.java:327)
I/global  ( 4847): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
I/global  ( 4847): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
I/global  ( 4847): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
I/global  ( 4847): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
I/global  ( 4847): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
I/global  ( 4847): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
I/global  ( 4847): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
I/global  ( 4847): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
I/global  ( 4847): 	at java.lang.Thread.run(Thread.java:864)
,W/IdleConnectionHandler( 4847): Removing a connection that never existed!
D/PMS     (  904): releaseWL(4211b328): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 null
,D/PMS     (  904): acquireWL(41e70df0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{423974d0: PendingIntentRecord{423e3038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1306061, Int=0
I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(41e70df0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(440f77e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(440f77e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
,I/HtcPowerSaver(  904): >> updateStatus
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1545): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42e2c530): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42e2c530): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(4266cb00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
V/AlarmManager(  904): sending alarm PendingIntent{423974d0: PendingIntentRecord{423e3038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1366061, Int=0
I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4266cb00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(424d6dc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(424d6dc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(423dee58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1545): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): releaseWL(423dee58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42809588): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{423974d0: PendingIntentRecord{423e3038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1426061, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42809588): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(425e3850): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(425e3850): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1545): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42e2c6d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42e2c6d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(428658f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
V/AlarmManager(  904): sending alarm PendingIntent{423974d0: PendingIntentRecord{423e3038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1486061, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(428658f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42873818): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42873818): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(43bb5810): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43bb5810): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
,I/HtcPowerSaver(  904): >> updateStatus
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1545): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42918680): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{423974d0: PendingIntentRecord{423e3038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1546061, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42918680): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(4249ad38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4249ad38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1545): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(44103f90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
D/ConnectivityService(  904): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  904): sending alarm PendingIntent{41e67408: PendingIntentRecord{42493e00 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1511729, Int=0
,D/ConnectivityService(  904): Done.
,D/ConnectivityService(  904): Setting timer for 720seconds
,I/ActivityManager(  904): Start proc com.htc.cs.dm for service com.htc.cs.dm/com.htc.cs.util.workflow.WorkflowService: pid=5122 uid=10098 gids={50098, 3003, 5012}
,V/AlarmManager(  904): sending alarm PendingIntent{42012e30: PendingIntentRecord{4278f488 com.htc.cs.dm startService}}, i=com.htc.cs.action.EXECUTE_WORKFLOW, t=1, cnt=1, w=1452009868633, Int=0
,V/AlarmManager(  904): sending alarm PendingIntent{426379d0: PendingIntentRecord{4265dcf8 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1452010194521, Int=1800000
,D/PMS     (  904): acquireWL(43825b08): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2225 10028 null
,D/PMS     (  904): acquireWL(423ede20): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2225 10028 null
,D/PMS     (  904): releaseWL(44103f90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,I/EventLogService( 2225): Aggregate from 1452008700762 (log), 1452008394459 (data)
D/PMS     (  904): releaseWL(43825b08): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
,I/DeviceManagement( 5122): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=5122 dbg=false s=true
,I/DeviceManagement( 5122): WorkflowService: Starting workflow service
,I/DeviceManagement( 5122): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.UpdateWorkflow@41b85e48] args=[Bundle[mParcelledData.dataSize=60]]
I/DeviceManagement( 5122): UpdateWorkflow: ==================================================
I/DeviceManagement( 5122): UpdateWorkflow: TTL update...
,I/DeviceManagement( 5122): UpdateWorkflow: ==================================================
,I/DeviceManagement( 5122): ModelRegistry: Loading model meta data from resources...
D/PMS     (  904): releaseWL(423ede20): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,I/DeviceManagement( 5122): SessionStateController: Checking invariants...
,I/DeviceManagement( 5122): BackgroundController: Invariants are unchanged.
,I/DeviceManagement( 5122): SessionStateController: Checking invariants...
,I/DeviceManagement( 5122): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,I/DeviceManagement( 5122): Perf: *** Cache update - start...
I/DeviceManagement( 5122): Perf: *** Enabled app cache update - start...
,I/DeviceManagement( 5122): EnabledAppController: *** Updating enabled app database...
I/DeviceManagement( 5122): Perf: *** Enabled app cache update - complete: 1 ms
I/DeviceManagement( 5122): Perf: *** Config cache update - start...
I/DeviceManagement( 5122): ConfigCacheController: *** Updating config cache...
,I/DeviceManagement( 5122): ConfigCacheController: *** Updating stale config cache entries...
,W/dalvikvm( 5122): VFY: unable to resolve static method 10661: Lcom/sun/net/httpserver/HttpServer;.create (Ljava/net/InetSocketAddress;I)Lcom/sun/net/httpserver/HttpServer;
,W/dalvikvm( 5122): VFY: unable to resolve virtual method 10666: Lcom/sun/net/httpserver/HttpServer;.stop (I)V
,W/dalvikvm( 5122): Link of class 'Lorg/restlet/engine/connector/HttpServerHelper$1;' failed
,W/System.err( 5122): Starting the internal HTTP client
,I/DeviceManagement( 5122): ConfigCacheController: Getting config update from server: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.launcher/versions/b354e2de-d3af-4a3f-b5dc-8239e0d5da72/cid/MDoxNToyMDE1LTEyLTI0VDA5OjIwOjU2LjA5NFo
,I/DeviceManagement( 5122): DeviceClientResource: Active network...
I/DeviceManagement( 5122):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.cs.dm (5122/10098)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.cs.dm (5122/10098)
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.cs.dm (5122/10098)
D/BuildInfo( 5122): Created new instance: com.htc.cs.lib.hms.BuildInfo@41de61b0
I/DeviceManagement( 5122): Version: Hello, this is: cs-lib-hms/1.3.4.6 (release)
,E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1178): environment dirty rate=11 [207][24][0]
,D/libc    ( 5122): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 5122): [NET] getaddrinfo-, 1
,D/libc    ( 5122): [NET] getaddrinfo_proxy+
D/libc    (  360): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  360): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  360): [NET] getaddrinfo-, SUCCESS
D/libc    (  360): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  360): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 5122): [NET] getaddrinfo_proxy-, success
,D/libc    ( 5122): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 5122): [NET] getaddrinfo-,err=8
D/libc    ( 5122): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 5122): [NET] getaddrinfo-, 1
,D/libc    ( 5122): [NET] getaddrinfo_proxy+
D/libc    (  360): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  360): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  360): [NET] +++++ res_nsend xid =777a +++++
D/libc    (  360): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  360): [NET] NOT IN CACHE
,D/libc    (  360): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  360): [NET]res_nsend:resplen=204
D/libc    (  360): [NET]res_queryN: exit 3, ancount=4
D/libc    (  360): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  360): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 5122): [NET] getaddrinfo_proxy-, success
,I/DeviceManagement( 5122): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 5122): ServiceClientResourceController: handleDirectives: []
,I/DeviceManagement( 5122): DeviceClientResourceController: handleDirectives: []
W/dalvikvm( 5122): VFY: unable to find class referenced in signature (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;)
,W/dalvikvm( 5122): VFY: unable to resolve virtual method 8166: Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;.schemaFor (Ljava/lang/Class;)Lcom/fasterxml/jackson/dataformat/csv/CsvSchema;
E/dalvikvm( 5122): Could not find class 'com.fasterxml.jackson.dataformat.smile.SmileFactory', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectMapper
,W/dalvikvm( 5122): VFY: unable to resolve new-instance 808 (Lcom/fasterxml/jackson/dataformat/smile/SmileFactory;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
W/dalvikvm( 5122): VFY: unable to resolve static method 11799: Ljavax/xml/stream/XMLInputFactory;.newFactory ()Ljavax/xml/stream/XMLInputFactory;
E/dalvikvm( 5122): Could not find class 'com.fasterxml.jackson.dataformat.yaml.YAMLFactory', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectMapper
W/dalvikvm( 5122): VFY: unable to resolve new-instance 811 (Lcom/fasterxml/jackson/dataformat/yaml/YAMLFactory;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 5122): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvFactory', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectMapper
W/dalvikvm( 5122): VFY: unable to resolve new-instance 805 (Lcom/fasterxml/jackson/dataformat/csv/CsvFactory;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 5122): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvMapper', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectReader
W/dalvikvm( 5122): VFY: unable to resolve check-cast 806 (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 5122): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvMapper', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectWriter
,W/dalvikvm( 5122): VFY: unable to resolve check-cast 806 (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 5122): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvMapper', referenced from method org.restlet.ext.jackson.JacksonRepresentation.getCsvSchema
W/dalvikvm( 5122): VFY: unable to resolve check-cast 806 (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
W/dalvikvm( 5122): VFY: unable to find class referenced in signature (Lcom/fasterxml/jackson/dataformat/csv/CsvSchema;)
,W/dalvikvm( 5122): VFY: unable to find class referenced in signature (Lcom/fasterxml/jackson/dataformat/csv/CsvSchema;)
I/System.out( 5122): isCompatible false
I/System.out( 5122): createObjectMapper
I/System.out( 5122): isCompatible false
I/System.out( 5122): isCompatible false
I/System.out( 5122): isCompatible false
I/System.out( 5122): isCompatible false
I/System.out( 5122): isCompatible false
I/System.out( 5122): isCompatible false
,I/System.out( 5122): isCompatible false
,I/DeviceManagement( 5122): ConfigCacheController: Getting config update from server: appID=com.htc.cs.pushclient, versionKey=c0b07203-b6aa-4cf1-944f-7ae27c536a6b, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.cs.pushclient/versions/c0b07203-b6aa-4cf1-944f-7ae27c536a6b/cid/MDoxOjIwMTMtMTItMjBUMDk6MzY6NTguNjI2Wg
,I/DeviceManagement( 5122): DeviceClientResource: Active network...
I/DeviceManagement( 5122):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.cs.dm (5122/10098)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.cs.dm (5122/10098)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.cs.dm (5122/10098)
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1178): environment dirty rate=0 [11][0][0]
D/libc    ( 5122): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 5122): [NET] getaddrinfo-, 1
D/libc    ( 5122): [NET] getaddrinfo_proxy+
D/libc    (  360): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  360): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  360): [NET] getaddrinfo-, SUCCESS
D/libc    (  360): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  360): [NET] getaddrinfo-, SUCCESS
D/libc    ( 5122): [NET] getaddrinfo_proxy-, success
D/libc    ( 5122): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 5122): [NET] getaddrinfo-,err=8
D/libc    ( 5122): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 5122): [NET] getaddrinfo-, 1
D/libc    ( 5122): [NET] getaddrinfo_proxy+
D/libc    (  360): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  360): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  360): [NET] +++++ res_nsend xid =1381 +++++
D/libc    (  360): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  360): [NET]res_queryN: exit 3, ancount=4
D/libc    (  360): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  360): [NET] getaddrinfo-, SUCCESS
D/libc    ( 5122): [NET] getaddrinfo_proxy-, success
,I/DeviceManagement( 5122): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 5122): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 5122): DeviceClientResourceController: handleDirectives: []
I/System.out( 5122): isCompatible false
I/System.out( 5122): createObjectMapper
I/System.out( 5122): isCompatible false
,I/System.out( 5122): isCompatible false
I/System.out( 5122): isCompatible false
I/System.out( 5122): isCompatible false
I/System.out( 5122): isCompatible false
I/System.out( 5122): isCompatible false
,I/System.out( 5122): isCompatible false
,I/DeviceManagement( 5122): ConfigCacheController: Getting config update from server: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.backup/versions/f14176fb-9327-4d08-a3c6-5749fcce54ec/cid/MDo0OjIwMTUtMDQtMjNUMjA6NTQ6MDcuMzczWg
,I/DeviceManagement( 5122): DeviceClientResource: Active network...
I/DeviceManagement( 5122):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1178): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.cs.dm (5122/10098)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.cs.dm (5122/10098)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.cs.dm (5122/10098)
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1178): nl80211: survey data missing!
E/wpa_supplicant( 1178): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1178): environment dirty rate=0 [8][0][0]
D/libc    ( 5122): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 5122): [NET] getaddrinfo-, 1
D/libc    ( 5122): [NET] getaddrinfo_proxy+
D/libc    (  360): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  360): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  360): [NET] getaddrinfo-, SUCCESS
D/libc    (  360): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  360): [NET] getaddrinfo-, SUCCESS
D/libc    ( 5122): [NET] getaddrinfo_proxy-, success
D/libc    ( 5122): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 5122): [NET] getaddrinfo-,err=8
D/libc    ( 5122): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 5122): [NET] getaddrinfo-, 1
D/libc    ( 5122): [NET] getaddrinfo_proxy+
D/libc    (  360): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  360): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  360): [NET] +++++ res_nsend xid =c349 +++++
D/libc    (  360): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  360): [NET]res_queryN: exit 3, ancount=4
D/libc    (  360): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  360): [NET] getaddrinfo-, SUCCESS
D/libc    ( 5122): [NET] getaddrinfo_proxy-, success
,I/DeviceManagement( 5122): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 5122): ServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 5122): DeviceClientResourceController: handleDirectives: []
I/System.out( 5122): isCompatible false
I/System.out( 5122): createObjectMapper
,I/System.out( 5122): isCompatible false
I/System.out( 5122): isCompatible false
I/System.out( 5122): isCompatible false
I/System.out( 5122): isCompatible false
I/System.out( 5122): isCompatible false
,I/System.out( 5122): isCompatible false
,I/System.out( 5122): isCompatible false
,I/DeviceManagement( 5122): ConfigCacheController: *** Update config cache: updating 3 entries...
,I/DeviceManagement( 5122): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, statusCode=0, authCode=0>
,I/DeviceManagement( 5122): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.cs.pushclient, versionKey=c0b07203-b6aa-4cf1-944f-7ae27c536a6b, statusCode=0, authCode=0>
,I/DeviceManagement( 5122): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, statusCode=0, authCode=0>
,I/DeviceManagement( 5122): ConfigCacheController: No changes need to be broadcasted.
,I/DeviceManagement( 5122): AlarmController: Scheduling TTL alarm for: 2016.01.06 at 17:09:57.244 CET (due to: com.htc.launcher)
,I/DeviceManagement( 5122): Perf: *** Config cache update - complete: 2282 ms
,I/DeviceManagement( 5122): Perf: *** Cache update - complete: 2286 ms
,I/DeviceManagement( 5122): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.UpdateWorkflow@41b85e48]
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=2, flag=1, pid=5122, uid=10098, userID:0
I/DeviceManagement( 5122): WorkflowService: Stopping workflow service
,D/Process (  904): killProcessQuiet, pid=4740
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4740:com.android.settings:remote/1000 (adj 15): empty #17
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0,
,I/ActivityManager(  904): Recipient 4740
,D/PMS     (  904): acquireWL(4268cbf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{423974d0: PendingIntentRecord{423e3038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1606061, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4268cbf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(4382a278): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4382a278): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/DotMatrix( 1545): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/PowerUI ( 1118): closing low battery warning: level=100
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43800e48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43800e48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(44156bf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{423974d0: PendingIntentRecord{423e3038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1666061, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(44156bf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(438859a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(438859a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(44153e60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(44153e60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1545): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(430e1e90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{423974d0: PendingIntentRecord{423e3038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1726061, Int=0
I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(430e1e90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(4418e6f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4418e6f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1545): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(426bd1d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(426bd1d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1545): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43bb1c38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
V/AlarmManager(  904): sending alarm PendingIntent{423974d0: PendingIntentRecord{423e3038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1786061, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43bb1c38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,D/PMS     (  904): acquireWL(43fa0ac0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43fa0ac0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1545): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1118): closing low battery warning: level=100
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  350): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  904): acquireWL(425f6d08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
V/AlarmManager(  904): sending alarm PendingIntent{423974d0: PendingIntentRecord{423e3038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1846061, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,I/ProcessStatsService(  904): Prepared write state in 42ms
,I/ProcessStatsService(  904): Prepared write state in 24ms
,I/ProcessStatsService(  904): Prepared write state in 11ms
,D/PMS     (  904): releaseWL(425f6d08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  904): Pruning old procstats: /data/system/procstats/state-2016-01-04-23-40-00.bin
,D/PMS     (  904): acquireWL(43a31a48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43a31a48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(43e21908): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): releaseWL(43e21908): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1545): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42861850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{423974d0: PendingIntentRecord{423e3038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1906061, Int=0
,D/Process (  904): killProcessQuiet, pid=4821
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
I/ActivityManager(  904): Killing 4821:com.htc.mms.backupagent/u0a77 (adj 15): empty for 1803s
,D/PMS     (  904): releaseWL(42861850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ActivityManager(  904): Recipient 4821
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 5157): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 5157): ====startRecUseTime====
D/htc.customization.log.level( 5157):  is 
W/CustomizationLogLevel( 5157): Level value is invalid, use default level 2
D/CustomizationManager( 5157):  Read ACC file spent 0.062 (s)
D/CIDMapFileReader( 5157): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5157): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5157): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5157): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 5157): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5157): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 5157): Parsing tag item name = HTC__016
D/CIDMapFileReader( 5157): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5157): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5157): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5157): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 5157): Parsing tag category name = system
I/CustomizationCIDLoader( 5157): Parsing tag category name = application
I/CustomizationCIDLoader( 5157): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5157): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5157): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5157): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5157): Parsing tag category name = Settings
D/CustomizationManager( 5157):  Read CID file spent 0.109 (s)
D/CustomizationManager( 5157):  All configurations done spent 0.109 (s)
W/HtcNativeFlag( 5157): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 5157): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 5157): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 5157): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  904): deletePackageAsUser: pkg=com.test.thalitest, pid=5157, uid=2000 user=0
I/ActivityManager(  904): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
D/Process (  904): killProcessQuiet, pid=1481
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  904): killProcessQuiet, pid=3923
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  904): killProcessQuiet, pid=4910
I/ActivityManager(  904): Killing 1481:com.htc.sense.hsp/u0a53 (adj 15): empty for 1801s
I/ActivityManager(  904): Killing 3923:com.google.android.apps.plus/u0a160 (adj 15): empty for 1802s
I/ActivityManager(  904): Killing 4910:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1802s
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  904): killProcessQuiet, pid=4893
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  904): killProcessQuiet, pid=4877
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  904): killProcessQuiet, pid=4242
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
W/asset   (  904): Copying FileAsset 0x627e6758 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  904): Killing 4893:com.android.chrome/u0a96 (adj 15): empty for 1802s
I/ActivityManager(  904): Killing 4877:com.google.android.setupwizard/u0a78 (adj 15): empty for 1802s
I/ActivityManager(  904): Killing 4242:com.google.android.music:main/u0a154 (adj 15): empty for 1802s
I/ActivityManager(  904): Recipient 4893
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Recipient 3923
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Recipient 4242
D/MediaRouterService(  904): Client com.google.android.music (pid 4242): Died!
I/ActivityManager(  904): Recipient 4877
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/PackageSettings(  904): Skipping PackageSetting{422c8980 com.example.hello/10356} due to missing metadata
E/JavaBinder(  904): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  904): !!! FAILED BINDER TRANSACTION !!!
I/ActivityManager(  904): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
D/DotMatrix( 1545): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1545): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1545): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/acms    ( 1853): Unregistering com.test.thalitest
E/acms    ( 1853): Could not unregister removed application com.test.thalitest
W/GeofencerStateMachine( 1533): Ignoring removeGeofence because network location is disabled.
I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver replacing:false
W/AccTypeManager( 1323): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1323): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  904): acquireWL(42669be0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1533 10028 null
D/PMS     (  904): releaseWL(42669be0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/VoicemailCleanupService( 1295): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  904): Recipient 4910
W/SystemReader( 1256): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "sms"
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Recipient 1481
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
D/AccTypeManager( 1323): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "smsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
D/PackageBroadcastService( 2225): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/Launcher( 1270): Deferring update until onResume
D/Launcher( 1270): waitUntilResume // bindAppsRemoved
I/InputMethodManagerService(  904): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/ActivityManager(  904): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=5171 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
E/ExternalAccountType( 1323): Unsupported attribute readOnly
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mmsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "sms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "smsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/MultiDex( 5171): install
I/MultiDex( 5171): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/ActivityManager(  904): Delaying start of: ServiceRecord{42716ab0 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/MultiDex( 5171): loading existing secondary dex files
I/MultiDex( 5171): load found 1 secondary dex files
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/MultiDex( 5171): install done
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mmsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
D/PhoneApp( 1245): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  904): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=5188 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PeopleContactsSync( 2225): CP2 sync disabled
I/Icing   ( 2225): doRemovePackageData com.test.thalitest
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2225, uid=10028, userID:0
D/PMS     (  904): acquireWL(43cd1148): PARTIAL_WAKE_LOCK  Icing 0x1 2225 10028 null
I/ProviderInstaller( 5171): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
D/PMS     (  904): releaseWL(43cd1148): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  904): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 5188): install
I/MultiDex( 5188): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 5188): loading existing secondary dex files
I/MultiDex( 5188): load found 1 secondary dex files
I/MultiDex( 5188): install done
I/ProviderInstaller( 5188): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Start proc com.htc.sense.hsp for broadcast com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver: pid=5206 uid=10053 gids={50053, 1023, 3003, 5012}
D/PluginProvider( 5206): PluginProvider onCreate
D/PluginProvider( 5206): current plugin count: 19
D/HtcAppUPService( 5206): HtcUPDataProvider onCreate()
W/PackageManager(  904): Unable to load service info ResolveInfo{41da88c0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  904): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  904): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  904): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  904): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  904): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  904): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  904): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  904): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  904): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  904): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  904): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  904): 	at dalvik.system.NativeStart.main(Native Method)
I/[PluginManager]RegisterService( 5206): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5171): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.gms/files
I/[PluginManager]RegisterService( 5206): handle notify Blinkfeed plugin client changed
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (5171/10028)
D/Prism.PackageStateRece_( 1270): action: android.intent.action.PACKAGE_REMOVED
I/IcingCorporaProvider( 3281): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (5171/10028)
I/ActivityManager(  904): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5227 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (5171/10028)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (5171/10028)
D/RemoteDisplayProvider(  904): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  904): start
E/SQLiteDBG( 3281): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x636008e8
W/dalvikvm( 3281): threadid=15: thread exiting with uncaught exception (group=0x41729e30)
E/ActivityManager(  904): App crashed! Process: com.google.android.googlequicksearchbox:search
E/AndroidRuntime( 3281): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 3281): Process: com.google.android.googlequicksearchbox:search, PID: 3281
E/AndroidRuntime( 3281): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/AndroidRuntime( 3281): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 3281): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 3281): 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
E/AndroidRuntime( 3281): 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
E/AndroidRuntime( 3281): 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:562)
E/AndroidRuntime( 3281): 	at cid.d(PG:192)
E/AndroidRuntime( 3281): 	at clo.g(PG:594)
E/AndroidRuntime( 3281): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 3281): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 3281): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 3281): 	at clp.Rl(PG:910)
E/AndroidRuntime( 3281): 	at clr.tL(PG:827)
E/AndroidRuntime( 3281): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 3281): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 3281): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 3281): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 3281): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 3281): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 3281): killProcess, pid=3281
D/Process ( 3281): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  904): Can't write: system_app_crash
E/DropBoxManagerService(  904): java.io.IOException: write failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.write(IoBridge.java:455)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.write(FileOutputStream.java:187)
E/DropBoxManagerService(  904): 	at java.io.BufferedOutputStream.flushInternal(BufferedOutputStream.java:185)
E/DropBoxManagerService(  904): 	at java.io.BufferedOutputStream.flush(BufferedOutputStream.java:85)
E/DropBoxManagerService(  904): 	at java.io.FilterOutputStream.close(FilterOutputStream.java:61)
E/DropBoxManagerService(  904): 	at java.io.BufferedOutputStream.close(BufferedOutputStream.java:152)
E/DropBoxManagerService(  904): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:245)
E/DropBoxManagerService(  904): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  904): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  904): Caused by: libcore.io.ErrnoException: write failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.Posix.writeBytes(Native Method)
E/DropBoxManagerService(  904): 	at libcore.io.Posix.write(Posix.java:202)
E/DropBoxManagerService(  904): 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:197)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.write(IoBridge.java:450)
E/DropBoxManagerService(  904): 	... 8 more
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Recipient 3281
D/MediaRouterService(  904): Client com.google.android.googlequicksearchbox (pid 3281): Died!
I/ActivityManager(  904): Process com.google.android.googlequicksearchbox:search (pid 3281) has died.
D/WifiService(  904): Client connection lost with reason: 4
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 10999ms
E/SQLiteDatabase( 5227): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 5227): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5227): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5227): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5227): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5227): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5227): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5227): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5227): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5227): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5227): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5227): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5227): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5227): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5227): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5227): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 5227): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 5227): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 5227): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 5227): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 5227): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5227): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 5227): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 5227): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 5227): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 5227): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 5227): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 5227): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 5227): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 5227): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 5227): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 5227): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5227): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5227): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5227): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5227): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5227): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5227): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5227): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 5227): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 5227): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5227): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5227): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 5227): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 5227): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5227): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5227): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5227): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 5227): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 5227): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 5227): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 5227): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 5227): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5227): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5227): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 5227): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 5227): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 5227): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 5227): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 5227): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5227): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 5227): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 5227): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 5227): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 5227): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 5227): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 5227): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 5227): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 5227): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 5227): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 5227): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5227): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 5227): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 5227): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5227): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5227): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 5227): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 5227): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 5227): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 5227): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 5227): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5227): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5227): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5227): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5227): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5227): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5227): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5227): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5227): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5227): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5227): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5227): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5227): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5227): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5227): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 5227): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 5227): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 5227): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 5227): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 5227): threadid=11: thread exiting with uncaught exception (group=0x41729e30)
E/AndroidRuntime( 5227): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 5227): Process: com.google.android.apps.docs, PID: 5227
E/AndroidRuntime( 5227): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5227): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5227): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5227): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5227): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5227): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5227): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5227): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5227): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5227): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5227): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5227): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5227): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5227): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5227): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 5227): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 5227): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 5227): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 5227): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ActivityManager(  904): App crashed! Process: com.google.android.apps.docs
I/ActivityManager(  904): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5245 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process ( 5227): killProcess, pid=5227
D/Process ( 5227): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  904): Can't write: system_app_crash
E/DropBoxManagerService(  904): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  904): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  904): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  904): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  904): 	... 5 more
I/ActivityManager(  904): Recipient 5227
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Process com.google.android.apps.docs (pid 5227) has died.
W/ContextImpl( 5245): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  904): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=5258 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 5245): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5245): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5245): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5245): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5245): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5245): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5245): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5245): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5245): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5245): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5245): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5245): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5245): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5245): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5245): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5245): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 5245): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 5245): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5245): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5245): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5245): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 5245): threadid=10: thread exiting with uncaught exception (group=0x41729e30)
E/ActivityManager(  904): App crashed! Process: com.android.keychain
E/AndroidRuntime( 5245): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5245): Process: com.android.keychain, PID: 5245
E/AndroidRuntime( 5245): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5245): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5245): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5245): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5245): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5245): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5245): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5245): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5245): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5245): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5245): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5245): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5245): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5245): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5245): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 5245): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 5245): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5245): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5245): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5245): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  904): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 5245): killProcess, pid=5245
D/Process ( 5245): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  904): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  904): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452010505271.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  904): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  904): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  904): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  904): 	... 4 more
D/AppTag  ( 5258): getInstance(Context context)
D/AppTag  ( 5258): getInstance(Context context)
D/AppTag  ( 5258): onCreate()
I/ActivityManager(  904): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5273 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
I/ActivityManager(  904): Recipient 5245
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Process com.android.keychain (pid 5245) has died.
W/ActivityManager(  904): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10669ms
I/DeviceManagement( 5122): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 5122): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/ActivityManager(  904): Delay finish: com.htc.cs.dm/.receiver.PackageUpdateReceiver
I/DeviceManagement( 5122): WorkflowService: Starting workflow service
I/DeviceManagement( 5122): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@42242ec8] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 5122): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5122): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 5122): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5122): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 5122): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
E/SQLiteLog( 5122): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 5122): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.cs.dm/databases/provisioning.db, handle = 0x5cac8160
E/SQLiteDatabase( 5273): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
E/SQLiteDatabase( 5273): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5273): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5273): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5273): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5273): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5273): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5273): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5273): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5273): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5273): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5273): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5273): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5273): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5273): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5273): 	at dek.getWritableDatabase(PG:48)
E/SQLiteDatabase( 5273): 	at del.a(PG:264)
E/SQLiteDatabase( 5273): 	at eeq.run(PG:187)
E/SQLiteDatabase( 5273): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteDatabase( 5273): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
E/SQLiteDatabase( 5273): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5273): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5273): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5273): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5273): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5273): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5273): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5273): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5273): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5273): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5273): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5273): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5273): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5273): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5273): 	at dek.getWritableDatabase(PG:51)
E/SQLiteDatabase( 5273): 	at del.a(PG:264)
E/SQLiteDatabase( 5273): 	at eeq.run(PG:187)
E/SQLiteDatabase( 5273): 	at java.lang.Thread.run(Thread.java:864)
W/DeviceManagement( 5122): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@42242ec8]java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
W/DeviceManagement( 5122): 	at android.database.sqlite.SQLiteSession.throwIfNoTransaction(SQLiteSession.java:915)
W/DeviceManagement( 5122): 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:398)
W/DeviceManagement( 5122): 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:562)
W/DeviceManagement( 5122): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:90)
W/DeviceManagement( 5122): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 5122): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 5122): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 5122): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 5122): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 5122): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 5122): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 5122): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 5122): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 5122): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 5122): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 5122): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 5122): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 5122): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 5122): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 5122): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 5122): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 5122): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 5122): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/EsApplication( 5273): Failed app initialization
E/EsApplication( 5273): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/EsApplication( 5273): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/EsApplication( 5273): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/EsApplication( 5273): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/EsApplication( 5273): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/EsApplication( 5273): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/EsApplication( 5273): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/EsApplication( 5273): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/EsApplication( 5273): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/EsApplication( 5273): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/EsApplication( 5273): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/EsApplication( 5273): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/EsApplication( 5273): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/EsApplication( 5273): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/EsApplication( 5273): 	at dek.getWritableDatabase(PG:51)
E/EsApplication( 5273): 	at del.a(PG:264)
E/EsApplication( 5273): 	at eeq.run(PG:187)
E/EsApplication( 5273): 	at java.lang.Thread.run(Thread.java:864)
I/DeviceManagement( 5122): WorkflowService: Stopping workflow service
I/ActivityManager(  904): Resuming delayed broadcast
D/PMS     (  904): acquireWL(43bd1ba0): PARTIAL_WAKE_LOCK  AsyncService 0x1 5273 10160 null
I/ActivityManager(  904): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5295 uid=10099 gids={50099, 3003, 5012}
D/PMS     (  904): releaseWL(43bd1ba0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/Documents( 5295): Loading roots for com.android.providers.downloads.documents
D/Documents( 5295): Loading roots for com.android.externalstorage.documents
E/SQLiteDatabase( 5295): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 5295): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5295): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5295): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5295): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5295): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5295): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5295): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5295): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5295): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5295): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5295): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5295): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5295): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5295): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5295): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 5295): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 5295): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 5295): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 5295): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 5295): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 5295): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 5295): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 5295): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5295): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5295): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5295): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5295): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5295): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5295): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5295): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 5295): threadid=1: thread exiting with uncaught exception (group=0x41729e30)
E/AndroidRuntime( 5295): FATAL EXCEPTION: main
E/AndroidRuntime( 5295): Process: com.android.documentsui, PID: 5295
E/AndroidRuntime( 5295): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5295): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 5295): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 5295): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 5295): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5295): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5295): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 5295): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 5295): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 5295): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 5295): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 5295): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 5295): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5295): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5295): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5295): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5295): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5295): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5295): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5295): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5295): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5295): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5295): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5295): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5295): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5295): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5295): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 5295): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 5295): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 5295): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 5295): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 5295): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 5295): 	... 10 more
I/ActivityManager(  904): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=5308 uid=10023 gids={50023, 1028, 1015, 1023}
E/ActivityManager(  904): App crashed! Process: com.android.documentsui
D/ErrorReport(  904): HtcErrorReportManager Begin---add error logs to dropbox
E/ErrorReport(  904): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  904): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452010505615.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  904): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  904): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  904): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  904): 	... 4 more
D/Process ( 5295): killProcess, pid=5295
D/Process ( 5295): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/GCM     ( 1502): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Recipient 5295
I/ActivityManager(  904): Process com.android.documentsui (pid 5295) has died.
D/GCM     ( 1502): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/ExternalStorage( 5308): After updating volumes, found 1 active roots
I/ActivityManager(  904): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=5323 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1270): loadItems() com.htc.launcher.pageview.WidgetManager@41beccf8 +
I/Prism.WidgetManager( 1270): onLoadItems() +
E/SQLiteDatabase( 5323): Failed to open database '/data/data/com.htc.task/databases/MyDB.db'.
E/SQLiteDatabase( 5323): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5323): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5323): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5323): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5323): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5323): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5323): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5323): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5323): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5323): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5323): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5323): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5323): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5323): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5323): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteDatabase( 5323): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteDatabase( 5323): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteDatabase( 5323): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteDatabase( 5323): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5323): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5323): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5323): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 5323): Couldn't open MyDB.db for writing (will try read-only):
E/SQLiteOpenHelper( 5323): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5323): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5323): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 5323): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 5323): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5323): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5323): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5323): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 5323): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 5323): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 5323): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 5323): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 5323): 	at android.databas,e.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5323): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5323): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteOpenHelper( 5323): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteOpenHelper( 5323): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteOpenHelper( 5323): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteOpenHelper( 5323): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 5323): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5323): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 5323): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 5323): Opened MyDB.db in read-only mode

```
