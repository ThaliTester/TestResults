#### Test 54970261aa56788_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main,
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1181): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  904):    returned true
E/cutils-trace( 4331): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4331): ====startRecUseTime====
D/htc.customization.log.level( 4331):  is 
W/CustomizationLogLevel( 4331): Level value is invalid, use default level 2
D/CustomizationManager( 4331):  Read ACC file spent 0.051 (s)
D/CIDMapFileReader( 4331): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4331): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4331): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4331): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4331): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4331): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4331): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4331): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4331): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4331): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4331): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4331): Parsing tag category name = system
I/CustomizationCIDLoader( 4331): Parsing tag category name = application
I/CustomizationCIDLoader( 4331): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4331): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4331): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4331): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4331): Parsing tag category name = Settings
D/CustomizationManager( 4331):  Read CID file spent 0.091 (s)
D/CustomizationManager( 4331):  All configurations done spent 0.091 (s)
W/HtcNativeFlag( 4331): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4331): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4331): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4331): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
W/CpuWake (  904): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  904): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  904): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  904): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  904): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  904): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  904): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4331
D/PMS     (  904): acquireHCC(42d2d380): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 904 1000 null
D/PMS     (  904): acquireHCC(437dcc08): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 904 1000 null
I/Intent  (  904): @test_code: getHtcIntentFlag: 0 obj: 1114578824
D/PMS     (  904): acquireWL(42581038): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 904 1000 null
I/FeedHostManager( 1266): [onPause]
I/FeedProviderManager( 1266): onPause
I/FeedHostManager( 1266): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41cb8b08
I/SocialFeedProvider( 1266): +onPause
I/SocialFeedProvider( 1266): -onPause
I/ActivityManager(  904): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4342 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1266): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 4342): Binding Chromium to main looper Looper (main, tid 1) {41b732d8}
I/LibraryLoader( 4342): Expected native library version number "",actual native library version number ""
I/chromium( 4342): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4342): Initializing chromium process, renderers=0
W/System.err(  904): java.lang.Throwable: stack dump
D/BluetoothManagerService(  904): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  904): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42744fc0:true
W/System.err(  904): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  904): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  904): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  904): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  904): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4342): 1102613776: getState(). Returning 12
D/PMS     (  904): acquireWL(441250f0): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  904): acquireWL(43d6fae8): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  904): releaseWL(441250f0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4342): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4342): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4342): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4342): Local Branch: 
I/Adreno-EGL( 4342): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4342): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4342):                  aa63bbd948f41d15fc72f585e
W/chromium( 4342): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4342): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4342): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4342): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4342): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4342): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4342): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4342): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4342): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4342): CordovaWebView is running on device made by: HTC
,W/AwContents( 4342): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  904): Disable input method client, pid=1266
,I/ActivityManager(  904): Displayed com.test.thalitest/.MainActivity: +255ms
,W/ResourceType( 4342): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4342): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41bba3c0, mServedView=org.apache.cordova.engine.SystemWebView{41b80028 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1206): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1206): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1206): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1206): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  904): Enable input method client, pid=4342
,W/AwContents( 4342): nativeOnDraw failed; clearing to background color.
D/PMS     (  904): releaseWL(42581038): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4342): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4342): JniHelper::setJavaVM(0x4164d010), pthread_self() = 1628744928
,D/JX-Cordova( 4342): jxcore cordova android initializing
,I/dalvikvm-heap( 4342): Grow heap (frag case) to 11.624MB for 95956-byte allocation
,I/dalvikvm-heap( 4342): Grow heap (frag case) to 11.703MB for 143930-byte allocation
,I/dalvikvm-heap( 4342): Grow heap (frag case) to 11.818MB for 215890-byte allocation
,I/dalvikvm-heap( 4342): Grow heap (frag case) to 11.993MB for 323830-byte allocation
,I/dalvikvm-heap( 4342): Grow heap (frag case) to 12.265MB for 485740-byte allocation
,I/dalvikvm-heap( 4342): Grow heap (frag case) to 13.265MB for 1092904-byte allocation
,I/dalvikvm-heap( 4342): Grow heap (frag case) to 14.156MB for 1639352-byte allocation
,I/dalvikvm-heap( 4342): Grow heap (frag case) to 15.484MB for 2459024-byte allocation
,I/dalvikvm-heap( 4342): Grow heap (frag case) to 17.504MB for 3688532-byte allocation
,W/jxcore-log( 4342): Initializing JXcore engine
,W/jxcore-log( 4342): JXcore engine is ready
,W/jxcore-log( 4342): Starting JXcore engine
,W/CpuWake (  904): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  904): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  904): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  904): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  904): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  904): <<release mCpuPerf_Freq wakelock
D/PMS     (  904): releaseHCC(42d2d380): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  904): releaseHCC(437dcc08): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4342): Platform android
W/jxcore-log( 4342): 
,W/jxcore-log( 4342): Process ARCH arm
W/jxcore-log( 4342): 
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1181): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
,I/jxcore-log( 4342): JXcore Cordova bridge is ready!
I/jxcore-log( 4342): 
,W/jxcore-log( 4342): JXcore engine is started
,I/chromium( 4342): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4342): Toggling radios to true
I/jxcore-log( 4342): 
,D/BluetoothAdapter( 4342): enable(): BT is already enabled..!
,D/WifiManager( 4342): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
W/HtcDLNAServiceManager(  904): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  904): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  904): Settings:Agentvalue: 2
W/Settings:Agent(  904): >> traceCallingStack()
W/Settings:Agent(  904): Process.myPid(): 904
W/Settings:Agent(  904): Process.myTid(): 1099
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
,D/WifiManager( 4342): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  904): doBoolean: DISCONNECT
D/WifiManager( 4342): reconnect: Base Package Name=com.test.thalitest, uid=10389
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1181): TDLS: Tear down peers
,I/wpa_supplicant( 1181): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4342): Radios toggled
I/jxcore-log( 4342): 
D/WifiService(  904): setWifiEnabled: true pid=4342, uid=10389
E/WifiService(  904): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  904): New client listening to asynchronous messages
I/WifiService(  904): isSprintWifiRestricted(): false
I/WifiService(  904): isMdmWifiRestricted(): false
D/WifiSettingsStore(  904): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1181): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1181): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,I/wpa_supplicant( 1181): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/Tethering(  904): interfaceLinkStateChanged wlan0, false
D/Tethering(  904): interfaceStatusChanged wlan0, false
,D/Tethering(  904): [isWifi] getHotspotEnabled: false
D/HTCRequest(  904): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  904): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  904): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  904): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  904): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1181): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1181): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1181): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1181): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1181): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1181): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1181): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1181): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1181): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1181): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb7ef4bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1181):    addr=c0:ff:d4:d3:aa:48
D/Tethering(  904): interfaceLinkStateChanged wlan0, false
E/wpa_supplicant( 1181): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1181): State: COMPLETED -> DISCONNECTED
D/Tethering(  904): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1181): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1181): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1181): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1181): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1181): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1181): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1181): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1181): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1181): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1181): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1181): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1181): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1181): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1181): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/Tethering(  904): [isWifi] getHotspotEnabled: false
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1181): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1181): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1181): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1181): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1181): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1181): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1181): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1181): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1181): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1181): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1181): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1181): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1181): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1181): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1181): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1181): RTM_NEWLI,NK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1181): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1181): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1181): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1181): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1181): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1181): nl80211: Event message available
D/wpa_supplicant( 1181): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1181): nl80211: Ignore disconnect event triggered during reassociation
D/WifiNative-wlan0(  904):    returned true
D/WifiPerfLock(  904): release()
D/WifiStateMachine(  904): PerfLock released for exiting ConnectedState
,D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0(  904): doBoolean: DRIVER POWERMODE 0
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0",
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1181): Power_Mode_Type mode = 0,
,I/wpa_supplicant( 1181): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 61
D/ConnectivityService(  904): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  904): acquireWL(441aacf8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 904 1000 null
D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1181): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  904):    returned true
,D/DhcpStateMachine(  904): [RunningState] Stop DHCP
D/libc    (  904): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
D/WifiP2pService(  904): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024217
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024669
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024957
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024979
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024997
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025019
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026480
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026494
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029170
D/WifiStateMachine(  904): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  904): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-, SUCCESS
D/WifiDataStallTracker(  904): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  904): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  904): stopDataStallAlarm: current tag=21006 mDataStallAlarmIntent=PendingIntent{4229f7b8: PendingIntentRecord{42688d30 android broadcastIntent}}
I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiNative-wlan0(  904): doBoolean: RECONNECT
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1181): Fast associate: Old scan results
I/wpa_supplicant( 1181): wpa_supplicant_scan enter
I/wpa_supplicant( 1181): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1181): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1181): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1181): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1181): nl80211: Event message available
D/wpa_supplicant( 1181): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/WifiNative-wlan0(  904):    returned true
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024217
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024669
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024957
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024979
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024997
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025019
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026480
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026494
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029170
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiStateTracker(  904): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  904): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  904): Provision feature enable=false
,D/ConnectivityService(  904): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiStateMachine(  904): Enter handleNetworkDisconnect
D/WifiNative-wlan0(  904): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1181): Power_Mode_Type mode = 0
I/wpa_supplicant( 1181): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1181): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  904):    returned true
D/UsbnetStateTracker(  904): isAvailable+-
D/UsbnetStateTracker(  904): reconnect
,D/UsbnetStateTracker(  904): isAvailable+-
,D/WISPrService( 3735): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  904): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/WifiP2pService(  904): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  904): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  904): default: reconnect()
D/MDST    (  904): default: setTeardownRequested(false)
D/MDST    (  904): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  904): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  904): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
,D/ConnectivityService(  904): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  904): Exit handleNetworkDisconnect
D/WifiDataStallTracker(  904): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  904): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WISPrService( 3735): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WISPrService( 3735): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  904): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WifiStateTracker(  904): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiService(  904): New client listening to asynchronous messages
W/ConnectivityService(  904): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  904): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  904): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  904): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
,D/ConnectivityService(  904): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WifiStateMachine(  904): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 3735): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,V/NativeCrypto( 1358): Read error: ssl=0x6565eb00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1358): SSL shutdown failed: ssl=0x6565eb00: I/O error during system call, Broken pipe
D/libc    (  364): [NET] entry_id:2   entry:0xb70e74f0  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb70e7320  removed 
D/libc    (  364): [NET] entry_id:5   entry:0xb70e6fd8  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb70e7428  removed 
D/libc    (  364): [NET] entry_id:6   entry:0xb70e7240  removed 
D/libc    (  364): [NET] entry_id:3   entry:0xb70e70e8  removed 
D/libc    (  364): [NET] entry_id:7   entry:0xb70e2f60  removed 
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
W/ConnectivityService(  904): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  904): handleConnectivityChange: resetting
D/ConnectivityService(  904): resetConnections(wlan0, 3)
D/PMS     (  904): acquireWL(42746cf8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  904): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  904): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  904): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  904): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/WirelessDisplayService(  904): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,I//system/bin/ip(  364): RTNETLINK answers: No such process
D/WirelessDisplayService(  904): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
D/PMS     (  904): acquireWL(43d59ee0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 904 1000 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  904): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by  (904/1000)
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024217
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024669
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024957
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024979
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024997
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025019
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026480
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026494
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029170
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1358/10029)
,D/WifiStateMachine(  904): startScan Pid: 904 Uid 1000
D/WifiNative-wlan0(  904): doBoolean: SCAN
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,I/wpa_supplicant( 1181): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  904):    returned false
,I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:0
D/BatSI   (  904): WIFI scan started for: 650a0300 uid:1000
D/ConnectivityService(  904): reportInetCondition for net -1, percentage: 0 by  (1358/10029)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1358/10029)
D/PMS     (  904): releaseWL(42746cf8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1358/10029)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1358/10029)
D/ConnectivityService(  904): mActiveDefaultNetwork: -1
D/ConnectivityService(  904): handleInetConditionChange: no active default network - ignore
,I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:1
D/PMS     (  904): releaseWL(43d59ee0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/PMS     (  904): releaseWL(43d6fae8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/SensorManager(  904): mEventCount = 1050
,V/Tethering(  904): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/Tethering(  904): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  904): bSetPropertyMultiRAB:false
D/htcCheckinService(  904): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  904): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,D/CaptivePortalTracker(  904): DelayedCaptiveCheckState
D/CaptivePortalTracker(  904): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  904): NoActiveNetworkState
I/ConnectivityHelper( 1266): [onReceive] WIFI(1): DISCONNECTED
,D/Tethering(  904): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  904): [AlarmQueuing] connectivity wifi: false
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by  (904/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.backuptransport (1575/10029)
D/PMS     (  904): acquireWL(434b2978): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 904 1000 null
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by com.google.android.music (3789/10154)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by com.htc.launcher (1266/10076)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
I/Tethering(  904): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  904): ipv4Default null
I/Tethering(  904): No IPv4 upstream interface, giving up.
,D/Tethering(  904): TetherMasterSM: InitialState processMessage what=3
,I/NetworkMonitor( 3789): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.docs (4194/10100)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024217
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024669
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024957
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024979
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024997
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025019
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026480
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026494
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029170
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.docs (4194/10100)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (2368/10021)
,I/ActivityManager(  904): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4395 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4395): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4395): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4395): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,D/GpsLocationProvider(  904): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  904): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  904): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  904): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  904): releaseWL(434b2978): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/SystemClassLoaderAdder( 4395): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4395): Preparing secondary program dexes.
V/DexLibLoader( 4395): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4395): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4395): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4395): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4395): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4395): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4395): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4395): Dex already copied
D/OdexVerifier( 4395): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4395): Creating class loader,
V/DexLibLoader( 4395): Finished creating class loader
V/DexLibLoader( 4395): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4395): Dex already copied
D/OdexVerifier( 4395): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4395): Creating class loader
,V/DexLibLoader( 4395): Finished creating class loader
V/DexLibLoader( 4395): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4395): Dex already copied
D/OdexVerifier( 4395): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4395): Creating class loader,
V/DexLibLoader( 4395): Finished creating class loader,
V/DexLibLoader( 4395): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4395): Dex already copied
D/OdexVerifier( 4395): Odex verification is skipped. OS version not supported.
V/DexLibLoader( 4395): Creating class loader
V/DexLibLoader( 4395): Finished creating class loader
V/DexLibLoader( 4395): Verifying classes from secondary dexes.
D/DexLibLoader( 4395): DexLibLoader.ensureDexLoaded took 16 ms
,W/dalvikvm( 4395): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4395): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4395): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4395): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4395): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4395): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4395): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,I/PMS     (  904): Going to sleep due to screen timeout...
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@422a1748
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  904): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 2
W/SensorService(  904): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@422a1748, eanble = 0, strlen(mName) = 59
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  904): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420082d8
W/SensorService(  904): Listener[1] = com.htc.smartdim.sensor_eye@427c2490
,W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  904): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  904): Couldn't get kernel wake lock stats
,V/LightsService(  904): setLight #2: color=#0
,D/qdlights(  904): set_light_buttons_func: on=0 brightness=0
,V/LightsService(  904): setLight #0: color=#0
,D/WirelessDisplayService(  904): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  904): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  904): mWirelessDisplayManager is null
,D/wpa_supplicant( 1181): nl80211: Event message available
D/wpa_supplicant( 1181): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1181): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1181): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1181): nl80211: Survey data missing
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1181): Sorted scan results
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1181): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1181): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1181): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-78
D/wpa_supplicant( 1181): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1181): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1181): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1181): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1181): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1181): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1181): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1181): wpa_supplicant_pick_network+
I/wpa_supplicant( 1181): Selecting BSS from priority group 1
I/wpa_supplicant( 1181): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1181): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1181): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1181): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1181):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1181):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1181): Start print parameters
I/wpa_supplicant( 1181): wpa_s->wpa_state is 3
I/wpa_supplicant( 1181): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1181): isConcurrentMode() is 0
I/wpa_supplicant( 1181): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1181): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1181): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1181): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1181): wpa_s->reassociate is 1
I/wpa_supplicant( 1181): wpa_s->is_screen_on 1
I/wpa_supplicant( 1181): wpa_s->ifname wlan0
I/wpa_supplicant( 1181): End print parameters
I/wpa_supplicant( 1181): selected network = 1
D/wpa_supplicant( 1181): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb7ef64e8  current_ssid=0x0
D/wpa_supplicant( 1181): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1181): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1181): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1181): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1181): check if in concurrent case
I/wpa_supplicant( 1181): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  904): doString: LIST_DONGLES
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( ,1181): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1181): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1181): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1181): RSN: PMKSA cache search - network_ctx=0xb7ef64e8 try_opportunistic=0
D/wpa_supplicant( 1181): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1181): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1181): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1181): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1181): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1181): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1181): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1181): nl80211: Unsubscribe mgmt frames handle 0xb7ef5718 (mode change)
D/wpa_supplicant( 1181): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7ef5718
D/wpa_supplicant( 1181): nl80211: Register frame type=0xd0 nl_handle=0xb7ef5718
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1181): nl80211: Register frame type=0xd0 nl_handle=0xb7ef5718
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1181): nl80211: Register frame type=0xd0 nl_handle=0xb7ef5718
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1181): nl80211: Register frame type=0xd0 nl_handle=0xb7ef5718
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1181): nl80211: Register frame type=0xd0 nl_handle=0xb7ef5718
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1181): nl80211: Register frame type=0xd0 nl_handle=0xb7ef5718
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1181): nl80211: Register frame type=0xd0 nl_handle=0xb7ef5718
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1181): nl80211: Register frame type=0xd0 nl_handle=0xb7ef5718
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1181): nl80211: Register frame type=0xd0 nl_handle=0xb7ef5718
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1181): nl80211: Register frame type=0xd0 nl_handle=0xb7ef5718
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1181): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1181):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1181):   * freq=2412
D/wpa_supplicant( 1181):   * Auth Type 0
D/wpa_supplicant( 1181):   * WPA Versions 0x2
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1181): nl80211: Connect request send successfully
D/wpa_supplicant( 1181): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1181): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1181): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1181): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1181): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1181): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1181): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1181): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1181): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  904): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1181): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1181): reply (489) for get BSS: id=0
I/wpa_supplicant( 1181): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1181): freq=5220
I/wpa_supplicant( 1181): level=-47
I/wpa_supplicant( 1181): tsf=0000000105091104
I/wpa_supplicant( 1181): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=NG7005g
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=1
I/wpa_supplicant( 1181): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1181): freq=2412
I/wpa_supplicant( 1181): level=-54
I/wpa_supplicant( 1181): tsf=0000000105091120
I/wpa_supplicant( 1181): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1181): ssid=NG700
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=2
I/wpa_supplicant( 1181): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1181): freq=2412
I/wpa_supplicant( 1181): level=-78
I/wpa_supplicant( 1181): tsf=0000000105091124
I/wpa_supplicant( 1181): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1181): ssid=Gonzos
I/wpa_supplicant( 1181): ====
I/wpa_supplicant( 1181): id=3
I/wpa_supplicant( 1181): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1181): freq=2412
I/wpa_supplicant( 1181): level=-55
I/wpa_supplicant( 1181): tsf=0000000105091115
I/wpa_supplicant( 1181): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1181): ssid=01ABC
I/wpa_supplicant( 1181): ####
D/WirelessDisplayService(  904): getDiscoveryDongleList
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSID
W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiStateMachine(  904): == begin of scan result ==
D/WifiStateMachine(  904): == (4) end of scan result ==
D/WifiManager( 1219): getScanResults enter 
D/WirelessDisplayService(  904): getDiscoveryDongleList
D/WifiStateMachine(  904): == begin of scan result ==
D/WifiStateMachine(  904): == (4) end of scan result ==
D/WifiStateMachine(  904): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 105091104, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 105091120, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2412, timestamp: 105091124, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 105091115, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  904): add 4 to mScanResults
D/BatSI   (  904): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  904): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,W/dalvikvm( 4395): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4395): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
D/wpa_supplicant( 1181): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1181): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1181): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1181): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1181): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1181): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1181): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1181): nl80211: Event message available
D/wpa_supplicant( 1181): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1181): nl80211: Connect event
D/wpa_supplicant( 1181): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1181): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1181): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1181): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1181): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1181): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1181): Add randomness: count=10 entropy=4
I/wpa_supplicant( 1181): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1181): TDLS: Remove peers on association
D/wpa_supplicant( 1181): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1181): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1181): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1181): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1181): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1181): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1181): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1181): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1181): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1181): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1181): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1181): EAPOL: enable timer tick
D/wpa_supplicant( 1181): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1181): htc_wext_set_keepalive +
I/wpa_supplicant( 1181): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1181): getPrivFuncNum +	
I/wpa_supplicant( 1181): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1181): htc_wext_set_keepalive fnum = 0x8bf6
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1181): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1181): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1181): Get randomness: len=32 entropy=5
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  904): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  904): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  904): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  904): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  904): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  904): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  904): WifiMonitor:handleSupplicantSt,ateChange(): SSIDNG700
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  904): Enter handleAssociatedWithEvent
D/WifiStateMachine(  904): Associated
D/WifiStateMachine(  904): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  904): Exit handleAssociatedWithEvent
D/WifiStateMachine(  904): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  904): updateConnectedAP...
D/WifiApDatabaseHandler(  904): updateConnectedAP...
,D/WifiStateMachine(  904): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiApDatabaseHandler(  904): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  904): This record is existed, only update it...
D/Tethering(  904): interfaceLinkStateChanged wlan0, false
,D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  904): updateConnectedAP...
,D/Tethering(  904): interfaceStatusChanged wlan0, false,
,D/Tethering(  904): [isWifi] getHotspotEnabled: false
,D/Tethering(  904): interfaceLinkStateChanged wlan0, true
,D/Tethering(  904): interfaceStatusChanged wlan0, true
,D/Tethering(  904): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  904): updateConnectedAP...
,I/wpa_supplicant( 1181): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1181): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb7ef59f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1181):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1181): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1181): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1181): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f38b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1181):    broadcast key
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1181): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1181): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1181): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1181): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1181): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1181): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1181): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1181): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1181): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1181): set send_ind_to_ndc = 0
I/wpa_supplicant( 1181): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1181): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1181): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1181): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1181): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1181): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1181): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1181): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1181): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1181): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1181): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1181): EAPOL authentication completed successfully
I/wpa_supplicant( 1181): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1181): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1181): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1181): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  904): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  904): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  904): interfaceLinkStateChanged wlan0, true
D/Tethering(  904): interfaceStatusChanged wlan0, true
D/HTCRequest(  904): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  904): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/WifiStateMachine(  904): fetchFrequency(), freq = 2412
D/WifiStateMachine(  904): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/Tetherin,g(  904): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  904): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  904): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  904): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiApDatabaseHandler(  904): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  904): This record is existed, only update it...
,D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  904): updateConnectedAP...
,D/WISPrService( 3735): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3735): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  904): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  904): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  904): Provision feature enable=false
D/ConnectivityService(  904): mActiveDefaultNetwork: -1
,D/WifiStateMachine(  904): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  904): updateConnectedAP...
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024217
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024669
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024957
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024979
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024997
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025019
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026480
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026494
,D/DhcpStateMachine(  904): [StoppedState] Start DHCP
D/WifiStateMachine(  904): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029170
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=50 [2][1][0]
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1181): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
,D/WifiNative-wlan0(  904): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1181): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  904):    returned true
D/WifiNative-wlan0(  904): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1181): Power_Mode_Type mode = 1
I/wpa_supplicant( 1181): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  904):    returned true
,D/WifiNative-wlan0(  904): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  904):    returned null
E/WifiStateMachine(  904): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  904): doString: DRIVER WLS_BATCHING STOP
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  904):    returned null
D/WifiStateMachine(  904): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  904): acquireWL(433ae710): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 904 1000 null
D/WifiStateMachine(  904): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  904): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4265b750 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4265b750 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:1
,E/FbInjectorInitializer( 4395): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/SurfaceControl(  904): Excessive delay in blankDisplay() while turning screen off: 333ms
D/NfcService( 1253): ScreenObserver: OFF
D/NfcService( 1253): applyRouting - 0
,V/KeyguardServiceDelegate(  904): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@434c6a58)
D/PMS     (  904): nativeSetInteractive:false
D/PMS     (  904): nativeSetInteractive:false done
D/PMS     (  904): nativeSetAutoSuspend:true
D/PMS     (  904): nativeSetAutoSuspend:true done
D/HABCtrl (  904): TPE algorithm. remove timeout.
D/PMS     (  904): OOBE c monitor 11
I/InputManager(  904): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  904): screenObserver, isScreenOn=false
I/InputMethodManagerService(  904): Disable input method client, pid=4342
,D/PMN     (  904): wakingUp
I/IntentController( 1115): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
V/KeyguardServiceDelegate(  904): **** SHOWN CALLED ****
,D/NfcService( 1253): applyRouting -2
D/WirelessDisplayService(  904): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  904): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  904): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  904): onReceive: action=android.intent.action.SCREEN_ON
I/WindowManager(  904): No lock screen! windowToken=null
D/PMS     (  904): acquireWL(435db628): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1253 1027 null
D/PMN     (  904): onScreenOn
D/PMS     (  904): releaseWL(435db628): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/AlarmManager(  904): ACTION_SCREEN_ON
I/AlarmManager(  904): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  904): [AlarmQueuing] done recovering
I/AlarmManager(  904): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  904): [AlarmQueuing] done EPS screen off alarm recovering
D/MtpService( 2368): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2368): [MTP][onReceive]-
,D/NfcService( 1253): applyRouting - 0
,D/NfcService( 1253): applyRouting -2
D/PMS     (  904): acquireWL(42703c40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
D/PMS     (  904): releaseWL(42703c40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): acquireWL(439b8f60): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1253 1027 null
D/PMS     (  904): releaseWL(439b8f60): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
V/NotificationService(  904): batLight: Full, plugged
D/WirelessDisplayService(  904): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  904): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  904): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
D/WifiNative-wlan0(  904): doBoolean: SET_SCREEN_ON 1
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1181): SET_SCREEN_ON:On
I/wpa_supplicant( 1181): htc_wext_set_keepalive +
I/wpa_supplicant( 1181): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1181): getPrivFuncNum +	
I/wpa_supplicant( 1181): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1181): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1181): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1181): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1181): htc_wext_set_TX_TRACKING - ret = 0
,D/WifiNative-wlan0(  904):    returned true
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1181): WiFioffload: SignalStrength: =97
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
,D/WifiNative-wlan0(  904):    returned true
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c800
D/qdlights(  904): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
V/NotificationService(  904): batLight: Full, plugged
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c800
D/qdlights(  904): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,V/SRS_Proc(  372): ParamSet string: screen_state=on
,D/WirelessDisplayService(  904): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/NetworkPolicy(  904): updateScreenOn: false
,I/ClockThread( 1115): stop update clock
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(439f1a60): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(439f1a60): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  904): acquireWL(43875a68): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  904): releaseWL(43875a68): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1776): onScreenOn: false
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1776): onScreenOn: 1452019252506
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1776): onScreenOn: 1452019252507
,W/fb4a(:<default>):StaticBindingVerifier( 4395): Verify
I/SensorManager(  904): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420082d8
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  904): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 2
W/SensorService(  904): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420082d8, eanble = 0, strlen(mName) = 91
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  904): Listener[0] = com.htc.smartdim.sensor_eye@427c2490
,W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  904): goingToSleep
D/PMS     (  904): acquireWL(437f5068): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 904 1000 null
,D/AlarmManager(  904): ACTION_SCREEN_OFF
I/AlarmManager(  904): [AlarmQueuing] screen off now: 
I/AlarmManager(  904): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  904): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  904): stopDataStallAlarm: current tag=21007 mDataStallAlarmIntent=null
D/WifiNative-wlan0(  904): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1181): SET_SCREEN_ON:Off
I/wpa_supplicant( 1181): htc_wext_set_keepalive +
I/wpa_supplicant( 1181): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1181): getPrivFuncNum +	
I/wpa_supplicant( 1181): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1181): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1181): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 1181): get_ip_address source addr = 02000000
I/wpa_supplicant( 1181): htc_wext_set_keepalive gateway addr = 00000000
,I/wpa_supplicant( 1181): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  904):    returned true
,V/SRS_Proc(  372): ParamSet string: screen_state=off
I/AlarmManager(  904): [AlarmQueuing] wifi connection: true
D/PMS     (  904): acquireWL(431bac78): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 904 1000 null
D/PMS     (  904): releaseWL(431bac78): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/NetworkPolicy(  904): updateScreenOn: false
,D/ContactMessageStore( 1240): start background delete task...
D/ContactMessageStore( 1240): size: 0 , 0
,D/ContactMessageStore( 1240): Background delete complete
,D/AutoSetting( 1316): service - mHandler: cancel location update
,D/AutoSetting( 1316): service -           changes count: 0
,D/PMS     (  904): acquireWL(441d9508): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(441d9508): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] getTotalRam: 1873 Mb
D/PMS     (  904): acquireWL(42cc3700): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  904): releaseWL(42cc3700): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1776): onScreenOff.
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1776): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1776): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1776): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1776): onScreenOff
,D/WifiService(  904): New client listening to asynchronous messages
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4395/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4395): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4395): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4395): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  904): killProcessQuiet, pid=4127
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  904): Killing 4127:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 4127
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1316): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/WifiService(  904): Client connection lost with reason: 4
,I/ActivityManager(  904): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4433 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.sense.hsp (1316/10055)
,D/AutoSetting( 1316): Util - no network available!
,D/AutoSetting( 1316): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.sense.hsp (1316/10055)
D/AutoSetting( 1316): service - mHandler: cancel location update
D/AutoSetting( 1316): service -           changes count: 0
D/libc    (  904): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent DefaultState
,W/fb4a(:<default>):UserScope( 4395): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 4395): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/MobileConnectivityChangeReceiver( 4433): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4433): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4433): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4433): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,W/fb4a(:<default>):UserScope( 4395): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,I/ActivityManager(  904): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4462 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  904): killProcessQuiet, pid=3771
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  904): Killing 3771:com.htc.mediamanager/u0a34 (adj 15): empty #17
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.setupwizard (4433/10079)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.setupwizard (4433/10079)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.setupwizard (4433/10079)
,I/ActivityManager(  904): Recipient 3771
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/libc    (  904): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
,D/libc    (  904): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
,D/libc    (  904): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
D/libc    (  904): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  904): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1181): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  904):    returned true
,D/WifiNative-wlan0(  904): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1181): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1181): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  904):    returned true
,D/WifiNative-wlan0(  904): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1181): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  904):    returned true
,D/WifiStateMachine(  904): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/Process (  904): killProcessQuiet, pid=4038
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/WifiP2pService(  904): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  904): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/ActivityManager(  904): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4481 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
D/PMS     (  904): releaseWL(433ae710): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,I/ActivityManager(  904): Killing 4038:com.google.android.talk/u0a111 (adj 15): empty #17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative RSSI = -53 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  904): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  904): doBoolean: SignalStrength 97
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1181): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  904):    returned true
D/WifiStateMachine(  904): gateway: /192.168.1.1
,D/WifiNative-wlan0(  904): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1181): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1181): htc_wext_set_keepalive +
I/wpa_supplicant( 1181): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1181): getPrivFuncNum +	
I/wpa_supplicant( 1181): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1181): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1181): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1181): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1181): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  904):    returned true
D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  904): VerifyingLinkState enter
D/WifiStateMachine(  904): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  904): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  904): VerifyingLinkState: enableIpv6
D/WIFI_ICON( 1115): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,D/WifiStateMachine(  904): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -53, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  904): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  904): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiWatchdogStateMachine(  904): WAN detection
,I/dalvikvm-heap( 4395): Grow heap (frag case) to 9.954MB for 84664-byte allocation
,I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Recipient 4038
D/WifiStateTracker(  904): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  904): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  904): Provision feature enable=false
D/ConnectivityService(  904): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/NetworkPolicy(  904): mWifiStateReceiver: meteredHint=false,EPS mode=false
V/ConnectivityService(  904): Policy requires mobile/UNKNOWN teardown quickly
E/dalvikvm( 4395): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4395): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4395): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4395): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4395): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4395): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,E/dalvikvm( 4395): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
D/MDST    (  904): default: teardown()
D/MDST    (  904): default: setTeardownRequested(true)
D/MDST    (  904): default: setEnableApn apnType =default , enable=false
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
W/dalvikvm( 4395): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4395): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4395): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4395): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4395): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4395): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4395): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4395): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4395): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4395): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4395): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
D/MDST    (  904): default: setTeardownRequested(true)
D/ConnectivityService(  904): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
,W/ActivityManager(  904): Activity pause timeout for ActivityRecord{41d13f10 u0 com.test.thalitest/.MainActivity t2}
D/WISPrService( 3735): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [1][0][0]
,I/QuickSettingWifi( 1115): receive.wifiConnect:true wifiAPname:NG700 elapse:1
I/dalvikvm-heap( 4395): Grow heap (frag case) to 10.036MB for 39954-byte allocation
,I/dalvikvm-heap( 4395): Grow heap (frag case) to 10.112MB for 79892-byte allocation
,D/WifiStateMachine(  904): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  904): syncGetConfiguredNetworks
D/libc    (  904): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
E/ConnectivityService(  904): Unexpected mtu value: android.net.wifi.WifiStateTracker@424f8708
D/ConnectivityService(  904): handleConnectivityChange: netType=1 doReset=false resetMask=0
,W/GAV2    ( 4481): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,W/ContextImpl( 4481): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
D/ConnectivityService(  904): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
W/Vold    (  350): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  904): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/ConnectivityService(  904): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  904): handleConnectivityChange: resetting
D/Nat464Xlat(  904): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  904): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
,W/Vold    (  350): Returning OperationFailed - no handler for errno 30
D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
,W/ContextImpl( 4481): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
D/ConnectivityService(  904): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  904): sendGeneralBroadcastDelayed, restrictEnable=false
D/PMS     (  904): acquireWL(4414e508): PARTIAL_WAKE_LOCK  NetworkStats 0x1 904 1000 null
D/ConnectivityService(  904): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  904): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by  (904/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.setupwizard (4433/10079)
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4481): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/WirelessDisplayService(  904): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,W/Vold    (  350): Returning OperationFailed - no handler for errno 30
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/WirelessDisplayService(  904):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  350): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4481): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
D/PMS     (  904): releaseWL(4414e508): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  904): acquireWL(43c25600): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(43c25538): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(43c25600): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I/CheckinService( 2176): Checkin interval check for package: unspecified last checkin: 1452019203228 min interval config: 0 actual interval: 49980
I//system/bin/ip(  364): RTNETLINK answers: No such process
I/logwrapper(  364): /system/bin/ip terminated by exit(2)
I/dalvikvm-heap( 4395): Grow heap (frag case) to 10.276MB for 75760-byte allocation
I/CheckinService( 2176): Checking schedule, now: 1452019253214 next: 1452019233203
,I/CheckinService( 2176): active receiver: enabled
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2176, uid=10029, userID:0
,D/ConnectivityService(  904): mActiveDefaultNetwork: WIFI
,I/CheckinService( 2176): Preparing to send checkin request
,I/EventLogService( 2176): Accumulating logs since 1452019199533
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4395/10027)
,W/BroadcastQueue(  904): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4248dd90 u0 ReceiverList{424903b0 4395 com.facebook.katana/10027/u0 remote:438158d8}}
,W/BroadcastQueue(  904): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4248dd90 u0 ReceiverList{424903b0 4395 com.facebook.katana/10027/u0 remote:438158d8}}
,W/BroadcastQueue(  904): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42465bd0 u0 ReceiverList{42470148 4395 com.facebook.katana/10027/u0 remote:4377d770}}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.magazines (4481/10151)
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024217
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024669
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024957
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024979
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024997
,I/CheckinRequestBuilder( 2176): Checkin reason type: 8 attempt count: 1
,V/WebViewChromiumFactoryProvider( 4481): Binding Chromium to main looper Looper (main, tid 1) {41b6a558}
,I/LibraryLoader( 4481): Expected native library version number "",actual native library version number ""
,I/chromium( 4481): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025019
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026480
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026494
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029170
I/ActivityManager(  904): Cannot resolve ContentProvider=com.google.android.wearable.settings
,E/ActivityThread( 2176): Failed to find provider info for com.google.android.wearable.settings
,I/BrowserStartupController( 4481): Initializing chromium process, renderers=0
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/wpa_supplicant( 1181): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1181): EAPOL: disable timer tick
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4395/10027)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4395/10027)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4395/10027)
D/PMS     (  904): acquireWL(42474908): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,E/AudioManagerAndroid( 4481): BLUETOOTH permission is missing!
D/PMS     (  904): acquireWL(42414c30): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  904): releaseWL(42474908): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4481): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4481): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4481): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4481): Local Branch: 
I/Adreno-EGL( 4481): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4481): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4481):                  aa63bbd948f41d15fc72f585e
,D/PMS     (  904): acquireWL(426cd4b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(426cd4b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/NSApplication( 4481): Starting up...
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.magazines (4481/10151)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.magazines (4481/10151)
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/Process (  904): killProcessQuiet, pid=4163
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.plus (3967/10160)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.plus (3967/10160)
I/ActivityManager(  904): Killing 4163:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 4163
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1358/10029)
,D/ConnectivityService(  904): getNetworkInfo networkType=9 called by com.google.android.gms (2176/10029)
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1358/10029)
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4395): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  350): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  904): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4536 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
V/GLSActivity( 1358): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,V/GLSActivity( 1358): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ContextImpl( 4395): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  350): Returning OperationFailed - no handler for errno 30
,W/Vold    (  350): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4395): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,W/ContextImpl( 4536): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  904): acquireWL(4241fa30): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4536 1000 null
,I/ActivityManager(  904): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4552 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/SmartSyncUtils( 4536): isEpsOn(), nState = 0
D/PMS     (  904): releaseWL(4241fa30): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4536): getMobilePolicyEnabled, result = true
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  904): killProcessQuiet, pid=4194
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  904): Killing 4194:com.google.android.apps.docs/u0a100 (adj 15): empty #17
W/dalvikvm( 4552): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
D/AutoSetting( 1316): receiver - intent: android.intent.action.USER_PRESENT
W/dalvikvm( 4552): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
D/AutoSetting( 1316): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
I/MultiDex( 4552): VM with version 1.6.0 does not have multidex support
I/MultiDex( 4552): install
,I/MultiDex( 4552): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
I/ActivityManager(  904): Recipient 4194
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/TetherSettings( 3735): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3735): Cust_ConnectToPC   : Internet_Sharing>true
I/MultiDex( 4552): loading existing secondary dex files
D/        ( 3735): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3735): Cust_ConnectToPC   : spcsc>false
D/        ( 3735): Cust_ConnectToPC   : IPT>true
D/        ( 3735): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3735): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3735): hasRemovableStorageSlot: true
I/MultiDex( 4552): load found 3 secondary dex files
D/SmartNS_Utility( 3735): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3735): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
I/MultiDex( 4552): install done
,I/PSReceiver( 3735): onReceive:android.intent.action.USER_PRESENT
,W/ContextImpl( 3735): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 3735): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3735): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3735):  defaultType:0
,W/dalvikvm( 4552): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4552): VFY: unable to resolve instance field 36
,W/dalvikvm( 4552): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4552): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ContextImpl( 4536): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4536): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4536): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4536): isEpsOn(), nState = 0
D/WifiService(  904): New client listening to asynchronous messages
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@427c2490
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  904): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 1
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@427c2490, eanble = 0, strlen(mName) = 36
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  904): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  904): pid=904, uid=1000
,W/SensorService(  904): Active sensors: size = 0
W/SensorService(  904): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@427c2490, eanble = 0, strlen(mName) = 36
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@427c2490
W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
E/ActivityThread(  904): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@427c29d8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  904): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@427c29d8 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,I/ProviderInstaller( 4552): Installed default security provider GmsCore_OpenSSL
,W/dalvikvm( 4552): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4552): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/WearableService( 1219): callingUid 10029, callindPid: 1219
,W/dalvikvm( 4552): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4552): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4552): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4552): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4552): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/LocationInitializer( 2176): Restart initialization of location
,E/MDM     ( 1219): [114] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1358): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1358): Proximity feature is not enabled.
,V/GLSActivity( 1358): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1219): No location to return for getLastLocation()
,W/FusedLocationProvider( 1219): location=null
D/PMS     (  904): acquireWL(441efe20): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  904): releaseWL(441efe20): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024217
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024669
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024957
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024979
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024997
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025019
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026480
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026494
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029170
,I/WVCdm   (  372): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  372): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  372): CdmEngine::OpenSession
,I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
,D/NativeLibraryUtils( 4552): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  372): PrepareKeyRequest: nonce=2629814818
,I/WVCdm   (  372): CdmEngine::CloseSession
,D/PMS     (  904): releaseWL(441aacf8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  904): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  904): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  904): [AlarmQueuing] connectivity wifi: true
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/GpsLocationProvider(  904): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  904): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  904): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  904): ignore wifi update if we are not in OPENING or CLOSING
,D/CaptivePortalTracker(  904): NoActiveNetworkState
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by  (904/1000)
D/PMS     (  904): acquireWL(430fcf50): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 904 1000 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/PMS     (  904): releaseWL(430fcf50): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by com.htc.launcher (1266/10076)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,I/ConnectivityHelper( 1266): [onReceive] WIFI(1): CONNECTED
,V/Tethering(  904): bSetPropertyMultiRAB:false
,D/Tethering(  904): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,I/NetworkMonitor( 3789): type=WIFI subType= reason=null isConnected=true
I/Tethering(  904): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
,I/Tethering(  904): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  904): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
D/AccTypeManager( 1342): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Tethering(  904): ipv4Default 0.0.0.0/0 -> 192.168.1.1
,I/Tethering(  904): Found interface wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/Tethering(  904): TetherMasterSM: InitialState processMessage what=3
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by com.google.android.music (3789/10154)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.setupwizard (4433/10079)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.musicenhancer (3812/10053)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.backuptransport (1575/10029)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
,D/PMS     (  904): acquireWL(43d7db00): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  904): DelayedCaptiveCheckState
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024217
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024669
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024957
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024979
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024997
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025019
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026480
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026494
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029170
D/PMS     (  904): releaseWL(43d7db00): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4395/10027)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.backuptransport (1575/10029)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (904/1000)
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024217
D/PMS     (  904): acquireWL(4417a680): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 904 1000 null
D/htcCheckinService(  904): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  904): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024669
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024957
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024979
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024997
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025019
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026480
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026494
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029170
D/PMS     (  904): releaseWL(4417a680): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4395/10027)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4395/10027)
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
W/AccTypeManager( 1342): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1342): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  904): getActiveNetworkInfo called by  (2368/10021)
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/ExternalAccountType( 1342): Unsupported attribute readOnly
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/AutoSetting( 1316): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/MobileConnectivityChangeReceiver( 4433): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4433): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.sense.hsp (1316/10055)
,D/AutoSetting( 1316): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1316): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 1316): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1316): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.sense.hsp (1316/10055)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.magazines (4481/10151)
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.plus (3967/10160)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.plus (3967/10160)
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,I/CheckinService( 2176): Checkin interval check for package: unspecified last checkin: 1452019203228 min interval config: 0 actual interval: 51077
D/PMS     (  904): acquireWL(427447b0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(427447b0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I/dalvikvm-heap( 3967): Grow heap (frag case) to 13.501MB for 1821008-byte allocation
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2176, uid=10029, userID:0
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1358/10029)
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1358/10029)
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,I/WVCdm   (  372): CdmEngine::OpenSession
,I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  372): PrepareKeyRequest: nonce=2436343806
,I/WVCdm   (  372): CdmEngine::CloseSession
,W/Settings( 4552): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4552): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4552): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4552): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4552): Local Branch: 
I/Adreno-EGL( 4552): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4552): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4552):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4552): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4552): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4552): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4552): Local Branch: 
I/Adreno-EGL( 4552): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4552): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4552):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (4552/10029)
,I/Adreno-EGL( 4552): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4552): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4552): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4552): Local Branch: 
I/Adreno-EGL( 4552): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4552): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4552):                  aa63bbd948f41d15fc72f585e
,I/CheckinRequestBuilder( 2176): Classify the device as Phone.
,D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2176): [NET] getaddrinfo-,err=8
D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2176): [NET] getaddrinfo-, 1
,D/libc    ( 2176): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =3457 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE,
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 269,
D/libc    (  364): [NET]res_nsend:resplen=84
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2,
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 2176): [NET] getaddrinfo_proxy-, success,
,D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2176): [NET] getaddrinfo-,err=8
,D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2176): [NET] getaddrinfo-,err=8
,D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2176): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2176): Sending checkin request (12087 bytes)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4395/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4395/10027)
,W/fb4a(:<default>):UserScope( 4395): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4395): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4395/10027)
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=6 [16][1][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4395/10027)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4395): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4395/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4395/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4395/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4395/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4395/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4395/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4395/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4395/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4395/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4395/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4395/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4395/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4395/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4395/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4395/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4395/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4395/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4395/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4395/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4395/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4395/10027)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.facebook.katana (4395/10027)
,D/libc    (  904): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-,err=8
D/libc    (  904): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  904): [NET] getaddrinfo-, 1
,D/libc    (  904): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =45e1 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,I/CheckinRequestBuilder( 2176): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  904): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2176): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  904): getNetworkInfo networkType=9 called by com.google.android.gms (2176/10029)
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [4][0][0]
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  904): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  904): Find DNS Address www.htc.com/104.85.244.81
,I/CheckinRequestBuilder( 2176): Classify the device as Phone.
,I/CheckinTask( 2176): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 2176): Checking schedule, now: 1452019256159 next: 1452542193155
,I/CheckinService( 2176): active receiver: disabled
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2176, uid=10029, userID:0
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024217
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024669
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024957
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024979
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024997
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025019
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026480
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026494
,I/CheckinService( 2176): Checking schedule, now: 1452019256184 next: 1452542193155
,I/CheckinService( 2176): active receiver: disabled
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029170
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2176, uid=10029, userID:0
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024217
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024669
,D/CheckinService( 2176): Recording last checkin time for package unspecified as 1452019256188
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024957
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024979
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024997
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025019
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026480
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026494
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029170
,D/PMS     (  904): releaseWL(43c25538): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,D/PMS     (  904): acquireWL(437ca478): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1358/10029)
D/GCM     ( 1358): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    ( 1358): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1358): [NET] getaddrinfo-,err=8
D/libc    ( 1358): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1358): [NET] getaddrinfo-, 1
D/libc    ( 1358): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =bfe +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 285
D/libc    (  364): [NET]res_nsend:resplen=79
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1358): [NET] getaddrinfo_proxy-, success
,D/PMS     (  904): releaseWL(42414c30): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/libc    ( 1358): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1358): [NET] getaddrinfo-,err=8
,D/libc    ( 1358): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1358): [NET] getaddrinfo-,err=8
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1358/10029)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1358/10029)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1358/10029)
D/ConnectivityService(  904): getActiveNetworkInfo called by  (1358/10029)
,D/PMS     (  904): acquireWL(42ccca98): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1358/10029)
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1358/10029)
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1358/10029)
,D/PMS     (  904): releaseWL(437ca478): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1358/10029)
,D/ConnectivityService(  904): reportInetCondition for net 1, percentage: 100 by  (1358/10029)
,D/ConnectivityService(  904): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  904): handleInetConditionChange: starting a change hold
,D/PMS     (  904): releaseWL(42ccca98): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(42651f68): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1358/10029)
,D/ConnectivityService(  904): reportInetCondition for net 1, percentage: 100 by  (1358/10029)
,D/ConnectivityService(  904): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  904): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1358/10029)
,D/ConnectivityService(  904): reportInetCondition for net 1, percentage: 100 by  (1358/10029)
,D/ConnectivityService(  904): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  904): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1358/10029)
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024217
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024669
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024957
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024979
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024997
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025019
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026480
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026494
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029170
,D/PMS     (  904): releaseWL(42651f68): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  904): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  904): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=18 [11][2][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  904): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  904): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  904): [MLHD] enter handleMediaLinkEvent DefaultState
,W/ActivityManager(  904): Sleep timeout!  Sleeping now.
,D/PMS     (  904): releaseWL(437f5068): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,I/GAV2    ( 4481): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 4342): Test app app.js loaded
I/jxcore-log( 4342): 
,I/Choreographer( 4342): Skipped 504 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4342): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
W/ResourceType( 4342): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4342): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41b80028 VFEDH.C. .F....ID 0,0-720,1134 #64}
,D/AutoSetting( 1509): service - handleMessage() stop self
,D/AutoSetting( 1509): service - onDestroy() END
,D/AutoSetting( 1509): service - handleMessage() quit looper
,D/Process (  904): killProcessQuiet, pid=4217
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4217:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 4217
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  904): killProcessQuiet, pid=4235
,I/ActivityManager(  904): Killing 4235:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/PMS     (  904): acquireWL(42745050): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,I/ActivityManager(  904): Recipient 4235
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/AlarmManager(  904): sending alarm PendingIntent{42002168: PendingIntentRecord{420622d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=112923, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42745050): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
,I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1342): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  904): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4609 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "sms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/Prism.ItemManager( 1266): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1266): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1266): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "smsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/Launcher( 1266): Deferring update until onResume
,D/Launcher( 1266): waitUntilResume // bindAppsUpdated
,W/SystemReader( 1253): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "mms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "mmsto"
,I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
W/AccTypeManager( 1342): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1342): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "sms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "smsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "mms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mmsto"
,E/ExternalAccountType( 1342): Unsupported attribute readOnly
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,D/PhoneApp( 1240): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,D/AutoSetting( 1316): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1316): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1316): service - requestNLP() NetworkLocationProvider not enabled
,I/Babel   ( 4609): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4609): MmsConfig.loadMmsSettings
,W/dalvikvm( 4609): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4609): VFY: unable to resolve instance field 36
,W/dalvikvm( 4609): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4609): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  904): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4633 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4609, uid=10111, userID:0
,D/MessageFrequencyProvider( 4633): onCreate
,W/Settings( 4609): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ProviderInstaller( 4609): Installed default security provider GmsCore_OpenSSL
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4609, uid=10111, userID:0
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4609, uid=10111, userID:0
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4609, uid=10111, userID:0
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4609, uid=10111, userID:0
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4609, uid=10111, userID:0
,D/CaptivePortalTracker(  904): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  904): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  904): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,V/GetPrviateResource( 4633): GetPrviateResource
,V/GetPrviateResource( 4633): GetPrviateResource
,D/MmsCustomizationProvider( 4633): query uri: content://htc-mms-customization/mms-ua/ua_string
D/PMS     (  904): acquireWL(44224b78): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4609 10111 null
,D/MmsCustomizationProvider( 4633): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/[PluginManager]RegisterService( 1316): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1316): handle notify Blinkfeed plugin client changed
,I/Babel   ( 4609): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4609): MmsConfig.loadFromDatabase
,I/IcingCorporaProvider( 2789): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,E/Babel   ( 4609): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4609): MmsConfig.loadFromResources
,E/Babel   ( 4609): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4609): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/ActivityManager(  904): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
D/PMS     (  904): acquireWL(441ca0d8): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  904): acquireWL(441c0b18): PARTIAL_WAKE_LOCK  AsyncService 0x1 3967 10160 null
,D/MessageCustFlag( 4633): sense_version=6.0
,D/BTAccessoryUtil( 4633): createReceiver
D/PMS     (  904): releaseWL(44224b78): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/dalvikvm-heap( 3967): Grow heap (frag case) to 15.200MB for 1821008-byte allocation
,D/BTAccessoryUtil( 4633): registerReceiver return intent = null
D/MessageCustFlag( 4633): sku_id=99
,W/SystemReader( 4633): Cannot find message_ambs_application_id, use default value instead
D/PMS     (  904): releaseWL(441c0b18): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/Messaging( 4633): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4633): networkCode: 
,D/MessageCustFlag( 4633): sku_id=99
D/MmsConfig( 4633): SIE smsPri: null
,D/MmsConfig( 4633): networkCode: 
I/ActivityManager(  904): Resuming delayed broadcast
,D/HtcTelephonyCapability( 4633): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4633): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 4633): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4633): Cannot find qct_8960_interface, use default value instead
,I/dalvikvm-heap( 3967): Grow heap (frag case) to 16.937MB for 1821008-byte allocation
,D/Process (  904): killProcessQuiet, pid=4181
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  904): Killing 4181:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 4181
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/PackageBroadcastService( 2176): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 2176): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  904): Resuming delayed broadcast
,I/Icing   ( 2176): updateResources: need to parse f{com.google.android.gms}
,D/Process (  904): killProcessQuiet, pid=3812
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3812:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/Prism.ItemManager( 1266): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1266): loadItems() com.htc.launcher.pageview.WidgetManager@41c01df0 +
,I/Prism.WidgetManager( 1266): onLoadItems() +
,I/ActivityManager(  904): Recipient 3812
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/PackageManager(  904): Unable to load service info ResolveInfo{44109640 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,I/IcingCorporaProvider( 2789): UpdateCorporaTask done [took 727 ms] updated apps [took 726 ms] 
,E/Prism.WidgetManager( 1266): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1266): onLoadItems() -
,I/Prism.ItemManager( 1266): loadItems() com.htc.launcher.pageview.WidgetManager@41c01df0 -
,D/RemoteDisplayProvider(  904): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  904): start
,I/GCoreNlp( 1219): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  904): applying state to connected service
,D/PhoneApp( 1240): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1240): -- N1 =0
,D/PhoneApp( 1240): -- N2 =0
,D/PhoneApp( 1240): -- N3 =0
,D/LocationProviderProxy(  904): applying state to connected service
D/PMS     (  904): acquireWL(4261ddc8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  904): releaseWL(4261ddc8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  904): acquireWL(4242b540): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  904): releaseWL(4242b540): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(42687770): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(42687770): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 2176): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2176): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  904): releaseWL(441ca0d8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/Messaging( 4633): mNeedToUpdateDate2 start
,D/MmsConfig( 4633): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4633): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4633): 
D/MmsAsyncWorkHandler( 4633): HM tk = 20001
,D/ReportIndicatorCache( 4633): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4633): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41b797c0
,I/Messaging( 4633): mccmnc> 
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/MmsSmsV2Provider( 1240):  phoneType = -1
D/DraftCache( 4633): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4633): [DraftCache/1] refresh
D/MmsSmsV2Provider( 1240): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/MmsConfig( 4633): networkCode: 
,D/Messaging( 4633): ViewCache CreatePreloadOnlyConversationList
,D/PhoneStorageUtil( 4633): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4633): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4633): createReceiver
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/MessageCustFlag( 4633): sense_version=6.0
,D/AccFlag ( 1240): sku_id=99
,D/Jerry   ( 4633): start to preload cursor >>>>>>>
,D/TelephUtils( 1240): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
V/MmsProvider( 1240): Update uri=content://mms, match=0
,V/MmsProvider( 1240): selection=st=129 AND m_type!=134
,D/Messaging( 4633): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4633): TransactionService is going to be woken up.
,D/DraftCache( 4633): [DraftCache/457] rebuildCache
D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/MmsSmsV2Provider( 1240):  phoneType = -1
,D/MmsSmsV2Provider( 1240): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,V/TransactionService( 4633): 1-Creating TransactionService
,D/Messaging( 4633): mNeedToUpdateDate2: false
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/MmsSmsV2Provider( 1240):  phoneType = -1
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
V/TransactionService( 4633): onStartCommand: 1
,D/MmsSystemEventReceiver( 4633): unRegisterForConnectionStateChanges
V/TransactionService( 4633): 4-Handling incoming message: { when=-1ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 4633): Loading previous transactions.
D/MmsSmsV2Provider( 1240):  phoneType = -1
,D/MmsSmsV2Provider( 1240): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/Messaging( 4633): ViewCache CreatePreload
,D/Messaging( 4633): ViewCache CreatePreloadOnlyMultipleOpsList
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/Jerry   ( 1240): URI_DRAFT
,D/Cust_MMSMS( 4633): _has_set_default_values_2=true
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1240): device_type: 1
,D/TransactionService( 4633): Force set service start id to 1
V/TransactionService( 4633): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4633): unRegisterForConnectionStateChanges
D/MsgPreferenceUtils( 4633): def_index: 0
,D/TransactionService( 4633): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4633): Destroying TransactionService
,V/TransactionService( 4633): 4-Handling incoming message: { when=-4ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/MsgPreferenceUtils( 4633): globalIndex = 1
,D/DraftCache( 4633): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 4633): [DraftCache/457] rebuildCache time: 2
D/MmsAsyncWorkHandler( 4633): 
D/MmsAsyncWorkHandler( 4633): HM tk = 20002
D/MsgPreferenceUtils( 4633): phone state: true
D/MsgPreferenceUtils( 4633): sd state: false
,D/MsgPreferenceUtils( 4633): vIndex = 0
D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/MmsSmsV2Provider( 1240):  phoneType = -1
,D/MmsSmsV2Provider( 1240): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 4633): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1240): sku_id=99
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1240): sku_id=99
,I/GAV4    ( 4609): Thread[GAThread,5,main]: No campaign data found.
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  904): acquireWL(43a66940): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  904): releaseWL(43a66940): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  904): acquireWL(42fae0d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  904): sending alarm PendingIntent{4378b8d0: PendingIntentRecord{4261b5f8 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=124375, Int=0
,V/AlarmManager(  904): sending alarm PendingIntent{41c06c58: PendingIntentRecord{41b64c48 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=135552, Int=0
,D/PMS     (  904): acquireWL(42624278): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1358/10029)
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=18 [16][3][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/PMS     (  904): acquireWL(437e1368): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(437e1368): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(42624278): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1358/10029)
,D/PMS     (  904): acquireWL(42671980): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(42fae0d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024217
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024669
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024957
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024979
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024997
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025019
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026480
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026494
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029170
,D/PMS     (  904): releaseWL(42671980): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(43dc2c40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=100 [1][1][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1358/10029)
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024217
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024669
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024957
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024979
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024997
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025019
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026480
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026494
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029170
,D/PMS     (  904): acquireWL(43d213d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(42737070): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1219): Vacuum at: now=1452019282913 tag=VacuumService
,D/PMS     (  904): releaseWL(43dc2c40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(4278c390): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1358/10029)
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024217
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024669
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024957
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024979
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024997
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025019
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026480
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026494
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029170
,D/PMS     (  904): releaseWL(4278c390): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(42737070): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(4349cb48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(43d213d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024217
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024669
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024957
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024979
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024997
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025019
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026480
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026494
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029170
,D/PMS     (  904): releaseWL(4349cb48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(442bc778): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024217
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024669
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024957
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024979
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024997
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025019
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026480
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026494
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029170
,D/PMS     (  904): releaseWL(442bc778): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(438c3fb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1358/10029)
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024217
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024669
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024957
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024979
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024997
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025019
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026480
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026494
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029170
,D/PMS     (  904): releaseWL(438c3fb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1316): service - mHandler: update timezone
,D/AutoSetting( 1316): service - handleMessage() stop self
,D/AutoSetting( 1509): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1509): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1509): service - onCreate()
,D/AutoSetting( 1316): service - handleMessage() quit looper
,D/AutoSetting( 1316): service - onDestroy() END
D/AutoSetting( 1509): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1509): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
W/ActivityManager(  904): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  904): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/DotMatrix( 1558): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
D/AutoSetting( 1509): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1509): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1509): service - mHandler: update timezone
,D/DotMatrix( 1558): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
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
,D/DotMatrix( 1558): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1558): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1115): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41f1f170 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.htc.htclocationservice 1 7 3 11
,D/PMS     (  904): acquireWL(42671ad8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/HtcPowerSaver(  904): updateBatteryInfo
,D/PMS     (  904): releaseWL(42671ad8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/Process (  904): killProcessQuiet, pid=4266
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4266:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 4266
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/ContactMessageStore( 1240): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1240): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  904): Waited long enough for: ServiceRecord{438f7500 u0 com.htc.htclocationservice/.AutoSettingService}
,D/AutoSetting( 1509): service - handleMessage() stop self
,D/AutoSetting( 1509): service - onDestroy() END
,D/AutoSetting( 1509): service - handleMessage() quit looper
,D/Process (  904): killProcessQuiet, pid=4280
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4280:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 4280
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  904): acquireWL(437efbf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10027}
,V/AlarmManager(  904): sending alarm PendingIntent{442bfc18: PendingIntentRecord{438fd540 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=172827, Int=0
,D/PMS     (  904): releaseWL(437efbf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/PMS     (  904): acquireWL(439863d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42002168: PendingIntentRecord{420622d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=172923, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(439863d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/TelephonyReceiver( 1240): switchBindHtcMsgCursor: null
,D/PMS     (  904): acquireWL(427c5f58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  904): sending alarm PendingIntent{4414f040: PendingIntentRecord{4261b5f8 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=184404, Int=0
,D/PMS     (  904): acquireWL(4333ad38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(427c5f58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1358/10029)
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=17 [17][3][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/PMS     (  904): acquireWL(43d14d08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(4333ad38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(43d14d08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(426446e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024217
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024669
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024957
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024979
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024997
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025019
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026480
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026494
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029170
,D/PMS     (  904): releaseWL(426446e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(438069b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1358/10029)
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024217
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024669
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024957
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024979
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024997
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025019
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026480
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026494
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029170
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/PMS     (  904): acquireWL(441c9710): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(438069b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1219): Scheduling Phenotype for one-off execution 3726 seconds from now (1452019332134)
,D/GetConfigurationSnapshotOperation( 1219): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1219): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1219): VFY: unable to find class referenced in signature (Landroid/net/Network;),
,W/dalvikvm( 1219): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1219): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1219): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1219): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  904): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
,W/dalvikvm( 1219): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/libc    ( 1219): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1219): [NET] getaddrinfo-,err=8
D/libc    ( 1219): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1219): [NET] getaddrinfo-, 1
,D/libc    ( 1219): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =7094 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 203
D/libc    (  364): [NET]res_nsend:resplen=87
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1219): [NET] getaddrinfo_proxy-, success,
,D/libc    ( 1219): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1219): [NET] getaddrinfo-,err=8
D/libc    ( 1219): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1219): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  904): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=16 [12][2][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  904): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=50 [2][1][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  904): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/PMS     (  904): releaseWL(441c9710): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(43c81528): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024217
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024669
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024957
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024979
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024997
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025019
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026480
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026494
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029170
,D/PMS     (  904): releaseWL(43c81528): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(438bd490): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1358/10029)
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1181): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024217
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024669
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024957
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024979
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024997
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025019
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026480
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026494
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029170
,D/PMS     (  904): releaseWL(438bd490): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(42fe9080): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42fe9080): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(439a3000): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42002168: PendingIntentRecord{420622d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=232923, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(439a3000): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  904): acquireWL(426eea38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(426eea38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  904): acquireWL(437ca648): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(437ca648): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
,D/PowerUI ( 1115): closing low battery warning: level=100
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  904): acquireWL(4389be78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42002168: PendingIntentRecord{420622d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=292923, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4389be78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(43ca20c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43ca20c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  904): acquireWL(4397f650): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42002168: PendingIntentRecord{420622d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=352923, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4397f650): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 4342): TAP version 13
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # setup
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # multiplex can send data,
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # teardown
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): ok 1 String should be length:200
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # setup
I/jxcore-log( 4342): 
,D/PMS     (  904): acquireWL(43b6a2a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43b6a2a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 4342): # basic
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # teardown
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): ok 2 sane
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # setup
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # another
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # teardown
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): ok 3 sane
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # setup
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # teardown
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): ok 4 should be equal
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): ok 5 null
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): ok 6 (unnamed assert),
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): ok 7 should be equal,
I/jxcore-log( 4342): 
I/jxcore-log( 4342): ok 8 should not throw
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # setup,
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # teardown
I/jxcore-log( 4342): 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 4342): ok 9 (unnamed assert)
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): ok 10 (unnamed assert)
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): ok 11 should not throw
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): ok 12 should be equal
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): ok 13 should be equal
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # setup
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # teardown
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): ok 14 should be equal
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # setup
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # failed to get mobile documents path
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # teardown
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): ok 15 should be equal
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # setup
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 4342): 
,D/PMS     (  904): acquireWL(438bd8f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42002168: PendingIntentRecord{420622d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=412923, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(438bd8f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4342): # teardown
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): ok 16 should be equal
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): ok 17 should be equal
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): ok 18 should be equal
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # setup
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # #init should register the networkChanged event
I/jxcore-log( 4342): 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 4342): # teardown
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): ok 19 should be equal
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # setup
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # #startBroadcasting should throw on null device name
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # teardown
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): ok 20 should throw
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # setup
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 4342): 
,D/PMS     (  904): acquireWL(42b2dcc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42b2dcc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4342): # teardown
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): ok 21 should throw
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # setup
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # #startBroadcasting should throw on non-number port
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # teardown
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): ok 22 should throw
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # setup
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # #startBroadcasting should throw on NaN port
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # teardown
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): ok 23 should throw
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # setup
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # #startBroadcasting should throw on negative port
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # teardown
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): ok 24 should throw
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # setup
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # #startBroadcasting should throw on too large port
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # teardown
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): ok 25 should throw
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # setup
I/jxcore-log( 4342): 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 4342): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 4342): 
,D/PMS     (  904): acquireWL(427a1a80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42002168: PendingIntentRecord{420622d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=472923, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(427a1a80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4342): # teardown
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): ok 26 should be equal
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): ok 27 should be equal
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): ok 28 should be equal
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # setup
I/jxcore-log( 4342): 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 4342): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # teardown
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): ok 29 should be equal
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): ok 30 should be equal
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): ok 31 should be equal
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # setup
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # teardown
I/jxcore-log( 4342): 
,D/PMS     (  904): acquireWL(42c75d88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42c75d88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 4342): ok 32 should be equal
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): ok 33 should be equal
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # setup
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # teardown
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): ok 34 should be equal
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): ok 35 should be equal
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # setup
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # teardown
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): ok 36 should be equal
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): ok 37 should be equal
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): ok 38 should be equal
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # setup
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 4342): 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 4342): # teardown
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): ok 39 should be equal
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): ok 40 should be equal
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # setup
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # should call Mobile("Disconnect") without an error
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # teardown
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): ok 41 should be equal
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): ok 42 should be equal
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # setup
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 4342): 
,D/PMS     (  904): acquireWL(43c4b1a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42002168: PendingIntentRecord{420622d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=532923, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43c4b1a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 4342): # teardown
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): ok 43 should be equal
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): ok 44 should be equal
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # setup
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 4342): 
,I/jxcore-log( 4342): # teardown
I/jxcore-log( 4342): 
,W/dalvikvm( 4342): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4342): threadid=1: thread exiting with uncaught exception (group=0x4173ee30)
,E/AndroidRuntime( 4342): FATAL EXCEPTION: main
E/AndroidRuntime( 4342): Process: com.test.thalitest, PID: 4342
E/AndroidRuntime( 4342): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4342): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4342): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4342): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4342): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4342): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:93)
E/AndroidRuntime( 4342): 	at io.jxcore.node.JXcoreExtension$5.Receiver(JXcoreExtension.java:155)
E/AndroidRuntime( 4342): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4342): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4342): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4342): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4342): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4342): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4342): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4342): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4342): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4342): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4342): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4342): 	at dalvik.system.NativeStart.main(Native Method)
,E/ActivityManager(  904): App crashed! Process: com.test.thalitest
W/ActivityManager(  904):   Force finishing activity com.test.thalitest/.MainActivity
,I/ActivityManager(  904): Killing 3929:com.google.android.gm/u0a107 (adj 15): empty #17
D/Process (  904): killProcessQuiet, pid=3929
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
D/Process ( 4342): killProcess, pid=4342
D/Process ( 4342): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 ,
,I/ActivityManager(  904): Recipient 3929
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/InputDispatcher(  904): channel '426a1c28 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  904): channel '426a1c28 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  904): Attempted to unregister already unregistered input channel '426a1c28 com.test.thalitest.MainActivity (s)'
I/WindowManager(  904): WINDOW DIED Window{426a1c28 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Recipient 4342
I/ActivityManager(  904): Process com.test.thalitest (pid 4342) has died.
D/WifiService(  904): Client connection lost with reason: 4
,W/InputMethodManagerService(  904): Got RemoteException sending setActive(false) notification to pid 4342 uid 10389
W/Binder  ( 1206): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1206): java.lang.NullPointerException
W/Binder  ( 1206): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1206): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1206): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1206): 	at dalvik.system.NativeStart.run(Native Method)
,D/PMS     (  904): acquireWL(435f8af8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(435f8af8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(42633ea0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42002168: PendingIntentRecord{420622d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=592923, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42633ea0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43a72050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PMS     (  904): releaseWL(43a72050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/ContextImpl( 4536): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3735): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3735): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3735): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3735): Cust_ConnectToPC   : spcsc>false
D/        ( 3735): Cust_ConnectToPC   : IPT>true
,D/        ( 3735): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3735): project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3735): Index of the first 1 = 3
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
W/ContextImpl( 3735): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 3735): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3735): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3735): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3735): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,W/ContextImpl( 3735): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
D/SmartNS_Utility( 3735): [ACC]android_networking:tethering_guard_support=false
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory),
,D/PMS     (  904): acquireWL(43a220e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): releaseWL(43a220e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/ContactMessageStore( 1240): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1240): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1240): sku_id=99
,D/ContactMessageStore( 1240): start background delete task...
,D/ContactMessageStore( 1240): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1240): size: 0 , 0
,D/ContactMessageStore( 1240): Background delete complete
,D/PMS     (  904): acquireWL(441c91a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42002168: PendingIntentRecord{420622d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=652923, Int=0
I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(441c91a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(4266f460): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  904): releaseWL(4266f460): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(434b6640): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): releaseWL(434b6640): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43385620): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42002168: PendingIntentRecord{420622d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=712923, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43385620): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(426aa250): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/PMS     (  904): releaseWL(426aa250): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(44203d40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(44203d40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(4349a6b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42002168: PendingIntentRecord{420622d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=772923, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4349a6b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(441e5bb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(441e5bb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43346cd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43346cd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
,I/HtcPowerSaver(  904): >> updateStatus
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(4416cdd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42002168: PendingIntentRecord{420622d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=832923, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1266): Grow heap (frag case) to 12.643MB for 50416-byte allocation
,D/PMS     (  904): releaseWL(4416cdd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43815c88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43815c88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  904): onReceive BATTERY_CHANGED
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43d96e10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  904): releaseWL(43d96e10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(437eaef8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42002168: PendingIntentRecord{420622d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=892923, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(437eaef8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(4392e198): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4392e198): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43d41ea8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,D/PMS     (  904): releaseWL(43d41ea8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(437eb6e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42002168: PendingIntentRecord{420622d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=952923, Int=0
I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(437eb6e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43963f58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43963f58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43998ee8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43998ee8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/ConnectivityService(  904): Sampling interval elapsed, updating statistics ..
,D/PMS     (  904): acquireWL(433842f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41e0a2d0: PendingIntentRecord{42502ec0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=784556, Int=0
,D/ConnectivityService(  904): Done.
,D/ConnectivityService(  904): Setting timer for 720seconds
,I/ActivityManager(  904): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4750 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  904): sending alarm PendingIntent{4256ef00: PendingIntentRecord{424eef70 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452019358220, Int=10800000
,V/AlarmManager(  904): sending alarm PendingIntent{432cec20: PendingIntentRecord{425d11f8 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1452019733660, Int=1800000
,V/AlarmManager(  904): sending alarm PendingIntent{42423b78: PendingIntentRecord{42423b40 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452020078573, Int=900000
,V/AlarmManager(  904): sending alarm PendingIntent{42ffa890: PendingIntentRecord{42523e90 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1452020153660, Int=0
,D/PMS     (  904): acquireWL(44152f90): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(437b9a20): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(44152f90): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4536): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4536): call getInstance()
D/SmartSyncUtils( 4536): isEpsOn(), nState = 0
,I/EventLogService( 2176): Aggregate from 1452019253244 (log), 1452017933600 (data)
,D/PowerUsageList:PowerUsageHelper( 4536): MY_DEBUG = false
D/PMS     (  904): releaseWL(433842f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(4395fc50): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4536 1000 null
D/SmartSyncScreenOnOffTimeReceiver( 4536): [updateNmRange] bManual = false
D/SmartSyncScreenOnOffTimeReceiver( 4536): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 4536): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4536): SettingOnTime = 1452060000000, randomSettingOnTime = 1452056983000
D/SmartSyncScreenOnOffTimeReceiver( 4536): SettingOffTime = 1452045600000, randomSettingOffTime = 1452052271000
D/SmartSyncScreenOnOffTimeReceiver( 4536): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4536): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 4536): bNightModeTurnOffOnce = false
,D/PMS     (  904): releaseWL(4395fc50): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.aurora (4750/10049)
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024217
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024669
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024957
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024979
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024997
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025019
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026480
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026494
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029170
,D/PMS     (  904): releaseWL(437b9a20): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024217
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024669
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024957
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024979
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024997
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025019
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026480
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026494
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029170
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,D/Process (  904): killProcessQuiet, pid=4313
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4313:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 4313
,D/PMS     (  904): acquireWL(43714d40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  904): sending alarm PendingIntent{42601e00: PendingIntentRecord{4273aaa0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1009458, Int=0
,D/PMS     (  904): acquireWL(426a8e20): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(426a8e20): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): releaseWL(43714d40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  904): acquireWL(424ba0c0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1358/10029)
,D/ConnectivityService(  904): reportInetCondition for net 1, percentage: 100 by  (1358/10029)
D/ConnectivityService(  904): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  904): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  904): getActiveNetworkInfo called by  (1358/10029)
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024217
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024669
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024957
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024979
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360024997
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360025019
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026480
W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360026494
,W/AlarmManager(  904): Converted elapesd time is over 1 year! when = 315360029170
,D/PMS     (  904): releaseWL(424ba0c0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  904): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  904): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
,W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=10 [299][32][0]
,D/WifiNative-wlan0(  904): doString: SIGNAL_POLL
W/WifiHW  (  904): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1181): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1181): nl80211: survey data missing!
E/wpa_supplicant( 1181): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1181): environment dirty rate=0 [0][0][0]
,D/PMS     (  904): acquireWL(441a2938): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42002168: PendingIntentRecord{420622d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1012923, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(441a2938): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(4269fbe8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4269fbe8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(4265ea20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4265ea20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,D/PowerUI ( 1115): closing low battery warning: level=100
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43249418): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42002168: PendingIntentRecord{420622d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1072923, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1266): Grow heap (frag case) to 12.643MB for 50416-byte allocation
,D/PMS     (  904): releaseWL(43249418): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(4254cf18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PMS     (  904): releaseWL(4254cf18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43a26180): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): releaseWL(43a26180): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(4349cc28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42002168: PendingIntentRecord{420622d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1132923, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4349cc28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(442bef68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
I/BatteryService(  904): n_update end
D/UsbnetService(  904): onReceive BATTERY_CHANGED
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
D/PMS     (  904): releaseWL(442bef68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(4240a7e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(4240a7e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
,D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43c4c950): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42002168: PendingIntentRecord{420622d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1192923, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43c4c950): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000},
,D/PMS     (  904): acquireWL(43d36280): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(43d36280): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory),
,D/PMS     (  904): acquireWL(437f2128): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(437f2128): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(4322ec98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42002168: PendingIntentRecord{420622d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1252923, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4322ec98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(43227be8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43227be8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(42507c30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42507c30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42602910): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42002168: PendingIntentRecord{420622d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1312923, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(42602910): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(438d76d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(438d76d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43d7d858): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43d7d858): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43986390): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42002168: PendingIntentRecord{420622d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1372923, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43986390): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(426ba6c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(426ba6c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
D/UsbnetService(  904): BroadcastReceiver::onReceive+
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43d5af80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(43d5af80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(4363abe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  904): sending alarm PendingIntent{42002168: PendingIntentRecord{420622d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1432923, Int=0
,D/PMS     (  904): releaseWL(4363abe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(441b3ce8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
D/PMS     (  904): releaseWL(441b3ce8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(4262ea58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): releaseWL(4262ea58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(4322bcf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42002168: PendingIntentRecord{420622d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1492923, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1266): Grow heap (frag case) to 12.691MB for 50416-byte allocation
D/PMS     (  904): releaseWL(4322bcf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(44175640): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(44175640): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  904): acquireWL(42cc1a78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42cc1a78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
,I/HtcPowerSaver(  904): >> updateStatus
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(425829e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42002168: PendingIntentRecord{420622d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1552923, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(425829e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(4383cb00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(4383cb00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42cd2490): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/PMS     (  904): releaseWL(42cd2490): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43d150e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42002168: PendingIntentRecord{420622d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1612923, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43d150e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(4381a2f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
I/BatteryService(  904): n_update end
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1115): closing low battery warning: level=100
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(4381a2f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
,I/HtcPowerSaver(  904): >> updateStatus
D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(438b90b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(438b90b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  904): updateBatteryInfo
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(43926570): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42002168: PendingIntentRecord{420622d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1672923, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43926570): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(426f5630): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false),
D/PMS     (  904): releaseWL(426f5630): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  904): acquireWL(441cabd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(441cabd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(439b0640): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42002168: PendingIntentRecord{420622d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1732923, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(439b0640): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(42797098): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
I/BatteryService(  904): n_update end
D/PowerUI ( 1115): closing low battery warning: level=100
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(42797098): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(425e7458): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PMS     (  904): releaseWL(425e7458): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(438e6e90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42002168: PendingIntentRecord{420622d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1792923, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(438e6e90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,D/PMS     (  904): acquireWL(439e3dd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(439e3dd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  904): acquireWL(423b58e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  904): releaseWL(423b58e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  904): updateBatteryInfo
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  904): << updateStatus
,I/ProcessStatsService(  904): Prepared write state in 27ms
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
I/ProcessStatsService(  904): Pruning old procstats: /data/system/procstats/state-2016-01-05-08-54-00.bin
,D/PMS     (  904): acquireWL(43ca4df0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{42002168: PendingIntentRecord{420622d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1852923, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(43ca4df0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  904): acquireWL(439231b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
I/BatteryService(  904): n_update end
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(439231b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  904): acquireWL(42fd8fa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(42fd8fa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  904): updateBatteryInfo
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4800): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4800): ====startRecUseTime====
D/htc.customization.log.level( 4800):  is 
W/CustomizationLogLevel( 4800): Level value is invalid, use default level 2
D/CustomizationManager( 4800):  Read ACC file spent 0.124 (s)
D/CIDMapFileReader( 4800): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4800): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4800): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4800): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4800): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4800): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4800): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4800): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4800): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4800): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4800): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4800): Parsing tag category name = system
I/CustomizationCIDLoader( 4800): Parsing tag category name = application
I/CustomizationCIDLoader( 4800): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4800): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4800): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4800): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4800): Parsing tag category name = Settings
D/CustomizationManager( 4800):  Read CID file spent 0.186 (s)
D/CustomizationManager( 4800):  All configurations done spent 0.186 (s)
W/HtcNativeFlag( 4800): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4800): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4800): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4800): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  904): deletePackageAsUser: pkg=com.test.thalitest, pid=4800, uid=2000 user=0
I/ActivityManager(  904): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  904): killProcessQuiet, pid=4481
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  904): Killing 4481:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1804s
I/ActivityManager(  904): Killing 4462:com.android.chrome/u0a96 (adj 15): empty for 1804s
D/Process (  904): killProcessQuiet, pid=4462
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  904): killProcessQuiet, pid=4433
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  904): killProcessQuiet, pid=3789
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  904): Killing 4433:com.google.android.setupwizard/u0a79 (adj 15): empty for 1804s
I/ActivityManager(  904): Killing 3789:com.google.android.music:main/u0a154 (adj 15): empty for 1804s
I/ActivityManager(  904): Recipient 4462
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Recipient 4433
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Recipient 3789
D/MediaRouterService(  904): Client com.google.android.music (pid 3789): Died!
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Recipient 4481
W/PackageSettings(  904): Skipping PackageSetting{42273eb0 com.example.hello/10397} due to missing metadata
I/ActivityManager(  904): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
D/DotMatrix( 1558): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1558): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1558): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
W/GeofencerStateMachine( 1219): Ignoring removeGeofence because network location is disabled.
D/PMS     (  904): acquireWL(437f1b10): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
D/AccTypeManager( 1342): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  904): releaseWL(437f1b10): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "sms"
W/SystemReader( 1253): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/VoicemailCleanupService( 1296): Cleaning up data for package: com.test.thalitest
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/Prism.ItemManager( 1266): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1266): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "smsto"
W/AccTypeManager( 1342): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1342): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/[PluginManager]RegisterService( 1316): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/Launcher( 1266): Deferring update until onResume
D/Launcher( 1266): waitUntilResume // bindAppsRemoved
D/Prism.PackageStateRece_( 1266): action: android.intent.action.PACKAGE_REMOVED
I/[PluginManager]RegisterService( 1316): handle notify Blinkfeed plugin client changed
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/IcingCorporaProvider( 2789): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/InputMethodManagerService(  904): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mmsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
E/ExternalAccountType( 1342): Unsupported attribute readOnly
I/ActivityManager(  904): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4814 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "sms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "smsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/PackageManager(  904):   Scheme: "mms"
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mmsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
D/PhoneApp( 1240): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  904): acquireWL(43a74f68): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2789): UpdateCorporaTask done [took 460 ms] updated apps [took 460 ms] 
D/PMS     (  904): acquireWL(4399fbc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
V/AlarmManager(  904): sending alarm PendingIntent{41e0a2d0: PendingIntentRecord{42502ec0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1726626, Int=0
V/AlarmManager(  904): sending alarm PendingIntent{420bec28: PendingIntentRecord{4264a248 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1822008, Int=1800000
V/AlarmManager(  904): sending alarm PendingIntent{4248bfa0: PendingIntentRecord{42743cd0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1847231, Int=0
V/AlarmManager(  904): sending alarm PendingIntent{438cbbe0: PendingIntentRecord{4273aaa0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1912322, Int=0
V/AlarmManager(  904): sending alarm PendingIntent{42423b78: PendingIntentRecord{42423b40 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452020978573, Int=900000
E/SQLiteDatabase( 4814): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4814): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4814): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4814): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4814): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4814): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4814): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4814): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4814): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4814): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4814): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4814): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4814): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4814): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4814): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4814): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4814): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4814): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4814): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4814): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4814): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4814): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4814): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4814): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4814): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4814): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4814): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4814): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4814): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4814): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4814): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4814): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4814): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4814): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4814): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4814): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4814): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4814): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4814): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4814): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4814): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4814): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4814): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4814): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4814): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4814): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4814): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4814): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4814): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4814): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4814): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4814): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4814): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4814): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4814): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4814): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4814): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4814): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4814): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4814): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4814): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4814): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4814): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4814): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4814): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4814): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4814): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4814): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4814): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4814): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4814): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4814): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4814): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4814): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4814): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4814): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4814): threadid=11: thread exiting with uncaught exception (group=0x4173ee30)
E/ActivityManager(  904): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4814): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4814): Process: com.google.android.apps.docs, PID: 4814
E/AndroidRuntime( 4814): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4814): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4814): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4814): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4814): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4814): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4814): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4814): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4814): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4814): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4814): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4814): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4814): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4814): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4814): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4814): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4814): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4814): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4814): 	at aho.run(AbstractDatabaseInstance.java:455)
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
D/Process ( 4814): killProcess, pid=4814
D/Process ( 4814): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  904): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4832 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  904): Recipient 4814
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Process com.google.android.apps.docs (pid 4814) has died.
W/ContextImpl( 4832): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  904): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4844 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4832): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4832): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4832): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4832): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4832): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4832): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4832): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4832): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4832): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4832): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4832): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4832): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4832): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4832): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4832): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4832): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4832): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4832): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4832): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4832): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4832): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4832): threadid=10: thread exiting with uncaught exception (group=0x4173ee30)
E/ActivityManager(  904): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4832): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4832): Process: com.android.keychain, PID: 4832
E/AndroidRuntime( 4832): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4832): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4832): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4832): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4832): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4832): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4832): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4832): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4832): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4832): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4832): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4832): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4832): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4832): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4832): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4832): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4832): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4832): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4832): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4832): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  904): HtcErrorReportManager Begin---add error logs to dropbox
D/AppTag  ( 4844): getInstance(Context context)
D/AppTag  ( 4844): getInstance(Context context)
D/Process ( 4832): killProcess, pid=4832
D/Process ( 4832): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/AppTag  ( 4844): onCreate()
E/ErrorReport(  904): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  904): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452021059937.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  904): Recipient 4832
I/ActivityManager(  904): Process com.android.keychain (pid 4832) has died.
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ActivityManager(  904): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/PMS     (  904): acquireWL(423c7b78): PARTIAL_WAKE_LOCK  AsyncService 0x1 3967 10160 null
D/PMS     (  904): releaseWL(423c7b78): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/Process (  904): killProcessQuiet, pid=4552
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 4552:com.google.android.gms.unstable/u0a29 (adj 15): empty for 1800s
V/AlarmManager(  904): sending alarm PendingIntent{42002168: PendingIntentRecord{420622d0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1912923, Int=0
W/dalvikvm( 3991): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 2176): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2176): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 2176): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2176): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 2176): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 2176): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2176): Module APK com.google.android.play.games already loaded
I/ActivityManager(  904): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
E/SQLiteLog( 2176): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2176): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca9bc70
E/SQLiteLog( 2176): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2176): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6e4cfa20
W/dalvikvm( 2176): threadid=48: thread exiting with uncaught exception (group=0x4173ee30)
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
I/ActivityManager(  904): Recipient 4552
E/ActivityManager(  904): App crashed! Process: com.google.android.gms
E/SQLiteDatabase( 2176): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
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
E/SQLiteDatabase( 2176): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2176): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2176): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2176): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 2176): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2176): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2176): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2176): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/PhenotypeInitializer( 2176): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 2176): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 2176): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 2176): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/PhenotypeInitializer( 2176): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/PhenotypeInitializer( 2176): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 2176): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 2176): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 2176): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/PhenotypeInitializer( 2176): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/PhenotypeInitializer( 2176): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/PhenotypeInitializer( 2176): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/PhenotypeInitializer( 2176): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2176): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2176): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 2176): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 2176): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 2176): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 2176): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 2176): 	at android.os.Looper.loop(Looper.java:157)
E/PhenotypeInitializer( 2176): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 2176): killProcess, pid=2176
D/Process ( 2176): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
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
I/Prism.ItemManager( 1266): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1266): loadItems() com.htc.launcher.pageview.WidgetManager@41c01df0 +
I/Prism.WidgetManager( 1266): onLoadItems() +
W/PackageManager(  904): Unable to load service info ResolveInfo{42494fd0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
I/ActivityManager(  904): Recipient 2176
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Process com.google.android.gms (pid 2176) has died.
D/PMS     (  904): handleWLDeath(43a74f68): PARTIAL_WAKE_LOCK  Icing 0x1
D/WifiService(  904): Client connection lost with reason: 4
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 10999ms
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20999ms
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 20999ms
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 20998ms
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20998ms
I/ActivityManager(  904): Resuming delayed broadcast
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20994ms
E/SQLiteLog( 1358): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1358): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x63fbf198
W/dalvikvm( 1358): threadid=1: thread exiting with uncaught exception (group=0x4173ee30)
E/ActivityManager(  904): App crashed! Process: com.google.process.gapps
E/AndroidRuntime( 1358): FATAL EXCEPTION: main
E/AndroidRuntime( 1358): Process: com.google.process.gapps, PID: 1358
E/AndroidRuntime( 1358): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1358): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1358): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1358): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1358): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1358): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1358): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1358): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1358): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1358): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1358): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1358): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1358): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1358): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1358): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1358): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1358): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1358): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1358): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1358): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1358): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1358): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1358): 	... 10 more
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
D/Process ( 1358): killProcess, pid=1358
D/Process ( 1358): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  904): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4874 uid=10098 gids={50098, 3003, 5012}
I/DeviceManagement( 4874): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4874 dbg=false s=true
I/DeviceManagement( 4874): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 4874): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Recipient 1358
D/WifiService(  904): Client connection lost with reason: 4
I/ActivityManager(  904): Process com.google.process.gapps (pid 1358) has died.
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20828ms
I/DeviceManagement( 4874): WorkflowService: Starting workflow service
I/DeviceManagement( 4874): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41ba40d8] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4874): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4874): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 4874): PackageUpdateWorkflow: ==================================================

```
