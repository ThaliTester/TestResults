#### Test 5615109370bee58_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/PMS     (  906): acquireWL(432051a0): PARTIAL_WAKE_LOCK  Icing 0x1 2231 10028 null
D/PMS     (  906): releaseWL(432051a0): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  906): acquireWL(422e4e18): PARTIAL_WAKE_LOCK  Icing 0x1 2231 10028 null
D/PMS     (  906): releaseWL(422e4e18): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/PMS     (  906): acquireWL(431582b0): PARTIAL_WAKE_LOCK  Icing 0x1 2231 10028 null
,D/PMS     (  906): releaseWL(431582b0): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/WIFI_ICON( 1115): WifiActivity: 0
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
--------- beginning of /dev/log/main
E/cutils-trace( 4415): Error opening trace file: No such file or directory (2)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 19
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 76
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
D/CustomizationManager( 4415): ====startRecUseTime====
D/htc.customization.log.level( 4415):  is 
W/CustomizationLogLevel( 4415): Level value is invalid, use default level 2
D/CustomizationManager( 4415):  Read ACC file spent 0.068 (s)
D/CIDMapFileReader( 4415): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4415): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4415): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4415): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4415): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4415): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4415): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4415): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4415): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4415): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4415): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4415): Parsing tag category name = system
I/CustomizationCIDLoader( 4415): Parsing tag category name = application
I/CustomizationCIDLoader( 4415): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4415): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4415): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4415): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4415): Parsing tag category name = Settings
D/CustomizationManager( 4415):  Read CID file spent 0.110 (s)
D/CustomizationManager( 4415):  All configurations done spent 0.110 (s)
W/HtcNativeFlag( 4415): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4415): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4415): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4415): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  906): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  906): <<acquire mCpuPerf_Freq wakelock
D/PMS     (  906): acquireHCC(423869b0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 906 1000 null
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4415
D/PMS     (  906): acquireHCC(4224da48): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 906 1000 null
W/asset   (  906): Copying FileAsset 0x6329ee90 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  906): @test_code: getHtcIntentFlag: 0 obj: 1111404768
I/FeedHostManager( 1266): [onPause]
I/FeedProviderManager( 1266): onPause
I/FeedHostManager( 1266): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41b814f0
I/SocialFeedProvider( 1266): +onPause
I/SocialFeedProvider( 1266): -onPause
D/PMS     (  906): acquireWL(4249b4e0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
I/ActivityManager(  906): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4426 uid=10189 gids={50189, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1266): [trimMemory] 20
W/asset   ( 4426): Copying FileAsset 0x5c74c6a8 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4426): Binding Chromium to main looper Looper (main, tid 1) {41ac3408}
I/LibraryLoader( 4426): Expected native library version number "",actual native library version number ""
I/chromium( 4426): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4426): Initializing chromium process, renderers=0
D/PMS     (  906): acquireWL(42e4d928): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  906): acquireWL(426de4f0): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  906): java.lang.Throwable: stack dump
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4252a740:true
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4426): 1101893184: getState(). Returning 12
D/PMS     (  906): releaseWL(42e4d928): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4426): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4426): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4426): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4426): Local Branch: 
I/Adreno-EGL( 4426): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4426): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4426):                  aa63bbd948f41d15fc72f585e
W/chromium( 4426): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4426): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4426): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4426): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4426): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4426): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4426): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4426): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4426): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4426): CordovaWebView is running on device made by: HTC
,W/AwContents( 4426): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  906): Displayed com.test.thalitest/.MainActivity: +297ms
W/ResourceType( 4426): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4426): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b0a4f0, mServedView=org.apache.cordova.engine.SystemWebView{41ad0158 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/InputMethodManagerService(  906): Disable input method client, pid=1266
I/InputMethodManagerService(  906): Enable input method client, pid=4426
W/XT9_C   ( 1208): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1208): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 4426): nativeOnDraw failed; clearing to background color.
D/PMS     (  906): releaseWL(4249b4e0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/WIFI_ICON( 1115): WifiActivity: 1
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/JsMessageQueue( 4426): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 4426): JniHelper::setJavaVM(0x41599048), pthread_self() = 1662916616
D/JX-Cordova( 4426): jxcore cordova android initializing
I/dalvikvm-heap( 4426): Grow heap (frag case) to 11.993MB for 42652-byte allocation
,I/dalvikvm-heap( 4426): Grow heap (frag case) to 12.075MB for 95956-byte allocation
,I/dalvikvm-heap( 4426): Grow heap (frag case) to 12.149MB for 143930-byte allocation
,I/dalvikvm-heap( 4426): Grow heap (frag case) to 12.264MB for 215890-byte allocation
,I/dalvikvm-heap( 4426): Grow heap (frag case) to 12.439MB for 323830-byte allocation
,I/dalvikvm-heap( 4426): Grow heap (frag case) to 12.711MB for 485740-byte allocation
,I/dalvikvm-heap( 4426): Grow heap (frag case) to 13.685MB for 1092904-byte allocation
,I/dalvikvm-heap( 4426): Grow heap (frag case) to 14.631MB for 1639352-byte allocation
,I/dalvikvm-heap( 4426): Grow heap (frag case) to 15.875MB for 2459024-byte allocation
,I/dalvikvm-heap( 4426): Grow heap (frag case) to 18.063MB for 3688532-byte allocation
,W/CpuWake (  906): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  906): <<release mCpuPerf_Freq wakelock
D/PMS     (  906): releaseHCC(423869b0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  906): releaseHCC(4224da48): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/PMS     (  906): acquireWL(4411d230): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=77 rxSum=62} preTxRxSum={txSum=77 rxSum=62}
D/WifiDataStallTracker(  906): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  906): onDataStallAlarm: tag=20518 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20519 delay=15s
V/AlarmManager(  906): sending alarm PendingIntent{4248aca8: PendingIntentRecord{42569438 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=108268, Int=0
D/PMS     (  906): releaseWL(4411d230): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/jxcore-log( 4426): Initializing JXcore engine
,W/jxcore-log( 4426): JXcore engine is ready
,W/jxcore-log( 4426): Starting JXcore engine
,W/jxcore-log( 4426): Platform android
W/jxcore-log( 4426): 
,W/jxcore-log( 4426): Process ARCH arm
W/jxcore-log( 4426): 
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 19
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 95
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1177): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:110, mTXpacketCount:110, avgLinkspeed:19,mAvgTxRate54
,D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,I/jxcore-log( 4426): JXcore Cordova bridge is ready!
I/jxcore-log( 4426): 
,W/jxcore-log( 4426): JXcore engine is started
,I/chromium( 4426): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PMS     (  906): releaseWL(426de4f0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4426): Toggling radios to true
I/jxcore-log( 4426): 
,D/BluetoothAdapter( 4426): enable(): BT is already enabled..!
,D/WifiManager( 4426): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10189
W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  906): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 2
W/Settings:Agent(  906): >> traceCallingStack()
W/Settings:Agent(  906): Process.myPid(): 906
W/Settings:Agent(  906): Process.myTid(): 917
W/Settings:Agent(  906): Process.myUid(): 1000
W/Settings:Agent(  906): 
W/Settings:Agent(  906): 
,W/System.err(  906): java.lang.Throwable: stack dump
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
,W/Settings:Agent(  906): << traceCallingStack(): 1(ms)
D/WifiManager( 4426): disconnect: Base Package Name=com.test.thalitest, uid=10189
D/WifiNative-wlan0(  906): doBoolean: DISCONNECT
D/WifiService(  906): New client listening to asynchronous messages
D/WifiService(  906): setWifiEnabled: true pid=4426, uid=10189
E/WifiService(  906): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  906): isSprintWifiRestricted(): false
I/WifiService(  906): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  906): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true,
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
D/WifiManager( 4426): reconnect: Base Package Name=com.test.thalitest, uid=10189
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): TDLS: Tear down peers
I/wpa_supplicant( 1177): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4426): Radios toggled
I/jxcore-log( 4426): 
I/jxcore-log( 4426): My device name is: HTC-HTC Desire 820
I/jxcore-log( 4426): 
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1177): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1177): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1177): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1177): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1177): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1177): send_and_recv error -67 - cmd 12
D/HTCRequest(  906): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1177): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  906): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1177): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1177): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1177): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1177): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1177): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1177): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8d5fbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1177):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1177): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1177): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1177): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1177): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1177): htc_wext_set_TX_TRACKING (0)+
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1177): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1177): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1177): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1177): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1177): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1177): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1177): EAPOL: Supplicant port status: Unauthorized
D/HTCRequest(  906): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1177): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1177): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1177): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1177): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  906): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1177): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1177): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1177): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1177): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1177): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1177): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1177): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1177): htc_w,ext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1177): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1177): EAPOL: Supplicant port status: Unauthorized
D/HTCRequest(  906): WifiMonitor:getReasonFromEventString() 3
D/wpa_supplicant( 1177): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  906): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1177): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1177): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1177): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 18
D/HTCRequest(  906): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1177): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1177): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1177): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1177): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1177): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
D/wpa_supplicant( 1177): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1177): Wireless event: cmd=0x8b15 len=20
D/WifiMonitor(  906): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1177): nl80211: Event message available
D/wpa_supplicant( 1177): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1177): nl80211: Ignore disconnect event triggered during reassociation
D/WifiNative-wlan0(  906):    returned true
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiPerfLock(  906): release()
D/WifiStateMachine(  906): PerfLock released for exiting ConnectedState
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/Tethering(  906): [isWifi] getHotspotEnabled: false
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1177): Power_Mode_Type mode = 0
I/wpa_supplicant( 1177): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 61
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1177): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  906):    returned true
D/ConnectivityService(  906): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  906): acquireWL(42f00120): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 906 1000 null
D/WifiP2pService(  906): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/DhcpStateMachine(  906): [RunningState] Stop DHCP
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  906): doBoolean: RECONNECT
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): Fast associate: Old scan results
D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=20519 mDataStallAlarmIntent=PendingIntent{4376fbc8: PendingIntentRecord{42569438 android broadcastIntent}}
I/wpa_supplicant( 1177): wpa_supplicant_scan enter
I/wpa_supplicant( 1177): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1177): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1177): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1177): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1177): nl80211: Event message available
D/wpa_supplicant( 1177): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): Enter handleNetworkDisconnect
,I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WISPrService( 3816): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1819/10178)
D/UsbnetStateTracker(  906): isAvailable+-
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/UsbnetStateTracker(  906): reconnect
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/UsbnetStateTracker(  906): isAvailable+-
I/wpa_supplicant( 1177): Power_Mode_Type mode = 0
I/wpa_supplicant( 1177): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1177): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  906):    returned true
,D/WISPrService( 3816): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/ConnectivityService(  906): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  906): default: reconnect()
D/MDST    (  906): default: setTeardownRequested(false)
D/MDST    (  906): default: setEnableApn apnType =default , enable=true
D/WifiP2pService(  906): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  906): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/WifiService(  906): New client listening to asynchronous messages
,D/ConnectivityService(  906): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  906): Exit handleNetworkDisconnect
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  906): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
,D/ConnectivityService(  906): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 3816): >>>>>WISPrService start isConnected = false<<<<<
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/ConnectivityService(  906): resetConnections(wlan0, 3)
,D/PMS     (  906): acquireWL(42543288): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1372 10028 null
D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/WISPrService( 3816): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/libc    (  363): [NET] entry_id:6   entry:0xb7066000  removed 
D/libc    (  363): [NET] entry_id:5   entry:0xb7066258  removed 
D/libc    (  363): [NET] entry_id:4   entry:0xb7066310  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb7066428  removed 
D/libc    (  363): [NET] entry_id:7   entry:0xb70668f8  removed 
D/libc    (  363): [NET] entry_id:3   entry:0xb70660e8  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb70664f0  removed 
D/libc    (  363): [NET] entry_id:8   entry:0xb70667d0  removed 
,D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
D/ConnectivityService(  906): flush DNS cache for net 1(wlan0)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1819/10178)
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
,I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:1
D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/PMS     (  906): acquireWL(424bd730): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  906): acquireWL(42578e20): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/ConnectivityService(  906): reportInetCondition for net -1, percentage: 0 by  (1372/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  906): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/PMS     (  906): releaseWL(424bd730): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/PMS     (  906): releaseWL(42543288): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/WifiStateMachine(  906): startScan Pid: 906 Uid 1000
,D/WifiNative-wlan0(  906): doBoolean: SCAN
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1177): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  906):    returned false
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
D/BatSI   (  906): WIFI scan started for: 650a0300 uid:1000
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10028)
,I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:0
D/PMS     (  906): releaseWL(42578e20): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  906): mActiveDefaultNetwork: -1
D/ConnectivityService(  906): handleInetConditionChange: no active default network - ignore
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
D/Tethering(  906): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  906): bSetPropertyMultiRAB:false
D/CaptivePortalTracker(  906): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: false
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3882/10154)
I/Tethering(  906): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  906): ipv4Default null
I/Tethering(  906): No IPv4 upstream interface, giving up.
D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
,D/CaptivePortalTracker(  906): NoActiveNetworkState
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,I/NetworkMonitor( 3882): type=WIFI subType= reason=null isConnected=false
,D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  906): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
,I/ConnectivityHelper( 1266): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1266/10075)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1437/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4298/10100)
D/PMS     (  906): acquireWL(42de2958): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1883/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1819/10178)
D/PMS     (  906): releaseWL(42de2958): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4298/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (2472/10021)
,I/ActivityManager(  906): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4481 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4481): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4481): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4481): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4481): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4481): Preparing secondary program dexes.
V/DexLibLoader( 4481): Loaded 4 raw lines of metadata.
V/DexLibLoader( 4481): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
,V/DexLibLoader( 4481): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4481): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4481): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4481): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4481): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4481): Dex already copied
D/OdexVerifier( 4481): Odex verification is skipped.
,V/DexLibLoader( 4481): Creating class loader
,V/DexLibLoader( 4481): Finished creating class loader
V/DexLibLoader( 4481): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4481): Dex already copied
D/OdexVerifier( 4481): Odex verification is skipped.
,V/DexLibLoader( 4481): Creating class loader,
V/DexLibLoader( 4481): Finished creating class loader,
V/DexLibLoader( 4481): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4481): Dex already copied
D/OdexVerifier( 4481): Odex verification is skipped.
,V/DexLibLoader( 4481): Creating class loader,
V/DexLibLoader( 4481): Finished creating class loader
V/DexLibLoader( 4481): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4481): Dex already copied,
D/OdexVerifier( 4481): Odex verification is skipped.
,V/DexLibLoader( 4481): Creating class loader
V/DexLibLoader( 4481): Finished creating class loader,
,V/DexLibLoader( 4481): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4481): DexLibLoader.ensureDexLoaded took 15 ms
,W/dalvikvm( 4481): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4481): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4481): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4481): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4481): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4481): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4481): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1177): nl80211: Event message available
D/wpa_supplicant( 1177): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1177): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1177): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1177): nl80211: Survey data missing
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1177): Sorted scan results
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1177): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1177): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
D/wpa_supplicant( 1177): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1177): Add randomness: count=7 entropy=0
D/wpa_supplicant( 1177): Add randomness: count=8 entropy=1
D/wpa_supplicant( 1177): Add randomness: count=9 entropy=2
D/wpa_supplicant( 1177): Add randomness: count=10 entropy=3
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1177): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1177): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1177): wpa_supplicant_pick_network+
I/wpa_supplicant( 1177): Selecting BSS from priority group 1
I/wpa_supplicant( 1177): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1177): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1177): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1177): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1177):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1177):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-58
I/wpa_supplicant( 1177): Start print parameters
I/wpa_supplicant( 1177): wpa_s->wpa_state is 3
I/wpa_supplicant( 1177): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1177): isConcurrentMode() is 0
I/wpa_supplicant( 1177): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1177): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1177): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1177): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1177): wpa_s->reassociate is 1
I/wpa_supplicant( 1177): wpa_s->is_screen_on 1
I/wpa_supplicant( 1177): wpa_s->ifname wlan0
I/wpa_supplicant( 1177): End print parameters
I/wpa_supplicant( 1177): selected network = 1
D/wpa_supplicant( 1177): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8d614e8  current_ssid=0x0
D/wpa_supplicant( 1177): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1177): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1177): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1177): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1177): check if in concurrent case
,I/wpa_supplicant( 1177): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz),
D/wpa_supplicant( 1177): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1177): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1177): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1177): RSN: PMKSA cache search - network_ctx=0xb8d614e8 try_opportunistic=0
D/wpa_supplicant( 1177): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1177): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1177): State: SCANNING -> ASSOCIATING
,D/wpa_supplicant( 1177): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1177): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1177): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1177): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 6
,D/wpa_supplicant( 1177): nl80211: Unsubscribe mgmt frames handle 0xb8d60718 (mode change)
D/wpa_supplicant( 1177): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8d60718
D/wpa_supplicant( 1177): nl80211: Register frame type=0xd0 nl_handle=0xb8d60718
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1177): nl80211: Register frame type=0xd0 nl_handle=0xb8d60718
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1177): nl80211: Register frame type=0xd0 nl_handle=0xb8d60718
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1177): nl80211: Register frame type=0xd0 nl_handle=0xb8d60718
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1177): nl80211: Register frame type=0xd0 nl_handle=0xb8d60718
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1177): nl80211: Register frame type=0xd0 nl_handle=0xb8d60718
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1177): nl80211: Register frame type=0xd0 nl_handle=0xb8d60718
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1177): nl80211: Register frame type=0xd0 nl_handle=0xb8d60718
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1177): nl80211: Register frame type=0xd0 nl_handle=0xb8d60718
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1177): nl80211: Register frame type=0xd0 nl_handle=0xb8d60718
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1177): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1177):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1177):   * freq=2412
D/wpa_supplicant( 1177):   * Auth Type 0
D/wpa_supplicant( 1177):   * WPA Versions 0x2
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1177): nl80211: Connect request send successfully
D/wpa_supplicant( 1177): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1177): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1177): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1177): EAPOL: External notification - EAP fail=0,
D/wpa_supplicant( 1177): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1177): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1177): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1177): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1177): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 18
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1177): reply (489) for get BSS: id=0
I/wpa_supplicant( 1177): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1177): freq=5220
I/wpa_supplicant( 1177): level=-48
I/wpa_supplicant( 1177): tsf=0000000111491203
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1177): ssid=NG7005g
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=1
I/wpa_supplicant( 1177): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1177): freq=2412
I/wpa_supplicant( 1177): level=-58
I/wpa_supplicant( 1177): tsf=0000000111491220
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1177): ssid=NG700
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=2
I/wpa_supplicant( 1177): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1177): freq=2412
I/wpa_supplicant( 1177): level=-58
I/wpa_supplicant( 1177): tsf=0000000111491216
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1177): ssid=01ABC
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=3
I/wpa_supplicant( 1177): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1177): freq=2427
I/wpa_supplicant( 1177): level=-77
I/wpa_supplicant( 1177): tsf=0000000111491223
I/wpa_supplicant( 1177): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1177): ssid=Gonzos
I/wpa_supplicant( 1177): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 111491203, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -58, frequency: 2412, timestamp: 111491220, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2412, timestamp: 111491216, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2427, timestamp: 111491223, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
D/BatSI   (  906): WIFI scan stopped for: 640a0300 uid:1000
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,W/dalvikvm( 4481): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4481): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1177): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1177): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1177): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 1177): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1177): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1177): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1177): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1177): nl80211: Event message available
D/wpa_supplicant( 1177): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1177): nl80211: Connect event
D/wpa_supplicant( 1177): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1177): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1177): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1177): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1177): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1177): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1177): Add randomness: count=11 entropy=4
I/wpa_supplicant( 1177): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1177): TDLS: Remove peers on association
D/wpa_supplicant( 1177): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1177): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1177): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1177): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1177): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1177): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1177): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1177): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1177): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1177): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1177): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1177): EAPOL: enable timer tick
D/wpa_supplicant( 1177): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1177): htc_wext_set_keepalive +
I/wpa_supplicant( 1177): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1177): getPrivFuncNum +	
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
I/wpa_supplicant( 1177): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1177): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1177): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1177): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1177): Get randomness: len=32 entropy=5
D/WifiMonitor(  906): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  906): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  906): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  906): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  906): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  906): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:handleSu,pplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  906): Enter handleAssociatedWithEvent
D/WifiStateMachine(  906): Associated
D/WifiStateMachine(  906): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  906): Exit handleAssociatedWithEvent
D/WifiStateMachine(  906): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
D/Tethering(  906): interfaceStatusChanged wlan0, true
D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  906): This record is existed, only update it...
I/wpa_supplicant( 1177): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1177): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb8d609f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1177):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1177): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1177): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1177): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6ed9b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1177):    broadcast key
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1177): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1177): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1177): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1177): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1177): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1177): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 1177): wlan0: Connect to SSID: NG700
D/WifiMonitor(  906): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1177): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1177): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1177): set send_ind_to_ndc = 0
I/wpa_supplicant( 1177): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1177): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1177): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1177): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1177): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1177): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1177): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1177): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1177): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1177): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1177): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1177): EAPOL authentication completed successfully
I/wpa_supplicant( 1177): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1177): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1177): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1177): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
D/Tethering(  906): interfaceStatusChanged wlan0, true
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/WifiStateMachine(  906): fetchFrequency(), freq = 2412
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  906): This record is existed, only update it...
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WISPrService( 3816): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WISPrService( 3816): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  906): updateConnectedAP...
,D/DhcpStateMachine(  906): [StoppedState] Start DHCP
D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,E/FbInjectorInitializer( 4481): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 1
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1177): Power_Mode_Type mode = 1
I/wpa_supplicant( 1177): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  906):    returned null
E/WifiStateMachine(  906): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 1177): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  906):    returned null
D/WifiStateMachine(  906): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  906): acquireWL(440ecd78): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 906 1000 null
D/WifiStateMachine(  906): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@41c248e0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@41c248e0 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:1
,W/fb4a(:<default>):StaticBindingVerifier( 4481): Verify
,D/WifiService(  906): New client listening to asynchronous messages
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4481): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4481): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4481): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  906): killProcessQuiet, pid=3864
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3864:com.htc.mediamanager/u0a32 (adj 15): empty #17
,D/PMS     (  906): acquireWL(424e0a50): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2231 10028 null
I/ActivityManager(  906): Recipient 3864
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(4316fd28): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2231 10028 null
,D/PMS     (  906): releaseWL(424e0a50): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2231/10028)
,D/PMS     (  906): releaseWL(4316fd28): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/GCM     ( 1372): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2231/10028)
,D/AutoSetting( 1401): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  906): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4510 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1401/10053)
,D/AutoSetting( 1401): Util - no network available!
,D/AutoSetting( 1401): service - onCreate()
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1401/10053)
D/AutoSetting( 1401): service - AddressCache: using context: com.htc.Weather
D/AutoSetting( 1401): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/LocationManagerService(  906): request 42359848 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/LocationManagerService(  906): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1401): service - mHandler: cancel location update
D/AutoSetting( 1401): service -           changes count: 0
,W/fb4a(:<default>):UserScope( 4481): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4481): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4481): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4510): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4510): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4510): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4510): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  906): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4526 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4510/10078)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4510/10078)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4510/10078)
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4481): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  906): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4543 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=4239
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 4239:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,E/dalvikvm( 4481): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4481): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4481): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4481): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4481): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4481): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4481): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4481): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4481): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4481): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4481): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4481): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4481): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4481): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4481): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4481): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4481): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4481): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,I/dalvikvm-heap( 4481): Grow heap (frag case) to 9.924MB for 39954-byte allocation
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4543): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system,
,W/ContextImpl( 4543): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/GAV2    ( 4543): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
I/ActivityManager(  906): Recipient 4239
D/WifiService(  906): Client connection lost with reason: 4
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4543): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
I/dalvikvm-heap( 4481): Grow heap (frag case) to 10.000MB for 79892-byte allocation
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4543): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4481): Grow heap (frag case) to 10.031MB for 84664-byte allocation
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4543/10151)
,V/WebViewChromiumFactoryProvider( 4543): Binding Chromium to main looper Looper (main, tid 1) {41ac71f0}
,I/LibraryLoader( 4543): Expected native library version number "",actual native library version number ""
,I/chromium( 4543): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4543): Initializing chromium process, renderers=0
,D/PMS     (  906): acquireWL(43fa4f88): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
,D/PMS     (  906): acquireWL(4410f7b0): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
,E/AudioManagerAndroid( 4543): BLUETOOTH permission is missing!
D/PMS     (  906): releaseWL(4410f7b0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4543): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4543): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4543): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4543): Local Branch: 
I/Adreno-EGL( 4543): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4543): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4543):                  aa63bbd948f41d15fc72f585e
,I/dalvikvm-heap( 4481): Grow heap (frag case) to 10.280MB for 75760-byte allocation
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1177): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1177): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
,I/NSApplication( 4543): Starting up...
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{44116fc0 u0 ReceiverList{44116f80 4481 com.facebook.katana/10026/u0 remote:44109ab8}}
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{44116fc0 u0 ReceiverList{44116f80 4481 com.facebook.katana/10026/u0 remote:44109ab8}}
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43141a08 u0 ReceiverList{431419a8 4481 com.facebook.katana/10026/u0 remote:426704f8}}
D/PMS     (  906): releaseWL(440ecd78): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [1][0][0]
,I/wpa_supplicant( 1177): Change stage from stage0 to stage3
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): gateway: /192.168.1.1
,D/WifiNative-wlan0(  906): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1177): WiFi gateway: 0x101a8c0
,I/wpa_supplicant( 1177): wlan0: Background scan every 600 seconds
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4543/10151)
D/WIFI_ICON( 1115): updateWifiState: RSSI_CHANGED -1 -> 3
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4543/10151)
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  906): VerifyingLinkState enter
D/WifiStateMachine(  906): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  906): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  906): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -57, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20521 delay=15s
,V/NetworkPolicy(  906): mWifiStateReceiver: meteredHint=false,EPS mode=false
,I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiWatchdogStateMachine(  906): WAN detection
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  906): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  906): default: teardown()
D/MDST    (  906): default: setTeardownRequested(true)
D/MDST    (  906): default: setEnableApn apnType =default , enable=false
,D/WISPrService( 3816): >>>>>WISPrService start isConnected = true<<<<<
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WIFI_ICON( 1115): WifiActivity: 1
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/MDST    (  906): default: setTeardownRequested(true)
D/ConnectivityService(  906): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4141/10160)
E/ConnectivityService(  906): Unexpected mtu value: android.net.wifi.WifiStateTracker@423f2a68
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4141/10160)
,D/WifiStateMachine(  906): syncGetConfiguredNetworks
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1819/10178)
D/ConnectivityService(  906): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  906): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/Process (  906): killProcessQuiet, pid=4268
,D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
D/ConnectivityService(  906): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
I/ActivityManager(  906): Killing 4268:com.google.android.partnersetup/u0a31 (adj 15): empty #17
D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  906): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/WirelessDisplayService(  906): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  906):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/PMS     (  906): acquireWL(43cf0e98): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/ConnectivityService(  906): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1819/10178)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4510/10078)
,I/QuickSettingWifi( 1115): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,D/GCM     ( 1372): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4268
D/PMS     (  906): acquireWL(43d85120): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2231 10028 null
,I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
,I/logwrapper(  363): /system/bin/ip terminated by exit(254)
D/wpa_supplicant( 1177): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1177): EAPOL: disable timer tick
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1819/10178)
D/PMS     (  906): acquireWL(4316c438): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1437 10028 null
,D/PMS     (  906): releaseWL(4316c438): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  906): acquireWL(43675ed0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2231 10028 null
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
D/PMS     (  906): releaseWL(43d85120): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2231/10028)
,D/PMS     (  906): acquireWL(43da3c48): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1437 10028 null
,I/CheckinService( 2231): Preparing to send checkin request
,D/GCoreFlp( 1437): Unknown pending intent to remove.
,I/EventLogService( 2231): Accumulating logs since 1453126541264
D/ConnectivityService(  906): mActiveDefaultNetwork: WIFI
D/PMS     (  906): releaseWL(43da3c48): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50,
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(43cf0e98): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/GoogleHttpClient( 2231): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 2231): Using GMS GoogleHttpClient
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (2231/10028)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (2231/10028)
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4481): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4481): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,I/jxcore-log( 4426): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 4426): 
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/CheckinRequestBuilder( 2231): awaiting user notification for token
,D/DotMatrix( 1577): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1577): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1115): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41bf1df8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.google.android.gms 1 7 2 12
,I/ActivityManager(  906): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4618 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 4618): install
,I/MultiDex( 4618): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4618): loading existing secondary dex files
,I/MultiDex( 4618): load found 1 secondary dex files
,I/MultiDex( 4618): install done
,I/ProviderInstaller( 4618): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/GCM     ( 1372): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/SensorManager(  906): mEventCount = 900
,I/SensorManager(  906): mEventCount = 900
,I/Adreno-EGL( 4618): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4618): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4618): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4618): Local Branch: 
I/Adreno-EGL( 4618): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4618): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4618):                  aa63bbd948f41d15fc72f585e
,I/jxcore-log( 4426): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 4426): 
,I/jxcore-log( 4426): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 4426): 
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (4618/10028)
,I/jxcore-log( 4426): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 4426): 
,I/PMS     (  906): Going to sleep due to screen timeout...
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421b0808
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  906): pid=906, uid=1000
,W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
,W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421b0808, eanble = 0, strlen(mName) = 59
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 2
,W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41ff6f50
W/SensorService(  906): Listener[1] = com.htc.smartdim.sensor_eye@4253d1d8
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  906): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  906): Couldn't get kernel wake lock stats
V/LightsService(  906): setLight #2: color=#0
D/qdlights(  906): set_light_buttons_func: on=0 brightness=0
V/LightsService(  906): setLight #0: color=#0
,I/Adreno-EGL( 4618): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4618): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4618): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4618): Local Branch: 
I/Adreno-EGL( 4618): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4618): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4618):                  aa63bbd948f41d15fc72f585e
,W/PMS     (  906): mWirelessDisplayManager is null
D/WirelessDisplayService(  906): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,I/jxcore-log( 4426): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 4426): 
,I/jxcore-log( 4426): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 4426): 
,I/Adreno-EGL( 4618): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4618): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4618): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4618): Local Branch: 
I/Adreno-EGL( 4618): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4618): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4618):                  aa63bbd948f41d15fc72f585e
,I/jxcore-log( 4426): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 4426): 
,D/WIFI_ICON( 1115): WifiActivity: 3
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  906): releaseWL(42f00120): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  906): NetTransition Wakelock for ConnectedState released by timeout
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: true
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  906): NoActiveNetworkState
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,V/Tethering(  906): bSetPropertyMultiRAB:false
,D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/Tethering(  906): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.118/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  906): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  906): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  906): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  906): Found interface wlan0
,D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
,I/NetworkMonitor( 3882): type=WIFI subType= reason=null isConnected=true
W/AccTypeManager( 1330): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1330): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(422a3608): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1437/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.musicenhancer (3906/10051)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3882/10154)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1883/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4510/10078)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
I/acms    ( 1883): Checking Certificates
I/acms    ( 1883): Checking Developer Certificates
I/acms    ( 1883): Checking Application Certificates
I/acms    ( 1883): Application certificate check KbIQWcDDG5G5l4tMK5_s3XMYvlmdO92lwBPrMsg7vHk (auto)
I/acms    ( 1883): Application certificate check qaGf3V64u9Y95N1vPXH-XsIXrzljUh8mzoxn0V00QaM (auto)
I/acms    ( 1883): Application certificate check Hu1DneCUMHDGpc4aJgrJgtsFTWpU7KTAHp-obi4Tyy4 (auto)
I/acms    ( 1883): Application certificate check OZ7dSWuK-qts6FYIb7pPrafdkOsJSmpx9BxSooxXMgU (auto)
I/acms    ( 1883): Application certificate check fOa4doBU6ydrOw24KazhW_Yle7SYXAx3UcoVmSSPv3Y (auto)
I/acms    ( 1883): Updating next query delay: 75600000
I/mlserverapp( 1883): MirrorLink is never connected, don't setup ACMS programed checks
,I/mlserverapp( 1883): cancelACMSProgrammedChecks
D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
,I/ConnectivityHelper( 1266): [onReceive] WIFI(1): CONNECTED
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4298/10100)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1266/10075)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1437/10028)
D/PMS     (  906): acquireWL(41e4e800): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4298/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1819/10178)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,W/Settings( 4618): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (2472/10021)
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/AccTypeManager( 1330): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): acquireWL(425b8d60): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 906 1000 WorkSource{10106}
E/ExternalAccountType( 1330): Unsupported attribute readOnly
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  906): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  906): Start proc com.google.android.apps.genie.geniewidget for service com.google.android.apps.genie.geniewidget/.sync.SyncAdapterService: pid=4642 uid=10106 gids={50106, 3003, 5012}
D/PMS     (  906): releaseWL(41e4e800): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  906): releaseWL(422a3608): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/SurfaceControl(  906): Excessive delay in blankDisplay() while turning screen off: 374ms
D/PMS     (  906): nativeSetInteractive:false
D/PMS     (  906): nativeSetInteractive:false done
D/PMS     (  906): nativeSetAutoSuspend:true
D/PMS     (  906): nativeSetAutoSuspend:true done
D/HABCtrl (  906): TPE algorithm. remove timeout.
D/PMS     (  906): OOBE c monitor 11
I/InputManager(  906): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  906): screenObserver, isScreenOn=false
,I/InputMethodManagerService(  906): Disable input method client, pid=4426
I/IntentController( 1115): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
V/KeyguardServiceDelegate(  906): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42ddd9c0)
D/NfcService( 1254): ScreenObserver: OFF
,D/NfcService( 1254): applyRouting - 0
,D/NfcService( 1254): applyRouting -2
,V/KeyguardServiceDelegate(  906): **** SHOWN CALLED ****
D/PMN     (  906): wakingUp
D/PMS     (  906): acquireWL(430c4368): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
I/WindowManager(  906): No lock screen! windowToken=null
D/PMN     (  906): onScreenOn
D/PMS     (  906): releaseWL(430c4368): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMS     (  906): acquireWL(43c8f648): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
D/PMS     (  906): releaseWL(43c8f648): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/WirelessDisplayService(  906): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/HtcPowerSaver(  906): updateBatteryInfo
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1577): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1577): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1577): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/MtpService( 2472): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2472): [MTP][onReceive]-
,D/NfcService( 1254): applyRouting - 0
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/NfcService( 1254): applyRouting -2
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/PMS     (  906): acquireWL(43a23db0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  906): releaseWL(43a23db0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,I/ClockThread( 1115): stop update clock
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20522 delay=15s
,D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
D/AlarmManager(  906): ACTION_SCREEN_ON
I/AlarmManager(  906): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done recovering
I/AlarmManager(  906): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done EPS screen off alarm recovering
,D/PMS     (  906): acquireWL(43e19d58): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2231 10028 null
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1177): SET_SCREEN_ON:On
I/wpa_supplicant( 1177): htc_wext_set_keepalive +
I/wpa_supplicant( 1177): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1177): getPrivFuncNum +	
I/wpa_supplicant( 1177): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1177): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1177): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1177): BG scan when screen On
I/wpa_supplicant( 1177): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1177): htc_wext_set_TX_TRACKING - ret = 0
I/wpa_supplicant( 1177): wpa_supplicant_scan enter
I/wpa_supplicant( 1177): Match BG scan, scan!
I/wpa_supplicant( 1177): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1177): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  906):    returned true
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1177): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1177): nl80211: Event message available
D/wpa_supplicant( 1177): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/WIFI_ICON( 1115): WifiActivity: 0
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  906): releaseWL(43e19d58): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
V/SRS_Proc(  370): ParamSet string: screen_state=on
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/GCM     ( 1372): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/NetworkPolicy(  906): updateScreenOn: false
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10028)
D/libc    ( 1372): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1372): [NET] getaddrinfo-,err=8
D/libc    ( 1372): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1372): [NET] getaddrinfo-, 1
,D/libc    ( 1372): [NET] getaddrinfo_proxy+
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10028)
D/PMS     (  906): acquireWL(42e4d7a8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1372 10028 null
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =7399 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2231/10028)
,D/AutoSetting( 1401): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4510): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4510): onReceive CONNECTIVITY_CHANGE networkType=1
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1401/10053)
D/AutoSetting( 1401): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1401): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 1401): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1401): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1401/10053)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4543/10151)
,D/DotMatrix( 1577): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1778): onScreenOn: false
D/PMS     (  906): acquireWL(42454940): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1437 10028 null
D/PMS     (  906): releaseWL(42454940): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1778): onScreenOn: 1453126596565
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1778): onScreenOn: 1453126596565
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4141/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4141/10160)
,D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1819/10178)
I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41ff6f50
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41ff6f50, eanble = 0, strlen(mName) = 91
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  906): Listener[0] = com.htc.smartdim.sensor_eye@4253d1d8
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  906): goingToSleep
,D/PMS     (  906): acquireWL(425fb430): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 906 1000 null
D/AutoSetting( 1401): receiver - intent: android.intent.action.USER_PRESENT
,I/dalvikvm-heap( 4141): Grow heap (frag case) to 13.500MB for 1821008-byte allocation
D/TetherSettings( 3816): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3816): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3816): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3816): Cust_ConnectToPC   : spcsc>false
D/        ( 3816): Cust_ConnectToPC   : IPT>true
D/        ( 3816): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3816): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3816): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3816): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3816): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 3816): onReceive:android.intent.action.USER_PRESENT
D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=20522 mDataStallAlarmIntent=PendingIntent{4252ccd0: PendingIntentRecord{42569438 android broadcastIntent}}
,D/AutoSetting( 1401): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
I/SmartNS_PSService( 3816): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3816): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3816):  defaultType:0
,D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 0
D/AlarmManager(  906): ACTION_SCREEN_OFF
I/AlarmManager(  906): [AlarmQueuing] screen off now: 
I/AlarmManager(  906): [AlarmQueuing] data connection: true
I/AlarmManager(  906): [AlarmQueuing] wifi connection: true
W/ContextImpl( 3816): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  906): acquireWL(43e25720): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 906 1000 null
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4672 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1177): SET_SCREEN_ON:Off
I/wpa_supplicant( 1177): htc_wext_set_keepalive +
I/wpa_supplicant( 1177): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1177): getPrivFuncNum +	
I/wpa_supplicant( 1177): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1177): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1177): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1177): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1177): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 120
,D/WifiStateMachine(  906): BroadcastRSSIForIMS, newrssi =-55 , oldRssi= -200
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 214
D/libc    (  363): [NET]res_nsend:resplen=79
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1372): [NET] getaddrinfo_proxy-, success
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1177): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
D/WIFI_ICON( 1115): updateWifiState: RSSI_CHANGED 3 -> 3
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
V/SRS_Proc(  370): ParamSet string: screen_state=off
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [3][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/NetworkPolicy(  906): updateScreenOn: false
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/ContactMessageStore( 1243): start background delete task...
D/ContactMessageStore( 1243): size: 0 , 0
,D/ContactMessageStore( 1243): Background delete complete
,D/wpa_supplicant( 1177): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl( 4672): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  906): releaseWL(43e25720): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
I/jxcore-log( 4426): Test app app.js loaded
I/jxcore-log( 4426): 
,D/SmartSyncUtils( 4672): isEpsOn(), nState = 0
D/PMS     (  906): acquireWL(441c3790): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4672 1000 null
,I/Choreographer( 4426): Skipped 292 frames!  The application may be doing too much work on its main thread.
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,I/chromium( 4426): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
W/ResourceType( 4426): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4426): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41ad0158 VFEDH.C. .F....ID 0,0-720,1134 #64}
,D/PMS     (  906): releaseWL(441c3790): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
I/CheckinTask( 2231): Sending checkin request (8972 bytes)
D/libc    ( 2231): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2231): [NET] getaddrinfo-,err=8
D/libc    ( 2231): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2231): [NET] getaddrinfo-, 1
D/libc    ( 2231): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =7073 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/SmartSyncUtils( 4672): getMobilePolicyEnabled, result = true
D/PMS     (  906): releaseWL(425fb430): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/NewsWeather( 4642): LocationClient connecting
,W/ContextImpl( 4672): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/DotMatrix( 1577): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1577): [EventService] getTotalRam: 1873 Mb
,D/SmartSyncUtils( 4672): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4672): getMobilePolicyEnabled, result = true
D/PMS     (  906): acquireWL(43cb8098): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1437 10028 null
,D/PMS     (  906): releaseWL(43cb8098): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/SmartSyncUtils( 4672): isEpsOn(), nState = 0
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1778): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1778): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1778): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1778): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1778): onScreenOff
D/WifiService(  906): New client listening to asynchronous messages
,D/AutoSetting( 1401): service - mHandler: cancel location update
,D/AutoSetting( 1401): service -           changes count: 0
,I/NewsWeather( 4642): NewsAccounts: 2, AllSystemAccounts 1.
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4253d1d8
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 1
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4253d1d8, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 0
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4253d1d8, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4253d1d8
E/dalvikvm( 4642): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 4642): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
E/dalvikvm( 4642): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 4642): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 4642): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
E/ActivityThread(  906): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4204ab60 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4204ab60 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,I/ActivityManager(  906): Killing 4298:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/Process (  906): killProcessQuiet, pid=4298
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/libc    ( 1372): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1372): [NET] getaddrinfo-,err=8
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10028)
D/PMS     (  906): acquireWL(43e22e30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
D/PMS     (  906): releaseWL(43e22e30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 247
D/libc    (  363): [NET]res_nsend:resplen=84
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2231): [NET] getaddrinfo_proxy-, success
,I/ProviderInstaller( 4642): Installed default security provider GmsCore_OpenSSL
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(4346a708): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,I/ActivityManager(  906): Recipient 4298
,I/NewsWeather( 4642): Last usage 0, idle 1453126596s, sync interval 2592000s
,I/NewsWeather( 4642): setPeriodicSync in seconds 2592000
,D/PMS     (  906): releaseWL(4346a708): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
W/dalvikvm( 4426): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4426): setDiscoveryMode: Mode set to BLE
I/jxcore-log( 4426): BLE advertisement is supported
I/jxcore-log( 4426): 
I/NewsWeather( 4642): onConnected null
,D/PMS     (  906): acquireWL(441147b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1437 10028 null
,W/GCoreFlp( 1437): No location to return for getLastLocation()
,I/NewsWeather( 4642): LocationClient onConnected: location null
D/PMS     (  906): acquireWL(4322d378): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1437 10028 null
D/PMS     (  906): releaseWL(441147b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/NewsWeather( 4642): Skip sync for lookup editions
,I/NewsWeather( 4642): syncNewsAppData traffic type BACKGROUND_POLL
D/PMS     (  906): releaseWL(4322d378): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/NewsWeather( 4642): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,D/GCM     ( 1372): Connected
W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/PMS     (  906): acquireWL(4323c7a8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1372 10028 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10028)
D/PMS     (  906): releaseWL(42e4d7a8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1372/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10028)
D/libc    ( 2231): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2231): [NET] getaddrinfo-,err=8
,D/PMS     (  906): releaseWL(4323c7a8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,D/PMS     (  906): acquireWL(43704f68): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1372 10028 null
,D/DotMatrix( 1577): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1577): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1115): com.google.android.gms (false,0)
,E/NewsWeather( 4642): Unrecoverable authentication exception
E/NewsWeather( 4642): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4642): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4642): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4642): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4642): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4642): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4642): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4642): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4642): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4642): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41c5c5c0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/libc    ( 4642): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
D/libc    ( 4642): [NET] getaddrinfo-,err=8
D/libc    ( 4642): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    ( 4642): [NET] getaddrinfo-, 1
,D/libc    ( 4642): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =45c4 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,I/RemoteViews.Performance( 1115): com.google.android.gms 2 10 4 12
,D/GCM     ( 1372): Message class mpf
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1372/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1372/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10028)
D/PMS     (  906): releaseWL(43704f68): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  906): acquireWL(432bfff0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
D/PMS     (  906): releaseWL(432bfff0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 215
D/libc    (  363): [NET]res_nsend:resplen=70
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4642): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4642): [NET] getaddrinfo+,hn 15(0x6e6577732e676f),sn(),family 0,flags 4
,D/libc    ( 4642): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
,W/fb4a(:<default>):UserScope( 4481): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4481): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4481): Called registerBroadcastReceiver twice.
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=5 [35][2][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(43d9f5e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(43d9f5e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (2231/10028)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (2231/10028)
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(43d375a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
,D/PMS     (  906): releaseWL(43d375a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
E/NewsWeather( 4642): Failed to syncNewsAppData
,E/NewsWeather( 4642): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42512058): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/SyncManager(  906): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 70941, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/PMS     (  906): releaseWL(425b8d60): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,D/Process (  906): killProcessQuiet, pid=4321
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/AccTypeManager( 1330): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1330): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/ActivityManager(  906): Killing 4321:com.htc.backup/1000 (adj 15): empty #17
D/PMS     (  906): releaseWL(42512058): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1437/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42638400): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
D/PMS     (  906): releaseWL(42638400): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 4321
,D/AccTypeManager( 1330): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
,E/ExternalAccountType( 1330): Unsupported attribute readOnly
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4481/10026)
,D/DotMatrix( 1577): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1577): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 2231): awaiting user notification for token
,I/RemoteViews( 1115): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41c7a6f0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.google.android.gms 2 12 4 12
,I/CheckinTask( 2231): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2231): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2231/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2231/10028)
,D/GCM     ( 1372): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  906): releaseWL(43675ed0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,E/ActivityThread( 2231): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41bcaa98 that was originally bound here
E/ActivityThread( 2231): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41bcaa98 that was originally bound here
E/ActivityThread( 2231): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2231): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2231): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2231): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2231): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2231): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2231): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2231): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2231): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2231): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2231): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2231): 	at bks.a(SourceFile:298)
E/ActivityThread( 2231): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2231): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2231): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2231): 	at java.lang.Thread.run(Thread.java:864)
,I/GCM     ( 1372): GCM config loaded
,D/PMS     (  906): releaseWL(43fa4f88): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =fdb8 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE,
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=172
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  906): Find DNS Address www.htc.com/104.81.130.175
,D/WifiStateMachine(  906): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/wpa_supplicant( 1177): nl80211: Event message available
D/wpa_supplicant( 1177): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1177): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1177): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1177): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1177): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1177): nl80211: Survey data missing
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1177): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1177): Sorted scan results
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1177): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1177): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
D/wpa_supplicant( 1177): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1177): Add randomness: count=12 entropy=0
D/wpa_supplicant( 1177): Add randomness: count=13 entropy=1
D/wpa_supplicant( 1177): Add randomness: count=14 entropy=2
D/wpa_supplicant( 1177): Add randomness: count=15 entropy=3
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1177): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1177): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1177): wpa_supplicant_pick_network+
I/wpa_supplicant( 1177): Selecting BSS from priority group 1
I/wpa_supplicant( 1177): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1177): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1177): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1177): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1177):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1177):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1177): Start print parameters
I/wpa_supplicant( 1177): wpa_s->wpa_state is 9
I/wpa_supplicant( 1177): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1177): isConcurrentMode() is 0
I/wpa_supplicant( 1177): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1177): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1177): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1177): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1177): wpa_s->reassociate is 0
I/wpa_supplicant( 1177): wpa_s->is_screen_on 0
I/wpa_supplicant( 1177): wpa_s->ifname wlan0
I/wpa_supplicant( 1177): End print parameters
I/wpa_supplicant( 1177): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1177): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1177): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1177): clear disabled list - type=1
I/wpa_supplicant( 1177): No suitable network found
W/wpa_supplicant( 1177): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1177): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1177): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1177): nl80211: Survey data missing
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1177): Sorted scan results
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1177): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-5,8
I/wpa_supplicant( 1177): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
D/wpa_supplicant( 1177): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1177): Add randomness: count=16 entropy=4
D/wpa_supplicant( 1177): Add randomness: count=17 entropy=5
D/wpa_supplicant( 1177): Add randomness: count=18 entropy=6
D/wpa_supplicant( 1177): Add randomness: count=19 entropy=7
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1177): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1177): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1177): wpa_supplicant_pick_network+
I/wpa_supplicant( 1177): clear disabled list - type=1
I/wpa_supplicant( 1177): No suitable network found
W/wpa_supplicant( 1177): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1177): State: DISCONNECTED -> INACTIVE
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1177): reply (489) for get BSS: id=0
I/wpa_supplicant( 1177): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1177): freq=5220
I/wpa_supplicant( 1177): level=-48
I/wpa_supplicant( 1177): tsf=0000000116801929
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1177): ssid=NG7005g
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=1
I/wpa_supplicant( 1177): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1177): freq=2412
I/wpa_supplicant( 1177): level=-55
I/wpa_supplicant( 1177): tsf=0000000116801955
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1177): ssid=NG700
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=2
I/wpa_supplicant( 1177): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1177): freq=2412
I/wpa_supplicant( 1177): level=-58
I/wpa_supplicant( 1177): tsf=0000000116801966
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1177): ssid=01ABC
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=3
I/wpa_supplicant( 1177): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1177): freq=2427
I/wpa_supplicant( 1177): level=-77
I/wpa_supplicant( 1177): tsf=0000000116801976
I/wpa_supplicant( 1177): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1177): ssid=Gonzos
I/wpa_supplicant( 1177): ####
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  906): InactiveState{ when=-4ms what=147462 obj=android.net.wifi.StateChangeResult@424a6ad8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-5ms what=147462 obj=android.net.wifi.StateChangeResult@424a6ad8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-5ms what=147462 obj=android.net.wifi.StateChangeResult@424a6ad8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 116801929, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 116801955, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2412, timestamp: 116801966, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2427, timestamp: 116801976, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/GAV2    ( 4543): Thread[GAThread,5,main]: No campaign data found.
,D/AutoSetting( 1502): service - handleMessage() stop self
,D/AutoSetting( 1502): service - onDestroy() END
,D/AutoSetting( 1502): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=4285
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4285:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4285
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/GAV4    ( 4642): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  906): killProcessQuiet, pid=4338
I/ActivityManager(  906): Killing 4338:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Recipient 4338
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  906): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{43dd9ed8 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/wpa_supplicant( 1177): wpa_supplicant_scan enter
I/wpa_supplicant( 1177): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1177): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1177): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1177): nl80211: Event message available
,D/wpa_supplicant( 1177): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  906): acquireWL(42524580): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42524580): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1577): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1577): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1577): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/wpa_supplicant( 1177): nl80211: Event message available
D/wpa_supplicant( 1177): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1177): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1177): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1177): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1177): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1177): nl80211: Survey data missing
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1177): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1177): Sorted scan results
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1177): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1177): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1177): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1177): Add randomness: count=20 entropy=8
D/wpa_supplicant( 1177): Add randomness: count=21 entropy=9
D/wpa_supplicant( 1177): Add randomness: count=22 entropy=10
D/wpa_supplicant( 1177): Add randomness: count=23 entropy=11
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1177): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1177): wpa_supplicant_pick_network+
I/wpa_supplicant( 1177): Selecting BSS from priority group 1
I/wpa_supplicant( 1177): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1177): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1177): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1177): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1177):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1177):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1177): Start print parameters
I/wpa_supplicant( 1177): wpa_s->wpa_state is 9
I/wpa_supplicant( 1177): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1177): isConcurrentMode() is 0
I/wpa_supplicant( 1177): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1177): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1177): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1177): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1177): wpa_s->reassociate is 0
I/wpa_supplicant( 1177): wpa_s->is_screen_on 0
I/wpa_supplicant( 1177): wpa_s->ifname wlan0
I/wpa_supplicant( 1177): End print parameters
I/wpa_supplicant( 1177): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1177): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1177): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1177): clear disabled list - type=1
I/wpa_supplicant( 1177): No suitable network found
W/wpa_supplicant( 1177): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1177): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1177): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1177): nl80211: Survey data missing
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1177): Sorted scan results
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1177): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1177): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1177): BSS: last_scan_res_used=4/32 ,last_scan_full=0
D/wpa_supplicant( 1177): Add randomness: count=24 entropy=12
D/wpa_supplicant( 1177): Add randomness: count=25 entropy=13
D/wpa_supplicant( 1177): Add randomness: count=26 entropy=14
D/wpa_supplicant( 1177): Add randomness: count=27 entropy=15
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1177): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1177): wpa_supplicant_pick_network+
I/wpa_supplicant( 1177): clear disabled list - type=1
I/wpa_supplicant( 1177): No suitable network found
,W/wpa_supplicant( 1177): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1177): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1177): reply (489) for get BSS: id=0
I/wpa_supplicant( 1177): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1177): freq=5220
I/wpa_supplicant( 1177): level=-48
I/wpa_supplicant( 1177): tsf=0000000135033386
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1177): ssid=NG7005g
,I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=1
I/wpa_supplicant( 1177): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1177): freq=2412
I/wpa_supplicant( 1177): level=-55
I/wpa_supplicant( 1177): tsf=0000000135033413
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1177): ssid=NG700
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=2
I/wpa_supplicant( 1177): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1177): freq=2412
I/wpa_supplicant( 1177): level=-58
I/wpa_supplicant( 1177): tsf=0000000135033423
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1177): ssid=01ABC
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=3
I/wpa_supplicant( 1177): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1177): freq=2427
I/wpa_supplicant( 1177): level=-79,
I/wpa_supplicant( 1177): tsf=0000000135033432
I/wpa_supplicant( 1177): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1177): ssid=Gonzos
I/wpa_supplicant( 1177): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiP2pService(  906): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 135033386, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 135033413, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2412, timestamp: 135033423, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 135033432, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42e593d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d3c268: PendingIntentRecord{42465300 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=135467, Int=0
,D/PMS     (  906): acquireWL(42e0a4a0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
D/PMS     (  906): releaseWL(42e593d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(43201518): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42e0a4a0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(43201518): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  906): acquireWL(43b21e10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4233b258: PendingIntentRecord{42338158 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=137345, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43b21e10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4334a220): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4334a220): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/AutoSetting( 1401): service - mHandler: update timezone
,D/AutoSetting( 1502): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1502): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1502): service - onCreate()
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1502): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1502): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/DotMatrix( 1577): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1577): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1502): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1502): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1502): service - mHandler: update timezone
,D/AutoSetting( 1502): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1502): service - processTimeZoneID() system nitz is valid: false (false),
,D/AutoSetting( 1502): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1502): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1577): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1577): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1115): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41b0bc08 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.htc.htclocationservice 1 8 2 11
,D/PMS     (  906): acquireWL(43e6c180): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423cbbe0: PendingIntentRecord{424a00a8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142098, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{41f62988: PendingIntentRecord{42540c10 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=144174, Int=0
,D/AutoSetting( 1401): service - handleMessage() stop self
,D/AutoSetting( 1401): service - handleMessage() quit looper
,D/AutoSetting( 1401): service - onDestroy() END
,D/GpsLocationProvider(  906): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  906): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  906): acquireWL(42c1bc30): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10028)
D/PMS     (  906): releaseWL(43e6c180): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
D/PMS     (  906): acquireWL(439e4438): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
D/PMS     (  906): releaseWL(439e4438): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =c115 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59,
D/libc    (  363): [NET]res_nsend:resplen=243
D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
I/global  (  906): call createSocket() return a new socket.
D/libc    (  906): [NET] getaddrinfo+,hn 14(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  906): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  906): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  906): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  906):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  906): releaseWL(42c1bc30): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,I/wpa_supplicant( 1177): wpa_supplicant_scan enter
I/wpa_supplicant( 1177): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1177): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1177): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1177): nl80211: Event message available
,D/wpa_supplicant( 1177): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/Process (  906): killProcessQuiet, pid=3906
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3906:com.htc.musicenhancer/u0a51 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3906
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/wpa_supplicant( 1177): nl80211: Event message available
D/wpa_supplicant( 1177): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1177): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1177): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1177): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1177): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1177): nl80211: Survey data missing
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1177): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1177): Sorted scan results
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1177): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1177): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1177): Add randomness: count=28 entropy=16
D/wpa_supplicant( 1177): Add randomness: count=29 entropy=17
D/wpa_supplicant( 1177): Add randomness: count=30 entropy=18
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1177): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1177): wpa_supplicant_pick_network+
I/wpa_supplicant( 1177): Selecting BSS from priority group 1
I/wpa_supplicant( 1177): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1177): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1177): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1177): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1177):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1177):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1177): Start print parameters
I/wpa_supplicant( 1177): wpa_s->wpa_state is 9
I/wpa_supplicant( 1177): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1177): isConcurrentMode() is 0
I/wpa_supplicant( 1177): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1177): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1177): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1177): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1177): wpa_s->reassociate is 0
I/wpa_supplicant( 1177): wpa_s->is_screen_on 0
I/wpa_supplicant( 1177): wpa_s->ifname wlan0
I/wpa_supplicant( 1177): End print parameters
I/wpa_supplicant( 1177): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1177): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1177): clear disabled list - type=1
I/wpa_supplicant( 1177): No suitable network found
W/wpa_supplicant( 1177): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1177): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1177): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1177): nl80211: Survey data missing
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1177): Sorted scan results
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1177): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1177): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1177): Add randomness: count=31 entropy=19
D/wpa_supplicant( 1177): Add randomness: count=32 entropy=20
D/wpa_supplicant( 1177): Add randomness: count=33 entropy=21
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1177): ,WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1177): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1177): wpa_supplicant_pick_network+
I/wpa_supplicant( 1177): clear disabled list - type=1
I/wpa_supplicant( 1177): No suitable network found
W/wpa_supplicant( 1177): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1177): State: INACTIVE -> INACTIVE
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1177): reply (489) for get BSS: id=0
I/wpa_supplicant( 1177): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1177): freq=5220
I/wpa_supplicant( 1177): level=-48
I/wpa_supplicant( 1177): tsf=0000000153185665
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1177): ssid=NG7005g
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=1
I/wpa_supplicant( 1177): bssid=c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 1177): freq=2412
I/wpa_supplicant( 1177): level=-55
I/wpa_supplicant( 1177): tsf=0000000153185693
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1177): ssid=NG700
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=2
I/wpa_supplicant( 1177): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1177): freq=2412
I/wpa_supplicant( 1177): level=-58
I/wpa_supplicant( 1177): tsf=0000000135033423
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1177): ssid=01ABC
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=3
I/wpa_supplicant( 1177): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1177): freq=2427
I/wpa_supplicant( 1177): level=-79
I/wpa_supplicant( 1177): tsf=0000000153185704
I/wpa_supplicant( 1177): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1177): ssid=Gonzos
I/wpa_supplicant( 1177): ####
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 153185665, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 153185693, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2412, timestamp: 135033423, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 153185704, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{42c3ea90 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  906): acquireWL(436fcd68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d3c268: PendingIntentRecord{42465300 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=165485, Int=0
,D/PMS     (  906): acquireWL(43d94c60): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): releaseWL(436fcd68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(43b1cf30): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=5 [54][3][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): acquireWL(43d61e10): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 906 1000 WorkSource{10106}
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(43d94c60): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  906): releaseWL(43b1cf30): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(4414b340): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(4414b340): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/NewsWeather( 4642): Last usage 0, idle 1453126648s, sync interval 2592000s
,I/NewsWeather( 4642): setPeriodicSync in seconds 2592000
,I/NewsWeather( 4642): Skip sync for lookup editions
,I/NewsWeather( 4642): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4642): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1577): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1577): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1115): com.google.android.gms (false,0)
,E/NewsWeather( 4642): Unrecoverable authentication exception
E/NewsWeather( 4642): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4642): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4642): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4642): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4642): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4642): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4642): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4642): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4642): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4642): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41bf1df8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.google.android.gms 2 12 5 12
,E/NewsWeather( 4642): Failed to syncNewsAppData
,E/NewsWeather( 4642): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  906): acquireWL(43da60d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42630878): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(43da60d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/SyncManager(  906): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 115208, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  906): releaseWL(43d61e10): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,W/AccTypeManager( 1330): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1330): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  906): releaseWL(42630878): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(43465920): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1437/10028)
,D/AccTypeManager( 1330): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/PMS     (  906): releaseWL(43465920): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/ExternalAccountType( 1330): Unsupported attribute readOnly
,I/wpa_supplicant( 1177): wpa_supplicant_scan enter
I/wpa_supplicant( 1177): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1177): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1177): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1177): nl80211: Event message available
,D/wpa_supplicant( 1177): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1177): nl80211: Event message available
D/wpa_supplicant( 1177): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1177): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1177): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1177): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1177): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1177): nl80211: Survey data missing
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1177): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1177): Sorted scan results
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1177): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-75
D/wpa_supplicant( 1177): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1177): Add randomness: count=34 entropy=22
D/wpa_supplicant( 1177): Add randomness: count=35 entropy=23
D/wpa_supplicant( 1177): Add randomness: count=36 entropy=24
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1177): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1177): wpa_supplicant_pick_network+
I/wpa_supplicant( 1177): Selecting BSS from priority group 1
I/wpa_supplicant( 1177): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1177): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1177): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1177): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1177):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1177):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1177): Start print parameters
I/wpa_supplicant( 1177): wpa_s->wpa_state is 9
I/wpa_supplicant( 1177): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1177): isConcurrentMode() is 0
I/wpa_supplicant( 1177): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1177): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1177): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1177): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1177): wpa_s->reassociate is 0
I/wpa_supplicant( 1177): wpa_s->is_screen_on 0
I/wpa_supplicant( 1177): wpa_s->ifname wlan0
I/wpa_supplicant( 1177): End print parameters
I/wpa_supplicant( 1177): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1177): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1177): clear disabled list - type=1
I/wpa_supplicant( 1177): No suitable network found
W/wpa_supplicant( 1177): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1177): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1177): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1177): nl80211: Survey data missing
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1177): Sorted scan results
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1177): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-75
D/wpa_supplicant( 1177): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1177): Add randomness: count=37 entropy=25
D/wpa_supplicant( 1177): Add randomness: count=38 entropy=26
D/wpa_supplicant( 1177): Add randomness: count=39 entropy=27
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len,=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1177): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1177): wpa_supplicant_pick_network+
I/wpa_supplicant( 1177): clear disabled list - type=1
I/wpa_supplicant( 1177): No suitable network found
W/wpa_supplicant( 1177): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1177): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0,
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1177): reply (376) for get BSS: id=0
I/wpa_supplicant( 1177): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1177): freq=5220
I/wpa_supplicant( 1177): level=-48
I/wpa_supplicant( 1177): tsf=0000000171222059
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1177): ssid=NG7005g
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=1
I/wpa_supplicant( 1177): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1177): freq=2412
I/wpa_supplicant( 1177): level=-56
I/wpa_supplicant( 1177): tsf=0000000171222086
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1177): ssid=NG700
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=3
I/wpa_supplicant( 1177): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1177): freq=2427
I/wpa_supplicant( 1177): level=-75
I/wpa_supplicant( 1177): tsf=0000000153185704
I/wpa_supplicant( 1177): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1177): ssid=Gonzos
I/wpa_supplicant( 1177): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 171222059, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 171222086, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2427, timestamp: 153185704, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 3 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (3) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/AutoSetting( 1502): service - handleMessage() stop self
,D/AutoSetting( 1502): service - onDestroy() END
,D/AutoSetting( 1502): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=4355
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4355:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4355
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TelephonyReceiver( 1243): switchBindHtcMsgCursor: null
,I/wpa_supplicant( 1177): wpa_supplicant_scan enter
I/wpa_supplicant( 1177): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1177): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1177): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1177): nl80211: Event message available
,D/wpa_supplicant( 1177): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1177): nl80211: Event message available
D/wpa_supplicant( 1177): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1177): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1177): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1177): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1177): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1177): nl80211: Survey data missing
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1177): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1177): Sorted scan results
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1177): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-75
I/wpa_supplicant( 1177): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-89
I/wpa_supplicant( 1177): [NULL] e8:40:f2:d6:e0:6b freq=2412 level=-90
D/wpa_supplicant( 1177): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1177): Add randomness: count=40 entropy=28
D/wpa_supplicant( 1177): Add randomness: count=41 entropy=29
D/wpa_supplicant( 1177): Add randomness: count=42 entropy=30
D/wpa_supplicant( 1177): Add randomness: count=43 entropy=31
D/wpa_supplicant( 1177): Add randomness: count=44 entropy=32
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1177): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1177): wpa_supplicant_pick_network+
I/wpa_supplicant( 1177): Selecting BSS from priority group 1
I/wpa_supplicant( 1177): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1177): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1177): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1177): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1177):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1177):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1177): Start print parameters
I/wpa_supplicant( 1177): wpa_s->wpa_state is 9
I/wpa_supplicant( 1177): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1177): isConcurrentMode() is 0
I/wpa_supplicant( 1177): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1177): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1177): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1177): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1177): wpa_s->reassociate is 0
I/wpa_supplicant( 1177): wpa_s->is_screen_on 0
I/wpa_supplicant( 1177): wpa_s->ifname wlan0
I/wpa_supplicant( 1177): End print parameters
I/wpa_supplicant( 1177): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1177): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1177): 3: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1177): 4: e8:40:f2:d6:e0:6b ssid='WDA83' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1177): clear disabled list - type=1
I/wpa_supplicant( 1177): No suitable network found
W/wpa_supplicant( 1177): wlan0: Not restrict scheduled scan for Not WFD CT3
,D/wpa_supplicant( 1177): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1177): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1177): nl80211: Survey data missing
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1177): Sorted scan results
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1177): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-75
I/wpa_supplicant( 1177): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-89
I/wpa_supplicant( 1177): [NULL] e8:40:f2:d6:e0:6b freq=2412 level=-90
D/wpa_supplicant( 1177): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1177): Add randomness: count=45 entropy=33
D/wpa_supplicant( 1177): Add randomness: count=46 entropy=34
,D/wpa_supplicant( 1177): Add randomness: count=47 entropy=35
D/wpa_supplicant( 1177): Add randomness: count=48 entropy=36
D/wpa_supplicant( 1177): Add randomness: count=49 entropy=37
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1177): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1177): wpa_supplicant_pick_network+
I/wpa_supplicant( 1177): clear disabled list - type=1
I/wpa_supplicant( 1177): No suitable network found
W/wpa_supplicant( 1177): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1177): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1177): reply (632) for get BSS: id=0
I/wpa_supplicant( 1177): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1177): freq=5220
I/wpa_supplicant( 1177): level=-48
I/wpa_supplicant( 1177): tsf=0000000189523768
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1177): ssid=NG7005g
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=1
I/wpa_supplicant( 1177): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1177): freq=2412
I/wpa_supplicant( 1177): level=-56
I/wpa_supplicant( 1177): tsf=0000000189523794
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1177): ssid=NG700
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=3
I/wpa_supplicant( 1177): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1177): freq=2427
I/wpa_supplicant( 1177): level=-75
I/wpa_supplicant( 1177): tsf=0000000189523804
I/wpa_supplicant( 1177): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1177): ssid=Gonzos
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=4
I/wpa_supplicant( 1177): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1177): freq=2437
I/wpa_supplicant( 1177): level=-89
I/wpa_supplicant( 1177): tsf=0000000189523825
I/wpa_supplicant( 1177): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1177): ssid=UPC Wi-Free
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=5
I/wpa_supplicant( 1177): bssid=e8:40:f2:d6:e0:6b
I/wpa_supplicant( 1177): freq=2412
I/wpa_supplicant( 1177): level=-90
I/wpa_supplicant( 1177): tsf=0000000189523815
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1177): ssid=WDA83
I/wpa_supplicant( 1177): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 189523768, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 189523794, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2427, timestamp: 189523804, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2437, timestamp: 189523825, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: WDA83, BSSID: e8:40:f2:d6:e0:6b, capabilities: [WPA2-PSK-CCMP][ESS], level: -90, frequency: 2412, timestamp: 189523815, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 5 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0,
V/ScoreHelper(  906):  + ScoreResult:  80, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  9 [2427], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  76, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-89], Tx: 13, Freq:  9 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  71, AP:                            WDA83 [e8:40:f2:d6:e0:6b], Rssi:  0 [-90], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (5) end of scan result ==
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(43d5d390): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43d5d390): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(43d98560): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,D/PMS     (  906): acquireWL(43f94ea0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d3c268: PendingIntentRecord{42465300 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=195538, Int=0
D/PMS     (  906): releaseWL(43f94ea0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(4330bca0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(43d98560): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(4330bca0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  906): acquireWL(4369f0b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4233b258: PendingIntentRecord{42338158 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=197345, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4369f0b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1177): wpa_supplicant_scan enter
I/wpa_supplicant( 1177): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1177): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1177): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1177): nl80211: Event message available
,D/wpa_supplicant( 1177): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1177): nl80211: Event message available
D/wpa_supplicant( 1177): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1177): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1177): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1177): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1177): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1177): nl80211: Survey data missing
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1177): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1177): Sorted scan results
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1177): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-75
I/wpa_supplicant( 1177): [NULL] e8:40:f2:d6:e0:6b freq=2412 level=-89
I/wpa_supplicant( 1177): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-89
D/wpa_supplicant( 1177): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1177): Add randomness: count=50 entropy=38
D/wpa_supplicant( 1177): Add randomness: count=51 entropy=39
D/wpa_supplicant( 1177): Add randomness: count=52 entropy=40
D/wpa_supplicant( 1177): Add randomness: count=53 entropy=41
D/wpa_supplicant( 1177): Add randomness: count=54 entropy=42
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1177): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1177): wpa_supplicant_pick_network+
I/wpa_supplicant( 1177): Selecting BSS from priority group 1
I/wpa_supplicant( 1177): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1177): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1177): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1177): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1177):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1177):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1177): Start print parameters
I/wpa_supplicant( 1177): wpa_s->wpa_state is 9
I/wpa_supplicant( 1177): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1177): isConcurrentMode() is 0
I/wpa_supplicant( 1177): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1177): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1177): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1177): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1177): wpa_s->reassociate is 0
I/wpa_supplicant( 1177): wpa_s->is_screen_on 0
I/wpa_supplicant( 1177): wpa_s->ifname wlan0
I/wpa_supplicant( 1177): End print parameters
I/wpa_supplicant( 1177): Do nothing, wait SELECT_BSSID CMD...
,D/wpa_supplicant( 1177): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1177): 3: e8:40:f2:d6:e0:6b ssid='WDA83' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1177): 4: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1177): clear disabled list - type=1
I/wpa_supplicant( 1177): No suitable network found
W/wpa_supplicant( 1177): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1177): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1177): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1177): nl80211: Survey data missing
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1177): Sorted scan results
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
,I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1177): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-75
I/wpa_supplicant( 1177): [NULL] e8:40:f2:d6:e0:6b freq=2412 level=-89
I/wpa_supplicant( 1177): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-89
D/wpa_supplicant( 1177): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1177): Add randomness: count=55 entropy=43
D/wpa_supplicant( 1177): Add randomness: count=56 entropy=44
D/wpa_supplicant( 1177): Add randomness: count=57 entropy=45
D/wpa_supplicant( 1177): Add randomness: count=58 entropy=46
D/wpa_supplicant( 1177): Add randomness: count=59 entropy=47
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0,
D/wpa_supplicant( 1177): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1177): wpa_supplicant_pick_network+
I/wpa_supplicant( 1177): clear disabled list - type=1
I/wpa_supplicant( 1177): No suitable network found
W/wpa_supplicant( 1177): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1177): State: INACTIVE -> INACTIVE
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1177): reply (632) for get BSS: id=0
I/wpa_supplicant( 1177): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1177): freq=5220
I/wpa_supplicant( 1177): level=-48
I/wpa_supplicant( 1177): tsf=0000000207713677
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1177): ssid=NG7005g
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=1
I/wpa_supplicant( 1177): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1177): freq=2412
I/wpa_supplicant( 1177): level=-56
I/wpa_supplicant( 1177): tsf=0000000207713703
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1177): ssid=NG700
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=3
I/wpa_supplicant( 1177): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1177): freq=2427
I/wpa_supplicant( 1177): level=-75
I/wpa_supplicant( 1177): tsf=0000000207713714
I/wpa_supplicant( 1177): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1177): ssid=Gonzos
,I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=4
I/wpa_supplicant( 1177): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1177): freq=2437
I/wpa_supplicant( 1177): level=-89
I/wpa_supplicant( 1177): tsf=0000000207713724
I/wpa_supplicant( 1177): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1177): ssid=UPC Wi-Free
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=5
I/wpa_supplicant( 1177): bssid=e8:40:f2:d6:e0:6b
I/wpa_supplicant( 1177): freq=2412
I/wpa_supplicant( 1177): level=-89
I/wpa_supplicant( 1177): tsf=0000000207713735
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1177): ssid=WDA83
I/wpa_supplicant( 1177): ####
D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 207713677, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 207713703, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2427, timestamp: 207713714, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  906): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2437, timestamp: 207713724, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: WDA83, BSSID: e8:40:f2:d6:e0:6b, capabilities: [WPA2-PSK-CCMP][ESS], level: -89, frequency: 2412, timestamp: 207713735, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 5 to mScanResults
V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  80, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  9 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  76, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-89], Tx: 13, Freq:  9 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  75, AP:                            WDA83 [e8:40:f2:d6:e0:6b], Rssi:  4 [-89], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (5) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1177): wpa_supplicant_scan enter
I/wpa_supplicant( 1177): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1177): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1177): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1177): nl80211: Event message available
,D/wpa_supplicant( 1177): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1177): nl80211: Event message available
D/wpa_supplicant( 1177): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1177): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1177): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1177): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1177): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1177): nl80211: Survey data missing
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1177): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1177): Sorted scan results
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1177): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1177): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-75
I/wpa_supplicant( 1177): [NULL] e8:40:f2:d6:e0:6b freq=2412 level=-89
I/wpa_supplicant( 1177): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-89
D/wpa_supplicant( 1177): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1177): Add randomness: count=60 entropy=48
D/wpa_supplicant( 1177): Add randomness: count=61 entropy=49
D/wpa_supplicant( 1177): Add randomness: count=62 entropy=50
D/wpa_supplicant( 1177): Add randomness: count=63 entropy=51
D/wpa_supplicant( 1177): Add randomness: count=64 entropy=52
D/wpa_supplicant( 1177): Add randomness: count=65 entropy=53
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1177): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1177): wpa_supplicant_pick_network+
I/wpa_supplicant( 1177): Selecting BSS from priority group 1
I/wpa_supplicant( 1177): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1177): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1177): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1177): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1177): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1177):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1177):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1177): Start print parameters
I/wpa_supplicant( 1177): wpa_s->wpa_state is 9
I/wpa_supplicant( 1177): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1177): isConcurrentMode() is 0
I/wpa_supplicant( 1177): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1177): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1177): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1177): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1177): wpa_s->reassociate is 0
I/wpa_supplicant( 1177): wpa_s->is_screen_on 0
I/wpa_supplicant( 1177): wpa_s->ifname wlan0
I/wpa_supplicant( 1177): End print parameters
I/wpa_supplicant( 1177): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1177): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1177): 4: e8:40:f2:d6:e0:6b ssid='WDA83' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1177): 5: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1177): clear disabled list - type=1
I/wpa_supplicant( 1177): No suitable network found
W/wpa_supplicant( 1177): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1177): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 32
,D/wpa_supplicant( 1177): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1177): nl80211: Survey data missing
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1177): Sorted scan results
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1177): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1177): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-75
I/wpa_supplicant( 1177): [NULL] e8:40:f2:d6:e0:6b freq=2412 level=-89
,I/wpa_supplicant( 1177): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-89
D/wpa_supplicant( 1177): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1177): Add randomness: count=66 entropy=54
D/wpa_supplicant( 1177): Add randomness: count=67 entropy=55
D/wpa_supplicant( 1177): Add randomness: count=68 entropy=56
D/wpa_supplicant( 1177): Add randomness: count=69 entropy=57
D/wpa_supplicant( 1177): Add randomness: count=70 entropy=58
D/wpa_supplicant( 1177): Add randomness: count=71 entropy=59
,D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1177): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1177): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1177): wpa_supplicant_pick_network+
,I/wpa_supplicant( 1177): clear disabled list - type=1
I/wpa_supplicant( 1177): No suitable network found
W/wpa_supplicant( 1177): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1177): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1177): reply (745) for get BSS: id=0
I/wpa_supplicant( 1177): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1177): freq=5220
I/wpa_supplicant( 1177): level=-48
I/wpa_supplicant( 1177): tsf=0000000225913293
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][WPS][ESS],
I/wpa_supplicant( 1177): ssid=NG7005g
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=1
I/wpa_supplicant( 1177): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1177): freq=2412
I/wpa_supplicant( 1177): level=-56
I/wpa_supplicant( 1177): tsf=0000000225913333
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1177): ssid=NG700
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=3
I/wpa_supplicant( 1177): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1177): freq=2427
I/wpa_supplicant( 1177): level=-75
I/wpa_supplicant( 1177): tsf=0000000225913344
I/wpa_supplicant( 1177): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1177): ssid=Gonzos
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=4
I/wpa_supplicant( 1177): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1177): freq=2437
I/wpa_supplicant( 1177): level=-89
I/wpa_supplicant( 1177): tsf=0000000225913420
I/wpa_supplicant( 1177): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1177): ssid=UPC Wi-Free
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=5
I/wpa_supplicant( 1177): bssid=e8:40:f2:d6:e0:6b
I/wpa_supplicant( 1177): freq=2412
,I/wpa_supplicant( 1177): level=-89
I/wpa_supplicant( 1177): tsf=0000000225913434
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1177): ssid=WDA83
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=6
I/wpa_supplicant( 1177): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1177): freq=2412
I/wpa_supplicant( 1177): level=-55
I/wpa_supplicant( 1177): tsf=0000000225913320
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1177): ssid=01ABC
I/wpa_supplicant( 1177): ####
D/WirelessDisplayService(  906): getDiscoveryDongleList
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 225913293, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 225913333, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2427, timestamp: 225913344, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2437, timestamp: 225913420, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: WDA83, BSSID: e8:40:f2:d6:e0:6b, capabilities: [WPA2-PSK-CCMP][ESS], level: -89, frequency: 2412, timestamp: 225913434, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  80, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq:  9 [2427], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  76, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-89], Tx: 13, Freq:  9 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): 5: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 225913320, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 6 to mScanResults
,V/ScoreHelper(  906):  + ScoreResult:  73, AP:                            WDA83 [e8:40:f2:d6:e0:6b], Rssi:  4 [-89], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (6) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(43d985d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d3c268: PendingIntentRecord{42465300 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=228559, Int=0
,D/PMS     (  906): acquireWL(43e4e8f8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
D/PMS     (  906): releaseWL(43d985d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(43ce32a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=3 [26][1][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(43ce7b10): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 906 1000 WorkSource{10106}
D/PMS     (  906): releaseWL(43e4e8f8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  906): releaseWL(43ce32a0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(424cf8d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(424cf8d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/NewsWeather( 4642): Last usage 0, idle 1453126711s, sync interval 2592000s
,I/NewsWeather( 4642): setPeriodicSync in seconds 2592000
,I/NewsWeather( 4642): Skip sync for lookup editions
,I/NewsWeather( 4642): syncNewsAppData traffic type BACKGROUND_POLL
,I/NewsWeather( 4642): ApiOperation url https://news.google.com/news/exec/fetchNewsApp
,W/GLSUser ( 1372): GoogleAccountDataService.getToken()
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1372): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/newsreader
,W/GLSActivity( 1372): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1577): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1577): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1115): com.google.android.gms (false,0)
,E/NewsWeather( 4642): Unrecoverable authentication exception
E/NewsWeather( 4642): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/NewsWeather( 4642): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/NewsWeather( 4642): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/NewsWeather( 4642): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.hJ(SourceFile:166)
E/NewsWeather( 4642): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:185)
E/NewsWeather( 4642): 	at com.google.android.apps.genie.geniewidget.sync.ApiClient.a(SourceFile:109)
E/NewsWeather( 4642): 	at com.google.android.apps.genie.geniewidget.sync.c.a(SourceFile:291)
E/NewsWeather( 4642): 	at com.google.android.apps.genie.geniewidget.sync.h.y(SourceFile:148)
E/NewsWeather( 4642): 	at com.google.android.apps.genie.geniewidget.sync.h.u(SourceFile:80)
E/NewsWeather( 4642): 	at com.google.android.apps.genie.geniewidget.sync.h.onPerformSync(SourceFile:70)
E/NewsWeather( 4642): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41c19c88 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.google.android.gms 3 10 4 12
,D/PMS     (  906): acquireWL(438af550): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10028 null
,E/NewsWeather( 4642): Failed to syncNewsAppData
,E/NewsWeather( 4642): Down sync of news app Failed, error code: SYNC_IO_ERROR
D/PMS     (  906): releaseWL(438af550): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(43d10f60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/SyncManager(  906): failed sync operation  u0 (com.google), com.google.android.apps.genie.geniewidget, PERIODIC, latestRunTime 165882, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
D/PMS     (  906): releaseWL(43ce7b10): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.genie.geniewidget/com.google/***** 0x1 WorkSource{10106}
,D/PMS     (  906): releaseWL(43d10f60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/AccTypeManager( 1330): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1330): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1437/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(43dfabe8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/AccTypeManager( 1330): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/PMS     (  906): releaseWL(43dfabe8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/ExternalAccountType( 1330): Unsupported attribute readOnly
,D/PMS     (  906): acquireWL(43e852f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{436f51a8: PendingIntentRecord{43395970 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=232566, Int=0
,I/ActivityManager(  906): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4727 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  906): sending alarm PendingIntent{423059c0: PendingIntentRecord{424d7008 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1453126704123, Int=10800000
,D/PMS     (  906): releaseWL(43e852f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.aurora (4727/10047)
,D/Process (  906): killProcessQuiet, pid=4370
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4370:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4370
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2231/10028)
,D/PMS     (  906): acquireWL(43ca34d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10026}
,V/AlarmManager(  906): sending alarm PendingIntent{42c55a20: PendingIntentRecord{43e06828 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=233808, Int=120000
,V/AlarmManager(  906): sending alarm PendingIntent{42342af0: PendingIntentRecord{43395970 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=233935, Int=0
,D/PMS     (  906): releaseWL(43ca34d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,I/wpa_supplicant( 1177): wpa_supplicant_scan enter
I/wpa_supplicant( 1177): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1177): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1177): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1177): nl80211: Event message available
,D/wpa_supplicant( 1177): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1177): nl80211: Event message available
D/wpa_supplicant( 1177): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1177): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1177): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1177): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1177): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1177): nl80211: Survey data missing
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1177): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1177): Sorted scan results
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1177): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1177): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
I/wpa_supplicant( 1177): [NULL] e8:40:f2:d6:e0:6b freq=2412 level=-89
D/wpa_supplicant( 1177): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1177): Add randomness: count=72 entropy=60
D/wpa_supplicant( 1177): Add randomness: count=73 entropy=61
D/wpa_supplicant( 1177): Add randomness: count=74 entropy=62
D/wpa_supplicant( 1177): Add randomness: count=75 entropy=63
D/wpa_supplicant( 1177): Add randomness: count=76 entropy=64
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1177): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1177): wpa_supplicant_pick_network+
I/wpa_supplicant( 1177): Selecting BSS from priority group 1
I/wpa_supplicant( 1177): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1177): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1177): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1177): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1177): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1177):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1177):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1177): Start print parameters
I/wpa_supplicant( 1177): wpa_s->wpa_state is 9
I/wpa_supplicant( 1177): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1177): isConcurrentMode() is 0
I/wpa_supplicant( 1177): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1177): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1177): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1177): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1177): wpa_s->reassociate is 0
I/wpa_supplicant( 1177): wpa_s->is_screen_on 0
I/wpa_supplicant( 1177): wpa_s->ifname wlan0
I/wpa_supplicant( 1177): End print parameters
I/wpa_supplicant( 1177): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1177): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1177): 4: e8:40:f2:d6:e0:6b ssid='WDA83' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1177): clear disabled list - type=1
I/wpa_supplicant( 1177): No suitable network found
W/wpa_supplicant( 1177): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1177): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1177): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1177): nl80211: Survey data missing
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1177): Sorted scan results
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 11,77): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1177): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
I/wpa_supplicant( 1177): [NULL] e8:40:f2:d6:e0:6b freq=2412 level=-89
D/wpa_supplicant( 1177): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1177): Add randomness: count=77 entropy=65
D/wpa_supplicant( 1177): Add randomness: count=78 entropy=66
D/wpa_supplicant( 1177): Add randomness: count=79 entropy=67
D/wpa_supplicant( 1177): Add randomness: count=80 entropy=68
D/wpa_supplicant( 1177): Add randomness: count=81 entropy=69
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1177): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,I/wpa_supplicant( 1177): wpa_supplicant_pick_network+
I/wpa_supplicant( 1177): clear disabled list - type=1
I/wpa_supplicant( 1177): No suitable network found
W/wpa_supplicant( 1177): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1177): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1177): reply (745) for get BSS: id=0
I/wpa_supplicant( 1177): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1177): freq=5220
I/wpa_supplicant( 1177): level=-48
I/wpa_supplicant( 1177): tsf=0000000244123452
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1177): ssid=NG7005g
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=1
I/wpa_supplicant( 1177): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1177): freq=2412
I/wpa_supplicant( 1177): level=-56,
I/wpa_supplicant( 1177): tsf=0000000244123489
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1177): ssid=NG700
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=3
I/wpa_supplicant( 1177): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1177): freq=2427
I/wpa_supplicant( 1177): level=-79
I/wpa_supplicant( 1177): tsf=0000000244123500
I/wpa_supplicant( 1177): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1177): ssid=Gonzos
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=4
I/wpa_supplicant( 1177): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1177): freq=2437
I/wpa_supplicant( 1177): level=-89
I/wpa_supplicant( 1177): tsf=0000000225913420
I/wpa_supplicant( 1177): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1177): ssid=UPC Wi-Free
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=5
I/wpa_supplicant( 1177): bssid=e8:40:f2:d6:e0:6b
I/wpa_supplicant( 1177): freq=2412
I/wpa_supplicant( 1177): level=-89
I/wpa_supplicant( 1177): tsf=0000000244123510
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1177): ssid=WDA83
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=6
I/wpa_supplicant( 1177): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1177): freq=2412
I/wpa_supplicant( 1177): level=-55
I/wpa_supplicant( 1177): tsf=0000000244123478
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1177): ssid=01ABC
I/wpa_supplicant( 1177): ####
,D/WirelessDisplayService(  906): getDiscoveryDongleList
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 244123452, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 244123489, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 244123500, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0,
D/WifiStateMachine(  906): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2437, timestamp: 225913420, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: WDA83, BSSID: e8:40:f2:d6:e0:6b, capabilities: [WPA2-PSK-CCMP][ESS], level: -89, frequency: 2412, timestamp: 244123510, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 5: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 244123478, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 6 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  80, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  9 [2427], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  76, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-89], Tx: 13, Freq:  9 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                            WDA83 [e8:40:f2:d6:e0:6b], Rssi:  4 [-89], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (6) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(43db5688): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43db5688): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42591bf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4233b258: PendingIntentRecord{42338158 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=257345, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42591bf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(438528a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
D/PMS     (  906): acquireWL(439e68f0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,V/AlarmManager(  906): sending alarm PendingIntent{41d3c268: PendingIntentRecord{42465300 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=258597, Int=0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(43cafc78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(438528a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): releaseWL(439e68f0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(43cafc78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/wpa_supplicant( 1177): wpa_supplicant_scan enter
I/wpa_supplicant( 1177): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1177): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1177): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1177): nl80211: Event message available
,D/wpa_supplicant( 1177): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,D/wpa_supplicant( 1177): nl80211: Event message available
D/wpa_supplicant( 1177): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1177): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1177): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1177): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1177): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1177): nl80211: Survey data missing
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1177): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1177): Sorted scan results
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1177): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1177): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-76
D/wpa_supplicant( 1177): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1177): Add randomness: count=82 entropy=70
D/wpa_supplicant( 1177): Add randomness: count=83 entropy=71
D/wpa_supplicant( 1177): Add randomness: count=84 entropy=72
D/wpa_supplicant( 1177): Add randomness: count=85 entropy=73
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1177): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1177): wpa_supplicant_pick_network+
I/wpa_supplicant( 1177): Selecting BSS from priority group 1
I/wpa_supplicant( 1177): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1177): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1177): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1177): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1177): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1177):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1177):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1177): Start print parameters
I/wpa_supplicant( 1177): wpa_s->wpa_state is 9
I/wpa_supplicant( 1177): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1177): isConcurrentMode() is 0
I/wpa_supplicant( 1177): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1177): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1177): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1177): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1177): wpa_s->reassociate is 0
I/wpa_supplicant( 1177): wpa_s->is_screen_on 0
I/wpa_supplicant( 1177): wpa_s->ifname wlan0
I/wpa_supplicant( 1177): End print parameters
I/wpa_supplicant( 1177): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1177): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1177): clear disabled list - type=1
I/wpa_supplicant( 1177): No suitable network found
W/wpa_supplicant( 1177): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1177): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1177): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1177): nl80211: Survey data missing
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1177): Sorted scan results
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1177): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1177): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-76
D/wpa_supplicant( 1177): BSS: last_scan_res_used=4/3,2 last_scan_full=0
D/wpa_supplicant( 1177): Add randomness: count=86 entropy=74
D/wpa_supplicant( 1177): Add randomness: count=87 entropy=75
D/wpa_supplicant( 1177): Add randomness: count=88 entropy=76
D/wpa_supplicant( 1177): Add randomness: count=89 entropy=77
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1177): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1177): wpa_supplicant_pick_network+
I/wpa_supplicant( 1177): clear disabled list - type=1
I/wpa_supplicant( 1177): No suitable network found
W/wpa_supplicant( 1177): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1177): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1177): reply (602) for get BSS: id=0
I/wpa_supplicant( 1177): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1177): freq=5220
I/wpa_supplicant( 1177): level=-48
I/wpa_supplicant( 1177): tsf=0000000262333161
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1177): ssid=NG7005g
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=1
I/wpa_supplicant( 1177): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1177): freq=2412
I/wpa_supplicant( 1177): level=-56
I/wpa_supplicant( 1177): tsf=0000000262333188
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1177): ssid=NG700
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=3
I/wpa_supplicant( 1177): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1177): freq=2427
I/wpa_supplicant( 1177): level=-76
I/wpa_supplicant( 1177): tsf=0000000262333208
I/wpa_supplicant( 1177): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1177): ssid=Gonzos
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=5
I/wpa_supplicant( 1177): bssid=e8:40:f2:d6:e0:6b
I/wpa_supplicant( 1177): freq=2412
I/wpa_supplicant( 1177): level=-89,
I/wpa_supplicant( 1177): tsf=0000000244123510
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1177): ssid=WDA83
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=6
I/wpa_supplicant( 1177): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1177): freq=2412
I/wpa_supplicant( 1177): level=-55
I/wpa_supplicant( 1177): tsf=0000000262333199
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1177): ssid=01ABC
I/wpa_supplicant( 1177): ####
D/WifiP2pService(  906): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 262333161, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 262333188, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2427, timestamp: 262333208, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: WDA83, BSSID: e8:40:f2:d6:e0:6b, capabilities: [WPA2-PSK-CCMP][ESS], level: -89, frequency: 2412, timestamp: 244123510, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 262333199, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 5 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  73, AP:                            WDA83 [e8:40:f2:d6:e0:6b], Rssi:  4 [-89], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (5) end of scan result ==
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1177): wpa_supplicant_scan enter
I/wpa_supplicant( 1177): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1177): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1177): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1177): nl80211: Event message available
,D/wpa_supplicant( 1177): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1177): nl80211: Event message available
D/wpa_supplicant( 1177): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1177): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1177): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1177): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1177): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1177): nl80211: Survey data missing
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1177): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1177): Sorted scan results
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1177): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1177): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
D/wpa_supplicant( 1177): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1177): Add randomness: count=90 entropy=78
D/wpa_supplicant( 1177): Add randomness: count=91 entropy=79
D/wpa_supplicant( 1177): Add randomness: count=92 entropy=80
D/wpa_supplicant( 1177): Add randomness: count=93 entropy=81
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1177): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1177): wpa_supplicant_pick_network+
I/wpa_supplicant( 1177): Selecting BSS from priority group 1
I/wpa_supplicant( 1177): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1177): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1177): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1177): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1177):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1177):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1177): Start print parameters
I/wpa_supplicant( 1177): wpa_s->wpa_state is 9
I/wpa_supplicant( 1177): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1177): isConcurrentMode() is 0
I/wpa_supplicant( 1177): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1177): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1177): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1177): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1177): wpa_s->reassociate is 0
I/wpa_supplicant( 1177): wpa_s->is_screen_on 0
I/wpa_supplicant( 1177): wpa_s->ifname wlan0
I/wpa_supplicant( 1177): End print parameters
I/wpa_supplicant( 1177): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1177): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1177): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1177): clear disabled list - type=1
I/wpa_supplicant( 1177): No suitable network found
W/wpa_supplicant( 1177): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1177): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1177): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1177): nl80211: Survey data missing
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1177): Sorted scan results
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1177): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1177): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
D/wpa_supplicant( 1177): BSS: last_scan_res_used=4/3,2 last_scan_full=0
D/wpa_supplicant( 1177): Add randomness: count=94 entropy=82
D/wpa_supplicant( 1177): Add randomness: count=95 entropy=83
D/wpa_supplicant( 1177): Add randomness: count=96 entropy=84
D/wpa_supplicant( 1177): Add randomness: count=97 entropy=85
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1177): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1177): wpa_supplicant_pick_network+
,I/wpa_supplicant( 1177): clear disabled list - type=1
I/wpa_supplicant( 1177): No suitable network found
W/wpa_supplicant( 1177): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1177): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1177): reply (489) for get BSS: id=0
I/wpa_supplicant( 1177): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1177): freq=5220
I/wpa_supplicant( 1177): level=-48
,I/wpa_supplicant( 1177): tsf=0000000280513347
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1177): ssid=NG7005g
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=1
I/wpa_supplicant( 1177): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1177): freq=2412
I/wpa_supplicant( 1177): level=-56
I/wpa_supplicant( 1177): tsf=0000000280513375
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1177): ssid=NG700
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=3
I/wpa_supplicant( 1177): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1177): freq=2427
I/wpa_supplicant( 1177): level=-77
I/wpa_supplicant( 1177): tsf=0000000280513395
I/wpa_supplicant( 1177): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1177): ssid=Gonzos
I/wpa_supplicant( 1177): ====,
I/wpa_supplicant( 1177): id=6
I/wpa_supplicant( 1177): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1177): freq=2412
I/wpa_supplicant( 1177): level=-56
I/wpa_supplicant( 1177): tsf=0000000280513386
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1177): ssid=01ABC
I/wpa_supplicant( 1177): ####
D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0,
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 280513347, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 280513375, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2427, timestamp: 280513395, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 280513386, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): add 4 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  906): getDiscoveryDongleList,
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/wpa_supplicant( 1177): wpa_supplicant_scan enter
I/wpa_supplicant( 1177): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1177): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1177): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1177): nl80211: Event message available
,D/wpa_supplicant( 1177): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1177): nl80211: Event message available
D/wpa_supplicant( 1177): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1177): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1177): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1177): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1177): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1177): nl80211: Survey data missing
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1177): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1177): Sorted scan results
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1177): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1177): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
I/wpa_supplicant( 1177): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-87
D/wpa_supplicant( 1177): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1177): Add randomness: count=98 entropy=86
D/wpa_supplicant( 1177): Add randomness: count=99 entropy=87
D/wpa_supplicant( 1177): Add randomness: count=100 entropy=88
D/wpa_supplicant( 1177): Add randomness: count=101 entropy=89
D/wpa_supplicant( 1177): Add randomness: count=102 entropy=90
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1177): WPS: AP dc:4a:3e:0f:c2:f1 type 0 added
D/wpa_supplicant( 1177): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1177): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1177): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1177): wpa_supplicant_pick_network+
I/wpa_supplicant( 1177): Selecting BSS from priority group 1
I/wpa_supplicant( 1177): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1177): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1177): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1177): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1177):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1177):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1177): Start print parameters
I/wpa_supplicant( 1177): wpa_s->wpa_state is 9
I/wpa_supplicant( 1177): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1177): isConcurrentMode() is 0
I/wpa_supplicant( 1177): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1177): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1177): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1177): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1177): wpa_s->reassociate is 0
I/wpa_supplicant( 1177): wpa_s->is_screen_on 0
I/wpa_supplicant( 1177): wpa_s->ifname wlan0
I/wpa_supplicant( 1177): End print parameters
I/wpa_supplicant( 1177): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1177): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1177): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1177): 4: dc:4a:3e:0f:c2:f1 ssid='DIRECT-AD-HP DeskJet 3630 series' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1177): clear disabled list - type=1
I/wpa_supplicant( 1177): No suitable network found
W/wpa_supplicant( 1177): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1177): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1177): send_and_recv erro,r 0 - cmd 32
D/wpa_supplicant( 1177): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1177): nl80211: Survey data missing
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1177): Sorted scan results
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1177): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1177): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
I/wpa_supplicant( 1177): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-87
D/wpa_supplicant( 1177): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1177): Add randomness: count=103 entropy=91
D/wpa_supplicant( 1177): Add randomness: count=104 entropy=92
D/wpa_supplicant( 1177): Add randomness: count=105 entropy=93
D/wpa_supplicant( 1177): Add randomness: count=106 entropy=94
D/wpa_supplicant( 1177): Add randomness: count=107 entropy=95
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1177): WPS: AP dc:4a:3e:0f:c2:f1 type 0 added
D/wpa_supplicant( 1177): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1177): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1177): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1177): wpa_supplicant_pick_network+
I/wpa_supplicant( 1177): clear disabled list - type=1
I/wpa_supplicant( 1177): No suitable network found
W/wpa_supplicant( 1177): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1177): State: INACTIVE -> INACTIVE
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1177): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: Unknown Vendor Extension (Vendor ID 311)
I/wpa_supplicant( 1177): reply (634) for get BSS: id=0
I/wpa_supplicant( 1177): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1177): freq=5220
I/wpa_supplicant( 1177): level=-48
I/wpa_supplicant( 1177): tsf=0000000298753114
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1177): ssid=NG7005g
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=1
I/wpa_supplicant( 1177): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1177): freq=2412
I/wpa_supplicant( 1177): level=-56
I/wpa_supplicant( 1177): tsf=0000000298753207
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][WPS][ESS]
,I/wpa_supplicant( 1177): ssid=NG700
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=3
I/wpa_supplicant( 1177): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1177): freq=2427
I/wpa_supplicant( 1177): level=-77
I/wpa_supplicant( 1177): tsf=0000000298753232
I/wpa_supplicant( 1177): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1177): ssid=Gonzos
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=6
I/wpa_supplicant( 1177): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1177): freq=2412
I/wpa_supplicant( 1177): level=-56
I/wpa_supplicant( 1177): tsf=0000000298753222
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1177): ssid=01ABC
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=7
I/wpa_supplicant( 1177): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1177): freq=2437
I/wpa_supplicant( 1177): level=-87
I/wpa_supplicant( 1177): tsf=0000000298753242
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][WPS][ESS],
I/wpa_supplicant( 1177): ssid=DIRECT-AD-HP DeskJet 3630 series
I/wpa_supplicant( 1177): ####
D/WirelessDisplayService(  906): getDiscoveryDongleList
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 298753114, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 298753207, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2427, timestamp: 298753232, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 298753222, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -87, frequency: 2437, timestamp: 298753242, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 5 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  906):  + ScoreResult:  80, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  9 [2427], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  76, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  4 [-87], Tx: 13, Freq:  9 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  906):  + computeScore(NG700): 1
D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (5) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  906): acquireWL(44271dc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(44271dc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1177): wpa_supplicant_scan enter
I/wpa_supplicant( 1177): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1177): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1177): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1177): nl80211: Event message available
,D/wpa_supplicant( 1177): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,I/jxcore-log( 4426): --= Surplus to requirements =--
I/jxcore-log( 4426): 
,I/jxcore-log( 4426): ****TEST TOOK:  ms ****
I/jxcore-log( 4426): 
,I/jxcore-log( 4426): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4426): 
,E/cutils-trace( 4748): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 4748): ====startRecUseTime====
D/htc.customization.log.level( 4748):  is 
,W/CustomizationLogLevel( 4748): Level value is invalid, use default level 2
,D/CustomizationManager( 4748):  Read ACC file spent 0.122 (s)
D/CIDMapFileReader( 4748): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4748): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4748): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4748): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4748): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4748): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4748): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4748): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4748): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 4748): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4748): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4748): Parsing tag category name = system
,I/CustomizationCIDLoader( 4748): Parsing tag category name = application,
I/CustomizationCIDLoader( 4748): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4748): Parsing tag category name = AutomotiveHome
,I/CustomizationCIDLoader( 4748): Parsing tag category name = AudioService
,I/CustomizationCIDLoader( 4748): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4748): Parsing tag category name = Settings
D/CustomizationManager( 4748):  Read CID file spent 0.176 (s)
,D/CustomizationManager( 4748):  All configurations done spent 0.176 (s),
W/HtcNativeFlag( 4748): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4748): Fail to get flag for type 'customer', use default value: -1
,W/HtcNativeFlag( 4748): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 4748): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  906): deletePackageAsUser: pkg=com.test.thalitest, pid=4748, uid=2000 user=0
,I/ActivityManager(  906): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
,D/Process (  906): killProcessQuiet, pid=4426
,I/ActivityManager(  906): Killing 4426:com.test.thalitest/u0a189 (adj 0): stop com.test.thalitest
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,W/ActivityManager(  906): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  906):   Force finishing activity ActivityRecord{41c19498 u0 com.test.thalitest/.MainActivity t2}
,W/asset   (  906): Copying FileAsset 0x6452e5a8 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,W/InputDispatcher(  906): channel '4250cfa8 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  906): channel '4250cfa8 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  906): Attempted to unregister already unregistered input channel '4250cfa8 com.test.thalitest.MainActivity (s)'
I/WindowManager(  906): WINDOW DIED Window{4250cfa8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  906): Client connection lost with reason: 4
,W/InputMethodManagerService(  906): Got RemoteException sending setActive(false) notification to pid 4426 uid 10189
,W/Binder  ( 1208): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1208): java.lang.NullPointerException
W/Binder  ( 1208): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1208): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1208): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1208): 	at dalvik.system.NativeStart.run(Native Method)
,I/ActivityManager(  906): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
,I/dalvikvm-heap( 4141): Grow heap (frag case) to 15.196MB for 1821008-byte allocation
D/DotMatrix( 1577): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1577): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1577): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
,I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.test.thalitest
,I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
,W/GeofencerStateMachine( 1437): Ignoring removeGeofence because network location is disabled.
D/PMS     (  906): acquireWL(43db2570): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1437 10028 null
,I/acms    ( 1883): Unregistering com.test.thalitest
,E/acms    ( 1883): Could not unregister removed application com.test.thalitest
D/PMS     (  906): releaseWL(43db2570): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/VoicemailCleanupService( 1296): Cleaning up data for package: com.test.thalitest
W/AccTypeManager( 1330): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1330): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
W/SystemReader( 1254): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/Prism.ItemManager( 1266): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1266): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Launcher( 1266): Deferring update until onResume
,D/Launcher( 1266): waitUntilResume // bindAppsRemoved
,D/PackageBroadcastService( 2231): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/ActivityManager(  906): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4763 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,D/AccTypeManager( 1330): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/MultiDex( 4763): install
,I/MultiDex( 4763): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4763): loading existing secondary dex files
,I/MultiDex( 4763): load found 1 secondary dex files
,I/MultiDex( 4763): install done
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/ActivityManager(  906): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4780 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,D/PhoneApp( 1243): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,I/PeopleContactsSync( 2231): CP2 sync disabled
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2231, uid=10028, userID:0
,D/PMS     (  906): acquireWL(43fac4b0): PARTIAL_WAKE_LOCK  Icing 0x1 2231 10028 null
I/Icing   ( 2231): doRemovePackageData com.test.thalitest
,D/PMS     (  906): releaseWL(43fac4b0): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ProviderInstaller( 4763): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,I/MultiDex( 4780): install
,I/MultiDex( 4780): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 4780): loading existing secondary dex files
,I/MultiDex( 4780): load found 1 secondary dex files
,I/MultiDex( 4780): install done
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
E/ExternalAccountType( 1330): Unsupported attribute readOnly
,I/ProviderInstaller( 4780): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=4017
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4017:com.google.android.gm/u0a107 (adj 15): empty #17
,I/[PluginManager]RegisterService( 1401): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/ActivityManager(  906): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,I/[PluginManager]RegisterService( 1401): handle notify Blinkfeed plugin client changed
I/ActivityManager(  906): Resuming delayed broadcast
,D/Prism.PackageStateRece_( 1266): action: android.intent.action.PACKAGE_REMOVED
,I/IcingCorporaProvider( 2907): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ActivityManager(  906): Recipient 4017
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4802 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,D/PMS     (  906): acquireWL(4250d3d8): PARTIAL_WAKE_LOCK  Icing 0x1 2231 10028 null
,E/SQLiteLog( 2907): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 2907): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x636abfc8
,E/IcingCorporaProvider( 2907): Exception thrown from notifyTableChanged
E/IcingCorporaProvider( 2907): java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2907): 	at apg.a(PG:301)
E/IcingCorporaProvider( 2907): 	at apg.c(PG:222)
E/IcingCorporaProvider( 2907): 	at clo.b(PG:660)
E/IcingCorporaProvider( 2907): 	at clo.a(PG:651)
E/IcingCorporaProvider( 2907): 	at clo.g(PG:597)
E/IcingCorporaProvider( 2907): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/IcingCorporaProvider( 2907): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/IcingCorporaProvider( 2907): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/IcingCorporaProvider( 2907): 	at clp.Rl(PG:910)
E/IcingCorporaProvider( 2907): 	at clr.tL(PG:827)
E/IcingCorporaProvider( 2907): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/IcingCorporaProvider( 2907): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/IcingCorporaProvider( 2907): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/IcingCorporaProvider( 2907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/IcingCorporaProvider( 2907): 	at android.os.Looper.loop(Looper.java:157)
E/IcingCorporaProvider( 2907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/IcingCorporaProvider( 2907): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2907): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/IcingCorporaProvider( 2907): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/IcingCorporaProvider( 2907): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/IcingCorporaProvider( 2907): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/IcingCorporaProvider( 2907): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/IcingCorporaProvider( 2907): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/IcingCorporaProvider( 2907): 	at apa.a(PG:382)
E/IcingCorporaProvider( 2907): 	at apg.i(PG:325)
E/IcingCorporaProvider( 2907): 	at aph.call(PG:215)
E/IcingCorporaProvider( 2907): 	at apg.a(PG:299)
E/IcingCorporaProvider( 2907): 	... 15 more
W/IcingCorporaProvider( 2907): notifyTableChanged failed.
W/IcingCorporaProvider( 2907): Table change notification failed for TableStorageSpec[applications]
,I/IcingCorporaProvider( 2907): UpdateCorporaTask done [took 254 ms] updated apps [took 254 ms] 
,D/PMS     (  906): releaseWL(4250d3d8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,E/SQLiteLog( 4763): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 4763): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5c9f1008
E/SQLiteLog( 4763): (3850) statement aborts at 5: [DELETE FROM ContentFileDeletionLock24] disk I/O error
,E/SQLiteDBG( 4763): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5c9f1008
,E/DriveAsyncService( 4763): disk I/O error (code 3850)
E/DriveAsyncService( 4763): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4763): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4763): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 4763): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4763): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4763): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 4763): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 4763): 	at ctj.c(SourceFile:904)
E/DriveAsyncService( 4763): 	at cva.h(SourceFile:1427)
E/DriveAsyncService( 4763): 	at cgv.a(SourceFile:15)
E/DriveAsyncService( 4763): 	at bzz.onHandleIntent(SourceFile:60)
E/DriveAsyncService( 4763): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/DriveAsyncService( 4763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DriveAsyncService( 4763): 	at android.os.Looper.loop(Looper.java:157)
E/DriveAsyncService( 4763): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DocListDatabase( 4763): Failed to delete from ContentFileDeletionLock24
E/DocListDatabase( 4763): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 4763): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 4763): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/DocListDatabase( 4763): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 4763): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 4763): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/DocListDatabase( 4763): 	at ctj.a(SourceFile:859)
E/DocListDatabase( 4763): 	at cva.k(SourceFile:1117)
E/DocListDatabase( 4763): 	at chr.<init>(SourceFile:45)
E/DocListDatabase( 4763): 	at chr.a(SourceFile:75)
E/DocListDatabase( 4763): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/DocListDatabase( 4763): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/DocListDatabase( 4763): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/DocListDatabase( 4763): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/DocListDatabase( 4763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DocListDatabase( 4763): 	at android.os.Looper.loop(Looper.java:157)
E/DocListDatabase( 4763): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/DocListDatabase( 4763): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DocListDatabase( 4763): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DocListDatabase( 4763): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/DocListDatabase( 4763): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/DocListDatabase( 4763): 	at dalvik.system.NativeStart.main(Native Method)
,W/dalvikvm( 4763): threadid=1: thread exiting with uncaught exception (group=0x41691e30)
E/AndroidRuntime( 4763): FATAL EXCEPTION: main
E/AndroidRuntime( 4763): Process: com.google.android.gms.drive, PID: 4763
E/AndroidRuntime( 4763): java.lang.RuntimeException: Unable to create service com.google.android.gms.drive.api.ApiService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4763): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2883)
E/AndroidRuntime( 4763): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/AndroidRuntime( 4763): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/AndroidRuntime( 4763): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4763): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4763): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4763): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4763): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4763): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4763): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4763): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4763): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4763): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4763): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 4763): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4763): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4763): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 4763): 	at ctj.a(SourceFile:859)
E/AndroidRuntime( 4763): 	at cva.k(SourceFile:1117)
E/AndroidRuntime( 4763): 	at chr.<init>(SourceFile:45)
E/AndroidRuntime( 4763): 	at chr.a(SourceFile:75)
E/AndroidRuntime( 4763): 	at com.google.android.gms.drive.api.ApiService.onCreate(SourceFile:64)
E/AndroidRuntime( 4763): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/AndroidRuntime( 4763): 	... 10 more
,E/ActivityManager(  906): App crashed! Process: com.google.android.gms.drive
,D/Process ( 4763): killProcess, pid=4763
,D/Process ( 4763): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager(  906): Recipient 4763
I/ActivityManager(  906): Process com.google.android.gms.drive (pid 4763) has died.
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.gms/.drive.api.ApiService in 1000ms
,E/SQLiteDatabase( 4802): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.,
E/SQLiteDatabase( 4802): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4802): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4802): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
,E/SQLiteDatabase( 4802): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4802): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4802): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
,E/SQLiteDatabase( 4802): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4802): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4802): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4802): ,	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4802): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4802): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4802): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4802): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4802): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4802): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4802): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4802): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4802): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4802): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4802): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4802): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4802): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4802): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4802): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4802): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4802): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4802): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4802): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4802): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4802): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4802): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4802): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4802): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4802): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4802): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4802): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4802): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4802): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4802): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4802): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4802): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4802): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4802): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4802): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4802): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4802): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4802): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4802): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4802): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4802): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4802): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4802): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4802): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4802): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4802): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4802): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4802): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4802): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4802): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4802): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4802): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4802): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4802): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4802): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4802): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4802): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4802): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4802): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4802): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4802): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4802): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4802): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4802): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4802): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4802): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4802): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 4802): Opened ClientFlag.db in read-only mode
,E/SQLiteDatabase( 4802): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4802): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4802): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4802): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4802): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4802): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4802): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4802): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4802): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4802): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4802): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4802): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4802): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4802): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4802): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4802): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4802): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4802): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4802): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4802): 	at aho.run(AbstractDatabaseInstance.java:455)
,W/dalvikvm( 4802): threadid=11: thread exiting with uncaught exception (group=0x41691e30)
,E/ActivityManager(  906): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4802): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4802): Process: com.google.android.apps.docs, PID: 4802
E/AndroidRuntime( 4802): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4802): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4802): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4802): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4802): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4802): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4802): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4802): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4802): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4802): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4802): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4802): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4802): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4802): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4802): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4802): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4802): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4802): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4802): 	at aho.run(AbstractDatabaseInstance.java:455)
,E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
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
,D/Process ( 4802): killProcess, pid=4802
,D/Process ( 4802): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  906): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4824 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  906): Recipient 4802
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Process com.google.android.apps.docs (pid 4802) has died.
,W/ContextImpl( 4824): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  906): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4837 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
,E/SQLiteDatabase( 4824): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4824): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4824): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4824): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4824): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4824): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4824): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4824): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4824): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4824): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4824): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4824): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4824): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4824): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4824): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4824): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4824): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4824): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4824): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4824): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4824): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 4824): threadid=10: thread exiting with uncaught exception (group=0x41691e30)
,E/AndroidRuntime( 4824): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4824): Process: com.android.keychain, PID: 4824
E/AndroidRuntime( 4824): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4824): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4824): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4824): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4824): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4824): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4824): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4824): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4824): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4824): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4824): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4824): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4824): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4824): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4824): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4824): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4824): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4824): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4824): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4824): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ActivityManager(  906): App crashed! Process: com.android.keychain
D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
,D/Process ( 4824): killProcess, pid=4824
,D/Process ( 4824): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453126799307.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  906): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  906): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  906): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  906): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  906): 	... 4 more
,D/AppTag  ( 4837): getInstance(Context context)
,I/ActivityManager(  906): Recipient 4824
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.android.keychain (pid 4824) has died.
,W/ActivityManager(  906): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10469ms
,I/Prism.ItemManager( 1266): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1266): loadItems() com.htc.launcher.pageview.WidgetManager@41b54d30 +
,I/Prism.WidgetManager( 1266): onLoadItems() +
,D/AppTag  ( 4837): getInstance(Context context)
,D/AppTag  ( 4837): onCreate()
,D/PMS     (  906): acquireWL(441984c8): PARTIAL_WAKE_LOCK  AsyncService 0x1 4141 10160 null
,W/PackageManager(  906): Unable to load service info ResolveInfo{42d92b00 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  906): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  906): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  906): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  906): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  906): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  906): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  906): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  906): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  906): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  906): 	at dalvik.system.NativeStart.main(Native Method)
,I/dalvikvm-heap( 4141): Grow heap (frag case) to 16.935MB for 1821008-byte allocation
D/PMS     (  906): releaseWL(441984c8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  906): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4855 uid=10098 gids={50098, 3003, 5012}
,D/wpa_supplicant( 1177): nl80211: Event message available
D/wpa_supplicant( 1177): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
,I/wpa_supplicant( 1177): Got an original EVENT_SCAN_RESULTS
D/Process (  906): killProcessQuiet, pid=4394
D/wpa_supplicant( 1177): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1177): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1177): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1177): nl80211: Survey data missing
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1177): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1177): Sorted scan results
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1177): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1177): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
D/wpa_supplicant( 1177): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1177): Add randomness: count=108 entropy=96
D/wpa_supplicant( 1177): Add randomness: count=109 entropy=97
D/wpa_supplicant( 1177): Add randomness: count=110 entropy=98
D/wpa_supplicant( 1177): Add randomness: count=111 entropy=99
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1177): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1177): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1177): wpa_supplicant_pick_network+
I/wpa_supplicant( 1177): Selecting BSS from priority group 1
I/wpa_supplicant( 1177): Recent assoc_freq = 2412 rssi = -56
D/wpa_supplicant( 1177): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1177): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1177): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1177):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1177):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-56
I/wpa_supplicant( 1177): Start print parameters
I/wpa_supplicant( 1177): wpa_s->wpa_state is 9
I/wpa_supplicant( 1177): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1177): isConcurrentMode() is 0
I/wpa_supplicant( 1177): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1177): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1177): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1177): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1177): wpa_s->reassociate is 0
I/wpa_supplicant( 1177): wpa_s->is_screen_on 0
,I/wpa_supplicant( 1177): wpa_s->ifname wlan0
I/wpa_supplicant( 1177): End print parameters
I/wpa_supplicant( 1177): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1177): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1177): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1177): clear disabled list - type=1
I/wpa_supplicant( 1177): No suitable network found
W/wpa_supplicant( 1177): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1177): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1177): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1177): nl80211: Survey data missing
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,D/wpa_supplicant( 1177): Sorted scan results
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1177): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1177): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-56
I/wpa_supplicant( 1177): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-77
D/wpa_supplicant( 1177): BSS: last_scan_res_used=4/32 last_scan_full=0
,D/wpa_supplicant( 1177): Add randomness: count=112 entropy=100
D/wpa_supplicant( 1177): Add randomness: count=113 entropy=101
D/wpa_supplicant( 1177): Add randomness: count=114 entropy=102
D/wpa_supplicant( 1177): Add randomness: count=115 entropy=103,
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: Unknown Vendor Extension (Vendor ID 311)
,D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1177): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1177): WPS: AP[2] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1177): wpa_supplicant_pick_network+
I/wpa_supplicant( 1177): clear disabled list - type=1
I/wpa_supplicant( 1177): No suitable network found
W/wpa_supplicant( 1177): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1177): State: INACTIVE -> INACTIVE
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  906): Killing 4394:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
D/WifiP2pService(  906): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1177): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1177): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1177): WPS: Unknown Vendor Extension (Vendor ID 311)
,I/wpa_supplicant( 1177): reply (634) for get BSS: id=0
I/wpa_supplicant( 1177): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1177): freq=5220
I/wpa_supplicant( 1177): level=-48
I/wpa_supplicant( 1177): tsf=0000000316802413
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1177): ssid=NG7005g
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=1
I/wpa_supplicant( 1177): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1177): freq=2412
I/wpa_supplicant( 1177): level=-56
I/wpa_supplicant( 1177): tsf=0000000316802436
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1177): ssid=NG700
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=3
I/wpa_supplicant( 1177): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1177): freq=2427
I/wpa_supplicant( 1177): level=-77
I/wpa_supplicant( 1177): tsf=0000000316802452
I/wpa_supplicant( 1177): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1177): ssid=Gonzos
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=6
I/wpa_supplicant( 1177): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1177): freq=2412
I/wpa_supplicant( 1177): level=-56
I/wpa_supplicant( 1177): tsf=0000000316802444
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1177): ssid=01ABC
I/wpa_supplicant( 1177): ====
I/wpa_supplicant( 1177): id=7
I/wpa_supplicant( 1177): bssid=dc:4a:3e:0f:c2:f1
I/wpa_supplicant( 1177): freq=2437
I/wpa_supplicant( 1177): level=-87
I/wpa_supplicant( 1177): tsf=0000000298753242
I/wpa_supplicant( 1177): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1177): ssid=DIRECT-AD-HP DeskJet 3630 series
I/wpa_supplicant( 1177): ####
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,I/ActivityManager(  906): Recipient 4394
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 316802413, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -56, frequency: 2412, timestamp: 316802436, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2427, timestamp: 316802452, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -56, frequency: 2412, timestamp: 316802444, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 4: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -87, frequency: 2437, timestamp: 298753242, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  906): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -56, 0
D/WifiStateMachine(  906): add 5 to mScanResults
,V/ScoreHelper(  906): Only print Top 10 in ApScanList
,V/ScoreHelper(  906):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  906):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-56], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  80, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-77], Tx: 13, Freq:  9 [2427], Disconn: 50, Last Used:  0
,V/ScoreHelper(  906):  + ScoreResult:  76, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  4 [-87], Tx: 13, Freq:  9 [2437], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  906):  + computeScore(NG700): 1
,D/WifiStateMachine(  906): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,I/DeviceManagement( 4855): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4855 dbg=false s=true
,I/DeviceManagement( 4855): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
,I/DeviceManagement( 4855): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
,I/DeviceManagement( 4855): WorkflowService: Starting workflow service
,I/DeviceManagement( 4855): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41af5278] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4855): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4855): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
,I/DeviceManagement( 4855): PackageUpdateWorkflow: ==================================================
,I/DeviceManagement( 4855): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  906): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4869 uid=10099 gids={50099, 3003, 5012}
,I/DeviceManagement( 4855): BackgroundController: *** Processing package remove for appID=com.test.thalitest
,I/DeviceManagement( 4855): SessionStateController: Checking invariants...

```
