#### Test 50650278bcecc5c_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/WIFI_ICON( 1113): WifiActivity: 0
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,--------- beginning of /dev/log/main
E/cutils-trace( 4432): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4432): ====startRecUseTime====
D/htc.customization.log.level( 4432):  is 
W/CustomizationLogLevel( 4432): Level value is invalid, use default level 2
D/WIFI_ICON( 1113): WifiActivity: 1
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/CustomizationManager( 4432):  Read ACC file spent 0.062 (s)
D/CIDMapFileReader( 4432): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4432): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4432): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4432): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4432): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4432): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4432): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4432): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4432): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4432): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4432): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4432): Parsing tag category name = system
I/CustomizationCIDLoader( 4432): Parsing tag category name = application
I/CustomizationCIDLoader( 4432): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4432): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4432): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4432): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4432): Parsing tag category name = Settings
D/CustomizationManager( 4432):  Read CID file spent 0.107 (s)
D/CustomizationManager( 4432):  All configurations done spent 0.107 (s)
W/HtcNativeFlag( 4432): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4432): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4432): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4432): Fail to get flag for type 'language', use default value: -1
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1150): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  903):    returned true
D/WifiStateMachine(  903): [ScoreAP] + current TXpacket:117, mTXpacketCount:117, avgLinkspeed:72,mAvgTxRate72
D/WifiStateMachine(  903): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
W/CpuWake (  903): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  903): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  903): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  903): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  903): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  903): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  903): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4432
D/PMS     (  903): acquireHCC(43d445b8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 903 1000 null
D/PMS     (  903): acquireHCC(43d0cf70): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 903 1000 null
W/asset   (  903): Copying FileAsset 0x64469f90 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  903): @test_code: getHtcIntentFlag: 0 obj: 1136123880
I/FeedHostManager( 1269): [onPause]
I/FeedProviderManager( 1269): onPause
I/FeedHostManager( 1269): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41e125d0
I/SocialFeedProvider( 1269): +onPause
I/SocialFeedProvider( 1269): -onPause
D/PMS     (  903): acquireWL(43be1ff0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 903 1000 null
I/ActivityManager(  903): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4443 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1269): [trimMemory] 20
W/asset   ( 4443): Copying FileAsset 0x5c7d7d40 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4443): Binding Chromium to main looper Looper (main, tid 1) {41d67420}
I/LibraryLoader( 4443): Expected native library version number "",actual native library version number ""
I/chromium( 4443): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4443): Initializing chromium process, renderers=0
D/PMS     (  903): acquireWL(439227e8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
W/System.err(  903): java.lang.Throwable: stack dump
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  903): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  903): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
D/BluetoothManagerService(  903): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4273a9c0:true
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4443): 1104662824: getState(). Returning 12
D/PMS     (  903): acquireWL(438fa798): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  903): releaseWL(438fa798): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4443): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4443): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4443): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4443): Local Branch: 
I/Adreno-EGL( 4443): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4443): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4443):                  aa63bbd948f41d15fc72f585e
W/chromium( 4443): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4443): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4443): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4443): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4443): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4443): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4443): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4443): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4443): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4443): CordovaWebView is running on device made by: HTC
,W/AwContents( 4443): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  903): Disable input method client, pid=1269
,W/ResourceType( 4443): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4443): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41dae7d8, mServedView=org.apache.cordova.engine.SystemWebView{41d74440 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1208): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1208): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  903): Enable input method client, pid=4443
,W/AwContents( 4443): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  903): Displayed com.test.thalitest/.MainActivity: +298ms
D/PMS     (  903): releaseWL(43be1ff0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4443): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4443): JniHelper::setJavaVM(0x41923010), pthread_self() = 1663978056
,D/JX-Cordova( 4443): jxcore cordova android initializing
,I/SensorManager(  903): mEventCount = 1051
,I/ActivityManager(  903): Waited long enough for: ServiceRecord{43df74f0 u0 com.htc.htclocationservice/.AutoSettingService}
,I/dalvikvm-heap( 4443): Grow heap (frag case) to 11.601MB for 144892-byte allocation
,I/dalvikvm-heap( 4443): Grow heap (frag case) to 11.717MB for 217334-byte allocation
,I/dalvikvm-heap( 4443): Grow heap (frag case) to 11.893MB for 325996-byte allocation
,I/dalvikvm-heap( 4443): Grow heap (frag case) to 12.167MB for 488990-byte allocation
,I/dalvikvm-heap( 4443): Grow heap (frag case) to 12.573MB for 733480-byte allocation
,I/dalvikvm-heap( 4443): Grow heap (frag case) to 14.020MB for 1650320-byte allocation
,I/dalvikvm-heap( 4443): Grow heap (frag case) to 15.434MB for 2475476-byte allocation
,I/dalvikvm-heap( 4443): Grow heap (frag case) to 17.457MB for 3713210-byte allocation
,W/jxcore-log( 4443): Initializing JXcore engine
,W/jxcore-log( 4443): JXcore engine is ready
,W/jxcore-log( 4443): Starting JXcore engine
,W/CpuWake (  903): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  903): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  903): >>release mCpuPerf_cpu_count wakelock
,W/CpuWake (  903): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  903): >>release mCpuPerf_Freq wakelock
,D/PMS     (  903): releaseHCC(43d445b8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
W/CpuWake (  903): <<release mCpuPerf_Freq wakelock
,D/PMS     (  903): releaseHCC(43d0cf70): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4443): Platform android
W/jxcore-log( 4443): 
,W/jxcore-log( 4443): Process ARCH arm
W/jxcore-log( 4443): 
,I/jxcore-log( 4443): JXcore Cordova bridge is ready!
I/jxcore-log( 4443): 
,W/jxcore-log( 4443): JXcore engine is started
,I/chromium( 4443): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1150): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,I/ActivityManager(  903): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4488 uid=10077 gids={50077}
,D/PMS     (  903): acquireWL(421edaa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10077}
,V/AlarmManager(  903): sending alarm PendingIntent{421b01c0: PendingIntentRecord{41d9fb68 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1450461153237, Int=60000
,D/PMS     (  903): releaseWL(421edaa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4488): SMSBackupAgentService started
,D/SMSBackup( 4488): Checking restore status
,D/SMSBackup( 4488): Restore complete
,D/SMSBackup( 4488): cancelCheckAlarm
,D/SMSBackup( 4488): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  903): killProcessQuiet, pid=4251
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4251:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4251
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  903): Client connection lost with reason: 4
,D/PMS     (  903): releaseWL(439227e8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4443): Toggling radios to true
I/jxcore-log( 4443): 
,D/BluetoothAdapter( 4443): enable(): BT is already enabled..!
,D/WifiManager( 4443): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
W/HtcDLNAServiceManager(  903): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  903): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  903): Settings:Agentvalue: 2
W/Settings:Agent(  903): >> traceCallingStack()
W/Settings:Agent(  903): Process.myPid(): 903
W/Settings:Agent(  903): Process.myTid(): 913
W/Settings:Agent(  903): Process.myUid(): 1000
W/Settings:Agent(  903): 
W/Settings:Agent(  903): 
,W/System.err(  903): java.lang.Throwable: stack dump
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  903): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  903): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
D/WifiService(  903): New client listening to asynchronous messages
D/WifiService(  903): setWifiEnabled: true pid=4443, uid=10348
E/WifiService(  903): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  903): isSprintWifiRestricted(): false
I/WifiService(  903): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  903): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/System.err(  903): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  903): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  903): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  903): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  903): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  903): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  903): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  903): 
W/Settings:Agent(  903): << traceCallingStack(): 1(ms)
D/WifiManager( 4443): disconnect: Base Package Name=com.test.thalitest, uid=10348
D/WifiNative-wlan0(  903): doBoolean: DISCONNECT
D/WifiManager( 4443): reconnect: Base Package Name=com.test.thalitest, uid=10348
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1150): TDLS: Tear down peers
I/wpa_supplicant( 1150): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4443): Radios toggled
I/jxcore-log( 4443): 
D/BluetoothManagerService(  903): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4443): Got Device Bluetooth address: 80:01:84:8A:B3:68
I/jxcore-log( 4443): 
I/jxcore-log( 4443): Perf Test app loaded loaded
I/jxcore-log( 4443): 
I/jxcore-log( 4443): check test folder
I/jxcore-log( 4443): 
I/jxcore-log( 4443): found test : ./testFindPeers.js
I/jxcore-log( 4443): 
,E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1150): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1150): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1150): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  903): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  903): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1150): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1150): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
,E/wpa_supplicant( 1150): send_and_recv error -67 - cmd 12
,D/wpa_supplicant( 1150): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1150): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1150): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1150): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1150): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1150): send_and_recv error -67 - cmd 12,
D/wpa_supplicant( 1150): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb7f5cbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1150):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1150): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1150): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1150): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1150): netlink: Operstate: linkmode=-1, operstate=5,
I/wpa_supplicant( 1150): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1150): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1150): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1150): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1150): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1150): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1150): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1150): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1150): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1150): EAPOL: External notification - portValid=0,
D/wpa_supplicant( 1150): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1150): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1150): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1150): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1150): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1150): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1150): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1150): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1150): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1150): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1150): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1150): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1150): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1150): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1150): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1150): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1150): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1150): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1150): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1150): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
,D/wpa_supplicant( 1150): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1150): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1150): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1150): nl80211: Event message available
D/wpa_supplicant( 1150): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1150): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  903): WifiMonitor:getReasonFromEventString() 3
I/jxcore-log( 4443): found test : ./testSendData.js
I/jxcore-log( 4443): 
D/HTCRequest(  903): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  903): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  903): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/WifiNative-wlan0(  903):    returned true
D/WifiPerfLock(  903): release()
,D/WifiStateMachine(  903): PerfLock released for exiting ConnectedState
D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/Tethering(  903): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
D/Tethering(  903): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1150): Power_Mode_Type mode = 0
I/wpa_supplicant( 1150): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 61
D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  903):    returned true
,D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  903): acquireWL(42745460): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 903 1000 null
,D/WifiP2pService(  903): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1150): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  903):    returned true
,D/Tethering(  903): interfaceLinkStateChanged wlan0, false
,D/Tethering(  903): interfaceStatusChanged wlan0, false
,D/Tethering(  903): [isWifi] getHotspotEnabled: false
,D/DhcpStateMachine(  903): [RunningState] Stop DHCP
D/libc    (  903): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  903): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  903): doBoolean: RECONNECT
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1150): Fast associate: Old scan results
I/wpa_supplicant( 1150): wpa_supplicant_scan enter
I/wpa_supplicant( 1150): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1150): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1150): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  903):    returned true
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1150): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1150): nl80211: Event message available
D/wpa_supplicant( 1150): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/WifiStateMachine(  903): Enter handleNetworkDisconnect
I/IntentController( 1113): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiDataStallTracker(  903): stopDataStallAlarm: current tag=20655 mDataStallAlarmIntent=PendingIntent{43905250: PendingIntentRecord{429247c0 android broadcastIntent}}
,D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1150): Power_Mode_Type mode = 0
I/wpa_supplicant( 1150): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  903):    returned true
,D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 2
D/WIFI_ICON( 1113): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiP2pService(  903): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1150): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,D/WifiNative-wlan0(  903):    returned true
D/UsbnetStateTracker(  903): isAvailable+-
D/UsbnetStateTracker(  903): reconnect
,D/UsbnetStateTracker(  903): isAvailable+-
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  903): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  903): Provision feature enable=false
D/ConnectivityService(  903): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1809/10178)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  903): default: reconnect()
D/MDST    (  903): default: setTeardownRequested(false)
D/MDST    (  903): default: setEnableApn apnType =default , enable=true
,D/WISPrService( 4221): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  903): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  903): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  903): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
,D/WifiService(  903): New client listening to asynchronous messages
D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WISPrService( 4221): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  903): Exit handleNetworkDisconnect
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  903): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
W/ConnectivityService(  903): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  903): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  903): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  903): Exception trying to remove a route: java.lang.IllegalStateException: command '33 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 33 Failed to remove route from default table (No such process)'
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,D/ConnectivityService(  903): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,I/IntentController( 1113): receive(android.net.wifi.STATE_CHANGE,1,false)
W/ConnectivityService(  903): Exception trying to remove a route: java.lang.IllegalStateException: command '34 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 34 Failed to remove route from default table (No such process)'
D/ConnectivityService(  903): handleConnectivityChange: resetting
D/ConnectivityService(  903): resetConnections(wlan0, 3)
,D/PMS     (  903): acquireWL(42915488): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1372 10028 null
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1809/10178)
,D/libc    (  364): [NET] entry_id:3   entry:0xb77ad8e0  removed 
D/libc    (  364): [NET] entry_id:6   entry:0xb77b2090  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb77b2190  removed 
D/libc    (  364): [NET] entry_id:5   entry:0xb77b2348  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb77b2428  removed 
D/libc    (  364): [NET] entry_id:7   entry:0xb77b2968  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb77b24f0  removed 
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
,I/QuickSettingWifi( 1113): receive.wifiConnect:false wifiAPname:null elapse:1
,D/WISPrService( 4221): >>>>>WISPrService start isConnected = false<<<<<
D/ConnectivityService(  903): flush DNS cache for net 1(wlan0)
D/WIFI_ICON( 1113): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/Nat464Xlat(  903): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  903): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  903): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  903): acquireWL(42731a40): PARTIAL_WAKE_LOCK  NetworkStats 0x1 903 1000 null
D/WirelessDisplayService(  903): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  903): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WifiStateMachine(  903): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/PMS     (  903): acquireWL(4281f5a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
D/ConnectivityService(  903): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/PMS     (  903): releaseWL(4281f5a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
I//system/bin/ip(  364): RTNETLINK answers: No such process
I/logwrapper(  364): /system/bin/ip terminated by exit(2)
D/WifiStateMachine(  903): startScan Pid: 903 Uid 1000
D/WifiNative-wlan0(  903): doBoolean: SCAN
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1150): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  903):    returned false
,D/WISPrService( 4221): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/BatSI   (  903): WIFI scan started for: 650a0300 uid:1000
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  903): reportInetCondition for net -1, percentage: 0 by  (1372/10028)
D/PMS     (  903): releaseWL(42731a40): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  903): releaseWL(42915488): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  903): mActiveDefaultNetwork: -1
,D/ConnectivityService(  903): handleInetConditionChange: no active default network - ignore
I/QuickSettingWifi( 1113): receive.wifiConnect:false wifiAPname:null elapse:0
,I/Choreographer( 4443): Skipped 88 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4443): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  903): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  903): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  903): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4509 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
D/GpsLocationProvider(  903): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  903): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  903): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  903): ignore wifi update if we are not in OPENING or CLOSING
,I/ConnectivityHelper( 1269): [onReceive] WIFI(1): DISCONNECTED
D/Tethering(  903): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  903): bSetPropertyMultiRAB:false
,D/Tethering(  903): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED,
I/Tethering(  903): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
D/PMS     (  903): acquireWL(4391fbf8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 903 1000 null
D/PMS     (  903): releaseWL(4391fbf8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1809/10178)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1447/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1857/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.htc.launcher (1269/10075)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.docs (4330/10100)
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
I/Tethering(  903): ipv4Default null
I/Tethering(  903): No IPv4 upstream interface, giving up.
D/Tethering(  903): TetherMasterSM: InitialState processMessage what=3
D/CaptivePortalTracker(  903): DelayedCaptiveCheckState
D/CaptivePortalTracker(  903): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/CaptivePortalTracker(  903): NoActiveNetworkState
D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.docs (4330/10100)
,I/MusicStore( 4509): Database version: 95
,W/ContextImpl( 4509): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4509): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4509): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4509): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4509): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4509, uid=10154, userID:0
,D/WifiDisplayAdapter(  903): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  903):     Client/Owner: Client
D/WifiDisplayAdapter(  903):     GroupId: 
D/WifiDisplayAdapter(  903):     Passphrase: 
D/WifiDisplayAdapter(  903):     SessionId: 0
D/WifiDisplayAdapter(  903):     IP Address: }
,D/MediaRouterService(  903): Client com.google.android.music (pid 4509): Registered
,I/MediaRouter( 4509): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  903): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  903):     Client/Owner: Client
D/WifiDisplayAdapter(  903):     GroupId: 
D/WifiDisplayAdapter(  903):     Passphrase: 
D/WifiDisplayAdapter(  903):     SessionId: 0
D/WifiDisplayAdapter(  903):     IP Address: }
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (2405/10021)
,I/ActivityManager(  903): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4529 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.music (4509/10154)
,D/MediaRouter( 4509): getSelectedRoute
,I/NetworkMonitor( 4509): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.google.android.music (4509/10154)
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=4509, uid=10154, userID:0
,D/Process (  903): killProcessQuiet, pid=3463
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/ACRA    ( 4529): ACRA is enabled for com.facebook.katana, intializing...
I/ActivityManager(  903): Killing 3463:com.htc.task/u0a70 (adj 15): empty #17
,D/ACRA    ( 4529): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4529): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4529): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4529): Preparing secondary program dexes.
V/DexLibLoader( 4529): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4529): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4529): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4529): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4529): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4529): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4529): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4529): Dex already copied
D/OdexVerifier( 4529): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4529): Creating class loader
,V/DexLibLoader( 4529): Finished creating class loader
V/DexLibLoader( 4529): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4529): Dex already copied
D/OdexVerifier( 4529): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4529): Creating class loader
,V/DexLibLoader( 4529): Finished creating class loader
V/DexLibLoader( 4529): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4529): Dex already copied
D/OdexVerifier( 4529): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4529): Creating class loader
,V/DexLibLoader( 4529): Finished creating class loader
V/DexLibLoader( 4529): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4529): Dex already copied
D/OdexVerifier( 4529): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4529): Creating class loader
,V/DexLibLoader( 4529): Finished creating class loader
,V/DexLibLoader( 4529): Verifying classes from secondary dexes.
,D/DexLibLoader( 4529): DexLibLoader.ensureDexLoaded took 21 ms
,I/ActivityManager(  903): Recipient 3463
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/dalvikvm( 4529): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4529): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4529): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4529): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4529): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4529): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4529): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1150): nl80211: Event message available
D/wpa_supplicant( 1150): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1150): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1150): nl80211: Received scan results (11 BSSes)
D/wpa_supplicant( 1150): nl80211: Survey data missing
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1150): Sorted scan results
I/wpa_supplicant( 1150): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1150): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-47
I/wpa_supplicant( 1150): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-47
I/wpa_supplicant( 1150): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-75
I/wpa_supplicant( 1150): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-79
I/wpa_supplicant( 1150): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-86
I/wpa_supplicant( 1150): [NULL] 06:7c:34:12:7f:81 freq=2462 level=-89
I/wpa_supplicant( 1150): [NULL] 64:7c:34:12:7f:81 freq=2462 level=-89
I/wpa_supplicant( 1150): [NULL] a0:c5:62:7a:49:96 freq=2437 level=-90
I/wpa_supplicant( 1150): [NULL] fe:94:e3:11:35:3c freq=2462 level=-91
I/wpa_supplicant( 1150): [NULL] 10:9a:dd:8e:22:d9 freq=2462 level=-92
D/wpa_supplicant( 1150): BSS: last_scan_res_used=11/32 last_scan_full=0
D/wpa_supplicant( 1150): Add randomness: count=17 entropy=0
D/wpa_supplicant( 1150): Add randomness: count=18 entropy=1
D/wpa_supplicant( 1150): Add randomness: count=19 entropy=2
D/wpa_supplicant( 1150): Add randomness: count=20 entropy=3
D/wpa_supplicant( 1150): Add randomness: count=21 entropy=4
D/wpa_supplicant( 1150): Add randomness: count=22 entropy=5
D/wpa_supplicant( 1150): Add randomness: count=23 entropy=6
D/wpa_supplicant( 1150): Add randomness: count=24 entropy=7
D/wpa_supplicant( 1150): Add randomness: count=25 entropy=8
D/wpa_supplicant( 1150): Add randomness: count=26 entropy=9
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  903): doString: LIST_DONGLES
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES",
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1150): WPS: WFA subelement id=1 len=6,
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1150): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: AP a0:c5:62:7a:49:96 type 0 added
D/wpa_supplicant( 1150): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1150): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1150): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1150): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1150): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1150): WPS: AP[5] a0:c5:62:7a:49:96 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1150): wpa_supplicant_pick_network+
I/wpa_supplicant( 1150): Selecting BSS from priority group 1
,I/wpa_supplicant( 1150): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1150): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1150): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1150): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1150):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1150):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-47
I/wpa_supplicant( 1150): Start print parameters
I/wpa_supplicant( 1150): wpa_s->wpa_state is 3
I/wpa_supplicant( 1150): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1150): isConcurrentMode() is 0
I/wpa_supplicant( 1150): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1150): wpa_s->br_p2p_connected is 0
,I/wpa_supplicant( 1150): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1150): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1150): wpa_s->reassociate is 1
I/wpa_supplicant( 1150): wpa_s->is_screen_on 1
I/wpa_supplicant( 1150): wpa_s->ifname wlan0
I/wpa_supplicant( 1150): End print parameters
I/wpa_supplicant( 1150): selected network = 4
D/wpa_supplicant( 1150): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb7f5e4e8  current_ssid=0x0
D/wpa_supplicant( 1150): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1150): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1150): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1150): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1150): check if in concurrent case
,I/wpa_supplicant( 1150): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1150): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1150): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1150): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1150): RSN: PMKSA cache search - network_ctx=0xb7f5e4e8 try_opportunistic=0
D/wpa_supplicant( 1150): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1150): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1150): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1150): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1150): netlink: Operstate: linkmode=-1, operstate=5
,D/wpa_supplicant( 1150): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1150): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1150): nl80211: Unsubscribe mgmt frames handle 0xb7f5d718 (mode change)
D/wpa_supplicant( 1150): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7f5d718
D/wpa_supplicant( 1150): nl80211: Register frame type=0xd0 nl_handle=0xb7f5d718
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1150): nl80211: Register frame type=0xd0 nl_handle=0xb7f5d718
,E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1150): nl80211: Register frame type=0xd0 nl_handle=0xb7f5d718
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1150): nl80211: Register frame type=0xd0 nl_handle=0xb7f5d718
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1150): nl80211: Register frame type=0xd0 nl_handle=0xb7f5d718
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1150): nl80211: Register frame type=0xd0 nl_handle=0xb7f5d718
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1150): nl80211: Register frame type=0xd0 nl_handle=0xb7f5d718
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1150): nl80211: Register frame type=0xd0 nl_handle=0xb7f5d718
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1150): nl80211: Register frame type=0xd0 nl_handle=0xb7f5d718
,E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1150): nl80211: Register frame type=0xd0 nl_handle=0xb7f5d718
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1150): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1150):   * bssid=c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 1150):   * freq=2412
D/wpa_supplicant( 1150):   * Auth Type 0
D/wpa_supplicant( 1150):   * WPA Versions 0x2
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1150): nl80211: Connect request send successfully
D/wpa_supplicant( 1150): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1150): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1150): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 1150): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1150): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1150): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1150): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1150): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1150): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 18
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  903): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: WFA subelement id=1 len=6
,D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1150): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1150): reply (1444) for get BSS: id=0
I/wpa_supplicant( 1150): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1150): freq=5220
I/wpa_supplicant( 1150): level=-49
I/wpa_supplicant( 1150): tsf=0000000108121439
I/wpa_supplicant( 1150): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1150): ssid=NG7005g
I/wpa_supplicant( 1150): ====
I/wpa_supplicant( 1150): id=1
I/wpa_supplicant( 1150): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1150): freq=2427
I/wpa_supplicant( 1150): level=-75
I/wpa_supplicant( 1150): tsf=0000000108121460
I/wpa_supplicant( 1150): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
,I/wpa_supplicant( 1150): ssid=Gonzos
I/wpa_supplicant( 1150): ====
I/wpa_supplicant( 1150): id=2
I/wpa_supplicant( 1150): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1150): freq=2437
I/wpa_supplicant( 1150): level=-79
I/wpa_supplicant( 1150): tsf=0000000108121463
I/wpa_supplicant( 1150): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1150): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1150): ====
I/wpa_supplicant( 1150): id=3
I/wpa_supplicant( 1150): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1150): freq=2437
I/wpa_supplicant( 1150): level=-86
I/wpa_supplicant( 1150): tsf=0000000108121471
I/wpa_supplicant( 1150): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1150): ssid=UPC4688432
I/wpa_supplicant( 1150): ====
I/wpa_supplicant( 1150): id=4
I/wpa_supplicant( 1150): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1150): freq=2412
I/wpa_supplicant( 1150): level=-47
I/wpa_supplicant( 1150): tsf=0000000108121456
I/wpa_supplicant( 1150): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1150): ssid=NG700
I/wpa_supplicant( 1150): ====
I/wpa_supplicant( 1150): id=5
,I/wpa_supplicant( 1150): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1150): freq=2462
I/wpa_supplicant( 1150): level=-91
I/wpa_supplicant( 1150): tsf=0000000108121482
I/wpa_supplicant( 1150): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1150): ssid=UPC Wi-Free
I/wpa_supplicant( 1150): ====
I/wpa_supplicant( 1150): id=6
I/wpa_supplicant( 1150): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1150): freq=2412
I/wpa_supplicant( 1150): level=-47
I/wpa_supplicant( 1150): tsf=0000000108121452
I/wpa_supplicant( 1150): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1150): ssid=01ABC
I/wpa_supplicant( 1150): ====
I/wpa_supplicant( 1150): id=7
I/wpa_supplicant( 1150): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1150): freq=2462
I/wpa_supplicant( 1150): level=-89
I/wpa_supplicant( 1150): tsf=0000000108121467
I/wpa_supplicant( 1150): flags=[WPA-EAP-CCMP+TKIP]
,D/WirelessDisplayService(  903): getDiscoveryDongleList
D/WifiStateMachine(  903): == begin of scan result ==
D/WifiStateMachine(  903): == (11) end of scan result ==
,D/WirelessDisplayService(  903): getDiscoveryDongleList
,D/WifiStateMachine(  903): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 108121439, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 1: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2427, timestamp: 108121460, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 2: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -79, frequency: 2437, timestamp: 108121463, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -86, frequency: 2437, timestamp: 108121471, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 4: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 2412, timestamp: 108121456, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 5: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -91, frequency: 2462, timestamp: 108121482, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 6: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -47, frequency: 2412, timestamp: 108121452, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 7: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 108121467, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 8: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -89, frequency: 2462, timestamp: 108121474, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 9: scan result = SSID: UPC243894600, BSSID: a0:c5:62:7a:49:96, capabilities: [WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 108121478, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  903): 10: scan result = SSID: Apple AirPort, BSSID: 10:9a:dd:8e:22:d9, capabilities: [WPA2-PSK-CCMP][ESS], level: -92, frequency: 2462, timestamp: 108121485, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  903): add 11 to mScanResults
D/BatSI   (  903): WIFI scan stopped for: 640a0300 uid:1000
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/WifiNotificationController(  903): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/wpa_supplicant( 1150): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1150): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1150): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1150): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1150): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1150): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1150): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1150): nl80211: Event message available
D/wpa_supplicant( 1150): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1150): nl80211: Connect event
D/wpa_supplicant( 1150): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1150): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1150): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1150): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1150): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1150): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1150): Add randomness: count=27 entropy=10
I/wpa_supplicant( 1150): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1150): TDLS: Remove peers on association
D/wpa_supplicant( 1150): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1150): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1150): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1150): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1150): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1150): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1150): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1150): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1150): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1150): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1150): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1150): EAPOL: enable timer tick
D/wpa_supplicant( 1150): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1150): htc_wext_set_keepalive +
I/wpa_supplicant( 1150): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1150): getPrivFuncNum +	
,I/wpa_supplicant( 1150): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1150): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1150): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1150): State: ASSOCIATED -> 4WAY_HANDSHAKE
,D/wpa_supplicant( 1150): Get randomness: len=32 entropy=11
D/Tethering(  903): interfaceLinkStateChanged wlan0, false
D/Tethering(  903): interfaceStatusChanged wlan0, false
D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/Tethering(  903): interfaceLinkStateChanged wlan0, true
D/Tethering(  903): interfaceStatusChanged wlan0, true
,D/Tethering(  903): [isWifi] getHotspotEnabled: false
,D/WifiMonitor(  903): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  903): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  903): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  903): WifiMonitor:getFreqFromEventString() 2412
,D/HTCRequest(  903): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  903): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  903): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  903): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  903): Enter handleAssociatedWithEvent
,D/WifiStateMachine(  903): Associated
D/WifiStateMachine(  903): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  903): Exit handleAssociatedWithEvent
,D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1150): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1150): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb7f5d9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 1150):    addr=c0:ff:d4:d3:aa:48
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1150): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1150): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1150): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f5fb4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1150):    broadcast key
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1150): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1150): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1150): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1150): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1150): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
,I/wpa_supplicant( 1150): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
E/wpa_supplicant( 1150): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1150): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1150): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1150): set send_ind_to_ndc = 0
I/wpa_supplicant( 1150): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1150): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1150): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1150): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1150): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1150): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1150): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1150): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1150): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1150): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 1150): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1150): EAPOL authentication completed successfully
I/wpa_supplicant( 1150): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1150): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1150): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1150): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  903): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  903): BSSID was changed, update WiFi database
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  903): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  903): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  903): interfaceLinkStateChanged wlan0, true
D/Tethering(  903): interfaceStatusChanged wlan0, true
,D/Tethering(  903): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  903): updateConnectedAP...
D/WifiApDatabaseHandler(  903): updateConnectedAP...
,D/WifiStateMachine(  903): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiApDatabaseHandler(  903): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  903): This record is existed, only update it...
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  903): updateConnectedAP...
,W/dalvikvm( 4529): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
,D/WifiApDatabaseHandler(  903): updateConnectedAP...,
,D/WifiStateMachine(  903): fetchFrequency(), freq = 2412,
D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  903): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiApDatabaseHandler(  903): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  903): This record is existed, only update it...,
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  903): updateConnectedAP...,
,I/IntentController( 1113): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WISPrService( 4221): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4221): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  903): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  903): Provision feature enable=false
D/ConnectivityService(  903): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1113): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateMachine(  903): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  903): updateConnectedAP...
,D/DhcpStateMachine(  903): [StoppedState] Start DHCP
D/WifiStateMachine(  903): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1150): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -48 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1150): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,W/dalvikvm( 4529): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1150): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 1
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1150): Power_Mode_Type mode = 1
I/wpa_supplicant( 1150): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1150): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  903):    returned null
E/WifiStateMachine(  903): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  903): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1150): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  903):    returned null
D/WifiStateMachine(  903): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  903): acquireWL(43153828): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 903 1000 null
D/WifiStateMachine(  903): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  903): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4290f8f0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4290f8f0 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1113): receive.wifiConnect:false wifiAPname:null elapse:0
,E/FbInjectorInitializer( 4529): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.,
,W/fb4a(:<default>):StaticBindingVerifier( 4529): Verify
,D/WifiService(  903): New client listening to asynchronous messages
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4529/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4529): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4529): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4529): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  903): killProcessQuiet, pid=3227
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  903): Killing 3227:com.android.defcontainer/u0a19 (adj 15): empty #17
,D/PMS     (  903): acquireWL(43b7c5b8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2184 10028 null
,D/PMS     (  903): acquireWL(43c14ae0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2184 10028 null
,D/PMS     (  903): releaseWL(43b7c5b8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2184/10028)
,I/ActivityManager(  903): Recipient 3227
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/GCM     ( 1372): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1372/10028)
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1372/10028)
D/PMS     (  903): releaseWL(43c14ae0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2184/10028)
,D/AutoSetting( 1387): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  903): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4560 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1387/10053)
,D/AutoSetting( 1387): Util - no network available!
,D/AutoSetting( 1387): service - onCreate()
,D/AutoSetting( 1387): service - AddressCache: using context: com.htc.Weather
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1387/10053)
D/LocationManagerService(  903): request 427f4528 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/LocationManagerService(  903): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1387): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1387): service - mHandler: cancel location update
D/AutoSetting( 1387): service -           changes count: 0
,W/fb4a(:<default>):UserScope( 4529): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4529): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/MobileConnectivityChangeReceiver( 4560): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4560): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4560): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4560): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,W/fb4a(:<default>):UserScope( 4529): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
I/ActivityManager(  903): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4576 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4560/10078)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4560/10078)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4560/10078)
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4529): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  903): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4593 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  903): killProcessQuiet, pid=3884
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Killing 3884:com.htc.mediamanager/u0a32 (adj 15): empty #17
,E/dalvikvm( 4529): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4529): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4529): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4529): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4529): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4529): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4529): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4529): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4529): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4529): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4529): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4529): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4529): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4529): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4529): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4529): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4529): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4529): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4593): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,I/dalvikvm-heap( 4529): Grow heap (frag case) to 9.918MB for 39954-byte allocation
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4593): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4593): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4593): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4593): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4529): Grow heap (frag case) to 9.995MB for 79892-byte allocation
,I/ActivityManager(  903): Recipient 3884
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4529): Grow heap (frag case) to 10.066MB for 84664-byte allocation
,I/dalvikvm-heap( 4529): Grow heap (frag case) to 10.092MB for 28144-byte allocation
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (4593/10151)
,V/WebViewChromiumFactoryProvider( 4593): Binding Chromium to main looper Looper (main, tid 1) {41d5ee70}
,I/LibraryLoader( 4593): Expected native library version number "",actual native library version number ""
,I/chromium( 4593): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4593): Initializing chromium process, renderers=0
,D/PMS     (  903): acquireWL(43d6d788): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,D/PMS     (  903): acquireWL(43e06870): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,E/AudioManagerAndroid( 4593): BLUETOOTH permission is missing!
D/PMS     (  903): releaseWL(43d6d788): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4593): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4593): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4593): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4593): Local Branch: 
I/Adreno-EGL( 4593): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4593): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4593):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4593): Starting up...
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (4593/10151)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (4593/10151)
,D/wpa_supplicant( 1150): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1150): EAPOL: disable timer tick
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (4199/10160)
,D/Process (  903): killProcessQuiet, pid=4044
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (4199/10160)
I/ActivityManager(  903): Killing 4044:com.google.android.gm/u0a107 (adj 15): empty #17
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1809/10178)
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1809/10178)
,D/GCM     ( 1372): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/dalvikvm-heap( 4529): Grow heap (frag case) to 10.280MB for 75760-byte allocation
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4529/10026)
,W/BroadcastQueue(  903): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42ab7840 u0 ReceiverList{42ab7720 4529 com.facebook.katana/10026/u0 remote:4295fb20}}
,W/BroadcastQueue(  903): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42ab7840 u0 ReceiverList{42ab7720 4529 com.facebook.katana/10026/u0 remote:4295fb20}}
,W/BroadcastQueue(  903): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43b297d0 u0 ReceiverList{43468878 4529 com.facebook.katana/10026/u0 remote:434269b0}}
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4529/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4529/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4529/10026)
,D/PMS     (  903): acquireWL(43841ea0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1447 10028 null
,D/PMS     (  903): releaseWL(43841ea0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/GCoreFlp( 1447): Unknown pending intent to remove.
D/PMS     (  903): acquireWL(43d5fe10): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1447 10028 null
I/ActivityManager(  903): Recipient 4044
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  903): releaseWL(43d5fe10): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4529): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4529): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,D/libc    (  903): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  903): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
D/libc    (  903): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
D/libc    (  903): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
D/libc    (  903): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  903): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1150): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1150): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 61,
D/WifiNative-wlan0(  903):    returned true,
,D/WifiNative-wlan0(  903): doBoolean: DRIVER BTCOEXMODE 2,
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2",
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1150): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12,
D/WifiNative-wlan0(  903):    returned true
,D/WifiStateMachine(  903): handlePostDhcpSetup release wake lock during DHCP
D/WifiP2pService(  903): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  903): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  903): releaseWL(43153828): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1150): environment dirty rate=100 [1][1][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1150): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,D/WifiStateMachine(  903): gateway: /192.168.1.1
D/WifiNative-wlan0(  903): doBoolean: DRIVER GATEWAY-ADD 16885952
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1150): WiFi gateway: 0x101a8c0,
D/WifiNative-wlan0(  903):    returned true
,D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  903): VerifyingLinkState enter
,D/WifiStateMachine(  903): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  903): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  903): VerifyingLinkState: enableIpv6
,D/WIFI_ICON( 1113): updateWifiState: RSSI_CHANGED -1 -> 3
,D/WifiStateMachine(  903): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -47, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  903): onReceive: action=android.net.wifi.STATE_CHANGE
,I/IntentController( 1113): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiDataStallTracker(  903): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  903): startDataStallAlarm: tag=20657 delay=15s
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
V/NetworkPolicy(  903): mWifiStateReceiver: meteredHint=false,EPS mode=false
,D/WifiWatchdogStateMachine(  903): WAN detection
D/WifiStateTracker(  903): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  903): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  903): Provision feature enable=false
D/ConnectivityService(  903): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  903): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  903): default: teardown()
D/MDST    (  903): default: setTeardownRequested(true)
D/MDST    (  903): default: setEnableApn apnType =default , enable=false
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1809/10178)
,D/WISPrService( 4221): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
D/libc    (  903): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
D/MDST    (  903): default: setTeardownRequested(true)
D/ConnectivityService(  903): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  903): Unexpected mtu value: android.net.wifi.WifiStateTracker@42692558
,D/ConnectivityService(  903): handleConnectivityChange: netType=1 doReset=false resetMask=0
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1150): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  903): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  903): syncGetConfiguredNetworks
D/WIFI_ICON( 1113): updateWifiState: NETWORK_STATE_CHANGED connected
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WIFI_ICON( 1113): WifiActivity: 3
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  903): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  903): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
,I/QuickSettingWifi( 1113): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/ConnectivityService(  903): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  903): handleConnectivityChange: resetting
D/Nat464Xlat(  903): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  903): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  903): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  903): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  903): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  903): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  903): acquireWL(434e88e0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 903 1000 null
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
D/WirelessDisplayService(  903): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  903):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4560/10078)
D/PMS     (  903): acquireWL(4445cd60): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2184 10028 null
,D/PMS     (  903): acquireWL(4303a468): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2184 10028 null
I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
D/PMS     (  903): releaseWL(4445cd60): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2184/10028)
,I/CheckinService( 2184): Preparing to send checkin request
,I/EventLogService( 2184): Accumulating logs since 1450461106243
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,I/GoogleHttpClient( 2184): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2184): Using GMS GoogleHttpClient
D/ConnectivityService(  903): mActiveDefaultNetwork: WIFI
,D/ConnectivityService(  903): getNetworkInfo networkType=9 called by com.google.android.gms (2184/10028)
,D/ConnectivityService(  903): getNetworkInfo networkType=0 called by com.google.android.gms (2184/10028)
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/PMS     (  903): releaseWL(434e88e0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1562): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1562): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/CheckinRequestBuilder( 2184): awaiting user notification for token
,I/RemoteViews( 1113): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{4210b070 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1113): com.google.android.gms 0 6 2 12
,I/ActivityManager(  903): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4668 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 4668): install
,I/MultiDex( 4668): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4668): loading existing secondary dex files
,I/MultiDex( 4668): load found 1 secondary dex files
,I/MultiDex( 4668): install done
,I/ProviderInstaller( 4668): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1372): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/Adreno-EGL( 4668): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4668): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4668): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4668): Local Branch: 
I/Adreno-EGL( 4668): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4668): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4668):                  aa63bbd948f41d15fc72f585e
,W/dalvikvm( 4443): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4443): threadid=1: thread exiting with uncaught exception (group=0x41934e30)
,E/ActivityManager(  903): App crashed! Process: com.test.thalitest
E/AndroidRuntime( 4443): FATAL EXCEPTION: main
E/AndroidRuntime( 4443): Process: com.test.thalitest, PID: 4443
E/AndroidRuntime( 4443): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4443): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4443): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4443): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4443): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4443): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4443): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4443): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4443): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4443): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4443): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4443): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4443): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4443): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4443): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4443): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4443): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4443): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4443): 	at dalvik.system.NativeStart.main(Native Method)
W/ActivityManager(  903):   Force finishing activity com.test.thalitest/.MainActivity
,I/ActivityManager(  903): mThumbnailWidth=360, mThumbnailHeight=640
,D/PMS     (  903): acquireWL(43bc57c8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 903 1000 null
,W/asset   (  903): Copying FileAsset 0x6a2b0ea0 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,D/WIFI_ICON( 1113): WifiActivity: 1
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  903): releaseWL(42745460): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  903): NetTransition Wakelock for ConnectedState released by timeout
,V/Tethering(  903): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
V/Tethering(  903): bSetPropertyMultiRAB:false
D/Tethering(  903): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/Tethering(  903): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  903): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  903): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  903): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  903): Found interface wlan0
,D/Tethering(  903): TetherMasterSM: InitialState processMessage what=3
I/AlarmManager(  903): [AlarmQueuing] connectivity wifi: true
,D/CaptivePortalTracker(  903): NoActiveNetworkState
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,I/NetworkMonitor( 4509): type=WIFI subType= reason=null isConnected=true
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
,I/ConnectivityHelper( 1269): [onReceive] WIFI(1): CONNECTED
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.google.android.music (4509/10154)
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.htc.launcher (1269/10075)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.docs (4330/10100)
D/ConnectivityService(  903): getNetworkInfo networkType=1 called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1809/10178)
,I/acms    ( 1857): Checking Certificates
,D/CaptivePortalTracker(  903): DelayedCaptiveCheckState
,I/acms    ( 1857): Checking Developer Certificates
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.docs (4330/10100)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.musicenhancer (3914/10051)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.setupwizard (4560/10078)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1857/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1447/10028)
D/PMS     (  903): acquireWL(4278f988): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 903 1000 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4529/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  903): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
,I/acms    ( 1857): Checking Application Certificates
I/acms    ( 1857): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1857): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1857): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1857): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1857): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1857): Updating next query delay: 75600000
I/mlserverapp( 1857): MirrorLink is never connected, don't setup ACMS programed checks
,I/mlserverapp( 1857): cancelACMSProgrammedChecks
D/GpsLocationProvider(  903): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  903): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  903): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  903): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/PMS     (  903): acquireWL(41fee360): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4529/10026)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4529/10026)
D/PMS     (  903): releaseWL(41fee360): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  903): releaseWL(4278f988): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (2405/10021)
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5,
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
D/PMS     (  903): acquireWL(43ce8cb0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2184 10028 null
D/PMS     (  903): releaseWL(43ce8cb0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1372): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2184/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1372/10028)
D/libc    ( 1372): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1372): [NET] getaddrinfo-,err=8
D/libc    ( 1372): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1372): [NET] getaddrinfo-, 1
,D/libc    ( 1372): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =4020 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/PMS     (  903): acquireWL(42588118): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1372 10028 null
,D/AutoSetting( 1387): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4560): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4560): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1387/10053)
,D/AutoSetting( 1387): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1387): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1387): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1387): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 1387): service - handleMessage() setting current location null
D/AutoSetting( 1387): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1387): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1387/10053)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.magazines (4593/10151)
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1150): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
,E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (4199/10160)
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.apps.plus (4199/10160)
D/ConnectivityService(  903): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1809/10178)
,I/dalvikvm-heap( 4199): Grow heap (frag case) to 13.511MB for 1821008-byte allocation
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 228
D/libc    (  364): [NET]res_nsend:resplen=79
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1372): [NET] getaddrinfo_proxy-, success
,W/Settings( 4668): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/libc    ( 1372): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1372): [NET] getaddrinfo-,err=8
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1150): environment dirty rate=0 [5][0][0]
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1372/10028)
D/PMS     (  903): acquireWL(43e58df0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
,D/PMS     (  903): releaseWL(43e58df0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiStateMachine(  903): BroadcastRSSIForIMS, newrssi =-47 , oldRssi= -200
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1150): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
D/WIFI_ICON( 1113): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/ActivityManager(  903): Activity pause timeout for ActivityRecord{4235f400 u0 com.test.thalitest/.MainActivity t2 f}
,I/Adreno-EGL( 4668): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4668): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4668): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4668): Local Branch: 
I/Adreno-EGL( 4668): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4668): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4668):                  aa63bbd948f41d15fc72f585e
,I/FeedHostManager( 1269): [onResume]
,I/FeedProviderManager( 1269): onResume
,I/SocialFeedProvider( 1269): +onResume
I/SocialFeedProvider( 1269): updateAccounts - Accounts is no change
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.launcher (1269/10075)
I/SocialFeedProvider( 1269): -onResume
,I/Adreno-EGL( 4668): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4668): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4668): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4668): Local Branch: 
I/Adreno-EGL( 4668): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4668): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4668):                  aa63bbd948f41d15fc72f585e
,D/GCM     ( 1372): Connected
D/PMS     (  903): acquireWL(428b5580): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1372 10028 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1372/10028)
D/PMS     (  903): releaseWL(42588118): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1372/10028)
,D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1372/10028)
,D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  903): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1372/10028)
,D/PMS     (  903): releaseWL(428b5580): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  903): acquireWL(42747c28): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1372 10028 null
,D/PMS     (  903): releaseWL(43bc57c8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,I/PMS     (  903): Going to sleep due to screen timeout...
,I/SensorManager(  903): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@423e8b68
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  903): disable: get sensor name = CM36282 Light sensor
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 2
W/SensorService(  903): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  903): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  903): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@423e8b68, eanble = 0, strlen(mName) = 59
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  903): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@425fbba0
W/SensorService(  903): Listener[1] = com.htc.smartdim.sensor_eye@42317330
,W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/WirelessDisplayService(  903): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  903): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  903): mWirelessDisplayManager is null
W/BatSI   (  903): Couldn't get kernel wake lock stats
V/LightsService(  903): setLight #2: color=#0
D/qdlights(  903): set_light_buttons_func: on=0 brightness=0
V/LightsService(  903): setLight #0: color=#0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1372/10028)
D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  903): handleInetConditionChange: currently in hold - not setting new end evt
,D/GCM     ( 1372): Message class mpf
,D/Process (  903): killProcessQuiet, pid=4299
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
I/ActivityManager(  903): Killing 4299:com.google.android.partnersetup/u0a31 (adj 15): empty #17
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1372/10028)
D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  903): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1372/10028)
,D/PMS     (  903): acquireWL(4279b4e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
,D/PMS     (  903): releaseWL(4279b4e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  903): releaseWL(42747c28): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,I/ActivityManager(  903): Recipient 4299
,D/SurfaceControl(  903): Excessive delay in blankDisplay() while turning screen off: 380ms
D/PMS     (  903): nativeSetInteractive:false
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  903): nativeSetInteractive:false done
,D/PMS     (  903): nativeSetAutoSuspend:true
,D/PMS     (  903): nativeSetAutoSuspend:true done
,D/HABCtrl (  903): TPE algorithm. remove timeout.
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (4668/10028)
,I/InputManager(  903): Cancel all due to getting PMS screen off broadcast
,D/PMS     (  903): acquireWL(428b8ef0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/InputMethodManagerService(  903): screenObserver, isScreenOn=false
D/NfcService( 1256): ScreenObserver: OFF
,D/NfcService( 1256): applyRouting - 0
,D/NfcService( 1256): applyRouting -2
I/BatteryService(  903): n_update end
I/InputMethodManagerService(  903): Disable input method client, pid=4443
D/PMS     (  903): OOBE c monitor 11
D/PMS     (  903): releaseWL(428b8ef0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  903): acquireWL(43e2d390): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): releaseWL(43e2d390): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/IntentController( 1113): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4529/10026)
,V/KeyguardServiceDelegate(  903): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@425fba50)
,V/KeyguardServiceDelegate(  903): **** SHOWN CALLED ****
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/PMN     (  903): wakingUp
I/WindowManager(  903): No lock screen! windowToken=null
,D/PMN     (  903): onScreenOn
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4529/10026)
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,D/ConnectivityService(  903): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  903): sendGeneralBroadcast, restrictEnable=false
,D/WirelessDisplayService(  903): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  903): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  903): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/MtpService( 2405): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2405): [MTP][onReceive]-
,D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/AutoSetting( 1387): receiver - intent: android.intent.action.USER_PRESENT
,D/NfcService( 1256): applyRouting - 0
,D/NfcService( 1256): applyRouting -2
D/PMS     (  903): acquireWL(43bc77b0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
D/WirelessDisplayService(  903): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  903): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  903): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,I/ClockThread( 1113): stop update clock
D/PMS     (  903): releaseWL(43bc77b0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
V/NotificationService(  903): batLight: Full, plugged
V/LightsService(  903): setLight #8: color=#c8c800
D/qdlights(  903): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  903): setLight #8: color=#c800
D/qdlights(  903): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AutoSetting( 1387): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
,D/WifiDataStallTracker(  903): onReceive: action=android.intent.action.SCREEN_ON
D/WifiDataStallTracker(  903): startDataStallAlarm: tag=20658 delay=15s
,I/CheckinTask( 2184): Sending checkin request (8963 bytes)
D/AlarmManager(  903): ACTION_SCREEN_ON
I/AlarmManager(  903): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  903): [AlarmQueuing] done recovering
I/AlarmManager(  903): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  903): [AlarmQueuing] done EPS screen off alarm recovering
D/WIFI_ICON( 1113): WifiActivity: 3
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
D/TetherSettings( 4221): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/WifiNative-wlan0(  903): doBoolean: SET_SCREEN_ON 1
D/libc    ( 2184): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2184): [NET] getaddrinfo-,err=8
D/libc    ( 2184): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2184): [NET] getaddrinfo-, 1
D/libc    ( 2184): [NET] getaddrinfo_proxy+
D/        ( 4221): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4221): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4221): Cust_ConnectToPC   : spcsc>false
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/        ( 4221): Cust_ConnectToPC   : IPT>true
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =c0c2 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
D/        ( 4221): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 4221): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1150): environment dirty rate=0 [4][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1150): SET_SCREEN_ON:On
I/wpa_supplicant( 1150): htc_wext_set_keepalive +
I/wpa_supplicant( 1150): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1150): getPrivFuncNum +	
I/wpa_supplicant( 1150): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1150): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1150): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1150): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1150): htc_wext_set_TX_TRACKING - ret = 0
E/SmartNS_Utility( 4221): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4221): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/WifiNative-wlan0(  903):    returned true
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/SmartNS_NSReceiver( 4221): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
I/PSReceiver( 4221): onReceive:android.intent.action.USER_PRESENT
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1150): environment dirty rate=100 [1][1][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
I/SmartNS_PSService( 4221): onReceive:android.intent.action.USER_PRESENT
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -47 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
W/Settings( 4221): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 4221):  defaultType:0
W/ContextImpl( 4221): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/WIFI_ICON( 1113): WifiActivity: 2
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
V/NotificationService(  903): batLight: Full, plugged
V/LightsService(  903): setLight #8: color=#c8c800
D/qdlights(  903): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  903): setLight #8: color=#c800
D/qdlights(  903): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1150): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  903):    returned true
V/SRS_Proc(  371): ParamSet string: screen_state=on
D/WirelessDisplayService(  903): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
W/fb4a(:<default>):UserScope( 4529): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/fb4a(:<default>):UserScope( 4529): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/WIFI_ICON( 1113): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_out_4 (gone) T]
D/NetworkPolicy(  903): updateScreenOn: false
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  364): [NET]res_nsend:resplen=84
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 2184): [NET] getaddrinfo_proxy-, success
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  903): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4713 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4529/10026)
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1150): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1150): environment dirty rate=0 [1][0][0]
D/libc    ( 2184): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2184): [NET] getaddrinfo-,err=8
,D/PMS     (  903): releaseWL(43e06870): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4529/10026)
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,W/ContextImpl( 4713): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  903): acquireWL(43029fd0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1447 10028 null
,D/PMS     (  903): releaseWL(43029fd0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1765): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1765): onScreenOn: 1450461160597
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1765): onScreenOn: 1450461160597
,D/SmartSyncUtils( 4713): isEpsOn(), nState = 0
D/PMS     (  903): acquireWL(43e64cc8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4713 1000 null
,I/SensorManager(  903): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@425fbba0
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  903): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 2
W/SensorService(  903): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  903): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  903): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@425fbba0, eanble = 0, strlen(mName) = 91
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  903): Listener[0] = com.htc.smartdim.sensor_eye@42317330
,W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  903): goingToSleep
D/PMS     (  903): acquireWL(44044688): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 903 1000 null
,D/PMS     (  903): releaseWL(43e64cc8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/AlarmManager(  903): ACTION_SCREEN_OFF
I/AlarmManager(  903): [AlarmQueuing] screen off now: 
I/AlarmManager(  903): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  903): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  903): stopDataStallAlarm: current tag=20658 mDataStallAlarmIntent=PendingIntent{43fe2058: PendingIntentRecord{429247c0 android broadcastIntent}}
I/FeedHostManager( 1269): [onPause]
,I/FeedProviderManager( 1269): onPause
I/FeedHostManager( 1269): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41e125d0
I/SocialFeedProvider( 1269): +onPause
,I/SocialFeedProvider( 1269): -onPause
,D/WifiNative-wlan0(  903): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1150): SET_SCREEN_ON:Off
I/wpa_supplicant( 1150): htc_wext_set_keepalive +
I/wpa_supplicant( 1150): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1150): getPrivFuncNum +	
I/wpa_supplicant( 1150): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1150): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1150): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1150): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1150): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  903):    returned true
I/AlarmManager(  903): [AlarmQueuing] wifi connection: true
,D/PMS     (  903): acquireWL(42ad7240): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 903 1000 null
D/WifiNative-wlan0(  903): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
,D/SmartSyncUtils( 4713): getMobilePolicyEnabled, result = true
,D/PMS     (  903): releaseWL(44044688): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,V/SRS_Proc(  371): ParamSet string: screen_state=off
,D/Process (  903): killProcessQuiet, pid=4330
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/wpa_supplicant( 1150): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  903):    returned true
I/ActivityManager(  903): Killing 4330:com.google.android.apps.docs/u0a100 (adj 15): empty #17
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  903): releaseWL(42ad7240): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
D/NetworkPolicy(  903): updateScreenOn: false
,D/PMS     (  903): acquireWL(4451afb0): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4509 10154 null
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1150): environment dirty rate=20 [10][2][0]
,W/ContextImpl( 4509): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/SmartSyncUtils( 4713): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4713): getMobilePolicyEnabled, result = true
,W/ContextImpl( 4713): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/SmartSyncUtils( 4713): isEpsOn(), nState = 0
,W/ContextImpl( 4509): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/ContactMessageStore( 1241): start background delete task...
D/WifiService(  903): New client listening to asynchronous messages
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  903): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42317330
D/ContactMessageStore( 1241): size: 0 , 0
D/ContactMessageStore( 1241): Background delete complete
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  903): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 1
W/SensorService(  903): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  903): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42317330, eanble = 0, strlen(mName) = 36
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  903): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 0
W/SensorService(  903): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42317330, eanble = 0, strlen(mName) = 36
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  903): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42317330
E/ActivityThread(  903): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@41ef6ce0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  903): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@41ef6ce0 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] getTotalRam: 1873 Mb
D/PMS     (  903): acquireWL(430f76a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1447 10028 null
,D/PMS     (  903): releaseWL(430f76a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1765): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1765): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1765): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1765): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1765): onScreenOff
D/AutoSetting( 1387): service - mHandler: cancel location update
,D/AutoSetting( 1387): service -           changes count: 0
I/ActivityManager(  903): Recipient 4330
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/fb4a(:<default>):LocalFbBroadcastManager( 4529): Called registerBroadcastReceiver twice.
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4509, uid=10154, userID:0
,I/MusicLeanback( 4509): Conditions not met for autocaching.
,I/MusicLeanback( 4509): Stop autocaching.
D/PMS     (  903): releaseWL(4451afb0): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4529/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4529/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4529/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4529/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4529/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4529/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4529/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4529/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4529/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4529/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4529/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4529/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4529/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4529/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4529/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4529/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4529/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4529/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4529/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4529/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4529/10026)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.facebook.katana (4529/10026)
,D/WifiStateMachine(  903): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  903): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  903): [MLHD] enter handleMediaLinkEvent DefaultState
,D/PMS     (  903): acquireWL(43af8300): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
,D/PMS     (  903): releaseWL(43af8300): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  903): getNetworkInfo networkType=9 called by com.google.android.gms (2184/10028)
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  903): getNetworkInfo networkType=0 called by com.google.android.gms (2184/10028)
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1150): environment dirty rate=75 [4][3][0]
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1562): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1562): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1113): com.google.android.gms (false,0)
,W/CheckinRequestBuilder( 2184): awaiting user notification for token
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{4213d740 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1113): com.google.android.gms 1 12 3 12
,I/CheckinTask( 2184): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2184): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2184/10028)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2184/10028)
,D/GCM     ( 1372): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  903): releaseWL(4303a468): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
E/ActivityThread( 2184): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41fc4d00 that was originally bound here
E/ActivityThread( 2184): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41fc4d00 that was originally bound here
E/ActivityThread( 2184): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2184): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2184): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2184): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2184): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2184): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2184): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2184): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2184): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2184): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2184): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2184): 	at bks.a(SourceFile:298)
E/ActivityThread( 2184): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2184): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2184): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2184): 	at java.lang.Thread.run(Thread.java:864)
,D/libc    (  903): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-,err=8
D/libc    (  903): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  903): [NET] getaddrinfo-, 1
D/libc    (  903): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
,D/libc    (  364): [NET] +++++ res_nsend xid =4a87 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,I/GCM     ( 1372): GCM config loaded
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  903): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  903): Find DNS Address www.htc.com/23.59.123.86
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC <<
,I/GAV2    ( 4593): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  903): acquireWL(445e9568): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1447 10028 null
,D/PMS     (  903): acquireWL(445d2c38): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1447 10028 null
,D/PMS     (  903): releaseWL(445e9568): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  903): releaseWL(445d2c38): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/Process (  903): killProcessQuiet, pid=4346
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4346:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4346
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1493): service - handleMessage() stop self
,D/AutoSetting( 1493): service - onDestroy() END
,D/AutoSetting( 1493): service - handleMessage() quit looper
,D/Process (  903): killProcessQuiet, pid=3914
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3914:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,D/CaptivePortalTracker(  903): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  903): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  903): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
I/ActivityManager(  903): Recipient 3914
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ActivityManager(  903): Activity destroy timeout for ActivityRecord{4235f400 u0 com.test.thalitest/.MainActivity t2 f}
,I/ActivityManager(  903): Waited long enough for: ServiceRecord{43533940 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  903): acquireWL(43e1a3b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e1be00: PendingIntentRecord{41e14c58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=131624, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43e1a3b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43df15e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1113): closing low battery warning: level=100
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): releaseWL(43df15e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
,I/HtcPowerSaver(  903): >> updateStatus
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1387): service - mHandler: update timezone
,D/AutoSetting( 1493): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  903): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1493): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1493): service - onCreate()
W/ActivityManager(  903): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1493): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1493): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,V/NotificationService(  903): batLight: Full, plugged
V/LightsService(  903): setLight #8: color=#c8c800
D/qdlights(  903): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  903): setLight #8: color=#c800
D/qdlights(  903): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/DotMatrix( 1562): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1562): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1493): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1493): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1493): service - mHandler: update timezone
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1493): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1493): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1493): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1493): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1562): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1562): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1113): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41eae6b0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1113): com.htc.htclocationservice 2 5 2 11
,D/GpsLocationProvider(  903): ALARM_XTRA_TIMEOUT
D/PMS     (  903): acquireWL(43b24df0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
V/AlarmManager(  903): sending alarm PendingIntent{425e33a8: PendingIntentRecord{42656a60 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142295, Int=0
D/PMS     (  903): acquireWL(43b1dd18): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 903 1000 null
D/GpsLocationProvider(  903): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  903): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
V/AlarmManager(  903): sending alarm PendingIntent{42dc7488: PendingIntentRecord{420eccd8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142383, Int=0
,D/PMS     (  903): releaseWL(43b24df0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1372/10028)
,D/PMS     (  903): acquireWL(43925dc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
,D/libc    (  903): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-,err=8
D/libc    (  903): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  903): [NET] getaddrinfo-, 1
,D/libc    (  903): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =5f37 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/PMS     (  903): releaseWL(43925dc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/AutoSetting( 1387): service - handleMessage() stop self
,D/AutoSetting( 1387): service - handleMessage() quit looper
,D/AutoSetting( 1387): service - onDestroy() END
,D/PMS     (  903): acquireWL(438d9920): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10028 null
,D/PMS     (  903): releaseWL(438d9920): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  903): acquireWL(43869cd0): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10028 null
,D/PMS     (  903): releaseWL(43869cd0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  903): acquireWL(4286f050): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10028 null
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  364): [NET]res_nsend:resplen=238
D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  903): [NET] getaddrinfo_proxy-, success
I/global  (  903): call createSocket() return a new socket.
D/libc    (  903): [NET] getaddrinfo+,hn 14(0x35342e3233302e),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-, SUCCESS
,D/PMS     (  903): releaseWL(4286f050): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  903): acquireWL(42600890): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10028 null
,D/GpsLocationProvider(  903): [handleDownloadXtraData] calling native_inject_xtra_data
,D/PMS     (  903): releaseWL(42600890): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/GpsLocationProvider(  903): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  903): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  903):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  903): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  903): releaseWL(43b1dd18): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/Process (  903): killProcessQuiet, pid=4317
,I/ActivityManager(  903): Killing 4317:com.htc.cs.dm/u0a98 (adj 15): empty #17
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  903): Recipient 4317
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/ActivityManager(  903): Waited long enough for: ServiceRecord{43e2aaf8 u0 com.htc.htclocationservice/.AutoSettingService}
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1493): service - handleMessage() stop self
,D/AutoSetting( 1493): service - onDestroy() END
,D/Process (  903): killProcessQuiet, pid=4369,
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/AutoSetting( 1493): service - handleMessage() quit looper
I/ActivityManager(  903): Killing 4369:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4369
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  903): acquireWL(4224fcd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PMS     (  903): releaseWL(4224fcd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1241): switchBindHtcMsgCursor: null
,D/PMS     (  903): acquireWL(42568980): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e1be00: PendingIntentRecord{41e14c58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=191623, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42568980): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(4297f400): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PowerUI ( 1113): closing low battery warning: level=100
,D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
D/PMS     (  903): releaseWL(4297f400): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  903): acquireWL(42331aa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10026}
,V/AlarmManager(  903): sending alarm PendingIntent{427876d0: PendingIntentRecord{435b3fd0 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=229285, Int=0
,I/ActivityManager(  903): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4765 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  903): sending alarm PendingIntent{4274c758: PendingIntentRecord{4274b7e0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1450461269589, Int=10800000
,D/PMS     (  903): releaseWL(42331aa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.aurora (4765/10047)
,D/Process (  903): killProcessQuiet, pid=4389
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4389:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4389
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2184/10028)
,D/PMS     (  903): acquireWL(42704530): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/PMS     (  903): releaseWL(42704530): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1113): closing low battery warning: level=100
D/HtcPowerSaver(  903): Checking...
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(42960ce8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10026}
,V/AlarmManager(  903): sending alarm PendingIntent{4285dc20: PendingIntentRecord{435b3fd0 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=232259, Int=0
,D/PMS     (  903): releaseWL(42960ce8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  903): acquireWL(4283e208): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000},
,V/AlarmManager(  903): sending alarm PendingIntent{41e1be00: PendingIntentRecord{41e14c58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=251623, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(4283e208): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(425b7068): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(425b7068): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  903): acquireWL(4280c578): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): releaseWL(4280c578): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  903): acquireWL(42564210): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e1be00: PendingIntentRecord{41e14c58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=311623, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42564210): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43926d10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43926d10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  903): acquireWL(42984360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): releaseWL(42984360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1562): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1562): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1113): com.google.android.gms (false,0)
,W/GLSActivity( 1372): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1372): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1372): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1372): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1372): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1372): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1372): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1372): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41f22d30 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/PlayEventLogger( 4163): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4163): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4163): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4163): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4163): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4163): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4163): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4163): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews.Performance( 1113): com.google.android.gms 1 12 5 12
,D/libc    ( 4163): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4163): [NET] getaddrinfo-,err=8
D/libc    ( 4163): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4163): [NET] getaddrinfo-, 1
,D/libc    ( 4163): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024,
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =603d +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE,
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 73
D/libc    (  364): [NET]res_nsend:resplen=87
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4163): [NET] getaddrinfo_proxy-, success
I/global  ( 4163): call createSocket() return a new socket.
D/libc    ( 4163): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4163): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 4163): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4163): [NET] getaddrinfo-,err=8
,D/PMS     (  903): acquireWL(427c6b50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e1be00: PendingIntentRecord{41e14c58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=371624, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(427c6b50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43980ca8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  903): releaseWL(43980ca8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 4
,D/Process ( 4443): killProcess, pid=4443
,D/Process ( 4443): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/InputMethodManagerService(  903): Disable input method client, pid=4443
,W/InputDispatcher(  903): channel '42601750 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  903): channel '42601750 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  903): Attempted to unregister already unregistered input channel '42601750 com.test.thalitest.MainActivity (s)'
I/WindowManager(  903): WINDOW DIED Window{42601750 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager(  903): Recipient 4443
I/ActivityManager(  903): Process com.test.thalitest (pid 4443) has died.
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  903): Client connection lost with reason: 4
W/WindowManager(  903): Failed looking up window
W/WindowManager(  903): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@41e2a7b0 does not exist
W/WindowManager(  903): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8463)
W/WindowManager(  903): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8454)
W/WindowManager(  903): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1052)
W/WindowManager(  903): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/WindowManager(  903): 	at dalvik.system.NativeStart.run(Native Method)
I/WindowState(  903): WIN DEATH: null
,D/PMS     (  903): acquireWL(438e89d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10026}
,V/AlarmManager(  903): sending alarm PendingIntent{43b1e588: PendingIntentRecord{428b66b0 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=411963, Int=300000
,V/AlarmManager(  903): sending alarm PendingIntent{43bbee48: PendingIntentRecord{428f29c8 com.google.android.gms broadcastIntent}}, i=null, t=1, cnt=1, w=1450461408397, Int=0
,D/PMS     (  903): releaseWL(438e89d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,W/Uploader( 2184): No account for auth token provided
,D/libc    ( 2184): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 2184): [NET] getaddrinfo-,err=8
D/libc    ( 2184): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 2184): [NET] getaddrinfo-, 1
,D/libc    ( 2184): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =a16 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 2184): [NET] getaddrinfo_proxy-, success
I/global  ( 2184): call createSocket() return a new socket.
D/libc    ( 2184): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 2184): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 2184): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 2184): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2184/10028)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2184/10028)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2184/10028)
,D/PMS     (  903): acquireWL(429558e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
V/NotificationService(  903): batLight: plugged
V/LightsService(  903): setLight #8: color=#c8c800
D/qdlights(  903): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  903): setLight #8: color=#c80000
D/qdlights(  903): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute
D/HtcPowerSaver(  903): updateBatteryInfo
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  903): releaseWL(429558e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1113): closing low battery warning: level=98
,D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetPhoneState( 1588): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/DotMatrix( 1562): [EventService] reorderNotification, total:1
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/ContextImpl( 4713): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 4221): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4221): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4221): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4221): Cust_ConnectToPC   : spcsc>false
D/        ( 4221): Cust_ConnectToPC   : IPT>true
D/        ( 4221): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 4221): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4221): Index of the first 1 = -1
W/Settings( 4221): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4221): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4221): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4221): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 4221): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/ContextImpl( 4221): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
I/BatteryController( 1113): status:2 level:98 unsupport:false plugged:true
,D/SmartNS_Utility( 4221): [ACC]android_networking:tethering_guard_support=false
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  903): acquireWL(43b83370): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e1be00: PendingIntentRecord{41e14c58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=431623, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43b83370): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43b49680): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=98
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): releaseWL(43b49680): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43b202a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PMS     (  903): releaseWL(43b202a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1113): closing low battery warning: level=98
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:2 level:98 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  903): acquireWL(4310be98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e1be00: PendingIntentRecord{41e14c58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=491624, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(4310be98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43027500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43027500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  903): updateBatteryInfo
D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1113): closing low battery warning: level=98
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
,I/HtcPowerSaver(  903): >> updateStatus
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/HtcPowerSaver(  903): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:2 level:98 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  903): acquireWL(43e74de8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43e74de8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  409): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  903): acquireWL(43e62888): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e1be00: PendingIntentRecord{41e14c58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=551624, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43e62888): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(4380a0a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PowerUI ( 1113): closing low battery warning: level=98
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PMS     (  903): releaseWL(4380a0a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  903): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(431058f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(431058f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(4451b050): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e1be00: PendingIntentRecord{41e14c58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=611624, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(4451b050): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43bd6a38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=98
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PMS     (  903): releaseWL(43bd6a38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  903): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:2 level:98 unsupport:false plugged:true
,E/PNP_UPDATERD(  351): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1241): MSG_CHECK_DELETION >>,
,D/ContactMessageStore( 1241): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1241): sku_id=99
D/ContactMessageStore( 1241): start background delete task...
,D/ContactMessageStore( 1241): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1241): size: 0 , 0
,D/ContactMessageStore( 1241): Background delete complete,
,D/PMS     (  903): acquireWL(43ea6a70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null,
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  903): releaseWL(43ea6a70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=99
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43931540): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e1be00: PendingIntentRecord{41e14c58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=671624, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43931540): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(42f749c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42f749c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(43bc7440): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10026}
,V/AlarmManager(  903): sending alarm PendingIntent{43b1e588: PendingIntentRecord{428b66b0 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=711963, Int=300000
,D/PMS     (  903): releaseWL(43bc7440): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  903): acquireWL(430867b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e1be00: PendingIntentRecord{41e14c58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=731623, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(430867b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(42919558): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42919558): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(43bd0a90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
V/AlarmManager(  903): sending alarm PendingIntent{42070db8: PendingIntentRecord{4269cd10 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=786940, Int=0
,D/ConnectivityService(  903): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  903): sending alarm PendingIntent{42ef98f8: PendingIntentRecord{428df598 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450461723297, Int=1800000
,D/PMS     (  903): acquireWL(4351bad8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2184 10028 null
,D/PMS     (  903): releaseWL(43bd0a90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  903): acquireWL(43b88440): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2184 10028 null
,D/PMS     (  903): releaseWL(4351bad8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 null
D/ConnectivityService(  903): Done.
,D/ConnectivityService(  903): Setting timer for 720seconds,
,I/EventLogService( 2184): Aggregate from 1450461158431 (log), 1450459923229 (data)
,D/PMS     (  903): releaseWL(43b88440): PARTIAL_WAKE_LOCK  Event Log Service 0x1 null
,D/PMS     (  903): acquireWL(43927500): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e1be00: PendingIntentRecord{41e14c58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=791624, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43927500): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(431ebdc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(431ebdc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(43bc0968): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43bc0968): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1562): [EventService] reorderNotification, total:0
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HeadsetPhoneState( 1588): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1113): closing low battery warning: level=100
,D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
V/NotificationService(  903): batLight: Full, plugged
V/LightsService(  903): setLight #8: color=#c8c800
D/qdlights(  903): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  903): setLight #8: color=#c800
D/qdlights(  903): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,W/ContextImpl( 4713): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,D/TetherSettings( 4221): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4221): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4221): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4221): Cust_ConnectToPC   : spcsc>false
D/        ( 4221): Cust_ConnectToPC   : IPT>true
,D/        ( 4221): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4221): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4221): Index of the first 1 = -1
W/ContextImpl( 4221): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/Settings( 4221): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 4221): hasRemovableStorageSlot: true
I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
D/SmartNS_Utility( 4221): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4221): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 4221): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,D/PMS     (  903): acquireWL(43b65a60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e1be00: PendingIntentRecord{41e14c58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=851624, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43b65a60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(4390c908): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(4390c908): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(4305ba98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e1be00: PendingIntentRecord{41e14c58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=911624, Int=0
I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(4305ba98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43c3ec28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43c3ec28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(439ca990): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e1be00: PendingIntentRecord{41e14c58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=971624, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(439ca990): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(4309d748): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(4309d748): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(43b86368): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10028}
V/AlarmManager(  903): sending alarm PendingIntent{43919988: PendingIntentRecord{4211e1d0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1011509, Int=0
D/PMS     (  903): acquireWL(44030218): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1372 10028 null
,V/AlarmManager(  903): sending alarm PendingIntent{42740628: PendingIntentRecord{427383d8 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450461990074, Int=900000
,D/PMS     (  903): releaseWL(44030218): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
,V/AlarmManager(  903): sending alarm PendingIntent{42850ae0: PendingIntentRecord{43e28d78 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450462060717, Int=0
,D/PMS     (  903): acquireWL(43205650): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
,W/ContextImpl( 4713): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  903): releaseWL(43205650): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PowerUsageService( 4713): call getInstance()
D/SmartSyncUtils( 4713): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4713): MY_DEBUG = false
,D/PMS     (  903): acquireWL(43e24b18): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4713 1000 null
,D/PMS     (  903): releaseWL(43b86368): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 4713): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4713): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 2, nStart = 1, nEnd = 2, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4713): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4713): SettingOnTime = 1450486800000, randomSettingOnTime = 1450484278000
,D/SmartSyncScreenOnOffTimeReceiver( 4713): SettingOffTime = 1450483200000, randomSettingOffTime = 1450483609000
,D/SmartSyncScreenOnOffTimeReceiver( 4713): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4713): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4713): bNightModeTurnOffOnce = false
D/PMS     (  903): acquireWL(438fd2b0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1372 10028 null
W/BatSI   (  903): Couldn't get kernel wake lock stats
D/PMS     (  903): releaseWL(43e24b18): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/GCM     ( 1372): Message class mow
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1372/10028)
D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  903): handleInetConditionChange: starting a change hold
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1372/10028)
,D/PMS     (  903): releaseWL(438fd2b0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  903): acquireWL(42905228): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
,D/PMS     (  903): releaseWL(42905228): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,D/ConnectivityService(  903): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  903): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1150): environment dirty rate=14 [144][21][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1150): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1150): nl80211: survey data missing!
E/wpa_supplicant( 1150): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1150): environment dirty rate=0 [0][0][0]
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,D/PMS     (  903): acquireWL(431bf0b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
V/AlarmManager(  903): sending alarm PendingIntent{41e1be00: PendingIntentRecord{41e14c58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1031624, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(431bf0b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43155758): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/HtcPowerSaver(  903): updateBatteryInfo
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): releaseWL(43155758): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(42fb8640): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e1be00: PendingIntentRecord{41e14c58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1091623, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42fb8640): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(42f1a228): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42f1a228): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(42cfe7b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e1be00: PendingIntentRecord{41e14c58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1151624, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42cfe7b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(42ad9290): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42ad9290): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(42949718): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
V/AlarmManager(  903): sending alarm PendingIntent{41e1be00: PendingIntentRecord{41e14c58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1211623, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42949718): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(428d4930): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(428d4930): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  351): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  903): acquireWL(428759f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e1be00: PendingIntentRecord{41e14c58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1271624, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(428759f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(42804da8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): releaseWL(42804da8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(42661220): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e1be00: PendingIntentRecord{41e14c58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1331623, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42661220): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(42600890): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/PowerUI ( 1113): closing low battery warning: level=100
,D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): releaseWL(42600890): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(421523a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e1be00: PendingIntentRecord{41e14c58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1391624, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(421523a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(4206ff40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(4206ff40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(41d5a2e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e1be00: PendingIntentRecord{41e14c58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1451623, Int=0
I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(41d5a2e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(426f0208): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(426f0208): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(424e80c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e1be00: PendingIntentRecord{41e14c58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1511624, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(424e80c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(421f4f90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(421f4f90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(421e00c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e1be00: PendingIntentRecord{41e14c58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1571624, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(421e00c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(427cf500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1113): closing low battery warning: level=100,
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PMS     (  903): releaseWL(427cf500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(42317770): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e1be00: PendingIntentRecord{41e14c58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1631624, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42317770): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(42123b70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
,D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): releaseWL(42123b70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(4244f310): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e1be00: PendingIntentRecord{41e14c58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1691624, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(4244f310): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(430daa20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(430daa20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(428355c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(428355c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,D/PowerUI ( 1113): closing low battery warning: level=100
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(42871a78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e1be00: PendingIntentRecord{41e14c58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1751624, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42871a78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(426e9c48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(426e9c48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  903): updateBatteryInfo
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,D/PMS     (  903): acquireWL(43525440): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e1be00: PendingIntentRecord{41e14c58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1811624, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43525440): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(42982098): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
,D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1113): closing low battery warning: level=100
D/PMS     (  903): releaseWL(42982098): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  351): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  903): acquireWL(44400688): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,D/ConnectivityService(  903): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  903): sending alarm PendingIntent{42070db8: PendingIntentRecord{4269cd10 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1506975, Int=0
,D/ConnectivityService(  903): Done.
,D/ConnectivityService(  903): Setting timer for 720seconds
,I/ProcessStatsService(  903): Prepared write state in 41ms
,V/AlarmManager(  903): sending alarm PendingIntent{425bc668: PendingIntentRecord{4276d808 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1821792, Int=1800000
,I/ProcessStatsService(  903): Pruning old procstats: /data/system/procstats/state-2015-12-18-03-47-30.bin
,I/ProcessStatsService(  903): Prepared write state in 30ms
D/PMS     (  903): acquireWL(426f2418): PARTIAL_WAKE_LOCK  NetworkStats 0x1 903 1000 null
,V/AlarmManager(  903): sending alarm PendingIntent{42740628: PendingIntentRecord{427383d8 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450462890074, Int=900000
,D/PMS     (  903): releaseWL(426f2418): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,W/ContextImpl( 4713): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  903): releaseWL(44400688): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,D/PMS     (  903): acquireWL(43ce8030): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{41e1be00: PendingIntentRecord{41e14c58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1871623, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(43ce8030): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(43bcdbb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(43bcdbb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  903): updateBatteryInfo
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,W/AppWidgetServiceImpl(  903): updateAppWidget failed! callbacks null
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(443975d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(443975d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4830): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4830): ====startRecUseTime====
D/htc.customization.log.level( 4830):  is 
W/CustomizationLogLevel( 4830): Level value is invalid, use default level 2
D/CustomizationManager( 4830):  Read ACC file spent 0.054 (s)
D/CIDMapFileReader( 4830): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4830): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4830): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4830): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4830): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4830): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4830): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4830): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4830): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4830): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4830): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4830): Parsing tag category name = system
I/CustomizationCIDLoader( 4830): Parsing tag category name = application
I/CustomizationCIDLoader( 4830): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4830): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4830): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4830): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4830): Parsing tag category name = Settings
D/CustomizationManager( 4830):  Read CID file spent 0.093 (s)
D/CustomizationManager( 4830):  All configurations done spent 0.093 (s)
W/HtcNativeFlag( 4830): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4830): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4830): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4830): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  903): deletePackageAsUser: pkg=com.test.thalitest, pid=4830, uid=2000 user=0
I/ActivityManager(  903): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
D/Process (  903): killProcessQuiet, pid=4199
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  903): killProcessQuiet, pid=4593
I/ActivityManager(  903): Killing 4199:com.google.android.apps.plus/u0a160 (adj 15): empty for 1801s
I/ActivityManager(  903): Killing 4593:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1801s
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  903): killProcessQuiet, pid=4576
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  903): killProcessQuiet, pid=4560
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  903): killProcessQuiet, pid=4488
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  903): killProcessQuiet, pid=4163
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  903): Killing 4576:com.android.chrome/u0a96 (adj 15): empty for 1801s
I/ActivityManager(  903): Killing 4560:com.google.android.setupwizard/u0a78 (adj 15): empty for 1801s
I/ActivityManager(  903): Killing 4488:com.htc.mms.backupagent/u0a77 (adj 15): empty for 1807s
I/ActivityManager(  903): Killing 4163:com.android.vending/u0a73 (adj 15): empty for 1822s
D/Process (  903): killProcessQuiet, pid=4403
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
W/asset   (  903): Copying FileAsset 0x6c6ba8e8 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  903): Killing 4403:com.android.settings:remote/1000 (adj 15): empty for 1835s
I/ActivityManager(  903): Recipient 4576
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 4593
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 4488
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 4403
I/ActivityManager(  903): Recipient 4560
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 4199
W/PackageSettings(  903): Skipping PackageSetting{42516798 com.example.hello/10356} due to missing metadata
I/ActivityManager(  903): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
I/ActivityManager(  903): Recipient 4163
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/acms    ( 1857): Unregistering com.test.thalitest
E/acms    ( 1857): Could not unregister removed application com.test.thalitest
D/DotMatrix( 1562): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1562): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver replacing:false
D/PMS     (  903): acquireWL(44648a58): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1447 10028 null
W/GeofencerStateMachine( 1447): Ignoring removeGeofence because network location is disabled.
I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/DotMatrix( 1562): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/AccTypeManager( 1332): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1332): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  903): releaseWL(44648a58): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/Launcher( 1269): Deferring update until onResume
D/Launcher( 1269): waitUntilResume // bindAppsRemoved
D/VoicemailCleanupService( 1284): Cleaning up data for package: com.test.thalitest
D/AccTypeManager( 1332): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
W/SystemReader( 1256): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "sms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "smsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
D/PackageBroadcastService( 2184): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mms"
I/ActivityManager(  903): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4844 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mmsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
E/ExternalAccountType( 1332): Unsupported attribute readOnly
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "sms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/InputMethodManagerService(  903): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "smsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/ActivityManager(  903): Delaying start of: ServiceRecord{43b81fa0 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mms"
I/MultiDex( 4844): install
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/ActivityManager(  903): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4859 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/MultiDex( 4844): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mmsto"
I/MultiDex( 4844): loading existing secondary dex files
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/MultiDex( 4844): load found 1 secondary dex files
I/MultiDex( 4844): install done
D/PhoneApp( 1241): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/PeopleContactsSync( 2184): CP2 sync disabled
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2184, uid=10028, userID:0
I/Icing   ( 2184): doRemovePackageData com.test.thalitest
D/PMS     (  903): acquireWL(422246e8): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10028 null
I/ProviderInstaller( 4844): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
D/PMS     (  903): releaseWL(422246e8): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/MultiDex( 4859): install
I/ActivityManager(  903): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4859): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4859): loading existing secondary dex files
I/MultiDex( 4859): load found 1 secondary dex files
I/MultiDex( 4859): install done
I/ProviderInstaller( 4859): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  903): Resuming delayed broadcast
I/[PluginManager]RegisterService( 1387): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1387): handle notify Blinkfeed plugin client changed
I/ActivityManager(  903): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4880 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
D/Process (  903): killProcessQuiet, pid=4509
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4509:com.google.android.music:main/u0a154 (adj 15): empty for 1801s
I/ActivityManager(  903): Recipient 4509
D/MediaRouterService(  903): Client com.google.android.music (pid 4509): Died!
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4880, uid=10073, userID:0
D/Finsky  ( 4880): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  903): getAllNetworkInfo called by com.android.vending (4880/10073)
E/SQLiteLog( 4844): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
D/ConnectivityService(  903): getAllNetworkInfo called by com.android.vending (4880/10073)
E/SQLiteDBG( 4844): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca9c668
E/DriveAsyncService( 4844): disk I/O error (code 3850)
E/DriveAsyncService( 4844): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4844): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4844): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 4844): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4844): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4844): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 4844): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 4844): 	at ctj.c(SourceFile:904)
E/DriveAsyncService( 4844): 	at cva.h(SourceFile:1427)
E/DriveAsyncService( 4844): 	at cgv.a(SourceFile:15)
E/DriveAsyncService( 4844): 	at bzz.onHandleIntent(SourceFile:60)
E/DriveAsyncService( 4844): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/DriveAsyncService( 4844): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DriveAsyncService( 4844): 	at android.os.Looper.loop(Looper.java:157)
E/DriveAsyncService( 4844): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/PackageManager(  903): Unable to load service info ResolveInfo{43049008 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
D/Finsky  ( 4880): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
D/PMS     (  903): acquireWL(43bda908): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10028}
V/AlarmManager(  903): sending alarm PendingIntent{428a2f58: PendingIntentRecord{4211e1d0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=1912466, Int=0
E/SQLiteLog( 4844): (3850) statement aborts at 5: [DELETE FROM ContentFileDeletionLock24] disk I/O error
E/SQLiteDBG( 4844): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca9c668
W/Settings( 4880): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 4880): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/DocListDatabase( 4844): Failed to delete from ContentFileDeletionLock24
E/DocListDatabase( 4844): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 4844): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 4844): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/DocListDatabase( 4844): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 4844): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 4844): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/DocListDatabase( 4844): 	at ctj.a(SourceFile:859)
E/DocListDatabase( 4844): 	at cva.k(SourceFile:1117)
E/DocListDatabase( 4844): 	at chr.<init>(SourceFile:45)
E/DocListDatabase( 4844): 	at chr.a(SourceFile:75)
E/DocListDatabase( 4844): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/DocListDatabase( 4844): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/DocListDatabase( 4844): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/DocListDatabase( 4844): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/DocListDatabase( 4844): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DocListDatabase( 4844): 	at android.os.Looper.loop(Looper.java:157)
E/DocListDatabase( 4844): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/DocListDatabase( 4844): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DocListDatabase( 4844): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DocListDatabase( 4844): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/DocListDatabase( 4844): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/DocListDatabase( 4844): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 4844): threadid=1: thread exiting with uncaught exception (group=0x41934e30)
E/SQLiteDatabase( 4880): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 4880): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4880): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4880): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4880): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4880): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4880): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4880): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4880): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4880): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4880): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4880): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4880): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4880): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4880): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4880): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/SQLiteDatabase( 4880): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/SQLiteDatabase( 4880): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/SQLiteDatabase( 4880): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 4880): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 4880): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4880): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4880): threadid=25: thread exiting with uncaught exception (group=0x41934e30)
E/ActivityManager(  903): App crashed! Process: com.google.android.gms.drive
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4880, uid=10073, userID:0
E/AndroidRuntime( 4844): FATAL EXCEPTION: main
E/AndroidRuntime( 4844): Process: com.google.android.gms.drive, PID: 4844
E/AndroidRuntime( 4844): java.lang.RuntimeException: Unable to create service com.google.android.gms.drive.api.ApiService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4844): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2883)
E/AndroidRuntime( 4844): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/AndroidRuntime( 4844): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/AndroidRuntime( 4844): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4844): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4844): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4844): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4844): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4844): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4844): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4844): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4844): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4844): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4844): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 4844): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4844): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4844): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 4844): 	at ctj.a(SourceFile:859)
E/AndroidRuntime( 4844): 	at cva.k(SourceFile:1117)
E/AndroidRuntime( 4844): 	at chr.<init>(SourceFile:45)
E/AndroidRuntime( 4844): 	at chr.a(SourceFile:75)
E/AndroidRuntime( 4844): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/AndroidRuntime( 4844): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/AndroidRuntime( 4844): 	... 10 more
E/AndroidRuntime( 4880): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime( 4880): Process: com.android.vending, PID: 4880
E/AndroidRuntime( 4880): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4880): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4880): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4880): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4880): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4880): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4880): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4880): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4880): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4880): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4880): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4880): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4880): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4880): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4880): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/AndroidRuntime( 4880): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/AndroidRuntime( 4880): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/AndroidRuntime( 4880): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4880): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4880): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4880): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  903): App crashed! Process: com.android.vending
D/Process ( 4844): killProcess, pid=4844
D/Process ( 4844): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  903): Can't write: system_app_crash
E/DropBoxManagerService(  903): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
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
D/Prism.PackageStateRece_( 1269): action: android.intent.action.PACKAGE_REMOVED
D/Process ( 4880): killProcess, pid=4880
D/Process ( 4880): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.finsky.FinskyApp$CrashHandler.uncaughtException:284 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  903): Can't write: system_app_crash
E/DropBoxManagerService(  903): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
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
I/IcingCorporaProvider( 2905): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  903): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4918 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/ActivityManager(  903): Recipient 4844
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Process com.google.android.gms.drive (pid 4844) has died.
W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.gms/.drive.api.ApiService in 1000ms
I/ActivityManager(  903): Recipient 4880
I/ActivityManager(  903): Process com.android.vending (pid 4880) has died.
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/SQLiteLog( 2905): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2905): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x64623ef8
W/dalvikvm( 2905): threadid=14: thread exiting with uncaught exception (group=0x41934e30)
E/AndroidRuntime( 2905): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2905): Process: com.google.android.googlequicksearchbox:search, PID: 2905
E/AndroidRuntime( 2905): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2905): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2905): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2905): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2905): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2905): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2905): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2905): 	at cid.d(PG:186)
E/AndroidRuntime( 2905): 	at clo.g(PG:594)
E/AndroidRuntime( 2905): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2905): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2905): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2905): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2905): 	at clr.tL(PG:827)
E/AndroidRuntime( 2905): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2905): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2905): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2905): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2905): 	at android.os.HandlerThread.run(HandlerThread.java:61)
F/ProcessStats(  903): Starting service ServiceState{425a3880 com.google.android.gms.drive.api.ApiService pkg=com.google.android.gms proc=425a3880} without owner
D/ErrorReport(  903): HtcErrorReportManager Begin---add error logs to dropbox
E/ErrorReport(  903): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  903): java.io.FileNotFoundException: /data/misc/SYSTEM_WTF@1450462962103.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  903): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  903): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  903): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:540)
E/ErrorReport(  903): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:227)
E/ErrorReport(  903): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10800)
E/ErrorReport(  903): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10685)
E/ErrorReport(  903): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:379)
E/ErrorReport(  903): 	at android.util.Log$1.onTerribleFailure(Log.java:104)
E/ErrorReport(  903): 	at android.util.Log.wtf(Log.java:293)
E/ErrorReport(  903): 	at android.util.Slog.wtf(Slog.java:82)
E/ErrorReport(  903): 	at com.android.internal.app.ProcessStats$ServiceState.setStarted(ProcessStats.java:3113)
E/ErrorReport(  903): 	at com.android.server.am.ProcessStatsService.setMemFactorLocked(ProcessStatsService.java:151)
E/ErrorReport(  903): 	at com.android.server.am.ActivityManagerService.updateOomAdjLocked(ActivityManagerService.java:17046)
E/ErrorReport(  903): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:4131)
E/ErrorReport(  903): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1146)
E/ErrorReport(  903): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
E/ErrorReport(  903): 	at dalvik.system.NativeStart.run(Native Method)
E/ErrorReport(  903): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  903): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  903): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  903): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  903): 	... 18 more
I/TrimMemoryManager( 1269): [trimMemory] 5
E/ActivityManager(  903): App crashed! Process: com.google.android.googlequicksearchbox:search
F/ProcessStats(  903): Starting service ServiceState{425a3880 com.google.android.gms.drive.api.ApiService pkg=com.google.android.gms proc=425a3880} without owner
D/ErrorReport(  903): HtcErrorReportManager Begin---add error logs to dropbox
E/ErrorReport(  903): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  903): java.io.FileNotFoundException: /data/misc/SYSTEM_WTF@1450462962147.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  903): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  903): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  903): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:540)
E/ErrorReport(  903): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:227)
E/ErrorReport(  903): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10800)
E/ErrorReport(  903): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10685)
E/ErrorReport(  903): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:379)
E/ErrorReport(  903): 	at android.util.Log$1.onTerribleFailure(Log.java:104)
E/ErrorReport(  903): 	at android.util.Log.wtf(Log.java:293)
E/ErrorReport(  903): 	at android.util.Slog.wtf(Slog.java:82)
E/ErrorReport(  903): 	at com.android.internal.app.ProcessStats$ServiceState.setStarted(ProcessStats.java:3113)
E/ErrorReport(  903): 	at com.android.server.am.ProcessStatsService.setMemFactorLocked(ProcessStatsService.java:151)
E/ErrorReport(  903): 	at com.android.server.am.ActivityManagerService.updateOomAdjLocked(ActivityManagerService.java:17046)
E/ErrorReport(  903): 	at com.android.server.am.ActivityManagerService.updateOomAdjLocked(ActivityManagerService.java:16827)
E/ErrorReport(  903): 	at com.android.server.am.ActivityManagerService.updateOomAdjLocked(ActivityManagerService.java:16804)
E/ErrorReport(  903): 	at com.android.server.am.ActiveServices.serviceDoneExecutingLocked(ActiveServices.java:1897)
E/ErrorReport(  903): 	at com.android.server.am.ActiveServices.serviceDoneExecutingLocked(ActiveServices.java:1846)
E/ErrorReport(  903): 	at com.android.server.am.ActivityManagerService.serviceDoneExecuting(ActivityManagerService.java:13937)
E/ErrorReport(  903): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:919)
E/ErrorReport(  903): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2330)
E/ErrorReport(  903): 	at android.os.Binder.execTransact(Binder.java:412)
E/ErrorReport(  903): 	at dalvik.system.NativeStart.run(Native Method)
E/ErrorReport(  903): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  903): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  903): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  903): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  903): 	... 23 more
D/Process ( 2905): killProcess, pid=2905
E/DropBoxManagerService(  903): Can't write: system_app_crash
E/DropBoxManagerService(  903): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 2905): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
D/RemoteDisplayProvider(  903): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  903): start
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 2905
D/WifiService(  903): Client connection lost with reason: 4
I/ActivityManager(  903): Process com.google.android.googlequicksearchbox:search (pid 2905) has died.
W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 10721ms
D/MediaRouterService(  903): Client com.google.android.googlequicksearchbox (pid 2905): Died!
W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 10720ms
E/SQLiteDatabase( 4918): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4918): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4918): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4918): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4918): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4918): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4918): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4918): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4918): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4918): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4918): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4918): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4918): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4918): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4918): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4918): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4918): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4918): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4918): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4918): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4918): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4918): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4918): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4918): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4918): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4918): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4918): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4918): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4918): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4918): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4918): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4918): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4918): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4918): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4918): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4918): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4918): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4918): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4918): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4918): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4918): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4918): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4918): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4918): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4918): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4918): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4918): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4918): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4918): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4918): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4918): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4918): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4918): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4918): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4918): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4918): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4918): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4918): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4918): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4918): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4918): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4918): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4918): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4918): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4918): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4918): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4918): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4918): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4918): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4918): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4918): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4918): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4918): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4918): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4918): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4918): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4918): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4918): threadid=11: thread exiting with uncaught exception (group=0x41934e30)
E/ActivityManager(  903): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4918): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4918): Process: com.google.android.apps.docs, PID: 4918
E/AndroidRuntime( 4918): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4918): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4918): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4918): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4918): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4918): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4918): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4918): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4918): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4918): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4918): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4918): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4918): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4918): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4918): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4918): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4918): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4918): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4918): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  903): Can't write: system_app_crash
E/DropBoxManagerService(  903): java.io.FileNotFoundException: /data/system/dropbox/drop144.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 4918): killProcess, pid=4918
D/Process ( 4918): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  903): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4934 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  903): Recipient 4918
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Process com.google.android.apps.docs (pid 4918) has died.
W/ContextImpl( 4934): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 4934): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4934): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4934): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4934): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4934): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4934): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4934): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4934): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4934): threadid=10: thread exiting with uncaught exception (group=0x41934e30)
E/ActivityManager(  903): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4934): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4934): Process: com.android.keychain, PID: 4934
E/AndroidRuntime( 4934): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4934): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4934): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4934): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4934): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4934): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4934): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4934): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4934): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4934): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4934): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4934): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4934): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4934): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4934): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4934): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4934): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4934): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4934): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  903): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4947 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/ErrorReport(  903): HtcErrorReportManager Begin---add error logs to dropbox

```
