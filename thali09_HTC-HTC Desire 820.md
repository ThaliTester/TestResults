#### Test 564317025f150b2_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/WifiDataStallTracker(  907): onReceive: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  907): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  907): updateDataStallInfo: mDataStallTxRxSum={txSum=130 rxSum=113} preTxRxSum={txSum=79 rxSum=65}
D/WifiDataStallTracker(  907): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  907): onDataStallAlarm: tag=21009 Sent 0 pkts since last received, < watchdogTrigger=5
--------- beginning of /dev/log/system
D/PMS     (  907): acquireWL(43496e30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{42cbd4c8: PendingIntentRecord{42442560 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=101372, Int=0
D/PMS     (  907): releaseWL(43496e30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/WifiDataStallTracker(  907): startDataStallAlarm: tag=21010 delay=15s
D/PMS     (  907): acquireWL(41b969c8): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(41b969c8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(437e4088): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(437e4088): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(430e5950): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(430e5950): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(426a1638): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(426a1638): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(43705c10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10074}
V/AlarmManager(  907): sending alarm PendingIntent{4252f3f0: PendingIntentRecord{4248ff60 com.android.vending startService}}, i=null, t=0, cnt=1, w=1453190745536, Int=0
D/PMS     (  907): releaseWL(43705c10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/Finsky  ( 4122): [434] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 4122): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
E/cutils-trace( 4515): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4515): ====startRecUseTime====
D/htc.customization.log.level( 4515):  is 
W/CustomizationLogLevel( 4515): Level value is invalid, use default level 2
V/LightsService(  907): setLight #0: color=#3c
D/CustomizationManager( 4515):  Read ACC file spent 0.058 (s)
D/CIDMapFileReader( 4515): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4515): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4515): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4515): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4515): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4515): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4515): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4515): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4515): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4515): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4515): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4515): Parsing tag category name = system
I/CustomizationCIDLoader( 4515): Parsing tag category name = application
I/CustomizationCIDLoader( 4515): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4515): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4515): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4515): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4515): Parsing tag category name = Settings
D/CustomizationManager( 4515):  Read CID file spent 0.098 (s)
D/CustomizationManager( 4515):  All configurations done spent 0.098 (s)
W/HtcNativeFlag( 4515): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4515): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4515): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4515): Fail to get flag for type 'language', use default value: -1
V/LightsService(  907): setLight #0: color=#39
V/LightsService(  907): setLight #0: color=#2f
W/CpuWake (  907): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  907): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4515
D/PMS     (  907): acquireHCC(434de5a0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 907 1000 null
D/PMS     (  907): acquireHCC(4350d720): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 907 1000 null
V/LightsService(  907): setLight #0: color=#2c
W/asset   (  907): Copying FileAsset 0x6c07c1f8 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  907): @test_code: getHtcIntentFlag: 0 obj: 1113570656
D/PMS     (  907): acquireWL(424f1610): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
I/FeedHostManager( 1274): [onPause]
I/FeedProviderManager( 1274): onPause
I/FeedHostManager( 1274): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@421539d0
I/SocialFeedProvider( 1274): +onPause
I/SocialFeedProvider( 1274): -onPause
V/LightsService(  907): setLight #0: color=#25
I/ActivityManager(  907): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4527 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1274): [trimMemory] 20
V/LightsService(  907): setLight #0: color=#1e
W/asset   ( 4527): Copying FileAsset 0x5c808c50 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/LightsService(  907): setLight #0: color=#18
V/WebViewChromiumFactoryProvider( 4527): Binding Chromium to main looper Looper (main, tid 1) {41a72370}
I/LibraryLoader( 4527): Expected native library version number "",actual native library version number ""
I/chromium( 4527): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4527): Initializing chromium process, renderers=0
W/System.err(  907): java.lang.Throwable: stack dump
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4308abc8:true
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4527): 1101561256: getState(). Returning 12
D/PMS     (  907): acquireWL(43197010): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  907): acquireWL(432516b8): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  907): releaseWL(43197010): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
V/LightsService(  907): setLight #0: color=#14
I/Adreno-EGL( 4527): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4527): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4527): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4527): Local Branch: 
I/Adreno-EGL( 4527): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4527): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4527):                  aa63bbd948f41d15fc72f585e
W/chromium( 4527): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4527): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4527): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4527): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4527): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4527): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4527): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4527): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4527): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4527): CordovaWebView is running on device made by: HTC
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  907):    returned true
,W/AwContents( 4527): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  907): Disable input method client, pid=1274
,W/ResourceType( 4527): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4527): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41ab9458, mServedView=org.apache.cordova.engine.SystemWebView{41a7f0c0 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1213): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
W/AwContents( 4527): nativeOnDraw failed; clearing to background color.
I/XT9_C   ( 1213): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1213): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1213): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,I/ActivityManager(  907): Displayed com.test.thalitest/.MainActivity: +288ms
I/InputMethodManagerService(  907): Enable input method client, pid=4527
D/PMS     (  907): releaseWL(424f1610): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4527): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4527): JniHelper::setJavaVM(0x41547048), pthread_self() = 1662496432
,D/JX-Cordova( 4527): jxcore cordova android initializing
,I/io.jxcore.node.ConnectionHelper( 4527): Build version SDK_INT: 19
,I/dalvikvm-heap( 4527): Grow heap (frag case) to 11.990MB for 42652-byte allocation
,I/dalvikvm-heap( 4527): Grow heap (frag case) to 12.090MB for 95956-byte allocation
,I/dalvikvm-heap( 4527): Grow heap (frag case) to 12.172MB for 143930-byte allocation
,I/dalvikvm-heap( 4527): Grow heap (frag case) to 12.290MB for 215890-byte allocation
,I/dalvikvm-heap( 4527): Grow heap (frag case) to 12.462MB for 323830-byte allocation
,D/WIFI_ICON( 1118): WifiActivity: 0
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/dalvikvm-heap( 4527): Grow heap (frag case) to 12.724MB for 485740-byte allocation
,I/dalvikvm-heap( 4527): Grow heap (frag case) to 13.666MB for 1092904-byte allocation
,I/dalvikvm-heap( 4527): Grow heap (frag case) to 14.626MB for 1639352-byte allocation
,I/dalvikvm-heap( 4527): Grow heap (frag case) to 15.947MB for 2459024-byte allocation
,W/CpuWake (  907): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  907): <<release mCpuPerf_Freq wakelock
,D/PMS     (  907): releaseHCC(434de5a0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  907): releaseHCC(4350d720): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4527): Grow heap (frag case) to 18.061MB for 3688532-byte allocation
,D/WIFI_ICON( 1118): WifiActivity: 1
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/jxcore-log( 4527): Initializing JXcore engine
,W/jxcore-log( 4527): JXcore engine is ready
,W/jxcore-log( 4527): Starting JXcore engine
,W/jxcore-log( 4527): Platform android
W/jxcore-log( 4527): 
,W/jxcore-log( 4527): Process ARCH arm
W/jxcore-log( 4527): 
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{425116c0 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  907): releaseWL(432516b8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 96
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WiFioffload: SignalStrength: =97
,I/jxcore-log( 4527): JXcore Cordova bridge is ready!
I/jxcore-log( 4527): 
,W/jxcore-log( 4527): JXcore engine is started
,D/WifiNative-wlan0(  907):    returned true
D/WIFI_ICON( 1118): WifiActivity: 0
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/chromium( 4527): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4527): Toggling radios to true
I/jxcore-log( 4527): 
,D/BluetoothAdapter( 4527): enable(): BT is already enabled..!
,D/WifiManager( 4527): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
W/HtcDLNAServiceManager(  907): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  907): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  907): Settings:Agentvalue: 2
W/Settings:Agent(  907): >> traceCallingStack()
W/Settings:Agent(  907): Process.myPid(): 907
W/Settings:Agent(  907): Process.myTid(): 1103
W/Settings:Agent(  907): Process.myUid(): 1000
W/Settings:Agent(  907): 
W/Settings:Agent(  907): 
W/System.err(  907): java.lang.Throwable: stack dump
,W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  907): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  907): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  907): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  907): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  907): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  907): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
,W/System.err(  907): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  907): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  907): 
,W/Settings:Agent(  907): << traceCallingStack(): 1(ms)
,D/WifiManager( 4527): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiService(  907): New client listening to asynchronous messages
D/WifiService(  907): setWifiEnabled: true pid=4527, uid=10389
E/WifiService(  907): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  907): isSprintWifiRestricted(): false
I/WifiService(  907): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  907): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true,
D/WifiNative-wlan0(  907): doBoolean: DISCONNECT
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
D/WifiManager( 4527): reconnect: Base Package Name=com.test.thalitest, uid=10389
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): TDLS: Tear down peers
,I/wpa_supplicant( 1161): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4527): Radios toggled
I/jxcore-log( 4527): 
I/jxcore-log( 4527): My device name is: HTC-HTC Desire 820
I/jxcore-log( 4527): 
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1161): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1161): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,I/wpa_supplicant( 1161): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  907): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1161): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1161): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1161): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1161): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1161): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb70aebc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1161):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1161): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1161): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1161): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1161): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1161): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1161): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1161): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1161): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1161): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1161): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1161): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1161): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1161): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1161): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1161): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1161): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
,D/wpa_supplicant( 1161): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1161): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1161): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1161): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1161): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1161): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1161): nl80211: Ignore disconnect event triggered during reassociation
,D/HTCRequest(  907): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  907): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  907): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/WifiNative-wlan0(  907):    returned true
D/WifiPerfLock(  907): release()
D/WifiStateMachine(  907): PerfLock released for exiting ConnectedState
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
,D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
,D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
D/Tethering(  907): [isWifi] getHotspotEnabled: false
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1161): Power_Mode_Type mode = 0
I/wpa_supplicant( 1161): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2,
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  907): acquireWL(4369b578): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 907 1000 null
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/DhcpStateMachine(  907): [RunningState] Stop DHCP
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  907): doBoolean: RECONNECT
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025250
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025277
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025300
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026675
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026692
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): Fast associate: Old scan results
I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=21010 mDataStallAlarmIntent=PendingIntent{4431e378: PendingIntentRecord{42442560 android broadcastIntent}}
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): Enter handleNetworkDisconnect
,I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025250
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025277
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025300
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026675
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026692
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  907): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  907): Provision feature enable=false
,D/ConnectivityService(  907): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1161): Power_Mode_Type mode = 0
I/wpa_supplicant( 1161): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
D/UsbnetStateTracker(  907): isAvailable+-
D/UsbnetStateTracker(  907): reconnect
,D/UsbnetStateTracker(  907): isAvailable+-
,D/WISPrService( 3827): >>>>>WISPrService start isConnected = false<<<<<
D/WifiP2pService(  907): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  907): default: reconnect()
D/MDST    (  907): default: setTeardownRequested(false)
D/MDST    (  907): default: setEnableApn apnType =default , enable=true
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  907): Exit handleNetworkDisconnect
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  907): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  907): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiService(  907): New client listening to asynchronous messages
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  907): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 3827): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,V/NativeCrypto( 1363): Read error: ssl=0x5ca43d20: I/O error during system call, Connection timed out
,D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  907): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/ConnectivityService(  907): resetConnections(wlan0, 3)
D/PMS     (  907): acquireWL(434eca28): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/ConnectivityService(  907): flush DNS cache for net 1(wlan0)
V/NativeCrypto( 1363): SSL shutdown failed: ssl=0x5ca43d20: I/O error during system call, Broken pipe
D/libc    (  364): [NET] entry_id:3   entry:0xb74e6220  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb74e5fd8  removed 
D/libc    (  364): [NET] entry_id:5   entry:0xb74e62f8  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb74e6428  removed 
D/libc    (  364): [NET] entry_id:6   entry:0xb74e1f68  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb74e60e8  removed 
D/libc    (  364): [NET] entry_id:7   entry:0xb74e2110  removed 
,D/libc    (  364): *************************,
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024549,
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025250
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025277
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025300
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026675
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026692
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1363/10029)
,D/WISPrService( 3827): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 3827): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false,
D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:1
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  907): reportInetCondition for net -1, percentage: 0 by  (1363/10029)
D/PMS     (  907): acquireWL(43e39070): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1363/10029)
D/ConnectivityService(  907): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/PMS     (  907): releaseWL(434eca28): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/WifiStateMachine(  907): startScan Pid: 907 Uid 1000
,D/WifiNative-wlan0(  907): doBoolean: SCAN
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1161): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  907):    returned false
D/BatSI   (  907): WIFI scan started for: 650a0300 uid:1000
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1363/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1363/10029)
I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2),
D/PMS     (  907): releaseWL(43e39070): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  907): mActiveDefaultNetwork: -1
,I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:0
D/ConnectivityService(  907): handleInetConditionChange: no active default network - ignore
,I/SensorManager(  907): mEventCount = 1200
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/Tethering(  907): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  907): bSetPropertyMultiRAB:false
,D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
,I/Tethering(  907): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  907): ipv4Default null
,I/Tethering(  907): No IPv4 upstream interface, giving up.
,D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: false
,I/NetworkMonitor( 3907): type=WIFI subType= reason=null isConnected=false
,I/ConnectivityHelper( 1274): [onReceive] WIFI(1): DISCONNECTED
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/CaptivePortalTracker(  907): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  907): NoActiveNetworkState
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (3907/10154)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1606/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1227/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1274/10076)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1227/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4324/10100)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(43b0f1a0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025250
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025277
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025300
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026675
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026692
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4324/10100)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (2449/10021)
,I/ActivityManager(  907): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4579 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4579): ACRA is enabled for com.facebook.katana, intializing...
D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  907): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
D/ACRA    ( 4579): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
D/ACRA    ( 4579): Looking for error files in /data/data/com.facebook.katana/app_minidumps
D/PMS     (  907): releaseWL(43b0f1a0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/SystemClassLoaderAdder( 4579): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4579): Preparing secondary program dexes.
V/DexLibLoader( 4579): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4579): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4579): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4579): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
V/DexLibLoader( 4579): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
W/DexLibLoader( 4579): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4579): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4579): Dex already copied
D/OdexVerifier( 4579): Odex verification is skipped.
,V/DexLibLoader( 4579): Creating class loader
,V/DexLibLoader( 4579): Finished creating class loader
V/DexLibLoader( 4579): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4579): Dex already copied
D/OdexVerifier( 4579): Odex verification is skipped.,
V/DexLibLoader( 4579): Creating class loader
,V/DexLibLoader( 4579): Finished creating class loader
V/DexLibLoader( 4579): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4579): Dex already copied
D/OdexVerifier( 4579): Odex verification is skipped.
,V/DexLibLoader( 4579): Creating class loader
,V/DexLibLoader( 4579): Finished creating class loader
V/DexLibLoader( 4579): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4579): Dex already copied
D/OdexVerifier( 4579): Odex verification is skipped.,
V/DexLibLoader( 4579): Creating class loader
V/DexLibLoader( 4579): Finished creating class loader
,V/DexLibLoader( 4579): Verifying classes from secondary dexes.
,D/DexLibLoader( 4579): DexLibLoader.ensureDexLoaded took 16 ms
,W/dalvikvm( 4579): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4579): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4579): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4579): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4579): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4579): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4579): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1161): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1161): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1161): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 3
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 1
I/wpa_supplicant( 1161): wpa_s->is_screen_on 1
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): selected network = 1
D/wpa_supplicant( 1161): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb70b04e8  current_ssid=0x0
D/wpa_supplicant( 1161): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1161): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1161): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1161): check if in concurrent case
,I/wpa_supplicant( 1161): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz),
D/wpa_supplicant( 1161): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1161): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1161): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1161): RSN: PMKSA cache search - network_ctx=0xb70b04e8 try_opportunistic=0
D/wpa_supplicant( 1161): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1161): RSN: No PMKSA cache entry found,
I/wpa_supplicant( 1161): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1161): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1161): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1161): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1161): nl80211: Unsubscribe mgmt frames handle 0xb70af718 (mode change),
D/wpa_supplicant( 1161): nl80211: Subscribe to mgmt frames with non-AP handle 0xb70af718
D/wpa_supplicant( 1161): nl80211: Register frame type=0xd0 nl_handle=0xb70af718
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1161): nl80211: Register frame type=0xd0 nl_handle=0xb70af718
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1161): nl80211: Register frame type=0xd0 nl_handle=0xb70af718
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 58,
D/wpa_supplicant( 1161): nl80211: Register frame type=0xd0 nl_handle=0xb70af718
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1161): nl80211: Register frame type=0xd0 nl_handle=0xb70af718
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1161): nl80211: Register frame type=0xd0 nl_handle=0xb70af718
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1161): nl80211: Register frame type=0xd0 nl_handle=0xb70af718,
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1161): nl80211: Register frame type=0xd0 nl_handle=0xb70af718
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1161): nl80211: Register frame type=0xd0 nl_handle=0xb70af718
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1161): nl80211: Register frame type=0xd0 nl_handle=0xb70af718
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1161): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1161):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1161):   * freq=2412
,D/wpa_supplicant( 1161):   * Auth Type 0
D/wpa_supplicant( 1161):   * WPA Versions 0x2
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1161): nl80211: Connect request send successfully
D/wpa_supplicant( 1161): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1161): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1161): EAPOL: External notification - portControl=Auto
,D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1161): reply (489) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000108041003
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000108041019
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2427
I/wpa_supplicant( 1161): level=-79
I/wpa_supplicant( 1161): tsf=0000000108041024
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=3
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-58
I/wpa_supplicant( 1161): tsf=0000000108041014
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 108041003, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 108041019, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 108041024, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2412, timestamp: 108041014, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
D/BatSI   (  907): WIFI scan stopped for: 640a0300 uid:1000
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiManager( 1227): getScanResults enter 
,D/WifiStateMachine(  907): == begin of scan result ==
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/dalvikvm( 4579): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1161): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1161): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1161): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 1161): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1161): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1161): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1161): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1161): nl80211: Connect event
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1161): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1161): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1161): Add randomness: count=10 entropy=4
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1161): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1161): TDLS: Remove peers on association
D/wpa_supplicant( 1161): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1161): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1161): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1161): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1161): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1161): EAPOL: enable timer tick
D/wpa_supplicant( 1161): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1161): htc_wext_set_keepalive +
I/wpa_supplicant( 1161): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1161): getPrivFuncNum +	
I/wpa_supplicant( 1161): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1161): htc_wext_set_keepalive fnum = 0x8bf6
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
I/wpa_supplicant( 1161): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1161): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1161): Get randomness: len=32 entropy=5
D/WifiMonitor(  907): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  907): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  907): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  907): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  907): handleAssociatedWithEvent. bLFR =false
D/,WifiMonitor(  907): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
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
W/dalvikvm( 4579): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  907): This record is existed, only update it...
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/Tethering(  907): interfaceStatusChanged wlan0, true
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/Tethering(  907): [isWifi] getHotspotEnabled: false
I/wpa_supplicant( 1161): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb70af9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1161):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1161): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1161): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6efeb4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1161):    broadcast key
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1161): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1161): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1161): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1161): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  907): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1161): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1161): set send_ind_to_ndc = 0
I/wpa_supplicant( 1161): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1161): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1161): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1161): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1161): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1161): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1161): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1161): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1161): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1161): EAPOL authentication completed successfully
I/wpa_supplicant( 1161): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1161): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1161): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1161): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
D/Tethering(  907): interfaceStatusChanged wlan0, true
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/WifiStateMachine(  907): fetchFrequency(), freq = 2412
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  907): This record is existed, only update it...
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WISPrService( 3827): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WISPrService( 3827): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiApDatabaseHandler(  907): updateConnectedAP...
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025250
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025277
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025300
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026675
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026692
D/DhcpStateMachine(  907): [StoppedState] Start DHCP
D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 1
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
D/WifiStateMachine(  907): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  907): acquireWL(42fbef58): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 907 1000 null
,D/WifiStateMachine(  907): handlePreDhcpSetup mBluetoothConnectionActive: false
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1161): Power_Mode_Type mode = 1
I/wpa_supplicant( 1161): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  907):    returned null
E/WifiStateMachine(  907): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  907):    returned null
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4243d090 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4243d090 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:0
,E/FbInjectorInitializer( 4579): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4579): Verify
,D/WifiService(  907): New client listening to asynchronous messages
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4579): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4579): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4579): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  907): killProcessQuiet, pid=1319
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 1319:com.htc.sense.hsp/u0a55 (adj 15): empty #17
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,W/fb4a(:<default>):UserScope( 4579): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4579): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4579): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 1319
,I/BroadcastQueue(  907): Schedule to resend BroadcastRecord{436a6b90 u-1 android.net.conn.CONNECTIVITY_CHANGE callingPid=907 callingUid=1000} for ResolveInfo{434dd270 com.htc.sense.hsp/.weather.location.AutoSettingReceiver m=0x108000} of com.htc.sense.hsp
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4579): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  907): Start proc com.htc.sense.hsp for broadcast com.htc.sense.hsp/.weather.location.AutoSettingReceiver: pid=4629 uid=10055 gids={50055, 1023, 3003, 5012}
,E/dalvikvm( 4579): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4579): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4579): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4579): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4579): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4579): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4579): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4579): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4579): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4579): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4579): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4579): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4579): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4579): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4579): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4579): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4579): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4579): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1161): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1161): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  907):    returned true
,D/WifiStateMachine(  907): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  907): releaseWL(42fbef58): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [1][0][0]
I/wpa_supplicant( 1161): Change stage from stage0 to stage3
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
D/WIFI_ICON( 1118): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  907):    returned true
I/dalvikvm-heap( 4579): Grow heap (frag case) to 9.963MB for 84664-byte allocation
D/WifiStateMachine(  907): gateway: /192.168.1.1
D/WifiNative-wlan0(  907): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1161): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1161): wlan0: Background scan every 600 seconds
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  907): VerifyingLinkState enter
D/WifiStateMachine(  907): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  907): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  907): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -57, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=21012 delay=15s
,I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiWatchdogStateMachine(  907): WAN detection
V/NetworkPolicy(  907): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
,D/WISPrService( 3827): >>>>>WISPrService start isConnected = true<<<<<
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  907): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  907): syncGetConfiguredNetworks
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  907): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  907): default: teardown()
D/MDST    (  907): default: setTeardownRequested(true)
D/MDST    (  907): default: setEnableApn apnType =default , enable=false
D/MDST    (  907): default: setTeardownRequested(true)
D/ConnectivityService(  907): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  907): Unexpected mtu value: android.net.wifi.WifiStateTracker@423fcd20
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  907): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WIFI_ICON( 1118): WifiActivity: 1
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/ConnectivityService(  907): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  907): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
,I/dalvikvm-heap( 4579): Grow heap (frag case) to 9.991MB for 39954-byte allocation
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  907): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  907): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
,D/PMS     (  907): acquireWL(4364a570): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
D/WirelessDisplayService(  907): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  907):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,I/QuickSettingWifi( 1118): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
,D/PluginProvider( 4629): PluginProvider onCreate
,D/PluginProvider( 4629): current plugin count: 18
,D/HtcAppUPService( 4629): HtcUPDataProvider onCreate()
,I/dalvikvm-heap( 4579): Grow heap (frag case) to 10.017MB for 28144-byte allocation
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  907): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(4364a570): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/dalvikvm-heap( 4579): Grow heap (frag case) to 10.094MB for 79892-byte allocation
,D/AutoSetting( 4629): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  907): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4656 uid=10079 gids={50079, 3003, 5012}
,D/Process (  907): killProcessQuiet, pid=4324
,I/ActivityManager(  907): Killing 4324:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (4629/10055)
,D/AutoSetting( 4629): service - onCreate()
,D/AutoSetting( 4629): service - AddressCache: using context: com.htc.Weather
D/AutoSetting( 4629): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/LocationManagerService(  907): request 4228e330 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/LocationManagerService(  907): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 4629): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 4629): service - requestNLP() NetworkLocationProvider not enabled
,D/AutoSetting( 4629): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 4629): service - handleMessage() setting current location null
D/AutoSetting( 4629): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 4629): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (4629/10055)
,D/MobileConnectivityChangeReceiver( 4656): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4656): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4656): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4656): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/dalvikvm-heap( 4579): Grow heap (frag case) to 10.281MB for 75760-byte allocation
,I/ActivityManager(  907): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4673 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4656/10079)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4656/10079)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4656/10079)
,W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4347c140 u0 ReceiverList{42c370e8 4579 com.facebook.katana/10027/u0 remote:42c36700}}
,W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4347c140 u0 ReceiverList{42c370e8 4579 com.facebook.katana/10027/u0 remote:42c36700}}
,I/ActivityManager(  907): Recipient 4324
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{425f7e08 u0 ReceiverList{425f7da8 4579 com.facebook.katana/10027/u0 remote:4367f978}}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025250
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025277
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025300
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026675
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026692
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
,D/wpa_supplicant( 1161): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1161): EAPOL: disable timer tick
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/Process (  907): killProcessQuiet, pid=4347
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4687 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
I/ActivityManager(  907): Killing 4347:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4347
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(42c36ff0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024549
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025250
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025277
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025300
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026675
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026692
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
,D/PMS     (  907): acquireWL(44353430): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2174): Checkin interval check for package: unspecified last checkin: 1453190708759 min interval config: 0 actual interval: 44475
D/PMS     (  907): releaseWL(42c36ff0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2174): Checking schedule, now: 1453190753241 next: 1453190738724
,I/CheckinService( 2174): active receiver: enabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2174, uid=10029, userID:0
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
I/CheckinService( 2174): Preparing to send checkin request
,I/EventLogService( 2174): Accumulating logs since 1453190704365
,W/ContextImpl( 4687): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
I/jxcore-log( 4527): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 4527): 
,W/ContextImpl( 4687): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4687): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4687): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4687): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/CheckinRequestBuilder( 2174): Checkin reason type: 8 attempt count: 1
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
I/ActivityManager(  907): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2174): Failed to find provider info for com.google.android.wearable.settings
,D/PMS     (  907): acquireWL(44268ae8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(44268ae8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/PMS     (  907): Going to sleep due to screen timeout...
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421c2908
,W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = CM36282 Light sensor
I/ActivityManager(  907): mThumbnailWidth=360, mThumbnailHeight=640
V/LightsService(  907): setLight #2: color=#0
W/BatSI   (  907): Couldn't get kernel wake lock stats
D/qdlights(  907): set_light_buttons_func: on=0 brightness=0
,V/LightsService(  907): setLight #0: color=#0
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421c2908, eanble = 0, strlen(mName) = 59
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  907): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41ee0788
W/SensorService(  907): Listener[1] = com.htc.smartdim.sensor_eye@41bb1268
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system,
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4579): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,W/PMS     (  907): mWirelessDisplayManager is null
D/WirelessDisplayService(  907): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4579): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4687/10151)
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (2174/10029)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,V/GLSActivity( 1363): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1363): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SurfaceControl(  907): Excessive delay in blankDisplay() while turning screen off: 315ms
D/NfcService( 1259): ScreenObserver: OFF
,D/NfcService( 1259): applyRouting - 0
,V/KeyguardServiceDelegate(  907): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@4241b1c8)
D/PMS     (  907): nativeSetInteractive:false
D/PMS     (  907): nativeSetInteractive:false done
D/PMS     (  907): nativeSetAutoSuspend:true
D/PMS     (  907): nativeSetAutoSuspend:true done
D/HABCtrl (  907): TPE algorithm. remove timeout.
D/PMS     (  907): OOBE c monitor 11
I/InputMethodManagerService(  907): screenObserver, isScreenOn=false
I/InputMethodManagerService(  907): Disable input method client, pid=4527
D/PMN     (  907): wakingUp
V/WebViewChromiumFactoryProvider( 4687): Binding Chromium to main looper Looper (main, tid 1) {41a77240}
,D/NfcService( 1259): applyRouting -2
I/LibraryLoader( 4687): Expected native library version number "",actual native library version number ""
,I/chromium( 4687): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4687): Initializing chromium process, renderers=0
,V/KeyguardServiceDelegate(  907): **** SHOWN CALLED ****
D/PMS     (  907): acquireWL(42455a60): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1259 1027 null
D/PMS     (  907): releaseWL(42455a60): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/InputManager(  907): Cancel all due to getting PMS screen off broadcast
D/WirelessDisplayService(  907): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  907): acquireWL(42211990): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/WindowManager(  907): No lock screen! windowToken=null
I/BatteryService(  907): n_update end
D/PMN     (  907): onScreenOn
D/PMS     (  907): releaseWL(42211990): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
,D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1118): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): acquireWL(43669488): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  907): acquireWL(4375f510): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PMS     (  907): releaseWL(43669488): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,D/MtpService( 2449): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2449): [MTP][onReceive]-
,D/NfcService( 1259): applyRouting - 0
I/ActivityManager(  907): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4712 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,E/AudioManagerAndroid( 4687): BLUETOOTH permission is missing!
,D/NfcService( 1259): applyRouting -2
D/PMS     (  907): acquireWL(424e6c10): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1259 1027 null
D/PMS     (  907): releaseWL(424e6c10): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=21013 delay=15s
,D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1161): SET_SCREEN_ON:On
I/wpa_supplicant( 1161): htc_wext_set_keepalive +
I/wpa_supplicant( 1161): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1161): getPrivFuncNum +	
I/wpa_supplicant( 1161): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1161): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1161): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1161): BG scan when screen On
I/wpa_supplicant( 1161): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1161): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): Match BG scan, scan!
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  907):    returned true
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AlarmManager(  907): ACTION_SCREEN_ON
I/AlarmManager(  907): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done recovering
I/AlarmManager(  907): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done EPS screen off alarm recovering
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025250
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025277
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025300
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026675
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026692
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,I/ClockThread( 1118): stop update clock
I/Adreno-EGL( 4687): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4687): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4687): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4687): Local Branch: 
I/Adreno-EGL( 4687): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4687): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4687):                  aa63bbd948f41d15fc72f585e
,V/SRS_Proc(  371): ParamSet string: screen_state=on
D/WIFI_ICON( 1118): WifiActivity: 3
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,W/dalvikvm( 4712): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4712): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4712): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4712): install
,I/MultiDex( 4712): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
D/NetworkPolicy(  907): updateScreenOn: false
,I/MultiDex( 4712): loading existing secondary dex files
,I/MultiDex( 4712): load found 3 secondary dex files
,I/MultiDex( 4712): install done
,I/jxcore-log( 4527): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 4527): 
,I/jxcore-log( 4527): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 4527): 
,I/NSApplication( 4687): Starting up...
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4687/10151)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4687/10151)
,D/PMS     (  907): acquireWL(426882f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 4712): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4712): VFY: unable to resolve instance field 36
,W/dalvikvm( 4712): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/PMS     (  907): releaseWL(426882f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,V/JNIHelp ( 4712): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  907): acquireWL(442c2020): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4095/10160)
,D/Process (  907): killProcessQuiet, pid=4311
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/jxcore-log( 4527): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 4527): 
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4095/10160)
I/ActivityManager(  907): Killing 4311:com.htc.cs.dm/u0a98 (adj 15): empty #17
,D/PMS     (  907): releaseWL(442c2020): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1790): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1790): onScreenOn: 1453190753860
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1790): onScreenOn: 1453190753860
D/PMS     (  907): releaseWL(4369b578): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
D/ConnectivityService(  907): NetTransition Wakelock for ConnectedState released by timeout
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
I/ActivityManager(  907): Recipient 4311
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41ee0788
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41ee0788, eanble = 0, strlen(mName) = 91
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  907): Listener[0] = com.htc.smartdim.sensor_eye@41bb1268
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  907): goingToSleep
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
D/PMS     (  907): acquireWL(436916b8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 907 1000 null
,I/jxcore-log( 4527): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 4527): 
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/jxcore-log( 4527): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 4527): 
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025250
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025277
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025300
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026675
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026692
,I/jxcore-log( 4527): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 4527): 
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: true
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1606/10029)
,D/AutoSetting( 4629): receiver - intent: android.intent.action.USER_PRESENT
,I/NetworkMonitor( 3907): type=WIFI subType= reason=null isConnected=true
,D/CaptivePortalTracker(  907): NoActiveNetworkState
,I/ConnectivityHelper( 1274): [onReceive] WIFI(1): CONNECTED
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1227/10029)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (3907/10154)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1274/10076)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4656/10079)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/PMS     (  907): acquireWL(43729de8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1227/10029)
D/AccTypeManager( 1341): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,V/Tethering(  907): bSetPropertyMultiRAB:false
,D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,I/Tethering(  907): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  907): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
,I/Tethering(  907): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
,I/Tethering(  907): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  907): Found interface wlan0
,D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
D/TetherSettings( 3827): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3827): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3827): Cust_ConnectToPC   : Modem_Link>false
,D/        ( 3827): Cust_ConnectToPC   : spcsc>false
,I/ProviderInstaller( 4712): Installed default security provider GmsCore_OpenSSL
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1363/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(41c3f030): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.musicenhancer (3930/10053)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1363/10029)
D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
,D/AutoSetting( 4629): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/        ( 3827): Cust_ConnectToPC   : IPT>true
D/        ( 3827): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3827): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3827): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3827): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3827): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  907): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
,I/PSReceiver( 3827): onReceive:android.intent.action.USER_PRESENT
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1606/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025250
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025277
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025300
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026675
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026692
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
D/PMS     (  907): releaseWL(41c3f030): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  907): releaseWL(43729de8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025250
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025277
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025300
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026675
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026692
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
W/ContextImpl( 3827): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=21013 mDataStallAlarmIntent=PendingIntent{43bad3a8: PendingIntentRecord{42442560 android broadcastIntent}}
I/SmartNS_PSService( 3827): onReceive:android.intent.action.USER_PRESENT
,W/Settings( 3827): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3827):  defaultType:0
,D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 0
W/AccTypeManager( 1341): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1341): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/AlarmManager(  907): ACTION_SCREEN_OFF
I/AlarmManager(  907): [AlarmQueuing] screen off now: 
I/AlarmManager(  907): [AlarmQueuing] data connection: true
I/AlarmManager(  907): [AlarmQueuing] wifi connection: true
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025250
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025277
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025300
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026675
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026692
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
D/PMS     (  907): acquireWL(436a1738): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 907 1000 null
,E/ExternalAccountType( 1341): Unsupported attribute readOnly
,W/dalvikvm( 4712): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4712): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,W/dalvikvm( 4712): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4712): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4712): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4712): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4712): Link of class 'Lcom/google/android/gms/common/j/c;' failed
I/ActivityManager(  907): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4752 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/NativeLibraryUtils( 4712): Install completed successfully. count=14 extracted=0
,I/WVCdm   (  371): Level3 Library Nov 20 2013 18:09:31
W/ContextImpl( 4752): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,W/WVCdm   (  371): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,D/SmartSyncUtils( 4752): isEpsOn(), nState = 0
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
D/PMS     (  907): acquireWL(44298e88): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4752 1000 null
,D/SmartSyncUtils( 4752): getMobilePolicyEnabled, result = true
D/PMS     (  907): releaseWL(44298e88): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/Process (  907): killProcessQuiet, pid=4365
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4365:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4365
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WVCdm   (  371): PrepareKeyRequest: nonce=1716380380
,I/WVCdm   (  371): CdmEngine::CloseSession
,W/ActivityManager(  907): Activity pause timeout for ActivityRecord{43247508 u0 com.test.thalitest/.MainActivity t2}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (4712/10029)
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1161): SET_SCREEN_ON:Off
I/wpa_supplicant( 1161): htc_wext_set_keepalive +
I/wpa_supplicant( 1161): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1161): getPrivFuncNum +	
I/wpa_supplicant( 1161): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1161): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1161): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1161): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1161): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
,D/WifiStateMachine(  907): BroadcastRSSIForIMS, newrssi =-57 , oldRssi= -200
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
D/WIFI_ICON( 1118): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1161): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
V/SRS_Proc(  371): ParamSet string: screen_state=off
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!,
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL,
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (2449/10021)
,D/NetworkPolicy(  907): updateScreenOn: false
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ContactMessageStore( 1247): start background delete task...
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/ContactMessageStore( 1247): size: 0 , 0
D/ContactMessageStore( 1247): Background delete complete
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(436a1738): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,I/jxcore-log( 4527): Test app app.js loaded
I/jxcore-log( 4527): 
,I/Choreographer( 4527): Skipped 289 frames!  The application may be doing too much work on its main thread.
,D/AutoSetting( 4629): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4656): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4656): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 4629): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 4629): service - onStartCommand() screen is off, don't request location
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (4629/10055)
D/AutoSetting( 4629): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 4629): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (4629/10055)
,W/ResourceType( 4527): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4527): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41a7f0c0 VFEDH.C. .F....ID 0,0-720,1134 #64}
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4687/10151)
D/PMS     (  907): acquireWL(43a08a68): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
,I/chromium( 4527): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/PMS     (  907): releaseWL(43a08a68): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(436916b8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1595): [EventService] getTotalRam: 1873 Mb
D/PMS     (  907): acquireWL(4377ec60): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(4377ec60): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4095/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4095/10160)
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1790): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1790): onScreenOff
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1790): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1790): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1790): onScreenOff
,I/CheckinService( 2174): Checkin interval check for package: unspecified last checkin: 1453190708759 min interval config: 0 actual interval: 45946
,I/Adreno-EGL( 4712): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4712): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4712): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4712): Local Branch: 
I/Adreno-EGL( 4712): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4712): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4712):                  aa63bbd948f41d15fc72f585e
D/PMS     (  907): acquireWL(436d7338): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(436d7338): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
D/AutoSetting( 4629): service - mHandler: cancel location update
D/AutoSetting( 4629): service -           changes count: 0
I/dalvikvm-heap( 4095): Grow heap (frag case) to 13.501MB for 1821008-byte allocation
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2174, uid=10029, userID:0
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1363/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1363/10029)
,D/WearableService( 1227): callingUid 10029, callindPid: 1227
,D/LocationInitializer( 2174): Restart initialization of location
,D/AuthorizationBluetoothService( 1363): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1363): Proximity feature is not enabled.
,E/MDM     ( 1227): [113] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/Adreno-EGL( 4712): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4712): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4712): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4712): Local Branch: 
I/Adreno-EGL( 4712): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4712): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4712):                  aa63bbd948f41d15fc72f585e
,V/GLSActivity( 1363): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1227): No location to return for getLastLocation()
,W/FusedLocationProvider( 1227): location=null
D/PMS     (  907): acquireWL(43548410): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(43548410): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025250
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025277
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025300
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026675
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026692
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
,I/Adreno-EGL( 4712): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4712): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4712): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4712): Local Branch: 
I/Adreno-EGL( 4712): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4712): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4712):                  aa63bbd948f41d15fc72f585e
,D/SmartSyncUtils( 4752): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4752): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4752): isEpsOn(), nState = 0
W/ContextImpl( 4752): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/WifiService(  907): New client listening to asynchronous messages
,W/Settings( 4712): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41bb1268
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/SensorService(  907): pid=907, uid=1000
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  907): Active sensors: size = 1
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41bb1268, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 0
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41bb1268, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41bb1268
E/ActivityThread(  907): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42649c28 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  907): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42649c28 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,W/dalvikvm( 4527): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4527): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 4527): BLE advertisement is supported
I/jxcore-log( 4527): 
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  371): PrepareKeyRequest: nonce=731275209
,I/WVCdm   (  371): CdmEngine::CloseSession
,I/CheckinRequestBuilder( 2174): Classify the device as Phone.
,D/libc    ( 2174): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2174): [NET] getaddrinfo-,err=8
D/libc    ( 2174): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2174): [NET] getaddrinfo-, 1
D/libc    ( 2174): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =85ae +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/WifiStateMachine(  907): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,W/fb4a(:<default>):UserScope( 4579): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4579): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4579): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4579/10027),
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8,
D/wpa_supplicant( 1161): nl80211: Event message available
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0,
D/libc    (  907): [NET] getaddrinfo-, 1
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/libc    (  907): [NET] getaddrinfo_proxy+
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
,D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated,
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
,I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=11 entropy=0
D/wpa_supplicant( 1161): Add randomness: count=12 entropy=1
D/wpa_supplicant( 1161): Add randomness: count=13 entropy=2,
D/wpa_supplicant( 1161): Add randomness: count=14 entropy=3
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431,
D/libc    (  364): [NET] +++++ res_nsend xid =a550 +++++
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
,D/libc    (  364): [NET] NOT IN CACHE
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
,I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
,I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
,I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
,I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing,
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
,D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=15 entropy=4
D/wpa_supplicant( 1161): Add randomness: count=16 entropy=5
D/wpa_supplicant( 1161): Add randomness: count=17 entropy=6
D/wpa_supplicant( 1161): Add randomness: count=18 entropy=7
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1161): State: DISCONNECTED -> INACTIVE
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@43635a58 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1161): reply (489) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000108041003
,I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000111881993
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2427
I/wpa_supplicant( 1161): level=-79
I/wpa_supplicant( 1161): tsf=0000000111882002
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
,I/wpa_supplicant( 1161): id=3
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-58
I/wpa_supplicant( 1161): tsf=0000000111881982
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ####
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@43635a58 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): DefaultState{ when=-9ms what=147462 obj=android.net.wifi.StateChangeResult@43635a58 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
V/ScoreHelper(  907): Only print Top 10 in ApScanList
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 108041003, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 111881993, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 111882002, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2412, timestamp: 111881982, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 226
,D/libc    (  364): [NET]res_nsend:resplen=84
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2174): [NET] getaddrinfo_proxy-, success
,D/WifiManager( 1227): getScanResults enter 
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4579/10027)
,D/libc    ( 2174): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2174): [NET] getaddrinfo-,err=8
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  907): Find DNS Address www.htc.com/104.81.130.175
,D/libc    ( 2174): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2174): [NET] getaddrinfo-,err=8
,D/libc    ( 2174): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2174): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2174): Sending checkin request (12204 bytes)
,I/CheckinRequestBuilder( 2174): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  907): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2174): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (2174/10029)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=6 [30][2][0]
,I/CheckinRequestBuilder( 2174): Classify the device as Phone.
,I/CheckinTask( 2174): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2174): Checking schedule, now: 1453190756648 next: 1453713693639
,I/CheckinService( 2174): active receiver: disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2174, uid=10029, userID:0
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025250
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025277
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025300
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026675
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026692
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
I/CheckinService( 2174): Checking schedule, now: 1453190756671 next: 1453713693639
,I/CheckinService( 2174): active receiver: disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2174, uid=10029, userID:0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024904
,D/CheckinService( 2174): Recording last checkin time for package unspecified as 1453190756681
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025250
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025277
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025300
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026675
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026692
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
,D/PMS     (  907): releaseWL(44353430): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
,D/PMS     (  907): acquireWL(4376f948): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4375f510): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/GCM     ( 1363): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    ( 1363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1363): [NET] getaddrinfo-,err=8
D/libc    ( 1363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1363): [NET] getaddrinfo-, 1
,D/libc    ( 1363): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =f827 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1363/10029)
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 289
D/libc    (  364): [NET]res_nsend:resplen=79
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1363): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1363): [NET] getaddrinfo-,err=8
,D/libc    ( 1363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1363): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1363/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1363/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1363/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1363/10029)
,D/PMS     (  907): acquireWL(435df598): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1363/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1363/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1363/10029)
,D/PMS     (  907): releaseWL(4376f948): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1363/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1363/10029)
,D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
,D/PMS     (  907): releaseWL(435df598): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(435bf8f0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1363/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1363/10029)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1363/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1363/10029)
,D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1363/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024904
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025250
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025277
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025300
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026675
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026692
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
,D/PMS     (  907): releaseWL(435bf8f0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=16 [12][2][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,I/GAV2    ( 4687): Thread[GAThread,5,main]: No campaign data found.
,D/ContactMessageStore( 1247): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1247): MSG_NOTIFY_CS_TO_SYNC <<
,D/PMS     (  907): acquireWL(425af8d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{42093438: PendingIntentRecord{41ae9090 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=116022, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(425af8d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  907): killProcessQuiet, pid=3649
I/ActivityManager(  907): Killing 3649:com.htc.task/u0a71 (adj 15): empty #17
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3649
,I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1341): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
I/ActivityManager(  907): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4804 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1274): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
W/AccTypeManager( 1341): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1341): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  907):   Scheme: "mms"
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
I/Launcher( 1274): Deferring update until onResume
D/Launcher( 1274): waitUntilResume // bindAppsUpdated
,W/SystemReader( 1259): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
,E/ExternalAccountType( 1341): Unsupported attribute readOnly
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,D/PhoneApp( 1247): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4804): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4804): MmsConfig.loadMmsSettings
,W/dalvikvm( 4804): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4804): VFY: unable to resolve instance field 36
,W/dalvikvm( 4804): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4804): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  907): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4827 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4804, uid=10111, userID:0
,W/Settings( 4804): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4804, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4804, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4804, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4804, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4804, uid=10111, userID:0
,D/MessageFrequencyProvider( 4827): onCreate
D/PMS     (  907): acquireWL(436270f0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4804 10111 null
,V/GetPrviateResource( 4827): GetPrviateResource
,V/GetPrviateResource( 4827): GetPrviateResource
,D/MmsCustomizationProvider( 4827): query uri: content://htc-mms-customization/mms-ua/ua_string
,I/ActivityManager(  907): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,D/MmsCustomizationProvider( 4827): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/[PluginManager]RegisterService( 4629): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 4629): handle notify Blinkfeed plugin client changed
,I/ActivityManager(  907): Resuming delayed broadcast
I/Babel   ( 4804): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4804): MmsConfig.loadFromDatabase
,I/IcingCorporaProvider( 2837): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  907): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,W/PackageManager(  907): Unable to load service info ResolveInfo{43453630 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
E/Babel   ( 4804): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4804): MmsConfig.loadFromResources
,E/Babel   ( 4804): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4804): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
D/PMS     (  907): acquireWL(4263d398): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4263d398): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(436270f0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ProviderInstaller( 4804): Installed default security provider GmsCore_OpenSSL
D/PMS     (  907): acquireWL(43668348): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Killing 4428:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=4428
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/MessageCustFlag( 4827): sense_version=6.0
,D/BTAccessoryUtil( 4827): createReceiver
,D/BTAccessoryUtil( 4827): registerReceiver return intent = null
D/MessageCustFlag( 4827): sku_id=99
,W/SystemReader( 4827): Cannot find message_ambs_application_id, use default value instead
I/ActivityManager(  907): Recipient 4428
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  907): Client connection lost with reason: 4
,D/Messaging( 4827): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4827): networkCode: 
,D/MessageCustFlag( 4827): sku_id=99
D/MmsConfig( 4827): SIE smsPri: null
,D/MmsConfig( 4827): networkCode: 
,D/HtcTelephonyCapability( 4827): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4827): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 4827): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4827): Cannot find qct_8960_interface, use default value instead
,D/PMS     (  907): releaseWL(43668348): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  907): acquireWL(426a1f70): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4430e9a8): PARTIAL_WAKE_LOCK  AsyncService 0x1 4095 10160 null
,I/dalvikvm-heap( 4095): Grow heap (frag case) to 15.200MB for 1821008-byte allocation
D/PMS     (  907): releaseWL(4430e9a8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  907): releaseWL(426a1f70): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Resuming delayed broadcast
,I/dalvikvm-heap( 4095): Grow heap (frag case) to 16.937MB for 1821008-byte allocation
I/ActivityManager(  907): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
D/PMS     (  907): acquireWL(43a3e638): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43a3e638): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): acquireWL(42581340): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
,D/PMS     (  907): releaseWL(42581340): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): acquireWL(437200b8): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
,D/PackageBroadcastService( 2174): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2174): Null package name or gms related package.  Ignoreing.
D/ConnectivityService(  907): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
I/ActivityManager(  907): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/PMS     (  907): releaseWL(437200b8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4429f000): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 2174): updateResources: need to parse f{com.google.android.gms}
,D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  907): start
,I/GCoreNlp( 1227): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/IcingCorporaProvider( 2837): UpdateCorporaTask done [took 365 ms] updated apps [took 365 ms] 
,D/LocationProviderProxy(  907): applying state to connected service
I/ActivityManager(  907): Resuming delayed broadcast
D/PMS     (  907): acquireWL(435482d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(435482d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  907): applying state to connected service
D/PMS     (  907): acquireWL(43c67978): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(43c67978): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(435082e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(435082e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1530): service - handleMessage() stop self
,D/AutoSetting( 1530): service - onDestroy() END
,D/AutoSetting( 1530): service - handleMessage() quit looper
,D/Process (  907): killProcessQuiet, pid=4391
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4391:com.htc.mediamanager/u0a34 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4391
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1274): loadItems() com.htc.launcher.pageview.WidgetManager@41b02d48 +
,I/Prism.WidgetManager( 1274): onLoadItems() +
,I/Icing   ( 2174): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2174): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  907): releaseWL(4429f000): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1274): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1274): onLoadItems() -
,I/Prism.ItemManager( 1274): loadItems() com.htc.launcher.pageview.WidgetManager@41b02d48 -
,D/PhoneApp( 1247): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1247): -- N1 =0
,D/PhoneApp( 1247): -- N2 =0
,D/PhoneApp( 1247): -- N3 =0
,D/Messaging( 4827): mNeedToUpdateDate2 start
,D/MmsConfig( 4827): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4827): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4827): 
D/MmsAsyncWorkHandler( 4827): HM tk = 20001
,D/ReportIndicatorCache( 4827): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4827): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41a79798
,D/TelephUtils( 1247): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,I/Messaging( 4827): mccmnc> 
,D/MmsSmsV2Provider( 1247):  phoneType = -1
D/MmsSmsV2Provider( 1247): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/DraftCache( 4827): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4827): [DraftCache/1] refresh
,D/MmsConfig( 4827): networkCode: 
,D/Messaging( 4827): ViewCache CreatePreloadOnlyConversationList
D/TelephUtils( 1247): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/MmsSmsV2Provider( 1247):  phoneType = -1
,D/MmsSmsV2Provider( 1247): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/TelephUtils( 1247): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
,D/MmsSmsV2Provider( 1247):  phoneType = -1
,D/MmsSmsV2Provider( 1247): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/MessageCustFlag( 4827): sense_version=6.0
,D/Jerry   ( 4827): start to preload cursor >>>>>>>
D/PhoneStorageUtil( 4827): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4827): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4827): createReceiver
,D/Messaging( 4827): mNeedToUpdateDate2: false
D/TelephUtils( 1247): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1247): sku_id=99
,D/TelephUtils( 1247): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,V/MmsProvider( 1247): Update uri=content://mms, match=0
,V/MmsProvider( 1247): selection=st=129 AND m_type!=134
,D/Messaging( 4827): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4827): TransactionService is going to be woken up.
,D/DraftCache( 4827): [DraftCache/487] rebuildCache
D/TelephUtils( 1247): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
D/MmsSmsV2Provider( 1247):  phoneType = -1
,D/MmsSmsV2Provider( 1247): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,V/TransactionService( 4827): 1-Creating TransactionService
D/TelephUtils( 1247): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
V/TransactionService( 4827): onStartCommand: 1
D/MmsSmsV2Provider( 1247):  phoneType = -1
,D/MmsSystemEventReceiver( 4827): unRegisterForConnectionStateChanges
V/TransactionService( 4827): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 4827): Loading previous transactions.
,D/Messaging( 4827): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1247): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/Jerry   ( 1247): URI_DRAFT
,D/TelephUtils( 1247): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
D/AccFlag ( 1247): device_type: 1
D/Messaging( 4827): ViewCache CreatePreload
,D/Messaging( 4827): ViewCache CreatePreloadOnlyMultipleOpsList
,D/DraftCache( 4827): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 4827): [DraftCache/487] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4827): 
D/MmsAsyncWorkHandler( 4827): HM tk = 20002
,D/TransactionService( 4827): Force set service start id to 1
D/TelephUtils( 1247): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1247): sku_id=99
,V/TransactionService( 4827): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4827): unRegisterForConnectionStateChanges
,D/TransactionService( 4827): stopSelfResult: true, mLastHandledServiceId: 1
V/TransactionService( 4827): Destroying TransactionService
,D/Cust_MMSMS( 4827): _has_set_default_values_2=true
,V/TransactionService( 4827): 4-Handling incoming message: { when=-4ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
D/TelephUtils( 1247): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1247): sku_id=99
,D/MsgPreferenceUtils( 4827): def_index: 0
,D/MsgPreferenceUtils( 4827): globalIndex = 1
,D/MsgPreferenceUtils( 4827): phone state: true
D/MsgPreferenceUtils( 4827): sd state: false
,D/MsgPreferenceUtils( 4827): vIndex = 0
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{436beee0 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/GAV4    ( 4804): Thread[GAThread,5,main]: No campaign data found.
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/Process (  907): killProcessQuiet, pid=3930
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3930:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3930
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=19 entropy=8
D/wpa_supplicant( 1161): Add randomness: count=20 entropy=9
D/wpa_supplicant( 1161): Add randomness: count=21 entropy=10
D/wpa_supplicant( 1161): Add randomness: count=22 entropy=11
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 ,last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=23 entropy=12
D/wpa_supplicant( 1161): Add randomness: count=24 entropy=13
D/wpa_supplicant( 1161): Add randomness: count=25 entropy=14
D/wpa_supplicant( 1161): Add randomness: count=26 entropy=15
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1161): reply (489) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000128962296
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000128962373
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2427
I/wpa_supplicant( 1161): level=-79
I/wpa_supplicant( 1161): tsf=0000000128962383
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=3
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-58
,I/wpa_supplicant( 1161): tsf=0000000128962362
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 128962296, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 128962373, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 128962383, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2412, timestamp: 128962362, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10,
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiManager( 1227): getScanResults enter 
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(437009d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  907): onReceive BATTERY_CHANGED
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PMS     (  907): releaseWL(437009d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 4629): service - mHandler: update timezone
,D/AutoSetting( 1530): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1530): service - onCreate()
,D/AutoSetting( 1530): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
D/AutoSetting( 1530): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1530): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/DotMatrix( 1595): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1595): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1530): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1530): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1530): service - mHandler: update timezone
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1530): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1530): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1530): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1530): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1595): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1595): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1118): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{41db6238 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1118): com.htc.htclocationservice 2 8 3 11
,D/AutoSetting( 4629): service - mHandler: update timezone
,D/AutoSetting( 1530): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1530): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1530): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1530): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/DotMatrix( 1595): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1595): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,D/AutoSetting( 1530): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1530): service - onStartCommand() handle command from HSP: processTimeZoneID
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1530): service - mHandler: update timezone
D/PMS     (  907): acquireWL(43406570): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
V/AlarmManager(  907): sending alarm PendingIntent{435ed6a8: PendingIntentRecord{43d416c8 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=134140, Int=0
V/AlarmManager(  907): sending alarm PendingIntent{435e6af8: PendingIntentRecord{4398e7b0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=140724, Int=0
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(425afc70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1363/10029)
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
D/AutoSetting( 1530): service - processTimeZoneID() system nitz: 
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/AutoSetting( 1530): service - processTimeZoneID() system nitz is valid: false (false)
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=10 [10][1][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/AutoSetting( 1530): service - processTimeZoneID() single-timezone, pop up dialog
,I/PhoneStatusBar( 1118): removeNotification.gc:51
,D/AutoSetting( 1530): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1595): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1595): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/PMS     (  907): acquireWL(43a3cae0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,I/RemoteViews( 1118): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{41a7ed90 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1118): com.htc.htclocationservice 2 8 3 11
,D/PMS     (  907): releaseWL(43a3cae0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(425afc70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1363/10029)
,D/PMS     (  907): acquireWL(4298b058): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43406570): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025250
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025277
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025300
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026675
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026692
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
,D/PMS     (  907): releaseWL(4298b058): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43509d20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1363/10029)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/AutoSetting( 4629): service - handleMessage() stop self
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025250
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025277
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025300
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026675
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026692
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
,D/AutoSetting( 4629): service - handleMessage() quit looper
,D/AutoSetting( 4629): service - onDestroy() END
,D/PMS     (  907): acquireWL(4373d3c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43090610): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1227): Vacuum at: now=1453190784930 tag=VacuumService
D/PMS     (  907): releaseWL(43509d20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4373d3c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43737900): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024549
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025239
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025250
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025277
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025300
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026675
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026692
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
,D/PMS     (  907): releaseWL(43737900): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4259e998): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1363/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(43090610): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025250
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025277
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025300
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026675
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026692
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
,D/PMS     (  907): releaseWL(4259e998): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43697058): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024549
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024904
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025239
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025250
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025277
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025300
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026675
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026692
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
,D/PMS     (  907): releaseWL(43697058): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(436bf4e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1363/10029)
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025250
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025277
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025300
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026675
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026692
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
,D/PMS     (  907): releaseWL(436bf4e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4354d290): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1363/10029)
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025250
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025277
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025300
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026675
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026692
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
,D/PMS     (  907): acquireWL(437ed170): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(437ed170): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(435ad0d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4354d290): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4367c490): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024549
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024904
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025239
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025250
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025277
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025300
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026675
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026692
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
,D/PMS     (  907): releaseWL(4367c490): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1227/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1227/10029)
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1227): Scheduling Phenotype for one-off execution 9061 seconds from now (1453190785698)
,D/GetConfigurationSnapshotOperation( 1227): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1227): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1227): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1227): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1227): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1227): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1227): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  907): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1227/10029)
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1227/10029)
,W/dalvikvm( 1227): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/libc    ( 1227): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1227): [NET] getaddrinfo-,err=8
D/libc    ( 1227): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1227): [NET] getaddrinfo-, 1
,D/libc    ( 1227): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =4cea +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 232
D/libc    (  364): [NET]res_nsend:resplen=87
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1227): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1227): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1227): [NET] getaddrinfo-,err=8
,D/libc    ( 1227): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1227): [NET] getaddrinfo-,err=8
,D/GpsLocationProvider(  907): ALARM_XTRA_TIMEOUT
,D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA
D/PMS     (  907): acquireWL(426369b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{41e67a58: PendingIntentRecord{424c8138 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142666, Int=0
D/PMS     (  907): acquireWL(442afe48): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
,D/PMS     (  907): releaseWL(426369b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/GpsLocationProvider(  907): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =8f84 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  364): [NET]res_nsend:resplen=238
D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
,I/global  (  907): call createSocket() return a new socket.,
D/libc    (  907): [NET] getaddrinfo+,hn 14(0x35342e3233302e),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/LocationManagerService(  907): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=20 [10][2][0]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1227/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1227/10029)
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/GpsLocationProvider(  907): [handleDownloadXtraData] calling native_inject_xtra_data
,D/PMS     (  907): releaseWL(435ad0d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(431c5878): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024549
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025250
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025277
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025300
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026675
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026692
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
,D/PMS     (  907): releaseWL(431c5878): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43511140): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10029 WorkSource{10029 com.google.android.gms}
,D/GpsLocationProvider(  907): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  907): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  907):  [handleDownloadXtraData]inject done.
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1363/10029)
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [27][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025239
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025250
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025277
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025300
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026675
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026692
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
,D/PMS     (  907): releaseWL(43511140): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=27 entropy=16
D/wpa_supplicant( 1161): Add randomness: count=28 entropy=17
D/wpa_supplicant( 1161): Add randomness: count=29 entropy=18
D/wpa_supplicant( 1161): Add randomness: count=30 entropy=19
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/3,2 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=31 entropy=20
D/wpa_supplicant( 1161): Add randomness: count=32 entropy=21
D/wpa_supplicant( 1161): Add randomness: count=33 entropy=22
D/wpa_supplicant( 1161): Add randomness: count=34 entropy=23
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
,I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1161): reply (489) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000146062456
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-59
I/wpa_supplicant( 1161): tsf=0000000146062491
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2427
I/wpa_supplicant( 1161): level=-79
I/wpa_supplicant( 1161): tsf=0000000128962383
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=3
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
,I/wpa_supplicant( 1161): tsf=0000000128962362
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 146062456, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 146062491, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 128962383, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 128962362, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiManager( 1227): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==,
D/WifiStateMachine(  907): == (4) end of scan result ==,
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): releaseWL(442afe48): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/Process (  907): killProcessQuiet, pid=4166
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4166:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4166
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/ContactMessageStore( 1247): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1247): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{434bfe70 u0 com.htc.htclocationservice/.AutoSettingService}
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=35 entropy=24
D/wpa_supplicant( 1161): Add randomness: count=36 entropy=25
D/wpa_supplicant( 1161): Add randomness: count=37 entropy=26
D/wpa_supplicant( 1161): Add randomness: count=38 entropy=27
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/3,2 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=39 entropy=28
D/wpa_supplicant( 1161): Add randomness: count=40 entropy=29
D/wpa_supplicant( 1161): Add randomness: count=41 entropy=30
D/wpa_supplicant( 1161): Add randomness: count=42 entropy=31
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1161): reply (489) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000163393713
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-59
I/wpa_supplicant( 1161): tsf=0000000163393748
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2427
I/wpa_supplicant( 1161): level=-79
I/wpa_supplicant( 1161): tsf=0000000163393758
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=3
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000128962362
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 163393713, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 163393748, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 163393758, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 128962362, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiManager( 1227): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/PMS     (  907): acquireWL(41e897d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(41e897d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1118): closing low battery warning: level=100
,D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1530): service - handleMessage() stop self
,D/AutoSetting( 1530): service - onDestroy() END
,D/AutoSetting( 1530): service - handleMessage() quit looper
,D/Process (  907): killProcessQuiet, pid=4451
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4451:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4451
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(4258ee00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{42093438: PendingIntentRecord{41ae9090 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=176022, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4258ee00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1161): nl80211: Event message available,
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
,I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=43 entropy=32
D/wpa_supplicant( 1161): Add randomness: count=44 entropy=33
D/wpa_supplicant( 1161): Add randomness: count=45 entropy=34
D/wpa_supplicant( 1161): Add randomness: count=46 entropy=35
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1161): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
,D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1,
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
,I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=47 entropy=36
D/wpa_supplicant( 1161): Add randomness: count=48 entropy=37
D/wpa_supplicant( 1161): Add randomness: count=49 entropy=38
D/wpa_supplicant( 1161): Add randomness: count=50 entropy=39
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WifiP2pService(  907): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1161): reply (489) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000180743708
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-59
I/wpa_supplicant( 1161): tsf=0000000180743745
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2427
I/wpa_supplicant( 1161): level=-79
I/wpa_supplicant( 1161): tsf=0000000180743756
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=3
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48,
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000128962362
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 180743708, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 180743745, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 180743756, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 128962362, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiManager( 1227): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): == (4) end of scan result ==,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/TelephonyReceiver( 1247): switchBindHtcMsgCursor: null
,D/PMS     (  907): acquireWL(43839268): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
,D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): releaseWL(43839268): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(41c40398): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(41c40398): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=51 entropy=40
D/wpa_supplicant( 1161): Add randomness: count=52 entropy=41
D/wpa_supplicant( 1161): Add randomness: count=53 entropy=42
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=54 entropy=43
D/wpa_supplicant( 1161): Add randomness: count=55 entropy=44
D/wpa_supplicant( 1161): Add randomness: count=56 entropy=45
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len,=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1161): reply (489) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000198013629
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-59
I/wpa_supplicant( 1161): tsf=0000000198013655
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2427
I/wpa_supplicant( 1161): level=-79
I/wpa_supplicant( 1161): tsf=0000000198013666
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=3
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-57
I/wpa_supplicant( 1161): tsf=0000000128962362
,I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ####
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 198013629, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 198013655, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 198013666, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 128962362, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiManager( 1227): getScanResults enter 
D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=57 entropy=46
D/wpa_supplicant( 1161): Add randomness: count=58 entropy=47
D/wpa_supplicant( 1161): Add randomness: count=59 entropy=48
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=60 entropy=49
D/wpa_supplicant( 1161): Add randomness: count=61 entropy=50
D/wpa_supplicant( 1161): Add randomness: count=62 entropy=51
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len,=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1161): reply (376) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000215313543
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-59
I/wpa_supplicant( 1161): tsf=0000000215313570
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
,I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2427
I/wpa_supplicant( 1161): level=-79
I/wpa_supplicant( 1161): tsf=0000000215313582
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0,
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 215313543, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 215313570, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 215313582, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiManager( 1227): getScanResults enter 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(425bae38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10027}
,V/AlarmManager(  907): sending alarm PendingIntent{435571d0: PendingIntentRecord{43a2abc0 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=229248, Int=0
,I/ActivityManager(  907): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4911 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  907): sending alarm PendingIntent{4240f090: PendingIntentRecord{4269ebc0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1453190857670, Int=10800000
,D/PMS     (  907): releaseWL(425bae38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.aurora (4911/10049)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024549
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025239
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025250
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025277
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025300
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026675
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026692
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
,D/Process (  907): killProcessQuiet, pid=4465
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4465:com.android.settings:remote/1000 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 4465
,D/PMS     (  907): acquireWL(442c1ea8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10027}
,V/AlarmManager(  907): sending alarm PendingIntent{424f7318: PendingIntentRecord{435211f8 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=229761, Int=120000
,V/AlarmManager(  907): sending alarm PendingIntent{4252a768: PendingIntentRecord{43a2abc0 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=229928, Int=0
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024549
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024904
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025239
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025250
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025277
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025300
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026675
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026692
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029432
,D/PMS     (  907): releaseWL(442c1ea8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=63 entropy=52
D/wpa_supplicant( 1161): Add randomness: count=64 entropy=53
D/wpa_supplicant( 1161): Add randomness: count=65 entropy=54
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=66 entropy=55
D/wpa_supplicant( 1161): Add randomness: count=67 entropy=56
D/wpa_supplicant( 1161): Add randomness: count=68 entropy=57
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len,=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1161): reply (376) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000232532106
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-59
I/wpa_supplicant( 1161): tsf=0000000232532131
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2427
I/wpa_supplicant( 1161): level=-79
I/wpa_supplicant( 1161): tsf=0000000232532143
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ####
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 232532106, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 232532131, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 232532143, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiManager( 1227): getScanResults enter 
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  907): acquireWL(4369f678): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{42093438: PendingIntentRecord{41ae9090 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=236023, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4369f678): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=69 entropy=58
D/wpa_supplicant( 1161): Add randomness: count=70 entropy=59
D/wpa_supplicant( 1161): Add randomness: count=71 entropy=60
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=72 entropy=61
,D/wpa_supplicant( 1161): Add randomness: count=73 entropy=62
D/wpa_supplicant( 1161): Add randomness: count=74 entropy=63
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
,I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1161): reply (376) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000249833850
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-59
I/wpa_supplicant( 1161): tsf=0000000249833877
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2427
I/wpa_supplicant( 1161): level=-79
I/wpa_supplicant( 1161): tsf=0000000249833888,
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 249833850, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 249833877, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 249833888, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiManager( 1227): getScanResults enter 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(426a1640): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null,
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(426a1640): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/HtcPowerSaver(  907): updateBatteryInfo
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  907): runPSCheck
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(434f4ec0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/PMS     (  907): releaseWL(434f4ec0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1595): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1595): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=75 entropy=64
D/wpa_supplicant( 1161): Add randomness: count=76 entropy=65
D/wpa_supplicant( 1161): Add randomness: count=77 entropy=66
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
,I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1161): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=78 entropy=67
D/wpa_supplicant( 1161): Add randomness: count=79 entropy=68
D/wpa_supplicant( 1161): Add randomness: count=80 entropy=69
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1161): reply (376) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000267163882
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
,I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-59
I/wpa_supplicant( 1161): tsf=0000000267163909
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2427
I/wpa_supplicant( 1161): level=-79
I/wpa_supplicant( 1161): tsf=0000000267163920
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ####
,D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 267163882, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 267163909, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 267163920, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults,
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiManager( 1227): getScanResults enter 
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
I/wpa_supplicant( 1161): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=81 entropy=70
D/wpa_supplicant( 1161): Add randomness: count=82 entropy=71
D/wpa_supplicant( 1161): Add randomness: count=83 entropy=72
D/wpa_supplicant( 1161): Add randomness: count=84 entropy=73
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 3: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL], c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
I/wpa_supplicant( 1161): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=85 entropy=74
D/wpa_supplicant( 1161): Add randomness: count=86 entropy=75
D/wpa_supplicant( 1161): Add randomness: count=87 entropy=76
D/wpa_supplicant( 1161): Add randomness: count=88 entropy=77
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP 64:7c:34:b0:03:6e type 0 added
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1161): reply (523) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000267163882
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-59
I/wpa_supplicant( 1161): tsf=0000000284332294
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2427
I/wpa_supplicant( 1161): level=-79
I/wpa_supplicant( 1161): tsf=0000000284332306
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=4
I/wpa_supplicant( 1161): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1161): freq=2437
I/wpa_supplicant( 1161): level=-93
I/wpa_supplicant( 1161): tsf=0000000284332315
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=UPC4688432
I/wpa_supplicant( 1161): ####
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 267163882, distance: ?(cm), distanceSd: ?(cm)
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 284332294, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 284332306, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -93, frequency: 2437, timestamp: 284332315, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  80, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  9 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  72, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-93], Tx: 13, Freq:  9 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiManager( 1227): getScanResults enter 
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43692af8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{42093438: PendingIntentRecord{41ae9090 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=296022, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43692af8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
I/wpa_supplicant( 1161): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=89 entropy=78
D/wpa_supplicant( 1161): Add randomness: count=90 entropy=79
D/wpa_supplicant( 1161): Add randomness: count=91 entropy=80
D/wpa_supplicant( 1161): Add randomness: count=92 entropy=81
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 3: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1161): ,[NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
I/wpa_supplicant( 1161): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=93 entropy=82
D/wpa_supplicant( 1161): Add randomness: count=94 entropy=83
D/wpa_supplicant( 1161): Add randomness: count=95 entropy=84
D/wpa_supplicant( 1161): Add randomness: count=96 entropy=85
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState,
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1161): reply (523) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
,I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000301422017
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-59
I/wpa_supplicant( 1161): tsf=0000000301422084
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2427
I/wpa_supplicant( 1161): level=-79
I/wpa_supplicant( 1161): tsf=0000000301422096
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=4
I/wpa_supplicant( 1161): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1161): freq=2437
I/wpa_supplicant( 1161): level=-93
I/wpa_supplicant( 1161): tsf=0000000301422106
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=UPC4688432
I/wpa_supplicant( 1161): ####
,D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 301422017, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 301422084, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 301422096, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -93, frequency: 2437, timestamp: 301422106, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  80, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  9 [2427], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  72, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-93], Tx: 13, Freq:  9 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiManager( 1227): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(43819080): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43819080): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4370a728): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4370a728): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
,D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1161): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1161): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
I/wpa_supplicant( 1161): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=97 entropy=86
D/wpa_supplicant( 1161): Add randomness: count=98 entropy=87
D/wpa_supplicant( 1161): Add randomness: count=99 entropy=88
D/wpa_supplicant( 1161): Add randomness: count=100 entropy=89
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): Selecting BSS from priority group 1
I/wpa_supplicant( 1161): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1161): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1161): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1161): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1161):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1161): Start print parameters
I/wpa_supplicant( 1161): wpa_s->wpa_state is 9
I/wpa_supplicant( 1161): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1161): isConcurrentMode() is 0
I/wpa_supplicant( 1161): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1161): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1161): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1161): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1161): wpa_s->reassociate is 0
I/wpa_supplicant( 1161): wpa_s->is_screen_on 0
I/wpa_supplicant( 1161): wpa_s->ifname wlan0
I/wpa_supplicant( 1161): End print parameters
I/wpa_supplicant( 1161): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1161): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1161): 3: 64:7c:34:b0:03:6e ssid='UPC4688432' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1161): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1161):, [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
I/wpa_supplicant( 1161): [NULL] 64:7c:34:b0:03:6e freq=2437 level=-93
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=101 entropy=90
D/wpa_supplicant( 1161): Add randomness: count=102 entropy=91
D/wpa_supplicant( 1161): Add randomness: count=103 entropy=92
D/wpa_supplicant( 1161): Add randomness: count=104 entropy=93
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1161): WPS: AP[2] 64:7c:34:b0:03:6e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1161): wpa_supplicant_pick_network+
I/wpa_supplicant( 1161): clear disabled list - type=1
I/wpa_supplicant( 1161): No suitable network found
W/wpa_supplicant( 1161): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1161): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1161): reply (523) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-46
I/wpa_supplicant( 1161): tsf=0000000318663895
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-59
I/wpa_supplicant( 1161): tsf=0000000318663921
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2427
I/wpa_supplicant( 1161): level=-79
I/wpa_supplicant( 1161): tsf=0000000318663932
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=4
I/wpa_supplicant( 1161): bssid=64:7c:34:b0:03:6e
I/wpa_supplicant( 1161): freq=2437
I/wpa_supplicant( 1161): level=-93
I/wpa_supplicant( 1161): tsf=0000000318663942
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=UPC4688432
I/wpa_supplicant( 1161): ####
,D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 318663895, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 318663921, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 318663932, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC4688432, BSSID: 64:7c:34:b0:03:6e, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -93, frequency: 2437, timestamp: 318663942, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList,
V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  80, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  9 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  72, AP:                       UPC4688432 [64:7c:34:b0:03:6e], Rssi:  0 [-93], Tx: 13, Freq:  9 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiManager( 1227): getScanResults enter 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/jxcore-log( 4527): --= Surplus to requirements =--,
I/jxcore-log( 4527): 
I/jxcore-log( 4527): ****TEST TOOK:  ms ****
I/jxcore-log( 4527): 
,I/jxcore-log( 4527): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****,
I/jxcore-log( 4527): 
,E/cutils-trace( 4934): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 4934): ====startRecUseTime====
D/htc.customization.log.level( 4934):  is 
,W/CustomizationLogLevel( 4934): Level value is invalid, use default level 2
,D/CustomizationManager( 4934):  Read ACC file spent 0.105 (s)
D/CIDMapFileReader( 4934): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4934): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4934): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4934): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4934): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4934): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4934): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4934): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4934): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4934): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 4934): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4934): Parsing tag category name = system
,I/CustomizationCIDLoader( 4934): Parsing tag category name = application
I/CustomizationCIDLoader( 4934): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4934): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4934): Parsing tag category name = AudioService
,I/CustomizationCIDLoader( 4934): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4934): Parsing tag category name = Settings
D/CustomizationManager( 4934):  Read CID file spent 0.156 (s)
,D/CustomizationManager( 4934):  All configurations done spent 0.156 (s)
,W/HtcNativeFlag( 4934): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4934): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4934): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 4934): Fail to get flag for type 'language', use default value: -1,
,D/PackageManager(  907): deletePackageAsUser: pkg=com.test.thalitest, pid=4934, uid=2000 user=0
,I/ActivityManager(  907): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
,D/Process (  907): killProcessQuiet, pid=4527
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,W/ActivityManager(  907): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  907): Killing 4527:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
I/ActivityManager(  907):   Force finishing activity ActivityRecord{43247508 u0 com.test.thalitest/.MainActivity t2}
,W/asset   (  907): Copying FileAsset 0x68a9d398 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,E/JavaBinder(  907): !!! FAILED BINDER TRANSACTION !!!
,W/InputMethodManagerService(  907): Got RemoteException sending setActive(false) notification to pid 4527 uid 10389
E/JavaBinder(  907): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 1213): !!! FAILED BINDER TRANSACTION !!!
W/PackageSettings(  907): Skipping PackageSetting{4217be08 com.example.hello/10397} due to missing metadata
,I/ActivityManager(  907): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
,D/DotMatrix( 1595): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1595): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1595): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver packageName:com.test.thalitest
,I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1341): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PMS     (  907): acquireWL(43783828): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
,W/GeofencerStateMachine( 1227): Ignoring removeGeofence because network location is disabled.
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  907): WIN DEATH: Window{43197440 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  907): Client connection lost with reason: 4
,D/VoicemailCleanupService( 1301): Cleaning up data for package: com.test.thalitest
I/Launcher( 1274): Deferring update until onResume
,D/Launcher( 1274): waitUntilResume // bindAppsRemoved
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
D/PMS     (  907): releaseWL(43783828): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
W/SystemReader( 1259): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,W/AccTypeManager( 1341): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1341): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/Prism.PackageStateRece_( 1274): action: android.intent.action.PACKAGE_REMOVED
I/[PluginManager]RegisterService( 4629): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,I/[PluginManager]RegisterService( 4629): handle notify Blinkfeed plugin client changed
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/IcingCorporaProvider( 2837): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,E/ExternalAccountType( 1341): Unsupported attribute readOnly
I/InputMethodManagerService(  907): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,I/ActivityManager(  907): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4949 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,D/PhoneApp( 1247): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,D/PMS     (  907): acquireWL(436582d0): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2837): UpdateCorporaTask done [took 422 ms] updated apps [took 422 ms] 
,E/SQLiteDatabase( 4949): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4949): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4949): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4949): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4949): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4949): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4949): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4949): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4949): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4949): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4949): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4949): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4949): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4949): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4949): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4949): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4949): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4949): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4949): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4949): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4949): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4949): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4949): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4949): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4949): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4949): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4949): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4949): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4949): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4949): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4949): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4949): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4949): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4949): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4949): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4949): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4949): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4949): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4949): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4949): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4949): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4949): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4949): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4949): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4949): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4949): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4949): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4949): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4949): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4949): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4949): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4949): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4949): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4949): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4949): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4949): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4949): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4949): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4949): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4949): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4949): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4949): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4949): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4949): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4949): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4949): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4949): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4949): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4949): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4949): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4949): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4949): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4949): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4949): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4949): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4949): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4949): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4949): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 4949): Opened ClientFlag.db in read-only mode
,E/SQLiteDatabase( 4949): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4949): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4949): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4949): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4949): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4949): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4949): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4949): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4949): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4949): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4949): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4949): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4949): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4949): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4949): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4949): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4949): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4949): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4949): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4949): 	at aho.run(AbstractDatabaseInstance.java:455)
,W/dalvikvm( 4949): threadid=11: thread exiting with uncaught exception (group=0x4163fe30)
,E/ActivityManager(  907): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4949): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4949): Process: com.google.android.apps.docs, PID: 4949
E/AndroidRuntime( 4949): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4949): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4949): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4949): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4949): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4949): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4949): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4949): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4949): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4949): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4949): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4949): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4949): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4949): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4949): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4949): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4949): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4949): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4949): 	at aho.run(AbstractDatabaseInstance.java:455)
,I/ActivityManager(  907): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4968 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process ( 4949): killProcess, pid=4949
,D/Process ( 4949): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
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
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 4949
,I/ActivityManager(  907): Process com.google.android.apps.docs (pid 4949) has died.
,W/ContextImpl( 4968): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,E/SQLiteDatabase( 4968): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4968): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4968): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4968): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4968): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4968): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4968): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4968): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4968): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4968): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4968): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4968): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4968): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4968): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4968): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4968): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4968): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4968): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4968): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4968): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4968): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 4968): threadid=10: thread exiting with uncaught exception (group=0x4163fe30)
E/AndroidRuntime( 4968): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4968): Process: com.android.keychain, PID: 4968
E/AndroidRuntime( 4968): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4968): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4968): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4968): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4968): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4968): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4968): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4968): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4968): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4968): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4968): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4968): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4968): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4968): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4968): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4968): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4968): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4968): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4968): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4968): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ActivityManager(  907): App crashed! Process: com.android.keychain
I/ActivityManager(  907): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4981 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
,D/Process ( 4968): killProcess, pid=4968
,D/Process ( 4968): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453190964989.dbox_tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager(  907): Recipient 4968
,I/ActivityManager(  907): Process com.android.keychain (pid 4968) has died.
,W/ActivityManager(  907): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AppTag  ( 4981): getInstance(Context context)
,D/AppTag  ( 4981): getInstance(Context context)
,D/AppTag  ( 4981): onCreate()
,D/PMS     (  907): acquireWL(43b0eff8): PARTIAL_WAKE_LOCK  AsyncService 0x1 4095 10160 null
,D/PMS     (  907): releaseWL(43b0eff8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,W/dalvikvm( 4122): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/Process (  907): killProcessQuiet, pid=4496
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 4496:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4496
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PackageBroadcastService( 2174): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2174): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 2174): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2174): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 2174): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2174): Module APK com.google.android.play.games already loaded
I/ActivityManager(  907): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
,E/SQLiteLog( 2174): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 2174): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6597c7e0
,W/dalvikvm( 2174): threadid=37: thread exiting with uncaught exception (group=0x4163fe30)
,E/SQLiteLog( 2174): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 2174): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca34668
,E/DriveAsyncService( 2174): disk I/O error (code 3850)
E/DriveAsyncService( 2174): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2174): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2174): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2174): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2174): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2174): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2174): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2174): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2174): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2174): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2174): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2174): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2174): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2174): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2174): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2174): 	at java.lang.Thread.run(Thread.java:864)
I/LocationSettingsChecker( 2174): Removing dialog suppression flag for package com.test.thalitest
,E/ActivityManager(  907): App crashed! Process: com.google.android.gms
,D/Process ( 2174): killProcess, pid=2174
,D/Process ( 2174): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/AndroidRuntime( 2174): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2174): Process: com.google.android.gms, PID: 2174
E/AndroidRuntime( 2174): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2174): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2174): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2174): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2174): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2174): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2174): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2174): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2174): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2174): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2174): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2174): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2174): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2174): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2174): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2174): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2174): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2174): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2174): 	at java.lang.Thread.run(Thread.java:864)
E/DropBoxManagerService(  907): Can't write: system_app_crash
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
,W/PackageManager(  907): Unable to load service info ResolveInfo{432f51a0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 2174
,I/ActivityManager(  907): Process com.google.android.gms (pid 2174) has died.
,D/PMS     (  907): handleWLDeath(436582d0): PARTIAL_WAKE_LOCK  Icing 0x1
,D/WifiService(  907): Client connection lost with reason: 4
,W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
,W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 11000ms
,W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10999ms
,W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10997ms
,I/ActivityManager(  907): Resuming delayed broadcast
,W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 10992ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 20992ms
,W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 30992ms
,I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1274): loadItems() com.htc.launcher.pageview.WidgetManager@41b02d48 +
,I/Prism.WidgetManager( 1274): onLoadItems() +
,E/SQLiteLog( 1363): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,E/SQLiteDBG( 1363): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x65f0fb20
D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  907): start
W/dalvikvm( 1363): threadid=1: thread exiting with uncaught exception (group=0x4163fe30)
,E/ActivityManager(  907): App crashed! Process: com.google.process.gapps
E/AndroidRuntime( 1363): FATAL EXCEPTION: main
E/AndroidRuntime( 1363): Process: com.google.process.gapps, PID: 1363
E/AndroidRuntime( 1363): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1363): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1363): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1363): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1363): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1363): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1363): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1363): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1363): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1363): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1363): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1363): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1363): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1363): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1363): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1363): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1363): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1363): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1363): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1363): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1363): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1363): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1363): 	... 10 more
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
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
,W/AtomicFile(  907): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  907): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,I/ActivityManager(  907): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5013 uid=10098 gids={50098, 3003, 5012}
D/Process ( 1363): killProcess, pid=1363
D/Process ( 1363): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
,I/DeviceManagement( 5013): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=5013 dbg=false s=true
,I/DeviceManagement( 5013): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
,I/DeviceManagement( 5013): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
,I/DeviceManagement( 5013): WorkflowService: Starting workflow service
I/DeviceManagement( 5013): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41aa40b0] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 5013): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5013): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
,I/DeviceManagement( 5013): PackageUpdateWorkflow: ==================================================
,I/DeviceManagement( 5013): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  907): Delay finish: com.htc.cs.dm/.receiver.PackageUpdateReceiver
,I/DeviceManagement( 5013): BackgroundController: *** Processing package remove for appID=com.test.thalitest
,I/DeviceManagement( 5013): SessionStateController: Checking invariants...
,I/ActivityManager(  907): Recipient 1363
,I/ActivityManager(  907): Process com.google.process.gapps (pid 1363) has died.
D/WifiService(  907): Client connection lost with reason: 4
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 40816ms
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/SQLiteDatabase( 5013): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 5013): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5013): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5013): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5013): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5013): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5013): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5013): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5013): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5013): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5013): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5013): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5013): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5013): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5013): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5013): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 5013): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 5013): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 5013): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 5013): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 5013): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 5013): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 5013): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 5013): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 5013): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 5013): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 5013): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 5013): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 5013): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 5013): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 5013): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 5013): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 5013): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 5013): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 5013): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 5013): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 5013): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 5013): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel,.java:176)
E/SQLiteDatabase( 5013): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 5013): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 5013): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5013): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5013): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5013): 	at java.lang.Thread.run(Thread.java:864)
I/DeviceManagement( 5013): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 5013): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,I/DeviceManagement( 5013): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
,E/SQLiteDatabase( 5013): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.,
E/SQLiteDatabase( 5013): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5013): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5013): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5013): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5013): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5013): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5013): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5013): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5013): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5013): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5013): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5013): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5013): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5013): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5013): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 5013): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 5013): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 5013): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 5013): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 5013): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 5013): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 5013): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 5013): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 5013): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 5013): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 5013): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 5013): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
E/SQLiteDatabase( 5013): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
E/SQLiteDatabase( 5013): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 5013): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 5013): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5013): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5013): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5013): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/DeviceManagement( 5013): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@41aa40b0]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/DeviceManagement( 5013): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/DeviceManagement( 5013): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/DeviceManagement( 5013): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/DeviceManagement( 5013): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/DeviceManagement( 5013): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/DeviceManagement( 5013): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/DeviceManagement( 5013): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/DeviceManagement( 5013): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/DeviceManagement( 5013): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/DeviceManagement( 5013): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
W/DeviceManagement( 5013): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
W/DeviceManagement( 5013): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/DeviceManagement( 5013): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/DeviceManagement( 5013): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
W/DeviceManagement( 5013): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 5013): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 5013): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 5013): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 5013): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 5013): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 5013): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 5013): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 5013): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 5013): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 5013): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 5013): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 5013): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 5013): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 5013): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 5013): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 5013): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 5013): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 5013): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/DeviceManagement( 5013): WorkflowService: Stopping workflow service
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5029 uid=10099 gids={50099, 3003, 5012}
,D/Process (  907): killProcessQuiet, pid=3907
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3907:com.google.android.music:main/u0a154 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3907
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  907): Client com.google.android.music (pid 3907): Died!
,D/Documents( 5029): Loading roots for com.android.providers.downloads.documents
,D/Documents( 5029): Loading roots for com.android.externalstorage.documents
,E/SQLiteDatabase( 5029): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 5029): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5029): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5029): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5029): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5029): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5029): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5029): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5029): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5029): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5029): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5029): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5029): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5029): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5029): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5029): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 5029): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 5029): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 5029): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 5029): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 5029): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 5029): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 5029): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 5029): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5029): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5029): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5029): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5029): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5029): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5029): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5029): 	at dalvik.system.NativeStart.main(Native Method)

```
