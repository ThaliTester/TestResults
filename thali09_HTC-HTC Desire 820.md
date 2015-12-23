#### Test 543122980a88295_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system,
D/WIFI_ICON( 1116): WifiActivity: 0
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
--------- beginning of /dev/log/main
E/cutils-trace( 4602): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4602): ====startRecUseTime====
D/htc.customization.log.level( 4602):  is 
W/CustomizationLogLevel( 4602): Level value is invalid, use default level 2
D/CustomizationManager( 4602):  Read ACC file spent 0.049 (s)
D/CIDMapFileReader( 4602): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4602): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4602): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4602): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4602): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4602): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4602): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4602): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4602): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4602): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4602): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4602): Parsing tag category name = system
I/CustomizationCIDLoader( 4602): Parsing tag category name = application
I/CustomizationCIDLoader( 4602): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4602): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4602): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4602): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4602): Parsing tag category name = Settings
D/CustomizationManager( 4602):  Read CID file spent 0.089 (s)
D/CustomizationManager( 4602):  All configurations done spent 0.089 (s)
W/HtcNativeFlag( 4602): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4602): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4602): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4602): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  904): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  904): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  904): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  904): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  904): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  904): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  904): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4602
D/PMS     (  904): acquireHCC(441b1af0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 904 1000 null
D/PMS     (  904): acquireHCC(43133c88): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 904 1000 null
W/asset   (  904): Copying FileAsset 0x6cdf9b68 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  904): @test_code: getHtcIntentFlag: 0 obj: 1136386392
I/FeedHostManager( 1271): [onPause]
I/FeedProviderManager( 1271): onPause
I/FeedHostManager( 1271): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@420206b8
I/SocialFeedProvider( 1271): +onPause
I/SocialFeedProvider( 1271): -onPause
D/PMS     (  904): acquireWL(423c5028): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 904 1000 null
I/ActivityManager(  904): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4613 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1271): [trimMemory] 20
W/asset   ( 4613): Copying FileAsset 0x5c7d0428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4613): Binding Chromium to main looper Looper (main, tid 1) {41a7f4f8}
I/LibraryLoader( 4613): Expected native library version number "",actual native library version number ""
I/chromium( 4613): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4613): Initializing chromium process, renderers=0
D/PMS     (  904): acquireWL(4342e920): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/BluetoothManagerService(  904): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  904): java.lang.Throwable: stack dump
D/BluetoothManagerService(  904): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@423bbb28:true
W/System.err(  904): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  904): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  904): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  904): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  904): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4613): 1101614896: getState(). Returning 12
D/PMS     (  904): acquireWL(43447ac8): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  904): releaseWL(43447ac8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4613): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4613): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4613): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4613): Local Branch: 
I/Adreno-EGL( 4613): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4613): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4613):                  aa63bbd948f41d15fc72f585e
W/chromium( 4613): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4613): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4613): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4613): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4613): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4613): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4613): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4613): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4613): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/SystemWebViewEngine( 4613): CordovaWebView is running on device made by: HTC
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -62 abnormalRssiCnt = 0 newLinkSpeed = 19
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 57
D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  904):    returned true
,W/AwContents( 4613): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  904): Disable input method client, pid=1271
,I/InputMethodManagerService(  904): Enable input method client, pid=4613
I/ActivityManager(  904): Displayed com.test.thalitest/.MainActivity: +263ms
W/ResourceType( 4613): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4613): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41ac65e0, mServedView=org.apache.cordova.engine.SystemWebView{41a8c248 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1208): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1208): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,W/AwContents( 4613): nativeOnDraw failed; clearing to background color.
D/PMS     (  904): releaseWL(423c5028): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/JsMessageQueue( 4613): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4613): JniHelper::setJavaVM(0x41554048), pthread_self() = 1662897408
,D/JX-Cordova( 4613): jxcore cordova android initializing
,I/dalvikvm-heap( 4613): Grow heap (frag case) to 11.550MB for 96598-byte allocation
,I/dalvikvm-heap( 4613): Grow heap (frag case) to 11.630MB for 144892-byte allocation
,I/dalvikvm-heap( 4613): Grow heap (frag case) to 11.746MB for 217334-byte allocation
,I/dalvikvm-heap( 4613): Grow heap (frag case) to 11.922MB for 325996-byte allocation
,I/dalvikvm-heap( 4613): Grow heap (frag case) to 12.197MB for 488990-byte allocation
,I/dalvikvm-heap( 4613): Grow heap (frag case) to 13.204MB for 1100216-byte allocation
,I/dalvikvm-heap( 4613): Grow heap (frag case) to 14.067MB for 1650320-byte allocation
,I/dalvikvm-heap( 4613): Grow heap (frag case) to 15.464MB for 2475476-byte allocation
,I/dalvikvm-heap( 4613): Grow heap (frag case) to 17.502MB for 3713210-byte allocation
,W/jxcore-log( 4613): Initializing JXcore engine
,W/jxcore-log( 4613): JXcore engine is ready
,W/CpuWake (  904): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  904): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  904): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  904): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  904): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  904): <<release mCpuPerf_Freq wakelock
,W/jxcore-log( 4613): Starting JXcore engine
D/PMS     (  904): releaseHCC(441b1af0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
D/PMS     (  904): releaseHCC(43133c88): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4613): Platform android
W/jxcore-log( 4613): 
,W/jxcore-log( 4613): Process ARCH arm
W/jxcore-log( 4613): 
,I/jxcore-log( 4613): JXcore Cordova bridge is ready!
I/jxcore-log( 4613): 
,W/jxcore-log( 4613): JXcore engine is started
,I/chromium( 4613): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/Choreographer( 4613): Skipped 137 frames!  The application may be doing too much work on its main thread.
,D/PMS     (  904): releaseWL(4342e920): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -62 abnormalRssiCnt = 0 newLinkSpeed = 19
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 76
D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1182): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
,I/jxcore-log( 4613): Toggling radios to true
I/jxcore-log( 4613): 
,D/BluetoothAdapter( 4613): enable(): BT is already enabled..!
,D/WifiManager( 4613): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
W/HtcDLNAServiceManager(  904): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  904): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  904): Settings:Agentvalue: 2
W/Settings:Agent(  904): >> traceCallingStack()
W/Settings:Agent(  904): Process.myPid(): 904
W/Settings:Agent(  904): Process.myTid(): 1362
W/Settings:Agent(  904): Process.myUid(): 1000
W/Settings:Agent(  904): 
W/Settings:Agent(  904): 
,W/System.err(  904): java.lang.Throwable: stack dump
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
D/WifiService(  904): New client listening to asynchronous messages
D/WifiService(  904): setWifiEnabled: true pid=4613, uid=10389
E/WifiService(  904): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  904): isSprintWifiRestricted(): false
I/WifiService(  904): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  904): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/System.err(  904): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  904): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  904): 
W/Settings:Agent(  904): << traceCallingStack(): 1(ms)
D/WifiManager( 4613): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  904): doBoolean: DISCONNECT
D/WifiManager( 4613): reconnect: Base Package Name=com.test.thalitest, uid=10389
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): TDLS: Tear down peers
I/wpa_supplicant( 1182): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4613): Radios toggled
I/jxcore-log( 4613): 
D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4613): Got Device Bluetooth address: B4:CE:F6:AB:A4:6A
I/jxcore-log( 4613): 
I/jxcore-log( 4613): Perf Test app loaded loaded
I/jxcore-log( 4613): 
I/Choreographer( 4613): Skipped 79 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 4613): check test folder
I/jxcore-log( 4613): 
,I/jxcore-log( 4613): found test : ./testFindPeers.js
I/jxcore-log( 4613): 
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1182): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1182): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1182): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1182): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1182): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  904): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  904): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  904): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1182): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1182): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1182): send_and_recv error -67 - cmd 12
D/HTCRequest(  904): WifiMonitor:getReasonFromEventString() 3
D/wpa_supplicant( 1182): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  904): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1182): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1182): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1182): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1182): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb7b46bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1182):    addr=c0:ff:d4:d3:aa:48
D/HTCRequest(  904): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1182): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1182): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1182): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1182): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1182): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1182): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1182): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1182): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1182): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1182): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1182): EAPOL: SUPP_BE entering state INITIALIZE
D/Tethering(  904): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1182): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1182): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/Tethering(  904): interfaceStatusChanged wlan0, false
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1182): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1182): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1182): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1182): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1182): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1182): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1182): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1182): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1182): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1182): htc_wext_set_TX_TRACKING (0)+
D/Tethering(  904): [isWifi] getHotspotEnabled: false
I/wpa_supplicant( 1182): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1182): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1182):, EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1182): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1182): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1182): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1182): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1182): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1182): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1182): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1182): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1182): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1182): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1182): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1182): nl80211: Event message available
D/wpa_supplicant( 1182): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1182): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  904): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  904): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/WifiNative-wlan0(  904):    returned true
D/WifiPerfLock(  904): release()
D/WifiStateMachine(  904): PerfLock released for exiting ConnectedState
D/Tethering(  904): interfaceLinkStateChanged wlan0, false
D/Tethering(  904): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  904): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1182): Power_Mode_Type mode = 0
I/wpa_supplicant( 1182): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 61
,D/Tethering(  904): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  904):    returned true
,D/WifiNative-wlan0(  904): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  904):    returned true
D/ConnectivityService(  904): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  904): acquireWL(43c98898): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 904 1000 null
D/WifiP2pService(  904): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 4613): found test : ./testSendData.js
I/jxcore-log( 4613): 
,D/DhcpStateMachine(  904): [RunningState] Stop DHCP
D/libc    (  904): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023644
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024011
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024167
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024177
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025645
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025659
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360028346
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029918
,D/WifiStateMachine(  904): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiNative-wlan0(  904): doBoolean: RECONNECT
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): Fast associate: Old scan results
I/wpa_supplicant( 1182): wpa_supplicant_scan enter
I/wpa_supplicant( 1182): State: DISCONNECTED -> SCANNING
D/WifiDataStallTracker(  904): onReceive: action=android.net.wifi.STATE_CHANGE
I/wpa_supplicant( 1182): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1182): wpa_supplicant_trigger_scan +
D/WifiDataStallTracker(  904): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  904): stopDataStallAlarm: current tag=20163 mDataStallAlarmIntent=PendingIntent{44070698: PendingIntentRecord{42325380 android broadcastIntent}}
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1182): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1182): nl80211: Event message available
D/wpa_supplicant( 1182): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/libc    (  904): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiNative-wlan0(  904):    returned true
,D/WifiStateMachine(  904): Enter handleNetworkDisconnect
D/WifiNative-wlan0(  904): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1182): Power_Mode_Type mode = 0
I/wpa_supplicant( 1182): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 61
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023644
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024011
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024167
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024177
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025645
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025659
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360028346
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029918
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  904): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  904): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  904): Provision feature enable=false
D/ConnectivityService(  904): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/UsbnetStateTracker(  904): isAvailable+-
D/UsbnetStateTracker(  904): reconnect
D/UsbnetStateTracker(  904): isAvailable+-
D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  904):    returned true
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  904): default: reconnect()
D/MDST    (  904): default: setTeardownRequested(false)
D/MDST    (  904): default: setEnableApn apnType =default , enable=true
D/WifiP2pService(  904): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  904): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  904): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  904): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4165): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  904): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  904): Exit handleNetworkDisconnect
W/ConnectivityService(  904): Exception trying to remove a route: java.lang.IllegalStateException: command '28 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 28 Failed to remove route from default table (No such process)'
D/ConnectivityService(  904): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  904): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  904): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  904): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WifiService(  904): New client listening to asynchronous messages
D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent DefaultState
D/WISPrService( 4165): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  904): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,V/NativeCrypto( 1376): Read error: ssl=0x662ad668: I/O error during system call, Connection timed out
D/WifiDataStallTracker(  904): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  904): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,V/NativeCrypto( 1376): SSL shutdown failed: ssl=0x662ad668: I/O error during system call, Broken pipe
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
W/ConnectivityService(  904): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  904): handleConnectivityChange: resetting
D/ConnectivityService(  904): resetConnections(wlan0, 3)
D/PMS     (  904): acquireWL(43575180): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
D/WifiStateTracker(  904): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WISPrService( 4165): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  904): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 4165): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023644
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024011
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024167
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024177
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025645
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025659
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360028346
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029918
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1376/10029)
D/ConnectivityService(  904): reportInetCondition for net -1, percentage: 0 by  (1376/10029)
,D/ConnectivityService(  904): flush DNS cache for net 1(wlan0)
D/libc    (  363): [NET] entry_id:4   entry:0xb8980350  removed 
D/libc    (  363): [NET] entry_id:9   entry:0xb897fe40  removed 
D/libc    (  363): [NET] entry_id:7   entry:0xb897fd90  removed 
D/libc    (  363): [NET] entry_id:3   entry:0xb8980860  removed 
D/libc    (  363): [NET] entry_id:6   entry:0xb8980218  removed 
D/libc    (  363): [NET] entry_id:8   entry:0xb897ff38  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb8980428  removed 
D/libc    (  363): [NET] entry_id:5   entry:0xb8980738  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb89800e8  removed 
D/libc    (  363): [NET] entry_id:10   entry:0xb897ffe8  removed 
D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
,I/jxcore-log( 4613): found test : ./testSendData2.js
I/jxcore-log( 4613): 
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:1
D/Nat464Xlat(  904): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  904): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1376/10029)
D/ConnectivityService(  904): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  904): releaseWL(43575180): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  904): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/WirelessDisplayService(  904): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  904): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WifiStateMachine(  904): startScan Pid: 904 Uid 1000
I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,D/WifiNative-wlan0(  904): doBoolean: SCAN
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1182): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  904):    returned false
D/PMS     (  904): acquireWL(435848b0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 904 1000 null
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by  (904/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1376/10029)
D/BatSI   (  904): WIFI scan started for: 650a0300 uid:1000
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1376/10029)
,D/ConnectivityService(  904): mActiveDefaultNetwork: -1
,D/ConnectivityService(  904): handleInetConditionChange: no active default network - ignore
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:0
D/PMS     (  904): releaseWL(435848b0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/chromium( 4613): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/PMS     (  904): Going to sleep due to screen timeout...
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42218410
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  904): disable: get sensor name = CM36282 Light sensor
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 2
W/SensorService(  904): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42218410, eanble = 0, strlen(mName) = 59
,W/SensorService(  904): Active Listeners: mActiveListeners.size() = 2,
W/SensorService(  904): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420412d8,
W/SensorService(  904): Listener[1] = com.htc.smartdim.sensor_eye@426a2c80
,W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  904): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  904): Couldn't get kernel wake lock stats
V/LightsService(  904): setLight #2: color=#0
D/qdlights(  904): set_light_buttons_func: on=0 brightness=0
V/LightsService(  904): setLight #0: color=#0
,D/WirelessDisplayService(  904): Screen File Receiver; callOnGoing: false, Screen On: false
,W/PMS     (  904): mWirelessDisplayManager is null
D/WirelessDisplayService(  904): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,D/SurfaceControl(  904): Excessive delay in blankDisplay() while turning screen off: 328ms
D/PMS     (  904): nativeSetInteractive:false
D/PMS     (  904): nativeSetInteractive:false done
D/PMS     (  904): nativeSetAutoSuspend:true
D/PMS     (  904): nativeSetAutoSuspend:true done
D/NfcService( 1254): ScreenObserver: OFF
,D/NfcService( 1254): applyRouting - 0
D/HABCtrl (  904): TPE algorithm. remove timeout.
I/InputManager(  904): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  904): screenObserver, isScreenOn=false
D/PMS     (  904): OOBE c monitor 11
I/InputMethodManagerService(  904): Disable input method client, pid=4613
,D/PMS     (  904): acquireWL(435c73b0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
D/NfcService( 1254): applyRouting -2
I/IntentController( 1116): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  904): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@4359b890)
,W/ResourceType( 4613): No package identifier when getting name for resource number 0x00000064
D/PMS     (  904): acquireWL(43630bd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
D/PMS     (  904): releaseWL(43630bd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): releaseWL(435c73b0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/PMN     (  904): wakingUp
,I/InputMethodManager( 4613): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41a8c248 VFEDH.C. .F...... 0,0-720,1134 #64}
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,V/KeyguardServiceDelegate(  904): **** SHOWN CALLED ****
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
I/WindowManager(  904): No lock screen! windowToken=null
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/MtpService( 1987): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 1987): [MTP][onReceive]-
,D/NfcService( 1254): applyRouting - 0
D/PMN     (  904): onScreenOn
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
D/AlarmManager(  904): ACTION_SCREEN_ON
I/AlarmManager(  904): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  904): [AlarmQueuing] done recovering
I/AlarmManager(  904): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  904): [AlarmQueuing] done EPS screen off alarm recovering
D/WirelessDisplayService(  904): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/NfcService( 1254): applyRouting -2
D/WirelessDisplayService(  904): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  904): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/AutoSetting( 1324): receiver - intent: android.intent.action.USER_PRESENT
D/PMS     (  904): acquireWL(4350fa20): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
D/PMS     (  904): releaseWL(4350fa20): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/AutoSetting( 1324): service - onCreate()
D/WirelessDisplayService(  904): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  904): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  904): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  904): onReceive: action=android.intent.action.SCREEN_ON
D/AutoSetting( 1324): service - AddressCache: using context: com.htc.Weather
D/WifiNative-wlan0(  904): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  904): doBoolean: SET pno 0
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1182): SET_SCREEN_ON:On
I/wpa_supplicant( 1182): htc_wext_set_keepalive +
I/wpa_supplicant( 1182): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1182): getPrivFuncNum +	
I/wpa_supplicant( 1182): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1182): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1182): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1182): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1182): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  904):    returned true
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): CTRL_IFACE SET 'pno'='0'
I/wpa_supplicant( 1182): wpa_supplicant_scan enter
D/WifiNative-wlan0(  904):    returned true
D/TetherSettings( 4165): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4165): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4165): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4165): Cust_ConnectToPC   : spcsc>false
D/        ( 4165): Cust_ConnectToPC   : IPT>true
D/        ( 4165): Cust_ConnectToPC   : Singel_USB>false
D/AutoSetting( 1324): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/LocationManagerService(  904): request 424eda88 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
V/NotificationService(  904): batLight: Full, plugged
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c800
D/qdlights(  904): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/LocationManagerService(  904): provider request: passive ProviderRequest[ON interval=0]
I/ClockThread( 1116): stop update clock
V/SRS_Proc(  370): ParamSet string: screen_state=on
W/Settings( 4165): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/WirelessDisplayService(  904): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
E/SmartNS_Utility( 4165): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 4165): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4165): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 4165): onReceive:android.intent.action.USER_PRESENT
V/NotificationService(  904): batLight: Full, plugged
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c800
D/qdlights(  904): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/NetworkPolicy(  904): updateScreenOn: false
W/ContextImpl( 4165): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/SmartNS_PSService( 4165): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4165): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4165):  defaultType:0
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,I/ActivityManager(  904): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4676 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PMS     (  904): acquireWL(441ccbd8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  904): releaseWL(441ccbd8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(43128f28): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  904): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  904): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  904): bSetPropertyMultiRAB:false
D/Tethering(  904): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  904): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  904): ipv4Default null
I/Tethering(  904): No IPv4 upstream interface, giving up.
,D/Tethering(  904): TetherMasterSM: InitialState processMessage what=3
D/PMS     (  904): releaseWL(43128f28): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1778): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1778): onScreenOn: 1450833992658
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1778): onScreenOn: 1450833992658
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420412d8
,W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  904): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/SensorService(  904): pid=904, uid=1000
,W/SensorService(  904): Active sensors: size = 2
W/SensorService(  904): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420412d8, eanble = 0, strlen(mName) = 91
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  904): Listener[0] = com.htc.smartdim.sensor_eye@426a2c80
,W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  904): goingToSleep
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.backuptransport (1594/10029)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.docs (4462/10100)
W/ContextImpl( 4676): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  904): acquireWL(441b9928): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 904 1000 null
I/AlarmManager(  904): [AlarmQueuing] connectivity wifi: false
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.docs (4462/10100)
,D/ConnectivityService(  904): getNetworkInfo networkType=1 called by  (904/1000)
,D/GpsLocationProvider(  904): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  904): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  904): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  904): ignore wifi update if we are not in OPENING or CLOSING
,D/CaptivePortalTracker(  904): DelayedCaptiveCheckState
D/CaptivePortalTracker(  904): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  904): NoActiveNetworkState
D/PMS     (  904): acquireWL(4370db08): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 904 1000 null
D/PMS     (  904): releaseWL(4370db08): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
I/ConnectivityHelper( 1271): [onReceive] WIFI(1): DISCONNECTED
D/htcCheckinService(  904): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  904): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,D/SmartSyncUtils( 4676): isEpsOn(), nState = 0
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by com.htc.launcher (1271/10076)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/AlarmManager(  904): ACTION_SCREEN_OFF
I/AlarmManager(  904): [AlarmQueuing] screen off now: 
I/AlarmManager(  904): [AlarmQueuing] data connection: true
I/AlarmManager(  904): [AlarmQueuing] wifi connection: true
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023644
D/PMS     (  904): acquireWL(44070120): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4676 1000 null
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024011
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024167
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024174
D/WifiDataStallTracker(  904): onReceive: action=android.intent.action.SCREEN_OFF
D/WifiDataStallTracker(  904): stopDataStallAlarm: current tag=20164 mDataStallAlarmIntent=null
,D/WifiNative-wlan0(  904): doBoolean: SET pno 1
,D/WifiNative-wlan0(  904): doBoolean: SET_SCREEN_ON 0
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1182): CTRL_IFACE SET 'pno'='1'
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024177
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025645
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025659
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360028346
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029918
D/PMS     (  904): acquireWL(43402df0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 904 1000 null
D/PMS     (  904): releaseWL(441b9928): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/SmartSyncUtils( 4676): getMobilePolicyEnabled, result = true
D/PMS     (  904): releaseWL(44070120): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1182): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1182): nl80211: Event message available
D/wpa_supplicant( 1182): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
,D/WifiNative-wlan0(  904):    returned true
D/wpa_supplicant( 1182): nl80211: Event message available
D/wpa_supplicant( 1182): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1182): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1182): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1182): nl80211: Survey data missing
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1182): Sorted scan results
I/wpa_supplicant( 1182): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-62
D/wpa_supplicant( 1182): BSS: last_scan_res_used=1/32 last_scan_full=0
D/wpa_supplicant( 1182): Add randomness: count=8 entropy=0
D/wpa_supplicant( 1182): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1182): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1182): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1182): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1182): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1182): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1182): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1182): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1182): WPS: AP[0] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1182): wpa_supplicant_pick_network+
I/wpa_supplicant( 1182): Selecting BSS from priority group 1
I/wpa_supplicant( 1182): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1182): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1182): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1182):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1182):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-62
I/wpa_supplicant( 1182): Start print parameters
I/wpa_supplicant( 1182): wpa_s->wpa_state is 3
I/wpa_supplicant( 1182): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1182): isConcurrentMode() is 0
I/wpa_supplicant( 1182): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1182): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1182): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1182): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1182): wpa_s->reassociate is 1
I/wpa_supplicant( 1182): wpa_s->is_screen_on 1
I/wpa_supplicant( 1182): wpa_s->ifname wlan0
I/wpa_supplicant( 1182): End print parameters
I/wpa_supplicant( 1182): selected network = 2
D/wpa_supplicant( 1182): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb7b484e8  current_ssid=0x0
D/wpa_supplicant( 1182): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1182): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1182): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1182): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1182): check if in concurrent case
I/wpa_supplicant( 1182): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/wpa_supplicant( 1182): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1182): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1182): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1182): RSN: PMKSA cache search - network_ctx=0xb7b484e8 try_opportunistic=0
D/wpa_supplicant( 1182): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1182): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1182): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1182): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1182): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1182): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1182): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1182): nl80211: Unsubscribe mgmt frames handle 0xb7b47718 (mode change)
D/WifiNative-wlan0(  904): doBoolean: DRIVER SETSUSPENDMODE 1
D/wpa_supplicant( 1182): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7b47718
D/wpa_supplicant( 1182): nl80211: Register frame type=0xd0 nl_handle=0xb7b47718
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1182): nl80211: Register frame type=0xd0 nl_handle=0xb7b47718
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1182): nl80211: Register frame type=0xd0 nl_handle=0xb7b47718
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1182): nl80211: Register frame type=0xd0 nl_handle=0xb7b47718
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1182): nl80211: Register frame type=0xd0 nl_handle=0xb7b47718
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1182): nl80211: Register frame type=0xd0 nl_handle=0xb7b47718
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1182): nl80211: Register frame type=0xd0 nl_handle=0xb7b47718
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSID
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1182): nl80211: Register frame type=0xd0 nl_handle=0xb7b47718
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1182): nl80211: Register frame type=0xd0 nl_handle=0xb7b47718
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1182): nl80211: Register frame type=0xd0 nl_handle=0xb7b47718
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1182): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1182):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1182):   * freq=2412
D/wpa_supplicant( 1182):   * Auth Type 0
D/wpa_supplicant( 1182):   * WPA Versions 0x2
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1182): nl80211: Connect request send successfully
D/wpa_supplicant( 1182): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1182): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1182): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1182): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1182): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1182): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1182): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1182): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1182): nl80211: Set supplicant port unauthorized for 00:00:00:00:00,:00
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1182): SET_SCREEN_ON:Off
I/wpa_supplicant( 1182): htc_wext_set_keepalive +
I/wpa_supplicant( 1182): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1182): getPrivFuncNum +	
I/wpa_supplicant( 1182): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1182): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1182): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 1182): get_ip_address source addr = 02000000
I/wpa_supplicant( 1182): htc_wext_set_keepalive gateway addr = 00000000
I/wpa_supplicant( 1182): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  904):    returned true
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doBoolean: SET pno 1
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): CTRL_IFACE SET 'pno'='1'
D/WifiNative-wlan0(  904):    returned true
D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  904): doString: LIST_DONGLES
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  904): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023644
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024011
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024167
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024177
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025645
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025659
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360028346
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029918
D/PMS     (  904): releaseWL(43402df0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1182): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1182): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1182): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1182): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1182): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1182): reply (617) for get BSS: id=0
I/wpa_supplicant( 1182): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1182): freq=5220
I/wpa_supplicant( 1182): level=-49
I/wpa_supplicant( 1182): tsf=0000000022270108
I/wpa_supplicant( 1182): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1182): ssid=NG7005g
I/wpa_supplicant( 1182): ====
I/wpa_supplicant( 1182): id=1
I/wpa_supplicant( 1182): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1182): freq=2412
I/wpa_supplicant( 1182): level=-62
I/wpa_supplicant( 1182): tsf=0000000022270119
I/wpa_supplicant( 1182): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1182): ssid=01ABC
I/wpa_supplicant( 1182): ====
I/wpa_supplicant( 1182): id=2
I/wpa_supplicant( 1182): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1182): freq=2412
I/wpa_supplicant( 1182): level=-62
I/wpa_supplicant( 1182): tsf=0000000106659003
I/wpa_supplicant( 1182): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1182): ssid=NG700
I/wpa_supplicant( 1182): ====
I/wpa_supplicant( 1182): id=3
I/wpa_supplicant( 1182): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1182): freq=2462
I/wpa_supplicant( 1182): level=-92
I/wpa_supplicant( 1182): tsf=0000000022270128
I/wpa_supplicant( 1182): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1182): ssid=UPC Wi-Free
I/wpa_supplicant( 1182): ====
I/wpa_supplicant( 1182): id=4
I/wpa_supplicant( 1182): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1182): freq=2462
I/wpa_supplicant( 1182): level=-92
I/wpa_supplicant( 1182): tsf=0000000022270132
I/wpa_supplicant( 1182): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1182): ssid=UPC0039325
I/wpa_supplicant( 1182): ####
D/WifiStateMachine(  904): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 22270108, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -62, frequency: 2412, timestamp: 22270119, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -62, frequency: 2412, timestamp: 106659003, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 3: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -92, frequency: 2462, timestamp: 22270128, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -92, frequency: 2462, timestamp: 22270132, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): add 5 to mScanResults
D/BatSI   (  904): WIFI scan stopped for: 440a0300 uid:1000
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  904): == begin of scan result ==
D/WifiStateMachine(  904): == (5) end of scan result ==
D/WifiStateMachine(  904): == begin of scan result ==
D/WifiStateMachine(  904): == (5) end of scan result ==
D/WirelessDisplayService(  904): getDiscoveryDongleList
D/WirelessDisplayService(  904): getDiscoveryDongleList
I/ActivityManager(  904): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4695 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
D/WifiNotificationController(  904): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
V/SRS_Proc(  370): ParamSet string: screen_state=off
D/NetworkPolicy(  904): updateScreenOn: false
,D/ContactMessageStore( 1239): start background delete task...
D/ContactMessageStore( 1239): size: 0 , 0
D/ContactMessageStore( 1239): Background delete complete
,I/MusicStore( 4695): Database version: 95
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] getTotalRam: 1873 Mb
,W/ContextImpl( 4695): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/PMS     (  904): acquireWL(440406d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  904): releaseWL(440406d0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/wpa_supplicant( 1182): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1182): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1182): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1182): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1182): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1182): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1182): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1182): nl80211: Event message available
D/wpa_supplicant( 1182): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1182): nl80211: Connect event
D/wpa_supplicant( 1182): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1182): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1182): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1182): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1182): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1182): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1182): Add randomness: count=9 entropy=1
I/wpa_supplicant( 1182): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1182): TDLS: Remove peers on association
D/wpa_supplicant( 1182): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1182): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1182): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 18
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1182): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1182): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1182): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/Tethering(  904): interfaceLinkStateChanged wlan0, false
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1182): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1182): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1182): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/Tethering(  904): interfaceStatusChanged wlan0, false
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1182): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1182): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1182): EAPOL: enable timer tick
D/wpa_supplicant( 1182): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1182): htc_wext_set_keepalive +
I/wpa_supplicant( 1182): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1182): getPrivFuncNum +	
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
I/wpa_supplicant( 1182): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1182): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1182): htc_wext_set_keepalive - ret = 0
D/Tethering(  904): [isWifi] getHotspotEnabled: false
I/wpa_supplicant( 1182): State: ASSOCIATED -> 4WAY_HANDSHAKE
,D/wpa_supplicant( 1182): Get randomness: len=32 entropy=2
D/Tethering(  904): interfaceLinkStateChanged wlan0, true
,D/Tethering(  904): interfaceStatusChanged wlan0, true
D/Tethering(  904): [isWifi] getHotspotEnabled: false
D/PMS     (  904): acquireWL(4362ce90): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(4362ce90): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/WifiMonitor(  904): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1778): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1778): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1778): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1778): disableBatteryAlarm: null
D/WifiMonitor(  904): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1778): onScreenOff
D/HTCRequest(  904): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  904): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  904): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  904): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  904): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  904): Enter handleAssociatedWithEvent
D/WifiStateMachine(  904): Associated
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
I/wpa_supplicant( 1182): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/WifiStateMachine(  904): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1182): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb7b479f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1182):    addr=c0:ff:d4:d3:aa:48
D/WifiStateMachine(  904): Exit handleAssociatedWithEvent
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1182): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1182): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1182): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6ef9b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1182):    broadcast key
D/WifiStateMachine(  904): BSSID was changed, update WiFi database
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1182): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1182): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1182): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1182): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1182): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1182): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1182): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1182): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1182): netlink: Operstate: linkmode=-1, operstate=6
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
I/wpa_supplicant( 1182): set send_ind_to_ndc = 0
I/wpa_supplicant( 1182): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1182): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_sup,plicant( 1182): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1182): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1182): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1182): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1182): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1182): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1182): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1182): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1182): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1182): EAPOL authentication completed successfully
I/wpa_supplicant( 1182): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1182): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1182): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1182): nl80211: if_removed already cleared - ignore event
D/WifiApDatabaseHandler(  904): updateConnectedAP...
D/WifiMonitor(  904): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
W/ContextImpl( 4695): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiApDatabaseHandler(  904): updateConnectedAP...
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  904): interfaceLinkStateChanged wlan0, true
D/Tethering(  904): interfaceStatusChanged wlan0, true
D/Tethering(  904): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  904): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  904): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  904): This record is existed, only update it...
D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  904): updateConnectedAP...
D/AutoSetting( 1324): service - mHandler: cancel location update
D/AutoSetting( 1324): service -           changes count: 0
,D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  904): updateConnectedAP...
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4695): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/WifiStateMachine(  904): fetchFrequency(), freq = 2412
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
D/WifiStateMachine(  904): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  904): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  904): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  904): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiApDatabaseHandler(  904): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  904): This record is existed, only update it...
D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  904): updateConnectedAP...
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  904): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  904): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  904): Provision feature enable=false
D/ConnectivityService(  904): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WISPrService( 4165): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WISPrService( 4165): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiApDatabaseHandler(  904): updateConnectedAP...
,D/WifiNative-wlan0(  904): doBoolean: SET pno 0
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1182): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1182): nl80211: Event message available
D/wpa_supplicant( 1182): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
,D/WifiNative-wlan0(  904):    returned true
,D/DhcpStateMachine(  904): [StoppedState] Start DHCP
,D/WifiStateMachine(  904): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiStateMachine(  904): handlePreDhcpSetup Held wake lock during DHCP
,D/WifiNative-wlan0(  904): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1182): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  904):    returned true
,D/WifiNative-wlan0(  904): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1182): Power_Mode_Type mode = 1
I/wpa_supplicant( 1182): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/wpa_supplicant( 1182): nl80211: Event message available
D/wpa_supplicant( 1182): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1182): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  904):    returned null
E/WifiStateMachine(  904): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  904): doString: DRIVER WLS_BATCHING STOP
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  904):    returned null
D/PMS     (  904): acquireWL(4256bb58): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 904 1000 null
D/WifiStateMachine(  904): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  904): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@424de750 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@424de750 target=com.android.internal.util.StateMachine$SmHandler }
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4695): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4695): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:0
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4695, uid=10154, userID:0
,D/WifiDisplayAdapter(  904): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  904):     Client/Owner: Client
D/WifiDisplayAdapter(  904):     GroupId: 
D/WifiDisplayAdapter(  904):     Passphrase: 
D/WifiDisplayAdapter(  904):     SessionId: 0
D/WifiDisplayAdapter(  904):     IP Address: }
,D/MediaRouterService(  904): Client com.google.android.music (pid 4695): Registered
,I/MediaRouter( 4695): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  904): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  904):     Client/Owner: Client
D/WifiDisplayAdapter(  904):     GroupId: 
D/WifiDisplayAdapter(  904):     Passphrase: 
D/WifiDisplayAdapter(  904):     SessionId: 0
D/WifiDisplayAdapter(  904):     IP Address: }
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.music (4695/10154)
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1987/10021)
,I/ActivityManager(  904): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4717 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4695): getSelectedRoute
,I/NetworkMonitor( 4695): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by com.google.android.music (4695/10154)
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4695, uid=10154, userID:0
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(430ea4c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/PMS     (  904): releaseWL(430ea4c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/Process (  904): killProcessQuiet, pid=4394
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4394:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,D/ACRA    ( 4717): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4717): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4717): Looking for error files in /data/data/com.facebook.katana/app_minidumps
I/ActivityManager(  904): Recipient 4394
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  904): Client connection lost with reason: 4
,W/SystemClassLoaderAdder( 4717): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4717): Preparing secondary program dexes.
V/DexLibLoader( 4717): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4717): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4717): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4717): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4717): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4717): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4717): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4717): Dex already copied
D/OdexVerifier( 4717): Odex verification is skipped.
,V/DexLibLoader( 4717): Creating class loader
,V/DexLibLoader( 4717): Finished creating class loader
V/DexLibLoader( 4717): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4717): Dex already copied
D/OdexVerifier( 4717): Odex verification is skipped.
,V/DexLibLoader( 4717): Creating class loader
,V/DexLibLoader( 4717): Finished creating class loader
V/DexLibLoader( 4717): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
,V/DexLibLoader( 4717): Dex already copied
D/OdexVerifier( 4717): Odex verification is skipped.
,V/DexLibLoader( 4717): Creating class loader
,V/DexLibLoader( 4717): Finished creating class loader
V/DexLibLoader( 4717): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4717): Dex already copied
D/OdexVerifier( 4717): Odex verification is skipped.
,V/DexLibLoader( 4717): Creating class loader
,V/DexLibLoader( 4717): Finished creating class loader
,V/DexLibLoader( 4717): Verifying classes from secondary dexes.
,D/DexLibLoader( 4717): DexLibLoader.ensureDexLoaded took 20 ms
,W/dalvikvm( 4717): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4717): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4717): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4717): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4717): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4717): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4717): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1182): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1182): EAPOL: disable timer tick
,W/dalvikvm( 4717): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4717): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4717): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4717): Verify
,I/SensorManager(  904): mEventCount = 1050
,D/libc    (  904): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiService(  904): New client listening to asynchronous messages
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4717/10027)
,D/libc    (  904): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
,W/fb4a(:<default>):BaseAnalyticsConfig( 4717): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4717): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
D/libc    (  904): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
,D/libc    (  904): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
D/libc    (  904): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  904): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1182): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  904):    returned true
,D/WifiNative-wlan0(  904): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1182): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1182): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  904):    returned true
,D/WifiNative-wlan0(  904): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/WifiP2pService(  904): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  904): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  904):    returned true
D/WifiStateMachine(  904): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [4][0][0]
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -62 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
D/PMS     (  904): releaseWL(4256bb58): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
I/dalvikvm-heap( 4717): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1182): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
,D/WifiStateMachine(  904): gateway: /192.168.1.1
D/WifiNative-wlan0(  904): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1182): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1182): htc_wext_set_keepalive +
I/wpa_supplicant( 1182): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1182): getPrivFuncNum +	
I/wpa_supplicant( 1182): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1182): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1182): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1182): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1182): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  904):    returned true
D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  904): VerifyingLinkState enter
D/WifiStateMachine(  904): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  904): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  904): VerifyingLinkState: enableIpv6
D/WIFI_ICON( 1116): updateWifiState: RSSI_CHANGED -1 -> 3
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/Process (  904): killProcessQuiet, pid=3926
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/WifiStateMachine(  904): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -62, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
,I/ActivityManager(  904): Killing 3926:com.htc.mediamanager/u0a34 (adj 15): empty #17
I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  904): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  904): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiWatchdogStateMachine(  904): WAN detection
D/WifiStateTracker(  904): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
V/NetworkPolicy(  904): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/ConnectivityService(  904): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  904): Provision feature enable=false
D/ConnectivityService(  904): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  904): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  904): default: teardown()
D/MDST    (  904): default: setTeardownRequested(true)
D/MDST    (  904): default: setEnableApn apnType =default , enable=false
,D/WISPrService( 4165): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/MDST    (  904): default: setTeardownRequested(true)
D/ConnectivityService(  904): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/libc    (  904): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
I/wpa_supplicant( 1182): Change stage from stage0 to stage3
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  904): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  904): syncGetConfiguredNetworks
E/ConnectivityService(  904): Unexpected mtu value: android.net.wifi.WifiStateTracker@424042f0
D/ConnectivityService(  904): handleConnectivityChange: netType=1 doReset=false resetMask=0
I/ActivityManager(  904): Recipient 3926
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  904): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  904): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  904): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  904): handleConnectivityChange: resetting
D/Nat464Xlat(  904): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  904): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/AutoSetting( 1324): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  904): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  904): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  904): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  904): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  904): acquireWL(440117a0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 904 1000 null
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by  (904/1000)
I/QuickSettingWifi( 1116): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/WirelessDisplayService(  904): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  904):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [1][0][0]
,D/AutoSetting( 1324): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
,I/logwrapper(  363): /system/bin/ip terminated by exit(254)
I/ActivityManager(  904): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4769 uid=10079 gids={50079, 3003, 5012}
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.sense.hsp (1324/10055)
D/AutoSetting( 1324): service - onStartCommand() screen is off, don't request location
,D/AutoSetting( 1324): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1324): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.sense.hsp (1324/10055)
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,W/fb4a(:<default>):UserScope( 4717): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4717): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
D/ConnectivityService(  904): mActiveDefaultNetwork: WIFI
,W/fb4a(:<default>):UserScope( 4717): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/PMS     (  904): releaseWL(440117a0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/MobileConnectivityChangeReceiver( 4769): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4769): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4769): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4769): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  904): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4790 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  904): killProcessQuiet, pid=4249
,I/ActivityManager(  904): Killing 4249:com.google.android.talk/u0a111 (adj 15): empty #17
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.setupwizard (4769/10079)
,D/PMS     (  904): acquireWL(423c99a0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.setupwizard (4769/10079)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.setupwizard (4769/10079)
,D/PMS     (  904): acquireWL(4256dfd0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(423c99a0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I/CheckinService( 2176): Checkin interval check for package: unspecified last checkin: 1450833941584 min interval config: 0 actual interval: 53183
,I/CheckinService( 2176): Checking schedule, now: 1450833994773 next: 1450833971563
,I/CheckinService( 2176): active receiver: enabled
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2176, uid=10029, userID:0
,I/CheckinService( 2176): Preparing to send checkin request
,I/EventLogService( 2176): Accumulating logs since 1450833938286
E/dalvikvm( 4717): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4717): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4717): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4717): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4717): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4717): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
E/dalvikvm( 4717): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4717): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4717): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4717): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4717): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4717): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4717): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4717): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4717): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4717): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4717): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4717): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 4249
,I/ActivityManager(  904): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4805 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  904): killProcessQuiet, pid=4431
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  904): Killing 4431:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 4431
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4717): Grow heap (frag case) to 9.921MB for 39954-byte allocation
,I/CheckinRequestBuilder( 2176): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  904): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2176): Failed to find provider info for com.google.android.wearable.settings
,I/dalvikvm-heap( 4717): Grow heap (frag case) to 9.999MB for 79892-byte allocation
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4805): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4805): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4805): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4805): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4805): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4717): Grow heap (frag case) to 10.061MB for 84664-byte allocation
,D/ConnectivityService(  904): getNetworkInfo networkType=9 called by com.google.android.gms (2176/10029)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [2][0][0]
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.magazines (4805/10151)
,V/WebViewChromiumFactoryProvider( 4805): Binding Chromium to main looper Looper (main, tid 1) {41a79b98}
,I/LibraryLoader( 4805): Expected native library version number "",actual native library version number ""
,I/chromium( 4805): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4805): Initializing chromium process, renderers=0
,D/PMS     (  904): acquireWL(4404a3b8): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
,E/AudioManagerAndroid( 4805): BLUETOOTH permission is missing!
D/PMS     (  904): acquireWL(4341efe8): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  904): releaseWL(4404a3b8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/dalvikvm-heap( 4717): Grow heap (frag case) to 10.275MB for 75760-byte allocation
,I/Adreno-EGL( 4805): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4805): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4805): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4805): Local Branch: 
I/Adreno-EGL( 4805): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4805): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4805):                  aa63bbd948f41d15fc72f585e
,I/ActivityManager(  904): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4840 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4717/10027)
,W/BroadcastQueue(  904): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{424af638 u0 ReceiverList{42451108 4717 com.facebook.katana/10027/u0 remote:4232d558}}
,W/BroadcastQueue(  904): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{424af638 u0 ReceiverList{42451108 4717 com.facebook.katana/10027/u0 remote:4232d558}}
,W/BroadcastQueue(  904): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4372ef38 u0 ReceiverList{4363a100 4717 com.facebook.katana/10027/u0 remote:434a2478}}
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023644
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024011
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024167
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024177
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025645
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025659
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360028346
,I/NSApplication( 4805): Starting up...
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029918
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4717/10027)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.magazines (4805/10151)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.magazines (4805/10151)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4717/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4717/10027)
W/dalvikvm( 4840): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
W/dalvikvm( 4840): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4840): VM with version 1.6.0 does not have multidex support
I/MultiDex( 4840): install
I/MultiDex( 4840): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,I/MultiDex( 4840): loading existing secondary dex files
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,I/MultiDex( 4840): load found 3 secondary dex files
,I/MultiDex( 4840): install done
,D/Process (  904): killProcessQuiet, pid=4462
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.plus (4141/10160)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.plus (4141/10160)
,I/ActivityManager(  904): Killing 4462:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
I/ActivityManager(  904): Recipient 4462
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,W/dalvikvm( 4840): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4840): VFY: unable to resolve instance field 36
,W/dalvikvm( 4840): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/PMS     (  904): acquireWL(4369a878): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,D/PMS     (  904): releaseWL(4369a878): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,V/JNIHelp ( 4840): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1376/10029)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1376/10029)
,D/SmartSyncUtils( 4676): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4676): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4676): isEpsOn(), nState = 0
W/ContextImpl( 4676): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/WifiService(  904): New client listening to asynchronous messages
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@426a2c80
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  904): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/ContextImpl( 4717): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 1
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@426a2c80, eanble = 0, strlen(mName) = 36
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  904): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 0
W/SensorService(  904): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@426a2c80, eanble = 0, strlen(mName) = 36
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@426a2c80
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4717): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
E/ActivityThread(  904): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4258b508 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  904): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4258b508 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4717): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,I/ProviderInstaller( 4840): Installed default security provider GmsCore_OpenSSL
,W/dalvikvm( 4840): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4840): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/WearableService( 1222): callingUid 10029, callindPid: 1222
,D/LocationInitializer( 2176): Restart initialization of location
,W/dalvikvm( 4840): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4840): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4840): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4840): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4840): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/AuthorizationBluetoothService( 1376): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1376): Proximity feature is not enabled.
,E/MDM     ( 1222): [120] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1222): No location to return for getLastLocation()
,W/FusedLocationProvider( 1222): location=null
D/PMS     (  904): acquireWL(441952c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  904): releaseWL(441952c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/WVCdm   (  370): Level3 Library Nov 20 2013 18:09:31
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023644
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024011
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024167
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024177
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025645
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025659
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360028346
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029918
,W/WVCdm   (  370): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  370): CdmEngine::OpenSession
,I/WVCdm   (  370): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  370): CdmEngine::GenerateKeyRequest
,D/NativeLibraryUtils( 4840): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  370): PrepareKeyRequest: nonce=3664629278
,I/WVCdm   (  370): CdmEngine::CloseSession
,D/PMS     (  904): releaseWL(43c98898): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  904): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  904): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  904): [AlarmQueuing] connectivity wifi: true
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/GpsLocationProvider(  904): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  904): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  904): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  904): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by  (904/1000)
D/PMS     (  904): acquireWL(4343dbf0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 904 1000 null
D/PMS     (  904): releaseWL(4343dbf0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
,D/CaptivePortalTracker(  904): NoActiveNetworkState
,I/WVCdm   (  370): CdmEngine::OpenSession
,I/WVCdm   (  370): CdmEngine::QueryKeyControlInfo
,V/Tethering(  904): bSetPropertyMultiRAB:false
I/WVCdm   (  370): CdmEngine::GenerateKeyRequest
,D/Tethering(  904): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by com.htc.launcher (1271/10076)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.backuptransport (1594/10029)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.setupwizard (4769/10079)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.musicenhancer (3966/10053)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4717/10027)
I/ConnectivityHelper( 1271): [onReceive] WIFI(1): CONNECTED
,D/CaptivePortalTracker(  904): DelayedCaptiveCheckState
,D/AccTypeManager( 1338): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/Tethering(  904): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  904): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  904): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  904): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  904): Found interface wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/Tethering(  904): TetherMasterSM: InitialState processMessage what=3
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,I/NetworkMonitor( 4695): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.backuptransport (1594/10029)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023644
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024011
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024167
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024177
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025645
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025659
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360028346
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029918
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by com.google.android.music (4695/10154)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4717/10027)
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/htcCheckinService(  904): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  904): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4717/10027)
,D/PMS     (  904): acquireWL(43500308): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=100 [1][1][0]
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,D/PMS     (  904): releaseWL(43500308): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
W/AccTypeManager( 1338): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1338): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1987/10021)
,E/ExternalAccountType( 1338): Unsupported attribute readOnly
,D/WVCdm   (  370): PrepareKeyRequest: nonce=3790363281
,D/AutoSetting( 1324): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4769): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4769): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.sense.hsp (1324/10055)
,D/AutoSetting( 1324): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1324): service - onStartCommand() screen is off, don't request location
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.magazines (4805/10151)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.sense.hsp (1324/10055)
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/AutoSetting( 1324): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1324): service - onStartCommand() check timezone in 30000
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.plus (4141/10160)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.plus (4141/10160)
,I/WVCdm   (  370): CdmEngine::CloseSession
,I/CheckinService( 2176): Checkin interval check for package: unspecified last checkin: 1450833941584 min interval config: 0 actual interval: 54218
,I/dalvikvm-heap( 4141): Grow heap (frag case) to 13.501MB for 1821008-byte allocation
D/PMS     (  904): acquireWL(435099c8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  904): releaseWL(435099c8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2176, uid=10029, userID:0
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1376/10029)
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1376/10029)
,I/Adreno-EGL( 4840): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4840): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4840): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4840): Local Branch: 
I/Adreno-EGL( 4840): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4840): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4840):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4840): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4840): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4840): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4840): Local Branch: 
I/Adreno-EGL( 4840): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4840): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4840):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4840): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4840): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4840): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4840): Local Branch: 
I/Adreno-EGL( 4840): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4840): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4840):                  aa63bbd948f41d15fc72f585e
,W/Settings( 4840): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (4840/10029)
,I/CheckinRequestBuilder( 2176): Classify the device as Phone.
,W/dalvikvm( 4613): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4613): threadid=1: thread exiting with uncaught exception (group=0x4164ce30)
,E/ActivityManager(  904): App crashed! Process: com.test.thalitest
E/AndroidRuntime( 4613): FATAL EXCEPTION: main
E/AndroidRuntime( 4613): Process: com.test.thalitest, PID: 4613
E/AndroidRuntime( 4613): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4613): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4613): 	,at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4613): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4613): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4613): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4613): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4613): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4613): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4613): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4613): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4613): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4613): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4613): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4613): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4613): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4613): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4613): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4613): 	at dalvik.system.NativeStart.main(Native Method)
W/ActivityManager(  904):   Force finishing activity com.test.thalitest/.MainActivity
,D/Process (  904): killProcessQuiet, pid=4485
,I/ActivityManager(  904): Killing 4485:com.htc.backup/1000 (adj 15): empty #17
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
D/Process ( 4613): killProcess, pid=4613
D/Process ( 4613): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2176): [NET] getaddrinfo-,err=8
D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2176): [NET] getaddrinfo-, 1
,D/libc    ( 2176): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =9229 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 287
D/libc    (  363): [NET]res_nsend:resplen=84
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2176): [NET] getaddrinfo_proxy-, success
,I/ActivityManager(  904): Recipient 4485
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2176): [NET] getaddrinfo-,err=8
,I/ActivityManager(  904): Recipient 4613
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Process com.test.thalitest (pid 4613) has died.
,I/WindowState(  904): WIN DEATH: Window{43766940 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2176): [NET] getaddrinfo-,err=8
D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2176): [NET] getaddrinfo-,err=8
D/WifiService(  904): Client connection lost with reason: 4
,D/WifiStateMachine(  904): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  904): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent DefaultState
,I/CheckinTask( 2176): Sending checkin request (12201 bytes)
,W/InputMethodManagerService(  904): Got RemoteException sending setActive(false) notification to pid 4613 uid 10389
W/Binder  ( 1208): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1208): java.lang.NullPointerException
W/Binder  ( 1208): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1208): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1208): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1208): 	at dalvik.system.NativeStart.run(Native Method)
,I/CheckinRequestBuilder( 2176): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  904): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2176): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4717/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4717/10027)
,D/ConnectivityService(  904): getNetworkInfo networkType=9 called by com.google.android.gms (2176/10029)
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=10 [19][2][0]
,W/fb4a(:<default>):UserScope( 4717): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4717): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4717/10027)
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,I/CheckinRequestBuilder( 2176): Classify the device as Phone.
,I/CheckinTask( 2176): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4717/10027)
,I/CheckinService( 2176): Checking schedule, now: 1450833997481 next: 1451356934473
,I/CheckinService( 2176): active receiver: disabled
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2176, uid=10029, userID:0
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023644
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024011
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024167
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024174
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024177
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025645
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025659
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360028346
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029918
,I/CheckinService( 2176): Checking schedule, now: 1450833997513 next: 1451356934473
,I/CheckinService( 2176): active receiver: disabled
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2176, uid=10029, userID:0
,D/CheckinService( 2176): Recording last checkin time for package unspecified as 1450833997521
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023644
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024011
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024167
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024177
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025645
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025659
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360028346
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029918
,D/PMS     (  904): releaseWL(4256dfd0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,D/PMS     (  904): acquireWL(44054620): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/libc    ( 1376): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1376): [NET] getaddrinfo-,err=8
D/libc    ( 1376): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1376): [NET] getaddrinfo-, 1
D/libc    ( 1376): [NET] getaddrinfo_proxy+
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1376/10029)
D/GCM     ( 1376): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =3ed4 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=79
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1376): [NET] getaddrinfo_proxy-, success
,D/libc    (  904): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-,err=8
D/libc    (  904): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  904): [NET] getaddrinfo-, 1
,D/libc    (  904): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =cddf +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    ( 1376): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1376): [NET] getaddrinfo-,err=8
,E/fb4a(:<default>):LocalFbBroadcastManager( 4717): Called registerBroadcastReceiver twice.
,D/libc    ( 1376): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1376): [NET] getaddrinfo-,err=8
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1376/10029)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1376/10029)
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=172
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  904): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  904): Find DNS Address www.htc.com/104.81.130.175
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1376/10029)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1376/10029)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4717/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4717/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4717/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4717/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4717/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4717/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4717/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4717/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4717/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4717/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4717/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4717/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4717/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4717/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4717/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4717/10027)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4717/10027)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4717/10027)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4717/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4717/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4717/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4717/10027)
,D/PMS     (  904): acquireWL(4373ced8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1376/10029)
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1376/10029)
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1376/10029)
,D/PMS     (  904): releaseWL(44054620): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1376/10029)
,D/ConnectivityService(  904): reportInetCondition for net 1, percentage: 100 by  (1376/10029)
,D/ConnectivityService(  904): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  904): handleInetConditionChange: starting a change hold
,D/PMS     (  904): releaseWL(4373ced8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(436f6f18): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1376/10029)
,D/ConnectivityService(  904): reportInetCondition for net 1, percentage: 100 by  (1376/10029)
D/ConnectivityService(  904): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  904): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1376/10029)
,D/ConnectivityService(  904): reportInetCondition for net 1, percentage: 100 by  (1376/10029)
,D/ConnectivityService(  904): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  904): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1376/10029)
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023644
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024011
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024167
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024177
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025645
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025659
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360028346
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029918
,D/PMS     (  904): releaseWL(436f6f18): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(44070b98): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4695 10154 null
,W/ContextImpl( 4695): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4695, uid=10154, userID:0
,I/MusicLeanback( 4695): Conditions not met for autocaching.
,I/MusicLeanback( 4695): Stop autocaching.
D/PMS     (  904): releaseWL(44070b98): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,W/ContextImpl( 4695): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/PMS     (  904): releaseWL(4341efe8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,E/ActivityThread( 4695): Service com.google.android.music.leanback.AutoCacheSchedulingService has leaked ServiceConnection com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp@41b80860 that was originally bound here
E/ActivityThread( 4695): android.app.ServiceConnectionLeaked: Service com.google.android.music.leanback.AutoCacheSchedulingService has leaked ServiceConnection com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp@41b80860 that was originally bound here
E/ActivityThread( 4695): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 4695): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 4695): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 4695): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 4695): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 4695): 	at com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService(SafeServiceConnection.java:98)
E/ActivityThread( 4695): 	at com.google.android.music.utils.SafeServiceConnection.bindService(SafeServiceConnection.java:259)
E/ActivityThread( 4695): 	at com.google.android.music.download.AbstractSchedulingService.onCreate(AbstractSchedulingService.java:764)
E/ActivityThread( 4695): 	at com.google.android.music.leanback.AutoCacheSchedulingService.onCreate(AutoCacheSchedulingService.java:175)
E/ActivityThread( 4695): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/ActivityThread( 4695): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/ActivityThread( 4695): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/ActivityThread( 4695): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4695): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread( 4695): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/ActivityThread( 4695): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread( 4695): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread( 4695): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread( 4695): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread( 4695): 	at dalvik.system.NativeStart.main(Native Method)
,D/ConnectivityService(  904): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  904): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [12][0][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/AutoSetting( 1508): service - handleMessage() stop self
,D/AutoSetting( 1508): service - onDestroy() END
,D/AutoSetting( 1508): service - handleMessage() quit looper
,D/ContactMessageStore( 1239): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1239): MSG_NOTIFY_CS_TO_SYNC <<
,I/GAV2    ( 4805): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  904): killProcessQuiet, pid=4505
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4505:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 4505
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  904): killProcessQuiet, pid=3966
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3966:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3966
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver replacing:false
,I/ActivityManager(  904): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4910 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,D/AccTypeManager( 1338): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  904):   Scheme: "sms"
,W/SystemReader( 1254): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "smsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1271): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "mms"
I/Launcher( 1271): Deferring update until onResume
,D/Launcher( 1271): waitUntilResume // bindAppsUpdated
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,W/AccTypeManager( 1338): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1338): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "mmsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "sms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "smsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "mms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "mmsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,E/ExternalAccountType( 1338): Unsupported attribute readOnly
,D/PhoneApp( 1239): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4910): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4910): MmsConfig.loadMmsSettings
,W/dalvikvm( 4910): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4910): VFY: unable to resolve instance field 36
,W/dalvikvm( 4910): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4910): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  904): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4933 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,D/MessageFrequencyProvider( 4933): onCreate
,W/Settings( 4910): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4910, uid=10111, userID:0
V/GetPrviateResource( 4933): GetPrviateResource
V/GetPrviateResource( 4933): GetPrviateResource
,D/MmsCustomizationProvider( 4933): query uri: content://htc-mms-customization/mms-ua/ua_string
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4910, uid=10111, userID:0
,D/MmsCustomizationProvider( 4933): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4910, uid=10111, userID:0
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4910, uid=10111, userID:0
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4910, uid=10111, userID:0
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4910, uid=10111, userID:0
D/PMS     (  904): acquireWL(430ea630): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4910 10111 null
,I/Babel   ( 4910): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4910): MmsConfig.loadFromDatabase
,E/Babel   ( 4910): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4910): MmsConfig.loadFromResources
,E/Babel   ( 4910): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4910): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/[PluginManager]RegisterService( 1324): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1324): handle notify Blinkfeed plugin client changed
I/ActivityManager(  904): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  904): Resuming delayed broadcast
,I/IcingCorporaProvider( 2896): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  904): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/ProviderInstaller( 4910): Installed default security provider GmsCore_OpenSSL
,D/PMS     (  904): acquireWL(436e62e0): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
D/MessageCustFlag( 4933): sense_version=6.0
,D/BTAccessoryUtil( 4933): createReceiver
,D/BTAccessoryUtil( 4933): registerReceiver return intent = null
D/MessageCustFlag( 4933): sku_id=99
,W/SystemReader( 4933): Cannot find message_ambs_application_id, use default value instead
,D/Process (  904): killProcessQuiet, pid=4449
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  904): releaseWL(430ea630): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
I/ActivityManager(  904): Killing 4449:com.htc.cs.dm/u0a98 (adj 15): empty #17
,D/Messaging( 4933): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4933): networkCode: 
,D/MessageCustFlag( 4933): sku_id=99
D/MmsConfig( 4933): SIE smsPri: null
,D/MmsConfig( 4933): networkCode: 
D/HtcTelephonyCapability( 4933): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4933): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4933): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4933): Cannot find qct_8960_interface, use default value instead
I/ActivityManager(  904): Recipient 4449
,W/PackageManager(  904): Unable to load service info ResolveInfo{4250bca0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  904): releaseWL(436e62e0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  904): Resuming delayed broadcast
,D/PMS     (  904): acquireWL(43438328): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  904): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  904): acquireWL(44153180): PARTIAL_WAKE_LOCK  AsyncService 0x1 4141 10160 null
,I/dalvikvm-heap( 4141): Grow heap (frag case) to 15.200MB for 1821008-byte allocation
D/PMS     (  904): releaseWL(43438328): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  904): releaseWL(44153180): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  904): Resuming delayed broadcast
,D/PMS     (  904): acquireWL(436067b0): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,I/dalvikvm-heap( 4141): Grow heap (frag case) to 16.937MB for 1821008-byte allocation
I/ActivityManager(  904): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  904): releaseWL(436067b0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  904): Resuming delayed broadcast
,D/PMS     (  904): acquireWL(42545028): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  904): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,D/PMS     (  904): releaseWL(42545028): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  904): Resuming delayed broadcast
,D/PMS     (  904): acquireWL(4305d200): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  904): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
,D/PMS     (  904): releaseWL(4305d200): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  904): Resuming delayed broadcast
,D/PMS     (  904): acquireWL(4365d2f8): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,D/PackageBroadcastService( 2176): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  904): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/PackageBroadcastService( 2176): Null package name or gms related package.  Ignoreing.
D/PMS     (  904): releaseWL(4365d2f8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(43b8abb8): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 2176): updateResources: need to parse f{com.google.android.gms}
,D/RemoteDisplayProvider(  904): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  904): start
,I/GCoreNlp( 1222): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  904): applying state to connected service
D/PMS     (  904): acquireWL(4311bb38): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  904): releaseWL(4311bb38): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  904): applying state to connected service
,D/PMS     (  904): acquireWL(43729ce8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(43729ce8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(435c5ed8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2896): UpdateCorporaTask done [took 332 ms] updated apps [took 332 ms] 
D/PMS     (  904): releaseWL(435c5ed8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  904): Resuming delayed broadcast
,D/CaptivePortalTracker(  904): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  904): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  904): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1271): loadItems() com.htc.launcher.pageview.WidgetManager@41b0fd10 +
,I/Prism.WidgetManager( 1271): onLoadItems() +
,I/Icing   ( 2176): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2176): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  904): releaseWL(43b8abb8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1271): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1271): onLoadItems() -
,I/Prism.ItemManager( 1271): loadItems() com.htc.launcher.pageview.WidgetManager@41b0fd10 -
,D/PhoneApp( 1239): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1239): -- N1 =0
,D/PhoneApp( 1239): -- N2 =0
,D/PhoneApp( 1239): -- N3 =0
,D/Messaging( 4933): mNeedToUpdateDate2 start
,D/MmsConfig( 4933): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4933): startAsyncQueryReports ---
,D/SettingsManager( 4933): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41a86558
D/MmsAsyncWorkHandler( 4933): 
D/MmsAsyncWorkHandler( 4933): HM tk = 20001
D/ReportIndicatorCache( 4933): MSG_QUERY_REPORTS >>
,I/Messaging( 4933): mccmnc> 
D/DraftCache( 4933): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4933): [DraftCache/1] refresh
,D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
D/MmsSmsV2Provider( 1239):  phoneType = -1
D/MmsSmsV2Provider( 1239): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/MmsConfig( 4933): networkCode: 
,D/Messaging( 4933): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
,D/MmsSmsV2Provider( 1239):  phoneType = -1
,D/MmsSmsV2Provider( 1239): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/MessageCustFlag( 4933): sense_version=6.0
D/PhoneStorageUtil( 4933): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4933): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4933): createReceiver
,D/Jerry   ( 4933): start to preload cursor >>>>>>>
,D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/TelephUtils( 1239): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
V/MmsProvider( 1239): Update uri=content://mms, match=0
,V/MmsProvider( 1239): selection=st=129 AND m_type!=134
,D/Messaging( 4933): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4933): TransactionService is going to be woken up.
D/MmsSmsV2Provider( 1239):  phoneType = -1
,D/MmsSmsV2Provider( 1239): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,V/TransactionService( 4933): 1-Creating TransactionService
,D/Messaging( 4933): mNeedToUpdateDate2: false
,D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/AccFlag ( 1239): sku_id=99
,V/TransactionService( 4933): onStartCommand: 1
,D/MmsSystemEventReceiver( 4933): unRegisterForConnectionStateChanges
V/TransactionService( 4933): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4933): Loading previous transactions.
,D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/DraftCache( 4933): [DraftCache/487] rebuildCache
,D/MmsSmsV2Provider( 1239):  phoneType = -1
,D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1239): device_type: 1
D/TransactionService( 4933): Force set service start id to 1
V/TransactionService( 4933): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4933): unRegisterForConnectionStateChanges
D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
D/MmsSmsV2Provider( 1239):  phoneType = -1
D/MmsSmsV2Provider( 1239): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/TransactionService( 4933): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4933): Destroying TransactionService
,V/TransactionService( 4933): 4-Handling incoming message: { when=-3ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/Jerry   ( 1239): URI_DRAFT
,D/Messaging( 4933): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/DraftCache( 4933): hasDraft() = false mNeedNotifyChange = true
D/Messaging( 4933): ViewCache CreatePreload
,D/Messaging( 4933): ViewCache CreatePreloadOnlyMultipleOpsList
D/DraftCache( 4933): [DraftCache/487] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4933): ,
D/MmsAsyncWorkHandler( 4933): HM tk = 20002
D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/AccFlag ( 1239): sku_id=99
,D/Cust_MMSMS( 4933): _has_set_default_values_2=true
,D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1239): sku_id=99
,D/MsgPreferenceUtils( 4933): def_index: 0
,D/MsgPreferenceUtils( 4933): globalIndex = 1
D/MsgPreferenceUtils( 4933): phone state: true
D/MsgPreferenceUtils( 4933): sd state: false
,D/MsgPreferenceUtils( 4933): vIndex = 0
,I/ActivityManager(  904): Waited long enough for: ServiceRecord{43752d48 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,I/GAV4    ( 4910): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  904): acquireWL(431162f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  904): sending alarm PendingIntent{426a8e10: PendingIntentRecord{42547a08 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=124843, Int=0
,D/PMS     (  904): releaseWL(431162f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(44050bf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1376/10029)
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=16 [6][1][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/PMS     (  904): acquireWL(433a1398): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(44050bf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(433a1398): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(43b65e58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023644
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024011
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024167
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024177
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025645
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025659
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360028346
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029918
,D/PMS     (  904): releaseWL(43b65e58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(440536c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1376/10029)
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023644
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024011
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024167
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024174
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024177
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025645
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025659
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360028346
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029918
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/PMS     (  904): acquireWL(43c770c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(43512630): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1222): Vacuum at: now=1450834011116 tag=VacuumService
D/PMS     (  904): releaseWL(440536c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(43c770c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(436dcc18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023644
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024011
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024167
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024177
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025645
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025659
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360028346
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029918
,D/PMS     (  904): releaseWL(436dcc18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(434391f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(43512630): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1376/10029)
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023644
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024011
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024167
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024174
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024177
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024181
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025645
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025659
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360028346
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029918
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  904): releaseWL(434391f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/PMS     (  904): acquireWL(430e79f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023644
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024011
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024167
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024174
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024177
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024181
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025645
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025659
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360028346
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029918
,D/PMS     (  904): releaseWL(430e79f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(43412b68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1376/10029)
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023644
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024011
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024167
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024174
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024177
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025645
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025659
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360028346
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029918
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  904): releaseWL(43412b68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  904): acquireWL(43553678): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1376/10029)
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023644
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024011
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024167
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024177
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025645
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025659
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360028346
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029918
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/PMS     (  904): acquireWL(435c5508): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(435c5508): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(43151b98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(43553678): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(435a2ac0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023644
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024011
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024167
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024174
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024177
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025645
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025659
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360028346
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029918
,D/PMS     (  904): releaseWL(435a2ac0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1222): Scheduling Phenotype for one-off execution 3035 seconds from now (1450834011814)
,D/GetConfigurationSnapshotOperation( 1222): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1222): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1222): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1222): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1222): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1222): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1222): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  904): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1222): [NET] getaddrinfo-,err=8
,D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1222): [NET] getaddrinfo-, 1
,D/libc    ( 1222): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =dbc3 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 263
D/libc    (  363): [NET]res_nsend:resplen=87
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1222): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1222): [NET] getaddrinfo-,err=8
D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1222): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  904): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=12 [8][1][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  904): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  904): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL,
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!,
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
,D/LocationManagerService(  904): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/PMS     (  904): releaseWL(43151b98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(437058d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023644
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024011
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024167
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024177
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025645
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025659
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360028346
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029918
,D/PMS     (  904): releaseWL(437058d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(436fabb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1376/10029)
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023644
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024011
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024167
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024177
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025645
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025659
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360028346
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029918
,D/PMS     (  904): releaseWL(436fabb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(436e5860): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(436e5860): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  904): acquireWL(4311cda0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41aaae88: PendingIntentRecord{41b29228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=133935, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4311cda0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42542ef8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  904): sending alarm PendingIntent{434383e8: PendingIntentRecord{42413a30 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=136804, Int=0
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1376/10029)
,D/PMS     (  904): releaseWL(42542ef8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1324): service - mHandler: update timezone
,D/AutoSetting( 1508): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  904): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1508): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1508): service - onCreate()
D/AutoSetting( 1508): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1508): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
W/ActivityManager(  904): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
V/NotificationService(  904): batLight: Full, plugged
D/AutoSetting( 1508): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1508): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1508): service - mHandler: update timezone
,D/DotMatrix( 1583): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1583): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c800
D/qdlights(  904): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1508): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1508): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1508): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1508): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1583): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1583): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1116): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41e58f48 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.htc.htclocationservice 2 8 2 11
,D/AutoSetting( 1324): service - mHandler: update timezone
,D/AutoSetting( 1508): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  904): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1508): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1508): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1508): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 1508): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1508): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1508): service - mHandler: update timezone
W/ActivityManager(  904): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
V/NotificationService(  904): batLight: Full, plugged
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c800
D/qdlights(  904): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/DotMatrix( 1583): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1583): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1508): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1508): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1508): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1508): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1583): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1583): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1116): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41e58f48 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/AutoSetting( 1324): service - handleMessage() stop self
,I/RemoteViews.Performance( 1116): com.htc.htclocationservice 3 7 2 11
,D/AutoSetting( 1324): service - onDestroy() END
,D/AutoSetting( 1324): service - handleMessage() quit looper
,D/GpsLocationProvider(  904): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  904): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  904): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  904): acquireWL(42470c80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
V/AlarmManager(  904): sending alarm PendingIntent{4244ceb8: PendingIntentRecord{423fec48 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141658, Int=0
D/PMS     (  904): acquireWL(42408118): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 904 1000 null
D/PMS     (  904): releaseWL(42470c80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  904): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-,err=8
D/libc    (  904): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  904): [NET] getaddrinfo-, 1
,D/libc    (  904): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =ab66 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE,
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59,
D/libc    (  363): [NET]res_nsend:resplen=238
D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  904): [NET] getaddrinfo_proxy-, success,
I/global  (  904): call createSocket() return a new socket.
D/libc    (  904): [NET] getaddrinfo+,hn 13(0x35342e3234302e),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  904): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  904): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  904): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  904):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  904): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  904): releaseWL(42408118): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,D/Process (  904): killProcessQuiet, pid=4226
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4226:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 4226
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/ContactMessageStore( 1239): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1239): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  904): Waited long enough for: ServiceRecord{4406c528 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  904): acquireWL(422ef5a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(422ef5a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/AutoSetting( 1508): service - handleMessage() stop self
,D/AutoSetting( 1508): service - onDestroy() END
,D/AutoSetting( 1508): service - handleMessage() quit looper
,I/ActivityManager(  904): Killing 4537:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  904): killProcessQuiet, pid=4537
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  904): Recipient 4537
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  904): acquireWL(4234f840): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10027}
,V/AlarmManager(  904): sending alarm PendingIntent{43089ba0: PendingIntentRecord{43f5a490 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=172504, Int=0
,D/PMS     (  904): releaseWL(4234f840): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1239): switchBindHtcMsgCursor: null
,D/PMS     (  904): acquireWL(423f1450): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(423f1450): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
,I/HtcPowerSaver(  904): >> updateStatus
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(424db208): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41aaae88: PendingIntentRecord{41b29228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=193935, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(424db208): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(425ddb28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(425ddb28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,I/ClearcutLoggerApiImpl( 1376): disconnect managed GoogleApiClient
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  904): acquireWL(424f1350): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(424f1350): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(425e7970): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41aaae88: PendingIntentRecord{41b29228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=253935, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(425e7970): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  904): acquireWL(424e5230): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): releaseWL(424e5230): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(425a14d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(425a14d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(424fc520): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41aaae88: PendingIntentRecord{41b29228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=313935, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1271): Grow heap (frag case) to 12.625MB for 50416-byte allocation
D/PMS     (  904): releaseWL(424fc520): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  904): killProcessQuiet, pid=4551
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4551:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 4551
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  904): acquireWL(43641970): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): closing low battery warning: level=100
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(43641970): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  904): acquireWL(43d67708): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43d67708): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1116): closing low battery warning: level=100
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  904): acquireWL(42573ed8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41aaae88: PendingIntentRecord{41b29228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=373935, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42573ed8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  904): acquireWL(44193428): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(44193428): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(44069bf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/UsbnetService(  904): BroadcastReceiver::onReceive+
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): onReceive BATTERY_CHANGED
,I/BatteryService(  904): n_update end
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/PMS     (  904): releaseWL(44069bf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(434961b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41aaae88: PendingIntentRecord{41b29228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=433935, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(434961b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43116890): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43116890): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
,I/HtcPowerSaver(  904): >> updateStatus
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  904): acquireWL(425335d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
D/PMS     (  904): releaseWL(425335d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  904): acquireWL(43b663a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41aaae88: PendingIntentRecord{41b29228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=493935, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43b663a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  904): acquireWL(43008048): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43008048): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(435b5060): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(435b5060): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(4245f730): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41aaae88: PendingIntentRecord{41b29228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=553935, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4245f730): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(436e2970): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
D/PMS     (  904): releaseWL(436e2970): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  904): BroadcastReceiver::onReceive-
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  351): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  904): acquireWL(42614ac0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41aaae88: PendingIntentRecord{41b29228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=613935, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1271): Grow heap (frag case) to 12.626MB for 50416-byte allocation
,D/PMS     (  904): releaseWL(42614ac0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ContactMessageStore( 1239): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1239): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1239): sku_id=99
,D/ContactMessageStore( 1239): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1239): start background delete task...
,D/ContactMessageStore( 1239): size: 0 , 0
,D/ContactMessageStore( 1239): Background delete complete
,D/PMS     (  904): acquireWL(423362a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): releaseWL(423362a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43b2fab0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
D/PMS     (  904): releaseWL(43b2fab0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42820b30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41aaae88: PendingIntentRecord{41b29228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=673935, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42820b30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(441b6500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PMS     (  904): releaseWL(441b6500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43c7b7f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43c7b7f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(433668b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41aaae88: PendingIntentRecord{41b29228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=733935, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(433668b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43519fa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PowerUI ( 1116): closing low battery warning: level=100
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PMS     (  904): releaseWL(43519fa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(4403b600): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
D/PMS     (  904): releaseWL(4403b600): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): closing low battery warning: level=100
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(435e2050): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41aaae88: PendingIntentRecord{41b29228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=793935, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(435e2050): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43ca1920): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(43ca1920): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(425319e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
D/PMS     (  904): releaseWL(425319e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(4340acc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41aaae88: PendingIntentRecord{41b29228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=853935, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4340acc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(437e2860): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(437e2860): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/ConnectivityService(  904): Sampling interval elapsed, updating statistics ..
,D/PMS     (  904): acquireWL(436365d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
V/AlarmManager(  904): sending alarm PendingIntent{41d4dcf8: PendingIntentRecord{4240eaa8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=785002, Int=0
,V/AlarmManager(  904): sending alarm PendingIntent{41d18a68: PendingIntentRecord{42475b28 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=889939, Int=0
,D/ConnectivityService(  904): Done.
,D/ConnectivityService(  904): Setting timer for 720seconds
,I/ActivityManager(  904): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=5045 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  904): sending alarm PendingIntent{425b0c30: PendingIntentRecord{41e27c50 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1450834097996, Int=10800000
,V/AlarmManager(  904): sending alarm PendingIntent{4264cfc8: PendingIntentRecord{425b15b8 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450834593578, Int=1800000
,D/PMS     (  904): acquireWL(433dfd58): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 904 1000 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(43712c08): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
,D/PMS     (  904): acquireWL(44062b90): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(433dfd58): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  904): releaseWL(43712c08): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  904): acquireWL(43b2fd88): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(44062b90): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(436365d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029}
,I/EventLogService( 2176): Aggregate from 1450833994827 (log), 1450832793513 (data)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.aurora (5045/10049)
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023644
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024011
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024167
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024177
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025645
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025659
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360028346
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029918
,D/PMS     (  904): releaseWL(43b2fd88): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023644
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024011
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024167
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024177
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025645
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025659
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360028346
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029918
,D/Process (  904): killProcessQuiet, pid=4584
,I/ActivityManager(  904): Killing 4584:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  904): Recipient 4584
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  904): acquireWL(44047600): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PowerUI ( 1116): closing low battery warning: level=100
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): releaseWL(44047600): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
,I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(436f0d00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41aaae88: PendingIntentRecord{41b29228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=913935, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(436f0d00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43009b70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  904): releaseWL(43009b70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): closing low battery warning: level=100
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43612950): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): releaseWL(43612950): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42505ba8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41aaae88: PendingIntentRecord{41b29228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=973935, Int=0
I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42505ba8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ActivityManager(  904): Start proc com.htc.launcher:biclient for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService: pid=5063 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,D/PMS     (  904): acquireWL(43ec82d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10076}
,V/AlarmManager(  904): sending alarm PendingIntent{43bcbc90: PendingIntentRecord{43bc9408 com.htc.launcher startService}}, i=com.htc.BiLogClient.ACTION_SEND_LOG, t=3, cnt=1, w=900000, Int=1800000
,V/AlarmManager(  904): sending alarm PendingIntent{423b9820: PendingIntentRecord{42602500 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450834818497, Int=900000
,V/AlarmManager(  904): sending alarm PendingIntent{425997d8: PendingIntentRecord{42511448 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450834895154, Int=0
,W/ContextImpl( 4676): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4676): call getInstance()
,D/SmartSyncUtils( 4676): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4676): MY_DEBUG = false
D/PMS     (  904): acquireWL(4238a990): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4676 1000 null
D/PMS     (  904): releaseWL(43ec82d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 4676): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4676): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4676): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4676): SettingOnTime = 1450850400000, randomSettingOnTime = 1450848627000
,D/SmartSyncScreenOnOffTimeReceiver( 4676): SettingOffTime = 1450836000000, randomSettingOffTime = 1450840614000
,D/SmartSyncScreenOnOffTimeReceiver( 4676): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 4676): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4676): bNightModeTurnOffOnce = false
,D/PMS     (  904): releaseWL(4238a990): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,I/ImageRamCache( 5063): create image Cache, size: 31457280.
I/ImageRamCache( 5063): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 5063): create image Cache, size: 12582912.
,I/FeedSettings( 5063): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 5063): GroupBudget 0.500000 0.380000
,I/FeedSettings( 5063): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 5063): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 5063): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 5063): loadGridSize() with Alternative
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,D/libc    ( 5063): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 4
D/libc    ( 5063): [NET] getaddrinfo-,err=8
D/libc    ( 5063): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 1024
D/libc    ( 5063): [NET] getaddrinfo-, 1
,D/libc    ( 5063): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =17a +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE,
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,D/PMS     (  904): acquireWL(441985f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  904): sending alarm PendingIntent{41c27410: PendingIntentRecord{424704a8 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1011772, Int=0
,D/PMS     (  904): acquireWL(4414b638): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(4414b638): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(441985f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(440e89a8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1376 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1376/10029)
,D/ConnectivityService(  904): reportInetCondition for net 1, percentage: 100 by  (1376/10029)
D/ConnectivityService(  904): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  904): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1376/10029)
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360023644
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024011
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024167
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024177
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024181
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025645
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025659
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360028346
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029918
,D/PMS     (  904): releaseWL(440e89a8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  904): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  904): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=3 [128][5][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/libc    (  363): [NET]Querying server xid =17a (# 1) address = 192.168.1.1 (try=2,nscount=1)
,D/libc    (  363): [NET]res_nsend:ETIMEDOUT
D/libc    (  363): [NET] -----res_nsend exit-1: xid=17a, total retry = 3 times, errno=110,v_circuit=0-----
D/libc    (  363): [NET]res_queryN: exit 2
D/libc    (  363): [NET]_dns_getaddrinfo- 6, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 5063): [NET] getaddrinfo_proxy-
,E/[CSBICLIENT][v9][BiLogUploadService]( 5063): Exception on getConfig()
D/Process (  904): killProcessQuiet, pid=4769
,I/ActivityManager(  904): Killing 4769:com.google.android.setupwizard/u0a79 (adj 15): empty #17
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  904): Recipient 4769
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  904): acquireWL(44052e00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(44052e00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43f5a428): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41aaae88: PendingIntentRecord{41b29228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1033935, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43f5a428): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43de8d08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43de8d08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43c725f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43c725f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(43c66b50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
V/AlarmManager(  904): sending alarm PendingIntent{41aaae88: PendingIntentRecord{41b29228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1093935, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43c66b50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43c64460): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43c64460): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43bbe460): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43bbe460): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43a5bd78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41aaae88: PendingIntentRecord{41b29228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1153935, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43a5bd78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43949fa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43949fa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(43744c40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43744c40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  351): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  904): acquireWL(43720568): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000},
,V/AlarmManager(  904): sending alarm PendingIntent{41aaae88: PendingIntentRecord{41b29228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1213935, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43720568): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(436754e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(436754e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(4351ed18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4351ed18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43403aa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41aaae88: PendingIntentRecord{41b29228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1273935, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1271): Grow heap (frag case) to 12.626MB for 50416-byte allocation
,D/PMS     (  904): releaseWL(43403aa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(431a1dc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(431a1dc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
,D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
V/NotificationService(  904): batLight: plugged
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c80000
D/qdlights(  904): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/HtcPowerSaver(  904): updateBatteryInfo
D/qdlights(  904): [LedInfo] has indicator attribute
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=98
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetPhoneState( 1688): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/DotMatrix( 1583): [EventService] reorderNotification, total:1
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/HtcPowerSaver(  904): updateStatus (8000,98,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
W/ContextImpl( 4676): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 4165): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4165): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4165): Cust_ConnectToPC   : Modem_Link>false
,D/        ( 4165): Cust_ConnectToPC   : spcsc>false
,D/        ( 4165): Cust_ConnectToPC   : IPT>true
,D/        ( 4165): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4165): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4165): Index of the first 1 = -1
W/ContextImpl( 4165): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 4165): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 4165): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4165): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4165): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4165): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
D/SmartNS_Utility( 4165): [ACC]android_networking:tethering_guard_support=false
I/BatteryController( 1116): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(423aacc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(423aacc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(41cc99e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41aaae88: PendingIntentRecord{41b29228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1333935, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(41cc99e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42322a70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42322a70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(422afd38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41aaae88: PendingIntentRecord{41b29228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1393935, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(422afd38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(422bc8d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(422bc8d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(41e5d3d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41aaae88: PendingIntentRecord{41b29228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1453935, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(41e5d3d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42590d30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42590d30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,D/PowerUI ( 1116): closing low battery warning: level=99
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1116): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(41d74fb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(41d74fb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(43691fa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41aaae88: PendingIntentRecord{41b29228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1513935, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43691fa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42560a90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/PMS     (  904): releaseWL(42560a90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,D/PowerUI ( 1116): closing low battery warning: level=99
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1116): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(41d51ef0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(41d51ef0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(422716b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41aaae88: PendingIntentRecord{41b29228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1573935, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(422716b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(425467e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PowerUI ( 1116): closing low battery warning: level=99
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(425467e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
,I/HtcPowerSaver(  904): >> updateStatus
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/HtcPowerSaver(  904): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1116): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43495590): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41aaae88: PendingIntentRecord{41b29228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1633935, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43495590): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42448168): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42448168): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HeadsetPhoneState( 1688): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HtcPowerSaver(  904): updateBatteryInfo
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1583): [EventService] reorderNotification, total:0
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
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
I/HtcPowerSaver(  904): >> updateStatus
W/ContextImpl( 4676): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,D/TetherSettings( 4165): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4165): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4165): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4165): Cust_ConnectToPC   : spcsc>false
D/        ( 4165): Cust_ConnectToPC   : IPT>true
D/        ( 4165): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 4165): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4165): Index of the first 1 = -1
W/ContextImpl( 4165): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 4165): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 4165): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4165): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4165): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4165): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(4245dc78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): releaseWL(4245dc78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42559be8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41aaae88: PendingIntentRecord{41b29228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1693936, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42559be8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(4373d110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4373d110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(41d14160): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41aaae88: PendingIntentRecord{41b29228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1753935, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(41d14160): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,D/PMS     (  904): acquireWL(43accf00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/PMS     (  904): releaseWL(43accf00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(426d7d18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(426d7d18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  351): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  904): acquireWL(424d5638): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41aaae88: PendingIntentRecord{41b29228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1813935, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(424d5638): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(425170c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(425170c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
,I/HtcPowerSaver(  904): >> updateStatus
D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,I/ProcessStatsService(  904): Prepared write state in 44ms
,I/ProcessStatsService(  904): Pruning old procstats: /data/system/procstats/state-2015-12-22-01-49-17.bin
,D/PMS     (  904): acquireWL(441951c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(441951c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(425d0518): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
V/AlarmManager(  904): sending alarm PendingIntent{41aaae88: PendingIntentRecord{41b29228 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1873935, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(425d0518): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 5110): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 5110): ====startRecUseTime====
D/htc.customization.log.level( 5110):  is 
W/CustomizationLogLevel( 5110): Level value is invalid, use default level 2
D/CustomizationManager( 5110):  Read ACC file spent 0.131 (s)
D/CIDMapFileReader( 5110): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5110): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5110): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5110): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 5110): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5110): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 5110): Parsing tag item name = HTC__016
D/CIDMapFileReader( 5110): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5110): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5110): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5110): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 5110): Parsing tag category name = system
I/CustomizationCIDLoader( 5110): Parsing tag category name = application
I/CustomizationCIDLoader( 5110): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5110): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5110): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5110): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5110): Parsing tag category name = Settings
D/CustomizationManager( 5110):  Read CID file spent 0.188 (s)
D/CustomizationManager( 5110):  All configurations done spent 0.189 (s)
W/HtcNativeFlag( 5110): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 5110): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 5110): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 5110): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  904): deletePackageAsUser: pkg=com.test.thalitest, pid=5110, uid=2000 user=0
I/ActivityManager(  904): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  904): killProcessQuiet, pid=4695
I/ActivityManager(  904): Killing 4695:com.google.android.music:main/u0a154 (adj 15): empty for 1800s
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  904): killProcessQuiet, pid=4805
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  904): killProcessQuiet, pid=4790
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  904): Killing 4805:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1802s
I/ActivityManager(  904): Killing 4790:com.android.chrome/u0a96 (adj 15): empty for 1802s
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Recipient 4695
D/MediaRouterService(  904): Client com.google.android.music (pid 4695): Died!
I/ActivityManager(  904): Recipient 4790
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/asset   (  904): Copying FileAsset 0x62448f40 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
W/PackageSettings(  904): Skipping PackageSetting{421bd150 com.example.hello/10397} due to missing metadata
I/ActivityManager(  904): Recipient 4805
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1583): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1583): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1583): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver replacing:false
W/GeofencerStateMachine( 1222): Ignoring removeGeofence because network location is disabled.
D/PMS     (  904): acquireWL(44047090): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  904): releaseWL(44047090): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/Prism.ItemManager( 5063): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 5063): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/AccTypeManager( 1338): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/VoicemailCleanupService( 1284): Cleaning up data for package: com.test.thalitest
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "sms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "smsto"
I/Launcher( 1271): Deferring update until onResume
D/Launcher( 1271): waitUntilResume // bindAppsRemoved
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/InputMethodManagerService(  904): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mms"
W/AccTypeManager( 1338): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1338): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/Prism.PackageStateRece_( 1271): action: android.intent.action.PACKAGE_REMOVED
I/[PluginManager]RegisterService( 1324): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1324): handle notify Blinkfeed plugin client changed
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
W/SystemReader( 1254): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mmsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/IcingCorporaProvider( 2896): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "sms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
E/ExternalAccountType( 1338): Unsupported attribute readOnly
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "smsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/ActivityManager(  904): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5125 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mmsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
D/PhoneApp( 1239): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  904): acquireWL(43c87f00): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  904): releaseWL(43c87f00): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  904): acquireWL(43c66cd0): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2896): UpdateCorporaTask done [took 472 ms] updated apps [took 472 ms] 
E/SQLiteDatabase( 5125): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 5125): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5125): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5125): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5125): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5125): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5125): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5125): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5125): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5125): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5125): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5125): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5125): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5125): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5125): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5125): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 5125): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 5125): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 5125): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 5125): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 5125): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5125): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 5125): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 5125): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 5125): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 5125): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 5125): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 5125): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 5125): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 5125): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 5125): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 5125): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5125): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5125): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5125): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5125): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5125): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5125): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5125): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 5125): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 5125): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5125): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5125): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 5125): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 5125): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5125): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5125): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5125): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 5125): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 5125): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 5125): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 5125): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 5125): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5125): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5125): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 5125): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 5125): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 5125): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 5125): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 5125): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5125): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 5125): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 5125): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 5125): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 5125): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 5125): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 5125): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 5125): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 5125): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 5125): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 5125): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5125): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 5125): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 5125): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5125): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5125): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 5125): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 5125): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 5125): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 5125): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 5125): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5125): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5125): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5125): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5125): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5125): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5125): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5125): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5125): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5125): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5125): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5125): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5125): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5125): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5125): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 5125): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 5125): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 5125): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 5125): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 5125): threadid=11: thread exiting with uncaught exception (group=0x4164ce30)
E/ActivityManager(  904): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 5125): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 5125): Process: com.google.android.apps.docs, PID: 5125
E/AndroidRuntime( 5125): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5125): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5125): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5125): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5125): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5125): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5125): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5125): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5125): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5125): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5125): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5125): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5125): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5125): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5125): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 5125): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 5125): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 5125): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 5125): 	at aho.run(AbstractDatabaseInstance.java:455)
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
E/SQLiteDatabase( 5125): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 5125): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5125): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5125): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5125): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5125): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5125): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5125): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5125): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5125): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5125): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5125): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5125): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5125): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5125): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5125): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 5125): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 5125): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 5125): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 5125): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 5125): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 5125): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5125): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5125): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5125): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5125): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5125): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5125): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5125): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 5125): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 5125): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5125): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5125): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 5125): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 5125): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5125): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5125): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5125): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 5125): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 5125): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 5125): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 5125): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 5125): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5125): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5125): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 5125): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 5125): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 5125): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 5125): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 5125): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 5125): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5125): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 5125): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 5125): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5125): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5125): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 5125): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 5125): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 5125): Opened ClientFlag.db in read-only mode
I/ActivityManager(  904): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5145 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process ( 5125): killProcess, pid=5125
D/Process ( 5125): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  904): Recipient 5125
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Process com.google.android.apps.docs (pid 5125) has died.
W/ContextImpl( 5145): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  904): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=5159 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 5145): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5145): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5145): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5145): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5145): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5145): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5145): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5145): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5145): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5145): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5145): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5145): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5145): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5145): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5145): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5145): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 5145): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 5145): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5145): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5145): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5145): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 5145): threadid=10: thread exiting with uncaught exception (group=0x4164ce30)
E/AndroidRuntime( 5145): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5145): Process: com.android.keychain, PID: 5145
E/AndroidRuntime( 5145): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5145): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5145): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5145): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5145): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5145): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5145): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5145): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5145): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5145): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5145): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5145): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5145): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5145): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5145): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 5145): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 5145): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5145): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5145): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5145): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  904): App crashed! Process: com.android.keychain
D/ErrorReport(  904): HtcErrorReportManager Begin---add error logs to dropbox
D/AppTag  ( 5159): getInstance(Context context)
D/Process ( 5145): killProcess, pid=5145
D/Process ( 5145): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  904): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  904): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1450835800070.dbox_tmp: open failed: EROFS (Read-only file system)
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
D/AppTag  ( 5159): getInstance(Context context)
D/AppTag  ( 5159): onCreate()
I/ActivityManager(  904): Recipient 5145
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Process com.android.keychain (pid 5145) has died.
W/ActivityManager(  904): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/PMS     (  904): acquireWL(424b0238): PARTIAL_WAKE_LOCK  AsyncService 0x1 4141 10160 null
D/PMS     (  904): releaseWL(424b0238): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/dalvikvm( 4182): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 2176): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2176): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 2176): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2176): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 2176): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2176): Module APK com.google.android.play.games already loaded
I/ActivityManager(  904): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
E/SQLiteLog( 2176): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 2176): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2176): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6ee88db8
E/SQLiteDBG( 2176): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x652949b8
I/LocationSettingsChecker( 2176): Removing dialog suppression flag for package com.test.thalitest
W/dalvikvm( 2176): threadid=48: thread exiting with uncaught exception (group=0x4164ce30)
W/PackageManager(  904): Unable to load service info ResolveInfo{423c19b0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
E/AndroidRuntime( 2176): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2176): Process: com.google.android.gms, PID: 2176
E/AndroidRuntime( 2176): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2176): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2176): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2176): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2176): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2176): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2176): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2176): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2176): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2176): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2176): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2176): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2176): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2176): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2176): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2176): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2176): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2176): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2176): 	at java.lang.Thread.run(Thread.java:864)
E/DriveAsyncService( 2176): disk I/O error (code 3850)
E/DriveAsyncService( 2176): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2176): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2176): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2176): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2176): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2176): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2176): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2176): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2176): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2176): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2176): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2176): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2176): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2176): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2176): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2176): 	at java.lang.Thread.run(Thread.java:864)
E/ActivityManager(  904): App crashed! Process: com.google.android.gms
D/Process ( 2176): killProcess, pid=2176
D/Process ( 2176): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/SQLiteDatabase( 2176): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 2176): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2176): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2176): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2176): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2176): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2176): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2176): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2176): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2176): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2176): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2176): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2176): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2176): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2176): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2176): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 2176): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 2176): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 2176): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 2176): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2176): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2176): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2176): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  904): Can't write: system_app_crash
E/DropBoxManagerService(  904): java.io.FileNotFoundException: /data/system/dropbox/drop144.tmp: open failed: EROFS (Read-only file system)
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
I/Prism.ItemManager( 5063): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 5063): loadItems() com.htc.launcher.pageview.WidgetManager@41aea728 +
I/Prism.WidgetManager( 5063): onLoadItems() +
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1271): loadItems() com.htc.launcher.pageview.WidgetManager@41b0fd10 +
I/Prism.WidgetManager( 1271): onLoadItems() +
I/ActivityManager(  904): Recipient 2176
D/PMS     (  904): handleWLDeath(43c66cd0): PARTIAL_WAKE_LOCK  Icing 0x1
D/WifiService(  904): Client connection lost with reason: 4
I/ActivityManager(  904): Process com.google.android.gms (pid 2176) has died.
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 11000ms
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 20999ms
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 20997ms
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20996ms
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20996ms
I/ActivityManager(  904): Resuming delayed broadcast
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20985ms
E/SQLiteLog( 1376): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1376): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x63f92010
W/dalvikvm( 1376): threadid=1: thread exiting with uncaught exception (group=0x4164ce30)
E/ActivityManager(  904): App crashed! Process: com.google.process.gapps
E/AndroidRuntime( 1376): FATAL EXCEPTION: main
E/AndroidRuntime( 1376): Process: com.google.process.gapps, PID: 1376
E/AndroidRuntime( 1376): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1376): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1376): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1376): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1376): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1376): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1376): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1376): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1376): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1376): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1376): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1376): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1376): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1376): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1376): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1376): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1376): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1376): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1376): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1376): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1376): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1376): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1376): 	... 10 more
E/DropBoxManagerService(  904): Can't write: system_app_crash
E/DropBoxManagerService(  904): java.io.FileNotFoundException: /data/system/dropbox/drop145.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 1376): killProcess, pid=1376
I/ActivityManager(  904): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5188 uid=10098 gids={50098, 3003, 5012}
D/Process ( 1376): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 

```
