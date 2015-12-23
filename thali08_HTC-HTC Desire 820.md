#### Test 543122980a88295_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/WIFI_ICON( 1111): WifiActivity: 0
D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,--------- beginning of /dev/log/main
E/cutils-trace( 4384): Error opening trace file: No such file or directory (2)
D/WIFI_ICON( 1111): WifiActivity: 1
D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/CustomizationManager( 4384): ====startRecUseTime====
D/htc.customization.log.level( 4384):  is 
W/CustomizationLogLevel( 4384): Level value is invalid, use default level 2
D/CustomizationManager( 4384):  Read ACC file spent 0.053 (s)
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
D/CustomizationManager( 4384):  Read CID file spent 0.093 (s)
D/CustomizationManager( 4384):  All configurations done spent 0.094 (s)
W/HtcNativeFlag( 4384): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4384): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4384): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4384): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  904): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  904): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  904): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  904): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  904): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  904): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  904): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4384
D/PMS     (  904): acquireHCC(42307ae0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 904 1000 null
D/PMS     (  904): acquireHCC(422c5f90): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 904 1000 null
W/asset   (  904): Copying FileAsset 0x6785c410 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  904): @test_code: getHtcIntentFlag: 0 obj: 1113522928
I/FeedHostManager( 1267): [onPause]
I/FeedProviderManager( 1267): onPause
I/FeedHostManager( 1267): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41b11ee0
I/SocialFeedProvider( 1267): +onPause
I/SocialFeedProvider( 1267): -onPause
D/PMS     (  904): acquireWL(42095790): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 904 1000 null
I/ActivityManager(  904): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4395 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1267): [trimMemory] 20
W/asset   ( 4395): Copying FileAsset 0x5c700428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4395): Binding Chromium to main looper Looper (main, tid 1) {41a7e8e8}
I/LibraryLoader( 4395): Expected native library version number "",actual native library version number ""
I/chromium( 4395): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4395): Initializing chromium process, renderers=0
W/System.err(  904): java.lang.Throwable: stack dump
D/BluetoothManagerService(  904): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  904): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@421f4af8:true
W/System.err(  904): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  904): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  904): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  904): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  904): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4395): 1101615008: getState(). Returning 12
D/PMS     (  904): acquireWL(424b5a78): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  904): acquireWL(4233dc20): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  904): releaseWL(4233dc20): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
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
,I/InputMethodManagerService(  904): Disable input method client, pid=1267
,W/ResourceType( 4395): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4395): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41ac6650, mServedView=org.apache.cordova.engine.SystemWebView{41a8c2b8 VFEDH.C. .F....I. 0,0-720,1134 #64}
,W/AwContents( 4395): nativeOnDraw failed; clearing to background color.
W/XT9_C   ( 1205): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1205): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1205): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1205): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,I/ActivityManager(  904): Displayed com.test.thalitest/.MainActivity: +251ms
I/InputMethodManagerService(  904): Enable input method client, pid=4395
D/PMS     (  904): releaseWL(42095790): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4395): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4395): JniHelper::setJavaVM(0x41557048), pthread_self() = 1662072616
,D/JX-Cordova( 4395): jxcore cordova android initializing
,I/dalvikvm-heap( 4395): Grow heap (frag case) to 11.585MB for 96598-byte allocation
,I/dalvikvm-heap( 4395): Grow heap (frag case) to 11.636MB for 144892-byte allocation
,I/dalvikvm-heap( 4395): Grow heap (frag case) to 11.746MB for 217334-byte allocation
,I/dalvikvm-heap( 4395): Grow heap (frag case) to 11.922MB for 325996-byte allocation
,I/dalvikvm-heap( 4395): Grow heap (frag case) to 12.197MB for 488990-byte allocation
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1151): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
,I/dalvikvm-heap( 4395): Grow heap (frag case) to 13.203MB for 1100216-byte allocation
,I/dalvikvm-heap( 4395): Grow heap (frag case) to 14.077MB for 1650320-byte allocation
,I/dalvikvm-heap( 4395): Grow heap (frag case) to 15.460MB for 2475476-byte allocation
,I/ActivityManager(  904): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4438 uid=10077 gids={50077}
,D/PMS     (  904): acquireWL(42d9b570): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10077}
V/AlarmManager(  904): sending alarm PendingIntent{41dcf830: PendingIntentRecord{41dcf7f8 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1450833996698, Int=60000
,D/PMS     (  904): releaseWL(42d9b570): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4438): SMSBackupAgentService started
,D/SMSBackup( 4438): Checking restore status
D/SMSBackup( 4438): Restore complete
,D/SMSBackup( 4438): cancelCheckAlarm
,D/SMSBackup( 4438): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  904): killProcessQuiet, pid=3474
,I/ActivityManager(  904): Killing 3474:com.htc.task/u0a70 (adj 15): empty #17
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  904): Waited long enough for: ServiceRecord{4317a850 u0 com.htc.htclocationservice/.AutoSettingService}
,I/dalvikvm-heap( 4395): Grow heap (frag case) to 17.462MB for 3713210-byte allocation
I/ActivityManager(  904): Recipient 3474
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SensorManager(  904): mEventCount = 1350
,W/jxcore-log( 4395): Initializing JXcore engine
,W/jxcore-log( 4395): JXcore engine is ready
,W/jxcore-log( 4395): Starting JXcore engine
,W/CpuWake (  904): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  904): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  904): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  904): <<release mCpuPerf_cpu_count wakelock
,W/CpuWake (  904): >>release mCpuPerf_Freq wakelock
W/CpuWake (  904): <<release mCpuPerf_Freq wakelock
D/PMS     (  904): releaseHCC(42307ae0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  904): releaseHCC(422c5f90): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4395): Platform android
W/jxcore-log( 4395): 
,W/jxcore-log( 4395): Process ARCH arm
W/jxcore-log( 4395): 
,I/jxcore-log( 4395): JXcore Cordova bridge is ready!
I/jxcore-log( 4395): 
,W/jxcore-log( 4395): JXcore engine is started
,I/chromium( 4395): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PMS     (  904): acquireWL(42d9f6e0): PARTIAL_WAKE_LOCK  Icing 0x1 1222 10028 null
,D/PMS     (  904): releaseWL(42d9f6e0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(42da1cb8): PARTIAL_WAKE_LOCK  Icing 0x1 1222 10028 null
,D/PMS     (  904): releaseWL(42da1cb8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(42da3528): PARTIAL_WAKE_LOCK  Icing 0x1 1222 10028 null
,D/PMS     (  904): releaseWL(42da3528): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(42da4da0): PARTIAL_WAKE_LOCK  Icing 0x1 1222 10028 null
,D/PMS     (  904): releaseWL(42da4da0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): releaseWL(424b5a78): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4395): Toggling radios to true
I/jxcore-log( 4395): 
,D/BluetoothAdapter( 4395): enable(): BT is already enabled..!
,D/WifiManager( 4395): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
W/HtcDLNAServiceManager(  904): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  904): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  904): Settings:Agentvalue: 2
W/Settings:Agent(  904): >> traceCallingStack()
W/Settings:Agent(  904): Process.myPid(): 904
W/Settings:Agent(  904): Process.myTid(): 1465
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
,W/Settings:Agent(  904): << traceCallingStack(): 1(ms)
D/WifiManager( 4395): disconnect: Base Package Name=com.test.thalitest, uid=10348
D/WifiNative-wlan0(  904): doBoolean: DISCONNECT
,D/WifiManager( 4395): reconnect: Base Package Name=com.test.thalitest, uid=10348
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1151): TDLS: Tear down peers
I/wpa_supplicant( 1151): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4395): Radios toggled
I/jxcore-log( 4395): 
,D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiService(  904): setWifiEnabled: true pid=4395, uid=10348
E/WifiService(  904): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  904): New client listening to asynchronous messages
I/WifiService(  904): isSprintWifiRestricted(): false
I/WifiService(  904): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  904): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
I/jxcore-log( 4395): Got Device Bluetooth address: 80:01:84:8A:B3:68
I/jxcore-log( 4395): 
I/jxcore-log( 4395): Perf Test app loaded loaded
I/jxcore-log( 4395): 
I/jxcore-log( 4395): check test folder
I/jxcore-log( 4395): 
I/jxcore-log( 4395): found test : ./testFindPeers.js
I/jxcore-log( 4395): 
,I/jxcore-log( 4395): found test : ./testSendData.js
I/jxcore-log( 4395): 
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1151): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1151): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1151): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  904): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  904): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  904): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  904): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getFreqFromEventString() 2412
,D/WifiMonitor(  904): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1151): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1151): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1151): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1151): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1151): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1151): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1151): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1151): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1151): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1151): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb7224bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1151):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1151): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1151): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1151): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1151): netlink: Operstate: linkmode=-1, operstate=5
D/Tethering(  904): interfaceLinkStateChanged wlan0, false
D/Tethering(  904): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1151): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1151): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1151): EAPOL: External notification - portEnabled=0
,D/wpa_supplicant( 1151): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1151): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1151): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1151): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1151): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1151): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1151): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1151): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1151): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1151): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1151): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1151): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1151): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1151): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1151): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1151): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1151): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1151): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1151): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1151): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1151): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1151): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1151): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1151): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1151): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1151): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1151): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1151): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1151): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1151): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1151): nl80211: Event message available
D/wpa_supplicant( 1151): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1151): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/WifiNative-wlan0(  904):    returned true
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/WifiPerfLock(  904): release()
D/WifiStateMachine(  904): PerfLock released for exiting ConnectedState
D/Tethering(  904): [isWifi] getHotspotEnabled: false
D/ConnectivityService(  904): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  904): acquireWL(42dab828): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 904 1000 null
D/Tethering(  904): interfaceLinkStateChanged wlan0, false
D/Tethering(  904): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  904): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1151): Power_Mode_Type mode = 0
I/wpa_supplicant( 1151): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 61
D/Tethering(  904): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1151): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  904):    returned true
D/libc    (  904): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-, SUCCESS
D/WifiP2pService(  904): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  904): [RunningState] Stop DHCP
D/WifiStateMachine(  904): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  904): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/WifiNative-wlan0(  904): doBoolean: RECONNECT
D/libc    (  904): [NET] getaddrinfo-, SUCCESS
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1151): Fast associate: Old scan results
I/wpa_supplicant( 1151): wpa_supplicant_scan enter
I/wpa_supplicant( 1151): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1151): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1151): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  904):    returned true
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1151): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1151): nl80211: Event message available
D/wpa_supplicant( 1151): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiStateMachine(  904): Enter handleNetworkDisconnect
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiDataStallTracker(  904): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  904): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  904): stopDataStallAlarm: current tag=18736 mDataStallAlarmIntent=PendingIntent{422f7e28: PendingIntentRecord{423bb8a0 android broadcastIntent}}
,D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,D/WifiNative-wlan0(  904): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1151): Power_Mode_Type mode = 0
I/wpa_supplicant( 1151): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1151): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  904):    returned true
,I/IntentController( 1111): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1111): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/UsbnetStateTracker(  904): isAvailable+-
D/UsbnetStateTracker(  904): reconnect
,D/UsbnetStateTracker(  904): isAvailable+-
,D/WISPrService( 4167): >>>>>WISPrService start isConnected = false<<<<<
D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiP2pService(  904): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateTracker(  904): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  904): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  904): Provision feature enable=false
D/ConnectivityService(  904): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  904): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1816/10178)
D/MDST    (  904): default: reconnect()
D/MDST    (  904): default: setTeardownRequested(false)
D/MDST    (  904): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  904): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4167): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  904): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  904): Exit handleNetworkDisconnect
,D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent DefaultState
,I/jxcore-log( 4395): found test : ./testSendData2.js
I/jxcore-log( 4395): 
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WifiDataStallTracker(  904): onReceive: action=android.net.wifi.STATE_CHANGE
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WifiDataStallTracker(  904): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiStateMachine(  904): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,I/IntentController( 1111): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  904): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  904): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiService(  904): New client listening to asynchronous messages
W/ConnectivityService(  904): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  904): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  904): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiStateTracker(  904): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/ConnectivityService(  904): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  904): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,D/ConnectivityService(  904): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1816/10178)
D/WIFI_ICON( 1111): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ConnectivityService(  904): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  904): handleConnectivityChange: resetting
,D/ConnectivityService(  904): resetConnections(wlan0, 3)
,D/PMS     (  904): acquireWL(43fa7a38): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1394 10028 null
,D/PMS     (  904): acquireWL(43f1e3e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1394 10028 null
,D/libc    (  363): [NET] entry_id:5   entry:0xb7c80fc8  removed 
D/libc    (  363): [NET] entry_id:7   entry:0xb7c81368  removed 
D/libc    (  363): [NET] entry_id:6   entry:0xb7c81180  removed 
D/libc    (  363): [NET] entry_id:4   entry:0xb7c85310  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb7c85248  removed 
D/libc    (  363): [NET] entry_id:8   entry:0xb7c81548  removed 
D/libc    (  363): [NET] entry_id:3   entry:0xb7c85038  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb7c85410  removed 
D/libc    (  363): [NET] entry_id:9   entry:0xb7c81720  removed 
,D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
,D/WISPrService( 4167): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  904): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 4167): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  904): flush DNS cache for net 1(wlan0)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1394/10028)
D/Nat464Xlat(  904): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  904): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  904): reportInetCondition for net -1, percentage: 0 by  (1394/10028)
D/ConnectivityService(  904): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  904): acquireWL(425d0a48): PARTIAL_WAKE_LOCK  NetworkStats 0x1 904 1000 null
,D/WirelessDisplayService(  904): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  904): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WifiStateMachine(  904): startScan Pid: 904 Uid 1000
,D/WifiNative-wlan0(  904): doBoolean: SCAN
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1151): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  904):    returned false
,I//system/bin/ip(  363): RTNETLINK answers: No such process
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  904): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by  (904/1000)
D/PMS     (  904): releaseWL(43f1e3e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/BatSI   (  904): WIFI scan started for: 650a0300 uid:1000
I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,I/QuickSettingWifi( 1111): receive.wifiConnect:false wifiAPname:null elapse:1
D/PMS     (  904): releaseWL(43fa7a38): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1394/10028)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1394/10028)
,D/ConnectivityService(  904): mActiveDefaultNetwork: -1
,D/ConnectivityService(  904): handleInetConditionChange: no active default network - ignore
,I/QuickSettingWifi( 1111): receive.wifiConnect:false wifiAPname:null elapse:1
D/PMS     (  904): releaseWL(425d0a48): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/Choreographer( 4395): Skipped 87 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4395): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  904): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  904): [AlarmQueuing] connectivity wifi: false
,D/ConnectivityService(  904): getNetworkInfo networkType=1 called by  (904/1000)
,D/Tethering(  904): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  904): bSetPropertyMultiRAB:false
D/Tethering(  904): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
D/GpsLocationProvider(  904): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  904): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  904): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  904): ignore wifi update if we are not in OPENING or CLOSING
I/Tethering(  904): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
,I/Tethering(  904): ipv4Default null
I/Tethering(  904): No IPv4 upstream interface, giving up.
D/Tethering(  904): TetherMasterSM: InitialState processMessage what=3
,D/CaptivePortalTracker(  904): DelayedCaptiveCheckState
D/CaptivePortalTracker(  904): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/CaptivePortalTracker(  904): NoActiveNetworkState
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/PMS     (  904): acquireWL(425ab990): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 904 1000 null
D/ConnectivityService(  904): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1816/10178)
D/PMS     (  904): releaseWL(425ab990): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1877/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1440/10028)
I/NetworkMonitor( 3881): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by com.google.android.music (3881/10154)
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by com.htc.launcher (1267/10075)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.docs (4285/10100)
D/htcCheckinService(  904): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
I/ConnectivityHelper( 1267): [onReceive] WIFI(1): DISCONNECTED
D/htcCheckinService(  904): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.docs (4285/10100)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (2363/10021)
,I/ActivityManager(  904): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4464 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4464): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4464): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4464): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4464): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4464): Preparing secondary program dexes.
V/DexLibLoader( 4464): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4464): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4464): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4464): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4464): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4464): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
,V/DexLibLoader( 4464): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4464): Dex already copied
D/OdexVerifier( 4464): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4464): Creating class loader
,V/DexLibLoader( 4464): Finished creating class loader
V/DexLibLoader( 4464): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
,V/DexLibLoader( 4464): Dex already copied
D/OdexVerifier( 4464): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4464): Creating class loader
V/DexLibLoader( 4464): Finished creating class loader
V/DexLibLoader( 4464): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4464): Dex already copied
D/OdexVerifier( 4464): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4464): Creating class loader
,V/DexLibLoader( 4464): Finished creating class loader
V/DexLibLoader( 4464): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar,
V/DexLibLoader( 4464): Dex already copied
D/OdexVerifier( 4464): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4464): Creating class loader
V/DexLibLoader( 4464): Finished creating class loader
,V/DexLibLoader( 4464): Verifying classes from secondary dexes.
,D/DexLibLoader( 4464): DexLibLoader.ensureDexLoaded took 22 ms,
,W/dalvikvm( 4464): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4464): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4464): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4464): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4464): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4464): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4464): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4464): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4464): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1151): nl80211: Event message available
D/wpa_supplicant( 1151): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1151): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1151): nl80211: Survey data missing
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1151): Sorted scan results
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1151): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-47
I/wpa_supplicant( 1151): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-48
I/wpa_supplicant( 1151): [NULL] fe:94:e3:11:35:3c freq=2462 level=-87
I/wpa_supplicant( 1151): [NULL] fc:94:e3:11:35:3a freq=2462 level=-87
I/wpa_supplicant( 1151): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-89
I/wpa_supplicant( 1151): [NULL] 0c:bd:51:2b:c1:25 freq=2462 level=-91
D/wpa_supplicant( 1151): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1151): Add randomness: count=7 entropy=0
D/wpa_supplicant( 1151): Add randomness: count=8 entropy=1
D/wpa_supplicant( 1151): Add randomness: count=9 entropy=2
D/wpa_supplicant( 1151): Add randomness: count=10 entropy=3
D/wpa_supplicant( 1151): Add randomness: count=11 entropy=4
D/wpa_supplicant( 1151): Add randomness: count=12 entropy=5
D/wpa_supplicant( 1151): Add randomness: count=13 entropy=6
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: AP 0c:bd:51:2b:c1:25 type 0 added
D/wpa_supplicant( 1151): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1151): WPS: AP[3] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1151): wpa_supplicant_pick_network+
I/wpa_supplicant( 1151): Selecting BSS from priority group 1
I/wpa_supplicant( 1151): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1151): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1151): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1151): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1151):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1151):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-47
I/wpa_supplicant( 1151): Start print parameters
I/wpa_supplicant( 1151): wpa_s->wpa_state is 3
I/wpa_supplicant( 1151): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1151): isConcurrentMode() is 0
I/wpa_supplicant( 1151): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1151): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1151): wpa_s->,bt_a2dp_status is 0
I/wpa_supplicant( 1151): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1151): wpa_s->reassociate is 1
I/wpa_supplicant( 1151): wpa_s->is_screen_on 1
I/wpa_supplicant( 1151): wpa_s->ifname wlan0
I/wpa_supplicant( 1151): End print parameters
I/wpa_supplicant( 1151): selected network = 1
D/wpa_supplicant( 1151): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb72264e8  current_ssid=0x0
D/wpa_supplicant( 1151): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1151): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1151): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1151): check if in concurrent case
I/wpa_supplicant( 1151): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  904): doString: LIST_DONGLES
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1151): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1151): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1151): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1151): RSN: PMKSA cache search - network_ctx=0xb72264e8 try_opportunistic=0
D/wpa_supplicant( 1151): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1151): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1151): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1151): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1151): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1151): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1151): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1151): nl80211: Unsubscribe mgmt frames handle 0xb7225718 (mode change)
D/wpa_supplicant( 1151): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7225718
D/wpa_supplicant( 1151): nl80211: Register frame type=0xd0 nl_handle=0xb7225718
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1151): nl80211: Register frame type=0xd0 nl_handle=0xb7225718
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1151): nl80211: Register frame type=0xd0 nl_handle=0xb7225718
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1151): nl80211: Register frame type=0xd0 nl_handle=0xb7225718
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1151): nl80211: Register frame type=0xd0 nl_handle=0xb7225718
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1151): nl80211: Register frame type=0xd0 nl_handle=0xb7225718
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1151): nl80211: Register frame type=0xd0 nl_handle=0xb7225718
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1151): nl80211: Register frame type=0xd0 nl_handle=0xb7225718
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1151): nl80211: Register frame type=0xd0 nl_handle=0xb7225718
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1151): nl80211: Register frame type=0xd0 nl_handle=0xb7225718
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1151): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1151):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1151):   * freq=2412
D/wpa_supplicant( 1151):   * Auth Type 0
D/wpa_supplicant( 1151):   * WPA Versions 0x2
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(),: SSID
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1151): nl80211: Connect request send successfully
D/wpa_supplicant( 1151): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1151): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1151): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1151): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1151): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1151): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1151): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1151): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1151): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  904): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1151): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1151): reply (893) for get BSS: id=0
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1151): freq=5220
I/wpa_supplicant( 1151): level=-48
I/wpa_supplicant( 1151): tsf=0000000107871188
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG7005g
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=1
I/wpa_supplicant( 1151): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-47
I/wpa_supplicant( 1151): tsf=0000000107871205
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=NG700
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=2
I/wpa_supplicant( 1151): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1151): freq=2462
I/wpa_supplicant( 1151): level=-87
I/wpa_supplicant( 1151): tsf=0000000020751537
I/wpa_supplicant( 1151): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1151): ssid=UPC0039325
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=3
I/wpa_supplicant( 1151): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1151): freq=2462
I/wpa_supplicant( 1151): level=-87
I/wpa_supplicant( 1151): tsf=0000000107871209
I/wpa_supplicant( 1151): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1151): ssid=UPC Wi-Free
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=4
I/wpa_supplicant( 1151): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): freq=2412
I/wpa_supplicant( 1151): level=-48
I/wpa_supplicant( 1151): tsf=0000000107871200
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1151): ssid=01ABC
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=5
I/wpa_supplicant( 1151): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1151): freq=2437
I/wpa_supplicant( 1151): level=-89
I/wpa_supplicant( 1151): tsf=0000000107871216
I/wpa_supplicant( 1151): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=UPC4688432
I/wpa_supplicant( 1151): ====
I/wpa_supplicant( 1151): id=6
I/wpa_supplicant( 1151): bssid=0c:bd:51:2b:c1:25
I/wpa_supplicant( 1151): freq=2462
I/wpa_supplicant( 1151): level=-91
I/wpa_supplicant( 1151): tsf=0000000107871220
I/wpa_supplicant( 1151): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1151): ssid=PLAY-ONLINE_1167
I/wpa_supplicant( 1151): ####
,D/WirelessDisplayService(  904): getDiscoveryDongleList
W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/WifiStateMachine(  904): == begin of scan result ==
,D/WifiStateMachine(  904): == (7) end of scan result ==
,D/WirelessDisplayService(  904): getDiscoveryDongleList
D/WifiStateMachine(  904): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 107871188, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 2412, timestamp: 107871205, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 2: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -87, frequency: 2462, timestamp: 20751537, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 3: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -87, frequency: 2462, timestamp: 107871209, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -48, frequency: 2412, timestamp: 107871200, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 5: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -89, frequency: 2437, timestamp: 107871216, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 6: scan result = SSID: PLAY-ONLINE_1167, BSSID: 0c:bd:51:2b:c1:25, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -91, frequency: 2462, timestamp: 107871220, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): add 7 to mScanResults
D/BatSI   (  904): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  904): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,E/FbInjectorInitializer( 4464): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/wpa_supplicant( 1151): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1151): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1151): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1151): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1151): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1151): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1151): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1151): nl80211: Event message available
D/wpa_supplicant( 1151): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1151): nl80211: Connect event
D/wpa_supplicant( 1151): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1151): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1151): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1151): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1151): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1151): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1151): Add randomness: count=14 entropy=7
I/wpa_supplicant( 1151): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1151): TDLS: Remove peers on association
D/wpa_supplicant( 1151): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1151): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1151): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1151): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1151): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1151): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1151): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1151): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1151): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1151): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1151): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1151): EAPOL: enable timer tick
D/wpa_supplicant( 1151): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1151): State: ASSOCIATED -> 4WAY_HANDSHAKE
,D/wpa_supplicant( 1151): Get randomness: len=32 entropy=8
,D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
I/wpa_supplicant( 1151): htc_wext_set_keepalive +
I/wpa_supplicant( 1151): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1151): getPrivFuncNum +	
I/wpa_supplicant( 1151): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1151): htc_wext_set_keepalive fnum = 0x8bf6
,I/wpa_supplicant( 1151): htc_wext_set_keepalive - ret = 0
D/Tethering(  904): interfaceLinkStateChanged wlan0, false
D/Tethering(  904): interfaceStatusChanged wlan0, false
D/Tethering(  904): [isWifi] getHotspotEnabled: false
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  904): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  904): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  904): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  904): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  904): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  904): handleAssociatedWithEvent. bLFR =false
,D/WifiMonitor(  904): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  904): Enter handleAssociatedWithEvent
D/WifiStateMachine(  904): Associated
D/WifiStateMachine(  904): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  904): Exit handleAssociatedWithEvent
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  904): interfaceLinkStateChanged wlan0, true
D/Tethering(  904): interfaceStatusChanged wlan0, true
,D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/Tethering(  904): [isWifi] getHotspotEnabled: false
,D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  904): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  904): updateConnectedAP...
I/wpa_supplicant( 1151): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1151): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb72259f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 1151):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1151): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1151): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1151): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f81b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1151):    broadcast key
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1151): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1151): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1151): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1151): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1151): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
,I/wpa_supplicant( 1151): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiApDatabaseHandler(  904): updateConnectedAP...
E/wpa_supplicant( 1151): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1151): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1151): netlink: Operstate: linkmode=-1, operstate=6
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1151): set send_ind_to_ndc = 0
I/wpa_supplicant( 1151): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1151): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1151): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1151): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1151): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1151): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1151): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1151): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1151): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1151): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1151): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1151): EAPOL authentication completed successfully
I/wpa_supplicant( 1151): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1151): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1151): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1151): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  904): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
,D/WifiMonitor(  904): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/WifiApDatabaseHandler(  904): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/Tethering(  904): interfaceLinkStateChanged wlan0, true
D/WifiStateMachine(  904): This record is existed, only update it...
D/Tethering(  904): interfaceStatusChanged wlan0, true
D/Tethering(  904): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  904): updateConnectedAP...
,D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  904): updateConnectedAP...
,D/WifiStateMachine(  904): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  904): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  904): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  904): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiDataStallTracker(  904): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1111): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiApDatabaseHandler(  904): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  904): This record is existed, only update it...
,D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  904): updateConnectedAP...
,D/WISPrService( 4167): >>>>>WISPrService start isConnected = false<<<<<
D/WIFI_ICON( 1111): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  904): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  904): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  904): Provision feature enable=false
,D/ConnectivityService(  904): mActiveDefaultNetwork: -1
D/WISPrService( 4167): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
W/fb4a(:<default>):StaticBindingVerifier( 4464): Verify
D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  904): updateConnectedAP...
,D/DhcpStateMachine(  904): [StoppedState] Start DHCP
,D/WifiStateMachine(  904): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1151): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
,D/WifiNative-wlan0(  904): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1151): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  904):    returned true
,D/WifiNative-wlan0(  904): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1151): Power_Mode_Type mode = 1
I/wpa_supplicant( 1151): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  904):    returned true
,D/WifiNative-wlan0(  904): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1151): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  904):    returned null
E/WifiStateMachine(  904): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  904): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1151): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  904):    returned null
D/WifiStateMachine(  904): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  904): acquireWL(43fe96b8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 904 1000 null
D/WifiStateMachine(  904): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  904): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@420e78e0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@420e78e0 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1111): receive.wifiConnect:false wifiAPname:null elapse:0
,D/WifiService(  904): New client listening to asynchronous messages
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4464): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4464): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4464): Grow heap (frag case) to 9.512MB for 73240-byte allocation
,D/Process (  904): killProcessQuiet, pid=3146
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  904): Killing 3146:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3146
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  904): acquireWL(436d79a0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1222 10028 null
,D/PMS     (  904): acquireWL(43b8a1a0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1222 10028 null
,D/PMS     (  904): releaseWL(436d79a0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1222/10028)
,D/GCM     ( 1394): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1394/10028)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1394/10028)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1394/10028)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1222/10028)
,D/PMS     (  904): releaseWL(43b8a1a0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/AutoSetting( 1383): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  904): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4493 uid=10078 gids={50078, 3003, 5012}
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.sense.hsp (1383/10053)
,D/AutoSetting( 1383): Util - no network available!
,D/AutoSetting( 1383): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/AutoSetting( 1383): service - mHandler: cancel location update
,D/AutoSetting( 1383): service -           changes count: 0
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.sense.hsp (1383/10053)
,W/fb4a(:<default>):UserScope( 4464): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4464): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4464): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4493): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4493): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4493): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4493): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  904): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4507 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  904): killProcessQuiet, pid=4222
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  904): Killing 4222:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.setupwizard (4493/10078)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.setupwizard (4493/10078)
,I/ActivityManager(  904): Recipient 4222
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.setupwizard (4493/10078)
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  904): Client connection lost with reason: 4
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4464): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,I/ActivityManager(  904): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4524 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  904): killProcessQuiet, pid=3862
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/ActivityManager(  904): Killing 3862:com.htc.mediamanager/u0a32 (adj 15): empty #17
E/dalvikvm( 4464): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
W/dalvikvm( 4464): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4464): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 4464): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4464): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 4464): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4464): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4464): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4464): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4464): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4464): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4464): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4464): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4464): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4464): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4464): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4464): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4464): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/ActivityManager(  904): Recipient 3862
,I/dalvikvm-heap( 4464): Grow heap (frag case) to 9.923MB for 39954-byte allocation
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4524): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4524): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAV2    ( 4524): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4524): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4524): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/dalvikvm-heap( 4464): Grow heap (frag case) to 10.000MB for 79892-byte allocation
,I/dalvikvm-heap( 4464): Grow heap (frag case) to 10.067MB for 84664-byte allocation
,I/dalvikvm-heap( 4464): Grow heap (frag case) to 10.095MB for 28144-byte allocation
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.magazines (4524/10151)
,V/WebViewChromiumFactoryProvider( 4524): Binding Chromium to main looper Looper (main, tid 1) {41a84338}
,I/LibraryLoader( 4524): Expected native library version number "",actual native library version number ""
,I/chromium( 4524): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4524): Initializing chromium process, renderers=0
,D/PMS     (  904): acquireWL(43fdc830): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
,D/PMS     (  904): acquireWL(43ff29c0): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
,E/AudioManagerAndroid( 4524): BLUETOOTH permission is missing!
D/PMS     (  904): releaseWL(43fdc830): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4524): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4524): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4524): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4524): Local Branch: 
I/Adreno-EGL( 4524): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4524): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4524):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4524): Starting up...
,I/dalvikvm-heap( 4464): Grow heap (frag case) to 10.280MB for 75760-byte allocation
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.magazines (4524/10151)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.magazines (4524/10151)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,W/BroadcastQueue(  904): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43f289e0 u0 ReceiverList{4254f3d0 4464 com.facebook.katana/10026/u0 remote:42527670}}
,W/BroadcastQueue(  904): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43f289e0 u0 ReceiverList{4254f3d0 4464 com.facebook.katana/10026/u0 remote:42527670}}
,W/BroadcastQueue(  904): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43b317e8 u0 ReceiverList{42547638 4464 com.facebook.katana/10026/u0 remote:424d9860}}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.plus (4146/10160)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.plus (4146/10160)
D/wpa_supplicant( 1151): EAPOL: startWhen --> 0
D/wpa_supplicant( 1151): EAPOL: disable timer tick
,D/Process (  904): killProcessQuiet, pid=4254
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  904): Killing 4254:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 4254
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  904): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1816/10178)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1816/10178)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/GCM     ( 1394): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/PMS     (  904): acquireWL(43a6e418): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1440 10028 null
,D/PMS     (  904): releaseWL(43a6e418): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/GCoreFlp( 1440): Unknown pending intent to remove.
D/PMS     (  904): acquireWL(43a17628): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1440 10028 null
D/PMS     (  904): releaseWL(43a17628): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4464): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4464): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,D/libc    (  904): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  904): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
,D/libc    (  904): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
,D/libc    (  904): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
,D/libc    (  904): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  904): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1151): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1151): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  904):    returned true
,D/WifiNative-wlan0(  904): doBoolean: DRIVER BTCOEXMODE 2
D/WifiP2pService(  904): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  904): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1151): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  904):    returned true
,D/WifiStateMachine(  904): handlePostDhcpSetup release wake lock during DHCP
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  904): releaseWL(43fe96b8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1151): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
D/WIFI_ICON( 1111): updateWifiState: RSSI_CHANGED -1 -> 3
D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,D/WifiStateMachine(  904): gateway: /192.168.1.1
,D/WifiNative-wlan0(  904): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1151): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  904):    returned true
D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  904): VerifyingLinkState enter
D/WifiStateMachine(  904): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  904): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  904): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  904): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -47, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  904): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  904): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  904): startDataStallAlarm: tag=18738 delay=15s
,I/IntentController( 1111): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NetworkPolicy(  904): mWifiStateReceiver: meteredHint=false,EPS mode=false
,D/WifiWatchdogStateMachine(  904): WAN detection
D/ConnectivityService(  904): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1816/10178)
D/WifiStateTracker(  904): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  904): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  904): Provision feature enable=false
D/ConnectivityService(  904): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  904): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  904): default: teardown()
D/MDST    (  904): default: setTeardownRequested(true)
D/MDST    (  904): default: setEnableApn apnType =default , enable=false
D/MDST    (  904): default: setTeardownRequested(true)
,D/WISPrService( 4167): >>>>>WISPrService start isConnected = true<<<<<
D/libc    (  904): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  904): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/WIFI_ICON( 1111): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WIFI_ICON( 1111): WifiActivity: 3
D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/ConnectivityService(  904): Unexpected mtu value: android.net.wifi.WifiStateTracker@423aec58
,D/ConnectivityService(  904): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  904): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  904): syncGetConfiguredNetworks
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  904): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  904): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  904): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  904): handleConnectivityChange: resetting
D/Nat464Xlat(  904): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  904): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  904): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  904): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  904): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  904): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  904): acquireWL(41ddc2b0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 904 1000 null
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
D/WirelessDisplayService(  904): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  904):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by  (904/1000)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.setupwizard (4493/10078)
,I/QuickSettingWifi( 1111): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/PMS     (  904): acquireWL(4375a650): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1222 10028 null
,I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
,I/logwrapper(  363): /system/bin/ip terminated by exit(254)
D/PMS     (  904): acquireWL(42d69350): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1222 10028 null
D/PMS     (  904): releaseWL(4375a650): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1222/10028)
,I/CheckinService( 1222): Preparing to send checkin request
,I/EventLogService( 1222): Accumulating logs since 1450833951844
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,I/GoogleHttpClient( 1222): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1222): Using GMS GoogleHttpClient
D/ConnectivityService(  904): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  904): releaseWL(41ddc2b0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  904): getNetworkInfo networkType=9 called by com.google.android.gms (1222/10028)
,D/ConnectivityService(  904): getNetworkInfo networkType=0 called by com.google.android.gms (1222/10028)
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
,W/GLSUser ( 1394): GoogleAccountDataService.getToken()
,W/GLSActivity( 1394): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1394): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1394): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/CheckinRequestBuilder( 1222): awaiting user notification for token
,D/DotMatrix( 1566): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1111): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1111): release indeterminate drawable android.widget.OnDemandProgressBar{41e58cf8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1111): com.google.android.gms 1 7 3 12
,I/ActivityManager(  904): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4599 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 4599): install
,I/MultiDex( 4599): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4599): loading existing secondary dex files
,I/MultiDex( 4599): load found 1 secondary dex files
,I/MultiDex( 4599): install done
,I/ProviderInstaller( 4599): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1394): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/PMS     (  904): Going to sleep due to screen timeout...
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@420c6018
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  904): disable: get sensor name = CM36282 Light sensor
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 2
W/SensorService(  904): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@420c6018, eanble = 0, strlen(mName) = 59
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  904): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42292e20
W/SensorService(  904): Listener[1] = com.htc.smartdim.sensor_eye@41ecff78
,W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  904): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  904): Couldn't get kernel wake lock stats
V/LightsService(  904): setLight #2: color=#0
D/qdlights(  904): set_light_buttons_func: on=0 brightness=0
V/LightsService(  904): setLight #0: color=#0
,W/PMS     (  904): mWirelessDisplayManager is null
D/WirelessDisplayService(  904): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  904): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,W/dalvikvm( 4395): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4395): threadid=1: thread exiting with uncaught exception (group=0x4164fe30)
,E/AndroidRuntime( 4395): FATAL EXCEPTION: main
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
,E/ActivityManager(  904): App crashed! Process: com.test.thalitest
W/ActivityManager(  904):   Force finishing activity com.test.thalitest/.MainActivity
,I/Adreno-EGL( 4599): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4599): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4599): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4599): Local Branch: 
I/Adreno-EGL( 4599): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4599): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4599):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4599): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4599): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4599): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4599): Local Branch: 
I/Adreno-EGL( 4599): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4599): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4599):                  aa63bbd948f41d15fc72f585e
,D/SurfaceControl(  904): Excessive delay in blankDisplay() while turning screen off: 370ms
D/PMS     (  904): nativeSetInteractive:false
D/PMS     (  904): nativeSetInteractive:false done
D/PMS     (  904): nativeSetAutoSuspend:true
D/PMS     (  904): nativeSetAutoSuspend:true done
,D/PMS     (  904): acquireWL(43143f70): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 904 1000 null
,D/HABCtrl (  904): TPE algorithm. remove timeout.
,D/PMS     (  904): OOBE c monitor 11
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (4599/10028)
,I/InputMethodManagerService(  904): screenObserver, isScreenOn=false
,D/NfcService( 1252): ScreenObserver: OFF
,D/NfcService( 1252): applyRouting - 0
D/PMS     (  904): acquireWL(436a33d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
,D/NfcService( 1252): applyRouting -2
D/PMS     (  904): acquireWL(43b99e18): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1252 1027 null
I/InputMethodManagerService(  904): Disable input method client, pid=4395
D/PMS     (  904): releaseWL(436a33d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): releaseWL(43b99e18): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,W/asset   (  904): Copying FileAsset 0x6a452bc8 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,V/KeyguardServiceDelegate(  904): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@4256deb8)
,V/KeyguardServiceDelegate(  904): **** SHOWN CALLED ****
D/PMN     (  904): wakingUp
I/WindowManager(  904): No lock screen! windowToken=null
D/PMN     (  904): onScreenOn
I/InputManager(  904): Cancel all due to getting PMS screen off broadcast
,I/IntentController( 1111): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/AlarmManager(  904): ACTION_SCREEN_ON
I/AlarmManager(  904): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  904): [AlarmQueuing] done recovering
I/AlarmManager(  904): [AlarmQueuing] recover EPS screen off blocked alarms
,D/WifiDataStallTracker(  904): onReceive: action=android.intent.action.SCREEN_ON
,I/AlarmManager(  904): [AlarmQueuing] done EPS screen off alarm recovering
D/WifiDataStallTracker(  904): startDataStallAlarm: tag=18739 delay=15s
D/WifiNative-wlan0(  904): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1151): SET_SCREEN_ON:On
I/wpa_supplicant( 1151): htc_wext_set_keepalive +
I/wpa_supplicant( 1151): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1151): getPrivFuncNum +	
I/wpa_supplicant( 1151): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1151): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1151): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1151): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1151): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  904):    returned true
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/WIFI_ICON( 1111): WifiActivity: 1
V/SRS_Proc(  370): ParamSet string: screen_state=on
D/WirelessDisplayService(  904): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
V/NotificationService(  904): batLight: Full, plugged
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c800
D/qdlights(  904): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiStateMachine(  904): BroadcastRSSIForIMS, newrssi =-48 , oldRssi= -200
D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1151): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  904):    returned true
D/NetworkPolicy(  904): updateScreenOn: false
I/SensorManager(  904): mEventCount = 1500
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  904): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  904): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  904): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/MtpService( 2363): [MTP][onReceive]+android.intent.action.USER_PRESENT
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
D/MtpService( 2363): [MTP][onReceive]-
I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/NfcService( 1252): applyRouting - 0
D/NfcService( 1252): applyRouting -2
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PMS     (  904): acquireWL(425431b8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1252 1027 null
D/AutoSetting( 1383): receiver - intent: android.intent.action.USER_PRESENT
I/ClockThread( 1111): stop update clock
D/PMS     (  904): releaseWL(425431b8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
D/AutoSetting( 1383): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/WirelessDisplayService(  904): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  904): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  904): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
V/NotificationService(  904): batLight: Full, plugged
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c800
D/qdlights(  904): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/TetherSettings( 4167): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4167): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4167): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4167): Cust_ConnectToPC   : spcsc>false
D/        ( 4167): Cust_ConnectToPC   : IPT>true
D/        ( 4167): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 4167): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4167): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4167): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4167): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/PSReceiver( 4167): onReceive:android.intent.action.USER_PRESENT
D/WIFI_ICON( 1111): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1111): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
W/ContextImpl( 4167): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/SmartNS_PSService( 4167): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4167): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4167):  defaultType:0
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): releaseWL(42dab828): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  904): NetTransition Wakelock for ConnectedState released by timeout
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,D/PMS     (  904): acquireWL(43a1ecf0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1440 10028 null
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1788): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1788): onScreenOn: 1450834004456
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1788): onScreenOn: 1450834004457
D/PMS     (  904): releaseWL(43a1ecf0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  904): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4629 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,V/Tethering(  904): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/SensorManager(  904): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42292e20
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  904): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 2
W/SensorService(  904): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42292e20, eanble = 0, strlen(mName) = 91
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  904): Listener[0] = com.htc.smartdim.sensor_eye@41ecff78
,W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:,
D/PMN     (  904): goingToSleep
,D/ConnectivityService(  904): getNetworkInfo networkType=1 called by com.google.android.music (3881/10154)
I/NetworkMonitor( 3881): type=WIFI subType= reason=null isConnected=true
D/GpsLocationProvider(  904): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  904): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  904): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  904): ignore wifi update if we are not in OPENING or CLOSING
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,I/ConnectivityHelper( 1267): [onReceive] WIFI(1): CONNECTED
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by  (904/1000)
D/PMS     (  904): acquireWL(43f2cd48): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 904 1000 null
D/PMS     (  904): releaseWL(43f2cd48): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  904): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1816/10178)
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by com.htc.launcher (1267/10075)
D/PMS     (  904): acquireWL(43fb8238): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 904 1000 null
D/PMS     (  904): releaseWL(43143f70): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/AlarmManager(  904): [AlarmQueuing] connectivity wifi: true
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.docs (4285/10100)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.setupwizard (4493/10078)
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,V/Tethering(  904): bSetPropertyMultiRAB:false
,D/Tethering(  904): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/Tethering(  904): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  904): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
,I/Tethering(  904): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  904): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  904): Found interface wlan0
,D/Tethering(  904): TetherMasterSM: InitialState processMessage what=3
,D/CaptivePortalTracker(  904): NoActiveNetworkState
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.musicenhancer (3916/10051)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1440/10028)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1877/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.docs (4285/10100)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/htcCheckinService(  904): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,I/acms    ( 1877): Checking Certificates
,D/htcCheckinService(  904): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/CaptivePortalTracker(  904): DelayedCaptiveCheckState
I/acms    ( 1877): Checking Developer Certificates
I/acms    ( 1877): Checking Application Certificates
I/acms    ( 1877): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
,I/acms    ( 1877): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1877): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1877): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1877): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1877): Updating next query delay: 75600000
I/mlserverapp( 1877): MirrorLink is never connected, don't setup ACMS programed checks
,I/mlserverapp( 1877): cancelACMSProgrammedChecks
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/PMS     (  904): acquireWL(42f961c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/PMS     (  904): releaseWL(42f961c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
D/WifiDataStallTracker(  904): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  904): stopDataStallAlarm: current tag=18739 mDataStallAlarmIntent=PendingIntent{4405e098: PendingIntentRecord{423c6628 android broadcastIntent}}
D/AlarmManager(  904): ACTION_SCREEN_OFF
I/AlarmManager(  904): [AlarmQueuing] screen off now: 
I/AlarmManager(  904): [AlarmQueuing] data connection: true
I/AlarmManager(  904): [AlarmQueuing] wifi connection: true
,W/ContextImpl( 4629): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/WifiNative-wlan0(  904): doBoolean: DRIVER SETSUSPENDMODE 1
,D/WifiNative-wlan0(  904): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1151): SET_SCREEN_ON:Off
I/wpa_supplicant( 1151): htc_wext_set_keepalive +
I/wpa_supplicant( 1151): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1151): getPrivFuncNum +	
I/wpa_supplicant( 1151): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1151): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1151): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1151): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1151): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  904):    returned true
,D/PMS     (  904): acquireWL(4407a988): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 904 1000 null
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  370): ParamSet string: screen_state=off
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/SmartSyncUtils( 4629): isEpsOn(), nState = 0
D/PMS     (  904): acquireWL(4361dfe8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4629 1000 null
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  904): releaseWL(4361dfe8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/wpa_supplicant( 1151): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  904):    returned true
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  904): releaseWL(4407a988): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/NetworkPolicy(  904): updateScreenOn: false
D/ConnectivityService(  904): getActiveNetworkInfo called by  (2363/10021)
,D/SmartSyncUtils( 4629): getMobilePolicyEnabled, result = true
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
,W/fb4a(:<default>):UserScope( 4464): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/Process (  904): killProcessQuiet, pid=4285
,W/fb4a(:<default>):UserScope( 4464): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,I/ActivityManager(  904): Killing 4285:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/PMS     (  904): acquireWL(440687c8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1222 10028 null
,D/PMS     (  904): releaseWL(440687c8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ContactMessageStore( 1241): start background delete task...
D/ContactMessageStore( 1241): size: 0 , 0
,D/ContactMessageStore( 1241): Background delete complete
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/GCM     ( 1394): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1394/10028)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1222/10028)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1394/10028)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1394/10028)
D/libc    ( 1394): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1394): [NET] getaddrinfo-,err=8
D/libc    ( 1394): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1394): [NET] getaddrinfo-, 1
,D/libc    ( 1394): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =6919 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/AutoSetting( 1383): service - mHandler: cancel location update
,D/AutoSetting( 1383): service -           changes count: 0
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] getTotalRam: 1873 Mb
D/PMS     (  904): acquireWL(434cd338): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1394 10028 null
I/ActivityManager(  904): Recipient 4285
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
D/PMS     (  904): acquireWL(43b84158): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1440 10028 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1788): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1788): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1788): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1788): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1788): onScreenOff
D/PMS     (  904): releaseWL(43b84158): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/AutoSetting( 1383): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4493): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4493): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1383): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1383): service - onStartCommand() screen is off, don't request location
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.sense.hsp (1383/10053)
D/AutoSetting( 1383): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1383): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.sense.hsp (1383/10053)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.magazines (4524/10151)
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=50 [2][1][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 224
D/libc    (  363): [NET]res_nsend:resplen=79
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1394): [NET] getaddrinfo_proxy-, success
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
W/ActivityManager(  904): Activity pause timeout for ActivityRecord{41a75320 u0 com.test.thalitest/.MainActivity t2 f}
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.plus (4146/10160)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.plus (4146/10160)
,D/Process (  904): killProcessQuiet, pid=4308
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  904): Killing 4308:com.htc.backup/1000 (adj 15): empty #17
D/ConnectivityService(  904): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1816/10178)
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 4308
,W/ContextImpl( 4629): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4629): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4629): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4629): isEpsOn(), nState = 0
D/WifiService(  904): New client listening to asynchronous messages
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41ecff78
,W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  904): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 1
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41ecff78, eanble = 0, strlen(mName) = 36
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  904): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 0
W/SensorService(  904): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41ecff78, eanble = 0, strlen(mName) = 36
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/libc    ( 1394): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1394): [NET] getaddrinfo-,err=8
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41ecff78
E/ActivityThread(  904): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@425abcb0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  904): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@425abcb0 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1394/10028)
D/PMS     (  904): acquireWL(43a399d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1394 10028 null
D/PMS     (  904): releaseWL(43a399d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,E/fb4a(:<default>):LocalFbBroadcastManager( 4464): Called registerBroadcastReceiver twice.
,I/Adreno-EGL( 4599): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4599): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4599): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4599): Local Branch: 
I/Adreno-EGL( 4599): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4599): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4599):                  aa63bbd948f41d15fc72f585e
,W/Settings( 4599): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4464/10026)
,I/CheckinTask( 1222): Sending checkin request (8960 bytes)
,D/GCM     ( 1394): Connected
D/PMS     (  904): acquireWL(434c0e20): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1394 10028 null
D/libc    ( 1222): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1222): [NET] getaddrinfo-,err=8
D/libc    ( 1222): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1222): [NET] getaddrinfo-, 1
,D/libc    ( 1222): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =edb8 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1394/10028)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1394/10028)
D/PMS     (  904): releaseWL(434cd338): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1394/10028)
D/ConnectivityService(  904): reportInetCondition for net 1, percentage: 100 by  (1394/10028)
D/ConnectivityService(  904): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  904): handleInetConditionChange: starting a change hold
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1394/10028)
D/PMS     (  904): releaseWL(434c0e20): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  904): acquireWL(43b7dbc0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1394 10028 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1394/10028)
,D/ConnectivityService(  904): reportInetCondition for net 1, percentage: 100 by  (1394/10028)
,D/ConnectivityService(  904): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/GCM     ( 1394): Message class mpf
D/ConnectivityService(  904): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1394/10028)
,D/ConnectivityService(  904): reportInetCondition for net 1, percentage: 100 by  (1394/10028)
D/ConnectivityService(  904): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  904): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1394/10028)
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 206
D/libc    (  363): [NET]res_nsend:resplen=84
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1222): [NET] getaddrinfo_proxy-, success
D/PMS     (  904): releaseWL(43b7dbc0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  904): acquireWL(43b02408): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1394 10028 null
D/PMS     (  904): releaseWL(43b02408): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/libc    ( 1222): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1222): [NET] getaddrinfo-,err=8
,D/PMS     (  904): releaseWL(43ff29c0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/PMS     (  904): acquireWL(4406b6d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1394 10028 null
,D/PMS     (  904): releaseWL(4406b6d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  904): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  904): sendGeneralBroadcast, restrictEnable=false,
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=13 [22][3][0]
,D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  904): getNetworkInfo networkType=9 called by com.google.android.gms (1222/10028)
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  904): getNetworkInfo networkType=0 called by com.google.android.gms (1222/10028)
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
,W/GLSUser ( 1394): GoogleAccountDataService.getToken()
,W/GLSActivity( 1394): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1394): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1394): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1566): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 1222): awaiting user notification for token
,I/RemoteViews( 1111): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1111): release indeterminate drawable android.widget.OnDemandProgressBar{41c21c38 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1111): com.google.android.gms 1 10 4 12
,I/CheckinTask( 1222): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 1222): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1222/10028)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1222/10028)
,D/PMS     (  904): releaseWL(42d69350): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/GCM     ( 1394): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
E/ActivityThread( 1222): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41cea658 that was originally bound here
E/ActivityThread( 1222): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41cea658 that was originally bound here
E/ActivityThread( 1222): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 1222): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 1222): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 1222): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 1222): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 1222): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 1222): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 1222): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 1222): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 1222): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 1222): 	at bkt.a(SourceFile:226)
E/ActivityThread( 1222): 	at bks.a(SourceFile:298)
E/ActivityThread( 1222): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 1222): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 1222): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1222): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1394): GCM config loaded
,D/libc    (  904): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-,err=8
D/libc    (  904): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  904): [NET] getaddrinfo-, 1
,D/libc    (  904): [NET] getaddrinfo_proxy+,
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =8eff +++++,
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE,
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19,
D/libc    (  363): [NET]res_nsend:resplen=172
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4,
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  904): [NET] getaddrinfo_proxy-, success,
,D/WifiWatchdogStateMachine(  904): Find DNS Address www.htc.com/104.81.130.175,
,I/GAV2    ( 4524): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  904): acquireWL(43b3bb60): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1440 10028 null
,D/PMS     (  904): acquireWL(43b23d70): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1440 10028 null
,D/PMS     (  904): releaseWL(43b3bb60): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  904): releaseWL(43b23d70): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/WifiStateMachine(  904): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  904): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent DefaultState
,W/ActivityManager(  904): Sleep timeout!  Sleeping now.
,D/PMS     (  904): releaseWL(43fb8238): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/Process (  904): killProcessQuiet, pid=4272
,I/ActivityManager(  904): Killing 4272:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  904): Recipient 4272
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1509): service - handleMessage() stop self
,D/AutoSetting( 1509): service - onDestroy() END
,D/AutoSetting( 1509): service - handleMessage() quit looper
,D/CaptivePortalTracker(  904): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  904): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  904): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,W/ActivityManager(  904): Activity destroy timeout for ActivityRecord{41a75320 u0 com.test.thalitest/.MainActivity t2 f}
,D/Process (  904): killProcessQuiet, pid=3916
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3916:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3916
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  405): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  904): acquireWL(436da540): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c9e918: PendingIntentRecord{41d7b228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=126553, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(436da540): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(436d7df0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(436d7df0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1111): closing low battery warning: level=100
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  405): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  904): acquireWL(42382170): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{4205cb88: PendingIntentRecord{420d31b0 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=140325, Int=0
,V/AlarmManager(  904): sending alarm PendingIntent{423d07c0: PendingIntentRecord{41a7eb70 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141273, Int=0
,D/GpsLocationProvider(  904): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  904): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  904): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  904): acquireWL(420efb48): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 904 1000 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1394/10028)
D/PMS     (  904): releaseWL(42382170): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
D/PMS     (  904): acquireWL(41fcf918): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1394 10028 null
,D/AutoSetting( 1383): service - mHandler: update timezone
D/libc    (  904): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-,err=8
D/libc    (  904): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  904): [NET] getaddrinfo-, 1
,D/libc    (  904): [NET] getaddrinfo_proxy+
D/AutoSetting( 1383): service - handleMessage() stop self
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1,
D/libc    (  363): [NET] +++++ res_nsend xid =fcd9 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =,
,D/libc    (  363): [NET] NOT IN CACHE
D/PMS     (  904): releaseWL(41fcf918): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/AutoSetting( 1509): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  904): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1509): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1509): service - onCreate()
,D/AutoSetting( 1383): service - handleMessage() quit looper
,D/AutoSetting( 1383): service - onDestroy() END
,D/AutoSetting( 1509): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,W/ActivityManager(  904): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1509): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/DotMatrix( 1566): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
D/AutoSetting( 1509): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1509): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1509): service - mHandler: update timezone
,D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  904): batLight: Full, plugged
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c800
D/qdlights(  904): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1509): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1509): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1509): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1509): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1566): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/PhoneStatusBar( 1111): removeNotification.gc:56
,I/RemoteViews( 1111): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1111): release indeterminate drawable android.widget.OnDemandProgressBar{41b30bb0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1111): com.htc.htclocationservice 2 6 2 11
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  363): [NET]res_nsend:resplen=243
D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  904): [NET] getaddrinfo_proxy-, success
I/global  (  904): call createSocket() return a new socket.
D/libc    (  904): [NET] getaddrinfo+,hn 13(0x35342e3139322e),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  904): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  904): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  904): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  904):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  904): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  904): releaseWL(420efb48): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  405): AtCmdFwd service not published, waiting... retryCnt : 3
,D/Process (  904): killProcessQuiet, pid=4325
,I/ActivityManager(  904): Killing 4325:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  904): Recipient 4325
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Waited long enough for: ServiceRecord{43b8ed58 u0 com.htc.htclocationservice/.AutoSettingService}
,W/Atfwd_Sendcmd(  405): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  904): acquireWL(423c7660): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PowerUI ( 1111): closing low battery warning: level=100
,D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/PMS     (  904): releaseWL(423c7660): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 1509): service - handleMessage() stop self
,D/AutoSetting( 1509): service - onDestroy() END
,D/AutoSetting( 1509): service - handleMessage() quit looper
,I/ActivityManager(  904): Killing 4344:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  904): killProcessQuiet, pid=4344
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  904): Recipient 4344
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TelephonyReceiver( 1241): switchBindHtcMsgCursor: null
,D/PMS     (  904): acquireWL(425d88c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c9e918: PendingIntentRecord{41d7b228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=186553, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(425d88c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42436f38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): releaseWL(42436f38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  405): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(42d96318): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10026}
,V/AlarmManager(  904): sending alarm PendingIntent{4389ae40: PendingIntentRecord{43eee5d8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=229011, Int=0
,I/ActivityManager(  904): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4684 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  904): sending alarm PendingIntent{425536b0: PendingIntentRecord{42557dc0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1450834113025, Int=10800000
,D/PMS     (  904): releaseWL(42d96318): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.aurora (4684/10047)
,I/ActivityManager(  904): Killing 4358:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  904): killProcessQuiet, pid=4358
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  904): Recipient 4358
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  904): acquireWL(424c12c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10026}
,V/AlarmManager(  904): sending alarm PendingIntent{425ce7e8: PendingIntentRecord{43eee5d8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=231130, Int=0
,D/PMS     (  904): releaseWL(424c12c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1222/10028)
,D/PMS     (  904): acquireWL(423fe0a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(423fe0a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  405): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  405): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  904): acquireWL(424cfd88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c9e918: PendingIntentRecord{41d7b228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=246553, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(424cfd88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43f76010): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43f76010): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
,I/HtcPowerSaver(  904): >> updateStatus
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  405): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  405): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  904): acquireWL(42d9b4b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,D/UsbnetService(  904): onReceive BATTERY_CHANGED
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): releaseWL(42d9b4b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1111): closing low battery warning: level=100
,D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  405): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(440360c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c9e918: PendingIntentRecord{41d7b228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=306552, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(440360c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43f8dd60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43f8dd60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  405): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  904): acquireWL(4252dfd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4252dfd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  904): BroadcastReceiver::onReceive+
,D/UsbnetService(  904): onReceive BATTERY_CHANGED
,D/HtcPowerSaver(  904): updateBatteryInfo
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  405): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  904): acquireWL(43fa11b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c9e918: PendingIntentRecord{41d7b228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=366552, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43fa11b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/GLSUser ( 1394): GoogleAccountDataService.getToken()
,W/GLSActivity( 1394): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1394): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1394): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/RemoteViews( 1111): com.google.android.gms (false,0)
,D/DotMatrix( 1566): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,W/GLSActivity( 1394): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1394): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1394): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1394): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1394): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1394): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1394): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1394): 	at dalvik.system.NativeStart.run(Native Method)
,D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/OnDemandProgressBar( 1111): release indeterminate drawable android.widget.OnDemandProgressBar{41f49a60 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/PlayEventLogger( 4111): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4111): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4111): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4111): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4111): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4111): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4111): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4111): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews.Performance( 1111): com.google.android.gms 1 10 4 12
,D/libc    ( 4111): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4111): [NET] getaddrinfo-,err=8
D/libc    ( 4111): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4111): [NET] getaddrinfo-, 1
,D/libc    ( 4111): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =8d96 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE,
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 281
D/libc    (  363): [NET]res_nsend:resplen=87
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4111): [NET] getaddrinfo_proxy-, success
I/global  ( 4111): call createSocket() return a new socket.
D/libc    ( 4111): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4111): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 4111): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4111): [NET] getaddrinfo-,err=8
,D/PMS     (  904): acquireWL(4401ac50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(4401ac50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/PowerUI ( 1111): closing low battery warning: level=100
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  405): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  405): AtCmdFwd service not published, waiting... retryCnt : 4
,D/Process ( 4395): killProcess, pid=4395
,D/Process ( 4395): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/InputMethodManagerService(  904): Disable input method client, pid=4395
,D/PMS     (  904): acquireWL(431e71e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10026}
,V/AlarmManager(  904): sending alarm PendingIntent{43b9cce0: PendingIntentRecord{440cedd0 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=410887, Int=300000
,D/PMS     (  904): releaseWL(431e71e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/InputDispatcher(  904): channel '424d0768 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  904): channel '424d0768 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  904): Attempted to unregister already unregistered input channel '424d0768 com.test.thalitest.MainActivity (s)'
I/ActivityManager(  904): Recipient 4395
I/ActivityManager(  904): Process com.test.thalitest (pid 4395) has died.
I/WindowManager(  904): WINDOW DIED Window{424d0768 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  904): Client connection lost with reason: 4
,W/WindowManager(  904): Failed looking up window
W/WindowManager(  904): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@42d98270 does not exist
W/WindowManager(  904): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8463)
W/WindowManager(  904): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8454)
W/WindowManager(  904): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1052)
W/WindowManager(  904): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/WindowManager(  904): 	at dalvik.system.NativeStart.run(Native Method)
,I/WindowState(  904): WIN DEATH: null
,D/PMS     (  904): acquireWL(4258da60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end,
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/PMS     (  904): releaseWL(4258da60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): Checking...
D/PowerUI ( 1111): closing low battery warning: level=100
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  405): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(4406bf20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c9e918: PendingIntentRecord{41d7b228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=426552, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4406bf20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43695788): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43695788): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  405): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  904): acquireWL(43f2e448): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43f2e448): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
D/PowerUI ( 1111): closing low battery warning: level=100
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  405): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  904): acquireWL(436de4d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c9e918: PendingIntentRecord{41d7b228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=486552, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false),
,D/PMS     (  904): releaseWL(436de4d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43b6a1e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43b6a1e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  405): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  405): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  904): acquireWL(422b0da0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
D/UsbnetService(  904): BroadcastReceiver::onReceive+
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1111): closing low battery warning: level=100
,D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(422b0da0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  405): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(42b3d008): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c9e918: PendingIntentRecord{41d7b228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=546553, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42b3d008): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43a483e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PMS     (  904): releaseWL(43a483e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43f46820): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(43f46820): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
,I/HtcPowerSaver(  904): >> updateStatus
D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43f54940): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c9e918: PendingIntentRecord{41d7b228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=606552, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43f54940): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(424be450): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): releaseWL(424be450): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  353): inotify_add_watch failed. (No such file or directory),
,D/ContactMessageStore( 1241): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1241): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1241): sku_id=99
D/ContactMessageStore( 1241): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1241): start background delete task...
D/ContactMessageStore( 1241): size: 0 , 0
,D/ContactMessageStore( 1241): Background delete complete
,D/PMS     (  904): acquireWL(434cf020): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c9e918: PendingIntentRecord{41d7b228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=666553, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(434cf020): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43b6f7b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/PMS     (  904): releaseWL(43b6f7b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(434d65d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10073}
,V/AlarmManager(  904): sending alarm PendingIntent{4318b070: PendingIntentRecord{422506e8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1450834566672, Int=0
,D/PMS     (  904): releaseWL(434d65d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,W/GLSUser ( 1394): GoogleAccountDataService.getToken()
,W/GLSActivity( 1394): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1394): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1394): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1394): GoogleAccountDataService.getToken()
,W/GLSActivity( 1394): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1394): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1394): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4111): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4111): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,W/GLSUser ( 1394): GoogleAccountDataService.getToken()
,W/GLSActivity( 1394): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1394): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1394): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4111): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4111): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4111): [1] DailyHygiene.reschedule: Scheduling new run in 28 minutes (failures=2)
,D/PMS     (  904): acquireWL(43b23890): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10073}
,V/AlarmManager(  904): sending alarm PendingIntent{425eecf8: PendingIntentRecord{43f3a1b8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1450834581804, Int=0
,D/PMS     (  904): releaseWL(43b23890): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/Finsky  ( 4111): [1] 5.onFinished: Installation state replication succeeded.
,D/PMS     (  904): acquireWL(43f73b90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
D/PMS     (  904): releaseWL(43f73b90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(436fb8a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c9e918: PendingIntentRecord{41d7b228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=726553, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(436fb8a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(433aba40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(433aba40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(432cb6c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): releaseWL(432cb6c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1111): closing low battery warning: level=100
,D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(4357ad58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000},
,V/AlarmManager(  904): sending alarm PendingIntent{41c9e918: PendingIntentRecord{41d7b228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=786552, Int=0,
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4357ad58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42db1238): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42db1238): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(4362fde0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4362fde0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(42a02270): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c9e918: PendingIntentRecord{41d7b228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=846552, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42a02270): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(433b4f90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(433b4f90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(43ba7e48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10026}
,V/AlarmManager(  904): sending alarm PendingIntent{43b9cce0: PendingIntentRecord{440cedd0 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=710887, Int=300000
,V/AlarmManager(  904): sending alarm PendingIntent{41d2bdf8: PendingIntentRecord{423b9410 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=788574, Int=0
,V/AlarmManager(  904): sending alarm PendingIntent{41c7fe38: PendingIntentRecord{4241ab98 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=870554, Int=0
,D/ConnectivityService(  904): Sampling interval elapsed, updating statistics ..
,D/PMS     (  904): acquireWL(438580f8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 904 1000 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/PMS     (  904): releaseWL(43ba7e48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(437fc590): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/PMS     (  904): releaseWL(438580f8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  904): releaseWL(437fc590): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  904): Done.
,D/ConnectivityService(  904): Setting timer for 720seconds
,D/PMS     (  904): acquireWL(43d4adb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43d4adb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(433ac938): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c9e918: PendingIntentRecord{41d7b228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=906552, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(433ac938): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(432e5c90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(432e5c90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(436ee490): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(436ee490): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(437ad3c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c9e918: PendingIntentRecord{41d7b228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=966552, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(437ad3c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(44024d28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(44024d28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43f5b620): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{424929c0: PendingIntentRecord{42492d10 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450834833380, Int=900000
,V/AlarmManager(  904): sending alarm PendingIntent{42351a58: PendingIntentRecord{43b4f7f0 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450834904809, Int=0
,W/ContextImpl( 4629): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4629): call getInstance()
,D/SmartSyncUtils( 4629): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4629): MY_DEBUG = false
D/PMS     (  904): releaseWL(43f5b620): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  904): acquireWL(43b93c10): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4629 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4629): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4629): [updateNmRange] USERNIGHT_TIMESTART = 20, USERNIGHT_TIMEEND = 23, nStart = 1, nEnd = 2, bNormalRange = true
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,D/SmartSyncScreenOnOffTimeReceiver( 4629): [updateNmRange] new USERNIGHT_TIMESTART = 1, new USERNIGHT_TIMEEND = 2
,W/ContextImpl( 4629): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.updateNmRange:2650 com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.SettingPowerModeAlarm:972 
,I/FeedHostManager( 1267): onReceive() -- Intent { act=com.htc.powersaver.SMARTSYNC_SLEEPMODE_TIME_UPDATE flg=0x10 }
,I/FeedHostManager( 1267): NightMode begin at 0, end at 7
D/PMS     (  904): acquireWL(43f5d958): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 1267 10075 null
,D/SmartSyncScreenOnOffTimeReceiver( 4629): AlarmOnTime = -1
,I/FeedHostManager( 1267): scheduleNextNightModeAlarm - today's NightMode - CurrentTime: 1450834904975, BeginTime: 1450825200000, EndTime: 1450850400000
D/SmartSyncScreenOnOffTimeReceiver( 4629): SettingOnTime = 1450918800000, randomSettingOnTime = 1450916050000
,D/SmartSyncScreenOnOffTimeReceiver( 4629): SettingOffTime = 1450915200000, randomSettingOffTime = 1450915750000
,D/SmartSyncScreenOnOffTimeReceiver( 4629): bDayMode = false
D/PMS     (  904): acquireWL(433af488): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10075}
V/AlarmManager(  904): sending alarm PendingIntent{4214ef40: PendingIntentRecord{44092250 com.htc.launcher broadcastIntent}}, i=com.htc.laucher.NIGHT_MODE_BEGIN, t=0, cnt=1, w=1450825200000, Int=0
,D/PMS     (  904): releaseWL(43f5d958): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 null
D/SmartSyncScreenOnOffTimeReceiver( 4629): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 4629): bNightModeTurnOffOnce = false
,I/FeedHostManager( 1267): onReceive() -- Intent { act=com.htc.laucher.NIGHT_MODE_BEGIN flg=0x14 (has extras) }
D/PMS     (  904): acquireWL(43a5f6a8): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 1267 10075 null
D/PMS     (  904): releaseWL(43a5f6a8): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 null
D/PMS     (  904): releaseWL(43b93c10): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/PMS     (  904): releaseWL(433af488): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10075}
,D/PMS     (  904): acquireWL(430d3c20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10028}
,V/AlarmManager(  904): sending alarm PendingIntent{42d8f8c8: PendingIntentRecord{41a7ea98 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1011579, Int=0
,D/PMS     (  904): acquireWL(435de650): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1394 10028 null
,D/PMS     (  904): releaseWL(435de650): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,D/PMS     (  904): releaseWL(430d3c20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  904): acquireWL(43f935c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1394 10028 null
,D/PMS     (  904): releaseWL(43f935c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,D/PMS     (  904): acquireWL(43311be8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43311be8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(43b62420): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1394 10028 null
,D/GCM     ( 1394): Message class mow
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1394/10028)
D/ConnectivityService(  904): reportInetCondition for net 1, percentage: 100 by  (1394/10028)
D/ConnectivityService(  904): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  904): handleInetConditionChange: starting a change hold
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1394/10028)
,D/PMS     (  904): acquireWL(41d23d98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1394 10028 null
,D/PMS     (  904): releaseWL(43b62420): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  904): releaseWL(41d23d98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  904): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
D/ConnectivityService(  904): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=7 [144][11][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1151): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1151): nl80211: survey data missing!
E/wpa_supplicant( 1151): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1151): environment dirty rate=0 [0][0][0]
,D/PMS     (  904): acquireWL(43b93fe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c9e918: PendingIntentRecord{41d7b228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1026552, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43b93fe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(425d19a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(425d19a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1111): closing low battery warning: level=100
,D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42349ce8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42349ce8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(43b43f30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c9e918: PendingIntentRecord{41d7b228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1086553, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43b43f30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(425bb680): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): releaseWL(425bb680): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=100
,D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(430dbe50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c9e918: PendingIntentRecord{41d7b228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1146553, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(430dbe50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42ccdef0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42ccdef0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1111): closing low battery warning: level=100
,D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(41d741a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(41d741a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(440cc728): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c9e918: PendingIntentRecord{41d7b228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1206553, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(440cc728): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(434b66e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
I/BatteryService(  904): n_update end
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
,I/HtcPowerSaver(  904): >> updateStatus
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): releaseWL(434b66e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  353): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  904): acquireWL(4369d728): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4369d728): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  904): updateBatteryInfo
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43146a18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c9e918: PendingIntentRecord{41d7b228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1266552, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43146a18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(436d1a58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(436d1a58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(4256e420): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): releaseWL(4256e420): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(4320f258): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c9e918: PendingIntentRecord{41d7b228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1326552, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4320f258): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43b56fb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,I/BatteryService(  904): n_update end
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1111): closing low battery warning: level=100
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PMS     (  904): releaseWL(43b56fb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43a35c10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43a35c10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42433a50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c9e918: PendingIntentRecord{41d7b228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1386552, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42433a50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(435440a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(435440a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(433a7340): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(433a7340): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43c09688): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c9e918: PendingIntentRecord{41d7b228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1446552, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43c09688): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(425cddf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(425cddf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,D/PMS     (  904): acquireWL(4315cb10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PMS     (  904): releaseWL(4315cb10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43f9d430): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c9e918: PendingIntentRecord{41d7b228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1506553, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43f9d430): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(4335f3b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4335f3b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  904): BroadcastReceiver::onReceive+
,D/PowerUI ( 1111): closing low battery warning: level=100
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(425ab7a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c9e918: PendingIntentRecord{41d7b228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1566552, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(425ab7a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(4345fa58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4345fa58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43b72b20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  904): updateBatteryInfo
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1111): closing low battery warning: level=100
D/PMS     (  904): runPSCheck
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PMS     (  904): releaseWL(43b72b20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(436ae818): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c9e918: PendingIntentRecord{41d7b228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1626552, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(436ae818): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(425cbe08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(425cbe08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
,D/PowerUI ( 1111): closing low battery warning: level=100
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
,I/HtcPowerSaver(  904): >> updateStatus
D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(440286c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): releaseWL(440286c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(4333c428): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c9e918: PendingIntentRecord{41d7b228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1686552, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4333c428): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43fb5f60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(43fb5f60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(432cde90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1111): closing low battery warning: level=100
,D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): releaseWL(432cde90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42536ea8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c9e918: PendingIntentRecord{41d7b228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1746553, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42536ea8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43f5b2c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
I/BatteryService(  904): n_update end
D/PMS     (  904): releaseWL(43f5b2c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(435d1470): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(435d1470): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
,I/HtcPowerSaver(  904): >> updateStatus
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,D/PMS     (  904): acquireWL(43e605d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c9e918: PendingIntentRecord{41d7b228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1806552, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43e605d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(440725f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(440725f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1111): closing low battery warning: level=100
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  353): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  904): acquireWL(435d4250): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41c9e918: PendingIntentRecord{41d7b228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1866553, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,I/ProcessStatsService(  904): Prepared write state in 30ms
,I/ProcessStatsService(  904): Prepared write state in 15ms
,I/ProcessStatsService(  904): Prepared write state in 9ms
,D/PMS     (  904): releaseWL(435d4250): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  904): Pruning old procstats: /data/system/procstats/state-2015-12-22-01-49-25.bin
,D/PMS     (  904): acquireWL(42da1d70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42da1d70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4761): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4761): ====startRecUseTime====
D/htc.customization.log.level( 4761):  is 
W/CustomizationLogLevel( 4761): Level value is invalid, use default level 2
D/CustomizationManager( 4761):  Read ACC file spent 0.129 (s)
D/CIDMapFileReader( 4761): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4761): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4761): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4761): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4761): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4761): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4761): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4761): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4761): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4761): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4761): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4761): Parsing tag category name = system
I/CustomizationCIDLoader( 4761): Parsing tag category name = application
I/CustomizationCIDLoader( 4761): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4761): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4761): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4761): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4761): Parsing tag category name = Settings
D/CustomizationManager( 4761):  Read CID file spent 0.183 (s)
D/CustomizationManager( 4761):  All configurations done spent 0.184 (s)
W/HtcNativeFlag( 4761): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4761): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4761): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4761): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  904): deletePackageAsUser: pkg=com.test.thalitest, pid=4761, uid=2000 user=0
I/ActivityManager(  904): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
D/Process (  904): killProcessQuiet, pid=4507
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  904): killProcessQuiet, pid=4493
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  904): killProcessQuiet, pid=1383
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  904): Killing 4507:com.android.chrome/u0a96 (adj 15): empty for 1801s
I/ActivityManager(  904): Killing 4493:com.google.android.setupwizard/u0a78 (adj 15): empty for 1801s
I/ActivityManager(  904): Killing 1383:com.htc.sense.hsp/u0a53 (adj 15): empty for 1801s
D/Process (  904): killProcessQuiet, pid=3881
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  904): killProcessQuiet, pid=4167
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  904): killProcessQuiet, pid=4438
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  904): Killing 3881:com.google.android.music:main/u0a154 (adj 15): empty for 1801s
I/ActivityManager(  904): Killing 4167:com.android.settings/1000 (adj 15): empty for 1802s
I/ActivityManager(  904): Killing 4438:com.htc.mms.backupagent/u0a77 (adj 15): empty for 1809s
I/ActivityManager(  904): Killing 4023:com.google.android.gm/u0a107 (adj 15): empty for 1834s
D/Process (  904): killProcessQuiet, pid=4023
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  904): Recipient 4493
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Recipient 4507
I/ActivityManager(  904): Recipient 4438
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Recipient 4023
W/asset   (  904): Copying FileAsset 0x6785e9d0 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Recipient 3881
D/MediaRouterService(  904): Client com.google.android.music (pid 3881): Died!
W/PackageSettings(  904): Skipping PackageSetting{42271078 com.example.hello/10356} due to missing metadata
I/ActivityManager(  904): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Recipient 4167
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  904): Client connection lost with reason: 4
I/ActivityManager(  904): Recipient 1383
I/dalvikvm-heap( 4146): Grow heap (frag case) to 13.521MB for 1821008-byte allocation
I/HtcKeyguardAppUpdateMonitor( 1111): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1566): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
I/acms    ( 1877): Unregistering com.test.thalitest
E/acms    ( 1877): Could not unregister removed application com.test.thalitest
D/DotMatrix( 1566): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1111): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1111): ApplicationsIntentReceiver replacing:false
W/GeofencerStateMachine( 1440): Ignoring removeGeofence because network location is disabled.
W/AccTypeManager( 1327): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1327): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  904): acquireWL(436503c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1440 10028 null
D/PMS     (  904): releaseWL(436503c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/Prism.ItemManager( 1267): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1267): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "sms"
D/VoicemailCleanupService( 1294): Cleaning up data for package: com.test.thalitest
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/Launcher( 1267): Deferring update until onResume
D/Launcher( 1267): waitUntilResume // bindAppsRemoved
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "smsto"
I/InputMethodManagerService(  904): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/AccTypeManager( 1327): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mmsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
D/PackageBroadcastService( 1222): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/ActivityManager(  904): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4775 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "sms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
W/SystemReader( 1252): Cannot find nfc_is_upgrade_to_ar890, use default value instead
E/ExternalAccountType( 1327): Unsupported attribute readOnly
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "smsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mmsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
D/PhoneApp( 1241): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/MultiDex( 4775): install
I/MultiDex( 4775): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/ActivityManager(  904): Delaying start of: ServiceRecord{43f91890 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/MultiDex( 4775): loading existing secondary dex files
I/MultiDex( 4775): load found 1 secondary dex files
I/PeopleContactsSync( 1222): CP2 sync disabled
I/MultiDex( 4775): install done
D/PMS     (  904): acquireWL(42039268): PARTIAL_WAKE_LOCK  Icing 0x1 1222 10028 null
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1222, uid=10028, userID:0
I/Icing   ( 1222): doRemovePackageData com.test.thalitest
D/PMS     (  904): releaseWL(42039268): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  904): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4794 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/ProviderInstaller( 4775): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  904): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4794): install
I/MultiDex( 4794): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4794): loading existing secondary dex files
I/MultiDex( 4794): load found 1 secondary dex files
I/MultiDex( 4794): install done
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Start proc com.htc.sense.hsp for broadcast com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver: pid=4810 uid=10053 gids={50053, 1023, 3003, 5012}
I/ProviderInstaller( 4794): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
D/Process (  904): killProcessQuiet, pid=4524
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4524:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1802s
E/SQLiteDatabase( 4775): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4775): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4775): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4775): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4775): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4775): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4775): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4775): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4775): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4775): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4775): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4775): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4775): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4775): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4775): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4775): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4775): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4775): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4775): threadid=12: thread exiting with uncaught exception (group=0x4164fe30)
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Recipient 4524
E/ActivityManager(  904): App crashed! Process: com.google.android.gms.drive
E/AndroidRuntime( 4775): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4775): Process: com.google.android.gms.drive, PID: 4775
E/AndroidRuntime( 4775): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4775): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4775): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4775): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4775): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4775): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4775): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4775): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4775): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4775): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4775): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4775): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4775): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4775): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4775): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4775): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4775): 	at ctn.run(SourceFile:985)
D/Process ( 4775): killProcess, pid=4775
D/Process ( 4775): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  904): Can't write: system_app_crash
E/DropBoxManagerService(  904): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  904): Recipient 4775
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Process com.google.android.gms.drive (pid 4775) has died.
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
D/PluginProvider( 4810): PluginProvider onCreate
E/SQLiteDatabase( 4810): Failed to open database '/data/data/com.htc.sense.hsp/databases/registry.db'.
E/SQLiteDatabase( 4810): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4810): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4810): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4810): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4810): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.onCreate(Unknown Source)
E/SQLiteDatabase( 4810): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1609)
E/SQLiteDatabase( 4810): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1574)
E/SQLiteDatabase( 4810): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5394)
E/SQLiteDatabase( 4810): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4965)
E/SQLiteDatabase( 4810): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4902)
E/SQLiteDatabase( 4810): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4810): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4810): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4810): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4810): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4810): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4810): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4810): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4810): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4810): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4810): Couldn't open registry.db for writing (will try read-only):
E/SQLiteOpenHelper( 4810): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4810): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4810): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4810): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4810): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4810): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4810): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4810): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4810): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4810): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4810): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4810): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4810): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4810): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4810): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.onCreate(Unknown Source)
E/SQLiteOpenHelper( 4810): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1609)
E/SQLiteOpenHelper( 4810): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1574)
E/SQLiteOpenHelper( 4810): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5394)
E/SQLiteOpenHelper( 4810): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4965)
E/SQLiteOpenHelper( 4810): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4902)
E/SQLiteOpenHelper( 4810): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4810): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4810): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4810): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4810): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4810): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4810): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4810): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4810): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4810): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4810): Opened registry.db in read-only mode
D/PluginProvider( 4810): current plugin count: 19
D/HtcAppUPService( 4810): HtcUPDataProvider onCreate()
W/PackageManager(  904): Unable to load service info ResolveInfo{4202cda0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
I/[PluginManager]RegisterService( 4810): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
W/[PluginManager]RegisterService( 4810): provider may killed!
W/[PluginManager]RegisterService( 4810): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/[PluginManager]RegisterService( 4810): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/[PluginManager]RegisterService( 4810): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/[PluginManager]RegisterService( 4810): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/[PluginManager]RegisterService( 4810): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/[PluginManager]RegisterService( 4810): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
W/[PluginManager]RegisterService( 4810): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:818)
W/[PluginManager]RegisterService( 4810): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:213)
W/[PluginManager]RegisterService( 4810): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/[PluginManager]RegisterService( 4810): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
W/[PluginManager]RegisterService( 4810): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/[PluginManager]RegisterService( 4810): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
W/[PluginManager]RegisterService( 4810): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 4810): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 4810): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 4810): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 4810): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/[PluginManager]RegisterService( 4810): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1267): action: android.intent.action.PACKAGE_REMOVED
D/Process (  904): killProcessQuiet, pid=4146
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/IcingCorporaProvider( 2898): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  904): Killing 4146:com.google.android.apps.plus/u0a160 (adj 15): empty for 1803s
I/ActivityManager(  904): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4830 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/ActivityManager(  904): Recipient 4146
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/SQLiteLog( 2898): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2898): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x643a3af8
W/dalvikvm( 2898): threadid=14: thread exiting with uncaught exception (group=0x4164fe30)
E/AndroidRuntime( 2898): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2898): Process: com.google.android.googlequicksearchbox:search, PID: 2898
E/AndroidRuntime( 2898): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2898): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2898): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2898): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2898): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2898): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2898): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2898): 	at cid.d(PG:186)
E/AndroidRuntime( 2898): 	at clo.g(PG:594)
E/AndroidRuntime( 2898): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2898): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2898): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2898): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2898): 	at clr.tL(PG:827)
E/AndroidRuntime( 2898): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2898): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2898): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2898): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  904): App crashed! Process: com.google.android.googlequicksearchbox:search
D/Process ( 2898): killProcess, pid=2898
D/Process ( 2898): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
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
I/Prism.ItemManager( 1267): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1267): loadItems() com.htc.launcher.pageview.WidgetManager@41b12dd0 +
I/Prism.WidgetManager( 1267): onLoadItems() +
D/RemoteDisplayProvider(  904): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  904): start
W/AtomicFile(  904): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  904): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
I/ActivityManager(  904): Recipient 2898
I/ActivityManager(  904): Process com.google.android.googlequicksearchbox:search (pid 2898) has died.
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 11000ms
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  904): Client com.google.android.googlequicksearchbox (pid 2898): Died!
D/WifiService(  904): Client connection lost with reason: 4
E/SQLiteDatabase( 4830): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4830): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4830): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4830): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4830): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4830): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4830): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4830): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4830): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4830): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4830): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4830): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4830): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4830): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4830): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4830): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4830): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4830): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4830): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4830): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4830): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4830): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4830): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4830): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4830): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4830): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4830): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4830): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4830): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4830): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4830): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4830): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4830): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4830): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4830): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4830): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4830): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4830): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4830): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4830): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4830): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4830): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4830): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4830): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4830): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4830): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4830): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4830): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4830): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4830): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4830): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4830): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4830): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4830): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4830): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4830): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4830): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4830): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4830): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4830): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4830): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4830): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4830): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4830): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4830): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4830): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4830): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4830): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4830): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4830): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4830): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4830): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4830): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4830): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4830): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4830): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4830): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4830): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4830): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4830): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4830): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4830): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4830): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4830): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4830): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4830): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4830): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4830): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4830): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4830): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4830): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4830): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4830): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4830): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4830): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4830): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4830): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4830): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4830): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4830): threadid=11: thread exiting with uncaught exception (group=0x4164fe30)
E/AndroidRuntime( 4830): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4830): Process: com.google.android.apps.docs, PID: 4830
E/AndroidRuntime( 4830): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4830): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4830): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4830): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4830): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4830): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4830): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4830): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4830): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4830): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4830): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4830): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4830): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4830): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4830): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4830): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4830): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4830): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4830): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ActivityManager(  904): App crashed! Process: com.google.android.apps.docs
E/DropBoxManagerService(  904): Can't write: system_app_crash
E/DropBoxManagerService(  904): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 4830): killProcess, pid=4830
D/Process ( 4830): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  904): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4846 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  904): Recipient 4830
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Process com.google.android.apps.docs (pid 4830) has died.

```
