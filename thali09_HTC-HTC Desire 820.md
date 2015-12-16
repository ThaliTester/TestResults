#### Test 50650278cd699a4_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
V/LightsService(  906): setLight #0: color=#25
,V/LightsService(  906): setLight #0: color=#21
V/LightsService(  906): setLight #0: color=#1b
V/LightsService(  906): setLight #0: color=#14
I/ActivityManager(  906): Waited long enough for: ServiceRecord{42e04f68 u0 com.htc.htclocationservice/.AutoSettingService}
--------- beginning of /dev/log/main
E/cutils-trace( 4443): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4443): ====startRecUseTime====
D/htc.customization.log.level( 4443):  is 
W/CustomizationLogLevel( 4443): Level value is invalid, use default level 2
D/CustomizationManager( 4443):  Read ACC file spent 0.060 (s)
D/CIDMapFileReader( 4443): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4443): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4443): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4443): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4443): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4443): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4443): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4443): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4443): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4443): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4443): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4443): Parsing tag category name = system
I/CustomizationCIDLoader( 4443): Parsing tag category name = application
I/CustomizationCIDLoader( 4443): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4443): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4443): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4443): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4443): Parsing tag category name = Settings
D/CustomizationManager( 4443):  Read CID file spent 0.101 (s)
D/CustomizationManager( 4443):  All configurations done spent 0.101 (s)
W/HtcNativeFlag( 4443): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4443): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4443): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4443): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  906): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  906): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4443
D/PMS     (  906): acquireHCC(425992d8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 906 1000 null
D/PMS     (  906): acquireHCC(424bef58): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 906 1000 null
W/asset   (  906): Copying FileAsset 0x6cd15f68 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  906): @test_code: getHtcIntentFlag: 0 obj: 1106642504
I/FeedHostManager( 1271): [onPause]
I/FeedProviderManager( 1271): onPause
I/FeedHostManager( 1271): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41ef0398
I/SocialFeedProvider( 1271): +onPause
I/SocialFeedProvider( 1271): -onPause
D/PMS     (  906): acquireWL(4291ec48): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
I/ActivityManager(  906): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4454 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1271): [trimMemory] 20
W/asset   ( 4454): Copying FileAsset 0x5c72e488 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4454): Binding Chromium to main looper Looper (main, tid 1) {41d2f0c8}
I/LibraryLoader( 4454): Expected native library version number "",actual native library version number ""
I/chromium( 4454): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4454): Initializing chromium process, renderers=0
D/PMS     (  906): acquireWL(4283f110): PARTIAL_WAKE_LOCK  AudioMix 0x1 363 1013 null
D/PMS     (  906): acquireWL(4279de38): PARTIAL_WAKE_LOCK  AudioMix 0x1 363 1013 null
D/PMS     (  906): releaseWL(4283f110): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  906): java.lang.Throwable: stack dump
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@426817d0:true
D/BluetoothAdapter( 4454): 1104444520: getState(). Returning 12
I/Adreno-EGL( 4454): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4454): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4454): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4454): Local Branch: 
I/Adreno-EGL( 4454): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4454): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4454):                  aa63bbd948f41d15fc72f585e
W/chromium( 4454): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4454): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4454): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4454): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4454): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4454): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4454): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4454): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4454): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4454): CordovaWebView is running on device made by: HTC
,W/AwContents( 4454): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  906): Disable input method client, pid=1271
,W/ResourceType( 4454): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4454): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41d79318, mServedView=org.apache.cordova.engine.SystemWebView{41d3ef80 VFEDH.C. .F....I. 0,0-720,1134 #64}
,I/InputMethodManagerService(  906): Enable input method client, pid=4454
W/XT9_C   ( 1208): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1208): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,W/AwContents( 4454): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  906): Displayed com.test.thalitest/.MainActivity: +308ms
,D/PMS     (  906): releaseWL(4291ec48): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4454): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4454): JniHelper::setJavaVM(0x418f2010), pthread_self() = 1598287080
,D/JX-Cordova( 4454): jxcore cordova android initializing
,I/dalvikvm-heap( 4454): Grow heap (frag case) to 11.579MB for 96598-byte allocation
,I/dalvikvm-heap( 4454): Grow heap (frag case) to 11.637MB for 144892-byte allocation
,I/dalvikvm-heap( 4454): Grow heap (frag case) to 11.740MB for 217334-byte allocation
,I/dalvikvm-heap( 4454): Grow heap (frag case) to 11.915MB for 325996-byte allocation
,I/dalvikvm-heap( 4454): Grow heap (frag case) to 12.189MB for 488990-byte allocation
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
,I/dalvikvm-heap( 4454): Grow heap (frag case) to 13.197MB for 1100216-byte allocation
,I/dalvikvm-heap( 4454): Grow heap (frag case) to 14.067MB for 1650320-byte allocation
,I/dalvikvm-heap( 4454): Grow heap (frag case) to 15.456MB for 2475476-byte allocation
,I/dalvikvm-heap( 4454): Grow heap (frag case) to 17.510MB for 3713210-byte allocation
,W/CpuWake (  906): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  906): <<release mCpuPerf_Freq wakelock
D/PMS     (  906): releaseHCC(425992d8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  906): releaseHCC(424bef58): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4454): Initializing JXcore engine
,W/jxcore-log( 4454): JXcore engine is ready
,W/jxcore-log( 4454): Starting JXcore engine
,W/jxcore-log( 4454): Platform android
W/jxcore-log( 4454): 
,W/jxcore-log( 4454): Process ARCH arm
W/jxcore-log( 4454): 
,I/jxcore-log( 4454): JXcore Cordova bridge is ready!
I/jxcore-log( 4454): 
,W/jxcore-log( 4454): JXcore engine is started
,I/chromium( 4454): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PMS     (  906): releaseWL(4279de38): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/SensorManager(  906): mEventCount = 1050
,I/jxcore-log( 4454): Toggling radios to true
I/jxcore-log( 4454): 
,D/BluetoothAdapter( 4454): enable(): BT is already enabled..!
,D/WifiManager( 4454): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  906): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 2
W/Settings:Agent(  906): >> traceCallingStack()
W/Settings:Agent(  906): Process.myPid(): 906
W/Settings:Agent(  906): Process.myTid(): 1371
W/Settings:Agent(  906): Process.myUid(): 1000
W/Settings:Agent(  906): 
W/Settings:Agent(  906): 
,W/System.err(  906): java.lang.Throwable: stack dump
D/WifiService(  906): New client listening to asynchronous messages
D/WifiService(  906): setWifiEnabled: true pid=4454, uid=10389
E/WifiService(  906): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  906): isSprintWifiRestricted(): false
I/WifiService(  906): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  906): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
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
W/Settings:Agent(  906): << traceCallingStack(): 1(ms)
D/WifiManager( 4454): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  906): doBoolean: DISCONNECT
D/WifiManager( 4454): reconnect: Base Package Name=com.test.thalitest, uid=10389
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): TDLS: Tear down peers
I/wpa_supplicant( 1183): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4454): Radios toggled
I/jxcore-log( 4454): 
D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4454): Got Device Bluetooth address: B4:CE:F6:AB:A4:6A
I/jxcore-log( 4454): 
I/jxcore-log( 4454): Perf Test app loaded loaded
I/jxcore-log( 4454): 
I/Choreographer( 4454): Skipped 78 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 4454): check test folder
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): found test : ./testFindPeers.js
I/jxcore-log( 4454): 
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1183): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1183): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1183): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  906): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/wpa_supplicant( 1183): TDLS: Remove peers on disassociation
D/HTCRequest(  906): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  906): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1183): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1183): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1183): send_and_recv error -67 - cmd 12
D/HTCRequest(  906): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  906): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1183): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb73e1bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1183):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1183): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1183): netlink: Operstate: linkmode=-1, operstate=5
D/HTCRequest(  906): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1183): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1183): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1183): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1183): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  906): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: External notification - EA,P success=0
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1183): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1183): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1183): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1183): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1183): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1183): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1183): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1183): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1183): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1183): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1183): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1183): nl80211: Ignore disconnect event triggered during reassociation
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  906):    returned true
D/WifiPerfLock(  906): release()
D/WifiStateMachine(  906): PerfLock released for exiting ConnectedState
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1183): Power_Mode_Type mode = 0
I/wpa_supplicant( 1183): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 61
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
D/Tethering(  906): interfaceStatusChanged wlan0, false
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiNative-wlan0(  906):    returned true
,D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  906): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  906): acquireWL(428139f0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 906 1000 null
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360022653
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023242
,D/DhcpStateMachine(  906): [RunningState] Stop DHCP
,I/jxcore-log( 4454): found test : ./testSendData.js
I/jxcore-log( 4454): 
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiNative-wlan0(  906): doBoolean: RECONNECT
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): Fast associate: Old scan results
I/wpa_supplicant( 1183): wpa_supplicant_scan enter
I/wpa_supplicant( 1183): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1183): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1183): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  906):    returned true
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1183): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiStateMachine(  906): Enter handleNetworkDisconnect
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1183): Power_Mode_Type mode = 0
I/wpa_supplicant( 1183): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 61
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023477
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023488
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023495
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024903
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024916
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027698
D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=19460 mDataStallAlarmIntent=PendingIntent{4278a0e0: PendingIntentRecord{422da048 android broadcastIntent}}
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  906):    returned true
,D/WISPrService( 3770): >>>>>WISPrService start isConnected = false<<<<<
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiP2pService(  906): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiP2pService(  906): P2pEnabledState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360022653
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023242
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023477
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023488
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023495
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024903
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024916
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027698
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  906): Provision feature enable=false
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  906): Exit handleNetworkDisconnect
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/UsbnetStateTracker(  906): isAvailable+-
D/UsbnetStateTracker(  906): reconnect
,D/UsbnetStateTracker(  906): isAvailable+-
,D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/ConnectivityService(  906): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  906): default: reconnect()
D/MDST    (  906): default: setTeardownRequested(false)
D/MDST    (  906): default: setEnableApn apnType =default , enable=true
D/WifiService(  906): New client listening to asynchronous messages
D/libc    (  356): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  356): [NET] getaddrinfo-, SUCCESS
D/libc    (  356): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  356): [NET] getaddrinfo-, SUCCESS
D/libc    (  356): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  356): [NET] getaddrinfo-, SUCCESS
D/libc    (  356): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  356): [NET] getaddrinfo-, SUCCESS
D/libc    (  356): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  356): [NET] getaddrinfo-, SUCCESS
D/libc    (  356): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  356): [NET] getaddrinfo-, SUCCESS
D/WISPrService( 3770): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  906): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  906): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  906): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WISPrService( 3770): >>>>>WISPrService start isConnected = false<<<<<
,V/NativeCrypto( 1360): Read error: ssl=0x660a1968: I/O error during system call, Connection timed out
,V/NativeCrypto( 1360): SSL shutdown failed: ssl=0x660a1968: I/O error during system call, Broken pipe
D/libc    (  356): [NET] entry_id:3   entry:0xb8789db8  removed 
D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/libc    (  356): [NET] entry_id:4   entry:0xb8789c88  removed 
D/libc    (  356): [NET] entry_id:1   entry:0xb8789f70  removed 
D/libc    (  356): [NET] entry_id:5   entry:0xb8780c20  removed 
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/ConnectivityService(  906): resetConnections(wlan0, 3)
D/PMS     (  906): acquireWL(438bb3c0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): flush DNS cache for net 1(wlan0)
D/libc    (  356): [NET] entry_id:2   entry:0xb8785458  removed 
D/libc    (  356): [NET] entry_id:6   entry:0xb87852d8  removed 
D/libc    (  356): *************************
D/libc    (  356): *** DNS CACHE FLUSHED ***
D/libc    (  356): *************************
,D/WISPrService( 3770): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  906): acquireWL(428b0ef8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  906): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:2
,D/WifiStateMachine(  906): startScan Pid: 906 Uid 1000
D/WifiNative-wlan0(  906): doBoolean: SCAN
I//system/bin/ip(  356): RTNETLINK answers: No such process
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
,I/logwrapper(  356): /system/bin/ip terminated by exit(2)
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1183): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  906):    returned false
D/BatSI   (  906): WIFI scan started for: 650a0300 uid:1000
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360022653
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023242
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023477
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023488
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023495
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024903
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024916
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027698
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
D/ConnectivityService(  906): reportInetCondition for net -1, percentage: 0 by  (1360/10029)
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
D/PMS     (  906): releaseWL(438bb3c0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
D/ConnectivityService(  906): mActiveDefaultNetwork: -1
D/ConnectivityService(  906): handleInetConditionChange: no active default network - ignore
,D/PMS     (  906): releaseWL(428b0ef8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/chromium( 4454): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: false
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4264/10100)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.backuptransport (1601/10029)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1271/10076)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
D/CaptivePortalTracker(  906): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/CaptivePortalTracker(  906): NoActiveNetworkState
D/Tethering(  906): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  906): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
,I/ConnectivityHelper( 1271): [onReceive] WIFI(1): DISCONNECTED,
V/Tethering(  906): bSetPropertyMultiRAB:false,
D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/NetworkMonitor( 3826): type=WIFI subType= reason=null isConnected=false
I/Tethering(  906): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
,I/Tethering(  906): ipv4Default null,
D/PMS     (  906): acquireWL(43f26b28): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3826/10154)
I/Tethering(  906): No IPv4 upstream interface, giving up.
D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): releaseWL(43f26b28): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (4264/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (2708/10021)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360022653
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023242
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023477
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023488
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023495
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024903
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024916
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027698
,I/ActivityManager(  906): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4505 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4505): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4505): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4505): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4505): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4505): Preparing secondary program dexes.
V/DexLibLoader( 4505): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4505): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4505): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4505): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4505): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4505): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4505): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4505): Dex already copied
D/OdexVerifier( 4505): Odex verification is skipped.
,V/DexLibLoader( 4505): Creating class loader
,V/DexLibLoader( 4505): Finished creating class loader
V/DexLibLoader( 4505): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4505): Dex already copied
D/OdexVerifier( 4505): Odex verification is skipped.
,V/DexLibLoader( 4505): Creating class loader
,V/DexLibLoader( 4505): Finished creating class loader
V/DexLibLoader( 4505): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4505): Dex already copied
D/OdexVerifier( 4505): Odex verification is skipped.
,V/DexLibLoader( 4505): Creating class loader
,V/DexLibLoader( 4505): Finished creating class loader
V/DexLibLoader( 4505): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4505): Dex already copied
D/OdexVerifier( 4505): Odex verification is skipped.
,V/DexLibLoader( 4505): Creating class loader
,V/DexLibLoader( 4505): Finished creating class loader
,V/DexLibLoader( 4505): Verifying classes from secondary dexes.
,D/DexLibLoader( 4505): DexLibLoader.ensureDexLoaded took 22 ms
,W/dalvikvm( 4505): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4505): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4505): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 4505): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 4505): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 4505): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4505): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,I/PMS     (  906): Going to sleep due to screen timeout...
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@424065d0
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  906): pid=906, uid=1000
,W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
I/ActivityManager(  906): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  906): Couldn't get kernel wake lock stats
V/LightsService(  906): setLight #2: color=#0
D/qdlights(  906): set_light_buttons_func: on=0 brightness=0
,V/LightsService(  906): setLight #0: color=#0
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@424065d0, eanble = 0, strlen(mName) = 59
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41ef58e0
W/SensorService(  906): Listener[1] = com.htc.smartdim.sensor_eye@41e57e80
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/WirelessDisplayService(  906): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  906): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  906): mWirelessDisplayManager is null
,W/dalvikvm( 4505): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4505): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1183): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1183): nl80211: Survey data missing
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1183): Sorted scan results
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1183): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1183): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1183): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1183): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1183): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1183): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1183): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1183): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1183): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1183): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1183): wpa_supplicant_pick_network+
I/wpa_supplicant( 1183): Selecting BSS from priority group 1
I/wpa_supplicant( 1183): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1183): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1183): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1183): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1183):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1183):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-50
I/wpa_supplicant( 1183): Start print parameters
I/wpa_supplicant( 1183): wpa_s->wpa_state is 3
I/wpa_supplicant( 1183): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1183): isConcurrentMode() is 0
I/wpa_supplicant( 1183): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1183): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1183): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1183): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1183): wpa_s->reassociate is 1
I/wpa_supplicant( 1183): wpa_s->is_screen_on 1
I/wpa_supplicant( 1183): wpa_s->ifname wlan0
I/wpa_supplicant( 1183): End print parameters
I/wpa_supplicant( 1183): selected network = 1
D/wpa_supplicant( 1183): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb73e34e8  current_ssid=0x0
D/wpa_supplicant( 1183): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1183): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1183): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1183): check if in concurrent case
I/wpa_supplicant( 1183): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  906): doString: LIST_DONGLES
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,D/wpa_supplicant( 1183): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1183): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1183): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1183): RSN: PMKSA cache search - network_ctx=0xb73e34e8 try_opportunistic=0
D/wpa_supplicant( 1183): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1183): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1183): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1183): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1183): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1183): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1183): nl80211: Unsubscribe mgmt frames handle 0xb73e2718 (mode change)
D/wpa_supplicant( 1183): nl80211: Subscribe to mgmt frames with non-AP handle 0xb73e2718
,D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb73e2718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb73e2718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb73e2718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb73e2718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb73e2718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb73e2718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb73e2718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb73e2718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb73e2718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1183): nl80211: Register frame type=0xd0 nl_handle=0xb73e2718
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1183): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1183):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1183):   * freq=2412
D/wpa_supplicant( 1183):   * Auth Type 0
D/wpa_supplicant( 1183):   * WPA Versions 0x2
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1183): nl80211: Connect request send successfully
D/wpa_supplicant( 1183): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiNative-wlan0(  906): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1183): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1183): reply (489) for get BSS: id=0
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1183): freq=5220
I/wpa_supplicant( 1183): level=-49
I/wpa_supplicant( 1183): tsf=0000000104570978
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG7005g
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=1,
I/wpa_supplicant( 1183): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-50
I/wpa_supplicant( 1183): tsf=0000000104570994
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1183): ssid=NG700
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=2
I/wpa_supplicant( 1183): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1183): freq=2427
I/wpa_supplicant( 1183): level=-79
I/wpa_supplicant( 1183): tsf=0000000104570998
I/wpa_supplicant( 1183): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1183): ssid=Gonzos
I/wpa_supplicant( 1183): ====
I/wpa_supplicant( 1183): id=3
I/wpa_supplicant( 1183): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): freq=2412
I/wpa_supplicant( 1183): level=-50
I/wpa_supplicant( 1183): tsf=0000000104570990
I/wpa_supplicant( 1183): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1183): ssid=01ABC
I/wpa_supplicant( 1183): ####
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WifiStateMachine(  906): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 104570978, distance: ?(cm), distanceSd: ?(cm)
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiStateMachine(  906): == begin of scan result ==
,D/WifiStateMachine(  906): == (4) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  906): == begin of scan result ==
D/WifiStateMachine(  906): == (4) end of scan result ==
,D/WirelessDisplayService(  906): getDiscoveryDongleList
D/WifiStateMachine(  906): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 2412, timestamp: 104570994, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 104570998, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiStateMachine(  906): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -50, frequency: 2412, timestamp: 104570990, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  906): add 4 to mScanResults
D/BatSI   (  906): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  906): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,E/FbInjectorInitializer( 4505): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/wpa_supplicant( 1183): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1183): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1183): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1183): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1183): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1183): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1183): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1183): nl80211: Event message available
D/wpa_supplicant( 1183): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1183): nl80211: Connect event
D/wpa_supplicant( 1183): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1183): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1183): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1183): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1183): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1183): Add randomness: count=10 entropy=4
I/wpa_supplicant( 1183): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1183): TDLS: Remove peers on association
D/wpa_supplicant( 1183): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1183): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1183): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1183): EAPOL: enable timer tick
D/wpa_supplicant( 1183): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1183): htc_wext_set_keepalive +
I/wpa_supplicant( 1183): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1183): getPrivFuncNum +	
I/wpa_supplicant( 1183): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1183): htc_wext_set_keepalive fnum = 0x8bf6
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
I/wpa_supplicant( 1183): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1183): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1183): Get randomness: len=32 entropy=5
D/WifiMonitor(  906): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  906): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  906): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  906): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  906): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  906): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantSt,ateChange(): SSIDNG700
D/WifiStateMachine(  906): Enter handleAssociatedWithEvent
D/WifiStateMachine(  906): Associated
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  906): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  906): Exit handleAssociatedWithEvent
D/WifiStateMachine(  906): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  906): This record is existed, only update it...
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  906): updateConnectedAP...
I/wpa_supplicant( 1183): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb73e29f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1183):    addr=c0:ff:d4:d3:aa:48
D/Tethering(  906): [isWifi] getHotspotEnabled: false
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1183): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1183): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6eceb4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1183):    broadcast key
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1183): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1183): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1183): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1183): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1183): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
E/wpa_supplicant( 1183): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1183): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1183): netlink: Operstate: linkmode=-1, operstate=6
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 1183): set send_ind_to_ndc = 0
I/wpa_supplicant( 1183): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1183): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1183): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1183): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1183): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1183): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1183): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1183): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1183): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1183): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1183): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1183): EAPOL authentication completed successfully
I/wpa_supplicant( 1183): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1183): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1183): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
D/wpa_supplicant( 1183): nl80211: if_removed already cleared - ignore event
D/Tethering(  906): interfaceStatusChanged wlan0, true
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  906): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/Tethering(  906): interfaceLinkStateChanged wlan0, true
D/Tethering(  906): interfaceStatusChanged wlan0, true
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  906): updateConnectedAP...
D/WifiStateMachine(  906): fetchFrequency(), freq = 2412
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  906): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  906): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  906): This record is existed, only update it...
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  906): updateConnectedAP...
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): mActiveDefaultNetwork: -1
D/WISPrService( 3770): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 3770): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  906): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  906): updateConnectedAP...
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360022653
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023242
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023477
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023488
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023495
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024903
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024916
D/DhcpStateMachine(  906): [StoppedState] Start DHCP
D/WifiStateMachine(  906): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027698
D/WifiStateMachine(  906): handlePreDhcpSetup Held wake lock during DHCP
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1183): Power_Mode_Type mode = 1
I/wpa_supplicant( 1183): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  906):    returned null
E/WifiStateMachine(  906): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/WifiNative-wlan0(  906):    returned null
D/PMS     (  906): acquireWL(434d43a0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 906 1000 null
D/WifiStateMachine(  906): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@427fd6f8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@427fd6f8 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:0
D/SurfaceControl(  906): Excessive delay in blankDisplay() while turning screen off: 320ms
,W/fb4a(:<default>):StaticBindingVerifier( 4505): Verify
D/PMS     (  906): nativeSetInteractive:false
D/PMS     (  906): nativeSetInteractive:false done
D/PMS     (  906): nativeSetAutoSuspend:true
D/PMS     (  906): nativeSetAutoSuspend:true done
D/HABCtrl (  906): TPE algorithm. remove timeout.
D/PMS     (  906): OOBE c monitor 11
,I/InputManager(  906): Cancel all due to getting PMS screen off broadcast
,V/KeyguardServiceDelegate(  906): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43e8c588)
D/NfcService( 1254): ScreenObserver: OFF
,D/NfcService( 1254): applyRouting - 0
,I/IntentController( 1117): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/NfcService( 1254): applyRouting -2
W/ResourceType( 4454): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4454): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41d3ef80 VFEDH.C. .F...... 0,0-720,1134 #64}
,V/KeyguardServiceDelegate(  906): **** SHOWN CALLED ****
D/PMN     (  906): wakingUp
I/InputMethodManagerService(  906): screenObserver, isScreenOn=false
I/InputMethodManagerService(  906): Disable input method client, pid=4454
D/PMS     (  906): acquireWL(428c6b90): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
I/WindowManager(  906): No lock screen! windowToken=null
D/PMN     (  906): onScreenOn
D/PMS     (  906): releaseWL(428c6b90): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMS     (  906): acquireWL(43e16d28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
D/PMS     (  906): releaseWL(43e16d28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/AlarmManager(  906): ACTION_SCREEN_ON
I/AlarmManager(  906): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done recovering
I/AlarmManager(  906): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  906): [AlarmQueuing] done EPS screen off alarm recovering
,D/WirelessDisplayService(  906): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_ON
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1587): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/MtpService( 2708): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/MtpService( 2708): [MTP][onReceive]-
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/NfcService( 1254): applyRouting - 0
,D/NfcService( 1254): applyRouting -2
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): acquireWL(43b7fdb0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
D/PMS     (  906): releaseWL(43b7fdb0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/qdlights(  906): [LedInfo] has indicator attribute
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
I/wpa_supplicant( 1183): SET_SCREEN_ON:On
I/wpa_supplicant( 1183): htc_wext_set_keepalive +
I/wpa_supplicant( 1183): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1183): getPrivFuncNum +	
I/wpa_supplicant( 1183): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1183): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1183): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1183): htc_wext_set_TX_TRACKING (1)+
,I/wpa_supplicant( 1183): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  906):    returned true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/WifiNative-wlan0(  906):    returned true
,V/SRS_Proc(  363): ParamSet string: screen_state=on
,D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,I/ClockThread( 1117): stop update clock
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/NetworkPolicy(  906): updateScreenOn: false
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/DotMatrix( 1587): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  906): acquireWL(42949d98): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42949d98): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(43e3c108): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1782): onScreenOn: false
,D/PMS     (  906): releaseWL(43e3c108): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1782): onScreenOn: 1450240664507
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1782): onScreenOn: 1450240664508
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41ef58e0
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41ef58e0, eanble = 0, strlen(mName) = 91
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  906): Listener[0] = com.htc.smartdim.sensor_eye@41e57e80
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  906): goingToSleep
D/PMS     (  906): acquireWL(43fe6f58): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 906 1000 null
D/WifiService(  906): New client listening to asynchronous messages
,D/AlarmManager(  906): ACTION_SCREEN_OFF
I/AlarmManager(  906): [AlarmQueuing] screen off now: 
I/AlarmManager(  906): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=19461 mDataStallAlarmIntent=null
I/AlarmManager(  906): [AlarmQueuing] wifi connection: true
,D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1183): SET_SCREEN_ON:Off
I/wpa_supplicant( 1183): htc_wext_set_keepalive +
I/wpa_supplicant( 1183): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1183): getPrivFuncNum +	
I/wpa_supplicant( 1183): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1183): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1183): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 1183): get_ip_address source addr = 02000000
I/wpa_supplicant( 1183): htc_wext_set_keepalive gateway addr = 00000000
I/wpa_supplicant( 1183): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  906):    returned true
,V/SRS_Proc(  363): ParamSet string: screen_state=off
D/PMS     (  906): acquireWL(43be9358): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 906 1000 null
D/PMS     (  906): releaseWL(43fe6f58): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/PMS     (  906): releaseWL(43be9358): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/ContactMessageStore( 1239): start background delete task...
D/ContactMessageStore( 1239): size: 0 , 0
,D/ContactMessageStore( 1239): Background delete complete
D/NetworkPolicy(  906): updateScreenOn: false
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4505/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4505): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4505): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,D/PMS     (  906): acquireWL(43d8a8a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(43d8a8a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1587): [EventService] getTotalRam: 1873 Mb
D/PMS     (  906): acquireWL(4332c800): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(4332c800): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/dalvikvm-heap( 4505): Grow heap (frag case) to 9.507MB for 73240-byte allocation
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1782): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1782): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1782): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1782): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1782): onScreenOff
,D/Process (  906): killProcessQuiet, pid=1327
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 1327:com.htc.sense.hsp/u0a55 (adj 15): empty #17
,E/JavaBinder(  906): !!! FAILED BINDER TRANSACTION !!!
W/BroadcastQueue(  906): Exception when sending broadcast to ComponentInfo{com.htc.sense.hsp/com.htc.sense.hsp.weather.location.AutoSettingReceiver}
W/BroadcastQueue(  906): android.os.TransactionTooLargeException
W/BroadcastQueue(  906): 	at android.os.BinderProxy.transact(Native Method)
W/BroadcastQueue(  906): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:966)
W/BroadcastQueue(  906): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:246)
W/BroadcastQueue(  906): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:974)
W/BroadcastQueue(  906): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:15076)
W/BroadcastQueue(  906): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:401)
W/BroadcastQueue(  906): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2330)
W/BroadcastQueue(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/BroadcastQueue(  906): 	at dalvik.system.NativeStart.run(Native Method)
,I/ActivityManager(  906): Start proc com.htc.sense.hsp for broadcast com.htc.sense.hsp/.weather.location.AutoSettingReceiver: pid=4543 uid=10055 gids={50055, 1023, 3003, 5012}
,W/fb4a(:<default>):UserScope( 4505): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4505): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/fb4a(:<default>):UserScope( 4505): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/PluginProvider( 4543): PluginProvider onCreate
,D/PluginProvider( 4543): current plugin count: 18
,D/HtcAppUPService( 4543): HtcUPDataProvider onCreate()
,E/dalvikvm( 4505): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4505): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4505): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4505): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4505): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4505): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,D/AutoSetting( 4543): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/dalvikvm-heap( 4505): Grow heap (frag case) to 9.958MB for 84664-byte allocation
E/dalvikvm( 4505): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4505): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4505): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4505): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4505): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4505): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4505): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4505): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4505): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4505): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
,D/Process (  906): killProcessQuiet, pid=4264
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4578 uid=10079 gids={50079, 3003, 5012}
I/ActivityManager(  906): Killing 4264:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,D/AutoSetting( 4543): Util - no network available!
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (4543/10055)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (4543/10055)
,D/AutoSetting( 4543): service - onCreate()
I/ActivityManager(  906): Recipient 4264
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 4543): service - AddressCache: using context: com.htc.Weather
,D/AutoSetting( 4543): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/LocationManagerService(  906): request 427bc3a0 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/LocationManagerService(  906): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 4543): service - mHandler: cancel location update
,D/AutoSetting( 4543): service -           changes count: 0
,I/dalvikvm-heap( 4505): Grow heap (frag case) to 9.972MB for 28144-byte allocation
W/dalvikvm( 4505): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4505): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1183): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1183): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  906): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  906): releaseWL(434d43a0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [1][0][0]
,D/MobileConnectivityChangeReceiver( 4578): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/MobileConnectivityChangeReceiver( 4578): onReceive CONNECTIVITY_CHANGE networkType=1
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
E/PhoneMonitor( 4578): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4578): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/dalvikvm-heap( 4505): Grow heap (frag case) to 10.013MB for 39954-byte allocation
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
I/ActivityManager(  906): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4594 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4578/10079)
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED -1 -> 3
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,D/WifiStateMachine(  906): gateway: /192.168.1.1
,D/WifiNative-wlan0(  906): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1183): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1183): htc_wext_set_keepalive +
I/wpa_supplicant( 1183): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1183): getPrivFuncNum +	
I/wpa_supplicant( 1183): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1183): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1183): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1183): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1183): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  906): VerifyingLinkState enter
D/WifiStateMachine(  906): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  906): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  906): VerifyingLinkState: enableIpv6
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4578/10079)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4578/10079)
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -50, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiWatchdogStateMachine(  906): WAN detection
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  906): Provision feature enable=false
V/NetworkPolicy(  906): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/ConnectivityService(  906): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  906): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  906): default: teardown()
D/MDST    (  906): default: setTeardownRequested(true)
D/MDST    (  906): default: setEnableApn apnType =default , enable=false
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/MDST    (  906): default: setTeardownRequested(true)
D/ConnectivityService(  906): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  906): Unexpected mtu value: android.net.wifi.WifiStateTracker@426b87a0
,D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WISPrService( 3770): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/dalvikvm-heap( 4505): Grow heap (frag case) to 10.088MB for 79892-byte allocation
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  906): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  906): syncGetConfiguredNetworks
D/libc    (  356): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  356): [NET] getaddrinfo-, SUCCESS
D/libc    (  356): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  356): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  906): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  356): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  356): [NET] getaddrinfo-, SUCCESS
D/libc    (  356): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  356): [NET] getaddrinfo-, SUCCESS
D/libc    (  356): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  356): [NET] getaddrinfo-, SUCCESS
D/libc    (  356): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  356): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  906): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  906): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
,D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
,D/libc    (  356): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  906): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  906): acquireWL(438a5590): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
D/WirelessDisplayService(  906): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  906):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,I/QuickSettingWifi( 1117): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4578/10079)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,I//system/bin/ip(  356): RTNETLINK answers: No such file or directory
,I/logwrapper(  356): /system/bin/ip terminated by exit(254)
D/PMS     (  906): acquireWL(436eab90): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 3990 10029 WorkSource{10029 com.google.android.gms}
,I//system/bin/ip(  356): RTNETLINK answers: No such process
,I/logwrapper(  356): /system/bin/ip terminated by exit(2)
,I/ActivityManager(  906): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4617 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/PMS     (  906): acquireWL(43bc3a00): PARTIAL_WAKE_LOCK  Checkin Service 0x1 3990 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): mActiveDefaultNetwork: WIFI
,D/PMS     (  906): releaseWL(436eab90): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): releaseWL(438a5590): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
I/CheckinService( 3990): Checkin interval check for package: unspecified last checkin: 1450240616136 min interval config: 0 actual interval: 49003
,I/CheckinService( 3990): Disabling old GoogleServicesFramework version
,I/dalvikvm-heap( 4505): Grow heap (frag case) to 10.276MB for 75760-byte allocation
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$Receiver, state=2, flag=1, pid=3990, uid=10029, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$TriggerReceiver, state=2, flag=1, pid=3990, uid=10029, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$SecretCodeReceiver, state=2, flag=1, pid=3990, uid=10029, userID:0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4505/10027)
,W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{44298f28 u0 ReceiverList{43d376b0 4505 com.facebook.katana/10027/u0 remote:43d8f738}}
,W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{44298f28 u0 ReceiverList{43d376b0 4505 com.facebook.katana/10027/u0 remote:43d8f738}}
,W/dalvikvm( 3990): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 3990): VFY: unable to find class referenced in signature (Landroid/net/Network;)
E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43ed0c80 u0 ReceiverList{43d342e0 4505 com.facebook.katana/10027/u0 remote:43be36a8}}
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4617): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 4617): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360022653
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023242
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023477
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023488
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023495
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024903
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024916
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027698
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
W/GAV2    ( 4617): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4505/10027)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4505/10027)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4505/10027)
E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4617): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4617): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
I/CheckinService( 3990): Checking schedule, now: 1450240665234 next: 1450240646103
,I/CheckinService( 3990): active receiver: enabled
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=3990, uid=10029, userID:0
,I/CheckinService( 3990): Preparing to send checkin request
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (3990/10029)
,D/PMS     (  906): acquireWL(43f3f0f0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,I/EventLogService( 3990): Accumulating logs since 1450240612415
D/PMS     (  906): releaseWL(43f3f0f0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/wpa_supplicant( 1183): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1183): EAPOL: disable timer tick
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4505): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4505): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4505): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4617/10151)
V/WebViewChromiumFactoryProvider( 4617): Binding Chromium to main looper Looper (main, tid 1) {41d36f80}
I/LibraryLoader( 4617): Expected native library version number "",actual native library version number ""
I/chromium( 4617): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4617): Initializing chromium process, renderers=0
,E/dalvikvm( 3990): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a
W/dalvikvm( 3990): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
,E/AudioManagerAndroid( 4617): BLUETOOTH permission is missing!
,W/dalvikvm( 3990): VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;)
W/dalvikvm( 3990): VFY: unable to resolve virtual method 6547: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
,W/dalvikvm( 3990): VFY: unable to resolve static field 229 (SUPPORTED_ABIS) in Landroid/os/Build;
D/PMS     (  906): acquireWL(43ed08a0): PARTIAL_WAKE_LOCK  AudioMix 0x1 363 1013 null
D/PMS     (  906): acquireWL(43ecd3e0): PARTIAL_WAKE_LOCK  AudioMix 0x1 363 1013 null
D/PMS     (  906): releaseWL(43ecd3e0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/CheckinRequestBuilder( 3990): Checkin reason type: 8 attempt count: 1
,I/Adreno-EGL( 4617): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4617): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4617): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4617): Local Branch: 
I/Adreno-EGL( 4617): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4617): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4617):                  aa63bbd948f41d15fc72f585e
D/WifiService(  906): New client listening to asynchronous messages
I/ActivityManager(  906): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 3990): Failed to find provider info for com.google.android.wearable.settings
,I/NSApplication( 4617): Starting up...
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4617/10151)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4617/10151)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [2][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/Process (  906): killProcessQuiet, pid=4287
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4021/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4021/10160)
I/ActivityManager(  906): Killing 4287:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4287
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/iu.SyncManager( 3990): SYNC; picasa accounts
,D/NetworkLogImpl( 3990): Loaded NetworkSpeedPredictor
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,I/iu.Environment( 3990): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (3990/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (3990/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (3990/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (3990/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (3990/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
,I/iu.UploadsManager( 3990): num queued entries: 0,
,I/iu.UploadsManager( 3990): num updated entries: 0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
I/iu.SyncManager( 3990): NEXT; no task
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4662 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (3990/10029)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (3990/10029)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4662): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4662): isEpsOn(), nState = 0
D/PMS     (  906): acquireWL(4266e408): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4662 1000 null
,D/PMS     (  906): releaseWL(4266e408): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4662): getMobilePolicyEnabled, result = true
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Process (  906): killProcessQuiet, pid=4305
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  906): Killing 4305:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/AutoSetting( 4543): receiver - intent: android.intent.action.USER_PRESENT
,D/AutoSetting( 4543): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/TetherSettings( 3770): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3770): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3770): Cust_ConnectToPC   : Modem_Link>false
,D/        ( 3770): Cust_ConnectToPC   : spcsc>false
D/        ( 3770): Cust_ConnectToPC   : IPT>true
D/        ( 3770): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3770): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/ActivityManager(  906): Recipient 4305
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/SmartNS_Utility( 3770): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3770): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3770): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 3770): onReceive:android.intent.action.USER_PRESENT
I/SmartNS_PSService( 3770): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3770): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3770):  defaultType:0
W/ContextImpl( 3770): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 4662): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4662): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4662): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4662): isEpsOn(), nState = 0
D/WifiService(  906): New client listening to asynchronous messages
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41e57e80
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 1
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41e57e80, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 0
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41e57e80, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41e57e80
E/ActivityThread(  906): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@426b1a18 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@426b1a18 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,I/ActivityManager(  906): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4685 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,W/dalvikvm( 4685): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4685): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4685): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4685): install
,I/MultiDex( 4685): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4685): loading existing secondary dex files
,I/MultiDex( 4685): load found 3 secondary dex files
,I/MultiDex( 4685): install done
,W/dalvikvm( 4685): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4685): VFY: unable to resolve instance field 36
,W/dalvikvm( 4685): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4685): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ProviderInstaller( 4685): Installed default security provider GmsCore_OpenSSL
,D/PMS     (  906): releaseWL(428139f0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  906): NetTransition Wakelock for ConnectedState released by timeout
,W/dalvikvm( 4685): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4685): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/WearableService( 1222): callingUid 10029, callindPid: 1222
,W/dalvikvm( 4685): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4685): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4685): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4685): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4685): Link of class 'Lcom/google/android/gms/common/j/c;' failed
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/LocationInitializer( 3990): Restart initialization of location
,V/Tethering(  906): bSetPropertyMultiRAB:false
,D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: true
E/MDM     ( 1222): [114] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/Tethering(  906): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  906): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  906): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  906): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  906): Found interface wlan0
,D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
,D/CaptivePortalTracker(  906): NoActiveNetworkState
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,D/AccTypeManager( 1343): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ConnectivityHelper( 1271): [onReceive] WIFI(1): CONNECTED
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/PMS     (  906): acquireWL(426e8228): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.backuptransport (1601/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360022653
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023242
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023477
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023488
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023491
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4578/10079)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023495
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024903
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024916
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027698
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1271/10076)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.musicenhancer (3849/10053)
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3826/10154)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.backuptransport (1601/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(4294e5e0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,I/NetworkMonitor( 3826): type=WIFI subType= reason=null isConnected=true
D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  906): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4505/10027)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4505/10027)
D/PMS     (  906): releaseWL(4294e5e0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  906): releaseWL(426e8228): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4505/10027)
W/AccTypeManager( 1343): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/AccTypeManager( 1343): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/AuthorizationBluetoothService( 1360): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1360): Proximity feature is not enabled.,
,D/PMS     (  906): acquireWL(4362fad0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
I/WVCdm   (  363): Level3 Library Nov 20 2013 18:09:31
E/ExternalAccountType( 1343): Unsupported attribute readOnly
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
W/GCoreFlp( 1222): No location to return for getLastLocation()
W/FusedLocationProvider( 1222): location=null
,W/WVCdm   (  363): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  363): CdmEngine::OpenSession
,I/WVCdm   (  363): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  363): CdmEngine::GenerateKeyRequest
D/PMS     (  906): releaseWL(4362fad0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360022653
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023242
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023477
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023488
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023495
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024903
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024916
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027698
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/NativeLibraryUtils( 4685): Install completed successfully. count=14 extracted=0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (2708/10021)
,D/AutoSetting( 4543): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/MobileConnectivityChangeReceiver( 4578): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4578): onReceive CONNECTIVITY_CHANGE networkType=1
,D/WVCdm   (  363): PrepareKeyRequest: nonce=207384104
,D/AutoSetting( 4543): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (4543/10055)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (4617/10151)
,D/AutoSetting( 4543): service - onStartCommand() screen is off, don't request location
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/AutoSetting( 4543): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 4543): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (4543/10055)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4021/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4021/10160)
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,D/PMS     (  906): acquireWL(43d37438): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 3990 10029 WorkSource{10029 com.google.android.gms}
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,I/CheckinService( 3990): Checkin interval check for package: unspecified last checkin: 1450240616136 min interval config: 0 actual interval: 50094
D/PMS     (  906): releaseWL(43d37438): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,I/WVCdm   (  363): CdmEngine::CloseSession
,I/dalvikvm-heap( 4021): Grow heap (frag case) to 13.500MB for 1821008-byte allocation
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=3990, uid=10029, userID:0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (3990/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (3990/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (3990/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,I/WVCdm   (  363): CdmEngine::OpenSession
,I/WVCdm   (  363): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  363): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  363): PrepareKeyRequest: nonce=1684581841
,I/WVCdm   (  363): CdmEngine::CloseSession
,I/Adreno-EGL( 4685): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4685): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4685): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4685): Local Branch: 
I/Adreno-EGL( 4685): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4685): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4685):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4685): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4685): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4685): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4685): Local Branch: 
I/Adreno-EGL( 4685): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4685): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4685):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4685): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4685): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4685): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4685): Local Branch: 
I/Adreno-EGL( 4685): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4685): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4685):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (4685/10029)
,I/jxcore-log( 4454): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 4454): 
,W/Settings( 4685): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinRequestBuilder( 3990): Classify the device as Phone.
,W/dalvikvm( 3990): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/libc    ( 3990): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 3990): [NET] getaddrinfo-,err=8
,D/libc    ( 3990): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    ( 3990): [NET] getaddrinfo-, 1
,D/libc    ( 3990): [NET] getaddrinfo_proxy+
D/libc    (  356): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  356): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  356): [NET] +++++ res_nsend xid =60d9 +++++
D/libc    (  356): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  356): [NET] NOT IN CACHE
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4505/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4505/10027)
,D/libc    (  356): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 28
D/libc    (  356): [NET]res_nsend:resplen=84
D/libc    (  356): [NET]res_queryN: exit 3, ancount=2
D/libc    (  356): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  356): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3990): [NET] getaddrinfo_proxy-, success
,W/fb4a(:<default>):UserScope( 4505): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4505): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/libc    ( 3990): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 3990): [NET] getaddrinfo-,err=8
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4505/10027)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [4][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/libc    ( 3990): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 3990): [NET] getaddrinfo-,err=8
D/libc    ( 3990): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 3990): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4505/10027)
I/CheckinTask( 3990): Sending checkin request (12199 bytes)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4505): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4505/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4505/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4505/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4505/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4505/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4505/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4505/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4505/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4505/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4505/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4505/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4505/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4505/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4505/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4505/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4505/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4505/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4505/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4505/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4505/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4505/10027)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (4505/10027)
,D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
,D/libc    (  356): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  356): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  356): [NET] +++++ res_nsend xid =f051 +++++
D/libc    (  356): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  356): [NET] NOT IN CACHE,
,I/CheckinRequestBuilder( 3990): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  906): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 3990): Failed to find provider info for com.google.android.wearable.settings
,D/libc    (  356): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  356): [NET]res_nsend:resplen=172
D/libc    (  356): [NET]res_queryN: exit 3, ancount=4
D/libc    (  356): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  356): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  906): Find DNS Address www.htc.com/23.59.123.86
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (3990/10029)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=14 [14][2][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (3990/10029)
,I/CheckinRequestBuilder( 3990): Classify the device as Phone.
,I/CheckinTask( 3990): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 3990): Checking schedule, now: 1450240668224 next: 1450763605220
,I/CheckinService( 3990): active receiver: disabled
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=3990, uid=10029, userID:0
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360022653
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023242
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023477
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023488
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023495
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024903
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024916
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027698
I/CheckinService( 3990): Checking schedule, now: 1450240668248 next: 1450763605220
,I/CheckinService( 3990): active receiver: disabled
,D/CheckinService( 3990): Recording last checkin time for package unspecified as 1450240668254
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=3990, uid=10029, userID:0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360022653
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023242
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023477
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023488
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023495
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024903
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024916
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027698
,D/PMS     (  906): releaseWL(43bc3a00): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (3990/10029)
,D/PMS     (  906): acquireWL(43386d78): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 1360): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    ( 1360): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1360): [NET] getaddrinfo-,err=8
D/libc    ( 1360): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1360): [NET] getaddrinfo-, 1
,D/libc    ( 1360): [NET] getaddrinfo_proxy+
D/libc    (  356): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  356): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  356): [NET] +++++ res_nsend xid =2b85 +++++
D/libc    (  356): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  356): [NET] NOT IN CACHE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
,D/libc    (  356): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 240
D/libc    (  356): [NET]res_nsend:resplen=79
,D/libc    (  356): [NET]res_queryN: exit 3, ancount=2
D/libc    (  356): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  356): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1360): [NET] getaddrinfo_proxy-, success
,D/PMS     (  906): releaseWL(43ed08a0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/libc    ( 1360): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1360): [NET] getaddrinfo-,err=8
,D/libc    ( 1360): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1360): [NET] getaddrinfo-,err=8
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
,D/PMS     (  906): acquireWL(43d37828): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
,D/PMS     (  906): releaseWL(43386d78): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
,D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1360/10029)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
,D/PMS     (  906): releaseWL(43d37828): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(43bccca0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
,D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1360/10029)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
,D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1360/10029)
,D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360022653
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023242
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023477
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023488
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023491
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023495
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024903
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024916
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027698
,D/PMS     (  906): releaseWL(43bccca0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=11 [9][1][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,I/GAV2    ( 4617): Thread[GAThread,5,main]: No campaign data found.
,D/WifiStateMachine(  906): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/Process (  906): killProcessQuiet, pid=4348
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/Process (  906): killProcessQuiet, pid=4251
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4348:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
I/ActivityManager(  906): Killing 4251:com.htc.cs.dm/u0a98 (adj 15): empty #18
,I/ActivityManager(  906): Recipient 4348
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  906): Client connection lost with reason: 4
I/ActivityManager(  906): Recipient 4251
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1520): service - handleMessage() stop self
,D/AutoSetting( 1520): service - onDestroy() END
,D/AutoSetting( 1520): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=3806
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3806:com.htc.mediamanager/u0a34 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3806
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=3990, uid=10029, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=3990, uid=10029, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=3990, uid=10029, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=3990, uid=10029, userID:0
,D/AccTypeManager( 1343): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/ActivityManager(  906): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4739 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1271): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
,I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/Launcher( 1271): Deferring update until onResume
D/Launcher( 1271): waitUntilResume // bindAppsUpdated
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
W/AccTypeManager( 1343): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
,D/AccTypeManager( 1343): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,W/SystemReader( 1254): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,E/ExternalAccountType( 1343): Unsupported attribute readOnly
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
,D/PhoneApp( 1239): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4739): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4739): MmsConfig.loadMmsSettings
,D/AutoSetting( 4543): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 4543): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 4543): service - requestNLP() NetworkLocationProvider not enabled
,W/dalvikvm( 4739): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4739): VFY: unable to resolve instance field 36
,W/dalvikvm( 4739): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,I/ActivityManager(  906): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4762 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,V/JNIHelp ( 4739): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4739, uid=10111, userID:0
,I/ProviderInstaller( 4739): Installed default security provider GmsCore_OpenSSL
,D/MessageFrequencyProvider( 4762): onCreate
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  906): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,W/Settings( 4739): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/GetPrviateResource( 4762): GetPrviateResource
,V/GetPrviateResource( 4762): GetPrviateResource
,D/MmsCustomizationProvider( 4762): query uri: content://htc-mms-customization/mms-ua/ua_string
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4739, uid=10111, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4739, uid=10111, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4739, uid=10111, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4739, uid=10111, userID:0
,D/MmsCustomizationProvider( 4762): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4739, uid=10111, userID:0
,D/PMS     (  906): acquireWL(44391468): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4739 10111 null
,I/Babel   ( 4739): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4739): MmsConfig.loadFromDatabase
,E/Babel   ( 4739): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4739): MmsConfig.loadFromResources
,E/Babel   ( 4739): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4739): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/[PluginManager]RegisterService( 4543): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 4543): handle notify Blinkfeed plugin client changed
I/ActivityManager(  906): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/IcingCorporaProvider( 2805): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
D/MessageCustFlag( 4762): sense_version=6.0
D/BTAccessoryUtil( 4762): createReceiver
D/BTAccessoryUtil( 4762): registerReceiver return intent = null
D/MessageCustFlag( 4762): sku_id=99
W/SystemReader( 4762): Cannot find message_ambs_application_id, use default value instead
,D/Messaging( 4762): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4762): networkCode: 
,D/MessageCustFlag( 4762): sku_id=99
D/MmsConfig( 4762): SIE smsPri: null
,D/MmsConfig( 4762): networkCode: 
D/HtcTelephonyCapability( 4762): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4762): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4762): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4762): Cannot find qct_8960_interface, use default value instead
D/PMS     (  906): releaseWL(44391468): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
D/PMS     (  906): acquireWL(442c6db8): PARTIAL_WAKE_LOCK  Icing 0x1 3990 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(442c6db8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(442ade10): PARTIAL_WAKE_LOCK  Icing 0x1 3990 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Delay finish: com.google.android.googlequicksearchbox/.GelStubAppWatcher
,D/PMS     (  906): releaseWL(442ade10): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(44196490): PARTIAL_WAKE_LOCK  Icing 0x1 3990 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  906): acquireWL(440f84d8): PARTIAL_WAKE_LOCK  AsyncService 0x1 4021 10160 null
,I/dalvikvm-heap( 4021): Grow heap (frag case) to 15.199MB for 1821008-byte allocation
D/PMS     (  906): releaseWL(440f84d8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  906): releaseWL(44196490): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Resuming delayed broadcast
,I/dalvikvm-heap( 4021): Grow heap (frag case) to 16.936MB for 1821008-byte allocation
I/ActivityManager(  906): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
D/PMS     (  906): acquireWL(440df398): PARTIAL_WAKE_LOCK  Icing 0x1 3990 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(440df398): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(43f3f0f0): PARTIAL_WAKE_LOCK  Icing 0x1 3990 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,D/PMS     (  906): releaseWL(43f3f0f0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(43f3efb0): PARTIAL_WAKE_LOCK  Icing 0x1 3990 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
,D/PMS     (  906): releaseWL(43f3efb0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(43f3c4d0): PARTIAL_WAKE_LOCK  Icing 0x1 3990 10029 WorkSource{10029 com.google.android.gms}
,D/PackageBroadcastService( 3990): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/PackageBroadcastService( 3990): Null package name or gms related package.  Ignoreing.
D/PMS     (  906): releaseWL(43f3c4d0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(43f22eb0): PARTIAL_WAKE_LOCK  Icing 0x1 3990 10029 WorkSource{10029 com.google.android.gms}
,W/PackageManager(  906): Unable to load service info ResolveInfo{43ed97f8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,I/Icing   ( 3990): updateResources: need to parse f{com.google.android.gms}
,I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1271): loadItems() com.htc.launcher.pageview.WidgetManager@41dc6df0 +
,I/Prism.WidgetManager( 1271): onLoadItems() +
,I/IcingCorporaProvider( 2805): UpdateCorporaTask done [took 497 ms] updated apps [took 497 ms] 
I/ActivityManager(  906): Resuming delayed broadcast
,D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  906): start
,I/GCoreNlp( 1222): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  906): applying state to connected service
D/PMS     (  906): acquireWL(43d340f0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(43d340f0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  906): applying state to connected service
D/PMS     (  906): acquireWL(42de0c40): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42de0c40): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4279c7a0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4279c7a0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1271): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1271): onLoadItems() -
,I/Prism.ItemManager( 1271): loadItems() com.htc.launcher.pageview.WidgetManager@41dc6df0 -
,D/PhoneApp( 1239): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1239): -- N1 =0
,D/PhoneApp( 1239): -- N2 =0
,D/PhoneApp( 1239): -- N3 =0
,I/Icing   ( 3990): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 3990): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,I/ActivityManager(  906): Killing 3849:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,D/Process (  906): killProcessQuiet, pid=3849
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  906): releaseWL(43f22eb0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Recipient 3849
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Messaging( 4762): mNeedToUpdateDate2 start
,D/MmsConfig( 4762): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4762): startAsyncQueryReports ---
,D/SettingsManager( 4762): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41d442d8
D/MmsAsyncWorkHandler( 4762): 
D/MmsAsyncWorkHandler( 4762): HM tk = 20001
,D/ReportIndicatorCache( 4762): MSG_QUERY_REPORTS >>
I/Messaging( 4762): mccmnc> 
,D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/MmsSmsV2Provider( 1239):  phoneType = -1
,D/MmsSmsV2Provider( 1239): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/DraftCache( 4762): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4762): [DraftCache/1] refresh
,D/MmsConfig( 4762): networkCode: 
,D/Messaging( 4762): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/MmsSmsV2Provider( 1239):  phoneType = -1
,D/MmsSmsV2Provider( 1239): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/MessageCustFlag( 4762): sense_version=6.0
D/MmsSmsV2Provider( 1239):  phoneType = -1
,D/MmsSmsV2Provider( 1239): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/Jerry   ( 4762): start to preload cursor >>>>>>>
D/PhoneStorageUtil( 4762): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4762): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4762): createReceiver
,D/Messaging( 4762): mNeedToUpdateDate2: false
D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1239): sku_id=99
D/TelephUtils( 1239): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
V/MmsProvider( 1239): Update uri=content://mms, match=0
,V/MmsProvider( 1239): selection=st=129 AND m_type!=134
,D/Messaging( 4762): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4762): TransactionService is going to be woken up.
,D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/MmsSmsV2Provider( 1239):  phoneType = -1
V/TransactionService( 4762): 1-Creating TransactionService
,D/DraftCache( 4762): [DraftCache/475] rebuildCache
,D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/MmsSmsV2Provider( 1239):  phoneType = -1
,D/MmsSmsV2Provider( 1239): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/Messaging( 4762): ViewCache CreatePreload
,D/Messaging( 4762): ViewCache CreatePreloadOnlyMultipleOpsList
V/TransactionService( 4762): onStartCommand: 1
,D/MmsSystemEventReceiver( 4762): unRegisterForConnectionStateChanges
D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
V/TransactionService( 4762): 4-Handling incoming message: { when=-1ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4762): Loading previous transactions.
,D/Jerry   ( 1239): URI_DRAFT
,D/Messaging( 4762): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/Cust_MMSMS( 4762): _has_set_default_values_2=true
D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/DraftCache( 4762): hasDraft() = false mNeedNotifyChange = true
D/AccFlag ( 1239): device_type: 1
D/DraftCache( 4762): [DraftCache/475] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4762): 
D/MmsAsyncWorkHandler( 4762): HM tk = 20002
D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/MsgPreferenceUtils( 4762): def_index: 0
D/TransactionService( 4762): Force set service start id to 1
V/TransactionService( 4762): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 4762): unRegisterForConnectionStateChanges
,D/AccFlag ( 1239): sku_id=99
D/TransactionService( 4762): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4762): Destroying TransactionService
,D/MsgPreferenceUtils( 4762): globalIndex = 1
,V/TransactionService( 4762): 4-Handling incoming message: { when=-5ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
D/MsgPreferenceUtils( 4762): phone state: true
D/MsgPreferenceUtils( 4762): sd state: false
,D/MsgPreferenceUtils( 4762): vIndex = 0
,D/TelephUtils( 1239): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1239): sku_id=99
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{4271d7f8 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  906): acquireWL(437b7960): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  906): sending alarm PendingIntent{42294420: PendingIntentRecord{424b2a98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=120402, Int=0
,D/PMS     (  906): releaseWL(437b7960): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/GAV4    ( 4739): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  906): killProcessQuiet, pid=4376
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4376:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4376
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 1
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=3990, uid=10029, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=3990, uid=10029, userID:0
,I/CheckinService( 3990): Done disabling old GoogleServicesFramework version
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=3990, uid=10029, userID:0
,D/PMS     (  906): acquireWL(4269ba68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4269ba68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1587): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(44334cd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(44334cd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1587): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(43c9db58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  906): sending alarm PendingIntent{4438bfd8: PendingIntentRecord{43c7fab8 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=126919, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{43bda450: PendingIntentRecord{438baf30 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=135034, Int=0
,D/PMS     (  906): acquireWL(42105a48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=18 [16][3][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(427cb1c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(427cb1c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42105a48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4429abb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
,D/PMS     (  906): releaseWL(43c9db58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360022653
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023242
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023477
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023488
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023495
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024903
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024916
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027698
,D/PMS     (  906): releaseWL(4429abb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4353e0f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360022653
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023242
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023477
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023488
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023495
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024903
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024916
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027698
,D/PMS     (  906): acquireWL(438233c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(43bc1068): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1222): Vacuum at: now=1450240694889 tag=VacuumService
,D/PMS     (  906): releaseWL(4353e0f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(438233c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(43bc1068): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(44286d48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360022653
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023242
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023477
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023488
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023495
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024903
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024916
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027698
,D/PMS     (  906): releaseWL(44286d48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(43f37240): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360022653
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023242
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023477
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023488
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023495
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024903
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024916
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027698
,D/PMS     (  906): releaseWL(43f37240): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(43f19aa0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360022653
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023242
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023477
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023488
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023495
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024903
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024916
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027698
,D/PMS     (  906): releaseWL(43f19aa0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(44406ae8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL,
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360022653
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023242
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023477
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023488
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023495
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024903
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024916
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027698
,D/PMS     (  906): releaseWL(44406ae8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42738740): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360022653
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023242
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023477
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023488
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023495
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024903
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024916
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027698
,D/PMS     (  906): acquireWL(43d381f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(43d381f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4380f068): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42738740): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(437f84c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360022653
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023242
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023477
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023488
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023495
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024903
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024916
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027698
,D/PMS     (  906): releaseWL(437f84c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1222): Scheduling Phenotype for one-off execution 3797 seconds from now (1450240695626)
,D/GetConfigurationSnapshotOperation( 1222): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1222): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1222): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1222): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1222): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1222): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1222): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  906): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
W/dalvikvm( 1222): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1222): [NET] getaddrinfo-,err=8
D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1222): [NET] getaddrinfo-, 1
D/libc    ( 1222): [NET] getaddrinfo_proxy+
D/libc    (  356): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  356): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  356): [NET] +++++ res_nsend xid =5044 +++++
D/libc    (  356): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  356): [NET] NOT IN CACHE
,D/libc    (  356): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  356): [NET]res_nsend:resplen=87
D/libc    (  356): [NET]res_queryN: exit 3, ancount=2
D/libc    (  356): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  356): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1222): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1222): [NET] getaddrinfo-,err=8
D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1222): [NET] getaddrinfo-,err=8
,D/PMS     (  906): releaseWL(4380f068): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42948c60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 4543): service - mHandler: update timezone
,D/AutoSetting( 4543): service - handleMessage() stop self
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360022653
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023242
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023477
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023488
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023495
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024903
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024916
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027698
,D/AutoSetting( 4543): service - handleMessage() quit looper
,D/AutoSetting( 4543): service - onDestroy() END
D/PMS     (  906): releaseWL(42948c60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(43e39ad0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/Process (  906): killProcessQuiet, pid=4390
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  906): Killing 4390:com.android.settings:remote/1000 (adj 15): empty #17
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [8][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/AutoSetting( 1520): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360022653
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023242
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023477
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023488
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023495
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024903
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024916
I/ActivityManager(  906): Recipient 4390
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027698
,W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1520): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1520): service - onCreate()
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1520): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1520): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/PMS     (  906): releaseWL(43e39ad0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AutoSetting( 1520): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1520): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1520): service - mHandler: update timezone
D/DotMatrix( 1587): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
D/DotMatrix( 1587): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,D/AutoSetting( 1520): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1520): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1520): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1520): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1587): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1587): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1117): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41d757b8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.htclocationservice 1 8 3 11
,D/PMS     (  906): acquireWL(43f465e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{426fe8b8: PendingIntentRecord{426ee4f0 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=140888, Int=0
,D/GpsLocationProvider(  906): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  906): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  906): acquireWL(43bf2710): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/PMS     (  906): releaseWL(43f465e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  356): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  356): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  356): [NET] +++++ res_nsend xid =ac6 +++++
D/libc    (  356): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  356): [NET] NOT IN CACHE
,D/libc    (  356): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  356): [NET]res_nsend:resplen=243
D/libc    (  356): [NET]res_queryN: exit 3, ancount=10
D/libc    (  356): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  356): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo_proxy-, success
I/global  (  906): call createSocket() return a new socket.
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  906): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  906): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  906): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  906):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  906): releaseWL(43bf2710): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/ContactMessageStore( 1239): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1239): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{43e71190 u0 com.htc.htclocationservice/.AutoSettingService}
,D/AutoSetting( 1520): service - handleMessage() stop self
,D/AutoSetting( 1520): service - onDestroy() END
,D/AutoSetting( 1520): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=4104
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4104:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4104
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(433432b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10027}
,V/AlarmManager(  906): sending alarm PendingIntent{43b4f660: PendingIntentRecord{4410a870 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=173280, Int=0
,D/PMS     (  906): releaseWL(433432b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1239): switchBindHtcMsgCursor: null
,D/PMS     (  906): acquireWL(43e82430): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42294420: PendingIntentRecord{424b2a98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=180402, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43e82430): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4442efa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): releaseWL(4442efa8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1587): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43660318): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43660318): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(434f1d40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/PMS     (  906): acquireWL(44029210): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,V/AlarmManager(  906): sending alarm PendingIntent{41ea75e8: PendingIntentRecord{427291d8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=216404, Int=0
,I/ActivityManager(  906): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4846 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  906): sending alarm PendingIntent{42642fc8: PendingIntentRecord{42711338 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1450240769922, Int=10800000
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(43710b10): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(434f1d40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10049}
,D/PMS     (  906): releaseWL(44029210): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(43710b10): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.aurora (4846/10049)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360022653
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023242
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023477
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023488
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023495
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024903
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024916
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027698,
D/Process (  906): killProcessQuiet, pid=4425
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4425:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4425
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(428f25e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42294420: PendingIntentRecord{424b2a98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=240402, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(428f25e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(4373b318): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4373b318): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(43e793d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42294420: PendingIntentRecord{424b2a98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=300402, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43e793d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(4374a040): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4374a040): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4454): Connected to the server!
I/jxcore-log( 4454): 
,I/chromium( 4454): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 4454): --- start :testFindPeers.js---
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): testFindPeers created [object Object]
I/jxcore-log( 4454): 
,I/jxcore-log( 4454): serverPort is 8876
I/jxcore-log( 4454): 
W/dalvikvm( 4454): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4454): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4454): threadid=1: thread exiting with uncaught exception (group=0x41903e30)
,E/ActivityManager(  906): App crashed! Process: com.test.thalitest
E/AndroidRuntime( 4454): FATAL EXCEPTION: main
E/AndroidRuntime( 4454): Process: com.test.thalitest, PID: 4454
E/AndroidRuntime( 4454): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4454): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:134)
E/AndroidRuntime( 4454): 	,at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:133)
E/AndroidRuntime( 4454): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:183)
E/AndroidRuntime( 4454): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:95)
E/AndroidRuntime( 4454): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:92)
E/AndroidRuntime( 4454): 	at io.jxcore.node.JXcoreExtension$5.Receiver(JXcoreExtension.java:155)
E/AndroidRuntime( 4454): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4454): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4454): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4454): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4454): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4454): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4454): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4454): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4454): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4454): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4454): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4454): 	at dalvik.system.NativeStart.main(Native Method)
W/ActivityManager(  906):   Force finishing activity com.test.thalitest/.MainActivity
,D/Process (  906): killProcessQuiet, pid=4662
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
I/ActivityManager(  906): Killing 4662:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,D/Process ( 4454): killProcess, pid=4454
,D/Process ( 4454): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/ActivityManager(  906): Recipient 4454
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.test.thalitest (pid 4454) has died.
I/WindowState(  906): WIN DEATH: Window{4253f518 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  906): Client connection lost with reason: 4
,I/ActivityManager(  906): Recipient 4662
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  906): Client connection lost with reason: 4
,W/Binder  ( 1208): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1208): java.lang.NullPointerException
W/Binder  ( 1208): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1208): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1208): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1208): 	at dalvik.system.NativeStart.run(Native Method)
W/InputMethodManagerService(  906): Got RemoteException sending setActive(false) notification to pid 4454 uid 10389
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(428142b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42294420: PendingIntentRecord{424b2a98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=360402, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(428142b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43e89a28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43e89a28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(43ba5198): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42294420: PendingIntentRecord{424b2a98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=420402, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43ba5198): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43830380): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43830380): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(4432f568): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42294420: PendingIntentRecord{424b2a98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=480402, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4432f568): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43344eb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43344eb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  906): acquireWL(43e42148): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43e42148): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1587): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  402): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(43947420): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42294420: PendingIntentRecord{424b2a98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=540403, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43947420): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43dedc08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43dedc08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4332cba8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42294420: PendingIntentRecord{424b2a98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=600402, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4332cba8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43b811c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43b811c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  349): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1239): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1239): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1239): sku_id=99
D/ContactMessageStore( 1239): start background delete task...
,D/ContactMessageStore( 1239): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1239): size: 0 , 0
,D/ContactMessageStore( 1239): Background delete complete
,D/PMS     (  906): acquireWL(43ea00b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42294420: PendingIntentRecord{424b2a98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=660402, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1271): Grow heap (frag case) to 12.649MB for 50416-byte allocation
,D/PMS     (  906): releaseWL(43ea00b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(441124a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(441124a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(433866d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42294420: PendingIntentRecord{424b2a98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=720402, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(433866d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43beefe0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43beefe0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4287fdf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42294420: PendingIntentRecord{424b2a98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=780403, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4287fdf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43bf0560): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43bf0560): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4377ae98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42294420: PendingIntentRecord{424b2a98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=840403, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4377ae98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43df2410): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43df2410): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(443096f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42294420: PendingIntentRecord{424b2a98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=900402, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(443096f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43ea4258): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43ea4258): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,D/PMS     (  906): acquireWL(42eff5c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42294420: PendingIntentRecord{424b2a98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=960402, Int=0
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42eff5c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43dc2820): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43dc2820): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(434f8360): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41f6fa00: PendingIntentRecord{426c2f58 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=787177, Int=0
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  906): sending alarm PendingIntent{43753058: PendingIntentRecord{43c36b00 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450240956926, Int=1800000
,V/AlarmManager(  906): sending alarm PendingIntent{426b78c8: PendingIntentRecord{429240e8 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450241490334, Int=900000
,V/AlarmManager(  906): sending alarm PendingIntent{42713f18: PendingIntentRecord{42770e90 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450241565752, Int=0
,D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,D/PMS     (  906): acquireWL(439a5a30): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 3990 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=4879 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PMS     (  906): acquireWL(429397c8): PARTIAL_WAKE_LOCK  Event Log Service 0x1 3990 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(439a5a30): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/EventLogService( 3990): Aggregate from 1450240665316 (log), 1450239156870 (data)
,W/ContextImpl( 4879): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4879): call getInstance()
,D/PowerUsageList:PowerUsageHelper( 4879): MY_DEBUG = false
D/PMS     (  906): acquireWL(43f1a638): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4879 1000 null
,D/SmartSyncUtils( 4879): isEpsOn(), nState = 0
,D/PMS     (  906): releaseWL(434f8360): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): releaseWL(43f1a638): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncScreenOnOffTimeReceiver( 4879): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4879): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/PMS     (  906): acquireWL(42ee4500): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4879 1000 null
D/SmartSyncScreenOnOffTimeReceiver( 4879): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4879): SettingOnTime = 1450245600000, randomSettingOnTime = 1450244762000
D/SmartSyncScreenOnOffTimeReceiver( 4879): SettingOffTime = 1450317600000, randomSettingOffTime = 1450321279000
D/SmartSyncScreenOnOffTimeReceiver( 4879): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4879): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 4879): bNightModeTurnOffOnce = false
,D/PMS     (  906): acquireWL(43e35ac8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41e81e98: PendingIntentRecord{438a0310 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_OFF_NETWORK_BY_CHECK, t=0, cnt=1, w=1450241566120, Int=0
,W/ContextImpl( 4879): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  906): Delay finish: com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver
,D/PMS     (  906): releaseWL(42ee4500): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4879): getMobilePolicyEnabled, result = true
,D/SmartSyncDataLinkTurnOffService( 4879): turnOffMobile bPolicyEnabled = true
,D/WifiStateMachine(  906): WiFiDisplay: getWifidisplayApEnabled=false
,D/SmartSyncUtils( 4879): isWifiHotSpotEnabled = false
,D/WifiService(  906): New client listening to asynchronous messages
D/SmartSyncDataLinkTurnOffService( 4879): turnOffMobile bCheckMobileData = false
,D/LocationManagerService(  906): getProviders()=[gps, network]
,D/LocationManagerService(  906): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
,D/LocationManagerService(  906): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/SmartSyncDataLinkTurnOffService( 4879): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
,D/SmartSyncUtils( 4879): isCharging status = 5
,D/SmartSyncDataLinkTurnOffService( 4879): turnOffWifi ui setting = true
,D/WifiStateMachine(  906): WiFiDisplay: getWifidisplayApEnabled=false
,D/SmartSyncUtils( 4879): isWifiHotSpotEnabled = false
,D/SmartSyncUtils( 4879): isWifiCallingOn, bOn = false
,D/SmartSyncDataLinkTurnOffService( 4879): turnOffWifi bCheckWifiData = true
,D/SmartSyncDataLinkTurnOffService( 4879): turnOffWifi bWifiConnected = true
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.htcpowermanager (4879/1000)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360022653
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023242
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023477
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023488
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023495
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024903
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024916
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027698
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): releaseWL(43e35ac8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): releaseWL(429397c8): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): acquireWL(4434e2c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  906): sending alarm PendingIntent{43ed2bb8: PendingIntentRecord{43a20d28 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1008970, Int=0
,D/PMS     (  906): acquireWL(43e41c28): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(43e41c28): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4434e2c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(433d1590): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1360 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
,D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1360/10029)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1360/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360022653
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023242
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023477
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023488
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023491
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023495
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024903
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024916
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027698
,D/PMS     (  906): releaseWL(433d1590): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=3 [161][5][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(43341af0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42294420: PendingIntentRecord{424b2a98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1020402, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43341af0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(428c6d20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(428c6d20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42dfd878): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42dfd878): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1587): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(428ba1c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42294420: PendingIntentRecord{424b2a98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1080402, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(428ba1c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43e706b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43e706b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(443d6398): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000},
,V/AlarmManager(  906): sending alarm PendingIntent{42294420: PendingIntentRecord{424b2a98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1140402, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false),
,D/PMS     (  906): releaseWL(443d6398): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42dfe438): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42dfe438): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(43f22560): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{43f3b1d0: PendingIntentRecord{441ff418 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_OFF_WIFI_RETRY, t=0, cnt=1, w=1450241746220, Int=0
,W/ContextImpl( 4879): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  906): releaseWL(43f22560): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/SmartSyncDataLinkTurnOffService( 4879): turnOffWifi ui setting = true
,D/WifiStateMachine(  906): WiFiDisplay: getWifidisplayApEnabled=false
D/SmartSyncUtils( 4879): isWifiHotSpotEnabled = false
,D/SmartSyncUtils( 4879): isWifiCallingOn, bOn = false
,D/SmartSyncDataLinkTurnOffService( 4879): turnOffWifi bCheckWifiData = false
,D/SmartSyncDataLinkTurnOffService( 4879): turnOffWifi bWifiConnected = true
,D/LocationManagerService(  906): getProviders()=[gps, network]
,D/LocationManagerService(  906): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.htcpowermanager (4879/1000)
D/LocationManagerService(  906): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/SmartSyncDataLinkTurnOffService( 4879): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
D/SmartSyncUtils( 4879): isCharging status = 5
,D/PMS     (  906): acquireWL(43e4da70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43e4da70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  906): << updateStatus
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1587): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,W/ContextImpl( 4879): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3770): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 3770): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3770): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3770): Cust_ConnectToPC   : spcsc>false
D/        ( 3770): Cust_ConnectToPC   : IPT>true
,D/        ( 3770): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3770): project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3770): Index of the first 1 = 3
,W/Settings( 3770): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3770): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3770): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3770): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 3770): [ACC]android_networking:tethering_guard_support=false
W/ContextImpl( 3770): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/ContextImpl( 3770): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43d62f00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42294420: PendingIntentRecord{424b2a98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1200402, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43d62f00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43f2e9b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43f2e9b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1587): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  349): inotify_add_watch failed. (No such file or directory),
,D/PMS     (  906): acquireWL(43d321a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43d321a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
,D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1587): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43bdd800): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42294420: PendingIntentRecord{424b2a98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1260402, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43bdd800): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43890838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43890838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4371a918): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): releaseWL(4371a918): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1587): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4431dd08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42294420: PendingIntentRecord{424b2a98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1320402, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4431dd08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(437b8f58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1587): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(437b8f58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42c1a170): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42c1a170): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,D/PowerUI ( 1117): closing low battery warning: level=100
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1587): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4430d990): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42294420: PendingIntentRecord{424b2a98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1380402, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4430d990): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(438042f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(438042f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1587): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PMS     (  906): runPSCheck
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(44289790): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(44289790): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1587): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(442a3040): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42294420: PendingIntentRecord{424b2a98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1440402, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1271): Grow heap (frag case) to 12.649MB for 50416-byte allocation
,D/PMS     (  906): releaseWL(442a3040): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43f1ab18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): releaseWL(43f1ab18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1587): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(438d24c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(438d24c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1117): closing low battery warning: level=100
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1587): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4377b018): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42294420: PendingIntentRecord{424b2a98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1500403, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4377b018): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4432e298): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4432e298): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1587): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42e1f980): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42294420: PendingIntentRecord{424b2a98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1560402, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1271): Grow heap (frag case) to 12.725MB for 50416-byte allocation
D/PMS     (  906): releaseWL(42e1f980): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43e39658): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43e39658): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1587): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(436c1178): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(436c1178): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1587): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43e3a138): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42294420: PendingIntentRecord{424b2a98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1620402, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(43e3a138): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(44393080): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1587): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): releaseWL(44393080): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(436ba710): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(436ba710): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1587): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(428e3940): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42294420: PendingIntentRecord{424b2a98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1680402, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(428e3940): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(43836dd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1587): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PMS     (  906): releaseWL(43836dd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(43d95108): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(43d95108): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1587): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(433b7a10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42294420: PendingIntentRecord{424b2a98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1740402, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(433b7a10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4432bf48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): releaseWL(4432bf48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1587): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): acquireWL(4444e428): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1587): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): releaseWL(4444e428): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42de23d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{42294420: PendingIntentRecord{424b2a98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1800402, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42de23d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(443172f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(443172f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1587): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  349): inotify_add_watch failed. (No such file or directory),
,D/PMS     (  906): acquireWL(4288f890): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4288f890): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1587): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
I/ProcessStatsService(  906): Prepared write state in 45ms
D/PMS     (  906): acquireWL(43eee850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{42294420: PendingIntentRecord{424b2a98 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1860402, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,I/ProcessStatsService(  906): Pruning old procstats: /data/system/procstats/state-2015-12-15-18-46-11.bin
,D/PMS     (  906): releaseWL(43eee850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4440eb98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1587): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(4440eb98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/PMS     (  906): runPSCheck
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4934): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4934): ====startRecUseTime====
D/htc.customization.log.level( 4934):  is 
W/CustomizationLogLevel( 4934): Level value is invalid, use default level 2
D/CustomizationManager( 4934):  Read ACC file spent 0.113 (s)
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
V/CustomizationCIDLoader( 4934): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4934): Parsing tag category name = system
I/CustomizationCIDLoader( 4934): Parsing tag category name = application
I/CustomizationCIDLoader( 4934): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4934): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4934): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4934): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4934): Parsing tag category name = Settings
D/CustomizationManager( 4934):  Read CID file spent 0.172 (s)
D/CustomizationManager( 4934):  All configurations done spent 0.172 (s)
W/HtcNativeFlag( 4934): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4934): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4934): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4934): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  906): deletePackageAsUser: pkg=com.test.thalitest, pid=4934, uid=2000 user=0
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  906): killProcessQuiet, pid=4617
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=4594
I/ActivityManager(  906): Killing 4617:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1802s
I/ActivityManager(  906): Killing 4594:com.android.chrome/u0a96 (adj 15): empty for 1802s
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=4578
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  906): killProcessQuiet, pid=3826
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  906): Killing 4578:com.google.android.setupwizard/u0a79 (adj 15): empty for 1802s
I/ActivityManager(  906): Killing 3826:com.google.android.music:main/u0a154 (adj 15): empty for 1802s
I/ActivityManager(  906): Recipient 4578
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3826
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  906): Client com.google.android.music (pid 3826): Died!
W/asset   (  906): Copying FileAsset 0x69323b28 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  906): Recipient 4617
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4594
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/PackageSettings(  906): Skipping PackageSetting{424d5160 com.example.hello/10397} due to missing metadata
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1587): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1587): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1587): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/SQLiteConnectionPool( 3990): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/PMS     (  906): acquireWL(4444c950): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
W/GeofencerStateMachine( 1222): Ignoring removeGeofence because network location is disabled.
I/Launcher( 1271): Deferring update until onResume
D/Launcher( 1271): waitUntilResume // bindAppsRemoved
D/PMS     (  906): releaseWL(4444c950): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/AccTypeManager( 1343): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/VoicemailCleanupService( 1294): Cleaning up data for package: com.test.thalitest
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/[PluginManager]RegisterService( 4543): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 4543): handle notify Blinkfeed plugin client changed
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
W/SystemReader( 1254): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/Prism.PackageStateRece_( 1271): action: android.intent.action.PACKAGE_REMOVED
W/AccTypeManager( 1343): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1343): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/IcingCorporaProvider( 2805): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
E/ExternalAccountType( 1343): Unsupported attribute readOnly
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/ActivityManager(  906): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4949 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
D/PhoneApp( 1239): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  906): acquireWL(426640f8): PARTIAL_WAKE_LOCK  Icing 0x1 3990 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(426640f8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(41fb4468): PARTIAL_WAKE_LOCK  Icing 0x1 3990 10029 WorkSource{10029 com.google.android.gms}
E/SQLiteLog( 2805): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2805): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x63a7c3c8
E/IcingCorporaProvider( 2805): Exception thrown from notifyTableChanged
E/IcingCorporaProvider( 2805): java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2805): 	at apg.a(PG:301)
E/IcingCorporaProvider( 2805): 	at apg.c(PG:222)
E/IcingCorporaProvider( 2805): 	at clo.b(PG:660)
E/IcingCorporaProvider( 2805): 	at clo.a(PG:651)
E/IcingCorporaProvider( 2805): 	at clo.g(PG:597)
E/IcingCorporaProvider( 2805): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/IcingCorporaProvider( 2805): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/IcingCorporaProvider( 2805): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/IcingCorporaProvider( 2805): 	at clp.Rl(PG:910)
E/IcingCorporaProvider( 2805): 	at clr.tL(PG:827)
E/IcingCorporaProvider( 2805): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/IcingCorporaProvider( 2805): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/IcingCorporaProvider( 2805): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/IcingCorporaProvider( 2805): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/IcingCorporaProvider( 2805): 	at android.os.Looper.loop(Looper.java:157)
E/IcingCorporaProvider( 2805): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/IcingCorporaProvider( 2805): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2805): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/IcingCorporaProvider( 2805): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/IcingCorporaProvider( 2805): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/IcingCorporaProvider( 2805): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/IcingCorporaProvider( 2805): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/IcingCorporaProvider( 2805): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/IcingCorporaProvider( 2805): 	at apa.a(PG:382)
E/IcingCorporaProvider( 2805): 	at apg.i(PG:325)
E/IcingCorporaProvider( 2805): 	at aph.call(PG:215)
E/IcingCorporaProvider( 2805): 	at apg.a(PG:299)
E/IcingCorporaProvider( 2805): 	... 15 more
W/IcingCorporaProvider( 2805): notifyTableChanged failed.
W/IcingCorporaProvider( 2805): Table change notification failed for TableStorageSpec[applications]
I/IcingCorporaProvider( 2805): UpdateCorporaTask done [took 317 ms] updated apps [took 317 ms] 
D/PMS     (  906): releaseWL(41fb4468): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
E/SQLiteDatabase( 4949): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
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
E/SQLiteOpenHelper( 4949): Couldn't open ClientFlag.db for writing (will try read-only):
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
W/SQLiteOpenHelper( 4949): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4949): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
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
W/dalvikvm( 4949): threadid=11: thread exiting with uncaught exception (group=0x41903e30)
E/ActivityManager(  906): App crashed! Process: com.google.android.apps.docs
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
D/Process ( 4949): killProcess, pid=4949
E/SQLiteDatabase( 4949): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
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
E/SQLiteDatabase( 4949): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
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
D/Process ( 4949): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/SQLiteOpenHelper( 4949): Couldn't open ClientFlag.db for writing (will try read-only):
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
E/SQLiteOpenHelper( 4949): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
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
I/ActivityManager(  906): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4968 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  906): Recipient 4949
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Process (  906): killProcessQuiet, pid=4685
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.appDiedLocked:4131 
I/ActivityManager(  906): Process com.google.android.apps.docs (pid 4949) has died.
I/ActivityManager(  906): Killing 4685:com.google.android.gms.unstable/u0a29 (adj 15): empty for 1800s
I/ActivityManager(  906): Recipient 4685
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ContextImpl( 4968): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  906): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4983 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4968): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
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
W/dalvikvm( 4968): threadid=10: thread exiting with uncaught exception (group=0x41903e30)
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
E/ActivityManager(  906): App crashed! Process: com.android.keychain
D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
D/AppTag  ( 4983): getInstance(Context context)
D/AppTag  ( 4983): getInstance(Context context)
D/Process ( 4968): killProcess, pid=4968
D/Process ( 4968): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/AppTag  ( 4983): onCreate()
E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1450242470704.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1271): loadItems() com.htc.launcher.pageview.WidgetManager@41dc6df0 +
I/Prism.WidgetManager( 1271): onLoadItems() +
I/ActivityManager(  906): Recipient 4968
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.android.keychain (pid 4968) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/PMS     (  906): acquireWL(43f0a4c8): PARTIAL_WAKE_LOCK  AsyncService 0x1 4021 10160 null
D/PMS     (  906): releaseWL(43f0a4c8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/TrimMemoryManager( 1271): [trimMemory] 5
W/dalvikvm( 4052): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 3990): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 3990): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 3990): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 3990): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 3990): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 3990): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 3990): Removing dialog suppression flag for package com.test.thalitest
I/ActivityManager(  906): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
E/SQLiteLog( 3990): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 3990): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x65af0d68
W/dalvikvm( 3990): threadid=39: thread exiting with uncaught exception (group=0x41903e30)
E/ActivityManager(  906): App crashed! Process: com.google.android.gms
E/AndroidRuntime( 3990): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 3990): Process: com.google.android.gms, PID: 3990
E/AndroidRuntime( 3990): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 3990): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 3990): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 3990): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 3990): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 3990): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 3990): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 3990): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 3990): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 3990): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 3990): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 3990): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 3990): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 3990): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 3990): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 3990): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 3990): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 3990): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 3990): 	at java.lang.Thread.run(Thread.java:864)
D/Process ( 3990): killProcess, pid=3990
W/PackageManager(  906): Unable to load service info ResolveInfo{444061e8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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

```
