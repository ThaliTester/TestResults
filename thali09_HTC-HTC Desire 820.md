#### Test 549702610263d9b_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
V/LightsService(  913): setLight #0: color=#26
,V/LightsService(  913): setLight #0: color=#23
V/LightsService(  913): setLight #0: color=#1c
V/LightsService(  913): setLight #0: color=#15
V/LightsService(  913): setLight #0: color=#14
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  913):    returned true
E/cutils-trace( 4461): Error opening trace file: No such file or directory (2)
I/ActivityManager(  913): Waited long enough for: ServiceRecord{43eec188 u0 com.htc.htclocationservice/.AutoSettingService}
D/CustomizationManager( 4461): ====startRecUseTime====
D/htc.customization.log.level( 4461):  is 
W/CustomizationLogLevel( 4461): Level value is invalid, use default level 2
D/CustomizationManager( 4461):  Read ACC file spent 0.060 (s)
D/CIDMapFileReader( 4461): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4461): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4461): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4461): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4461): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4461): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4461): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4461): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4461): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4461): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4461): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4461): Parsing tag category name = system
I/CustomizationCIDLoader( 4461): Parsing tag category name = application
I/CustomizationCIDLoader( 4461): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4461): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4461): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4461): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4461): Parsing tag category name = Settings
D/CustomizationManager( 4461):  Read CID file spent 0.105 (s)
D/CustomizationManager( 4461):  All configurations done spent 0.105 (s)
W/HtcNativeFlag( 4461): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4461): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4461): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4461): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  913): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  913): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  913): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  913): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  913): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  913): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  913): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4461
D/PMS     (  913): acquireHCC(4292bd78): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 913 1000 null
D/PMS     (  913): acquireHCC(42ef6420): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 913 1000 null
W/asset   (  913): Copying FileAsset 0x6809f4b0 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  913): @test_code: getHtcIntentFlag: 0 obj: 1124251992
I/FeedHostManager( 1273): [onPause]
I/FeedProviderManager( 1273): onPause
I/FeedHostManager( 1273): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@428ceb18
I/SocialFeedProvider( 1273): +onPause
I/SocialFeedProvider( 1273): -onPause
D/PMS     (  913): acquireWL(429d1750): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 913 1000 null
I/ActivityManager(  913): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4472 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1273): [trimMemory] 20
W/asset   ( 4472): Copying FileAsset 0x5c882428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4472): Binding Chromium to main looper Looper (main, tid 1) {42410a40}
I/LibraryLoader( 4472): Expected native library version number "",actual native library version number ""
I/chromium( 4472): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4472): Initializing chromium process, renderers=0
D/PMS     (  913): acquireWL(441c2868): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  913): acquireWL(4303d428): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/BluetoothManagerService(  913): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  913): java.lang.Throwable: stack dump
D/BluetoothManagerService(  913): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44616908:true
W/System.err(  913): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  913): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  913): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  913): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  913): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4472): 1111650008: getState(). Returning 12
D/PMS     (  913): releaseWL(441c2868): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4472): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4472): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4472): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4472): Local Branch: 
I/Adreno-EGL( 4472): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4472): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4472):                  aa63bbd948f41d15fc72f585e
W/chromium( 4472): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4472): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4472): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4472): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4472): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4472): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4472): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4472): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4472): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4472): CordovaWebView is running on device made by: HTC
,W/AwContents( 4472): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  913): Disable input method client, pid=1273
,W/ResourceType( 4472): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4472): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@42458588, mServedView=org.apache.cordova.engine.SystemWebView{4241e1f0 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1210): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1210): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,I/InputMethodManagerService(  913): Enable input method client, pid=4472
W/AwContents( 4472): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  913): Displayed com.test.thalitest/.MainActivity: +294ms
,D/PMS     (  913): releaseWL(429d1750): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4472): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4472): JniHelper::setJavaVM(0x41fd0010), pthread_self() = 1663810376
,D/JX-Cordova( 4472): jxcore cordova android initializing
,I/dalvikvm-heap( 4472): Grow heap (frag case) to 11.632MB for 95956-byte allocation
,I/dalvikvm-heap( 4472): Grow heap (frag case) to 11.710MB for 143930-byte allocation
,I/dalvikvm-heap( 4472): Grow heap (frag case) to 11.822MB for 215890-byte allocation
,I/dalvikvm-heap( 4472): Grow heap (frag case) to 11.994MB for 323830-byte allocation
,I/dalvikvm-heap( 4472): Grow heap (frag case) to 12.266MB for 485740-byte allocation
,I/dalvikvm-heap( 4472): Grow heap (frag case) to 13.272MB for 1092904-byte allocation
,I/dalvikvm-heap( 4472): Grow heap (frag case) to 14.182MB for 1639352-byte allocation
,I/dalvikvm-heap( 4472): Grow heap (frag case) to 15.518MB for 2459024-byte allocation
,W/CpuWake (  913): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  913): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  913): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  913): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  913): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  913): <<release mCpuPerf_Freq wakelock
D/PMS     (  913): releaseHCC(4292bd78): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  913): releaseHCC(42ef6420): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4472): Grow heap (frag case) to 17.624MB for 3688532-byte allocation
,W/jxcore-log( 4472): Initializing JXcore engine
,W/jxcore-log( 4472): JXcore engine is ready
,W/jxcore-log( 4472): Starting JXcore engine
,W/jxcore-log( 4472): Platform android
W/jxcore-log( 4472): 
,W/jxcore-log( 4472): Process ARCH arm
W/jxcore-log( 4472): 
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  913):    returned true
,D/PMS     (  913): releaseWL(4303d428): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4472): JXcore Cordova bridge is ready!
I/jxcore-log( 4472): 
,W/jxcore-log( 4472): JXcore engine is started
,I/chromium( 4472): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4472): Toggling radios to true
I/jxcore-log( 4472): 
,D/BluetoothAdapter( 4472): enable(): BT is already enabled..!
,D/WifiManager( 4472): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
,W/HtcDLNAServiceManager(  913): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  913): Settings:Agentname: wifi_on
D/WifiService(  913): New client listening to asynchronous messages
D/WifiService(  913): setWifiEnabled: true pid=4472, uid=10389
E/WifiService(  913): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  913): isSprintWifiRestricted(): false
I/WifiService(  913): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  913): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/HtcDLNAServiceManager(  913): Settings:Agentvalue: 2
W/Settings:Agent(  913): >> traceCallingStack()
W/Settings:Agent(  913): Process.myPid(): 913
W/Settings:Agent(  913): Process.myTid(): 1312
W/Settings:Agent(  913): Process.myUid(): 1000
W/Settings:Agent(  913): 
W/Settings:Agent(  913): 
W/System.err(  913): java.lang.Throwable: stack dump
W/System.err(  913): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  913): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  913): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  913): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  913): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  913): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  913): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  913): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  913): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  913): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  913): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  913): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  913): 
W/Settings:Agent(  913): << traceCallingStack(): 1(ms)
D/WifiManager( 4472): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  913): doBoolean: DISCONNECT
D/WifiManager( 4472): reconnect: Base Package Name=com.test.thalitest, uid=10389
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): TDLS: Tear down peers
I/wpa_supplicant( 1157): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4472): Radios toggled
I/jxcore-log( 4472): 
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1157): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1157): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,I/wpa_supplicant( 1157): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  913): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1157): TDLS: Remove peers on disassociation
D/HTCRequest(  913): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
,D/HTCRequest(  913): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  913): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  913): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  913): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  913): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  913): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  913): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  913): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  913): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
E/wpa_supplicant( 1157): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1157): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1157): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1157): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb7259bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1157):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1157): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1157): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1157): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1157): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1157): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1157): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1157): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1157): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1157): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1157): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1157): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1157): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1157): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1157): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1157): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1157): EAPOL: External notification - portValid=0
,D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1157): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1157): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1157): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1157): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1157): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1157): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1157): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1157): nl80211: Event message available
D/wpa_supplicant( 1157): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1157): nl80211: Ignore disconnect event triggered during reassociation
D/WifiNative-wlan0(  913):    returned true
,D/HTCRequest(  913): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  913): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  913): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  913): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/WifiPerfLock(  913): release()
D/WifiStateMachine(  913): PerfLock released for exiting ConnectedState
D/Tethering(  913): interfaceLinkStateChanged wlan0, false
D/Tethering(  913): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  913): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1157): Power_Mode_Type mode = 0
I/wpa_supplicant( 1157): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 61
D/Tethering(  913): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  913):    returned true
D/Tethering(  913): interfaceLinkStateChanged wlan0, false
D/Tethering(  913): interfaceStatusChanged wlan0, false
D/Tethering(  913): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  913): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  913):    returned true
D/ConnectivityService(  913): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  913): acquireWL(44a8b448): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 913 1000 null
D/WifiP2pService(  913): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  913): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  913): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  913): [NET] getaddrinfo-, SUCCESS
D/DhcpStateMachine(  913): [RunningState] Stop DHCP
D/WifiStateMachine(  913): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  913): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  913): [NET] getaddrinfo-, SUCCESS
D/WifiDataStallTracker(  913): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  913): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  913): stopDataStallAlarm: current tag=20844 mDataStallAlarmIntent=PendingIntent{42f75680: PendingIntentRecord{42cebee8 android broadcastIntent}}
I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024951
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025043
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025047
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025050
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025054
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026558
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026576
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029785
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiNative-wlan0(  913): doBoolean: RECONNECT
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): Fast associate: Old scan results
I/wpa_supplicant( 1157): wpa_supplicant_scan enter
I/wpa_supplicant( 1157): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1157): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1157): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1157): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1157): nl80211: Event message available
D/wpa_supplicant( 1157): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/HTCRequest(  913): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  913): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  913): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  913): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiNative-wlan0(  913):    returned true
,D/WifiStateMachine(  913): Enter handleNetworkDisconnect
D/WifiNative-wlan0(  913): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1157): Power_Mode_Type mode = 0
I/wpa_supplicant( 1157): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  913):    returned true
,D/WifiNative-wlan0(  913): doBoolean: DRIVER BTCOEXMODE 2
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024951
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025043
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025047
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025050
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025054
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026558
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026576
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029785
D/WifiStateTracker(  913): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  913): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  913): Provision feature enable=false
D/ConnectivityService(  913): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/UsbnetStateTracker(  913): isAvailable+-
D/UsbnetStateTracker(  913): reconnect
D/UsbnetStateTracker(  913): isAvailable+-
,D/WifiNative-wlan0(  913):    returned true
,D/WISPrService( 3807): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/WifiP2pService(  913): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  913): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  913): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  913): default: reconnect()
D/MDST    (  913): default: setTeardownRequested(false)
D/MDST    (  913): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  913): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  913): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  913): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
,D/WISPrService( 3807): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  913): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  913): Exit handleNetworkDisconnect
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/WifiService(  913): New client listening to asynchronous messages
W/ConnectivityService(  913): Exception trying to remove a route: java.lang.IllegalStateException: command '29 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 29 Failed to remove route from default table (No such process)'
D/ConnectivityService(  913): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  913): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  913): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
,D/ConnectivityService(  913): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WifiDataStallTracker(  913): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  913): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
,V/NativeCrypto( 1356): Read error: ssl=0x64071318: I/O error during system call, Connection timed out
D/libc    (  365): [NET] entry_id:4   entry:0xb7760320  removed 
D/libc    (  365): [NET] entry_id:5   entry:0xb775ffd8  removed 
D/libc    (  365): [NET] entry_id:2   entry:0xb77604f0  removed 
D/libc    (  365): [NET] entry_id:1   entry:0xb7760428  removed 
D/libc    (  365): [NET] entry_id:6   entry:0xb7760240  removed 
D/libc    (  365): [NET] entry_id:3   entry:0xb77600e8  removed 
D/libc    (  365): [NET] entry_id:7   entry:0xb775bf60  removed 
,D/libc    (  365): *************************
D/libc    (  365): *** DNS CACHE FLUSHED ***
D/libc    (  365): *************************
V/NativeCrypto( 1356): SSL shutdown failed: ssl=0x64071318: I/O error during system call, Broken pipe
D/WifiStateMachine(  913): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  913): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateTracker(  913): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/ConnectivityService(  913): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  913): handleConnectivityChange: resetting
D/ConnectivityService(  913): resetConnections(wlan0, 3)
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/PMS     (  913): acquireWL(4448ad30): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  913): flush DNS cache for net 1(wlan0)
,D/WifiStateMachine(  913): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 3807): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  913): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 3807): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/Nat464Xlat(  913): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  913): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  913): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024951
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025043
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025047
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025050
D/ConnectivityService(  913): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025054
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026558
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026576
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029785
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
D/ConnectivityService(  913): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  913): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1356/10029)
D/ConnectivityService(  913): reportInetCondition for net -1, percentage: 0 by  (1356/10029)
D/PMS     (  913): acquireWL(42ff11d0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 913 1000 null
,I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:1
D/WirelessDisplayService(  913): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  913): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/WifiStateMachine(  913): startScan Pid: 913 Uid 1000
D/WifiNative-wlan0(  913): doBoolean: SCAN
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1157): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/WifiNative-wlan0(  913):    returned false
I//system/bin/ip(  365): RTNETLINK answers: No such process
I/logwrapper(  365): /system/bin/ip terminated by exit(2)
D/ConnectivityService(  913): getNetworkInfo networkType=1 called by  (913/1000)
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1356/10029)
D/BatSI   (  913): WIFI scan started for: 650a0300 uid:1000
D/PMS     (  913): releaseWL(4448ad30): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1356/10029)
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1356/10029)
D/ConnectivityService(  913): mActiveDefaultNetwork: -1
D/ConnectivityService(  913): handleInetConditionChange: no active default network - ignore
,I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:1
D/PMS     (  913): releaseWL(42ff11d0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,V/Tethering(  913): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  913): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  913): [AlarmQueuing] connectivity wifi: false
D/Tethering(  913): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  913): bSetPropertyMultiRAB:false
D/Tethering(  913): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  913): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  913): ipv4Default null
I/Tethering(  913): No IPv4 upstream interface, giving up.
D/Tethering(  913): TetherMasterSM: InitialState processMessage what=3
D/CaptivePortalTracker(  913): DelayedCaptiveCheckState
D/CaptivePortalTracker(  913): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  913): NoActiveNetworkState
,I/NetworkMonitor( 4347): type=WIFI subType= reason=null isConnected=false
,I/ConnectivityHelper( 1273): [onReceive] WIFI(1): DISCONNECTED
D/htcCheckinService(  913): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  913): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  913): getNetworkInfo networkType=1 called by  (913/1000)
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
D/PMS     (  913): acquireWL(42ea5240): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 913 1000 null
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.backuptransport (1573/10029)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.apps.docs (4273/10100)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.google.android.music (4347/10154)
D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.htc.launcher (1273/10076)
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.apps.docs (4273/10100)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024951
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025043
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025047
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025050
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025054
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026558
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026576
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029785
D/ConnectivityService(  913): getActiveNetworkInfo called by  (2729/10021)
,D/GpsLocationProvider(  913): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  913): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  913): getAGpsConnectionInfo connType - 4
,I/ActivityManager(  913): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4526 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/GpsLocationProvider(  913): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  913): releaseWL(42ea5240): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ACRA    ( 4526): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4526): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4526): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4526): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4526): Preparing secondary program dexes.
V/DexLibLoader( 4526): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4526): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4526): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4526): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4526): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4526): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4526): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4526): Dex already copied
D/OdexVerifier( 4526): Odex verification is skipped.
,V/DexLibLoader( 4526): Creating class loader
,V/DexLibLoader( 4526): Finished creating class loader
V/DexLibLoader( 4526): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4526): Dex already copied
D/OdexVerifier( 4526): Odex verification is skipped.
,V/DexLibLoader( 4526): Creating class loader,
V/DexLibLoader( 4526): Finished creating class loader
,V/DexLibLoader( 4526): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4526): Dex already copied
D/OdexVerifier( 4526): Odex verification is skipped.
,V/DexLibLoader( 4526): Creating class loader
,V/DexLibLoader( 4526): Finished creating class loader
V/DexLibLoader( 4526): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4526): Dex already copied
D/OdexVerifier( 4526): Odex verification is skipped.
,V/DexLibLoader( 4526): Creating class loader
,V/DexLibLoader( 4526): Finished creating class loader
,V/DexLibLoader( 4526): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4526): DexLibLoader.ensureDexLoaded took 17 ms
,W/dalvikvm( 4526): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4526): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4526): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4526): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4526): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4526): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4526): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1157): nl80211: Event message available
D/wpa_supplicant( 1157): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1157): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1157): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1157): nl80211: Survey data missing
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1157): Sorted scan results
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1157): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1157): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-54
I/wpa_supplicant( 1157): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-77
D/wpa_supplicant( 1157): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1157): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1157): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1157): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1157): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1157): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1157): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1157): wpa_supplicant_pick_network+
I/wpa_supplicant( 1157): Selecting BSS from priority group 1
I/wpa_supplicant( 1157): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1157): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1157): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1157): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1157):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1157):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1157): Start print parameters
I/wpa_supplicant( 1157): wpa_s->wpa_state is 3
I/wpa_supplicant( 1157): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1157): isConcurrentMode() is 0
I/wpa_supplicant( 1157): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1157): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1157): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1157): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1157): wpa_s->reassociate is 1
I/wpa_supplicant( 1157): wpa_s->is_screen_on 1
I/wpa_supplicant( 1157): wpa_s->ifname wlan0
I/wpa_supplicant( 1157): End print parameters
I/wpa_supplicant( 1157): selected network = 1
D/wpa_supplicant( 1157): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb725b4e8  current_ssid=0x0
D/wpa_supplicant( 1157): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1157): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1157): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1157): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1157): check if in concurrent case
I/wpa_supplicant( 1157): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  913): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  913): doString: LIST_DONGLES
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1157): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1157): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1157): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1157): RSN: PMKSA cache search - network_ctx=0xb725b4e8 try_opportunistic=0
D/wpa_supplicant( 1157): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1157): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1157): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1157): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1157): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1157): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1157): nl80211: Unsubscribe mgmt frames handle 0xb725a718 (mode change)
D/wpa_supplicant( 1157): nl80211: Subscribe to mgmt frames with non-AP handle 0xb725a718
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb725a718
D/HTCRequest(  913): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  913): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb725a718
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb725a718
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb725a718
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb725a718
D/HTCRequest(  913): WifiMonitor:handleSupplicantStateChange(): SSID
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb725a718
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb725a718
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb725a718
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/WifiMonitor(  913): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb725a718
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Register frame type=0xd0 nl_handle=0xb725a718
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1157): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1157):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1157):   * freq=2412
D/wpa_supplicant( 1157):   * Auth Type 0
D/wpa_supplicant( 1157):   * WPA Versions 0x2
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1157): nl80211: Connect request send successfully
D/wpa_supplicant( 1157): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1157): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 1157): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,W/ContextImpl(  913): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  913): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1157): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1157): reply (489) for get BSS: id=0
I/wpa_supplicant( 1157): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1157): freq=5220
I/wpa_supplicant( 1157): level=-46
I/wpa_supplicant( 1157): tsf=0000000105111167
I/wpa_supplicant( 1157): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=NG7005g
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=1
I/wpa_supplicant( 1157): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1157): freq=2412
I/wpa_supplicant( 1157): level=-54
I/wpa_supplicant( 1157): tsf=0000000105111183
I/wpa_supplicant( 1157): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1157): ssid=NG700
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=2
I/wpa_supplicant( 1157): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1157): freq=2412
I/wpa_supplicant( 1157): level=-77
I/wpa_supplicant( 1157): tsf=0000000105111187
I/wpa_supplicant( 1157): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1157): ssid=Gonzos
I/wpa_supplicant( 1157): ====
I/wpa_supplicant( 1157): id=3
I/wpa_supplicant( 1157): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1157): freq=2412
I/wpa_supplicant( 1157): level=-54
I/wpa_supplicant( 1157): tsf=0000000105111179
I/wpa_supplicant( 1157): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1157): ssid=01ABC
I/wpa_supplicant( 1157): ####
,D/WirelessDisplayService(  913): getDiscoveryDongleList
,D/WifiStateMachine(  913): == begin of scan result ==
,D/WifiStateMachine(  913): == (4) end of scan result ==
,D/WirelessDisplayService(  913): getDiscoveryDongleList
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
D/WifiStateMachine(  913): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 105111167, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  913): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 105111183, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  913): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -77, frequency: 2412, timestamp: 105111187, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  913): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 105111179, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  913): add 4 to mScanResults
D/BatSI   (  913): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  913): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
D/WifiManager( 1224): getScanResults enter 
D/WifiStateMachine(  913): == begin of scan result ==
D/WifiStateMachine(  913): == (4) end of scan result ==
,W/dalvikvm( 4526): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4526): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1157): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1157): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1157): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1157): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1157): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1157): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1157): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1157): nl80211: Event message available
D/wpa_supplicant( 1157): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1157): nl80211: Connect event
D/Tethering(  913): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1157): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1157): nl80211: Associated with c0:ff:d4:d3:aa:48
D/Tethering(  913): interfaceStatusChanged wlan0, false
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1157): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1157): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1157): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1157): Add randomness: count=10 entropy=4
I/wpa_supplicant( 1157): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1157): TDLS: Remove peers on association
D/wpa_supplicant( 1157): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1157): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1157): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1157): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1157): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1157): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1157): EAPOL: enable timer tick
D/wpa_supplicant( 1157): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1157): State: ASSOCIATED -> 4WAY_HANDSHAKE
,D/wpa_supplicant( 1157): Get randomness: len=32 entropy=5
D/HTCRequest(  913): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  913): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  913): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  913): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
I/wpa_supplicant( 1157): htc_wext_set_keepalive +
I/wpa_supplicant( 1157): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1157): getPrivFuncNum +	
I/wpa_supplicant( 1157): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1157): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1157): htc_wext_set_keepalive - ret = 0
D/Tethering(  913): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  913): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  913): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  913): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  913): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  913): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  913): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  913): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
,D/Tethering(  913): interfaceLinkStateChanged wlan0, true
D/WifiMonitor(  913): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  913): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
,D/Tethering(  913): interfaceStatusChanged wlan0, true
D/WifiStateMachine(  913): Enter handleAssociatedWithEvent
D/HTCRequest(  913): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  913): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  913): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  913): Associated
,D/WifiMonitor(  913): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/Tethering(  913): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  913): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
,D/WifiStateMachine(  913): Exit handleAssociatedWithEvent
,D/WifiStateMachine(  913): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  913): updateConnectedAP...
,D/WifiApDatabaseHandler(  913): updateConnectedAP...
,D/WifiStateMachine(  913): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiApDatabaseHandler(  913): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  913): This record is existed, only update it...
,D/WifiStateMachine(  913): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  913): updateConnectedAP...
,D/WifiStateMachine(  913): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  913): updateConnectedAP...
,I/wpa_supplicant( 1157): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb725a9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 1157):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1157): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1157): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6efbb4a key_idx=1 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 1157):    broadcast key
D/HTCRequest(  913): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  913): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 11
D/HTCRequest(  913): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1157): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1157): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1157): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1157): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
D/WifiMonitor(  913): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
,I/wpa_supplicant( 1157): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  913): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1157): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1157): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
,D/wpa_supplicant( 1157): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1157): set send_ind_to_ndc = 0
I/wpa_supplicant( 1157): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1157): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1157): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1157): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1157): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1157): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1157): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1157): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1157): EAPOL: Supplicant port status: Authorized
D/HTCRequest(  913): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1157): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  913): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 18
D/HTCRequest(  913): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1157): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1157): EAPOL authentication completed successfully
I/wpa_supplicant( 1157): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1157): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1157): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/WifiMonitor(  913): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/wpa_supplicant( 1157): nl80211: if_removed already cleared - ignore event
,D/WifiStateMachine(  913): fetchFrequency(), freq = 2412
D/WifiStateMachine(  913): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/Tethering(  913): interfaceLinkStateChanged wlan0, true
,D/Tethering(  913): interfaceStatusChanged wlan0, true
D/Tethering(  913): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  913): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  913): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  913): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateTracker(  913): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,D/WifiApDatabaseHandler(  913): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  913): This record is existed, only update it...
D/WifiStateMachine(  913): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiApDatabaseHandler(  913): updateConnectedAP...
D/ConnectivityService(  913): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  913): Provision feature enable=false
D/ConnectivityService(  913): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WISPrService( 3807): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3807): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  913): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  913): updateConnectedAP...
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024951
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025043
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025047
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025050
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025054
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026558
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026576
,D/WifiStateMachine(  913): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/DhcpStateMachine(  913): [StoppedState] Start DHCP
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,E/FbInjectorInitializer( 4526): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  913):    returned true
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029785
,D/WifiNative-wlan0(  913): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  913):    returned true
,D/WifiNative-wlan0(  913): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1157): Power_Mode_Type mode = 1
I/wpa_supplicant( 1157): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  913):    returned true
D/WifiNative-wlan0(  913): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  913):    returned null
E/WifiStateMachine(  913): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  913): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  913):    returned null
D/WifiStateMachine(  913): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  913): acquireWL(44a72b68): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 913 1000 null
D/WifiStateMachine(  913): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  913): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42d23ea0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  913): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42d23ea0 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:0
,W/fb4a(:<default>):StaticBindingVerifier( 4526): Verify
,D/WifiService(  913): New client listening to asynchronous messages
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4526/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4526): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4526): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4526): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  913): killProcessQuiet, pid=4142
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  913): Killing 4142:com.google.android.talk/u0a111 (adj 15): empty #17
,D/AutoSetting( 1317): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  913): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4555 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.htc.sense.hsp (1317/10055)
,D/AutoSetting( 1317): Util - no network available!
,D/AutoSetting( 1317): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1317): service - mHandler: cancel location update
,D/AutoSetting( 1317): service -           changes count: 0
D/ConnectivityService(  913): getActiveNetworkInfo called by com.htc.sense.hsp (1317/10055)
,W/fb4a(:<default>):UserScope( 4526): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4526): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/MobileConnectivityChangeReceiver( 4555): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4555): onReceive CONNECTIVITY_CHANGE networkType=1
,E/PhoneMonitor( 4555): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4555): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,W/fb4a(:<default>):UserScope( 4526): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
I/ActivityManager(  913): Recipient 4142
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  913): killProcessQuiet, pid=4242
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  913): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4569 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
I/ActivityManager(  913): Killing 4242:com.google.android.partnersetup/u0a32 (adj 15): empty #17
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.setupwizard (4555/10079)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.setupwizard (4555/10079)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.setupwizard (4555/10079)
,I/ActivityManager(  913): Recipient 4242
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4526): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,D/libc    (  913): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  913): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  913): [MLHD] enter handleMediaLinkEvent DefaultState
,D/Process (  913): killProcessQuiet, pid=4273
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  913): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4592 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
I/ActivityManager(  913): Killing 4273:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/dalvikvm-heap( 4526): Grow heap (frag case) to 9.958MB for 84664-byte allocation
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4592): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4592): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4526): Grow heap (frag case) to 9.973MB for 28144-byte allocation
,E/dalvikvm( 4526): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4526): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4526): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4526): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4526): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4526): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4526): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4526): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/GAV2    ( 4592): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/dalvikvm( 4526): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4526): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4526): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4526): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4526): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4526): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  913): Recipient 4273
E/dalvikvm( 4526): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4526): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/dalvikvm( 4526): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4526): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,W/ContextImpl( 4592): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4592): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4526): Grow heap (frag case) to 10.042MB for 39954-byte allocation
,I/dalvikvm-heap( 4526): Grow heap (frag case) to 10.119MB for 79892-byte allocation
,I/PMS     (  913): Going to sleep due to screen timeout...
,I/SensorManager(  913): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42a7aed0
,W/SensorService(  913): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  913): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  913): pid=913, uid=1000
W/SensorService(  913): Active sensors: size = 2
,W/SensorService(  913): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  913): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  913): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42a7aed0, eanble = 0, strlen(mName) = 59
W/SensorService(  913): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  913): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42cb3230
W/SensorService(  913): Listener[1] = com.htc.smartdim.sensor_eye@42eed360
,W/SensorService(  913): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  913): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  913): Couldn't get kernel wake lock stats
V/LightsService(  913): setLight #2: color=#0
D/qdlights(  913): set_light_buttons_func: on=0 brightness=0
V/LightsService(  913): setLight #0: color=#0
,W/PMS     (  913): mWirelessDisplayManager is null
D/WirelessDisplayService(  913): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  913): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.apps.magazines (4592/10151)
,I/dalvikvm-heap( 4526): Grow heap (frag case) to 10.281MB for 75760-byte allocation
,D/libc    (  913): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  913): [NET] getaddrinfo-, SUCCESS
,D/libc    (  913): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  913): [NET] getaddrinfo-, SUCCESS
,D/libc    (  913): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  913): [NET] getaddrinfo-, SUCCESS
,D/libc    (  913): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  913): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  913): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1157): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1157): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4526/10027)
W/BroadcastQueue(  913): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{44a4f2b0 u0 ReceiverList{44a4f190 4526 com.facebook.katana/10027/u0 remote:44a4edd8}}
W/BroadcastQueue(  913): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{44a4f2b0 u0 ReceiverList{44a4f190 4526 com.facebook.katana/10027/u0 remote:44a4edd8}}
W/BroadcastQueue(  913): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42f85198 u0 ReceiverList{42f85138 4526 com.facebook.katana/10027/u0 remote:442a3c48}}
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  913):    returned true
,D/WifiNative-wlan0(  913): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  913):    returned true
,D/WifiStateMachine(  913): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/WifiP2pService(  913): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  913): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/PMS     (  913): releaseWL(44a72b68): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024951
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025043
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025047
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025050
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025054
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026558
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026576
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029785
D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4526/10027)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4526/10027)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4526/10027)
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  913):    returned true
D/WifiStateMachine(  913): gateway: /192.168.1.1
,D/WifiNative-wlan0(  913): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1157): WiFi gateway: 0x101a8c0
D/WifiNative-wlan0(  913):    returned true
D/WifiStateMachine(  913): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  913): VerifyingLinkState enter
D/WifiStateMachine(  913): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  913): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  913): VerifyingLinkState: enableIpv6
D/WIFI_ICON( 1115): updateWifiState: RSSI_CHANGED -1 -> 3
,D/WifiStateMachine(  913): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -54, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  913): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  913): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/WifiDataStallTracker(  913): startDataStallAlarm: tag=20846 delay=15s
,I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiWatchdogStateMachine(  913): WAN detection
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
V/NetworkPolicy(  913): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiStateTracker(  913): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  913): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
,D/WISPrService( 3807): >>>>>WISPrService start isConnected = true<<<<<
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/libc    (  913): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  913): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  913): Provision feature enable=false
D/ConnectivityService(  913): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  913): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  913): default: teardown()
D/MDST    (  913): default: setTeardownRequested(true)
D/MDST    (  913): default: setEnableApn apnType =default , enable=false
D/MDST    (  913): default: setTeardownRequested(true)
D/ConnectivityService(  913): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  913): Unexpected mtu value: android.net.wifi.WifiStateTracker@42d99528
D/ConnectivityService(  913): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/WifiStateMachine(  913): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
D/WifiStateMachine(  913): syncGetConfiguredNetworks
D/PMS     (  913): acquireWL(44658908): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  913): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED connected
D/ConnectivityService(  913): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/PMS     (  913): releaseWL(44658908): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  913): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  913): handleConnectivityChange: resetting
D/Nat464Xlat(  913): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  913): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/WirelessDisplayService(  913): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  913):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  913): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  913): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  913): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  913): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  913): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  913): acquireWL(4303c2d0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 913 1000 null
D/ConnectivityService(  913): getNetworkInfo networkType=1 called by  (913/1000)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.setupwizard (4555/10079)
,I/QuickSettingWifi( 1115): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,D/PMS     (  913): acquireWL(4303e920): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
I//system/bin/ip(  365): RTNETLINK answers: No such file or directory
,I/logwrapper(  365): /system/bin/ip terminated by exit(254)
I/CheckinService( 2184): Checkin interval check for package: unspecified last checkin: 1452015120289 min interval config: 0 actual interval: 47266
D/wpa_supplicant( 1157): EAPOL: startWhen --> 0
D/wpa_supplicant( 1157): EAPOL: disable timer tick
D/PMS     (  913): acquireWL(445ddff0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(4303e920): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I/CheckinService( 2184): Checking schedule, now: 1452015167560 next: 1452015150255
,I/CheckinService( 2184): active receiver: enabled
,I//system/bin/ip(  365): RTNETLINK answers: No such process
,I/logwrapper(  365): /system/bin/ip terminated by exit(2)
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2184, uid=10029, userID:0
,D/ConnectivityService(  913): mActiveDefaultNetwork: WIFI
,I/CheckinService( 2184): Preparing to send checkin request
,I/EventLogService( 2184): Accumulating logs since 1452015115862
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/PMS     (  913): releaseWL(4303c2d0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,I/CheckinRequestBuilder( 2184): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  913): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2184): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  913): getNetworkInfo networkType=9 called by com.google.android.gms (2184/10029)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [1][0][0]
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SurfaceControl(  913): Excessive delay in blankDisplay() while turning screen off: 318ms
D/PMS     (  913): nativeSetInteractive:false
D/PMS     (  913): nativeSetInteractive:false done
D/PMS     (  913): nativeSetAutoSuspend:true
D/PMS     (  913): nativeSetAutoSuspend:true done
D/HABCtrl (  913): TPE algorithm. remove timeout.
D/PMS     (  913): OOBE c monitor 11
,V/KeyguardServiceDelegate(  913): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@4300da10)
V/WebViewChromiumFactoryProvider( 4592): Binding Chromium to main looper Looper (main, tid 1) {42415330}
I/LibraryLoader( 4592): Expected native library version number "",actual native library version number ""
D/NfcService( 1256): applyRouting - 0
,D/NfcService( 1256): ScreenObserver: OFF
I/chromium( 4592): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4592): Initializing chromium process, renderers=0
,D/NfcService( 1256): applyRouting -2
I/InputMethodManagerService(  913): screenObserver, isScreenOn=false
I/InputMethodManagerService(  913): Disable input method client, pid=4472
D/PMN     (  913): wakingUp
D/PMS     (  913): acquireWL(4460b5a8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
D/PMS     (  913): releaseWL(4460b5a8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/KeyguardServiceDelegate(  913): **** SHOWN CALLED ****
D/PMS     (  913): acquireWL(4419c520): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
I/InputManager(  913): Cancel all due to getting PMS screen off broadcast
I/WindowManager(  913): No lock screen! windowToken=null
D/PMS     (  913): acquireWL(4418edd0): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  913): releaseWL(4419c520): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/PMS     (  913): acquireWL(434a4070): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/PMN     (  913): onScreenOn
,E/AudioManagerAndroid( 4592): BLUETOOTH permission is missing!
I/BatteryService(  913): n_update end
D/PMS     (  913): releaseWL(434a4070): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/Adreno-EGL( 4592): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4592): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4592): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4592): Local Branch: 
I/Adreno-EGL( 4592): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4592): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4592):                  aa63bbd948f41d15fc72f585e
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
,D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
I/ActivityManager(  913): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4655 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/WirelessDisplayService(  913): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  913): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  913): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
D/MtpService( 2729): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/NfcService( 1256): applyRouting - 0
D/MtpService( 2729): [MTP][onReceive]-
,D/NfcService( 1256): applyRouting -2
D/WirelessDisplayService(  913): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  913): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  913): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  913): acquireWL(449d3230): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
V/NotificationService(  913): batLight: Full, plugged
V/LightsService(  913): setLight #8: color=#c8c800
D/qdlights(  913): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  913): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  913): setLight #8: color=#c800
D/qdlights(  913): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  913): [LedInfo] has indicator attribute
D/PMS     (  913): releaseWL(449d3230): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/qdlights(  913): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  913): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024951
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025043
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025047
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025050
,I/NSApplication( 4592): Starting up...
,D/WifiDataStallTracker(  913): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  913): startDataStallAlarm: tag=20847 delay=15s
,D/WifiNative-wlan0(  913): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1157): SET_SCREEN_ON:On
I/wpa_supplicant( 1157): htc_wext_set_keepalive +
I/wpa_supplicant( 1157): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1157): getPrivFuncNum +	
I/wpa_supplicant( 1157): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1157): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1157): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1157): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1157): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  913):    returned true
D/AlarmManager(  913): ACTION_SCREEN_ON
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025054
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026558
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026576
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029785
I/AlarmManager(  913): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  913): [AlarmQueuing] done recovering
I/AlarmManager(  913): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  913): [AlarmQueuing] done EPS screen off alarm recovering
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024951
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025043
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025047
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025050
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025054
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026558
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026576
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029785
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
W/dalvikvm( 4655): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  913): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiStateMachine(  913): BroadcastRSSIForIMS, newrssi =-54 , oldRssi= -200
,D/WifiNative-wlan0(  913): doBoolean: SignalStrength 97
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1157): WiFioffload: SignalStrength: =97
,V/SRS_Proc(  372): ParamSet string: screen_state=on
,W/dalvikvm( 4655): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
D/WifiNative-wlan0(  913):    returned true
,D/WirelessDisplayService(  913): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
I/MultiDex( 4655): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4655): install
D/WIFI_ICON( 1115): WifiActivity: 3
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
V/NotificationService(  913): batLight: Full, plugged
V/LightsService(  913): setLight #8: color=#c8c800
D/qdlights(  913): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  913): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  913): setLight #8: color=#c800
D/qdlights(  913): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  913): [LedInfo] has indicator attribute
D/qdlights(  913): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  913): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,I/MultiDex( 4655): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4655): loading existing secondary dex files
,I/MultiDex( 4655): load found 3 secondary dex files
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.apps.magazines (4592/10151)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.apps.magazines (4592/10151)
I/MultiDex( 4655): install done
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/ClockThread( 1115): stop update clock,
D/WIFI_ICON( 1115): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/NetworkPolicy(  913): updateScreenOn: false
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.apps.plus (4047/10160)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.apps.plus (4047/10160)
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
D/Process (  913): killProcessQuiet, pid=4289
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 4655): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4655): VFY: unable to resolve instance field 36
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
W/dalvikvm( 4655): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
I/ActivityManager(  913): Killing 4289:com.htc.backup/1000 (adj 15): empty #17
,W/Vold    (  348): Returning OperationFailed - no handler for errno 30
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
W/ContextImpl( 4526): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,V/JNIHelp ( 4655): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
I/ActivityManager(  913): Recipient 4289
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4526): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
,D/AutoSetting( 1317): receiver - intent: android.intent.action.USER_PRESENT
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1356/10029)
,D/TetherSettings( 3807): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3807): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3807): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3807): Cust_ConnectToPC   : spcsc>false
D/        ( 3807): Cust_ConnectToPC   : IPT>true
D/        ( 3807): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3807): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3807): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3807): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3807): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/AutoSetting( 1317): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,I/PSReceiver( 3807): onReceive:android.intent.action.USER_PRESENT
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/SmartNS_PSService( 3807): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3807): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3807):  defaultType:0
D/PMS     (  913): acquireWL(44540960): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1356/10029)
D/PMS     (  913): releaseWL(44540960): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
W/ContextImpl( 3807): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1758): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1758): onScreenOn: 1452015167898
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1758): onScreenOn: 1452015167898
D/PMS     (  913): acquireWL(44344d18): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): releaseWL(44344d18): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/SensorManager(  913): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42cb3230
,W/SensorService(  913): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  913): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  913): pid=913, uid=1000
W/SensorService(  913): Active sensors: size = 2
,W/SensorService(  913): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  913): CM36282 Proximity sensor (handle=0x00000001, connections=1)
,W/SensorService(  913): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42cb3230, eanble = 0, strlen(mName) = 91
,W/SensorService(  913): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  913): Listener[0] = com.htc.smartdim.sensor_eye@42eed360
,W/SensorService(  913): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  913): goingToSleep
D/PMS     (  913): acquireWL(43c10630): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 913 1000 null
,I/ProviderInstaller( 4655): Installed default security provider GmsCore_OpenSSL
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024951
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025043
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025047
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025050
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025054
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026558
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026576
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029785
,I/ActivityManager(  913): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4683 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/AlarmManager(  913): ACTION_SCREEN_OFF
I/AlarmManager(  913): [AlarmQueuing] screen off now: 
I/AlarmManager(  913): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  913): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  913): stopDataStallAlarm: current tag=20847 mDataStallAlarmIntent=PendingIntent{42d13718: PendingIntentRecord{42cebee8 android broadcastIntent}}
I/AlarmManager(  913): [AlarmQueuing] wifi connection: true
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024951
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025043
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025047
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025050
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025054
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026558
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026576
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029785
,D/WifiNative-wlan0(  913): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1157): SET_SCREEN_ON:Off
I/wpa_supplicant( 1157): htc_wext_set_keepalive +
I/wpa_supplicant( 1157): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1157): getPrivFuncNum +	
I/wpa_supplicant( 1157): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1157): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1157): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1157): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1157): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  913):    returned true
D/WifiNative-wlan0(  913): doBoolean: DRIVER SETSUSPENDMODE 1,
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  372): ParamSet string: screen_state=off
D/PMS     (  913): acquireWL(44607628): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 913 1000 null
D/NetworkPolicy(  913): updateScreenOn: false
,W/dalvikvm( 4655): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4655): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
W/ContextImpl( 4683): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/wpa_supplicant( 1157): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  913):    returned true
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 4655): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4655): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4655): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
W/dalvikvm( 4655): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/PMS     (  913): releaseWL(44607628): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
W/dalvikvm( 4655): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/SmartSyncUtils( 4683): isEpsOn(), nState = 0
D/PMS     (  913): acquireWL(43f6ae28): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4683 1000 null
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/PMS     (  913): releaseWL(43f6ae28): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/PhoneStatusBar( 1115): removeHeadsNotification.gc: 52
,D/SmartSyncUtils( 4683): getMobilePolicyEnabled, result = true
W/ContextImpl(  913): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  913): killProcessQuiet, pid=4260
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  913): Killing 4260:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/ContactMessageStore( 1244): start background delete task...
D/ContactMessageStore( 1244): size: 0 , 0
D/ContactMessageStore( 1244): Background delete complete
,I/ActivityManager(  913): Recipient 4260
,D/AutoSetting( 1317): service - mHandler: cancel location update
,D/AutoSetting( 1317): service -           changes count: 0
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  913): acquireWL(433bec88): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] getTotalRam: 1873 Mb
D/PMS     (  913): releaseWL(433bec88): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): acquireWL(433005c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
,I/WVCdm   (  372): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  372): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  372): CdmEngine::OpenSession
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1758): onScreenOff.
I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1758): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1758): disableBatteryAlarm
,I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1758): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1758): onScreenOff
D/PMS     (  913): releaseWL(433005c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/NativeLibraryUtils( 4655): Install completed successfully. count=14 extracted=0
,D/WearableService( 1224): callingUid 10029, callindPid: 1224
,D/LocationInitializer( 2184): Restart initialization of location
,E/MDM     ( 1224): [113] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1356): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1356): Proximity feature is not enabled.
,W/GCoreFlp( 1224): No location to return for getLastLocation()
,W/FusedLocationProvider( 1224): location=null
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  913): acquireWL(43264fa0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): releaseWL(43264fa0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024951
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025043
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025047
,D/WVCdm   (  372): PrepareKeyRequest: nonce=3566862277
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025050
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025054
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026558
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026576
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029785
,D/SmartSyncUtils( 4683): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4683): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4683): isEpsOn(), nState = 0
W/ContextImpl( 4683): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/WifiService(  913): New client listening to asynchronous messages
,I/SensorManager(  913): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42eed360
,W/SensorService(  913): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  913): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  913): pid=913, uid=1000
W/SensorService(  913): Active sensors: size = 1
W/SensorService(  913): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  913): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42eed360, eanble = 0, strlen(mName) = 36
W/SensorService(  913): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  913): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  913): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  913): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  913): pid=913, uid=1000
W/SensorService(  913): Active sensors: size = 0
W/SensorService(  913): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42eed360, eanble = 0, strlen(mName) = 36
W/SensorService(  913): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  913): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  913): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42eed360
W/ContextImpl(  913): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
E/ActivityThread(  913): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42f2bb38 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  913): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42f2bb38 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  913): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  913): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  913): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  913): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  913): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  913): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  913): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  913): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  913): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  913): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  913): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  913): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  913): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  913): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  913): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  913): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  913): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  913): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  913): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  913): 	at dalvik.system.NativeStart.main(Native Method)
,I/WVCdm   (  372): CdmEngine::CloseSession
,W/ActivityManager(  913): Activity pause timeout for ActivityRecord{42c0bd70 u0 com.test.thalitest/.MainActivity t2}
,D/PMS     (  913): releaseWL(44a8b448): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  913): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  913): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  913): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  913): [AlarmQueuing] connectivity wifi: true
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
D/ConnectivityService(  913): getNetworkInfo networkType=1 called by  (913/1000)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
D/PMS     (  913): acquireWL(44b7f970): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 913 1000 null
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
,D/CaptivePortalTracker(  913): NoActiveNetworkState
,V/Tethering(  913): bSetPropertyMultiRAB:false
D/Tethering(  913): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/htcCheckinService(  913): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  913): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,I/Tethering(  913): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
I/Tethering(  913): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
,I/Tethering(  913): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  913): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  913): Found interface wlan0
,D/Tethering(  913): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.setupwizard (4555/10079)
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
,D/AccTypeManager( 1347): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024951
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025043
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025047
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025050
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025054
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026558
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026576
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029785
D/ConnectivityService(  913): getActiveNetworkInfo called by com.htc.musicenhancer (3925/10053)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.backuptransport (1573/10029)
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
,I/ConnectivityHelper( 1273): [onReceive] WIFI(1): CONNECTED
,D/CaptivePortalTracker(  913): DelayedCaptiveCheckState
D/GpsLocationProvider(  913): [handleMessage] UPDATE_NETWORK_STATE
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/GpsLocationProvider(  913): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
D/GpsLocationProvider(  913): getAGpsConnectionInfo connType - 4
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,D/GpsLocationProvider(  913): ignore wifi update if we are not in OPENING or CLOSING
,I/NetworkMonitor( 4347): type=WIFI subType= reason=null isConnected=true
D/PMS     (  913): acquireWL(44a586c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 913 1000 null
D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.htc.launcher (1273/10076)
D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
D/PMS     (  913): releaseWL(44a586c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4526/10027)
D/PMS     (  913): releaseWL(44b7f970): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  913): getNetworkInfo networkType=1 called by com.google.android.music (4347/10154)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.backuptransport (1573/10029)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4526/10027)
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4526/10027)
,W/AccTypeManager( 1347): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1347): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (2729/10021)
D/WifiStateMachine(  913): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  913): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  913): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!,
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0],
E/ExternalAccountType( 1347): Unsupported attribute readOnly
D/WifiStateMachine(  913): [MLHD] enter handleMediaLinkEvent DefaultState
,D/AutoSetting( 1317): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4555): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4555): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1317): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1317): service - onStartCommand() screen is off, don't request location
D/ConnectivityService(  913): getActiveNetworkInfo called by com.htc.sense.hsp (1317/10055)
D/AutoSetting( 1317): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1317): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  913): getActiveNetworkInfo called by com.htc.sense.hsp (1317/10055)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.apps.magazines (4592/10151)
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.apps.plus (4047/10160)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.apps.plus (4047/10160)
,D/PMS     (  913): acquireWL(42e78910): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(42e78910): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I/CheckinService( 2184): Checkin interval check for package: unspecified last checkin: 1452015120289 min interval config: 0 actual interval: 48393
,I/dalvikvm-heap( 4047): Grow heap (frag case) to 13.500MB for 1821008-byte allocation
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2184, uid=10029, userID:0
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1356/10029)
,I/WVCdm   (  372): CdmEngine::OpenSession
,I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  372): PrepareKeyRequest: nonce=1692826084
,I/WVCdm   (  372): CdmEngine::CloseSession
,W/Settings( 4655): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 4655): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4655): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4655): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4655): Local Branch: 
I/Adreno-EGL( 4655): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4655): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4655):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4655): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4655): OpenGL ES Shader Compiler Version: E031.24.02.07,
I/Adreno-EGL( 4655): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4655): Local Branch: 
I/Adreno-EGL( 4655): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4655): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4655):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (4655/10029)
,I/Adreno-EGL( 4655): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4655): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4655): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4655): Local Branch: 
I/Adreno-EGL( 4655): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4655): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4655):                  aa63bbd948f41d15fc72f585e
,I/CheckinRequestBuilder( 2184): Classify the device as Phone.
,D/libc    ( 2184): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2184): [NET] getaddrinfo-,err=8
D/libc    ( 2184): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2184): [NET] getaddrinfo-, 1
,D/libc    ( 2184): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =f56a +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 259
D/libc    (  365): [NET]res_nsend:resplen=84
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2184): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2184): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2184): [NET] getaddrinfo-,err=8
,D/libc    ( 2184): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2184): [NET] getaddrinfo-,err=8
,D/libc    ( 2184): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2184): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2184): Sending checkin request (12081 bytes)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4526/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4526/10027)
,W/fb4a(:<default>):UserScope( 4526): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4526): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4526/10027)
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=5 [17][1][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4526/10027)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4526): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4526/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4526/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4526/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4526/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4526/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4526/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4526/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4526/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4526/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4526/10027)
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4526/10027)
,I/CheckinRequestBuilder( 2184): Checkin reason type: 8 attempt count: 1
D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4526/10027)
I/ActivityManager(  913): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2184): Failed to find provider info for com.google.android.wearable.settings
D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4526/10027)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4526/10027)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4526/10027)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4526/10027)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4526/10027)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4526/10027)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4526/10027)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4526/10027)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4526/10027)
D/ConnectivityService(  913): getActiveNetworkInfo called by com.facebook.katana (4526/10027)
,D/ConnectivityService(  913): getNetworkInfo networkType=9 called by com.google.android.gms (2184/10029)
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [1][0][0]
,I/CheckinRequestBuilder( 2184): Classify the device as Phone.
,I/CheckinTask( 2184): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2184): Checking schedule, now: 1452015170145 next: 1452538107140
,I/CheckinService( 2184): active receiver: disabled
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2184, uid=10029, userID:0
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024256
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024951
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025043
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025047
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025050
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025054
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026558
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026576
,I/CheckinService( 2184): Checking schedule, now: 1452015170169 next: 1452538107140
,I/CheckinService( 2184): active receiver: disabled
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029785
I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2184, uid=10029, userID:0
,D/CheckinService( 2184): Recording last checkin time for package unspecified as 1452015170175
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024951
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025043
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025047
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025050
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025054
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026558
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026576
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029785
,D/PMS     (  913): releaseWL(445ddff0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
,D/PMS     (  913): acquireWL(42fec078): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 1356): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    ( 1356): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1356): [NET] getaddrinfo-,err=8
D/libc    ( 1356): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1356): [NET] getaddrinfo-, 1
D/libc    ( 1356): [NET] getaddrinfo_proxy+
,D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =54e4 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1356/10029)
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 234
,D/libc    (  365): [NET]res_nsend:resplen=79
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1356): [NET] getaddrinfo_proxy-, success,
,D/libc    ( 1356): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1356): [NET] getaddrinfo-,err=8
,D/libc    ( 1356): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1356): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1356/10029)
,D/PMS     (  913): acquireWL(444fbb68): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1356/10029)
,D/PMS     (  913): releaseWL(42fec078): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  913): reportInetCondition for net 1, percentage: 100 by  (1356/10029)
D/ConnectivityService(  913): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  913): handleInetConditionChange: starting a change hold
,D/PMS     (  913): releaseWL(444fbb68): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(44ac8388): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  913): reportInetCondition for net 1, percentage: 100 by  (1356/10029)
,D/ConnectivityService(  913): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  913): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  913): reportInetCondition for net 1, percentage: 100 by  (1356/10029)
,D/ConnectivityService(  913): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  913): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1356/10029)
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024256
,D/libc    (  913): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  913): [NET] getaddrinfo-,err=8
D/libc    (  913): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  913): [NET] getaddrinfo-, 1
,D/libc    (  913): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =f6f0 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024951
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025043
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025047
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025050
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025054
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026558
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026576
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029785
D/PMS     (  913): releaseWL(44ac8388): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
,D/libc    (  365): [NET]res_nsend:resplen=172
D/libc    (  365): [NET]res_queryN: exit 3, ancount=4
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  913): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  913): Find DNS Address www.htc.com/104.81.130.175
,D/PMS     (  913): releaseWL(4418edd0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/ConnectivityService(  913): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  913): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  913): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [12][0][0]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,I/GAV2    ( 4592): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 4472): Test app app.js loaded
I/jxcore-log( 4472): 
,I/Choreographer( 4472): Skipped 509 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4472): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
W/ResourceType( 4472): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4472): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{4241e1f0 VFEDH.C. .F....ID 0,0-720,1134 #64}
D/PMS     (  913): releaseWL(43c10630): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/Process (  913): killProcessQuiet, pid=4313
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 4313:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  913): Recipient 4313
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ContactMessageStore( 1244): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1244): MSG_NOTIFY_CS_TO_SYNC <<
,D/AutoSetting( 1507): service - handleMessage() stop self
,D/AutoSetting( 1507): service - onDestroy() END
,D/AutoSetting( 1507): service - handleMessage() quit looper
,I/ActivityManager(  913): Killing 4368:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/Process (  913): killProcessQuiet, pid=4368
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  913): Recipient 4368
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  913): Client connection lost with reason: 4
,I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1347): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  913):   Scheme: "sms"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/ActivityManager(  913): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4738 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1273): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  913):   Scheme: "smsto"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  913):   Scheme: "mms"
,I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/Launcher( 1273): Deferring update until onResume
D/Launcher( 1273): waitUntilResume // bindAppsUpdated
,W/AccTypeManager( 1347): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1347): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
W/SystemReader( 1256): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "mmsto"
,I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  913):   Scheme: "sms"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  913):   Scheme: "smsto"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  913):   Scheme: "mms"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  913):   Scheme: "mmsto"
,E/ExternalAccountType( 1347): Unsupported attribute readOnly
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,D/PhoneApp( 1244): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4738): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4738): MmsConfig.loadMmsSettings
,W/dalvikvm( 4738): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4738): VFY: unable to resolve instance field 36
,W/dalvikvm( 4738): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4738): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/ActivityManager(  913): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4761 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4738, uid=10111, userID:0
,W/Settings( 4738): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4738, uid=10111, userID:0
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4738, uid=10111, userID:0
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4738, uid=10111, userID:0
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4738, uid=10111, userID:0
,I/PackageManager(  913):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4738, uid=10111, userID:0
,D/MessageFrequencyProvider( 4761): onCreate
D/PMS     (  913): acquireWL(44a08f68): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4738 10111 null
,D/MmsCustomizationProvider( 4761): query uri: content://htc-mms-customization/mms-ua/ua_string
,V/GetPrviateResource( 4761): GetPrviateResource
,V/GetPrviateResource( 4761): GetPrviateResource
,I/[PluginManager]RegisterService( 1317): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1317): handle notify Blinkfeed plugin client changed
,I/IcingCorporaProvider( 2826): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/MmsCustomizationProvider( 4761): query uri: content://htc-mms-customization/mms-ua/ua_profile
,D/PMS     (  913): acquireWL(441bf2a0): PARTIAL_WAKE_LOCK  AsyncService 0x1 4047 10160 null
,I/ActivityManager(  913): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/Babel   ( 4738): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4738): MmsConfig.loadFromDatabase
D/PMS     (  913): acquireWL(44038288): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,I/dalvikvm-heap( 4047): Grow heap (frag case) to 15.200MB for 1821008-byte allocation
D/PMS     (  913): releaseWL(441bf2a0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,E/Babel   ( 4738): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4738): MmsConfig.loadFromResources
,I/dalvikvm-heap( 4047): Grow heap (frag case) to 16.935MB for 1821008-byte allocation
,E/Babel   ( 4738): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4738): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/ProviderInstaller( 4738): Installed default security provider GmsCore_OpenSSL
,D/MessageCustFlag( 4761): sense_version=6.0
,D/BTAccessoryUtil( 4761): createReceiver
D/PMS     (  913): releaseWL(44a08f68): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  913): Resuming delayed broadcast
D/BTAccessoryUtil( 4761): registerReceiver return intent = null
D/MessageCustFlag( 4761): sku_id=99
W/SystemReader( 4761): Cannot find message_ambs_application_id, use default value instead
,D/Messaging( 4761): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4761): networkCode: 
,D/MessageCustFlag( 4761): sku_id=99
D/MmsConfig( 4761): SIE smsPri: null
,D/MmsConfig( 4761): networkCode: 
,D/Process (  913): killProcessQuiet, pid=3846
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  913): Killing 3846:com.htc.mediamanager/u0a34 (adj 15): empty #17
D/HtcTelephonyCapability( 4761): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 4761): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4761): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4761): Cannot find qct_8960_interface, use default value instead
,D/PackageBroadcastService( 2184): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/ActivityManager(  913): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/PackageBroadcastService( 2184): Null package name or gms related package.  Ignoreing.
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  913): Recipient 3846
,I/Icing   ( 2184): updateResources: need to parse f{com.google.android.gms}
I/ActivityManager(  913): Resuming delayed broadcast
,W/PackageManager(  913): Unable to load service info ResolveInfo{4419be38 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  913): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  913): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  913): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  913): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  913): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  913): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  913): 	,at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  913): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  913): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  913): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  913): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  913): 	at dalvik.system.NativeStart.main(Native Method)
,D/RemoteDisplayProvider(  913): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  913): start
,I/GCoreNlp( 1224): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  913): applying state to connected service
D/PMS     (  913): acquireWL(444dbe68): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): releaseWL(444dbe68): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  913): applying state to connected service
,D/PMS     (  913): acquireWL(43ba7838): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(43ba7838): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(440a0b18): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(440a0b18): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2826): UpdateCorporaTask done [took 444 ms] updated apps [took 444 ms] 
,D/CaptivePortalTracker(  913): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  913): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  913): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@424a4e18 +
,I/Prism.WidgetManager( 1273): onLoadItems() +
,I/Icing   ( 2184): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2184): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  913): releaseWL(44038288): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1273): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1273): onLoadItems() -
,I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@424a4e18 -
,D/PhoneApp( 1244): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1244): -- N1 =0
,D/PhoneApp( 1244): -- N2 =0
,D/PhoneApp( 1244): -- N3 =0
,D/PMS     (  913): acquireWL(446680f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{42554c20: PendingIntentRecord{42848038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=118660, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(446680f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Messaging( 4761): mNeedToUpdateDate2 start
,D/MmsConfig( 4761): packageName: com.htc.vvm.att does not exist
D/ReportIndicatorCache( 4761): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4761): 
D/MmsAsyncWorkHandler( 4761): HM tk = 20001
,D/ReportIndicatorCache( 4761): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4761): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@42422728
,I/Messaging( 4761): mccmnc> 
D/DraftCache( 4761): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4761): [DraftCache/1] refresh
,D/MmsConfig( 4761): networkCode: 
D/Messaging( 4761): ViewCache CreatePreloadOnlyConversationList
D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
D/MmsSmsV2Provider( 1244):  phoneType = -1
,D/MmsSmsV2Provider( 1244): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MmsSmsV2Provider( 1244):  phoneType = -1
,D/MmsSmsV2Provider( 1244): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/PhoneStorageUtil( 4761): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4761): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4761): createReceiver
,D/MessageCustFlag( 4761): sense_version=6.0
,D/Messaging( 4761): mNeedToUpdateDate2: false
,D/Jerry   ( 4761): start to preload cursor >>>>>>>
,D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/MmsSmsV2Provider( 1244):  phoneType = -1
,D/TelephUtils( 1244): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,V/MmsProvider( 1244): Update uri=content://mms, match=0
,V/MmsProvider( 1244): selection=st=129 AND m_type!=134
,D/Messaging( 4761): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4761): TransactionService is going to be woken up.
V/TransactionService( 4761): 1-Creating TransactionService
D/Messaging( 4761): ViewCache CreatePreload
,D/Messaging( 4761): ViewCache CreatePreloadOnlyMultipleOpsList
,V/TransactionService( 4761): onStartCommand: 1
D/MmsSystemEventReceiver( 4761): unRegisterForConnectionStateChanges
,D/Cust_MMSMS( 4761): _has_set_default_values_2=true
V/TransactionService( 4761): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4761): Loading previous transactions.
,D/MsgPreferenceUtils( 4761): def_index: 0
,D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1244): device_type: 1
,D/MsgPreferenceUtils( 4761): globalIndex = 1
D/MsgPreferenceUtils( 4761): phone state: true
D/MsgPreferenceUtils( 4761): sd state: false
,D/MsgPreferenceUtils( 4761): vIndex = 0
,D/TransactionService( 4761): Force set service start id to 1
V/TransactionService( 4761): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4761): unRegisterForConnectionStateChanges
,D/TransactionService( 4761): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4761): Destroying TransactionService
,V/TransactionService( 4761): 4-Handling incoming message: { when=-3ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/MmsSmsV2Provider( 1244):  phoneType = -1
,D/MmsSmsV2Provider( 1244): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1244): sku_id=99
,D/DraftCache( 4761): [DraftCache/475] rebuildCache
,D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/MmsSmsV2Provider( 1244):  phoneType = -1
,D/MmsSmsV2Provider( 1244): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 4761): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/Jerry   ( 1244): URI_DRAFT
,D/DraftCache( 4761): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 4761): [DraftCache/475] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4761): 
D/MmsAsyncWorkHandler( 4761): HM tk = 20002
D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1244): sku_id=99
,D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1244): sku_id=99
,D/Process (  913): killProcessQuiet, pid=3925
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 3925:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  913): Recipient 3925
,I/GAV4    ( 4738): Thread[GAThread,5,main]: No campaign data found.
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  913): acquireWL(43335c68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  913): onReceive BATTERY_CHANGED
,D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
I/BatteryService(  913): n_update end
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
D/PMS     (  913): releaseWL(43335c68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  913): acquireWL(4455db80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  913): sending alarm PendingIntent{42f99dc8: PendingIntentRecord{42fa8b60 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=126312, Int=0
,V/AlarmManager(  913): sending alarm PendingIntent{4285be70: PendingIntentRecord{42af4690 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=136907, Int=0
,D/PMS     (  913): acquireWL(43337a40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1356/10029)
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [14][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0,
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50,
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,D/PMS     (  913): acquireWL(44a04cf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(43337a40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(44a04cf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(4455db80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1356/10029)
,D/PMS     (  913): acquireWL(43414c60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024951
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025043
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025047
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025050
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025054
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026558
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026576
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029785
,D/PMS     (  913): releaseWL(43414c60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(44609a98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1356/10029)
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024951
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025043
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025047
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025050
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025054
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026558
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026576
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029785
,D/PMS     (  913): acquireWL(44a1ef70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(4419f2e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1224): Vacuum at: now=1452015198629 tag=VacuumService
,D/PMS     (  913): releaseWL(44609a98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(44a1ef70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(44b7f970): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1356/10029)
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024951
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025043
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025047
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025050
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025054
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026558
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026576
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029785
,D/AutoSetting( 1317): service - has update message, not stop
,D/AutoSetting( 1317): service - mHandler: update timezone
,D/AutoSetting( 1507): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
D/PMS     (  913): releaseWL(44b7f970): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): acquireWL(44b27048): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
W/ActivityManager(  913): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1507): service - onCreate()
D/AutoSetting( 1507): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1507): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/AutoSetting( 1507): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
D/PMS     (  913): releaseWL(4419f2e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024951
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025043
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025047
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025050
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025054
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026558
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026576
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029785
D/PMS     (  913): releaseWL(44b27048): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1562): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1562): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,D/AutoSetting( 1507): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1507): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1507): service - mHandler: update timezone
W/ActivityManager(  913): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
V/NotificationService(  913): batLight: Full, plugged
V/LightsService(  913): setLight #8: color=#c8c800
D/qdlights(  913): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  913): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  913): setLight #8: color=#c800
D/qdlights(  913): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  913): [LedInfo] has indicator attribute
D/qdlights(  913): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  913): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  913): acquireWL(44a83f08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1356/10029)
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024951
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025043
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025047
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025050
D/AutoSetting( 1507): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1507): service - processTimeZoneID() system nitz is valid: false (false)
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025054
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026558
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026576
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029785
,D/AutoSetting( 1507): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1507): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1562): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1562): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1115): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{427b5b38 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/PMS     (  913): acquireWL(449fec80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
I/RemoteViews.Performance( 1115): com.htc.htclocationservice 2 6 3 11
,D/PMS     (  913): releaseWL(44a83f08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(449e5fd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(449fec80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024256
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024951
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025043
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025047
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025050
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025054
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026558
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026576
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029785
,D/PMS     (  913): releaseWL(449e5fd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(4465b760): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024256
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024951
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025043
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025047
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025050
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025054
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026558
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026576
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029785
,D/PMS     (  913): releaseWL(4465b760): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(4465a958): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  913): getActiveNetworkInfo called by  (1356/10029)
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024951
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025043
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025047
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025050
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025054
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026558
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026576
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029785
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [1][0][0]
D/PMS     (  913): releaseWL(4465a958): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/ContactMessageStore( 1244): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1244): MSG_NOTIFY_CS_TO_SYNC <<
,W/ContextImpl(  913): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/ActivityManager(  913): Waited long enough for: ServiceRecord{44a856e0 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  913): acquireWL(44509440): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(44509440): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  913): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
,I/HtcPowerSaver(  913): >> updateStatus
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 1317): service - handleMessage() stop self
,D/AutoSetting( 1507): service - handleMessage() stop self
,D/AutoSetting( 1317): service - onDestroy() END
,D/AutoSetting( 1317): service - handleMessage() quit looper
,D/Process (  913): killProcessQuiet, pid=4398
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 4398:com.htc.calendar/u0a13 (adj 15): empty #17
,D/AutoSetting( 1507): service - onDestroy() END
,D/AutoSetting( 1507): service - handleMessage() quit looper
,D/Process (  913): killProcessQuiet, pid=4412
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  913): Killing 4412:com.android.settings:remote/1000 (adj 15): empty #17
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  913): Recipient 4412
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,I/ActivityManager(  913): Recipient 4398
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  913): acquireWL(43ea8b08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{42554c20: PendingIntentRecord{42848038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=178660, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(43ea8b08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000},
,D/TelephonyReceiver( 1244): switchBindHtcMsgCursor: null
,D/PMS     (  913): acquireWL(43c09c28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
,D/UsbnetService(  913): onReceive BATTERY_CHANGED
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/BatteryService(  913): n_update end
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  913): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  913): releaseWL(43c09c28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  913): acquireWL(42fe58f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{10027}
,V/AlarmManager(  913): sending alarm PendingIntent{43c69d18: PendingIntentRecord{4453e4c8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=226436, Int=0
,I/ActivityManager(  913): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4831 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  913): sending alarm PendingIntent{42e9a730: PendingIntentRecord{42f3e860 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452015273513, Int=10800000
,D/PMS     (  913): releaseWL(42fe58f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.htc.aurora (4831/10049)
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024951
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025043
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025047
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025050
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025054
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026558
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026576
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029785
,D/PMS     (  913): acquireWL(42e8bdd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{10027}
,V/AlarmManager(  913): sending alarm PendingIntent{433cb350: PendingIntentRecord{4439f208 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=226443, Int=120000
,V/AlarmManager(  913): sending alarm PendingIntent{42ca2b08: PendingIntentRecord{4453e4c8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=226597, Int=0
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024951
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025043
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025047
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025050
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025054
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026558
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026576
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029785
,D/PMS     (  913): releaseWL(42e8bdd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/Process (  913): killProcessQuiet, pid=4119
,D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  913): Killing 4119:com.google.android.gm/u0a107 (adj 15): empty #17
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  913): Recipient 4119
,D/PMS     (  913): acquireWL(42d54530): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/PMS     (  913): releaseWL(42d54530): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  913): acquireWL(429e2fa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{42554c20: PendingIntentRecord{42848038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=238659, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(429e2fa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  913): acquireWL(426638d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
,D/UsbnetService(  913): onReceive BATTERY_CHANGED
,D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  913): releaseWL(426638d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  913): updateBatteryInfo
D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  913): acquireWL(42551670): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(42551670): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  913): acquireWL(42d68cd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{42554c20: PendingIntentRecord{42848038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=298660, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(42d68cd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  913): acquireWL(42a68ff0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(42a68ff0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  913): acquireWL(42f17590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): releaseWL(42f17590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  913): acquireWL(42f5d8b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{42554c20: PendingIntentRecord{42848038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=358660, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(42f5d8b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(42f22fc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(42f22fc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 4472): TAP version 13
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # setup
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # multiplex can send data
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # teardown
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): ok 1 String should be length:200
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # setup
I/jxcore-log( 4472): 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 4472): # basic
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # teardown
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): ok 2 sane
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # setup
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # another
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # teardown
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): ok 3 sane
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # setup
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # teardown
I/jxcore-log( 4472): 
,D/PMS     (  913): acquireWL(43fbeac0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(43fbeac0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
,I/HtcPowerSaver(  913): >> updateStatus
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4472): ok 4 should be equal
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): ok 5 null
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): ok 6 (unnamed assert)
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): ok 7 should be equal
I/jxcore-log( 4472): 
I/jxcore-log( 4472): ok 8 should not throw
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # setup
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # teardown
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): ok 9 (unnamed assert)
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): ok 10 (unnamed assert)
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): ok 11 should not throw
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): ok 12 should be equal
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): ok 13 should be equal
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # setup
I/jxcore-log( 4472): 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 4472): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 4472): 
,D/PMS     (  913): acquireWL(42ddac90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{42554c20: PendingIntentRecord{42848038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=418660, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(42ddac90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4472): # teardown
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): ok 14 should be equal
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # setup
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # failed to get mobile documents path
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # teardown
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): ok 15 should be equal
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # setup
I/jxcore-log( 4472): 
,D/PMS     (  913): acquireWL(43fbe7b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(43fbe7b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  913): updateBatteryInfo
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4472): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # teardown
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): ok 16 should be equal
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): ok 17 should be equal
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): ok 18 should be equal
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # setup
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # #init should register the networkChanged event
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # teardown
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): ok 19 should be equal
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # setup
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # #startBroadcasting should throw on null device name
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # teardown
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): ok 20 should throw
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # setup
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # teardown
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): ok 21 should throw
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # setup
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # #startBroadcasting should throw on non-number port
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # teardown
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): ok 22 should throw
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # setup
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # #startBroadcasting should throw on NaN port
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # teardown
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): ok 23 should throw
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # setup
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # #startBroadcasting should throw on negative port
I/jxcore-log( 4472): 
,D/PMS     (  913): acquireWL(42cc2880): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(42cc2880): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  913): updateBatteryInfo
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 4472): # teardown
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): ok 24 should throw
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # setup
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # #startBroadcasting should throw on too large port
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # teardown
I/jxcore-log( 4472): 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  913): acquireWL(42fb4510): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{42554c20: PendingIntentRecord{42848038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=478660, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(42fb4510): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4472): ok 25 should throw
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # setup
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # teardown
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): ok 26 should be equal
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): ok 27 should be equal
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): ok 28 should be equal
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # setup
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 4472): 
,D/PMS     (  913): acquireWL(42eacf18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  913): releaseWL(42eacf18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  913): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 4472): # teardown
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): ok 29 should be equal
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): ok 30 should be equal
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): ok 31 should be equal
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # setup
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # teardown
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): ok 32 should be equal
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): ok 33 should be equal
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # setup
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # teardown
I/jxcore-log( 4472): 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 4472): ok 34 should be equal
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): ok 35 should be equal
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # setup
I/jxcore-log( 4472): 
,D/PMS     (  913): acquireWL(42f99478): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{4264cc28: PendingIntentRecord{42e0abe0 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=514662, Int=0
,D/PMS     (  913): acquireWL(42f5cfe8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 913 1000 null
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (913/1000)
,D/PMS     (  913): releaseWL(42f99478): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(43a60030): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 913 1000 null
,D/PMS     (  913): releaseWL(42f5cfe8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  913): releaseWL(43a60030): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/jxcore-log( 4472): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # teardown
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): ok 36 should be equal
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): ok 37 should be equal
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): ok 38 should be equal
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # setup
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # teardown
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): ok 39 should be equal
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): ok 40 should be equal
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # setup
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # should call Mobile("Disconnect") without an error
I/jxcore-log( 4472): 
,D/PMS     (  913): acquireWL(42f0c228): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{10027}
,V/AlarmManager(  913): sending alarm PendingIntent{4286af10: PendingIntentRecord{4439f208 com.facebook.katana broadcastIntent}}, i=com.facebook.push.mqtt.KeepaliveManager.ACTION_INEXACT_ALARM.com.facebook.katana, t=2, cnt=1, w=526603, Int=300000
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024256
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024951
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025043
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025047
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025050
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025054
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026558
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026576
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029785
,D/PMS     (  913): releaseWL(42f0c228): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,I/jxcore-log( 4472): # teardown
I/jxcore-log( 4472): 
,D/PMS     (  913): acquireWL(44a1dfc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/PMS     (  913): releaseWL(44a1dfc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4472): ok 41 should be equal
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): ok 42 should be equal
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # setup
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 4472): 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  913): acquireWL(42f13470): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{42554c20: PendingIntentRecord{42848038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=538660, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(42f13470): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4472): # teardown
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): ok 43 should be equal
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): ok 44 should be equal
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # setup
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 4472): 
,I/jxcore-log( 4472): # teardown
I/jxcore-log( 4472): 
,W/dalvikvm( 4472): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4472): threadid=1: thread exiting with uncaught exception (group=0x41fe1e30)
,E/AndroidRuntime( 4472): FATAL EXCEPTION: main
E/AndroidRuntime( 4472): Process: com.test.thalitest, PID: 4472
E/AndroidRuntime( 4472): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4472): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4472): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4472): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4472): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4472): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:93)
E/AndroidRuntime( 4472): 	at io.jxcore.node.JXcoreExtension$5.Receiver(JXcoreExtension.java:155)
E/AndroidRuntime( 4472): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4472): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4472): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4472): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4472): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4472): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4472): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4472): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4472): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4472): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4472): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4472): 	at dalvik.system.NativeStart.main(Native Method)
,E/ActivityManager(  913): App crashed! Process: com.test.thalitest
W/ActivityManager(  913):   Force finishing activity com.test.thalitest/.MainActivity
,D/Process (  913): killProcessQuiet, pid=4443
,I/ActivityManager(  913): Killing 4443:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
D/Process ( 4472): killProcess, pid=4472
D/Process ( 4472): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  913): Recipient 4443
,W/InputDispatcher(  913): channel '44a0f558 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  913): channel '44a0f558 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  913): Attempted to unregister already unregistered input channel '44a0f558 com.test.thalitest.MainActivity (s)'
I/WindowManager(  913): WINDOW DIED Window{44a0f558 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager(  913): Recipient 4472
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  913): Process com.test.thalitest (pid 4472) has died.
D/WifiService(  913): Client connection lost with reason: 4
,W/WindowManager(  913): Failed looking up window
W/WindowManager(  913): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@449f80a0 does not exist
W/WindowManager(  913): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8463)
W/WindowManager(  913): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8454)
W/WindowManager(  913): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1052)
W/WindowManager(  913): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/WindowManager(  913): 	at dalvik.system.NativeStart.run(Native Method)
,I/WindowState(  913): WIN DEATH: null
,W/InputMethodManagerService(  913): Got RemoteException sending setActive(false) notification to pid 4472 uid 10389
,W/Binder  ( 1210): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1210): java.lang.NullPointerException
W/Binder  ( 1210): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1210): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1210): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1210): 	at dalvik.system.NativeStart.run(Native Method)
,D/PMS     (  913): acquireWL(42d9a040): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(42d9a040): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  913): updateBatteryInfo
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(4429efc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(4429efc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  913): acquireWL(42fbccb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{42554c20: PendingIntentRecord{42848038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=598660, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(42fbccb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(445f4798): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PMS     (  913): releaseWL(445f4798): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  352): inotify_add_watch failed. (No such file or directory),
,D/ContactMessageStore( 1244): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1244): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1244): sku_id=99
,D/ContactMessageStore( 1244): start background delete task...
,D/ContactMessageStore( 1244): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1244): size: 0 , 0
,D/ContactMessageStore( 1244): Background delete complete
,D/PMS     (  913): acquireWL(42e80aa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(42e80aa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  913): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(441bc4b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{42554c20: PendingIntentRecord{42848038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=658660, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(441bc4b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(42f252c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(42f252c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  913): acquireWL(445ae0c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{42554c20: PendingIntentRecord{42848038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=718660, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(445ae0c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(42fe3f10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/PMS     (  913): releaseWL(42fe3f10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  913): updateBatteryInfo
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(42ef36f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{42554c20: PendingIntentRecord{42848038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=778660, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(42ef36f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(4429d470): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(4429d470): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  913): acquireWL(42f526d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{42554c20: PendingIntentRecord{42848038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=838660, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(42f526d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(448708f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): releaseWL(448708f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(44185df8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(44185df8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  913): acquireWL(42fb0c00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{42554c20: PendingIntentRecord{42848038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=898660, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(42fb0c00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(44517f80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
,D/PMS     (  913): releaseWL(44517f80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  913): updateBatteryInfo
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(42fbd930): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,D/ConnectivityService(  913): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  913): sending alarm PendingIntent{42673220: PendingIntentRecord{42da3ce0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=786517, Int=0
,V/AlarmManager(  913): sending alarm PendingIntent{43bd4058: PendingIntentRecord{42fe3570 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1452015735339, Int=1800000
,V/AlarmManager(  913): sending alarm PendingIntent{428f01f0: PendingIntentRecord{42ca4fe8 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452015993850, Int=900000
,D/PMS     (  913): acquireWL(441b0550): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  913): Done.
,D/ConnectivityService(  913): Setting timer for 720seconds
,W/ContextImpl( 4683): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4683): call getInstance()
D/PMS     (  913): releaseWL(42fbd930): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PowerUsageList:PowerUsageHelper( 4683): MY_DEBUG = false
D/PMS     (  913): acquireWL(42f9b1a0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  913): releaseWL(441b0550): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/EventLogService( 2184): Aggregate from 1452015167591 (log), 1452013935275 (data)
W/BatSI   (  913): Couldn't get kernel wake lock stats
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024256
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024951
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025043
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025047
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025050
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025054
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026558
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026576
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029785
,D/PMS     (  913): releaseWL(42f9b1a0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,W/BatSI   (  913): Couldn't get kernel wake lock stats
,W/BatSI   (  913): Couldn't get kernel wake lock stats
,W/BatSI   (  913): Couldn't get kernel wake lock stats
,D/PMS     (  913): acquireWL(44be5d38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(44be5d38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  913): acquireWL(44ba5858): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{42554c20: PendingIntentRecord{42848038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=958660, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(44ba5858): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(44b7f970): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(44b7f970): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
,D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(44a7dad8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,D/SmartSyncUtils( 4683): isEpsOn(), nState = 0
V/AlarmManager(  913): sending alarm PendingIntent{4283d878: PendingIntentRecord{444b0920 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1452016068326, Int=0
,D/PMS     (  913): releaseWL(44a7dad8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(44a6e918): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4683 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4683): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4683): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4683): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4683): SettingOnTime = 1452060000000, randomSettingOnTime = 1452057803000
,D/SmartSyncScreenOnOffTimeReceiver( 4683): SettingOffTime = 1452045600000, randomSettingOffTime = 1452049734000
,D/SmartSyncScreenOnOffTimeReceiver( 4683): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4683): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4683): bNightModeTurnOffOnce = false
,D/PMS     (  913): releaseWL(44a6e918): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  913): acquireWL(44a65828): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
,D/UsbnetService(  913): onReceive BATTERY_CHANGED
I/BatteryService(  913): n_update end
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  913): releaseWL(44a65828): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(44a27460): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  913): sending alarm PendingIntent{44a7d928: PendingIntentRecord{42dd8aa0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1009161, Int=0
,D/PMS     (  913): acquireWL(44a26fe8): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(44a26fe8): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(44a26ce8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(44a27460): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1356/10029)
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=7 [289][23][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024951,
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025043
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025047
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025050
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025054
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026558
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026576
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029785
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,D/PMS     (  913): acquireWL(44a07f08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): releaseWL(44a26ce8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [1][0][0]
I/wpa_supplicant( 1157): Change stage from stage0 to stage3
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1224): Scheduling Phenotype for one-off execution 7111 seconds from now (1452016071001)
,D/GetConfigurationSnapshotOperation( 1224): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1224): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1224): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1224): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1224): VFY: unable to find class referenced in signature (Landroid/net/Network;),
W/dalvikvm( 1224): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1224): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  913): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=100 [1][1][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
,W/dalvikvm( 1224): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,D/libc    ( 1224): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1224): [NET] getaddrinfo-,err=8
D/libc    ( 1224): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1224): [NET] getaddrinfo-, 1
,D/libc    ( 1224): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =c90a +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE,
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 191
,D/libc    (  365): [NET]res_nsend:resplen=87
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
,D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1224): [NET] getaddrinfo_proxy-, success
,D/PMS     (  913): acquireWL(42e53748): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  913): reportInetCondition for net 1, percentage: 100 by  (1356/10029)
D/ConnectivityService(  913): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  913): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1356/10029)
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024951
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025043
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025047
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025050
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025054
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026558
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026576
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029785
,D/PMS     (  913): releaseWL(42e53748): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    ( 1224): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1224): [NET] getaddrinfo-,err=8
D/libc    ( 1224): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1224): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  913): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=5 [17][1][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,D/ConnectivityService(  913): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,D/PMS     (  913): releaseWL(44a07f08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(42d8c3c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024256
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024951
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025043
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025047
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025050
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025054
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026558
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026576
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029785
,D/PMS     (  913): releaseWL(42d8c3c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  913): acquireWL(4283aa40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  913): getActiveNetworkInfo called by  (1356/10029)
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=50 [2][1][0]
D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360024951
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025043
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025047
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025050
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360025054
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026558
W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360026576
,W/AlarmManager(  913): Converted elapesd time is over 1 year! when = 315360029785
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,D/PMS     (  913): releaseWL(4283aa40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  913): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  913): sendGeneralBroadcast, restrictEnable=false
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  913): doString: SIGNAL_POLL
,W/WifiHW  (  913): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1157): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  913): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1157): nl80211: survey data missing!
E/wpa_supplicant( 1157): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1157): environment dirty rate=0 [0][0][0]
,D/PMS     (  913): acquireWL(42ea5800): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{42554c20: PendingIntentRecord{42848038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1018660, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(42ea5800): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(42cbb3b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(42cbb3b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  913): acquireWL(4418e2a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  913): n_update end
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
,D/PMS     (  913): releaseWL(4418e2a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(43a98db8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{42554c20: PendingIntentRecord{42848038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1078659, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(43a98db8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(42f5d8f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(42f5d8f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  913): acquireWL(42e69e90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(42e69e90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED,
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  913): updateBatteryInfo
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(441a4498): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{42554c20: PendingIntentRecord{42848038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1138660, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1273): Grow heap (frag case) to 12.641MB for 50416-byte allocation
,D/PMS     (  913): releaseWL(441a4498): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(42f1d398): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
,D/PowerUI ( 1115): closing low battery warning: level=100
D/UsbnetService(  913): onReceive BATTERY_CHANGED
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  913): BroadcastReceiver::onReceive-
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  913): releaseWL(42f1d398): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(42ee7330): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{42554c20: PendingIntentRecord{42848038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1198659, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(42ee7330): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(444b12b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/BatteryService(  913): n_update end
D/HtcPowerSaver(  913): updateBatteryInfo
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  913): releaseWL(444b12b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  352): inotify_add_watch failed. (No such file or directory),
,D/PMS     (  913): acquireWL(42fcdd18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(42fcdd18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(43040178): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{42554c20: PendingIntentRecord{42848038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1258660, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(43040178): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(42e57f38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
,I/BatteryService(  913): n_update end
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): releaseWL(42e57f38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(42ed84a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{42554c20: PendingIntentRecord{42848038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1318660, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(42ed84a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(42c603a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(42c603a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(4400a710): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(4400a710): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  913): updateBatteryInfo
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(445e5c20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{42554c20: PendingIntentRecord{42848038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1378660, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(445e5c20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(4301fa78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(4301fa78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  913): acquireWL(42e40af0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
V/AlarmManager(  913): sending alarm PendingIntent{42554c20: PendingIntentRecord{42848038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1438660, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(42e40af0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(42f68d00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
,D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): releaseWL(42f68d00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(42f0fb50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(42f0fb50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  913): acquireWL(44addb88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{42554c20: PendingIntentRecord{42848038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1498660, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(44addb88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(43042708): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(43042708): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(42e45a18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{42554c20: PendingIntentRecord{42848038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1558660, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(42e45a18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(4300c160): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(4300c160): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  913): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
,I/HtcPowerSaver(  913): >> updateStatus
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(44468098): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{42554c20: PendingIntentRecord{42848038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1618660, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(44468098): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(42dd8080): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(42dd8080): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
D/UsbnetService(  913): BroadcastReceiver::onReceive+
,D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  913): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(441c9c10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(441c9c10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(42dae730): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{42554c20: PendingIntentRecord{42848038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1678660, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(42dae730): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(4425e248): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  913): n_update end
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  913): BroadcastReceiver::onReceive+
,D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/PMS     (  913): releaseWL(4425e248): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(44015ee0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  913): n_update end
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/PMS     (  913): releaseWL(44015ee0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,D/PowerUI ( 1115): closing low battery warning: level=100
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(42d54690): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{42554c20: PendingIntentRecord{42848038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1738660, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(42d54690): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  913): acquireWL(43a087c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(43a087c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  913): updateBatteryInfo
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(42f18f58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(42f18f58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  913): updateBatteryInfo
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  913): acquireWL(430470c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
,V/AlarmManager(  913): sending alarm PendingIntent{42554c20: PendingIntentRecord{42848038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1798660, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  913): releaseWL(430470c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  913): Couldn't get kernel wake lock stats
,D/PMS     (  913): acquireWL(44628ae0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(44628ae0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  913): updateBatteryInfo
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  913): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  352): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  913): acquireWL(42f98630): PARTIAL_WAKE_LOCK  AlarmManager 0x1 913 1000 WorkSource{1000}
V/AlarmManager(  913): sending alarm PendingIntent{42554c20: PendingIntentRecord{42848038 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1858660, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,I/ProcessStatsService(  913): Prepared write state in 37ms
,D/PMS     (  913): releaseWL(42f98630): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  913): Pruning old procstats: /data/system/procstats/state-2016-01-05-02-51-22.bin
,D/PMS     (  913): acquireWL(44a54518): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  913): n_update end
,D/PMS     (  913): releaseWL(44a54518): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  913): BroadcastReceiver::onReceive+
D/UsbnetService(  913): onReceive BATTERY_CHANGED
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  913):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  913): BroadcastReceiver::onReceive-
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  913): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  913): runPSCheck
D/HtcPowerSaver(  913): Checking...
I/HtcPowerSaver(  913): >> updateStatus
,I/HtcPowerSaver(  913): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  913): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4920): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4920): ====startRecUseTime====
D/htc.customization.log.level( 4920):  is 
W/CustomizationLogLevel( 4920): Level value is invalid, use default level 2
D/CustomizationManager( 4920):  Read ACC file spent 0.110 (s)
D/CIDMapFileReader( 4920): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4920): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4920): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4920): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4920): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4920): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4920): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4920): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4920): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4920): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4920): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4920): Parsing tag category name = system
I/CustomizationCIDLoader( 4920): Parsing tag category name = application
I/CustomizationCIDLoader( 4920): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4920): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4920): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4920): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4920): Parsing tag category name = Settings
D/CustomizationManager( 4920):  Read CID file spent 0.161 (s)
D/CustomizationManager( 4920):  All configurations done spent 0.162 (s)
W/HtcNativeFlag( 4920): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4920): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4920): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4920): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  913): deletePackageAsUser: pkg=com.test.thalitest, pid=4920, uid=2000 user=0
I/ActivityManager(  913): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  913): killProcessQuiet, pid=4592
D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  913): Killing 4592:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1803s
D/Process (  913): killProcessQuiet, pid=4569
D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  913): killProcessQuiet, pid=4555
D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  913): killProcessQuiet, pid=4347
D/Process (  913): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  913): Killing 4569:com.android.chrome/u0a96 (adj 15): empty for 1803s
I/ActivityManager(  913): Killing 4555:com.google.android.setupwizard/u0a79 (adj 15): empty for 1803s
I/ActivityManager(  913): Killing 4347:com.google.android.music:main/u0a154 (adj 15): empty for 1803s
I/ActivityManager(  913): Recipient 4569
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  913): Recipient 4555
W/asset   (  913): Copying FileAsset 0x676ec940 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  913): Recipient 4592
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/PackageSettings(  913): Skipping PackageSetting{42bb9780 com.example.hello/10397} due to missing metadata
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  913): Recipient 4347
D/MediaRouterService(  913): Client com.google.android.music (pid 4347): Died!
I/ActivityManager(  913): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1562): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1562): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1562): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1224): Ignoring removeGeofence because network location is disabled.
D/PMS     (  913): acquireWL(44035f78): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/AccTypeManager( 1347): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  913): releaseWL(44035f78): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/VoicemailCleanupService( 1300): Cleaning up data for package: com.test.thalitest
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/SystemReader( 1256): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "sms"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/[PluginManager]RegisterService( 1317): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
W/SQLiteConnectionPool( 2184): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/[PluginManager]RegisterService( 1317): handle notify Blinkfeed plugin client changed
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
W/AccTypeManager( 1347): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1347): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  913):   Scheme: "smsto"
I/Launcher( 1273): Deferring update until onResume
D/Launcher( 1273): waitUntilResume // bindAppsRemoved
D/Prism.PackageStateRece_( 1273): action: android.intent.action.PACKAGE_REMOVED
I/InputMethodManagerService(  913): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "mms"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "mmsto"
I/IcingCorporaProvider( 2826): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
E/ExternalAccountType( 1347): Unsupported attribute readOnly
D/PMS     (  913): acquireWL(44be5d38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  913): n_update end
D/PMS     (  913): releaseWL(44be5d38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "sms"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/ActivityManager(  913): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4934 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "smsto"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "mms"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  913):   Action: "android.intent.action.SENDTO"
I/PackageManager(  913):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  913):   Scheme: "mmsto"
I/PackageManager(  913): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
D/PhoneApp( 1244): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  913): acquireWL(449de848): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2826): UpdateCorporaTask done [took 429 ms] updated apps [took 429 ms] 
E/SQLiteDatabase( 4934): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
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
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4934): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4934): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4934): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4934): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4934): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4934): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4934): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4934): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4934): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4934): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4934): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4934): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4934): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4934): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4934): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4934): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4934): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4934): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4934): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4934): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4934): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4934): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4934): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4934): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4934): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4934): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4934): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4934): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4934): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4934): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4934): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4934): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4934): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4934): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4934): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4934): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4934): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4934): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4934): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4934): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4934): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4934): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4934): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4934): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4934): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4934): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4934): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4934): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4934): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4934): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4934): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4934): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4934): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4934): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4934): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4934): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4934): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4934): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4934): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4934): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4934): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4934): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4934): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
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
E/SQLiteDatabase( 4934): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4934): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4934): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4934): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4934): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4934): threadid=11: thread exiting with uncaught exception (group=0x41fe1e30)
E/ActivityManager(  913): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4934): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4934): Process: com.google.android.apps.docs, PID: 4934
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
E/AndroidRuntime( 4934): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4934): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4934): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4934): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4934): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  913): Can't write: system_app_crash
E/DropBoxManagerService(  913): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  913): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  913): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  913): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  913): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  913): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  913): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  913): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  913): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  913): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  913): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  913): 	... 5 more
E/SQLiteDatabase( 4934): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
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
E/SQLiteDatabase( 4934): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4934): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4934): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4934): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4934): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4934): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4934): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4934): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4934): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4934): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4934): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4934): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4934): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4934): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4934): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4934): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4934): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4934): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4934): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4934): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4934): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4934): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4934): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4934): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4934): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4934): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4934): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4934): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4934): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4934): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4934): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4934): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4934): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4934): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4934): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4934): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4934): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4934): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4934): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4934): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4934): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4934): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4934): 	at dalvik.system.NativeStart.main(Native Method)
I/ActivityManager(  913): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4952 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process ( 4934): killProcess, pid=4934
D/Process ( 4934): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  913): Recipient 4934
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  913): Process com.google.android.apps.docs (pid 4934) has died.
W/ContextImpl( 4952): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  913): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4965 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4952): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4952): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4952): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4952): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4952): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4952): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4952): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4952): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4952): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4952): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4952): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4952): threadid=10: thread exiting with uncaught exception (group=0x41fe1e30)
E/ActivityManager(  913): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4952): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4952): Process: com.android.keychain, PID: 4952
E/AndroidRuntime( 4952): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4952): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4952): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4952): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4952): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4952): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4952): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4952): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4952): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4952): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4952): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4952): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4952): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4952): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4952): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4952): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4952): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4952): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4952): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4952): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  913): HtcErrorReportManager Begin---add error logs to dropbox
D/AppTag  ( 4965): getInstance(Context context)
D/AppTag  ( 4965): getInstance(Context context)
D/Process ( 4952): killProcess, pid=4952
D/Process ( 4952): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/AppTag  ( 4965): onCreate()
E/ErrorReport(  913): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  913): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452016973552.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  913): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  913): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  913): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  913): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  913): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  913): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  913): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  913): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  913): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  913): 	... 4 more
I/ActivityManager(  913): Recipient 4952
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  913): Process com.android.keychain (pid 4952) has died.
W/ActivityManager(  913): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/PMS     (  913): acquireWL(43041d60): PARTIAL_WAKE_LOCK  AsyncService 0x1 4047 10160 null
W/dalvikvm( 4070): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PMS     (  913): releaseWL(43041d60): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/PackageBroadcastService( 2184): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2184): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 2184): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2184): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 2184): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2184): Module APK com.google.android.play.games already loaded
I/ActivityManager(  913): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
I/LocationSettingsChecker( 2184): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 2184): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 2184): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2184): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x6cfabd20
E/SQLiteDBG( 2184): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6d4b50f0
W/dalvikvm( 2184): threadid=41: thread exiting with uncaught exception (group=0x41fe1e30)
E/DriveAsyncService( 2184): disk I/O error (code 3850)
E/DriveAsyncService( 2184): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2184): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2184): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2184): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2184): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2184): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2184): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2184): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2184): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2184): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2184): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2184): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2184): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2184): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2184): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2184): 	at java.lang.Thread.run(Thread.java:864)
E/AndroidRuntime( 2184): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2184): Process: com.google.android.gms, PID: 2184
E/AndroidRuntime( 2184): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2184): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2184): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2184): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2184): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2184): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2184): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2184): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2184): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2184): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2184): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2184): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2184): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2184): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2184): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2184): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2184): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2184): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2184): 	at java.lang.Thread.run(Thread.java:864)
E/ActivityManager(  913): App crashed! Process: com.google.android.gms
D/Process ( 2184): killProcess, pid=2184
D/Process ( 2184): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  913): Can't write: system_app_crash
E/DropBoxManagerService(  913): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  913): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  913): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  913): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  913): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  913): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  913): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  913): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  913): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  913): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  913): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  913): 	... 5 more
I/ActivityManager(  913): Recipient 2184
I/ActivityManager(  913): Process com.google.android.gms (pid 2184) has died.
D/WifiService(  913): Client connection lost with reason: 4
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  913): handleWLDeath(449de848): PARTIAL_WAKE_LOCK  Icing 0x1
W/ActivityManager(  913): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  913): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 10999ms
W/ActivityManager(  913): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 20999ms
W/ActivityManager(  913): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 20998ms
W/ActivityManager(  913): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20998ms
W/ActivityManager(  913): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20997ms
I/ActivityManager(  913): Resuming delayed broadcast
W/ActivityManager(  913): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20994ms
E/SQLiteLog( 1356): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1356): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x5cad9008
W/dalvikvm( 1356): threadid=1: thread exiting with uncaught exception (group=0x41fe1e30)
E/AndroidRuntime( 1356): FATAL EXCEPTION: main
E/AndroidRuntime( 1356): Process: com.google.process.gapps, PID: 1356
E/AndroidRuntime( 1356): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1356): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1356): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1356): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1356): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1356): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1356): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1356): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1356): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1356): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1356): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1356): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1356): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1356): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1356): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1356): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1356): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1356): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1356): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1356): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1356): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1356): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1356): 	... 10 more
E/ActivityManager(  913): App crashed! Process: com.google.process.gapps
E/DropBoxManagerService(  913): Can't write: system_app_crash
E/DropBoxManagerService(  913): java.io.FileNotFoundException: /data/system/dropbox/drop144.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  913): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  913): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  913): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  913): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  913): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  913): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  913): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  913): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  913): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  913): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  913): 	... 5 more
D/Process ( 1356): killProcess, pid=1356
D/Process ( 1356): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  913): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4995 uid=10098 gids={50098, 3003, 5012}
W/PackageManager(  913): Unable to load service info ResolveInfo{42ecad48 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  913): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  913): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  913): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  913): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  913): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  913): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  913): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  913): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  913): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  913): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  913): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  913): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  913): 	at dalvik.system.NativeStart.main(Native Method)
I/DisplayManagerService(  913): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  913): Recipient 1356
D/WifiService(  913): Client connection lost with reason: 4
I/ActivityManager(  913): Process com.google.process.gapps (pid 1356) has died.
W/ActivityManager(  913): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20862ms
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@424a4e18 +
I/Prism.WidgetManager( 1273): onLoadItems() +
I/DeviceManagement( 4995): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4995 dbg=false s=true
I/DeviceManagement( 4995): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 4995): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 4995): WorkflowService: Starting workflow service
I/DeviceManagement( 4995): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@42441e68] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4995): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4995): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 4995): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4995): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  913): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5009 uid=10099 gids={50099, 3003, 5012}
I/DeviceManagement( 4995): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 4995): SessionStateController: Checking invariants...
D/Documents( 5009): Loading roots for com.android.providers.downloads.documents
D/Documents( 5009): Loading roots for com.android.externalstorage.documents
E/SQLiteDatabase( 5009): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 5009): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5009): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5009): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5009): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5009): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5009): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5009): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5009): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5009): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5009): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5009): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5009): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5009): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5009): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5009): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 5009): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 5009): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 5009): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 5009): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 5009): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 5009): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 5009): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 5009): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5009): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5009): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5009): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5009): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5009): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5009): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5009): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 5009): threadid=1: thread exiting with uncaught exception (group=0x41fe1e30)
E/AndroidRuntime( 5009): FATAL EXCEPTION: main
E/AndroidRuntime( 5009): Process: com.android.documentsui, PID: 5009
E/AndroidRuntime( 5009): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5009): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 5009): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 5009): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 5009): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5009): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5009): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 5009): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 5009): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 5009): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 5009): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 5009): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 5009): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5009): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5009): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5009): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5009): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5009): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5009): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5009): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5009): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5009): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5009): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5009): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5009): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5009): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5009): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 5009): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 5009): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 5009): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 5009): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 5009): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 5009): 	... 10 more

```
