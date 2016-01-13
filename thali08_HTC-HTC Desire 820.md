#### Test 558877588826def_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/WIFI_ICON( 1117): WifiActivity: 1
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,--------- beginning of /dev/log/main
E/cutils-trace( 4606): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4606): ====startRecUseTime====
D/htc.customization.log.level( 4606):  is 
W/CustomizationLogLevel( 4606): Level value is invalid, use default level 2
D/CustomizationManager( 4606):  Read ACC file spent 0.058 (s)
D/CIDMapFileReader( 4606): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4606): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4606): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4606): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4606): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4606): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4606): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4606): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4606): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4606): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4606): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4606): Parsing tag category name = system
I/CustomizationCIDLoader( 4606): Parsing tag category name = application
I/CustomizationCIDLoader( 4606): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4606): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4606): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4606): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4606): Parsing tag category name = Settings
D/CustomizationManager( 4606):  Read CID file spent 0.101 (s)
D/CustomizationManager( 4606):  All configurations done spent 0.102 (s)
W/HtcNativeFlag( 4606): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4606): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4606): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4606): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  907): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  907): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4606
D/PMS     (  907): acquireHCC(4406cec0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 907 1000 null
D/PMS     (  907): acquireHCC(424023d8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 907 1000 null
W/asset   (  907): Copying FileAsset 0x65ed89b0 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  907): @test_code: getHtcIntentFlag: 0 obj: 1130335120
I/FeedHostManager( 1272): [onPause]
I/FeedProviderManager( 1272): onPause
I/FeedHostManager( 1272): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41cc9dd0
I/SocialFeedProvider( 1272): +onPause
I/SocialFeedProvider( 1272): -onPause
D/PMS     (  907): acquireWL(4308ffe0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
I/ActivityManager(  907): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4617 uid=10189 gids={50189, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1272): [trimMemory] 20
W/asset   ( 4617): Copying FileAsset 0x5c884428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4617): Binding Chromium to main looper Looper (main, tid 1) {41b34530}
I/LibraryLoader( 4617): Expected native library version number "",actual native library version number ""
I/chromium( 4617): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4617): Initializing chromium process, renderers=0
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  907): java.lang.Throwable: stack dump
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42bd8060:true
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4617): 1102356328: getState(). Returning 12
D/PMS     (  907): acquireWL(440d8a50): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  907): acquireWL(42068720): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  907): releaseWL(440d8a50): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4617): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4617): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4617): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4617): Local Branch: 
I/Adreno-EGL( 4617): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4617): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4617):                  aa63bbd948f41d15fc72f585e
W/chromium( 4617): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4617): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4617): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4617): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4617): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4617): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4617): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4617): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4617): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4617): CordovaWebView is running on device made by: HTC
,W/AwContents( 4617): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  907): Disable input method client, pid=1272
W/ResourceType( 4617): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4617): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b7b618, mServedView=org.apache.cordova.engine.SystemWebView{41b41280 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/InputMethodManagerService(  907): Enable input method client, pid=4617
W/XT9_C   ( 1211): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1211): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1211): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1211): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 4617): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  907): Displayed com.test.thalitest/.MainActivity: +294ms
D/PMS     (  907): releaseWL(4308ffe0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/SensorManager(  907): mEventCount = 900
D/JsMessageQueue( 4617): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 4617): JniHelper::setJavaVM(0x41605048), pthread_self() = 1663263000
D/JX-Cordova( 4617): jxcore cordova android initializing
I/ActivityManager(  907): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4661 uid=10077 gids={50077}
D/PMS     (  907): acquireWL(4258d9b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10077}
V/AlarmManager(  907): sending alarm PendingIntent{425c06b0: PendingIntentRecord{4257bfc0 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1452688674591, Int=60000
D/PMS     (  907): releaseWL(4258d9b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
D/SMSBackup( 4661): SMSBackupAgentService started
D/SMSBackup( 4661): Checking restore status
D/SMSBackup( 4661): Restore complete
D/SMSBackup( 4661): cancelCheckAlarm
D/SMSBackup( 4661): SMSBackupAgentService completed: completed in 0.0 seconds
D/Process (  907): killProcessQuiet, pid=3279
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3279:com.android.defcontainer/u0a19 (adj 15): empty #17
I/ActivityManager(  907): Recipient 3279
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4617): Grow heap (frag case) to 11.533MB for 63974-byte allocation
,I/dalvikvm-heap( 4617): Grow heap (frag case) to 11.586MB for 95956-byte allocation
,I/dalvikvm-heap( 4617): Grow heap (frag case) to 11.656MB for 143930-byte allocation
,I/dalvikvm-heap( 4617): Grow heap (frag case) to 11.774MB for 215890-byte allocation
,I/dalvikvm-heap( 4617): Grow heap (frag case) to 11.946MB for 323830-byte allocation
,I/dalvikvm-heap( 4617): Grow heap (frag case) to 12.622MB for 728606-byte allocation
,I/dalvikvm-heap( 4617): Grow heap (frag case) to 13.218MB for 1092904-byte allocation
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 39
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 130
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,I/dalvikvm-heap( 4617): Grow heap (frag case) to 14.127MB for 1639352-byte allocation
,I/dalvikvm-heap( 4617): Grow heap (frag case) to 15.453MB for 2459024-byte allocation
,W/CpuWake (  907): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  907): <<release mCpuPerf_Freq wakelock
D/PMS     (  907): releaseHCC(4406cec0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  907): releaseHCC(424023d8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,D/PMS     (  907): acquireWL(434f9790): PARTIAL_WAKE_LOCK  Icing 0x1 1226 10028 null
,I/dalvikvm-heap( 4617): Grow heap (frag case) to 17.585MB for 3688532-byte allocation
,D/Process (  907): killProcessQuiet, pid=3966
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3966:com.google.android.music:main/u0a154 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3966
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  907): Client com.google.android.music (pid 3966): Died!
,D/PMS     (  907): releaseWL(434f9790): PARTIAL_WAKE_LOCK  Icing 0x1 null
,W/jxcore-log( 4617): Initializing JXcore engine
,W/jxcore-log( 4617): JXcore engine is ready
,W/jxcore-log( 4617): Starting JXcore engine
,W/jxcore-log( 4617): Platform android
W/jxcore-log( 4617): 
,W/jxcore-log( 4617): Process ARCH arm
W/jxcore-log( 4617): 
,D/PMS     (  907): releaseWL(42068720): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4617): JXcore Cordova bridge is ready!
I/jxcore-log( 4617): 
,W/jxcore-log( 4617): JXcore engine is started
,I/chromium( 4617): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4617): Toggling radios to true
I/jxcore-log( 4617): 
,D/BluetoothAdapter( 4617): enable(): BT is already enabled..!
,D/WifiManager( 4617): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10189
D/WifiService(  907): New client listening to asynchronous messages
D/WifiService(  907): setWifiEnabled: true pid=4617, uid=10189
E/WifiService(  907): Invoking mWifiStateMachine.setWifiEnabled
,W/HtcDLNAServiceManager(  907): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  907): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  907): Settings:Agentvalue: 2
W/Settings:Agent(  907): >> traceCallingStack()
,W/Settings:Agent(  907): Process.myPid(): 907
W/Settings:Agent(  907): Process.myTid(): 1515
W/Settings:Agent(  907): Process.myUid(): 1000
W/Settings:Agent(  907): 
W/Settings:Agent(  907): 
,W/System.err(  907): java.lang.Throwable: stack dump
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  907): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  907): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  907): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  907): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  907): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  907): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  907): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  907): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  907): 
,W/Settings:Agent(  907): << traceCallingStack(): 2(ms)
,D/WifiManager( 4617): disconnect: Base Package Name=com.test.thalitest, uid=10189
D/WifiNative-wlan0(  907): doBoolean: DISCONNECT
,D/WifiManager( 4617): reconnect: Base Package Name=com.test.thalitest, uid=10189
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): TDLS: Tear down peers
,I/wpa_supplicant( 1173): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4617): Radios toggled,
I/jxcore-log( 4617): 
,I/jxcore-log( 4617): My device name is: HTC-HTC Desire 820,
I/jxcore-log( 4617): 
I/WifiService(  907): isSprintWifiRestricted(): false
I/WifiService(  907): isMdmWifiRestricted(): false
D/WifiSettingsStore(  907): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1173): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1173): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1173): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  907): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  907): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getReasonFromEventString() 3
,D/HTCRequest(  907): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1173): TDLS: Remove peers on disassociation,
D/wpa_supplicant( 1173): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
E/wpa_supplicant( 1173): send_and_recv error -67 - cmd 12
D/WifiMonitor(  907): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1173): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1173): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1173): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1173): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1173): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1173): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1173): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8473bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1173):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error -2 - cmd 12
,I/wpa_supplicant( 1173): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1173): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1173): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1173): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1173): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1173): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1173): EAPOL: SUPP_PAE entering state DISCONNECTED,
D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1173): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1173): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1173): EAPOL: External notification - EAP success=0
,D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1173): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1173): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1173): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1173): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1173): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1173): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1173): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1173): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1173): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
,D/wpa_supplicant( 1173): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1173): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1173): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1173): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1173): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1173): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1173): nl80211: Event message available
D/wpa_supplicant( 1173): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1173): nl80211: Ignore disconnect event triggered during reassociation
D/WifiNative-wlan0(  907):    returned true
D/WifiPerfLock(  907): release()
D/WifiStateMachine(  907): PerfLock released for exiting ConnectedState
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
,D/Tethering(  907): interfaceStatusChanged wlan0, false
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1173): Power_Mode_Type mode = 0
I/wpa_supplicant( 1173): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 61
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/Tethering(  907): [isWifi] getHotspotEnabled: false
,D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  907):    returned true
D/ConnectivityService(  907): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  907): acquireWL(437e8990): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 907 1000 null
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/DhcpStateMachine(  907): [RunningState] Stop DHCP
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  907): doBoolean: RECONNECT
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): Fast associate: Old scan results
I/wpa_supplicant( 1173): wpa_supplicant_scan enter
I/wpa_supplicant( 1173): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1173): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1173): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1173): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1173): nl80211: Event message available
D/wpa_supplicant( 1173): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0(  907):    returned true
,D/WifiStateMachine(  907): Enter handleNetworkDisconnect
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1173): Power_Mode_Type mode = 0
I/wpa_supplicant( 1173): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 61
,D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=19787 mDataStallAlarmIntent=PendingIntent{423f5580: PendingIntentRecord{425e7a78 android broadcastIntent}}
D/WifiNative-wlan0(  907):    returned true
D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0,
D/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  907):    returned true
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiP2pService(  907): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1879/10178)
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,D/UsbnetStateTracker(  907): isAvailable+-
D/UsbnetStateTracker(  907): reconnect
,D/UsbnetStateTracker(  907): isAvailable+-
D/ConnectivityService(  907): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  907): default: reconnect()
D/MDST    (  907): default: setTeardownRequested(false)
D/MDST    (  907): default: setEnableApn apnType =default , enable=true
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WISPrService( 4257): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): Exit handleNetworkDisconnect
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  907): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  907): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  907): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiService(  907): New client listening to asynchronous messages
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,D/WISPrService( 4257): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/libc    (  363): [NET] entry_id:6   entry:0xb7596ea0  removed 
D/libc    (  363): [NET] entry_id:9   entry:0xb758daf8  removed 
D/libc    (  363): [NET] entry_id:8   entry:0xb7596de8  removed 
D/libc    (  363): [NET] entry_id:5   entry:0xb758dc20  removed 
D/libc    (  363): [NET] entry_id:13   entry:0xb75932e8  removed 
D/libc    (  363): [NET] entry_id:7   entry:0xb7592238  removed 
D/libc    (  363): [NET] entry_id:3   entry:0xb7596d38  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb7592428  removed 
D/libc    (  363): [NET] entry_id:11   entry:0xb7592930  removed 
D/libc    (  363): [NET] entry_id:10   entry:0xb7592350  removed 
D/libc    (  363): [NET] entry_id:4   entry:0xb7596c18  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb7596f50  removed 
D/libc    (  363): [NET] entry_id:12   entry:0xb7592aa0  removed 
,D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/ConnectivityService(  907): resetConnections(wlan0, 3)
D/PMS     (  907): acquireWL(4356fb70): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1365 10028 null
D/ConnectivityService(  907): flush DNS cache for net 1(wlan0)
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/PMS     (  907): acquireWL(43560cc0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10028 null
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1879/10178)
D/PMS     (  907): releaseWL(43560cc0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
D/WISPrService( 4257): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/WISPrService( 4257): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/PMS     (  907): acquireWL(42447448): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  907): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  907): reportInetCondition for net -1, percentage: 0 by  (1365/10028)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/WifiStateMachine(  907): startScan Pid: 907 Uid 1000
D/WifiNative-wlan0(  907): doBoolean: SCAN
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1173): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/WifiNative-wlan0(  907):    returned false
D/BatSI   (  907): WIFI scan started for: 650a0300 uid:1000
D/PMS     (  907): releaseWL(4356fb70): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
I//system/bin/ip(  363): RTNETLINK answers: No such process
I/logwrapper(  363): /system/bin/ip terminated by exit(2)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1365/10028)
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:2
D/PMS     (  907): releaseWL(42447448): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  907): mActiveDefaultNetwork: -1
D/ConnectivityService(  907): handleInetConditionChange: no active default network - ignore
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  907): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4687 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
,D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  907): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/PMS     (  907): acquireWL(42109960): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): releaseWL(42109960): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/CaptivePortalTracker(  907): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  907): NoActiveNetworkState
D/Tethering(  907): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  907): bSetPropertyMultiRAB:false
D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  907): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  907): ipv4Default null
I/Tethering(  907): No IPv4 upstream interface, giving up.
,D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
,I/ConnectivityHelper( 1272): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4478/10100)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1418/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1879/10178)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1921/1000)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1272/10075)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4478/10100)
,I/MusicStore( 4687): Database version: 95
W/ContextImpl( 4687): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
W/ContextImpl( 4687): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4687): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4687): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4687): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4687, uid=10154, userID:0
,D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
,D/MediaRouterService(  907): Client com.google.android.music (pid 4687): Registered
,I/MediaRouter( 4687): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (2042/10021)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.music (4687/10154)
,I/ActivityManager(  907): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4707 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4687): getSelectedRoute
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (4687/10154)
I/NetworkMonitor( 4687): type=WIFI subType= reason=null isConnected=false
,D/ACRA    ( 4707): ACRA is enabled for com.facebook.katana, intializing...
,D/Process (  907): killProcessQuiet, pid=4404
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/ACRA    ( 4707): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4707): Looking for error files in /data/data/com.facebook.katana/app_minidumps
I/ActivityManager(  907): Killing 4404:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=4687, uid=10154, userID:0
I/ActivityManager(  907): Recipient 4404
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  907): Client connection lost with reason: 4
,W/SystemClassLoaderAdder( 4707): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4707): Preparing secondary program dexes.
V/DexLibLoader( 4707): Loaded 4 raw lines of metadata.
V/DexLibLoader( 4707): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
,V/DexLibLoader( 4707): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4707): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4707): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4707): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4707): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4707): Dex already copied
D/OdexVerifier( 4707): Odex verification is skipped.
,V/DexLibLoader( 4707): Creating class loader
,V/DexLibLoader( 4707): Finished creating class loader
V/DexLibLoader( 4707): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4707): Dex already copied
D/OdexVerifier( 4707): Odex verification is skipped.
,V/DexLibLoader( 4707): Creating class loader
,V/DexLibLoader( 4707): Finished creating class loader
V/DexLibLoader( 4707): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
,V/DexLibLoader( 4707): Dex already copied
D/OdexVerifier( 4707): Odex verification is skipped.
,V/DexLibLoader( 4707): Creating class loader
,V/DexLibLoader( 4707): Finished creating class loader
V/DexLibLoader( 4707): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4707): Dex already copied
D/OdexVerifier( 4707): Odex verification is skipped.
,V/DexLibLoader( 4707): Creating class loader
V/DexLibLoader( 4707): Finished creating class loader,
,V/DexLibLoader( 4707): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4707): DexLibLoader.ensureDexLoaded took 16 ms
,W/dalvikvm( 4707): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4707): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4707): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4707): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4707): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4707): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4707): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1173): nl80211: Event message available
D/wpa_supplicant( 1173): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1173): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1173): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2452 level=-77
I/wpa_supplicant( 1173): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-82
I/wpa_supplicant( 1173): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-87
I/wpa_supplicant( 1173): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-89
D/wpa_supplicant( 1173): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=7 entropy=0
D/wpa_supplicant( 1173): Add randomness: count=8 entropy=1
D/wpa_supplicant( 1173): Add randomness: count=9 entropy=2
D/wpa_supplicant( 1173): Add randomness: count=10 entropy=3
D/wpa_supplicant( 1173): Add randomness: count=11 entropy=4
D/wpa_supplicant( 1173): Add randomness: count=12 entropy=5
D/wpa_supplicant( 1173): Add randomness: count=13 entropy=6
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1173): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: AP dc:4a:3e:0f:c2:f1 type 0 added
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): Selecting BSS from priority group 1
I/wpa_supplicant( 1173): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1173): 0: c0:f,f:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1173): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1173): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1173):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1173):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1173): Start print parameters
I/wpa_supplicant( 1173): wpa_s->wpa_state is 3
I/wpa_supplicant( 1173): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1173): isConcurrentMode() is 0
I/wpa_supplicant( 1173): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1173): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1173): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1173): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1173): wpa_s->reassociate is 1
I/wpa_supplicant( 1173): wpa_s->is_screen_on 1
I/wpa_supplicant( 1173): wpa_s->ifname wlan0
I/wpa_supplicant( 1173): End print parameters
I/wpa_supplicant( 1173): selected network = 1
D/wpa_supplicant( 1173): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb84754e8  current_ssid=0x0
D/wpa_supplicant( 1173): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1173): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1173): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1173): check if in concurrent case
I/wpa_supplicant( 1173): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState,
D/wpa_supplicant( 1173): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1173): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1173): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1173): RSN: PMKSA cache search - network_ctx=0xb84754e8 try_opportunistic=0
D/wpa_supplicant( 1173): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1173): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1173): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1173): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT),
D/wpa_supplicant( 1173): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1173): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1173): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1173): nl80211: Unsubscribe mgmt frames handle 0xb8474718 (mode change)
D/wpa_supplicant( 1173): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8474718
D/wpa_supplicant( 1173): nl80211: Register frame type=0xd0 nl_handle=0xb8474718
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1173): nl80211: Register frame type=0xd0 nl_handle=0xb8474718
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1173): nl80211: Register frame type=0xd0 nl_handle=0xb8474718
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 58,
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1173): nl80211: Register frame type=0xd0 nl_handle=0xb8474718
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1173): nl80211: Register frame type=0xd0 nl_handle=0xb8474718
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1173): nl80211: Register frame type=0xd0 nl_handle=0xb8474718
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1173): nl80211: Register frame type=0xd0 nl_handle=0xb8474718
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1173): nl80211: Register frame type=0xd0 nl_handle=0xb8474718
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1173): nl80211: Register frame type=0xd0 nl_handle=0xb8474718
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1173): nl80211: Register frame type=0xd0 nl_handle=0xb8474718
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1173): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1173):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1173):   * freq=2412
,D/wpa_supplicant( 1173):   * Auth Type 0
D/wpa_supplicant( 1173):   * WPA Versions 0x2
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1173): nl80211: Connect request send successfully
D/wpa_supplicant( 1173): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1173): EAPOL: External notification - EAP fail=0
,D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1173): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1173): reply (923) for get BSS: id=0
,I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1173): freq=5220
I/wpa_supplicant( 1173): level=-47
I/wpa_supplicant( 1173): tsf=0000000108631283
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
,I/wpa_supplicant( 1173): ssid=NG7005g
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=1
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-57
,I/wpa_supplicant( 1173): tsf=0000000108631299
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG700
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=2
,I/wpa_supplicant( 1173): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1173): freq=2452
I/wpa_supplicant( 1173): level=-77
I/wpa_supplicant( 1173): tsf=0000000108631304
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS],
I/wpa_supplicant( 1173): ssid=Gonzos
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=3
I/wpa_supplicant( 1173): bssid=9e:93:4e:3e:ba:c5
,I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-82
I/wpa_supplicant( 1173): tsf=0000000108631308
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1173): ssid=DIRECT-qjWorkCentre 3025,
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=4
I/wpa_supplicant( 1173): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-57
,I/wpa_supplicant( 1173): tsf=0000000108631295
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1173): ssid=01ABC
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=5
,I/wpa_supplicant( 1173): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-87
I/wpa_supplicant( 1173): tsf=0000000108631317
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS],
I/wpa_supplicant( 1173): ssid=DIRECT-AD-HP DeskJet 3630 series
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=6
I/wpa_supplicant( 1173): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1173): freq=2437,
I/wpa_supplicant( 1173): level=-89
I/wpa_supplicant( 1173): tsf=0000000108631313
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC4688432
I/wpa_supplicant( 1173): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 108631283, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 108631299, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000),
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2452, timestamp: 108631304, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -82, frequency: 2437, timestamp: 108631308, distance: ?(cm), distanceSd: ?(cm),
D/WifiStateMachine(  907): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 108631295, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -87, frequency: 2437, timestamp: 108631317, distance: ?(cm), distanceSd: ?(cm),
D/WifiStateMachine(  907): 6: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -89, frequency: 2437, timestamp: 108631313, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 7 to mScanResults
,D/BatSI   (  907): WIFI scan stopped for: 640a0300 uid:1000
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (7) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/dalvikvm( 4707): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;,
,D/wpa_supplicant( 1173): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1173): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1173): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1173): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1173): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1173): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1173): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1173): nl80211: Event message available
D/wpa_supplicant( 1173): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1173): nl80211: Connect event
D/wpa_supplicant( 1173): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1173): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1173): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1173): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1173): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1173): Add randomness: count=14 entropy=7
I/wpa_supplicant( 1173): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1173): TDLS: Remove peers on association
D/wpa_supplicant( 1173): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1173): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1173): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1173): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1173): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1173): EAPOL: enable timer tick
D/wpa_supplicant( 1173): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1173): htc_wext_set_keepalive +
I/wpa_supplicant( 1173): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1173): getPrivFuncNum +	
I/wpa_supplicant( 1173): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1173): htc_wext_set_keepalive fnum = 0x8bf6
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
I/wpa_supplicant( 1173): htc_wext_set_keepalive - ret = 0
D/WifiMonitor(  907): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  907): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  907): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  907): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  907): handleAssociatedWithEvent. bLFR =false
D/WifiMonito,r(  907): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  907): Enter handleAssociatedWithEvent
D/WifiStateMachine(  907): Associated
D/WifiStateMachine(  907): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  907): Exit handleAssociatedWithEvent
I/wpa_supplicant( 1173): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1173): Get randomness: len=32 entropy=8
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  907): BSSID was changed, update WiFi database
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/Tethering(  907): interfaceStatusChanged wlan0, true
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  907): This record is existed, only update it...
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  907): updateConnectedAP...
I/wpa_supplicant( 1173): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1173): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb84749f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1173):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1173): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1173): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1173): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f89b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1173):    broadcast key
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 11
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1173): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1173): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1173): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1173): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  907): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1173): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1173): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1173): set send_ind_to_ndc = 0
I/wpa_supplicant( 1173): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1173): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1173): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1173): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1173): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1173): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1173): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1173): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1173): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1173): EAPOL authentication completed successfully
I/wpa_supplicant( 1173): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1173): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1173): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1173): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
D/Tethering(  907): interfaceStatusChanged wlan0, true
D/Tethering(  907): [isWifi] getHotspotEnabled: false
W/dalvikvm( 4707): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/WifiStateMachine(  907): fetchFrequency(), freq = 2412
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  907): This record is existed, only update it...
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  907): updateConnectedAP...
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WISPrService( 4257): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4257): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/DhcpStateMachine(  907): [StoppedState] Start DHCP
D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 1
D/WifiStateMachine(  907): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  907): acquireWL(425e67c0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 907 1000 null
D/WifiStateMachine(  907): handlePreDhcpSetup mBluetoothConnectionActive: false
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1173): Power_Mode_Type mode = 1
I/wpa_supplicant( 1173): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  907):    returned null
E/WifiStateMachine(  907): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  907):    returned null
D/WifiP2pService(  907): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@424dbef0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@424dbef0 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:0
,E/FbInjectorInitializer( 4707): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4707): Verify
,D/WifiService(  907): New client listening to asynchronous messages
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4707/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4707): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4707): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4707): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  907): killProcessQuiet, pid=4426
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 4426:com.htc.mediamanager/u0a32 (adj 15): empty #17
,D/PMS     (  907): acquireWL(4263e790): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1226 10028 null
,I/ActivityManager(  907): Recipient 4426
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(43c9b220): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1226 10028 null
,D/PMS     (  907): releaseWL(4263e790): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,D/PMS     (  907): acquireWL(42e1c800): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{42104638: PendingIntentRecord{423c0178 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=109225, Int=0
,D/GCM     ( 1365): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1365/10028)
,D/PMS     (  907): releaseWL(42e1c800): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,D/PMS     (  907): releaseWL(43c9b220): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/AutoSetting( 1399): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ClockThread( 1117): now=1452688680059 next=59941
,D/AutoSetting( 1399): Util - no network available!
I/ActivityManager(  907): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4739 uid=10078 gids={50078, 3003, 5012}
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1399/10053)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1399/10053)
D/AutoSetting( 1399): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1399): service - mHandler: cancel location update
D/AutoSetting( 1399): service -           changes count: 0
,W/fb4a(:<default>):UserScope( 4707): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4707): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4707): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4739): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4739): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4739): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4739): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  907): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4753 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=4108
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 4108:com.google.android.gm/u0a107 (adj 15): empty #17
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4739/10078)
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4707): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4739/10078)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4739/10078)
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  907): Recipient 4108
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/dalvikvm( 4707): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4707): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4707): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4707): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4707): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4707): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4707): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4707): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4707): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4707): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4707): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4707): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4707): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4707): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4707): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4707): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4707): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4707): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,D/Process (  907): killProcessQuiet, pid=4341
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4770 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
I/ActivityManager(  907): Killing 4341:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/dalvikvm-heap( 4707): Grow heap (frag case) to 9.902MB for 39954-byte allocation
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4770): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4770): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4707): Grow heap (frag case) to 9.978MB for 79892-byte allocation
,W/GAV2    ( 4770): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4770): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4770): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
I/ActivityManager(  907): Recipient 4341
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4707): Grow heap (frag case) to 10.050MB for 84664-byte allocation
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4770/10151)
,V/WebViewChromiumFactoryProvider( 4770): Binding Chromium to main looper Looper (main, tid 1) {41b2ec20}
,I/LibraryLoader( 4770): Expected native library version number "",actual native library version number ""
,I/chromium( 4770): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4770): Initializing chromium process, renderers=0
,D/PMS     (  907): acquireWL(43140d58): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
,D/PMS     (  907): acquireWL(43162748): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
,E/AudioManagerAndroid( 4770): BLUETOOTH permission is missing!
D/PMS     (  907): releaseWL(43162748): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4770): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4770): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4770): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4770): Local Branch: 
I/Adreno-EGL( 4770): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4770): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4770):                  aa63bbd948f41d15fc72f585e
,I/dalvikvm-heap( 4707): Grow heap (frag case) to 10.271MB for 75760-byte allocation
,I/NSApplication( 4770): Starting up...
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4707/10026)
W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43610e88 u0 ReceiverList{43559668 4707 com.facebook.katana/10026/u0 remote:4260cd90}}
W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43610e88 u0 ReceiverList{43559668 4707 com.facebook.katana/10026/u0 remote:4260cd90}}
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4770/10151)
W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4352df90 u0 ReceiverList{4352df30 4707 com.facebook.katana/10026/u0 remote:4351f0e0}}
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4770/10151)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4235/10160)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4235/10160)
,D/Process (  907): killProcessQuiet, pid=4478
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 4478:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4707/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4707/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1879/10178)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4707/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1879/10178)
,D/GCM     ( 1365): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/PMS     (  907): acquireWL(42d91e78): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1418 10028 null
,D/PMS     (  907): releaseWL(42d91e78): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/PMS     (  907): Going to sleep due to screen timeout...
,I/ActivityManager(  907): mThumbnailWidth=360, mThumbnailHeight=640
I/ActivityManager(  907): Recipient 4478
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421d5778
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = CM36282 Light sensor
D/wpa_supplicant( 1173): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1173): EAPOL: disable timer tick
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
,W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421d5778, eanble = 0, strlen(mName) = 59
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  907): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@422f8420
W/SensorService(  907): Listener[1] = com.htc.smartdim.sensor_eye@41dcc3a8
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/BatSI   (  907): Couldn't get kernel wake lock stats
V/LightsService(  907): setLight #2: color=#0
D/qdlights(  907): set_light_buttons_func: on=0 brightness=0
V/LightsService(  907): setLight #0: color=#0
,D/GCoreFlp( 1418): Unknown pending intent to remove.
D/WirelessDisplayService(  907): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  907): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
D/PMS     (  907): acquireWL(42be2d18): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1418 10028 null
W/PMS     (  907): mWirelessDisplayManager is null
D/PMS     (  907): releaseWL(42be2d18): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/SurfaceControl(  907): Excessive delay in blankDisplay() while turning screen off: 391ms
D/PMS     (  907): nativeSetInteractive:false
D/PMS     (  907): nativeSetInteractive:false done
D/PMS     (  907): nativeSetAutoSuspend:true
D/PMS     (  907): nativeSetAutoSuspend:true done
D/HABCtrl (  907): TPE algorithm. remove timeout.
D/PMS     (  907): OOBE c monitor 11
I/InputManager(  907): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  907): screenObserver, isScreenOn=false
V/KeyguardServiceDelegate(  907): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42be2488)
D/NfcService( 1258): ScreenObserver: OFF,
,D/NfcService( 1258): applyRouting - 0
,I/IntentController( 1117): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMN     (  907): wakingUp
,I/InputMethodManagerService(  907): Disable input method client, pid=4617
,V/KeyguardServiceDelegate(  907): **** SHOWN CALLED ****
,D/NfcService( 1258): applyRouting -2
D/PMS     (  907): acquireWL(437a2d90): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1258 1027 null
I/WindowManager(  907): No lock screen! windowToken=null
D/PMS     (  907): acquireWL(437c2578): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(437a2d90): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/WirelessDisplayService(  907): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/MtpService( 2042): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2042): [MTP][onReceive]-
,D/NfcService( 1258): applyRouting - 0
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  907): releaseWL(437c2578): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMN     (  907): onScreenOn
D/HtcPowerSaver(  907): updateBatteryInfo
,D/PMS     (  907): acquireWL(441010e8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1258 1027 null
D/NfcService( 1258): applyRouting -2
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/AutoSetting( 1399): receiver - intent: android.intent.action.USER_PRESENT
D/PMS     (  907): releaseWL(441010e8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/AutoSetting( 1399): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
D/AlarmManager(  907): ACTION_SCREEN_ON
I/AlarmManager(  907): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done recovering
I/AlarmManager(  907): [AlarmQueuing] recover EPS screen off blocked alarms
,D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_ON
D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 1
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1173): SET_SCREEN_ON:On
I/wpa_supplicant( 1173): htc_wext_set_keepalive +
I/wpa_supplicant( 1173): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1173): getPrivFuncNum +	
I/wpa_supplicant( 1173): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1173): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1173): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1173): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1173): htc_wext_set_TX_TRACKING - ret = 0
,D/WifiNative-wlan0(  907):    returned true
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/TetherSettings( 4257): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4257): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4257): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4257): Cust_ConnectToPC   : spcsc>false
D/        ( 4257): Cust_ConnectToPC   : IPT>true
,D/        ( 4257): Cust_ConnectToPC   : Singel_USB>false
,I/ClockThread( 1117): stop update clock
I/AlarmManager(  907): [AlarmQueuing] done EPS screen off alarm recovering
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=100 [1][1][0]
I/wpa_supplicant( 1173): Change stage from stage0 to stage3
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  907):    returned true
W/Settings( 4257): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,V/SRS_Proc(  370): ParamSet string: screen_state=on
D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,E/SmartNS_Utility( 4257): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4257): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4257): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 4257): onReceive:android.intent.action.USER_PRESENT
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
D/NetworkPolicy(  907): updateScreenOn: false
W/ContextImpl( 4257): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/SmartNS_PSService( 4257): onReceive:android.intent.action.USER_PRESENT
,W/Settings( 4257): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4257):  defaultType:0
D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4707): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4707): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
I/ActivityManager(  907): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4833 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  907): acquireWL(4372a508): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1418 10028 null
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1851): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1851): onScreenOn: 1452688681203
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1851): onScreenOn: 1452688681203
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/PMS     (  907): releaseWL(4372a508): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,W/ContextImpl( 4833): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@422f8420
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@422f8420, eanble = 0, strlen(mName) = 91
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  907): Listener[0] = com.htc.smartdim.sensor_eye@41dcc3a8
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1173): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1173): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
D/PMN     (  907): goingToSleep
D/PMS     (  907): acquireWL(437d8d68): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 907 1000 null
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  907):    returned true
D/SmartSyncUtils( 4833): isEpsOn(), nState = 0
,D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=19788 mDataStallAlarmIntent=null
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  907): releaseWL(425e67c0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/AlarmManager(  907): ACTION_SCREEN_OFF
I/AlarmManager(  907): [AlarmQueuing] screen off now: 
I/AlarmManager(  907): [AlarmQueuing] data connection: true
I/AlarmManager(  907): [AlarmQueuing] wifi connection: true
D/PMS     (  907): acquireWL(43498c90): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4833 1000 null
,D/PMS     (  907): acquireWL(43712de0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 907 1000 null
D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1173): SET_SCREEN_ON:Off
I/wpa_supplicant( 1173): htc_wext_set_keepalive +
I/wpa_supplicant( 1173): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1173): getPrivFuncNum +	
I/wpa_supplicant( 1173): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1173): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1173): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1173): htc_wext_set_keepalive gateway addr = 00000000
I/wpa_supplicant( 1173): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): gateway: /192.168.1.1
,D/WifiNative-wlan0(  907): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1173): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1173): htc_wext_set_keepalive +
I/wpa_supplicant( 1173): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1173): getPrivFuncNum +	
I/wpa_supplicant( 1173): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1173): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1173): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1173): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1173): htc_wext_set_keepalive - ret = 0
V/SRS_Proc(  370): ParamSet string: screen_state=off
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  907): VerifyingLinkState enter
,D/WifiStateMachine(  907): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/SmartSyncUtils( 4833): getMobilePolicyEnabled, result = true
D/PMS     (  907): releaseWL(43498c90): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/Process (  907): killProcessQuiet, pid=4495
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4495:com.htc.backup/1000 (adj 15): empty #17
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/NetworkPolicy(  907): updateScreenOn: false
,D/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  907): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -57, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
D/PMS     (  907): releaseWL(43712de0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
I/ActivityManager(  907): Recipient 4495
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiWatchdogStateMachine(  907): WAN detection
V/NetworkPolicy(  907): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/ContextImpl( 4833): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  907): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  907): default: teardown()
D/MDST    (  907): default: setTeardownRequested(true)
,D/MDST    (  907): default: setEnableApn apnType =default , enable=false
D/WISPrService( 4257): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/SmartSyncUtils( 4833): isEpsOn(), nState = 0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  907): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/SmartSyncUtils( 4833): getMobilePolicyEnabled, result = true
,D/WifiStateMachine(  907): syncGetConfiguredNetworks
D/MDST    (  907): default: setTeardownRequested(true)
,D/ConnectivityService(  907): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  907): Unexpected mtu value: android.net.wifi.WifiStateTracker@4245f6d8
D/WifiService(  907): New client listening to asynchronous messages
,D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/SmartSyncUtils( 4833): isEpsOn(), nState = 0
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  907): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  907): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  907): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  907): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/ContactMessageStore( 1247): start background delete task...
D/ConnectivityService(  907): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED connected
D/PMS     (  907): acquireWL(437d5928): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4739/10078)
D/ContactMessageStore( 1247): size: 0 , 0
,D/ContactMessageStore( 1247): Background delete complete
D/WirelessDisplayService(  907): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  907):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41dcc3a8
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 1
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41dcc3a8, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 0
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41dcc3a8, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41dcc3a8
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1879/10178)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
,E/ActivityThread(  907): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42613298 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  907): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42613298 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  907): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  907): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  907): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  907): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  907): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  907): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  907): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  907): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  907): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  907): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  907): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  907): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  907): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  907): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  907): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  907): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  907): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  907): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  907): 	at dalvik.system.NativeStart.main(Native Method)
I/QuickSettingWifi( 1117): receive.wifiConnect:true wifiAPname:NG700 elapse:1
I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
I/logwrapper(  363): /system/bin/ip terminated by exit(254)
,D/AutoSetting( 1399): service - mHandler: cancel location update
,D/AutoSetting( 1399): service -           changes count: 0
,D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1585): [EventService] getTotalRam: 1873 Mb
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1851): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1851): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1851): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1851): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1851): onScreenOff
D/PMS     (  907): acquireWL(431225e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1418 10028 null
D/PMS     (  907): releaseWL(431225e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/ConnectivityService(  907): mActiveDefaultNetwork: WIFI
,D/PMS     (  907): acquireWL(43543288): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1226 10028 null
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/PMS     (  907): acquireWL(434f75b8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1226 10028 null
D/PMS     (  907): releaseWL(43543288): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/PMS     (  907): releaseWL(437d5928): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,D/GCM     ( 1365): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/PMS     (  907): releaseWL(434f75b8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,W/ActivityManager(  907): Activity pause timeout for ActivityRecord{4400d800 u0 com.test.thalitest/.MainActivity t2}
,D/PMS     (  907): releaseWL(437e8990): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  907): NetTransition Wakelock for ConnectedState released by timeout
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: true
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,D/CaptivePortalTracker(  907): NoActiveNetworkState
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/PMS     (  907): acquireWL(4414abb0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1272/10075)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1921/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1879/10178)
I/ConnectivityHelper( 1272): [onReceive] WIFI(1): CONNECTED
,V/Tethering(  907): bSetPropertyMultiRAB:false
D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,I/NetworkMonitor( 4687): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (4687/10154)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1418/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4707/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4739/10078)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.musicenhancer (3989/10051)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
I/Tethering(  907): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  907): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
,I/Tethering(  907): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  907): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  907): Found interface wlan0
D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,I/acms    ( 1921): Checking Certificates
I/acms    ( 1921): Checking Developer Certificates
I/acms    ( 1921): Checking Application Certificates
,I/acms    ( 1921): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1921): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1921): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4707/10026)
I/acms    ( 1921): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1921): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1921): Updating next query delay: 75600000
I/mlserverapp( 1921): MirrorLink is never connected, don't setup ACMS programed checks
,I/mlserverapp( 1921): cancelACMSProgrammedChecks
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  907): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  907): acquireWL(440bea60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4707/10026)
D/PMS     (  907): releaseWL(440bea60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  907): releaseWL(4414abb0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (2042/10021)
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(43775ae0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1226 10028 null
,D/PMS     (  907): acquireWL(43773768): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1226 10028 null
,D/PMS     (  907): releaseWL(43775ae0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,D/GCM     ( 1365): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  907): releaseWL(43773768): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1365/10028)
,D/PMS     (  907): acquireWL(43730928): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1365 10028 null
D/libc    ( 1365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1365): [NET] getaddrinfo-,err=8
D/libc    ( 1365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1365): [NET] getaddrinfo-, 1
D/libc    ( 1365): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =21bd +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
,D/AutoSetting( 1399): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4739): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4739): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1399): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1399): service - onStartCommand() screen is off, don't request location
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1399/10053)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1399/10053)
D/AutoSetting( 1399): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1399): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4770/10151)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 223
D/libc    (  363): [NET]res_nsend:resplen=79
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1365): [NET] getaddrinfo_proxy-, success
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [2][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4235/10160)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4235/10160)
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1879/10178)
,D/GCM     ( 1365): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/dalvikvm-heap( 4235): Grow heap (frag case) to 13.657MB for 1821008-byte allocation
,D/libc    ( 1365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1365): [NET] getaddrinfo-,err=8
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1365/10028)
D/PMS     (  907): acquireWL(4264b2d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10028 null
D/PMS     (  907): releaseWL(4264b2d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/GCM     ( 1365): Connected
D/PMS     (  907): acquireWL(4258e100): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1365 10028 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1365/10028)
,D/PMS     (  907): releaseWL(43730928): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1365/10028)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1365/10028)
,D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1365/10028)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4707/10026)
,D/PMS     (  907): releaseWL(4258e100): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  907): acquireWL(4239f628): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1365 10028 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4707/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1365/10028)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1365/10028)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
,D/GCM     ( 1365): Message class mpf
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1365/10028)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1365/10028)
,D/PMS     (  907): acquireWL(423a1b28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10028 null
,D/PMS     (  907): releaseWL(4239f628): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  907): releaseWL(423a1b28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
W/fb4a(:<default>):UserScope( 4707): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/fb4a(:<default>):UserScope( 4707): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4707/10026)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=25 [8][2][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4707/10026)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4707): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4707/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4707/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4707/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4707/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4707/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4707/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4707/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4707/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4707/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4707/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4707/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4707/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4707/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4707/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4707/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4707/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4707/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4707/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4707/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4707/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4707/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4707/10026)
,D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): releaseWL(43140d58): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/PMS     (  907): acquireWL(42515c00): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4687 10154 null
,W/ContextImpl( 4687): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4687): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4687, uid=10154, userID:0
,I/MusicLeanback( 4687): Conditions not met for autocaching.
,I/MusicLeanback( 4687): Stop autocaching.
D/PMS     (  907): releaseWL(42515c00): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =da1 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 7,
D/libc    (  363): [NET]res_nsend:resplen=172
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  907): Find DNS Address www.htc.com/23.206.98.145,
,D/WifiStateMachine(  907): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,D/AutoSetting( 1501): service - handleMessage() stop self
,D/AutoSetting( 1501): service - onDestroy() END
,D/AutoSetting( 1501): service - handleMessage() quit looper
,D/Process (  907): killProcessQuiet, pid=4465
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4465:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4465
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/GAV2    ( 4770): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  907): acquireWL(437b3548): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1418 10028 null
,D/PMS     (  907): acquireWL(433fcff0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1418 10028 null
,D/PMS     (  907): releaseWL(437b3548): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  907): releaseWL(433fcff0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/jxcore-log( 4617): Test app app.js loaded
I/jxcore-log( 4617): 
,I/Choreographer( 4617): Skipped 520 frames!  The application may be doing too much work on its main thread.
,W/ResourceType( 4617): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4617): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41b41280 VFEDH.C. .F....ID 0,0-720,1134 #64}
,I/chromium( 4617): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/PMS     (  907): releaseWL(437d8d68): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  907): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  907): acquireWL(4248d260): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4248d260): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(4406b1b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10028}
,V/AlarmManager(  907): sending alarm PendingIntent{4238fb78: PendingIntentRecord{4266afc8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=140594, Int=0
V/AlarmManager(  907): sending alarm PendingIntent{4202a108: PendingIntentRecord{42346768 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141305, Int=0
,V/AlarmManager(  907): sending alarm PendingIntent{4375b068: PendingIntentRecord{437ebb70 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1452688701564, Int=563223000
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1365/10028)
,D/PMS     (  907): acquireWL(433d8568): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10028 null
,D/PMS     (  907): releaseWL(433d8568): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/GpsLocationProvider(  907): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  907): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  907): acquireWL(43737038): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/PMS     (  907): acquireWL(423d9230): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1226 10028 null
,D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =7da6 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/PMS     (  907): releaseWL(4406b1b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
D/PMS     (  907): acquireWL(425f8808): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1226 10028 null
D/PMS     (  907): releaseWL(423d9230): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
I/CheckinService( 1226): Preparing to send checkin request
I/EventLogService( 1226): Accumulating logs since 1452688669405
,I/GoogleHttpClient( 1226): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1226): Using GMS GoogleHttpClient
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (1226/10028)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.google.android.gms (1226/10028)
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=13 [22][3][0]
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  363): [NET]res_nsend:resplen=238
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
I/global  (  907): call createSocket() return a new socket.
D/libc    (  907): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,W/GLSUser ( 1365): GoogleAccountDataService.getToken()
,D/GpsLocationProvider(  907): [handleDownloadXtraData] calling native_inject_xtra_data
,D/AutoSetting( 1399): service - mHandler: update timezone
,D/AutoSetting( 1399): service - handleMessage() stop self
,D/AutoSetting( 1501): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1501): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1501): service - onCreate()
W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1365): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1501): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1501): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/DotMatrix( 1585): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1585): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AutoSetting( 1501): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1501): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1501): service - mHandler: update timezone
,D/AutoSetting( 1399): service - handleMessage() quit looper
,D/AutoSetting( 1399): service - onDestroy() END
,D/DotMatrix( 1585): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1585): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
D/AutoSetting( 1501): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1501): service - processTimeZoneID() system nitz is valid: false (false)
,W/CheckinRequestBuilder( 1226): awaiting user notification for token
,D/AutoSetting( 1501): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1501): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1585): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1585): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1117): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41e441f0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.google.android.gms 1 9 3 12
,I/RemoteViews( 1117): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41ee57d8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.htclocationservice 2 10 3 11
,D/GpsLocationProvider(  907): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  907): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  907):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  907): acquireWL(42bddb60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(42bddb60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (4581/10028)
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Settings( 4581): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4581): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4581): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4581): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4581): Local Branch: 
I/Adreno-EGL( 4581): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4581): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4581):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4581): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4581): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4581): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4581): Local Branch: 
I/Adreno-EGL( 4581): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4581): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4581):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4581): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4581): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4581): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4581): Local Branch: 
I/Adreno-EGL( 4581): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4581): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4581):                  aa63bbd948f41d15fc72f585e
,D/PMS     (  907): acquireWL(42a3f708): PARTIAL_WAKE_LOCK  Icing 0x1 1226 10028 null
,I/CheckinTask( 1226): Sending checkin request (8970 bytes)
,D/libc    ( 1226): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1226): [NET] getaddrinfo-,err=8
D/libc    ( 1226): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1226): [NET] getaddrinfo-, 1
D/libc    ( 1226): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =762f +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/PMS     (  907): releaseWL(42a3f708): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(43198020): PARTIAL_WAKE_LOCK  Icing 0x1 1226 10028 null
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 255
D/libc    (  363): [NET]res_nsend:resplen=84
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1226): [NET] getaddrinfo_proxy-, success
,D/PMS     (  907): releaseWL(43198020): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(4252b620): PARTIAL_WAKE_LOCK  Icing 0x1 1226 10028 null
,D/PMS     (  907): releaseWL(4252b620): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(430fc2b0): PARTIAL_WAKE_LOCK  Icing 0x1 1226 10028 null
,D/PMS     (  907): releaseWL(430fc2b0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/libc    ( 1226): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1226): [NET] getaddrinfo-,err=8
,D/PMS     (  907): acquireWL(4264f7f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10028 null
,D/PMS     (  907): releaseWL(4264f7f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (1226/10028)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.google.android.gms (1226/10028)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=10 [48][5][0]
,W/GLSUser ( 1365): GoogleAccountDataService.getToken()
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1365): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/CheckinRequestBuilder( 1226): awaiting user notification for token
,D/DotMatrix( 1585): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1585): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1117): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41f0f480 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.google.android.gms 0 10 3 12
,I/CheckinTask( 1226): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 1226): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,D/GCM     ( 1365): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  907): releaseWL(425f8808): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 1226): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41cff190 that was originally bound here
E/ActivityThread( 1226): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41cff190 that was originally bound here
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
,I/GCM     ( 1365): GCM config loaded
,D/PMS     (  907): releaseWL(43737038): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 3
,D/Process (  907): killProcessQuiet, pid=3989
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3989:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3989
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{44100370 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  907): acquireWL(440bc448): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{42104638: PendingIntentRecord{423c0178 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=169224, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(440bc448): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1501): service - handleMessage() stop self
,D/AutoSetting( 1501): service - onDestroy() END
,D/AutoSetting( 1501): service - handleMessage() quit looper
,D/Process (  907): killProcessQuiet, pid=4519
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4519:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4519
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TelephonyReceiver( 1247): switchBindHtcMsgCursor: null
,D/PMS     (  907): acquireWL(425d35b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): releaseWL(425d35b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43559820): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41dde998: PendingIntentRecord{424cb618 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=193228, Int=0
,D/PMS     (  907): acquireWL(4378ab70): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
,D/PMS     (  907): releaseWL(43559820): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(430cb560): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(4378ab70): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(430cb560): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(43185168): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43185168): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(434f0828): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{42104638: PendingIntentRecord{423c0178 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=229224, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(434f0828): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(437571d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10026}
,V/AlarmManager(  907): sending alarm PendingIntent{435e7a98: PendingIntentRecord{429eb068 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=229686, Int=0
,I/ActivityManager(  907): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4923 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  907): sending alarm PendingIntent{42690eb0: PendingIntentRecord{4269f550 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452688790940, Int=10800000
,D/PMS     (  907): releaseWL(437571d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.aurora (4923/10047)
,D/Process (  907): killProcessQuiet, pid=4537
,I/ActivityManager(  907): Killing 4537:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 4537
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(4405fd38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10026}
,V/AlarmManager(  907): sending alarm PendingIntent{4381a4f0: PendingIntentRecord{430930b8 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=230216, Int=120000
,V/AlarmManager(  907): sending alarm PendingIntent{4404a740: PendingIntentRecord{429eb068 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=230450, Int=0
,D/PMS     (  907): releaseWL(4405fd38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1226/10028)
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(430ce668): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(430ce668): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(43596960): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{42104638: PendingIntentRecord{423c0178 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=289224, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43596960): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  408): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 4617): --= Surplus to requirements =--
I/jxcore-log( 4617): 
I/jxcore-log( 4617): ****TEST TOOK:  ms ****
I/jxcore-log( 4617): 
,I/jxcore-log( 4617): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****,
I/jxcore-log( 4617): 
,E/cutils-trace( 4944): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 4944): ====startRecUseTime====
D/htc.customization.log.level( 4944):  is 
,W/CustomizationLogLevel( 4944): Level value is invalid, use default level 2
,D/CustomizationManager( 4944):  Read ACC file spent 0.091 (s)
D/CIDMapFileReader( 4944): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4944): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4944): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4944): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4944): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4944): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4944): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4944): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4944): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4944): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4944): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 4944): Parsing tag category name = system
,I/CustomizationCIDLoader( 4944): Parsing tag category name = application
I/CustomizationCIDLoader( 4944): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4944): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4944): Parsing tag category name = AudioService
,I/CustomizationCIDLoader( 4944): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4944): Parsing tag category name = Settings
D/CustomizationManager( 4944):  Read CID file spent 0.134 (s)
,D/CustomizationManager( 4944):  All configurations done spent 0.135 (s)
,W/HtcNativeFlag( 4944): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4944): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4944): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 4944): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  907): deletePackageAsUser: pkg=com.test.thalitest, pid=4944, uid=2000 user=0
,I/ActivityManager(  907): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
,D/Process (  907): killProcessQuiet, pid=4617
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  907): Killing 4617:com.test.thalitest/u0a189 (adj 0): stop com.test.thalitest
,W/ActivityManager(  907): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  907):   Force finishing activity ActivityRecord{4400d800 u0 com.test.thalitest/.MainActivity t2}
,W/asset   (  907): Copying FileAsset 0x6914cc68 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,W/InputDispatcher(  907): channel '43fa12d8 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  907): channel '43fa12d8 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  907): Attempted to unregister already unregistered input channel '43fa12d8 com.test.thalitest.MainActivity (s)'
I/WindowManager(  907): WINDOW DIED Window{43fa12d8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  907): Client connection lost with reason: 4
W/WindowManager(  907): Failed looking up window
W/WindowManager(  907): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@439276c0 does not exist
W/WindowManager(  907): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8463)
W/WindowManager(  907): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8454)
W/WindowManager(  907): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1052)
W/WindowManager(  907): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/WindowManager(  907): 	at dalvik.system.NativeStart.run(Native Method)
I/WindowState(  907): WIN DEATH: null
,W/InputMethodManagerService(  907): Got RemoteException sending setActive(false) notification to pid 4617 uid 10189
,W/Binder  ( 1211): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1211): java.lang.NullPointerException
W/Binder  ( 1211): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1211): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1211): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1211): 	at dalvik.system.NativeStart.run(Native Method)
,I/ActivityManager(  907): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
,D/DotMatrix( 1585): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
I/acms    ( 1921): Unregistering com.test.thalitest
,E/acms    ( 1921): Could not unregister removed application com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1585): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1585): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.test.thalitest
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
,D/PMS     (  907): acquireWL(435ac308): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1418 10028 null
,W/GeofencerStateMachine( 1418): Ignoring removeGeofence because network location is disabled.
,I/dalvikvm-heap( 4235): Grow heap (frag case) to 15.347MB for 1821008-byte allocation
,D/PMS     (  907): releaseWL(435ac308): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
W/AccTypeManager( 1341): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1341): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/VoicemailCleanupService( 1302): Cleaning up data for package: com.test.thalitest
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/SystemReader( 1258): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
,D/PackageBroadcastService( 1226): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,I/Launcher( 1272): Deferring update until onResume
,D/Launcher( 1272): waitUntilResume // bindAppsRemoved
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
D/AccTypeManager( 1341): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/ActivityManager(  907): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4959 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,I/InputMethodManagerService(  907): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,E/ExternalAccountType( 1341): Unsupported attribute readOnly
,I/MultiDex( 4959): install
,I/MultiDex( 4959): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/ActivityManager(  907): Delaying start of: ServiceRecord{42219b50 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/MultiDex( 4959): loading existing secondary dex files
I/MultiDex( 4959): load found 1 secondary dex files
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
,I/MultiDex( 4959): install done
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,I/ActivityManager(  907): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4975 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,I/PeopleContactsSync( 1226): CP2 sync disabled
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,I/ProviderInstaller( 4959): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/PhoneApp( 1247): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1226, uid=10028, userID:0
,I/Icing   ( 1226): doRemovePackageData com.test.thalitest
D/PMS     (  907): acquireWL(4400fd68): PARTIAL_WAKE_LOCK  Icing 0x1 1226 10028 null
,I/MultiDex( 4975): install
,I/MultiDex( 4975): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
D/PMS     (  907): releaseWL(4400fd68): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/MultiDex( 4975): loading existing secondary dex files
,I/MultiDex( 4975): load found 1 secondary dex files
,I/MultiDex( 4975): install done
I/ActivityManager(  907): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
,I/ProviderInstaller( 4975): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,I/ActivityManager(  907): Resuming delayed broadcast
,D/Process (  907): killProcessQuiet, pid=4552
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4552:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  907): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,I/[PluginManager]RegisterService( 1399): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest,
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 4552
,I/[PluginManager]RegisterService( 1399): handle notify Blinkfeed plugin client changed
,I/ActivityManager(  907): Resuming delayed broadcast
,D/Prism.PackageStateRece_( 1272): action: android.intent.action.PACKAGE_REMOVED
,I/IcingCorporaProvider( 2936): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ActivityManager(  907): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4997 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,D/PMS     (  907): acquireWL(423c5680): PARTIAL_WAKE_LOCK  Icing 0x1 1226 10028 null
,E/SQLiteLog( 2936): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 2936): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x63cba7e8
E/SQLiteLog( 4959): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 4959): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca5e910
,E/DriveAsyncService( 4959): disk I/O error (code 3850)
E/DriveAsyncService( 4959): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4959): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4959): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 4959): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4959): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4959): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 4959): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 4959): 	at ctj.c(SourceFile:904)
E/DriveAsyncService( 4959): 	at cva.h(SourceFile:1427)
E/DriveAsyncService( 4959): 	at cgv.a(SourceFile:15)
E/DriveAsyncService( 4959): 	at bzz.onHandleIntent(SourceFile:60)
E/DriveAsyncService( 4959): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/DriveAsyncService( 4959): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DriveAsyncService( 4959): 	at android.os.Looper.loop(Looper.java:157)
E/DriveAsyncService( 4959): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/IcingCorporaProvider( 2936): Exception thrown from notifyTableChanged
E/IcingCorporaProvider( 2936): java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2936): 	at apg.a(PG:301)
E/IcingCorporaProvider( 2936): 	at apg.c(PG:222)
E/IcingCorporaProvider( 2936): 	at clo.b(PG:660)
E/IcingCorporaProvider( 2936): 	at clo.a(PG:651)
E/IcingCorporaProvider( 2936): 	at clo.g(PG:597)
E/IcingCorporaProvider( 2936): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/IcingCorporaProvider( 2936): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/IcingCorporaProvider( 2936): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/IcingCorporaProvider( 2936): 	at clp.Rl(PG:910)
E/IcingCorporaProvider( 2936): 	at clr.tL(PG:827)
E/IcingCorporaProvider( 2936): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/IcingCorporaProvider( 2936): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/IcingCorporaProvider( 2936): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/IcingCorporaProvider( 2936): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/IcingCorporaProvider( 2936): 	at android.os.Looper.loop(Looper.java:157)
E/IcingCorporaProvider( 2936): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/IcingCorporaProvider( 2936): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2936): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/IcingCorporaProvider( 2936): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/IcingCorporaProvider( 2936): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/IcingCorporaProvider( 2936): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/IcingCorporaProvider( 2936): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/IcingCorporaProvider( 2936): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/IcingCorporaProvider( 2936): 	at apa.a(PG:382)
E/IcingCorporaProvider( 2936): 	at apg.i(PG:325)
E/IcingCorporaProvider( 2936): 	at aph.call(PG:215)
E/IcingCorporaProvider( 2936): 	at apg.a(PG:299)
E/IcingCorporaProvider( 2936): 	... 15 more
W/IcingCorporaProvider( 2936): notifyTableChanged failed.
W,/IcingCorporaProvider( 2936): Table change notification failed for TableStorageSpec[applications]
I/IcingCorporaProvider( 2936): UpdateCorporaTask done [took 224 ms] updated apps [took 224 ms] 
D/PMS     (  907): releaseWL(423c5680): PARTIAL_WAKE_LOCK  Icing 0x1 null
E/SQLiteLog( 4959): (3850) statement aborts at 5: [DELETE FROM ContentFileDeletionLock24] disk I/O error
E/SQLiteDBG( 4959): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca5e910
E/DocListDatabase( 4959): Failed to delete from ContentFileDeletionLock24
E/DocListDatabase( 4959): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 4959): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 4959): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/DocListDatabase( 4959): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 4959): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 4959): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/DocListDatabase( 4959): 	at ctj.a(SourceFile:859)
E/DocListDatabase( 4959): 	at cva.k(SourceFile:1117)
E/DocListDatabase( 4959): 	at chr.<init>(SourceFile:45)
E/DocListDatabase( 4959): 	at chr.a(SourceFile:75)
E/DocListDatabase( 4959): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/DocListDatabase( 4959): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/DocListDatabase( 4959): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/DocListDatabase( 4959): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/DocListDatabase( 4959): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DocListDatabase( 4959): 	at android.os.Looper.loop(Looper.java:157)
E/DocListDatabase( 4959): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/DocListDatabase( 4959): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DocListDatabase( 4959): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DocListDatabase( 4959): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/DocListDatabase( 4959): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/DocListDatabase( 4959): 	at dalvik.system.NativeStart.main(Native Method)
,W/dalvikvm( 4959): threadid=1: thread exiting with uncaught exception (group=0x416fde30)
,E/AndroidRuntime( 4959): FATAL EXCEPTION: main
E/AndroidRuntime( 4959): Process: com.google.android.gms.drive, PID: 4959
E/AndroidRuntime( 4959): java.lang.RuntimeException: Unable to create service com.google.android.gms.drive.api.ApiService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4959): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2883)
E/AndroidRuntime( 4959): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/AndroidRuntime( 4959): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/AndroidRuntime( 4959): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4959): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4959): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4959): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4959): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4959): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4959): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4959): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4959): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4959): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4959): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 4959): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4959): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4959): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 4959): 	at ctj.a(SourceFile:859)
E/AndroidRuntime( 4959): 	at cva.k(SourceFile:1117)
E/AndroidRuntime( 4959): 	at chr.<init>(SourceFile:45)
E/AndroidRuntime( 4959): 	at chr.a(SourceFile:75)
E/AndroidRuntime( 4959): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/AndroidRuntime( 4959): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/AndroidRuntime( 4959): 	... 10 more
E/ActivityManager(  907): App crashed! Process: com.google.android.gms.drive
,D/Process ( 4959): killProcess, pid=4959
,D/Process ( 4959): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  907): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  907): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  907): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  907): 	... 5 more
I/ActivityManager(  907): Recipient 4959
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Process com.google.android.gms.drive (pid 4959) has died.
,W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.drive.api.ApiService in 1000ms
,E/SQLiteDatabase( 4997): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.,
E/SQLiteDatabase( 4997): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4997): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4997): 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4997): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4997): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4997): 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4997): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4997): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4997): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829),
E/SQLiteDatabase( 4997): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4997): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4997): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4997): ,	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4997): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4997): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4997): 	,at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4997): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4997): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4997): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4997): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4997): ,	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4997): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4997): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4997): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4997): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4997): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4997): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4997): ,	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4997): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4997): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4997): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4997): 	at android.os.Looper.loop(Looper.java:157),
E/SQLiteDatabase( 4997): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4997): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4997): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4997): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4997): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4997): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4997): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4997): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4997): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4997): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4997): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4997): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463),
E/SQLiteOpenHelper( 4997): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4997): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4997): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4997): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4997): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4997): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4997): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4997): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4997): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4997): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4997): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4997): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4997): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4997): 	at aJm.a(Scopes.java:65),
E/SQLiteOpenHelper( 4997): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4997): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4997): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4997): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4997): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4997): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4997): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4997): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4997): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4997): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4997): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4997): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4997): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4997): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4997): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4997): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4997): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4997): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4997): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 4997): Opened ClientFlag.db in read-only mode,
,E/SQLiteDatabase( 4997): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4997): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4997): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4997): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4997): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4997): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4997): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4997): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4997): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4997): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4997): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4997): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4997): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4997): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4997): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4997): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4997): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4997): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4997): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4997): 	at aho.run(AbstractDatabaseInstance.java:455)
,W/dalvikvm( 4997): threadid=11: thread exiting with uncaught exception (group=0x416fde30)
,E/ActivityManager(  907): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4997): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4997): Process: com.google.android.apps.docs, PID: 4997
E/AndroidRuntime( 4997): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4997): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4997): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4997): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4997): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4997): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4997): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4997): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4997): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4997): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4997): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4997): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4997): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4997): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4997): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4997): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4997): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4997): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4997): 	at aho.run(AbstractDatabaseInstance.java:455)
,E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  907): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  907): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  907): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  907): 	... 5 more
,I/ActivityManager(  907): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5018 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process ( 4997): killProcess, pid=4997
D/Process ( 4997): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 4997
,D/Process (  907): killProcessQuiet, pid=4299
,I/ActivityManager(  907): Killing 4299:com.google.android.configupdater/u0a16 (adj 15): empty #17
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  907): Process com.google.android.apps.docs (pid 4997) has died.
,W/ContextImpl( 5018): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  907): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=5031 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
,E/SQLiteDatabase( 5018): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5018): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5018): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5018): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5018): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5018): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5018): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5018): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5018): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5018): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5018): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5018): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5018): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5018): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5018): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5018): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 5018): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 5018): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5018): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5018): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5018): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 5018): threadid=10: thread exiting with uncaught exception (group=0x416fde30)
E/AndroidRuntime( 5018): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5018): Process: com.android.keychain, PID: 5018
E/AndroidRuntime( 5018): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5018): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5018): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5018): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5018): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5018): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5018): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5018): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5018): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5018): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5018): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5018): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5018): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5018): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5018): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 5018): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 5018): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5018): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5018): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5018): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ActivityManager(  907): Recipient 4299
,E/ActivityManager(  907): App crashed! Process: com.android.keychain
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
,D/Process ( 5018): killProcess, pid=5018
,D/Process ( 5018): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,D/AppTag  ( 5031): getInstance(Context context)
I/ActivityManager(  907): Recipient 5018
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.android.keychain (pid 5018) has died.
W/ActivityManager(  907): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10446ms
E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452688878873.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  907): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  907): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  907): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  907): 	... 4 more
,D/AppTag  ( 5031): getInstance(Context context)
,D/AppTag  ( 5031): onCreate()
,I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1272): loadItems() com.htc.launcher.pageview.WidgetManager@41bc0d98 +
,I/Prism.WidgetManager( 1272): onLoadItems() +
D/PMS     (  907): acquireWL(420edf50): PARTIAL_WAKE_LOCK  AsyncService 0x1 4235 10160 null
,I/dalvikvm-heap( 4235): Grow heap (frag case) to 17.081MB for 1821008-byte allocation
I/ActivityManager(  907): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5049 uid=10098 gids={50098, 3003, 5012}
D/PMS     (  907): releaseWL(420edf50): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,W/PackageManager(  907): Unable to load service info ResolveInfo{41f3dae0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  907): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  907): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  907): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  907): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  907): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  907): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  907): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  907): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  907): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  907): 	at dalvik.system.NativeStart.main(Native Method)
,I/DeviceManagement( 5049): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=5049 dbg=false s=true
,I/DeviceManagement( 5049): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
,I/DeviceManagement( 5049): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
,I/DeviceManagement( 5049): WorkflowService: Starting workflow service
I/DeviceManagement( 5049): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b5ad50] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 5049): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5049): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
,I/DeviceManagement( 5049): PackageUpdateWorkflow: ==================================================
,I/DeviceManagement( 5049): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  907): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5063 uid=10099 gids={50099, 3003, 5012}
,I/DeviceManagement( 5049): BackgroundController: *** Processing package remove for appID=com.test.thalitest
,I/DeviceManagement( 5049): SessionStateController: Checking invariants...
,D/Documents( 5063): Loading roots for com.android.providers.downloads.documents
,D/Documents( 5063): Loading roots for com.android.externalstorage.documents
,E/SQLiteDatabase( 5063): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 5063): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5063): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5063): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5063): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5063): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5063): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5063): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5063): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5063): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5063): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5063): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5063): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5063): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5063): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5063): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 5063): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 5063): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 5063): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 5063): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 5063): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 5063): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 5063): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 5063): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5063): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5063): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5063): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5063): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5063): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5063): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5063): 	at dalvik.system.NativeStart.main(Native Method)
,W/dalvikvm( 5063): threadid=1: thread exiting with uncaught exception (group=0x416fde30)
E/AndroidRuntime( 5063): FATAL EXCEPTION: main
E/AndroidRuntime( 5063): Process: com.android.documentsui, PID: 5063
E/AndroidRuntime( 5063): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5063): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 5063): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 5063): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 5063): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5063): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5063): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 5063): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 5063): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 5063): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 5063): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 5063): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 5063): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5063): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5063): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5063): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5063): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5063): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5063): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5063): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5063): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5063): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5063): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5063): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5063): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5063): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5063): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 5063): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 5063): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 5063): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 5063): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 5063): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 5063): 	... 10 more
,I/ActivityManager(  907): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=5077 uid=10023 gids={50023, 1028, 1015, 1023}
,D/Process (  907): killProcessQuiet, pid=4661
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,E/ActivityManager(  907): App crashed! Process: com.android.documentsui
,D/GCM     ( 1365): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  907): Killing 4661:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
,I/ActivityManager(  907): Recipient 4661
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Process (  907): killProcessQuiet, pid=4833
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
I/ActivityManager(  907): Killing 4833:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,D/GCM     ( 1365): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,E/SQLiteDatabase( 5049): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 5049): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5049): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5049): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5049): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5049): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5049): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5049): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5049): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5049): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5049): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5049): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5049): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5049): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5049): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5049): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 5049): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 5049): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 5049): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 5049): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 5049): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 5049): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 5049): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 5049): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 5049): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 5049): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 5049): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 5049): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 5049): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 5049): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 5049): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 5049): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 5049): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 5049): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 5049): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 5049): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 5049): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 5049): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel,.java:176)
E/SQLiteDatabase( 5049): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 5049): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 5049): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5049): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5049): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5049): 	at java.lang.Thread.run(Thread.java:864)
D/ExternalStorage( 5077): After updating volumes, found 1 active roots
E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452688879239.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  907): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  907): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  907): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  907): 	... 4 more
I/ActivityManager(  907): Recipient 4833
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  907): Client connection lost with reason: 4
I/DeviceManagement( 5049): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/ActivityManager(  907): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=5093 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
I/DeviceManagement( 5049): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 5049): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
D/Process ( 5063): killProcess, pid=5063
D/Process ( 5063): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  907): Recipient 5063
,E/SQLiteDatabase( 5049): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 5049): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5049): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5049): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5049): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5049): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5049): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5049): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5049): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5049): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5049): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5049): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5049): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5049): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5049): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5049): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 5049): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 5049): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 5049): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 5049): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 5049): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 5049): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 5049): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 5049): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 5049): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 5049): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 5049): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 5049): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
E/SQLiteDatabase( 5049): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
E/SQLiteDatabase( 5049): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 5049): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 5049): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5049): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5049): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5049): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Process com.android.documentsui (pid 5063) has died.
W/DeviceManagement( 5049): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b5ad50]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/DeviceManagement( 5049): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/DeviceManagement( 5049): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/DeviceManagement( 5049): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/DeviceManagement( 5049): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/DeviceManagement( 5049): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/DeviceManagement( 5049): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/DeviceManagement( 5049): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/DeviceManagement( 5049): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/DeviceManagement( 5049): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
,W/DeviceManagement( 5049): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
W/DeviceManagement( 5049): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
W/DeviceManagement( 5049): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/DeviceManagement( 5049): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/DeviceManagement( 5049): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
W/DeviceManagement( 5049): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 5049): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 5049): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 5049): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 5049): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 5049): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 5049): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 5049): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 5049): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 5049): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 5049): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 5049): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 5049): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 5049): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 5049): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 5049): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 5049): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 5049): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 5049): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/DeviceManagement( 5049): WorkflowService: Stopping workflow service

```
