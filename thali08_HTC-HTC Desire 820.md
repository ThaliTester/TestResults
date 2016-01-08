#### Test 54970261d953416_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
E/cutils-trace( 4472): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4472): ====startRecUseTime====
D/htc.customization.log.level( 4472):  is 
W/CustomizationLogLevel( 4472): Level value is invalid, use default level 2
D/CustomizationManager( 4472):  Read ACC file spent 0.063 (s)
D/CIDMapFileReader( 4472): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4472): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4472): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4472): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4472): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4472): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4472): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4472): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4472): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4472): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4472): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4472): Parsing tag category name = system
I/CustomizationCIDLoader( 4472): Parsing tag category name = application
I/CustomizationCIDLoader( 4472): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4472): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4472): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4472): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4472): Parsing tag category name = Settings
D/CustomizationManager( 4472):  Read CID file spent 0.102 (s)
D/CustomizationManager( 4472):  All configurations done spent 0.103 (s)
W/HtcNativeFlag( 4472): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4472): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4472): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4472): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
W/CpuWake (  907): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  907): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4472
D/PMS     (  907): acquireHCC(42916700): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 907 1000 null
D/PMS     (  907): acquireHCC(41e52b28): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 907 1000 null
W/asset   (  907): Copying FileAsset 0x638e8d28 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  907): @test_code: getHtcIntentFlag: 0 obj: 1139343008
I/FeedHostManager( 1274): [onPause]
I/FeedProviderManager( 1274): onPause
I/FeedHostManager( 1274): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41f34a58
I/SocialFeedProvider( 1274): +onPause
I/SocialFeedProvider( 1274): -onPause
D/PMS     (  907): acquireWL(4305a228): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
I/ActivityManager(  907): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4483 uid=10348 gids={50348, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1274): [trimMemory] 20
W/asset   ( 4483): Copying FileAsset 0x5c6ec540 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4483): Binding Chromium to main looper Looper (main, tid 1) {41e486b0}
I/LibraryLoader( 4483): Expected native library version number "",actual native library version number ""
I/chromium( 4483): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4483): Initializing chromium process, renderers=0
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  907): java.lang.Throwable: stack dump
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42886e48:true
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
D/PMS     (  907): acquireWL(4207a168): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  907): acquireWL(42950a18): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  907): releaseWL(4207a168): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4483): 1105584360: getState(). Returning 12
I/Adreno-EGL( 4483): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4483): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4483): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4483): Local Branch: 
I/Adreno-EGL( 4483): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4483): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4483):                  aa63bbd948f41d15fc72f585e
W/chromium( 4483): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4483): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4483): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4483): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4483): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4483): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4483): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4483): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4483): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4483): CordovaWebView is running on device made by: HTC
,W/AwContents( 4483): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  907): Disable input method client, pid=1274
W/ResourceType( 4483): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4483): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41e8f798, mServedView=org.apache.cordova.engine.SystemWebView{41e55400 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/ActivityManager(  907): Displayed com.test.thalitest/.MainActivity: +289ms
W/AwContents( 4483): nativeOnDraw failed; clearing to background color.
W/XT9_C   ( 1212): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1212): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1212): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1212): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  907): Enable input method client, pid=4483
D/PMS     (  907): releaseWL(4305a228): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/JsMessageQueue( 4483): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 4483): JniHelper::setJavaVM(0x41a04010), pthread_self() = 1662901344
D/JX-Cordova( 4483): jxcore cordova android initializing
I/ActivityManager(  907): Waited long enough for: ServiceRecord{4447ebb0 u0 com.htc.htclocationservice/.AutoSettingService}
I/SensorManager(  907): mEventCount = 1050
I/dalvikvm-heap( 4483): Grow heap (frag case) to 11.548MB for 63974-byte allocation
,I/dalvikvm-heap( 4483): Grow heap (frag case) to 11.603MB for 95956-byte allocation
,I/dalvikvm-heap( 4483): Grow heap (frag case) to 11.681MB for 143930-byte allocation
,I/dalvikvm-heap( 4483): Grow heap (frag case) to 11.793MB for 215890-byte allocation
,I/dalvikvm-heap( 4483): Grow heap (frag case) to 11.958MB for 323830-byte allocation
,I/dalvikvm-heap( 4483): Grow heap (frag case) to 12.625MB for 728606-byte allocation
,I/dalvikvm-heap( 4483): Grow heap (frag case) to 13.222MB for 1092904-byte allocation
,I/dalvikvm-heap( 4483): Grow heap (frag case) to 14.136MB for 1639352-byte allocation
,I/dalvikvm-heap( 4483): Grow heap (frag case) to 15.482MB for 2459024-byte allocation
,W/CpuWake (  907): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  907): <<release mCpuPerf_Freq wakelock
D/PMS     (  907): releaseHCC(42916700): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  907): releaseHCC(41e52b28): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4483): Grow heap (frag case) to 17.575MB for 3688532-byte allocation
,I/ActivityManager(  907): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4526 uid=10077 gids={50077}
D/PMS     (  907): acquireWL(43fafce8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10077}
,V/AlarmManager(  907): sending alarm PendingIntent{42849530: PendingIntentRecord{4286e1e8 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1452280481237, Int=60000
,W/jxcore-log( 4483): Initializing JXcore engine
,W/jxcore-log( 4483): JXcore engine is ready
D/PMS     (  907): releaseWL(43fafce8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4526): SMSBackupAgentService started
,D/SMSBackup( 4526): Checking restore status
D/SMSBackup( 4526): Restore complete
,D/SMSBackup( 4526): cancelCheckAlarm
,W/jxcore-log( 4483): Starting JXcore engine
,D/SMSBackup( 4526): SMSBackupAgentService completed: completed in 0.0 seconds
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,D/Process (  907): killProcessQuiet, pid=3060
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  907): Killing 3060:com.android.defcontainer/u0a19 (adj 15): empty #17
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 144
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,I/ActivityManager(  907): Recipient 3060
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/jxcore-log( 4483): Platform android
W/jxcore-log( 4483): 
,W/jxcore-log( 4483): Process ARCH arm
W/jxcore-log( 4483): 
,D/WIFI_ICON( 1119): WifiActivity: 0
,D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/jxcore-log( 4483): JXcore Cordova bridge is ready!
I/jxcore-log( 4483): 
,W/jxcore-log( 4483): JXcore engine is started
,D/PMS     (  907): releaseWL(42950a18): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/chromium( 4483): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4483): Toggling radios to true
I/jxcore-log( 4483): 
,D/BluetoothAdapter( 4483): enable(): BT is already enabled..!
,D/WifiManager( 4483): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10348
,W/HtcDLNAServiceManager(  907): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  907): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  907): Settings:Agentvalue: 2
W/Settings:Agent(  907): >> traceCallingStack()
W/Settings:Agent(  907): Process.myPid(): 907
W/Settings:Agent(  907): Process.myTid(): 1470
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
,D/WifiManager( 4483): disconnect: Base Package Name=com.test.thalitest, uid=10348
D/WifiNative-wlan0(  907): doBoolean: DISCONNECT
,D/WifiManager( 4483): reconnect: Base Package Name=com.test.thalitest, uid=10348
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): TDLS: Tear down peers
,I/wpa_supplicant( 1173): wpa_driver_nl80211_disconnect(reason_code=3),
,I/jxcore-log( 4483): Radios toggled,
I/jxcore-log( 4483): 
D/WifiService(  907): New client listening to asynchronous messages
D/WifiService(  907): setWifiEnabled: true pid=4483, uid=10348
E/WifiService(  907): Invoking mWifiStateMachine.setWifiEnabled,
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
D/wpa_supplicant( 1173): TDLS: Remove peers on disassociation
,D/wpa_supplicant( 1173): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  907): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  907): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1173): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1173): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1173): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1173): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1173): send_and_recv error -67 - cmd 12
,D/wpa_supplicant( 1173): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1173): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1173): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb856cbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1173):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1173): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1173): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1173): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1173): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1173): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1173): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1173): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1173): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1173): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1173): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1173): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1173): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1173): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1173): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1173): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1173): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1173): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1173): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1173): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1173): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1173): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1173): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1173): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1173): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1173): nl80211: Event message available
D/wpa_supplicant( 1173): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1173): nl80211: Ignore disconnect event triggered during reassociation
,D/WifiNative-wlan0(  907):    returned true
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  907): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiPerfLock(  907): release()
D/WifiStateMachine(  907): PerfLock released for exiting ConnectedState
,D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
,D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
,D/Tethering(  907): interfaceStatusChanged wlan0, false
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1173): Power_Mode_Type mode = 0
I/wpa_supplicant( 1173): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 61
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/ConnectivityService(  907): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
,D/PMS     (  907): acquireWL(442ca2d8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 907 1000 null
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/DhcpStateMachine(  907): [RunningState] Stop DHCP
D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=21647 mDataStallAlarmIntent=PendingIntent{4279ec10: PendingIntentRecord{42903760 android broadcastIntent}}
I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
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
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): Enter handleNetworkDisconnect
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1173): Power_Mode_Type mode = 0
I/wpa_supplicant( 1173): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 61
,D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  907):    returned true
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1883/10178)
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 4242): >>>>>WISPrService start isConnected = false<<<<<
D/UsbnetStateTracker(  907): isAvailable+-
D/UsbnetStateTracker(  907): reconnect
,D/UsbnetStateTracker(  907): isAvailable+-
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  907): default: reconnect()
D/MDST    (  907): default: setTeardownRequested(false)
D/MDST    (  907): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  907): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  907): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WISPrService( 4242): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiStateMachine(  907): Exit handleNetworkDisconnect
,D/WISPrService( 4242): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4242): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiService(  907): New client listening to asynchronous messages
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1883/10178)
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  907): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
,D/ConnectivityService(  907): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] entry_id:5   entry:0xb7a428e0  removed 
D/libc    (  363): [NET] entry_id:6   entry:0xb7a43020  removed 
D/libc    (  363): [NET] entry_id:4   entry:0xb7a470e0  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb7a47248  removed 
D/libc    (  363): [NET] entry_id:7   entry:0xb7a47190  removed 
D/libc    (  363): [NET] entry_id:3   entry:0xb7a46fd8  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb7a47410  removed 
,D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/ConnectivityService(  907): resetConnections(wlan0, 3)
D/PMS     (  907): acquireWL(43f51e90): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1371 10028 null
D/ConnectivityService(  907): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:0
D/WifiStateMachine(  907): startScan Pid: 907 Uid 1000
,I//system/bin/ip(  363): RTNETLINK answers: No such process
D/WifiNative-wlan0(  907): doBoolean: SCAN
I/logwrapper(  363): /system/bin/ip terminated by exit(2)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1173): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  907):    returned false
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  907): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/PMS     (  907): acquireWL(428b9a78): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/PMS     (  907): acquireWL(431272d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10028 null
D/PMS     (  907): releaseWL(431272d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/BatSI   (  907): WIFI scan started for: 650a0300 uid:1000
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1371/10028)
D/ConnectivityService(  907): reportInetCondition for net -1, percentage: 0 by  (1371/10028)
D/PMS     (  907): releaseWL(43f51e90): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1371/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1371/10028)
D/ConnectivityService(  907): mActiveDefaultNetwork: -1
D/ConnectivityService(  907): handleInetConditionChange: no active default network - ignore
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:1
D/PMS     (  907): releaseWL(428b9a78): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  907): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  907): bSetPropertyMultiRAB:false
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
D/CaptivePortalTracker(  907): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/CaptivePortalTracker(  907): NoActiveNetworkState
D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
D/GpsLocationProvider(  907): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: false
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1918/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4367/10100)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/PMS     (  907): acquireWL(43118b60): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
,D/PMS     (  907): releaseWL(43118b60): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/Tethering(  907): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  907): ipv4Default null
,I/Tethering(  907): No IPv4 upstream interface, giving up.
,D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
,I/ConnectivityHelper( 1274): [onReceive] WIFI(1): DISCONNECTED
I/NetworkMonitor( 3969): type=WIFI subType= reason=null isConnected=false
,D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4367/10100)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (3969/10154)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1274/10075)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1430/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1883/10178)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (2449/10021)
,I/ActivityManager(  907): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4547 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4547): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4547): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4547): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4547): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4547): Preparing secondary program dexes.,
V/DexLibLoader( 4547): Loaded 4 raw lines of metadata.
V/DexLibLoader( 4547): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4547): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4547): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4547): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4547): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4547): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4547): Dex already copied
D/OdexVerifier( 4547): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4547): Creating class loader
,V/DexLibLoader( 4547): Finished creating class loader
V/DexLibLoader( 4547): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4547): Dex already copied
D/OdexVerifier( 4547): Odex verification is skipped. OS version not supported.
V/DexLibLoader( 4547): Creating class loader
V/DexLibLoader( 4547): Finished creating class loader
V/DexLibLoader( 4547): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4547): Dex already copied
D/OdexVerifier( 4547): Odex verification is skipped. OS version not supported.
V/DexLibLoader( 4547): Creating class loader
V/DexLibLoader( 4547): Finished creating class loader
V/DexLibLoader( 4547): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4547): Dex already copied
D/OdexVerifier( 4547): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4547): Creating class loader
,V/DexLibLoader( 4547): Finished creating class loader
,V/DexLibLoader( 4547): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4547): DexLibLoader.ensureDexLoaded took 18 ms
,W/dalvikvm( 4547): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4547): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4547): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4547): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4547): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4547): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4547): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/PMS     (  907): acquireWL(429447f8): PARTIAL_WAKE_LOCK  Icing 0x1 2229 10028 null
,W/dalvikvm( 4547): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1173): nl80211: Event message available
D/wpa_supplicant( 1173): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1173): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1173): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-83
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 06:7c:34:38:27:cc freq=2462 level=-90
D/wpa_supplicant( 1173): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1173): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1173): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1173): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1173): Add randomness: count=10 entropy=4
D/wpa_supplicant( 1173): Add randomness: count=11 entropy=5
D/wpa_supplicant( 1173): Add randomness: count=12 entropy=6
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): Selecting BSS from priority group 1
I/wpa_supplicant( 1173): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1173): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1173): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1173): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1173): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1173):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1173):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
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
I/wpa_supplicant( 1173):, selected network = 2
D/wpa_supplicant( 1173): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb856e4e8  current_ssid=0x0
D/wpa_supplicant( 1173): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1173): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1173): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1173): check if in concurrent case
I/wpa_supplicant( 1173): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1173): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1173): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1173): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1173): RSN: PMKSA cache search - network_ctx=0xb856e4e8 try_opportunistic=0
D/wpa_supplicant( 1173): RSN: Search for BSSID c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 1173): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1173): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1173): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1173): netlink: Operstate: linkmode=-1, operstate=5
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
,D/wpa_supplicant( 1173): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1173): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 6
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,D/wpa_supplicant( 1173): nl80211: Unsubscribe mgmt frames handle 0xb856d718 (mode change)
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/wpa_supplicant( 1173): nl80211: Subscribe to mgmt frames with non-AP handle 0xb856d718
D/wpa_supplicant( 1173): nl80211: Register frame type=0xd0 nl_handle=0xb856d718
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 58
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/wpa_supplicant( 1173): nl80211: Register frame type=0xd0 nl_handle=0xb856d718
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1173): nl80211: Register frame type=0xd0 nl_handle=0xb856d718
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1173): nl80211: Register frame type=0xd0 nl_handle=0xb856d718
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1173): nl80211: Register frame type=0xd0 nl_handle=0xb856d718
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1173): nl80211: Register frame type=0xd0 nl_handle=0xb856d718
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1173): nl80211: Register frame type=0xd0 nl_handle=0xb856d718
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1173): nl80211: Register frame type=0xd0 nl_handle=0xb856d718
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1173): nl80211: Register frame type=0xd0 nl_handle=0xb856d718
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1173): nl80211: Register frame type=0xd0 nl_handle=0xb856d718
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1173): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1173):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1173):   * freq=2412
D/wpa_supplicant( 1173):   * Auth Type 0
D/wpa_supplicant( 1173):   * WPA Versions 0x2
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
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1173): reply (922) for get BSS: id=0
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1173): freq=5220
I/wpa_supplicant( 1173): level=-47
I/wpa_supplicant( 1173): tsf=0000000109421345
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG7005g
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=1
I/wpa_supplicant( 1173): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-55
I/wpa_supplicant( 1173): tsf=0000000109421357
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1173): ssid=01ABC
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=2
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-55
I/wpa_supplicant( 1173): tsf=0000000109421361
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG700
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=3
I/wpa_supplicant( 1173): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-78
I/wpa_supplicant( 1173): tsf=0000000109421365
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=Gonzos
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=4
I/wpa_supplicant( 1173): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-83
I/wpa_supplicant( 1173): tsf=0000000109421373
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC5999698
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=5
I/wpa_supplicant( 1173): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-84
I/wpa_supplicant( 1173): tsf=0000000109421369
I/wpa_supplicant( 1173): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=UPC Wi-Free
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=6
I/wpa_supplicant( 1173): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1173): freq=2462
I/wpa_supplicant( 1173): level=-90
I/wpa_supplicant( 1173): tsf=0000000109421385
I/wpa_supplicant( 1173): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=UPC Wi-Free
I/wpa_supplicant( 1173): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 109421345, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 109421357, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 109421361, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 109421365, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -83, frequency: 2437, timestamp: 109421373, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -84, frequency: 2437, timestamp: 109421369, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 6: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 109421385, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 7 to mScanResults
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (7) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/BatSI   (  907): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/dalvikvm( 4547): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/PMS     (  907): releaseWL(429447f8): PARTIAL_WAKE_LOCK  Icing 0x1 null
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
D/wpa_supplicant( 1173): Add randomness: count=13 entropy=7
I/wpa_supplicant( 1173): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1173): TDLS: Remove peers on association
D/wpa_supplicant( 1173): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1173): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1173): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1173): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1173): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
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
I/wpa_supplicant( 1173): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1173): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1173): Get randomness: len=32 entropy=8
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  907): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  907): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  907): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  907): handleAssociatedWit,hEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  907): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  907): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  907): Enter handleAssociatedWithEvent
D/WifiStateMachine(  907): Associated
D/WifiStateMachine(  907): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  907): Exit handleAssociatedWithEvent
D/WifiStateMachine(  907): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/Tethering(  907): [isWifi] getHotspotEnabled: false
I/wpa_supplicant( 1173): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1173): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb856d9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
D/wpa_supplicant( 1173):    addr=c0:ff:d4:d3:aa:48
D/Tethering(  907): interfaceStatusChanged wlan0, true
D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1173): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1173): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1173): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6ef4b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1173):    broadcast key
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1173): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1173): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1173): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1173): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  907): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1173): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1173): netlink: Operstate: linkmode=-1, operstate=6
D/WifiStateMachine(  907): This record is existed, only update it...
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
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1173): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1173): EAPOL authentication completed successfully
I/wpa_supplicant( 1173): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1173): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1173): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1173): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
D/Tethering(  907): interfaceStatusChanged wlan0, true
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  907): updateConnectedAP...
E/FbInjectorInitializer( 4547): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
D/WifiStateMachine(  907): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  907): This record is existed, only update it...
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  907): updateConnectedAP...
I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WISPrService( 4242): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4242): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): mActiveDefaultNetwork: -1
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
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
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 1
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
D/WifiNative-wlan0(  907):    returned null
D/WifiStateMachine(  907): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  907): acquireWL(43f42468): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 907 1000 null
D/WifiStateMachine(  907): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  907): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42694fe8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42694fe8 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1119): receive.wifiConnect:false wifiAPname:null elapse:0
,W/fb4a(:<default>):StaticBindingVerifier( 4547): Verify
,D/WifiService(  907): New client listening to asynchronous messages
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4547/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4547): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4547): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4547): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  907): killProcessQuiet, pid=3687
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 3687:com.htc.task/u0a70 (adj 15): empty #17
,D/PMS     (  907): acquireWL(428b6818): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2229 10028 null
,D/PMS     (  907): acquireWL(42db6818): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2229 10028 null
,D/PMS     (  907): releaseWL(428b6818): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1371): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2229/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1371/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1371/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1371/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2229/10028)
,D/AutoSetting( 1407): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  907): releaseWL(42db6818): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,I/ActivityManager(  907): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4580 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1407/10053)
,D/AutoSetting( 1407): Util - no network available!
,D/AutoSetting( 1407): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1407): service - mHandler: cancel location update
,D/AutoSetting( 1407): service -           changes count: 0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1407/10053)
,I/ActivityManager(  907): Recipient 3687
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/fb4a(:<default>):UserScope( 4547): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4580): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4580): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4580): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4580): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4547): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4547): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/Process (  907): killProcessQuiet, pid=3929
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4594 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
I/ActivityManager(  907): Killing 3929:com.htc.mediamanager/u0a32 (adj 15): empty #17
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4580/10078)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4580/10078)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4580/10078)
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4547): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,D/Process (  907): killProcessQuiet, pid=4072
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4611 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
I/ActivityManager(  907): Killing 4072:com.google.android.gm/u0a107 (adj 15): empty #17
,E/dalvikvm( 4547): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4547): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,E/dalvikvm( 4547): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4547): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,E/dalvikvm( 4547): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4547): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,E/dalvikvm( 4547): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4547): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4547): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
,E/dalvikvm( 4547): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4547): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4547): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4547): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4547): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4547): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4547): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4547): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4547): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
I/ActivityManager(  907): Recipient 3929
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4547): Grow heap (frag case) to 9.918MB for 39954-byte allocation
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4611): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4611): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/GAV2    ( 4611): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4611): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4611): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4547): Grow heap (frag case) to 9.995MB for 79892-byte allocation
,I/dalvikvm-heap( 4547): Grow heap (frag case) to 10.072MB for 84664-byte allocation
I/ActivityManager(  907): Recipient 4072
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4547): Grow heap (frag case) to 10.092MB for 28144-byte allocation
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4611/10151)
,V/WebViewChromiumFactoryProvider( 4611): Binding Chromium to main looper Looper (main, tid 1) {41e4d2b8}
,I/LibraryLoader( 4611): Expected native library version number "",actual native library version number ""
,I/chromium( 4611): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4611): Initializing chromium process, renderers=0
,D/PMS     (  907): acquireWL(43bcad20): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
,D/PMS     (  907): acquireWL(43eb4568): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
,E/AudioManagerAndroid( 4611): BLUETOOTH permission is missing!
D/PMS     (  907): releaseWL(43bcad20): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4611): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4611): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4611): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4611): Local Branch: 
I/Adreno-EGL( 4611): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4611): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4611):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4611): Starting up...
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4611/10151)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4611/10151)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4220/10160)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4220/10160)
,D/Process (  907): killProcessQuiet, pid=4303
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/dalvikvm-heap( 4547): Grow heap (frag case) to 10.280MB for 75760-byte allocation
I/ActivityManager(  907): Killing 4303:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1883/10178)
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1883/10178)
,D/GCM     ( 1371): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4547/10026)
,W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{442efba0 u0 ReceiverList{43fac998 4547 com.facebook.katana/10026/u0 remote:43fac808}}
,W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{442efba0 u0 ReceiverList{43fac998 4547 com.facebook.katana/10026/u0 remote:43fac808}}
,W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42c49a58 u0 ReceiverList{42c499f8 4547 com.facebook.katana/10026/u0 remote:443f2ca8}}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4547/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4547/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4547/10026)
,I/ActivityManager(  907): Recipient 4303
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  907): Client connection lost with reason: 4
,D/PMS     (  907): acquireWL(438d20c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1430 10028 null
,D/PMS     (  907): releaseWL(438d20c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/GCoreFlp( 1430): Unknown pending intent to remove.
D/PMS     (  907): acquireWL(428c8f00): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1430 10028 null
D/PMS     (  907): releaseWL(428c8f00): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4547): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4547): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,D/wpa_supplicant( 1173): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1173): EAPOL: disable timer tick
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1173): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1173): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  907):    returned true
,D/WifiStateMachine(  907): handlePostDhcpSetup release wake lock during DHCP
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(43f42468): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiP2pService(  907): InactiveState{ when=-6ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=-6ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [2][0][0]
I/wpa_supplicant( 1173): Change stage from stage0 to stage3
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 96
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): gateway: /192.168.1.1
,D/WifiNative-wlan0(  907): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1173): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1173): wlan0: Background scan every 600 seconds
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  907): VerifyingLinkState enter
D/WifiStateMachine(  907): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  907): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  907): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -55, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WIFI_ICON( 1119): updateWifiState: RSSI_CHANGED -1 -> 3
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,I/IntentController( 1119): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=21649 delay=15s
V/NetworkPolicy(  907): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1883/10178)
,D/WISPrService( 4242): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/WifiWatchdogStateMachine(  907): WAN detection
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  907): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  907): default: teardown()
D/MDST    (  907): default: setTeardownRequested(true)
D/MDST    (  907): default: setEnableApn apnType =default , enable=false
D/MDST    (  907): default: setTeardownRequested(true)
D/ConnectivityService(  907): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  907): syncGetConfiguredNetworks
D/WIFI_ICON( 1119): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WIFI_ICON( 1119): WifiActivity: 3
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/ConnectivityService(  907): Unexpected mtu value: android.net.wifi.WifiStateTracker@42778918
,D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
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
,I/QuickSettingWifi( 1119): receive.wifiConnect:true wifiAPname:NG700 elapse:0
D/WirelessDisplayService(  907): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  907):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  907): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  907): acquireWL(439e59e8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4580/10078)
,D/PMS     (  907): acquireWL(4390d4d0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2229 10028 null
,I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
,I/logwrapper(  363): /system/bin/ip terminated by exit(254)
D/PMS     (  907): acquireWL(43ad9120): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2229 10028 null
D/PMS     (  907): releaseWL(4390d4d0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2229/10028)
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
I/CheckinService( 2229): Preparing to send checkin request
,I/EventLogService( 2229): Accumulating logs since 1452280434892
,I/GoogleHttpClient( 2229): Falling back to old SSLCertificateSocketFactory
I/GoogleHttpClient( 2229): Using GMS GoogleHttpClient
D/ConnectivityService(  907): mActiveDefaultNetwork: WIFI
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(439e59e8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (2229/10028)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.google.android.gms (2229/10028)
,W/GLSUser ( 1371): GoogleAccountDataService.getToken()
,W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1371): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1594): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1594): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 2229): awaiting user notification for token
,I/RemoteViews( 1119): com.google.android.gms (false,0)
I/ActivityManager(  907): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4686 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41e45788 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1119): com.google.android.gms 5 9 3 12
,I/MultiDex( 4686): install
,I/MultiDex( 4686): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4686): loading existing secondary dex files
,I/MultiDex( 4686): load found 1 secondary dex files
,I/MultiDex( 4686): install done
,I/ProviderInstaller( 4686): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1371): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/Adreno-EGL( 4686): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4686): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4686): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4686): Local Branch: 
I/Adreno-EGL( 4686): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4686): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4686):                  aa63bbd948f41d15fc72f585e
,D/PMS     (  907): releaseWL(442ca2d8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  907): NetTransition Wakelock for ConnectedState released by timeout
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: true
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4580/10078)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4367/10100)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/CaptivePortalTracker(  907): NoActiveNetworkState
I/acms    ( 1918): Checking Certificates
I/acms    ( 1918): Checking Developer Certificates
I/acms    ( 1918): Checking Application Certificates
I/acms    ( 1918): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
,I/acms    ( 1918): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1918): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1918): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1918): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1918): Updating next query delay: 75600000
I/mlserverapp( 1918): MirrorLink is never connected, don't setup ACMS programed checks
,I/mlserverapp( 1918): cancelACMSProgrammedChecks
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,I/NetworkMonitor( 3969): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1918/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.musicenhancer (3990/10051)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1430/10028)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (3969/10154)
D/PMS     (  907): acquireWL(43a4dbd0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [3][0][0]
,V/Tethering(  907): bSetPropertyMultiRAB:false
,D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,I/ConnectivityHelper( 1274): [onReceive] WIFI(1): CONNECTED
I/Tethering(  907): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
,I/Tethering(  907): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  907): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  907): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  907): Found interface wlan0
,D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1883/10178)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1274/10075)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4367/10100)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(439e5b38): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4547/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4547/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4547/10026)
,D/PMS     (  907): releaseWL(439e5b38): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/GpsLocationProvider(  907): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(43a4dbd0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (2449/10021)
,D/PMS     (  907): acquireWL(41fe5358): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2229 10028 null
,D/PMS     (  907): releaseWL(41fe5358): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/GCM     ( 1371): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1371/10028)
D/libc    ( 1371): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1371): [NET] getaddrinfo-,err=8
D/libc    ( 1371): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1371): [NET] getaddrinfo-, 1
,D/libc    ( 1371): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =55f8 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1371/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1371/10028)
D/PMS     (  907): acquireWL(42649040): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1371 10028 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2229/10028)
,D/AutoSetting( 1407): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4580): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4580): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1407/10053)
,D/AutoSetting( 1407): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4611/10151)
D/AutoSetting( 1407): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1407): service - requestNLP() NetworkLocationProvider not enabled
,D/AutoSetting( 1407): service - onStartCommand() REMOVE current location bundle
D/AutoSetting( 1407): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1407): service - onStartCommand() check timezone in 30000
,D/AutoSetting( 1407): service - handleMessage() setting current location null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1407/10053)
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 241
D/libc    (  363): [NET]res_nsend:resplen=79
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/libc    ( 1371): [NET] getaddrinfo_proxy-, success
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4220/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4220/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1883/10178)
,I/dalvikvm-heap( 4220): Grow heap (frag case) to 13.519MB for 1821008-byte allocation
,D/libc    ( 1371): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1371): [NET] getaddrinfo-,err=8
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1371/10028)
,D/PMS     (  907): acquireWL(423b6748): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10028 null
,D/PMS     (  907): releaseWL(423b6748): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (4686/10028)
,I/Adreno-EGL( 4686): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4686): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4686): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4686): Local Branch: 
I/Adreno-EGL( 4686): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4686): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4686):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4686): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4686): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4686): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4686): Local Branch: 
I/Adreno-EGL( 4686): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4686): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4686):                  aa63bbd948f41d15fc72f585e
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=20 [5][1][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 168
D/WifiStateMachine(  907): BroadcastRSSIForIMS, newrssi =-55 , oldRssi= -200
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  907):    returned true
D/WIFI_ICON( 1119): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/GCM     ( 1371): Connected
D/PMS     (  907): acquireWL(4434e4b8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1371 10028 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1371/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1371/10028)
D/PMS     (  907): releaseWL(42649040): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1371/10028)
D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1371/10028)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1371/10028)
D/PMS     (  907): releaseWL(4434e4b8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  907): acquireWL(428634b0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1371 10028 null
W/Settings( 4686): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1371/10028)
D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1371/10028)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
,D/GCM     ( 1371): Message class mpf
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1371/10028)
D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1371/10028)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1371/10028)
D/PMS     (  907): releaseWL(428634b0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4547/10026)
D/PMS     (  907): acquireWL(42765358): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10028 null
D/PMS     (  907): releaseWL(42765358): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4547/10026)
W/fb4a(:<default>):UserScope( 4547): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
I/CheckinTask( 2229): Sending checkin request (9017 bytes)
W/fb4a(:<default>):UserScope( 4547): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/libc    ( 2229): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2229): [NET] getaddrinfo-,err=8
D/libc    ( 2229): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2229): [NET] getaddrinfo-, 1
D/libc    ( 2229): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =2f92 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=33 [3][1][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4547/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4547/10026)
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 208
D/libc    (  363): [NET]res_nsend:resplen=84
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2229): [NET] getaddrinfo_proxy-, success
,E/fb4a(:<default>):LocalFbBroadcastManager( 4547): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4547/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4547/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4547/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4547/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4547/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4547/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4547/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4547/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4547/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4547/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4547/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4547/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4547/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4547/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4547/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4547/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4547/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4547/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4547/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4547/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4547/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4547/10026)
,D/libc    ( 2229): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2229): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=23 [13][3][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,D/PMS     (  907): releaseWL(43eb4568): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/PMS     (  907): acquireWL(4291f200): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10028 null
,D/PMS     (  907): releaseWL(4291f200): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (2229/10028)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.google.android.gms (2229/10028)
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=0 [2][0][0]
,W/GLSUser ( 1371): GoogleAccountDataService.getToken()
,W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1371): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1594): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,W/CheckinRequestBuilder( 2229): awaiting user notification for token
,D/DotMatrix( 1594): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1119): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41ed58b0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1119): com.google.android.gms 1 6 2 12
,I/CheckinTask( 2229): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2229): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2229/10028)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2229/10028)
,D/PMS     (  907): releaseWL(43ad9120): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/GCM     ( 1371): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
E/ActivityThread( 2229): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41ea5b08 that was originally bound here
E/ActivityThread( 2229): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41ea5b08 that was originally bound here
E/ActivityThread( 2229): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2229): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2229): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2229): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2229): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2229): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2229): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2229): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2229): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2229): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2229): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2229): 	at bks.a(SourceFile:298)
E/ActivityThread( 2229): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2229): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2229): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2229): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1371): GCM config loaded
,I/SensorManager(  907): mEventCount = 1200
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =6df8 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=172
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  907): Find DNS Address www.htc.com/104.81.130.175,
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC <<
,I/GAV2    ( 4611): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  907): acquireWL(437edb10): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1430 10028 null
,D/PMS     (  907): acquireWL(439d7e70): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1430 10028 null
,D/PMS     (  907): releaseWL(437edb10): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  907): releaseWL(439d7e70): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1173): environment dirty rate=25 [4][1][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 240
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =1
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
D/WIFI_ICON( 1119): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/jxcore-log( 4483): Test app app.js loaded
I/jxcore-log( 4483): 
,I/Choreographer( 4483): Skipped 529 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4483): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/PMS     (  907): Going to sleep due to screen timeout...
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42519f20
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = CM36282 Light sensor
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42519f20, eanble = 0, strlen(mName) = 59
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  907): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4267d830
W/SensorService(  907): Listener[1] = com.htc.smartdim.sensor_eye@42954e30
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  907): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  907): Couldn't get kernel wake lock stats
V/LightsService(  907): setLight #2: color=#0
D/qdlights(  907): set_light_buttons_func: on=0 brightness=0
V/LightsService(  907): setLight #0: color=#0
,W/PMS     (  907): mWirelessDisplayManager is null
D/WirelessDisplayService(  907): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,D/SurfaceControl(  907): Excessive delay in blankDisplay() while turning screen off: 375ms
D/PMS     (  907): nativeSetInteractive:false
D/PMS     (  907): nativeSetInteractive:false done
D/PMS     (  907): nativeSetAutoSuspend:true
D/PMS     (  907): nativeSetAutoSuspend:true done
D/HABCtrl (  907): TPE algorithm. remove timeout.
D/PMS     (  907): OOBE c monitor 11
I/InputManager(  907): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  907): screenObserver, isScreenOn=false
,I/InputMethodManagerService(  907): Disable input method client, pid=4483
D/NfcService( 1261): ScreenObserver: OFF
D/NfcService( 1261): applyRouting - 0
W/ResourceType( 4483): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4483): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41e55400 VFEDH.C. .F...... 0,0-720,1134 #64}
V/KeyguardServiceDelegate(  907): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@4295f1e8)
,D/NfcService( 1261): applyRouting -2
,I/IntentController( 1119): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMS     (  907): acquireWL(4442da20): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1261 1027 null
D/PMN     (  907): wakingUp
D/PMS     (  907): releaseWL(4442da20): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/KeyguardServiceDelegate(  907): **** SHOWN CALLED ****
D/WirelessDisplayService(  907): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/PMS     (  907): acquireWL(43af1e78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(43af1e78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/WindowManager(  907): No lock screen! windowToken=null
,D/PMN     (  907): onScreenOn
D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/ActivityManager(  907): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.extremepowersaver.ExtremePowerSaverReceiver: pid=4727 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/MtpService( 2449): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2449): [MTP][onReceive]-
,D/NfcService( 1261): applyRouting - 0
,D/NfcService( 1261): applyRouting -2
D/PMS     (  907): acquireWL(4434b3b8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1261 1027 null
D/PMS     (  907): releaseWL(4434b3b8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,I/ClockThread( 1119): stop update clock
D/AlarmManager(  907): ACTION_SCREEN_ON
I/AlarmManager(  907): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done recovering
I/AlarmManager(  907): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done EPS screen off alarm recovering
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=21650 delay=15s
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=20 [5][1][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 312
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1173): SET_SCREEN_ON:On
I/wpa_supplicant( 1173): htc_wext_set_keepalive +
I/wpa_supplicant( 1173): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1173): getPrivFuncNum +	
I/wpa_supplicant( 1173): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1173): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1173): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1173): BG scan when screen On
I/wpa_supplicant( 1173): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1173): htc_wext_set_TX_TRACKING - ret = 0
I/wpa_supplicant( 1173): wpa_supplicant_scan enter
I/wpa_supplicant( 1173): Match BG scan, scan!
I/wpa_supplicant( 1173): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1173): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1173): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1173): nl80211: Event message available
D/wpa_supplicant( 1173): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiNative-wlan0(  907):    returned true
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1173): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WifiStateMachine(  907): [ScoreAP] + current TXpacket:49, mTXpacketCount:0, avgLinkspeed:62,mAvgTxRate54
,D/WifiStateMachine(  907): [ScoreAP] + TX packet increase one time, don't update TX rate in DB
W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
D/WIFI_ICON( 1119): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,V/SRS_Proc(  370): ParamSet string: screen_state=on
,D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/WIFI_ICON( 1119): WifiActivity: 0
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/StatusBar.NetworkController( 1119): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
W/ContextImpl( 4727): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/NetworkPolicy(  907): updateScreenOn: false
D/TetherSettings( 4242): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4242): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4242): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4242): Cust_ConnectToPC   : spcsc>false
D/        ( 4242): Cust_ConnectToPC   : IPT>true
D/        ( 4242): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4242): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4242): Index of the first 1 = -1
W/ContextImpl( 4242): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/Settings( 4242): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 4242): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4242): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4242): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 4242): [ACC]android_networking:tethering_guard_support=false
W/ContextImpl( 4242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  907): killProcessQuiet, pid=4334
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/AutoSetting( 1407): receiver - intent: android.intent.action.USER_PRESENT
,I/ActivityManager(  907): Killing 4334:com.google.android.partnersetup/u0a31 (adj 15): empty #17
D/TetherSettings( 4242): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4242): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4242): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4242): Cust_ConnectToPC   : spcsc>false
D/        ( 4242): Cust_ConnectToPC   : IPT>true
D/        ( 4242): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 4242): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4242): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4242): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4242): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/AutoSetting( 1407): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,I/PSReceiver( 4242): onReceive:android.intent.action.USER_PRESENT
I/ActivityManager(  907): Recipient 4334
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ContextImpl( 4242): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/SmartNS_PSService( 4242): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4242): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4242):  defaultType:0
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  907): acquireWL(43eab3a0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1430 10028 null
,D/PMS     (  907): releaseWL(43eab3a0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1850): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1850): onScreenOn: 1452280492578
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1850): onScreenOn: 1452280492579
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4267d830
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4267d830, eanble = 0, strlen(mName) = 91
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  907): Listener[0] = com.htc.smartdim.sensor_eye@42954e30
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/ContextImpl( 4727): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/PMN     (  907): goingToSleep
D/PMS     (  907): acquireWL(43a1bed0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 907 1000 null
,D/SmartSyncUtils( 4727): isEpsOn(), nState = 0
D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=21650 mDataStallAlarmIntent=PendingIntent{44387dc8: PendingIntentRecord{42903760 android broadcastIntent}}
D/PMS     (  907): releaseWL(43a1bed0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/AlarmManager(  907): ACTION_SCREEN_OFF
I/AlarmManager(  907): [AlarmQueuing] screen off now: 
I/AlarmManager(  907): [AlarmQueuing] data connection: true
I/AlarmManager(  907): [AlarmQueuing] wifi connection: true
,D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 0
D/PMS     (  907): acquireWL(4286da88): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4727 1000 null
D/PMS     (  907): acquireWL(439b7ae8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 907 1000 null
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): releaseWL(4286da88): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1173): SET_SCREEN_ON:Off
I/wpa_supplicant( 1173): htc_wext_set_keepalive +
I/wpa_supplicant( 1173): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1173): getPrivFuncNum +	
I/wpa_supplicant( 1173): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1173): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1173): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1173): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1173): htc_wext_set_keepalive - ret = 0
D/SmartSyncUtils( 4727): getMobilePolicyEnabled, result = true
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,V/SRS_Proc(  370): ParamSet string: screen_state=off
,D/wpa_supplicant( 1173): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/NetworkPolicy(  907): updateScreenOn: false
D/PMS     (  907): releaseWL(439b7ae8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1173): nl80211: survey data missing!
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1173): environment dirty rate=0 [0][0][0]
W/ContextImpl( 4727): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4727): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4727): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4727): getMobilePolicyEnabled, result = true
I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42954e30
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 1
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42954e30, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = CM36282 Proximity sensor
D/WifiService(  907): New client listening to asynchronous messages
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 0
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42954e30, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42954e30
E/ActivityThread(  907): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@429554a0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  907): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@429554a0 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/ContactMessageStore( 1243): start background delete task...
D/ContactMessageStore( 1243): size: 0 , 0
,D/ContactMessageStore( 1243): Background delete complete
,D/Process (  907): killProcessQuiet, pid=4367
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4367:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,D/AutoSetting( 1407): service - mHandler: cancel location update
,D/AutoSetting( 1407): service -           changes count: 0
,D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] getTotalRam: 1873 Mb
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1850): onScreenOff.
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1850): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1850): disableBatteryAlarm
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1850): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1850): onScreenOff
D/PMS     (  907): acquireWL(432030a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1430 10028 null
D/PMS     (  907): releaseWL(432030a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/ActivityManager(  907): Recipient 4367
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1510): service - handleMessage() stop self
,D/AutoSetting( 1510): service - onDestroy() END
,D/AutoSetting( 1510): service - handleMessage() quit looper
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4547/10026)
,I/dalvikvm-heap( 4547): Grow heap (frag case) to 10.987MB for 37010-byte allocation
,I/dalvikvm-heap( 4547): Grow heap (frag case) to 11.016MB for 55510-byte allocation
,I/dalvikvm-heap( 4547): Grow heap (frag case) to 11.033MB for 54554-byte allocation
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4547/10026)
,I/dalvikvm-heap( 4547): Grow heap (frag case) to 11.108MB for 82852-byte allocation
,I/dalvikvm-heap( 4547): Grow heap (frag case) to 11.115MB for 55794-byte allocation
,D/wpa_supplicant( 1173): nl80211: Event message available
D/wpa_supplicant( 1173): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1173): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1173): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1173): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1173): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 06:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1173): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
I/wpa_supplicant( 1173): [NULL] 64:7c:34:38:27:cc freq=2462 level=-91
D/wpa_supplicant( 1173): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=14 entropy=0
D/wpa_supplicant( 1173): Add randomness: count=15 entropy=1
D/wpa_supplicant( 1173): Add randomness: count=16 entropy=2
D/wpa_supplicant( 1173): Add randomness: count=17 entropy=3
D/wpa_supplicant( 1173): Add randomness: count=18 entropy=4
D/wpa_supplicant( 1173): Add randomness: count=19 entropy=5
D/wpa_supplicant( 1173): Add randomness: count=20 entropy=6
D/wpa_supplicant( 1173): Add randomness: count=21 entropy=7
D/wpa_supplicant( 1173): Add randomness: count=22 entropy=8
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP 64:7c:34:38:27:cc type 0 added
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): Selecting BSS from priority group 1
I/wpa_supplicant( 1173): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1173): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1173): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1173): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1173): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1173):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1173):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1173): Start print parameters
I/wpa_supplicant( 1173): wpa_s->wpa_state is 9
I/wpa_supplicant( 1173): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1173): isConcu,rrentMode() is 0
I/wpa_supplicant( 1173): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1173): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1173): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1173): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1173): wpa_s->reassociate is 0
I/wpa_supplicant( 1173): wpa_s->is_screen_on 0
I/wpa_supplicant( 1173): wpa_s->ifname wlan0
I/wpa_supplicant( 1173): End print parameters
I/wpa_supplicant( 1173): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1173): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 6: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 7: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 8: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1173): p2p0: Updating scan results from sibling
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
,E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): Sorted scan results
,I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1173): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
,I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84,
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 06:7c:34:38:27:cc freq=2462 level=-90
,I/wpa_supplicant( 1173): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
,I/wpa_supplicant( 1173): [NULL] 64:7c:34:38:27:cc freq=2462 level=-91
D/wpa_supplicant( 1173): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=23 entropy=9
,D/wpa_supplicant( 1173): Add randomness: count=24 entropy=10
D/wpa_supplicant( 1173): Add randomness: count=25 entropy=11
,D/wpa_supplicant( 1173): Add randomness: count=26 entropy=12
D/wpa_supplicant( 1173): Add randomness: count=27 entropy=13
D/wpa_supplicant( 1173): Add randomness: count=28 entropy=14
,D/wpa_supplicant( 1173): Add randomness: count=29 entropy=15
D/wpa_supplicant( 1173): Add randomness: count=30 entropy=16
D/wpa_supplicant( 1173): Add randomness: count=31 entropy=17
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP 64:7c:34:38:27:cc type 0 added
,D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): clear disabled list - type=1
,I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1173): State: DISCONNECTED -> INACTIVE
,D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@43918a28 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@43918a28 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@43918a28 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1173): reply (1216) for get BSS: id=0
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1173): freq=5220
I/wpa_supplicant( 1173): level=-47
I/wpa_supplicant( 1173): tsf=0000000120501458
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG7005g
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=1
I/wpa_supplicant( 1173): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-55
I/wpa_supplicant( 1173): tsf=0000000120501480
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1173): ssid=01ABC
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=2
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-55
I/wpa_supplicant( 1173): tsf=0000000120501489
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG700
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=3
I/wpa_supplicant( 1173): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-78
I/wpa_supplicant( 1173): tsf=0000000120501499
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=Gonzos
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=4
I/wpa_supplicant( 1173): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-84
I/wpa_supplicant( 1173): tsf=0000000120501518
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC5999698
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=5
I/wpa_supplicant( 1173): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-84
I/wpa_supplicant( 1173): tsf=0000000120501508
I/wpa_supplicant( 1173): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=UPC Wi-Free
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=6
I/wpa_supplicant( 1173): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1173): freq=2462
I/wpa_supplicant( 1173): level=-90
I/wpa_supplicant( 1173): tsf=0000000120501527
I/wpa_supplicant( 1173): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=UPC Wi-Free
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=7
I/wpa_supplicant( 1173): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-91
I/wpa_supplicant( 1173): tsf=0000000120501537
I/wpa_supplicant( 1173): flags
,D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 120501458, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 120501480, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 120501489, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 120501499, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -84, frequency: 2437, timestamp: 120501518, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  907): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -84, frequency: 2437, timestamp: 120501508, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 6: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 120501527, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 7: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 120501537, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 8: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2462, timestamp: 120501549, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 9 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  69, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (9) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/dalvikvm-heap( 4547): Grow heap (frag case) to 11.155MB for 72364-byte allocation
,D/libc    ( 4547): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
D/libc    ( 4547): [NET] getaddrinfo-,err=8
D/libc    ( 4547): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    ( 4547): [NET] getaddrinfo-, 1
,D/libc    ( 4547): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =b4f9 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 32
D/libc    (  363): [NET]res_nsend:resplen=93
D/libc    (  363): [NET]res_queryN: exit 3, ancount=3
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4547): [NET] getaddrinfo_proxy-, success
,I/global  ( 4547): call createSocket() return a new socket.
D/libc    ( 4547): [NET] getaddrinfo+,hn 11(0x33312e31332e38),sn(),family 0,flags 4
,D/libc    ( 4547): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4547): [NET] getaddrinfo+,hn 18(0x622d6170692e66),sn(),family 0,flags 4
,D/libc    ( 4547): [NET] getaddrinfo-,err=8
,D/PMS     (  907): acquireWL(445a6468): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 4547 10026 null
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  907): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/global  ( 4547): I/O error closing connection
I/global  ( 4547): java.net.SocketException: Socket is closed
I/global  ( 4547): 	at java.net.Socket.checkOpenAndCreate(Socket.java:672)
I/global  ( 4547): 	at java.net.Socket.getSoLinger(Socket.java:435)
I/global  ( 4547): 	at com.android.org.conscrypt.OpenSSLSocketImplWrapper.getSoLinger(OpenSSLSocketImplWrapper.java:156)
I/global  ( 4547): 	at org.apache.http.impl.conn.tsccm.AbstractConnPool.closeConnection(AbstractConnPool.java:328)
I/global  ( 4547): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteEntry(ConnPoolByRoute.java:530)
I/global  ( 4547): 	at org.apache.http.impl.conn.tsccm.ConnPoolByRoute.deleteClosedConnections(ConnPoolByRoute.java:653)
I/global  ( 4547): 	at org.apache.http.impl.conn.tsccm.ThreadSafeClientConnManager.closeIdleConnections(ThreadSafeClientConnManager.java:295)
I/global  ( 4547): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager.b(FbClientConnManager.java:316)
I/global  ( 4547): 	at com.facebook.http.common.executorimpl.apache.FbClientConnManager$CloseIdleConnectionsRunnable.run(FbClientConnManager.java:327)
I/global  ( 4547): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
I/global  ( 4547): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
I/global  ( 4547): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
I/global  ( 4547): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
I/global  ( 4547): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
I/global  ( 4547): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
I/global  ( 4547): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
I/global  ( 4547): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
I/global  ( 4547): 	at java.lang.Thread.run(Thread.java:864)
,W/IdleConnectionHandler( 4547): Removing a connection that never existed!
D/PMS     (  907): releaseWL(445a6468): PARTIAL_WAKE_LOCK  FbClientConnManager 0x1 null
,I/ActivityManager(  907): Killing 3990:com.htc.musicenhancer/u0a51 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=3990
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 3990
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 1
D/PMS     (  907): acquireWL(44381c90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{424a38c8: PendingIntentRecord{426e9f68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=125003, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(44381c90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4437ae18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/PMS     (  907): releaseWL(4437ae18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 2
,I/wpa_supplicant( 1173): wpa_supplicant_scan enter
I/wpa_supplicant( 1173): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1173): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1173): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1173): nl80211: Event message available
,D/wpa_supplicant( 1173): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1173): nl80211: Event message available
D/wpa_supplicant( 1173): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1173): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1173): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1173): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1173): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 06:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1173): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
I/wpa_supplicant( 1173): [NULL] 64:7c:34:38:27:cc freq=2462 level=-91
D/wpa_supplicant( 1173): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=32 entropy=18
D/wpa_supplicant( 1173): Add randomness: count=33 entropy=19
D/wpa_supplicant( 1173): Add randomness: count=34 entropy=20
D/wpa_supplicant( 1173): Add randomness: count=35 entropy=21
D/wpa_supplicant( 1173): Add randomness: count=36 entropy=22
D/wpa_supplicant( 1173): Add randomness: count=37 entropy=23
D/wpa_supplicant( 1173): Add randomness: count=38 entropy=24
D/wpa_supplicant( 1173): Add randomness: count=39 entropy=25
D/wpa_supplicant( 1173): Add randomness: count=40 entropy=26
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): Selecting BSS from priority group 1
I/wpa_supplicant( 1173): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1173): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1173): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1173): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1173): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1173):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1173):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1173): Start print parameters
I/wpa_supplicant( 1173): wpa_s->wpa_state is 9
I/wpa_supplicant( 1173): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1173): isConcurrentMode() is 0
I/wpa_supplicant( 1173): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1173): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1173): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1173): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1173): wpa_s->reassociate is 0
I/wpa_supplicant( 1173): wpa_s->i,s_screen_on 0
I/wpa_supplicant( 1173): wpa_s->ifname wlan0
I/wpa_supplicant( 1173): End print parameters
I/wpa_supplicant( 1173): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1173): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 6: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 7: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 8: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1173): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1173): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 06:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1173): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
I/wpa_supplicant( 1173): [NULL] 64:7c:34:38:27:cc freq=2462 level=-91
D/wpa_supplicant( 1173): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=41 entropy=27
D/wpa_supplicant( 1173): Add randomness: count=42 entropy=28
D/wpa_supplicant( 1173): Add randomness: count=43 entropy=29
D/wpa_supplicant( 1173): Add randomness: count=44 entropy=30
D/wpa_supplicant( 1173): Add randomness: count=45 entropy=31
D/wpa_supplicant( 1173): Add randomness: count=46 entropy=32
D/wpa_supplicant( 1173): Add randomness: count=47 entropy=33
D/wpa_supplicant( 1173): Add randomness: count=48 entropy=34
D/wpa_supplicant( 1173): Add randomness: count=49 entropy=35
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): clear disabled list - type=1
,I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1173): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1173): reply (1216) for get BSS: id=0
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:4a,
I/wpa_supplicant( 1173): freq=5220
I/wpa_supplicant( 1173): level=-47
I/wpa_supplicant( 1173): tsf=0000000138673355
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG7005g
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=1
I/wpa_supplicant( 1173): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-55
I/wpa_supplicant( 1173): tsf=0000000138673383
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1173): ssid=01ABC
I/wpa_supplicant( 1173): ====,
I/wpa_supplicant( 1173): id=2
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-55
I/wpa_supplicant( 1173): tsf=0000000138673400
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG700
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=3
I/wpa_supplicant( 1173): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-78
I/wpa_supplicant( 1173): tsf=0000000138673413
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=Gonzos
I/wpa_supplicant( 1173): ====
,I/wpa_supplicant( 1173): id=4
I/wpa_supplicant( 1173): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-84
I/wpa_supplicant( 1173): tsf=0000000138673435
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC5999698
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=5
I/wpa_supplicant( 1173): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-84
,I/wpa_supplicant( 1173): tsf=0000000138673423
I/wpa_supplicant( 1173): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=UPC Wi-Free
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=6
I/wpa_supplicant( 1173): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1173): freq=2462
I/wpa_supplicant( 1173): level=-90
I/wpa_supplicant( 1173): tsf=0000000138673446
I/wpa_supplicant( 1173): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=UPC Wi-Free
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=7
I/wpa_supplicant( 1173): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-91
I/wpa_supplicant( 1173): tsf=0000000138673455
I/wpa_supplicant( 1173): flags
D/WirelessDisplayService(  907): getDiscoveryDongleList
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 138673355, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 138673383, distance: ?(cm), distanceSd: ?(cm),
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  907): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 138673400, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 138673413, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -84, frequency: 2437, timestamp: 138673435, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -84, frequency: 2437, timestamp: 138673423, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 6: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 138673446, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 7: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 138673455, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 8: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2462, timestamp: 138673465, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 9 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  75, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  69, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (9) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/AutoSetting( 1407): service - mHandler: update timezone
,D/AutoSetting( 1510): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1510): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1510): service - onCreate()
D/AutoSetting( 1510): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1510): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
,D/DotMatrix( 1594): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1594): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,D/AutoSetting( 1510): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1510): service - onStartCommand() handle command from HSP: processTimeZoneID
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AutoSetting( 1510): service - mHandler: update timezone
,D/AutoSetting( 1510): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1510): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1510): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1510): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1594): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1594): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1119): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1119): release indeterminate drawable android.widget.OnDemandProgressBar{41f99028 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1119): com.htc.htclocationservice 1 8 2 11
,D/GpsLocationProvider(  907): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  907): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  907): acquireWL(42884ee0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{42835108: PendingIntentRecord{428216f0 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=143218, Int=0
D/PMS     (  907): acquireWL(427cbff0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
V/AlarmManager(  907): sending alarm PendingIntent{43876eb8: PendingIntentRecord{428406e8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=147749, Int=0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1371/10028)
D/PMS     (  907): releaseWL(42884ee0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
D/PMS     (  907): acquireWL(421d80b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10028 null
,D/PMS     (  907): releaseWL(421d80b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =d827 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/AutoSetting( 1407): service - handleMessage() stop self
,D/AutoSetting( 1407): service - onDestroy() END
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  363): [NET]res_nsend:resplen=238
D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/AutoSetting( 1407): service - handleMessage() quit looper
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
I/global  (  907): call createSocket() return a new socket.
D/libc    (  907): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  907): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  907): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  907): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  907):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 3
,I/ActivityManager(  907): Killing 4383:com.htc.backup/1000 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=4383
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 4383
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  907): releaseWL(427cbff0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/wpa_supplicant( 1173): wpa_supplicant_scan enter
I/wpa_supplicant( 1173): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1173): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1173): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1173): nl80211: Event message available
,D/wpa_supplicant( 1173): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1173): nl80211: Event message available
D/wpa_supplicant( 1173): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1173): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1173): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1173): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-83
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 64:7c:34:38:27:cc freq=2462 level=-89
I/wpa_supplicant( 1173): [NULL] 06:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1173): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1173): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=50 entropy=36
D/wpa_supplicant( 1173): Add randomness: count=51 entropy=37
D/wpa_supplicant( 1173): Add randomness: count=52 entropy=38
D/wpa_supplicant( 1173): Add randomness: count=53 entropy=39
D/wpa_supplicant( 1173): Add randomness: count=54 entropy=40
D/wpa_supplicant( 1173): Add randomness: count=55 entropy=41
D/wpa_supplicant( 1173): Add randomness: count=56 entropy=42
D/wpa_supplicant( 1173): Add randomness: count=57 entropy=43
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): Selecting BSS from priority group 1
I/wpa_supplicant( 1173): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1173): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1173): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1173): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1173):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1173):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1173): Start print parameters
I/wpa_supplicant( 1173): wpa_s->wpa_state is 9
I/wpa_supplicant( 1173): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1173): isConcurrentMode() is 0
I/wpa_supplicant( 1173): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1173): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1173): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1173): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1173): wpa_s->reassociate is 0
I/wpa_supplicant( 1173): wpa_s->is_screen_on 0
I/wpa_supplicant( 1173): wpa_s->ifname wlan0
I/wpa_supplicant( 1173): End print parameters
I/wpa_supplicant( 1173): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1173): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 ,rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 3: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 5: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 6: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 7: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1173): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-83
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 64:7c:34:38:27:cc freq=2462 level=-89
I/wpa_supplicant( 1173): [NULL] 06:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1173): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-91
D/wpa_supplicant( 1173): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=58 entropy=44
D/wpa_supplicant( 1173): Add randomness: count=59 entropy=45
D/wpa_supplicant( 1173): Add randomness: count=60 entropy=46
D/wpa_supplicant( 1173): Add randomness: count=61 entropy=47
D/wpa_supplicant( 1173): Add randomness: count=62 entropy=48
D/wpa_supplicant( 1173): Add randomness: count=63 entropy=49
D/wpa_supplicant( 1173): Add randomness: count=64 entropy=50
D/wpa_supplicant( 1173): Add randomness: count=65 entropy=51
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1173): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1173): reply (1216) for get BSS: id=0
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1173): freq=5220
I/wpa_supplicant( 1173): level=-47
I/wpa_supplicant( 1173): tsf=0000000156883240
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG7005g
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=1
I/wpa_supplicant( 1173): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-55
I/wpa_supplicant( 1173): tsf=0000000138673383
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1173): ssid=01ABC
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=2
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-55
I/wpa_supplicant( 1173): tsf=0000000156883267
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG700
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=3
I/wpa_supplicant( 1173): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-78
I/wpa_supplicant( 1173): tsf=0000000138673413
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=Gonzos
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=4
I/wpa_supplicant( 1173): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-83
I/wpa_supplicant( 1173): tsf=0000000156883302
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
,I/wpa_supplicant( 1173): ssid=UPC5999698
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=5
I/wpa_supplicant( 1173): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-84
I/wpa_supplicant( 1173): tsf=0000000156883292
I/wpa_supplicant( 1173): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=UPC Wi-Free
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=6
I/wpa_supplicant( 1173): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1173): freq=2462
I/wpa_supplicant( 1173): level=-90
I/wpa_supplicant( 1173): tsf=0000000156883312
I/wpa_supplicant( 1173): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=UPC Wi-Free
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=7
I/wpa_supplicant( 1173): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-91
I/wpa_supplicant( 1173): tsf=0000000156883332
I/wpa_supplicant( 1173): flags
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0,
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 156883240, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 138673383, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 156883267, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 138673413, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -83, frequency: 2437, timestamp: 156883302, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -84, frequency: 2437, timestamp: 156883292, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 6: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 156883312, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 7: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 156883332, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 8: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -89, frequency: 2462, timestamp: 156883322, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 9 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  6 [-83], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  69, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (9) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{443e6428 u0 com.htc.htclocationservice/.AutoSettingService}
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 4
,I/wpa_supplicant( 1173): wpa_supplicant_scan enter
I/wpa_supplicant( 1173): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1173): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1173): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1173): nl80211: Event message available
,D/wpa_supplicant( 1173): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/AutoSetting( 1510): service - handleMessage() stop self
,D/AutoSetting( 1510): service - onDestroy() END
,D/AutoSetting( 1510): service - handleMessage() quit looper
,D/Process (  907): killProcessQuiet, pid=4354
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 ,
I/ActivityManager(  907): Killing 4354:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4354
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/wpa_supplicant( 1173): nl80211: Event message available
D/wpa_supplicant( 1173): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1173): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1173): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1173): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 06:7c:34:38:27:cc freq=2462 level=-89
I/wpa_supplicant( 1173): [NULL] 64:7c:34:38:27:cc freq=2462 level=-89
D/wpa_supplicant( 1173): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=66 entropy=52
D/wpa_supplicant( 1173): Add randomness: count=67 entropy=53
D/wpa_supplicant( 1173): Add randomness: count=68 entropy=54
D/wpa_supplicant( 1173): Add randomness: count=69 entropy=55
D/wpa_supplicant( 1173): Add randomness: count=70 entropy=56
D/wpa_supplicant( 1173): Add randomness: count=71 entropy=57
D/wpa_supplicant( 1173): Add randomness: count=72 entropy=58
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): Selecting BSS from priority group 1
I/wpa_supplicant( 1173): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1173): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1173): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1173): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1173):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1173):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1173): Start print parameters
I/wpa_supplicant( 1173): wpa_s->wpa_state is 9
I/wpa_supplicant( 1173): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1173): isConcurrentMode() is 0
I/wpa_supplicant( 1173): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1173): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1173): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1173): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1173): wpa_s->reassociate is 0
I/wpa_supplicant( 1173): wpa_s->is_screen_on 0
I/wpa_supplicant( 1173): wpa_s->ifname wlan0
I/wpa_supplicant( 1173): End print parameters
I/wpa_supplicant( 1173): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1173): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 4: 64:,7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 5: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 6: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1173): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 06:7c:34:38:27:cc freq=2462 level=-89
I/wpa_supplicant( 1173): [NULL] 64:7c:34:38:27:cc freq=2462 level=-89
D/wpa_supplicant( 1173): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=73 entropy=59
D/wpa_supplicant( 1173): Add randomness: count=74 entropy=60
D/wpa_supplicant( 1173): Add randomness: count=75 entropy=61,
D/wpa_supplicant( 1173): Add randomness: count=76 entropy=62,
,D/wpa_supplicant( 1173): Add randomness: count=77 entropy=63
D/wpa_supplicant( 1173): Add randomness: count=78 entropy=64
D/wpa_supplicant( 1173): Add randomness: count=79 entropy=65
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1173): State: INACTIVE -> INACTIVE
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1173): reply (1103) for get BSS: id=0
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1173): freq=5220
I/wpa_supplicant( 1173): level=-47
I/wpa_supplicant( 1173): tsf=0000000174961919
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG7005g
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=2
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-55
,I/wpa_supplicant( 1173): tsf=0000000174961945
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG700
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=3
I/wpa_supplicant( 1173): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-78
I/wpa_supplicant( 1173): tsf=0000000174961961
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=Gonzos
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=4
I/wpa_supplicant( 1173): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-84
I/wpa_supplicant( 1173): tsf=0000000174961983
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
,I/wpa_supplicant( 1173): ssid=UPC5999698
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=5
I/wpa_supplicant( 1173): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-84
I/wpa_supplicant( 1173): tsf=0000000174961972
I/wpa_supplicant( 1173): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=UPC Wi-Free
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=6
I/wpa_supplicant( 1173): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1173): freq=2462
I/wpa_supplicant( 1173): level=-89
I/wpa_supplicant( 1173): tsf=0000000156883312
I/wpa_supplicant( 1173): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=UPC Wi-Free
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=7
I/wpa_supplicant( 1173): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-91
I/wpa_supplicant( 1173): tsf=0000000156883332
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC4688432
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=8
I/wpa_supplicant( 1173): bssid=64:7c:34:38:27:cc
I/wpa_supplicant( 1173): freq=2462,
I/wpa_supplicant( 1173): le
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-6ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 174961919, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 174961945, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 174961961, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -84, frequency: 2437, timestamp: 174961983, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -84, frequency: 2437, timestamp: 174961972, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 156883312, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 6: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2437, timestamp: 156883332, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 7: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -89, frequency: 2462, timestamp: 174962031, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 8 to mScanResults
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  69, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-91], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (8) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(427ed5c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(427ed5c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1119): closing low battery warning: level=100
,D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(4326f428): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{424a38c8: PendingIntentRecord{426e9f68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=185004, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4326f428): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/TelephonyReceiver( 1243): switchBindHtcMsgCursor: null
,I/wpa_supplicant( 1173): wpa_supplicant_scan enter
I/wpa_supplicant( 1173): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1173): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1173): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1173): nl80211: Event message available
,D/wpa_supplicant( 1173): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/PMS     (  907): acquireWL(428c8798): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  907): n_update end
D/HtcPowerSaver(  907): updateBatteryInfo
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1119): closing low battery warning: level=100
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/PMS     (  907): releaseWL(428c8798): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1173): nl80211: Event message available
D/wpa_supplicant( 1173): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1173): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1173): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1173): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1173): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 64:7c:34:38:27:cc freq=2462 level=-89
I/wpa_supplicant( 1173): [NULL] 06:7c:34:38:27:cc freq=2462 level=-89
I/wpa_supplicant( 1173): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
D/wpa_supplicant( 1173): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=80 entropy=66
D/wpa_supplicant( 1173): Add randomness: count=81 entropy=67
D/wpa_supplicant( 1173): Add randomness: count=82 entropy=68
D/wpa_supplicant( 1173): Add randomness: count=83 entropy=69
D/wpa_supplicant( 1173): Add randomness: count=84 entropy=70
D/wpa_supplicant( 1173): Add randomness: count=85 entropy=71
D/wpa_supplicant( 1173): Add randomness: count=86 entropy=72
D/wpa_supplicant( 1173): Add randomness: count=87 entropy=73
D/wpa_supplicant( 1173): Add randomness: count=88 entropy=74
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): Selecting BSS from priority group 1
I/wpa_supplicant( 1173): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1173): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1173): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1173): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1173):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1173):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1173): Start print parameters
I/wpa_supplicant( 1173): wpa_s->wpa_state is 9
I/wpa_supplicant( 1173): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1173): isConcurrentMode() is 0
I/wpa_supplicant( 1173): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1173): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1173): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1173): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1173): wpa_s->reassociate is 0
I/wpa_supplicant( 1173): wpa_s->is_screen_on 0
I/wpa_supplicant( 1173): wpa_s->ifname wlan0
I/wpa_supplicant( 1173): End print parameters
I/wp,a_supplicant( 1173): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1173): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1173): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 5: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 6: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 7: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 8: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1173): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
I/wpa_supplicant( 1173): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 64:7c:34:38:27:cc freq=2462 level=-89
I/wpa_supplicant( 1173): [NULL] 06:7c:34:38:27:cc freq=2462 level=-89
I/wpa_supplicant( 1173): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
D/wpa_supplicant( 1173): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=89 entropy=75
D/wpa_supplicant( 1173): Add randomness: count=90 entropy=76
D/wpa_supplicant( 1173): Add randomness: count=91 entropy=77
D/wpa_supplicant( 1173): Add randomness: count=92 entropy=78
D/wpa_supplicant( 1173): Add randomness: count=93 entropy=79
D/wpa_supplicant( 1173): Add randomness: count=94 entropy=80
D/wpa_supplicant( 1173): Add randomness: count=95 entropy=81
D/wpa_supplicant( 1173): Add randomness: count=96 entropy=82
D/wpa_supplicant( 1173): Add randomness: count=97 entropy=83
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1173): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1173): reply (1216) for get BSS: id=0
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1173): freq=5220
I/wpa_supplicant( 1173): level=-47
I/wpa_supplicant( 1173): tsf=0000000174961919
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG7005g
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=2
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): freq=2412,
I/wpa_supplicant( 1173): level=-55
I/wpa_supplicant( 1173): tsf=0000000193213902
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG700
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=3
I/wpa_supplicant( 1173): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-78
I/wpa_supplicant( 1173): tsf=0000000193213927
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=Gonzos
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=4
I/wpa_supplicant( 1173): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-84
I/wpa_supplicant( 1173): tsf=0000000193213946
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC5999698
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=5
I/wpa_supplicant( 1173): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-84
I/wpa_supplicant( 1173): tsf=0000000193213936
I/wpa_supplicant( 1173): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=UPC Wi-Free
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=6
I/wpa_supplicant( 1173): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1173): freq=2462
I/wpa_supplicant( 1173): level=-89
I/wpa_supplicant( 1173): tsf=0000000156883312
I/wpa_supplicant( 1173): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=UPC Wi-Free
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=7
I/wpa_supplicant( 1173): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1173): freq=2437,
I/wpa_supplicant( 1173): level=-90
I/wpa_supplicant( 1173): tsf=0000000193213981
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC4688432
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=8
I/wpa_supplicant( 1173): bssid=64:7c:34:38:27:cc
I/wpa_supplicant( 1173): freq=2462
I/wpa_supplicant( 1173): le
D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 174961919, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 193213902, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 193213927, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -84, frequency: 2437, timestamp: 193213946, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -84, frequency: 2437, timestamp: 193213936, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 156883312, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 6: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 193213981, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 7: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -89, frequency: 2462, timestamp: 193213957, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 8: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 193213915, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 9 to mScanResults
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  69, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-90], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (9) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(443952c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(443952c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1173): wpa_supplicant_scan enter
I/wpa_supplicant( 1173): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1173): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1173): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1173): nl80211: Event message available
,D/wpa_supplicant( 1173): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1173): nl80211: Event message available
D/wpa_supplicant( 1173): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1173): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1173): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1173): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1173): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 06:7c:34:38:27:cc freq=2462 level=-89
I/wpa_supplicant( 1173): [NULL] 64:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1173): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
D/wpa_supplicant( 1173): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=98 entropy=84
D/wpa_supplicant( 1173): Add randomness: count=99 entropy=85
D/wpa_supplicant( 1173): Add randomness: count=100 entropy=86
D/wpa_supplicant( 1173): Add randomness: count=101 entropy=87
D/wpa_supplicant( 1173): Add randomness: count=102 entropy=88
D/wpa_supplicant( 1173): Add randomness: count=103 entropy=89
D/wpa_supplicant( 1173): Add randomness: count=104 entropy=90
D/wpa_supplicant( 1173): Add randomness: count=105 entropy=91
D/wpa_supplicant( 1173): Add randomness: count=106 entropy=92
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): Selecting BSS from priority group 1
I/wpa_supplicant( 1173): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1173): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1173): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1173): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1173):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1173):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1173): Start print parameters
I/wpa_supplicant( 1173): wpa_s->wpa_state is 9
I/wpa_supplicant( 1173): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1173): isConcurrentMode() is 0
I/wpa_supplicant( 1173): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1173): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1173): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1173): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1173): wpa_s->reassociate is 0
I/wpa_supplicant( 1173): wpa_s->is_screen_on 0
I/wpa_supplicant( 1173): wpa_s->ifname wlan0
I/wpa_supplicant( 1173): End print parameter,s
I/wpa_supplicant( 1173): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1173): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1173): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 5: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 6: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 7: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 8: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1173): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1173): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 06:7c:34:38:27:cc freq=2462 level=-89
I/wpa_supplicant( 1173): [NULL] 64:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1173): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
D/wpa_supplicant( 1173): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=107 entropy=93
D/wpa_supplicant( 1173): Add randomness: count=108 entropy=94
D/wpa_supplicant( 1173): Add randomness: count=109 entropy=95
D/wpa_supplicant( 1173): Add randomness: count=110 entropy=96
D/wpa_supplicant( 1173): Add randomness: count=111 entropy=97
D/wpa_supplicant( 1173): Add randomness: count=112 entropy=98
D/wpa_supplicant( 1173): Add randomness: count=113 entropy=99
D/wpa_supplicant( 1173): Add randomness: count=114 entropy=100
D/wpa_supplicant( 1173): Add randomness: count=115 entropy=101
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1173): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1173): reply (1216) for get BSS: id=0
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1173): freq=5220
I/wpa_supplicant( 1173): level=-47
I/wpa_supplicant( 1173): tsf=0000000211383905
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG7005g
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=2
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-55
I/wpa_supplicant( 1173): tsf=0000000211383934
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG700
,I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=3
I/wpa_supplicant( 1173): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-78
I/wpa_supplicant( 1173): tsf=0000000211383957
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=Gonzos
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=4
I/wpa_supplicant( 1173): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-84
I/wpa_supplicant( 1173): tsf=0000000211383979
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC5999698
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=5
I/wpa_supplicant( 1173): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-84
I/wpa_supplicant( 1173): tsf=0000000211383966
I/wpa_supplicant( 1173): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=UPC Wi-Free
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=6
I/wpa_supplicant( 1173): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1173): freq=2462
I/wpa_supplicant( 1173): level=-89
,I/wpa_supplicant( 1173): tsf=0000000156883312
I/wpa_supplicant( 1173): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=UPC Wi-Free
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=7
I/wpa_supplicant( 1173): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-90
I/wpa_supplicant( 1173): tsf=0000000211384002
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC4688432
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=8
I/wpa_supplicant( 1173): bssid=64:7c:34:38:27:cc
,I/wpa_supplicant( 1173): freq=2462
I/wpa_supplicant( 1173): le
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 211383905, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 211383934, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 211383957, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -84, frequency: 2437, timestamp: 211383979, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -84, frequency: 2437, timestamp: 211383966, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 156883312, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 6: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 211384002, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 7: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2462, timestamp: 211384012, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 8: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 211383946, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 9 to mScanResults
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  69, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-90], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (9) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000),
D/WirelessDisplayService(  907): getDiscoveryDongleList
,I/wpa_supplicant( 1173): wpa_supplicant_scan enter
I/wpa_supplicant( 1173): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1173): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1173): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1173): nl80211: Event message available
,D/wpa_supplicant( 1173): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1173): nl80211: Event message available
D/wpa_supplicant( 1173): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1173): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1173): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1173): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1173): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 64:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1173): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
D/wpa_supplicant( 1173): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=116 entropy=102
D/wpa_supplicant( 1173): Add randomness: count=117 entropy=103
D/wpa_supplicant( 1173): Add randomness: count=118 entropy=104
D/wpa_supplicant( 1173): Add randomness: count=119 entropy=105
D/wpa_supplicant( 1173): Add randomness: count=120 entropy=106
D/wpa_supplicant( 1173): Add randomness: count=121 entropy=107
D/wpa_supplicant( 1173): Add randomness: count=122 entropy=108
D/wpa_supplicant( 1173): Add randomness: count=123 entropy=109
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): Selecting BSS from priority group 1
I/wpa_supplicant( 1173): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1173): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1173): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1173): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1173):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1173):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1173): Start print parameters
I/wpa_supplicant( 1173): wpa_s->wpa_state is 9
I/wpa_supplicant( 1173): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1173): isConcurrentMode() is 0
I/wpa_supplicant( 1173): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1173): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1173): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1173): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1173): wpa_s->reassociate is 0
I/wpa_supplicant( 1173): wpa_s->is_screen_on 0
I/wpa_supplicant( 1173): wpa_s->ifname wlan0
I/wpa_supplicant( 1173): End print parameters
I/wpa_supplicant( 1173): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1173): 2: c2:ff:d4:d3:aa:48 ssid='01ABC', wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1173): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 5: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 6: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 7: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1173): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1173): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 64:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1173): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1173): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=124 entropy=110
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1173): Add randomness: count=125 entropy=111
D/wpa_supplicant( 1173): Add randomness: count=126 entropy=112
D/wpa_supplicant( 1173): Add randomness: count=127 entropy=113
D/wpa_supplicant( 1173): Add randomness: count=128 entropy=114
D/wpa_supplicant( 1173): Add randomness: count=129 entropy=115
D/wpa_supplicant( 1173): Add randomness: count=130 entropy=116
D/wpa_supplicant( 1173): Add randomness: count=131 entropy=117
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 l,ast_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1173): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1173): reply (1216) for get BSS: id=0
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1173): freq=5220
I/wpa_supplicant( 1173): level=-48
I/wpa_supplicant( 1173): tsf=0000000211383905
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG7005g
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=2
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-55
I/wpa_supplicant( 1173): tsf=0000000229563688
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG700
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=3
I/wpa_supplicant( 1173): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-78
I/wpa_supplicant( 1173): tsf=0000000229563715
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=Gonzos
I/wpa_supplicant( 1173): ====,
I/wpa_supplicant( 1173): id=4
I/wpa_supplicant( 1173): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-84
I/wpa_supplicant( 1173): tsf=0000000229563733
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC5999698
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=5
I/wpa_supplicant( 1173): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-84
I/wpa_supplicant( 1173): tsf=0000000211383966
I/wpa_supplicant( 1173): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=UPC Wi-Free
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=6
I/wpa_supplicant( 1173): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1173): freq=2462
I/wpa_supplicant( 1173): level=-89
I/wpa_supplicant( 1173): tsf=0000000156883312
I/wpa_supplicant( 1173): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=UPC Wi-Free
I/wpa_supplicant( 1173): ====
,I/wpa_supplicant( 1173): id=7
I/wpa_supplicant( 1173): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-90
I/wpa_supplicant( 1173): tsf=0000000229563743
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC4688432
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=8
I/wpa_supplicant( 1173): bssid=64:7c:34:38:27:cc
I/wpa_supplicant( 1173): freq=2462
I/wpa_supplicant( 1173): le
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 211383905, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 229563688, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 229563715, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -84, frequency: 2437, timestamp: 229563733, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -84, frequency: 2437, timestamp: 211383966, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  907): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 156883312, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 6: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 229563743, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 7: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2462, timestamp: 229563755, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 8: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 229563703, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 9 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-78], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  69, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-90], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (9) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(430daef8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10026}
,V/AlarmManager(  907): sending alarm PendingIntent{438d91d0: PendingIntentRecord{43fcab58 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=230444, Int=0
,I/ActivityManager(  907): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4773 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  907): sending alarm PendingIntent{42859ff0: PendingIntentRecord{4283bbd0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452280597140, Int=10800000
,D/PMS     (  907): releaseWL(430daef8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.aurora (4773/10047)
,D/Process (  907): killProcessQuiet, pid=4406
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4406:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4406
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2229/10028)
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  907): acquireWL(42957bc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10026}
,V/AlarmManager(  907): sending alarm PendingIntent{43bc9090: PendingIntentRecord{43fcab58 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=237613, Int=0
,D/PMS     (  907): releaseWL(42957bc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,I/wpa_supplicant( 1173): wpa_supplicant_scan enter
I/wpa_supplicant( 1173): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1173): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1173): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1173): nl80211: Event message available
,D/wpa_supplicant( 1173): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  907): acquireWL(426ef290): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{424a38c8: PendingIntentRecord{426e9f68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=245004, Int=0
,I/IntentController( 1119): receive(android.intent.action.TIME_TICK,1,false)
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): releaseWL(426ef290): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1173): nl80211: Event message available
D/wpa_supplicant( 1173): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1173): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1173): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1173): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 06:7c:34:38:27:cc freq=2462 level=-88
I/wpa_supplicant( 1173): [NULL] 64:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1173): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
D/wpa_supplicant( 1173): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=132 entropy=118
D/wpa_supplicant( 1173): Add randomness: count=133 entropy=119
D/wpa_supplicant( 1173): Add randomness: count=134 entropy=120
D/wpa_supplicant( 1173): Add randomness: count=135 entropy=121
D/wpa_supplicant( 1173): Add randomness: count=136 entropy=122
D/wpa_supplicant( 1173): Add randomness: count=137 entropy=123
D/wpa_supplicant( 1173): Add randomness: count=138 entropy=124
D/wpa_supplicant( 1173): Add randomness: count=139 entropy=125
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): Selecting BSS from priority group 1
I/wpa_supplicant( 1173): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1173): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1173): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1173): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1173):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1173):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1173): Start print parameters
I/wpa_supplicant( 1173): wpa_s->wpa_state is 9
I/wpa_supplicant( 1173): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1173): isConcurrentMode() is 0
I/wpa_supplicant( 1173): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1173): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1173): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1173): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1173): wpa_s->reassociate is 0
I/wpa_supplicant( 1173): wpa_s->is_screen_on 0
I/wpa_supplicant( 1173): wpa_s->ifname wlan0
I/wpa_supplicant( 1173): End print parameters
I/wpa_supplicant( 1173): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1173): 2: 38:f8:89:11:e9:11 ssid='Gonzos,' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 3: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 5: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 6: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 7: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1173): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 06:7c:34:38:27:cc freq=2462 level=-88
I/wpa_supplicant( 1173): [NULL] 64:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1173): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
D/wpa_supplicant( 1173): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=140 entropy=126
D/wpa_supplicant( 1173): Add randomness: count=141 entropy=127
D/wpa_supplicant( 1173): Add randomness: count=142 entropy=128
D/wpa_supplicant( 1173): Add randomness: count=143 entropy=129
D/wpa_supplicant( 1173): Add randomness: count=144 entropy=130
D/wpa_supplicant( 1173): Add randomness: count=145 entropy=131
D/wpa_supplicant( 1173): Add randomness: count=146 entropy=132
D/wpa_supplicant( 1173): Add randomness: count=147 entropy=133
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1173): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1173): reply (1216) for get BSS: id=0
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1173): freq=5220
I/wpa_supplicant( 1173): level=-46
I/wpa_supplicant( 1173): tsf=0000000211383905
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG7005g
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=2
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-55
,I/wpa_supplicant( 1173): tsf=0000000247803409
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG700
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=3
I/wpa_supplicant( 1173): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-81
I/wpa_supplicant( 1173): tsf=0000000247803445
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=Gonzos
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=4
I/wpa_supplicant( 1173): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-84
I/wpa_supplicant( 1173): tsf=0000000247803431
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC5999698
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=5
I/wpa_supplicant( 1173): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-84
I/wpa_supplicant( 1173): tsf=0000000247803421
I/wpa_supplicant( 1173): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=UPC Wi-Free
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=6
I/wpa_supplicant( 1173): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1173): freq=2462
I/wpa_supplicant( 1173): level=-88
I/wpa_supplicant( 1173): tsf=0000000247803466
I/wpa_supplicant( 1173): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=UPC Wi-Free
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=7
I/wpa_supplicant( 1173): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-90
I/wpa_supplicant( 1173): tsf=0000000247803454
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC4688432
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=8
I/wpa_supplicant( 1173): bssid=64:7c:34:38:27:cc
I/wpa_supplicant( 1173): freq=2462
I/wpa_supplicant( 1173): le
,D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 211383905, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 247803409, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2412, timestamp: 247803445, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -84, frequency: 2437, timestamp: 247803431, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -84, frequency: 2437, timestamp: 247803421, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 247803466, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 6: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 247803454, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  907): 7: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2462, timestamp: 247803479, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 8: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 229563703, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 9 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  4 [-88], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  75, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  69, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-90], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (9) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43b42988): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,I/IntentController( 1119): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(43b42988): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1594): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1594): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/PowerUI ( 1119): closing low battery warning: level=100
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1119): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1119): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 3
,I/wpa_supplicant( 1173): wpa_supplicant_scan enter
I/wpa_supplicant( 1173): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1173): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1173): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1173): nl80211: Event message available
,D/wpa_supplicant( 1173): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1173): nl80211: Event message available
D/wpa_supplicant( 1173): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1173): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1173): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1173): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 06:7c:34:38:27:cc freq=2462 level=-88
I/wpa_supplicant( 1173): [NULL] 64:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1173): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
I/wpa_supplicant( 1173): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-91
D/wpa_supplicant( 1173): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=148 entropy=134
D/wpa_supplicant( 1173): Add randomness: count=149 entropy=135
D/wpa_supplicant( 1173): Add randomness: count=150 entropy=136
D/wpa_supplicant( 1173): Add randomness: count=151 entropy=137
D/wpa_supplicant( 1173): Add randomness: count=152 entropy=138
D/wpa_supplicant( 1173): Add randomness: count=153 entropy=139
D/wpa_supplicant( 1173): Add randomness: count=154 entropy=140
D/wpa_supplicant( 1173): Add randomness: count=155 entropy=141
D/wpa_supplicant( 1173): Add randomness: count=156 entropy=142
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: AP dc:4a:3e:0f:c2:f1 type 0 added
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): Selecting BSS from priority group 1
I/wpa_supplicant( 1173): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1173): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1173): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1173): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1173):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1173):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1173): Start print parameters
I/wpa_supplicant( 1173): wpa_s->wpa_state is 9
I/wpa_supplicant( 1173): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1173): isConcurrentMode() is 0
I/wpa_supplicant( 1173): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1173): wpa_s->br_p2,p_connected is 0
I/wpa_supplicant( 1173): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1173): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1173): wpa_s->reassociate is 0
I/wpa_supplicant( 1173): wpa_s->is_screen_on 0
I/wpa_supplicant( 1173): wpa_s->ifname wlan0
I/wpa_supplicant( 1173): End print parameters
I/wpa_supplicant( 1173): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1173): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 3: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 5: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 6: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 7: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 8: dc:4a:3e:0f:c2:f1 ssid='DIRECT-AD-HP DeskJet 3630 series' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1173): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 06:7c:34:38:27:cc freq=2462 level=-88
I/wpa_supplicant( 1173): [NULL] 64:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1173): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
I/wpa_supplicant( 1173): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-91
D/wpa_supplicant( 1173): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=157 entropy=143
D/wpa_supplicant( 1173): Add randomness: count=158 entropy=144
D/wpa_supplicant( 1173): Add randomness: count=159 entropy=145
D/wpa_supplicant( 1173): Add randomness: count=160 entropy=146
D/wpa_supplicant( 1173): Add randomness: count=161 entropy=147
D/wpa_supplicant( 1173): Add randomness: count=162 entropy=148
D/wpa_supplicant( 1173): Add randomness: count=163 entropy=149
D/wpa_supplicant( 1173): Add randomness: count=164 entropy=150
D/wpa_supplicant( 1173): Add randomness: count=165 entropy=151
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: AP dc:4a:3e:0f:c2:f1 type 0 added
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1173): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1173): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1173): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
I/wpa_supplicant( 1173): reply (1249) for get BSS: id=0
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1173): freq=5220
I/wpa_supplicant( 1173): level=-47
I/wpa_supplicant( 1173): tsf=0000000266023713
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG7005g
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=2
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-55
I/wpa_supplicant( 1173): tsf=0000000266023740
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG700
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=3
I/wpa_supplicant( 1173): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-79
I/wpa_supplicant( 1173): tsf=0000000266023753
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=Gonzos
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=4
I/wpa_supplicant( 1173): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-84
I/wpa_supplicant( 1173): tsf=0000000266023771
,I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC5999698
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=5
I/wpa_supplicant( 1173): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-84
I/wpa_supplicant( 1173): tsf=0000000266023762
I/wpa_supplicant( 1173): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=UPC Wi-Free
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=6
I/wpa_supplicant( 1173): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1173): freq=2462
I/wpa_supplicant( 1173): level=-88
I/wpa_supplicant( 1173): tsf=0000000266023792
I/wpa_supplicant( 1173): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=UPC Wi-Free
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=7
I/wpa_supplicant( 1173): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-90
I/wpa_supplicant( 1173): tsf=0000000266023782
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC4688432
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=8
I/wpa_supplicant( 1173): bssid=64:7c:34:38:27:cc
I/wpa_supplicant( 1173): freq=2462
I/wpa_supplicant( 1173): le
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 266023713, distance: ?(cm), distanceSd: ?(cm)
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 266023740, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 266023753, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -84, frequency: 2437, timestamp: 266023771, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -84, frequency: 2437, timestamp: 266023762, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 266023792, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 6: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 266023782, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/WifiStateMachine(  907): 7: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2462, timestamp: 266023802, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 8: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -91, frequency: 2437, timestamp: 266023813, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 9 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  75, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  4 [-88], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  67, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-90], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  67, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  0 [-91], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (9) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  406): AtCmdFwd service not published, waiting... retryCnt : 4
,I/wpa_supplicant( 1173): wpa_supplicant_scan enter
I/wpa_supplicant( 1173): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1173): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1173): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1173): nl80211: Event message available
,D/wpa_supplicant( 1173): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1173): nl80211: Event message available
D/wpa_supplicant( 1173): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1173): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1173): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1173): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1173): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-83
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 64:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1173): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
I/wpa_supplicant( 1173): [NULL] 06:7c:34:38:27:cc freq=2462 level=-90
D/wpa_supplicant( 1173): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=166 entropy=152
D/wpa_supplicant( 1173): Add randomness: count=167 entropy=153
D/wpa_supplicant( 1173): Add randomness: count=168 entropy=154
D/wpa_supplicant( 1173): Add randomness: count=169 entropy=155
D/wpa_supplicant( 1173): Add randomness: count=170 entropy=156
D/wpa_supplicant( 1173): Add randomness: count=171 entropy=157
D/wpa_supplicant( 1173): Add randomness: count=172 entropy=158
D/wpa_supplicant( 1173): Add randomness: count=173 entropy=159
D/wpa_supplicant( 1173): Add randomness: count=174 entropy=160
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): Selecting BSS from priority group 1
I/wpa_supplicant( 1173): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1173): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1173): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1173): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1173):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1173):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1173): Start print parameters
I/wpa_supplicant( 1173): wpa_s->wpa_state is 9
I/wpa_supplicant( 1173): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1173): isConcurrentMode() is 0
I/wpa_supplicant( 1173): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1173): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1173): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1173): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1173): wpa_s->reassociate is 0
I/wpa_supplicant( 117,3): wpa_s->is_screen_on 0
I/wpa_supplicant( 1173): wpa_s->ifname wlan0
I/wpa_supplicant( 1173): End print parameters
I/wpa_supplicant( 1173): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1173): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1173): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 4: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 5: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 6: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 7: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1173): 8: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1173): clear disabled list - type=1
I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1173): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1173): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1173): nl80211: Survey data missing
E/wpa_supplicant( 1173): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1173): Sorted scan results
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1173): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1173): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1173): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1173): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-83
I/wpa_supplicant( 1173): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1173): [NULL] 64:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1173): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-90
I/wpa_supplicant( 1173): [NULL] 06:7c:34:38:27:cc freq=2462 level=-90
D/wpa_supplicant( 1173): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1173): Add randomness: count=175 entropy=161
D/wpa_supplicant( 1173): Add randomness: count=176 entropy=162
D/wpa_supplicant( 1173): Add randomness: count=177 entropy=163
D/wpa_supplicant( 1173): Add randomness: count=178 entropy=164
D/wpa_supplicant( 1173): Add randomness: count=179 entropy=165
D/wpa_supplicant( 1173): Add randomness: count=180 entropy=166
D/wpa_supplicant( 1173): Add randomness: count=181 entropy=167
D/wpa_supplicant( 1173): Add randomness: count=182 entropy=168
D/wpa_supplicant( 1173): Add randomness: count=183 entropy=169
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
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1173): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[3] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1173): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1173): wpa_supplicant_pick_network+
I/wpa_supplicant( 1173): clear disabled list - type=1
,I/wpa_supplicant( 1173): No suitable network found
W/wpa_supplicant( 1173): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1173): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
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
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1173): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1173): WPS: Unknown Vendor Extension (Vendor ID 311)
,I/wpa_supplicant( 1173): reply (1363) for get BSS: id=0
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1173): freq=5220
I/wpa_supplicant( 1173): level=-48
I/wpa_supplicant( 1173): tsf=0000000284273883
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG7005g
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=2
I/wpa_supplicant( 1173): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-55
I/wpa_supplicant( 1173): tsf=0000000284273923
I/wpa_supplicant( 1173): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=NG700
I/wpa_supplicant( 1173): ====
,I/wpa_supplicant( 1173): id=3
I/wpa_supplicant( 1173): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1173): freq=2412
I/wpa_supplicant( 1173): level=-79
I/wpa_supplicant( 1173): tsf=0000000284273934
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=Gonzos
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=4
I/wpa_supplicant( 1173): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-83
I/wpa_supplicant( 1173): tsf=0000000284273953
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC5999698
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=5
I/wpa_supplicant( 1173): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1173): freq=2437,
I/wpa_supplicant( 1173): level=-84
I/wpa_supplicant( 1173): tsf=0000000284273943
I/wpa_supplicant( 1173): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=UPC Wi-Free
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=6
I/wpa_supplicant( 1173): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1173): freq=2462
I/wpa_supplicant( 1173): level=-90
I/wpa_supplicant( 1173): tsf=0000000266023792
I/wpa_supplicant( 1173): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1173): ssid=UPC Wi-Free
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=7
I/wpa_supplicant( 1173): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1173): freq=2437
I/wpa_supplicant( 1173): level=-90
I/wpa_supplicant( 1173): tsf=0000000284273964,
I/wpa_supplicant( 1173): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1173): ssid=UPC4688432
I/wpa_supplicant( 1173): ====
I/wpa_supplicant( 1173): id=8
I/wpa_supplicant( 1173): bssid=64:7c:34:38:27:cc
I/wpa_supplicant( 1173): freq=2462
I/wpa_supplicant( 1173): le
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 284273883, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 284273923, distance: ?(cm), distanceSd: ?(cm)
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 284273934, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -83, frequency: 2437, timestamp: 284273953, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -84, frequency: 2437, timestamp: 284273943, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 266023792, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 6: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2437, timestamp: 284273964, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 7: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2462, timestamp: 284273983, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 8: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -91, frequency: 2437, timestamp: 266023813, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 9: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 284273911, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 10 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  6 [-83], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  67, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-90], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  67, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  0 [-91], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (10) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/jxcore-log( 4483): --= Surplus to requirements =--
I/jxcore-log( 4483): 
I/jxcore-log( 4483): ****TEST TOOK:  ms ****
I/jxcore-log( 4483): 
,I/jxcore-log( 4483): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4483): 
,D/CustomizationManager( 4795): ====startRecUseTime====
D/htc.customization.log.level( 4795):  is 
,W/CustomizationLogLevel( 4795): Level value is invalid, use default level 2
,D/CustomizationManager( 4795):  Read ACC file spent 0.108 (s)
D/CIDMapFileReader( 4795): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4795): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4795): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4795): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4795): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4795): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4795): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4795): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4795): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 4795): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4795): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4795): Parsing tag category name = system,
,I/CustomizationCIDLoader( 4795): Parsing tag category name = application
I/CustomizationCIDLoader( 4795): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4795): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4795): Parsing tag category name = AudioService
,I/CustomizationCIDLoader( 4795): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4795): Parsing tag category name = Settings
D/CustomizationManager( 4795):  Read CID file spent 0.160 (s)
,D/CustomizationManager( 4795):  All configurations done spent 0.160 (s),
,W/HtcNativeFlag( 4795): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4795): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4795): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 4795): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  907): deletePackageAsUser: pkg=com.test.thalitest, pid=4795, uid=2000 user=0
,I/ActivityManager(  907): Force stopping com.test.thalitest appid=10348 user=-1: uninstall pkg
,D/Process (  907): killProcessQuiet, pid=4483
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,W/ActivityManager(  907): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  907): Killing 4483:com.test.thalitest/u0a348 (adj 0): stop com.test.thalitest
I/ActivityManager(  907):   Force finishing activity ActivityRecord{42340ac0 u0 com.test.thalitest/.MainActivity t2}
,W/asset   (  907): Copying FileAsset 0x6323f8c0 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,W/InputDispatcher(  907): channel '4242aea8 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  907): channel '4242aea8 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  907): Attempted to unregister already unregistered input channel '4242aea8 com.test.thalitest.MainActivity (s)'
I/WindowManager(  907): WINDOW DIED Window{4242aea8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  907): Client connection lost with reason: 4
,W/PackageSettings(  907): Skipping PackageSetting{425ad4b0 com.example.hello/10356} due to missing metadata
,W/InputMethodManagerService(  907): Got RemoteException sending setActive(false) notification to pid 4483 uid 10348
,W/Binder  ( 1212): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1212): java.lang.NullPointerException
W/Binder  ( 1212): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1212): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1212): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1212): 	at dalvik.system.NativeStart.run(Native Method)
,I/ActivityManager(  907): Force stopping com.test.thalitest appid=10348 user=0: pkg removed
,D/DotMatrix( 1594): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1594): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1594): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/acms    ( 1918): Unregistering com.test.thalitest
E/acms    ( 1918): Could not unregister removed application com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver packageName:com.test.thalitest
,I/HtcKeyguardAppUpdateMonitor( 1119): ApplicationsIntentReceiver replacing:false
,I/dalvikvm-heap( 4220): Grow heap (frag case) to 15.214MB for 1821008-byte allocation
,W/GeofencerStateMachine( 1430): Ignoring removeGeofence because network location is disabled.
,D/PMS     (  907): acquireWL(439b8288): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1430 10028 null
W/AccTypeManager( 1331): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1331): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/PMS     (  907): releaseWL(439b8288): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/VoicemailCleanupService( 1288): Cleaning up data for package: com.test.thalitest
,W/SystemReader( 1261): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/Launcher( 1274): Deferring update until onResume
,D/Launcher( 1274): waitUntilResume // bindAppsRemoved
,D/PackageBroadcastService( 2229): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccTypeManager( 1331): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/ActivityManager(  907): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4811 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,W/Parcel  ( 1261): Reading a NULL string not supported here.
,E/ExternalAccountType( 1331): Unsupported attribute readOnly
I/InputMethodManagerService(  907): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,E/cutils-trace( 4795): Error opening trace file: No such file or directory (2)
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/MultiDex( 4811): install
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/ActivityManager(  907): Delaying start of: ServiceRecord{4441e6e8 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,D/PhoneApp( 1243): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,I/MultiDex( 4811): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4811): loading existing secondary dex files
,I/MultiDex( 4811): load found 1 secondary dex files
,I/MultiDex( 4811): install done
I/ActivityManager(  907): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4827 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/PeopleContactsSync( 2229): CP2 sync disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2229, uid=10028, userID:0
,I/Icing   ( 2229): doRemovePackageData com.test.thalitest
D/PMS     (  907): acquireWL(43a1c5e8): PARTIAL_WAKE_LOCK  Icing 0x1 2229 10028 null
,D/PMS     (  907): releaseWL(43a1c5e8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ProviderInstaller( 4811): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
,I/MultiDex( 4827): install
,I/MultiDex( 4827): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4827): loading existing secondary dex files
,I/MultiDex( 4827): load found 1 secondary dex files
,I/MultiDex( 4827): install done
,I/ProviderInstaller( 4827): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,I/ActivityManager(  907): Resuming delayed broadcast
,I/[PluginManager]RegisterService( 1407): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,I/[PluginManager]RegisterService( 1407): handle notify Blinkfeed plugin client changed
,D/Prism.PackageStateRece_( 1274): action: android.intent.action.PACKAGE_REMOVED
,D/Process (  907): killProcessQuiet, pid=4426
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4426:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4426
,I/IcingCorporaProvider( 2919): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4848 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,D/PMS     (  907): acquireWL(41ff9940): PARTIAL_WAKE_LOCK  Icing 0x1 2229 10028 null
,E/SQLiteLog( 2919): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 2919): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x63c4f778
D/PMS     (  907): releaseWL(41ff9940): PARTIAL_WAKE_LOCK  Icing 0x1 null
,E/SQLiteLog( 4811): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 4811): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5c9b2008
E/IcingCorporaProvider( 2919): Exception thrown from notifyTableChanged
E/IcingCorporaProvider( 2919): java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2919): 	at apg.a(PG:301)
E/IcingCorporaProvider( 2919): 	at apg.c(PG:222)
E/IcingCorporaProvider( 2919): 	at clo.b(PG:660)
E/IcingCorporaProvider( 2919): 	at clo.a(PG:651)
E/IcingCorporaProvider( 2919): 	at clo.g(PG:597)
E/IcingCorporaProvider( 2919): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/IcingCorporaProvider( 2919): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/IcingCorporaProvider( 2919): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/IcingCorporaProvider( 2919): 	at clp.Rl(PG:910)
E/IcingCorporaProvider( 2919): 	at clr.tL(PG:827)
E/IcingCorporaProvider( 2919): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/IcingCorporaProvider( 2919): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/IcingCorporaProvider( 2919): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/IcingCorporaProvider( 2919): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/IcingCorporaProvider( 2919): 	at android.os.Looper.loop(Looper.java:157)
E/IcingCorporaProvider( 2919): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/IcingCorporaProvider( 2919): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2919): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/IcingCorporaProvider( 2919): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/IcingCorporaProvider( 2919): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/IcingCorporaProvider( 2919): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/IcingCorporaProvider( 2919): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/IcingCorporaProvider( 2919): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/IcingCorporaProvider( 2919): 	at apa.a(PG:382)
E/IcingCorporaProvider( 2919): 	at apg.i(PG:325)
E/IcingCorporaProvider( 2919): 	at aph.call(PG:215)
E/IcingCorporaProvider( 2919): 	at apg.a(PG:299)
E/IcingCorporaProvider( 2919): 	... 15 more
W/IcingCorporaProvider( 2919): notifyTableChanged failed.
W/IcingCorporaProvider( 2919): Table change notification failed for TableStorageSpec[applications]
,I/IcingCorporaProvider( 2919): UpdateCorporaTask done [took 209 ms] updated apps [took 209 ms] 
,E/DriveAsyncService( 4811): disk I/O error (code 3850)
E/DriveAsyncService( 4811): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4811): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4811): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 4811): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4811): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4811): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 4811): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 4811): 	at ctj.c(SourceFile:904)
E/DriveAsyncService( 4811): 	at cva.h(SourceFile:1427)
E/DriveAsyncService( 4811): 	at cgv.a(SourceFile:15)
E/DriveAsyncService( 4811): 	at bzz.onHandleIntent(SourceFile:60)
E/DriveAsyncService( 4811): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/DriveAsyncService( 4811): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DriveAsyncService( 4811): 	at android.os.Looper.loop(Looper.java:157)
E/DriveAsyncService( 4811): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog( 4811): (3850) statement aborts at 5: [DELETE FROM ContentFileDeletionLock24] disk I/O error
,E/SQLiteDBG( 4811): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5c9b2008
E/DocListDatabase( 4811): Failed to delete from ContentFileDeletionLock24
E/DocListDatabase( 4811): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 4811): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 4811): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/DocListDatabase( 4811): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 4811): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 4811): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/DocListDatabase( 4811): 	at ctj.a(SourceFile:859)
E/DocListDatabase( 4811): 	at cva.k(SourceFile:1117)
E/DocListDatabase( 4811): 	at chr.<init>(SourceFile:45)
E/DocListDatabase( 4811): 	at chr.a(SourceFile:75)
E/DocListDatabase( 4811): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/DocListDatabase( 4811): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/DocListDatabase( 4811): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/DocListDatabase( 4811): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/DocListDatabase( 4811): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DocListDatabase( 4811): 	at android.os.Looper.loop(Looper.java:157)
E/DocListDatabase( 4811): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/DocListDatabase( 4811): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DocListDatabase( 4811): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DocListDatabase( 4811): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/DocListDatabase( 4811): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/DocListDatabase( 4811): 	at dalvik.system.NativeStart.main(Native Method)
,W/dalvikvm( 4811): threadid=1: thread exiting with uncaught exception (group=0x41a15e30)
,E/AndroidRuntime( 4811): FATAL EXCEPTION: main
E/AndroidRuntime( 4811): Process: com.google.android.gms.drive, PID: 4811
E/AndroidRuntime( 4811): java.lang.RuntimeException: Unable to create service com.google.android.gms.drive.api.ApiService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4811): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2883)
E/AndroidRuntime( 4811): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/AndroidRuntime( 4811): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/AndroidRuntime( 4811): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4811): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4811): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4811): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4811): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4811): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4811): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4811): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4811): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4811): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4811): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 4811): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4811): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4811): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 4811): 	at ctj.a(SourceFile:859)
E/AndroidRuntime( 4811): 	at cva.k(SourceFile:1117)
E/AndroidRuntime( 4811): 	at chr.<init>(SourceFile:45)
E/AndroidRuntime( 4811): 	at chr.a(SourceFile:75)
E/AndroidRuntime( 4811): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/AndroidRuntime( 4811): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/AndroidRuntime( 4811): 	... 10 more
E/ActivityManager(  907): App crashed! Process: com.google.android.gms.drive
,D/Process ( 4811): killProcess, pid=4811
,D/Process ( 4811): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop136.tmp: open failed: EROFS (Read-only file system)
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
,W/PackageManager(  907): Unable to load service info ResolveInfo{43f3d948 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,E/SQLiteDatabase( 4848): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4848): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4848): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4848): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4848): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4848): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4848): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4848): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4848): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4848): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4848): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4848): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4848): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4848): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4848): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4848): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4848): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4848): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4848): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4848): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4848): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4848): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4848): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4848): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4848): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4848): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4848): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4848): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4848): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4848): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4848): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4848): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4848): ,	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4848): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4848): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4848): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4848): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4848): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4848): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4848): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4848): 	,at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4848): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4848): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4848): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4848): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4848): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4848): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4848): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4848): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4848),: 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4848): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4848): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4848): 	,at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4848): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4848): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4848): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020),
E/SQLiteOpenHelper( 4848): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4848): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4848): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4848): 	at android.os.Handler.dispatchMessage(Handler.java:102),
E/SQLiteOpenHelper( 4848): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4848): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4848): 	at java.lang.reflect.Method.invokeNative(Native Method),
E/SQLiteOpenHelper( 4848): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4848): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4848): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4848): ,	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 4848): Opened ClientFlag.db in read-only mode
,E/SQLiteDatabase( 4848): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4848): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4848): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4848): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4848): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4848): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
,E/SQLiteDatabase( 4848): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4848): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4848): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4848): 	at aho.run(AbstractDatabaseInstance.java:455)
,W/dalvikvm( 4848): threadid=11: thread exiting with uncaught exception (group=0x41a15e30)
,E/ActivityManager(  907): App crashed! Process: com.google.android.apps.docs,
E/AndroidRuntime( 4848): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4848): Process: com.google.android.apps.docs, PID: 4848
,E/AndroidRuntime( 4848): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4848): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4848): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4848): ,	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4848): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4848): 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4848): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4848): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4848): ,	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4848): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4848): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
,E/AndroidRuntime( 4848): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4848): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4848): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164),
E/AndroidRuntime( 4848): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4848): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4848): 	at ahn.a(AbstractDatabaseInstance.java:437),
E/AndroidRuntime( 4848): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4848): ,	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  907): Can't write: system_app_crash,
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop137.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  907): ,	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  907): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  907): ,	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  907): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  907): 	,... 5 more
,D/Process ( 4848): killProcess, pid=4848
,I/ActivityManager(  907): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4869 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process ( 4848): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/ActivityManager(  907): Recipient 4848
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Process com.google.android.apps.docs (pid 4848) has died.
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 4811
,I/ActivityManager(  907): Process com.google.android.gms.drive (pid 4811) has died.
,W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.drive.api.ApiService in 1000ms
,D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  907): start
,W/AtomicFile(  907): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  907): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,W/ContextImpl( 4869): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,E/SQLiteDatabase( 4869): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4869): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4869): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4869): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4869): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4869): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4869): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4869): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4869): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4869): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4869): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4869): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4869): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4869): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4869): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4869): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4869): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4869): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4869): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 4869): threadid=10: thread exiting with uncaught exception (group=0x41a15e30)
,E/AndroidRuntime( 4869): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4869): Process: com.android.keychain, PID: 4869
E/AndroidRuntime( 4869): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4869): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4869): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4869): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4869): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4869): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4869): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4869): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4869): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4869): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4869): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4869): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4869): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4869): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4869): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4869): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4869): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4869): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4869): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ActivityManager(  907): App crashed! Process: com.android.keychain
I/ActivityManager(  907): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4883 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
,D/Process ( 4869): killProcess, pid=4869
,D/Process ( 4869): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452280672391.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  907): Recipient 4869
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.android.keychain (pid 4869) has died.
W/ActivityManager(  907): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10819ms
,D/AppTag  ( 4883): getInstance(Context context)
,D/AppTag  ( 4883): getInstance(Context context)
,D/AppTag  ( 4883): onCreate()
,I/dalvikvm-heap( 4220): Grow heap (frag case) to 16.950MB for 1821008-byte allocation
I/ActivityManager(  907): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4900 uid=10098 gids={50098, 3003, 5012}
,D/Process (  907): killProcessQuiet, pid=4442
D/PMS     (  907): acquireWL(4287d710): PARTIAL_WAKE_LOCK  AsyncService 0x1 4220 10160 null
D/PMS     (  907): releaseWL(4287d710): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  907): Killing 4442:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 4442,
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DeviceManagement( 4900): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4900 dbg=false s=true
,I/DeviceManagement( 4900): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
,I/DeviceManagement( 4900): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
,I/DeviceManagement( 4900): WorkflowService: Starting workflow service
I/DeviceManagement( 4900): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41e7a2f8] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4900): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4900): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
,I/DeviceManagement( 4900): PackageUpdateWorkflow: ==================================================
,I/DeviceManagement( 4900): ModelRegistry: Loading model meta data from resources...,
,I/ActivityManager(  907): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4915 uid=10099 gids={50099, 3003, 5012}
,I/DeviceManagement( 4900): BackgroundController: *** Processing package remove for appID=com.test.thalitest
,I/DeviceManagement( 4900): SessionStateController: Checking invariants...
,D/Documents( 4915): Loading roots for com.android.providers.downloads.documents
,E/SQLiteDatabase( 4915): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4915): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4915): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4915): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4915): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4915): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4915): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4915): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4915): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4915): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4915): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4915): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4915): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4915): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4915): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4915): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4915): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4915): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4915): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4915): 	at dalvik.system.NativeStart.main(Native Method)
,W/dalvikvm( 4915): threadid=1: thread exiting with uncaught exception (group=0x41a15e30)
,D/Documents( 4915): Loading roots for com.android.externalstorage.documents
E/AndroidRuntime( 4915): FATAL EXCEPTION: main
E/AndroidRuntime( 4915): Process: com.android.documentsui, PID: 4915
E/AndroidRuntime( 4915): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4915): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4915): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4915): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4915): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4915): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4915): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4915): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4915): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4915): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4915): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4915): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4915): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4915): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4915): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4915): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4915): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4915): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4915): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4915): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4915): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4915): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4915): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4915): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4915): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4915): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4915): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4915): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4915): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4915): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4915): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4915): 	... 10 more
,I/ActivityManager(  907): Killing 4526:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=4526
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  907): Recipient 4526
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/ActivityManager(  907): App crashed! Process: com.android.documentsui
,D/GCM     ( 1371): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  907): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4929 uid=10023 gids={50023, 1028, 1015, 1023}
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
,D/Process ( 4915): killProcess, pid=4915
,D/Process ( 4915): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452280672669.dbox_tmp: open failed: EROFS (Read-only file system)
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
,D/GCM     ( 1371): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  907): Recipient 4915
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1274): loadItems() com.htc.launcher.pageview.WidgetManager@41ed8f10 +
,I/Prism.WidgetManager( 1274): onLoadItems() +
,D/Process (  907): killProcessQuiet, pid=3969
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
I/ActivityManager(  907): Killing 3969:com.google.android.music:main/u0a154 (adj 15): empty #17
I/ActivityManager(  907): Process com.android.documentsui (pid 4915) has died.
,I/ActivityManager(  907): Recipient 3969
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  907): Client com.google.android.music (pid 3969): Died!
,D/ExternalStorage( 4929): After updating volumes, found 1 active roots
,E/SQLiteDatabase( 4900): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4900): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4900): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4900): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4900): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4900): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4900): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4900): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4900): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4900): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4900): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4900): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4900): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4900): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4900): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4900): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4900): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 4900): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 4900): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4900): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4900): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 4900): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 4900): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 4900): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 4900): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 4900): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4900): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4900): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4900): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 4900): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 4900): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 4900): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 4900): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 4900): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4900): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 4900): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 4900): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4900): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel,.java:176)
E/SQLiteDatabase( 4900): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 4900): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 4900): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4900): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4900): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4900): 	at java.lang.Thread.run(Thread.java:864)
I/DeviceManagement( 4900): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4900): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4900): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
I/ActivityManager(  907): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=4945 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4900): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4900): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4900): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4900): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4900): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4900): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4900): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4900): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4900): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4900): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4900): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4900): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4900): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4900): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4900): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4900): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4900): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 4900): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 4900): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 4900): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 4900): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 4900): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4900): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4900): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4900): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 4900): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 4900): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 4900): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
E/SQLiteDatabase( 4900): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
E/SQLiteDatabase( 4900): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 4900): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 4900): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4900): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4900): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4900): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DeviceManagement( 4900): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@41e7a2f8]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/DeviceManagement( 4900): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/DeviceManagement( 4900): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/DeviceManagement( 4900): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/DeviceManagement( 4900): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/DeviceManagement( 4900): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/DeviceManagement( 4900): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/DeviceManagement( 4900): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/DeviceManagement( 4900): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/DeviceManagement( 4900): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/DeviceManagement( 4900): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
W/DeviceManagement( 4900): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
W/DeviceManagement( 4900): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/DeviceManagement( 4900): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/DeviceManagement( 4900): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
W/DeviceManagement( 4900): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 4900): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 4900): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 4900): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 4900): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 4900): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 4900): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 4900): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 4900): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 4900): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 4900): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 4900): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 4900): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 4900): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 4900): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 4900): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 4900): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 4900): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 4900): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/DeviceManagement( 4900): WorkflowService: Stopping workflow service
,E/SQLiteDatabase( 4945): Failed to open database '/data/data/com.htc.task/databases/MyDB.db'.
E/SQLiteDatabase( 4945): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4945): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4945): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4945): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4945): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4945): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4945): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4945): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4945): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4945): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4945): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4945): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4945): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4945): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4945): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteDatabase( 4945): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteDatabase( 4945): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteDatabase( 4945): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteDatabase( 4945): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4945): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4945): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4945): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 4945): Couldn't open MyDB.db for writing (will try read-only):
E/SQLiteOpenHelper( 4945): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4945): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4945): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4945): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4945): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4945): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4945): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4945): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4945): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4945): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4945): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4945): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4945): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4945): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4945): 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
E/SQLiteOpenHelper( 4945): 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
E/SQLiteOpenHelper( 4945): 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
E/SQLiteOpenHelper( 4945): 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
E/SQLiteOpenHelper( 4945): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 4945): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4945): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4945): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/SQLiteOpenHelper( 4945): Opened MyDB.db in read-only mode
,D/Process (  907): killProcessQuiet, pid=4580
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4580:com.google.android.setupwizard/u0a78 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4580
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0

```
