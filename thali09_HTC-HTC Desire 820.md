#### Test 50650278b44f053_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
V/LightsService(  908): setLight #0: color=#1a
V/LightsService(  908): setLight #0: color=#14
,--------- beginning of /dev/log/main
I/SensorManager(  908): mEventCount = 900
E/cutils-trace( 4445): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4445): ====startRecUseTime====
D/htc.customization.log.level( 4445):  is 
W/CustomizationLogLevel( 4445): Level value is invalid, use default level 2
D/CustomizationManager( 4445):  Read ACC file spent 0.060 (s)
D/CIDMapFileReader( 4445): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4445): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4445): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4445): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4445): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4445): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4445): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4445): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4445): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4445): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4445): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4445): Parsing tag category name = system
I/CustomizationCIDLoader( 4445): Parsing tag category name = application
I/CustomizationCIDLoader( 4445): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4445): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4445): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4445): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4445): Parsing tag category name = Settings
D/CustomizationManager( 4445):  Read CID file spent 0.101 (s)
D/CustomizationManager( 4445):  All configurations done spent 0.101 (s)
W/HtcNativeFlag( 4445): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4445): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4445): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4445): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  908): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  908): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  908): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  908): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  908): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  908): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  908): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4445
D/PMS     (  908): acquireHCC(436e32d0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 908 1000 null
D/PMS     (  908): acquireHCC(43c4a5d0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 908 1000 null
W/asset   (  908): Copying FileAsset 0x6cdba3f8 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  908): @test_code: getHtcIntentFlag: 0 obj: 1141997984
I/FeedHostManager( 1273): [onPause]
I/FeedProviderManager( 1273): onPause
I/FeedHostManager( 1273): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41b74ea8
I/SocialFeedProvider( 1273): +onPause
I/SocialFeedProvider( 1273): -onPause
D/PMS     (  908): acquireWL(43c12e68): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 908 1000 null
I/ActivityManager(  908): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4456 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1273): [trimMemory] 20
W/asset   ( 4456): Copying FileAsset 0x5c906c90 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4456): Binding Chromium to main looper Looper (main, tid 1) {41b606e8}
I/LibraryLoader( 4456): Expected native library version number "",actual native library version number ""
I/chromium( 4456): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4456): Initializing chromium process, renderers=0
D/PMS     (  908): acquireWL(442c0f88): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  908): acquireWL(442b43a0): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
W/System.err(  908): java.lang.Throwable: stack dump
D/BluetoothManagerService(  908): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  908): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43ca2d08:true
W/System.err(  908): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  908): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  908): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  908): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  908): 	at dalvik.system.NativeStart.run(Native Method)
,D/PMS     (  908): releaseWL(442c0f88): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothAdapter( 4456): 1102540280: getState(). Returning 12
I/Adreno-EGL( 4456): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4456): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4456): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4456): Local Branch: 
I/Adreno-EGL( 4456): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4456): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4456):                  aa63bbd948f41d15fc72f585e
W/chromium( 4456): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4456): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4456): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4456): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4456): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4456): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4456): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4456): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4456): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4456): CordovaWebView is running on device made by: HTC
W/AwContents( 4456): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  908): Disable input method client, pid=1273
W/ResourceType( 4456): No package identifier when getting name for resource number 0x00000064
I/InputMethodManagerService(  908): Enable input method client, pid=4456
I/InputMethodManager( 4456): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41ba84a8, mServedView=org.apache.cordova.engine.SystemWebView{41b6e110 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1208): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1208): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 4456): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  908): Displayed com.test.thalitest/.MainActivity: +403ms
D/PMS     (  908): releaseWL(43c12e68): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/JsMessageQueue( 4456): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 4456): JniHelper::setJavaVM(0x4163b048), pthread_self() = 1663809192
D/JX-Cordova( 4456): jxcore cordova android initializing
,I/dalvikvm-heap( 4456): Grow heap (frag case) to 11.631MB for 144892-byte allocation
,I/dalvikvm-heap( 4456): Grow heap (frag case) to 11.748MB for 217334-byte allocation
,I/dalvikvm-heap( 4456): Grow heap (frag case) to 11.915MB for 325996-byte allocation
,I/dalvikvm-heap( 4456): Grow heap (frag case) to 12.189MB for 488990-byte allocation
,I/dalvikvm-heap( 4456): Grow heap (frag case) to 12.594MB for 733480-byte allocation
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,I/dalvikvm-heap( 4456): Grow heap (frag case) to 14.121MB for 1650320-byte allocation
,W/CpuWake (  908): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  908): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  908): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  908): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  908): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  908): <<release mCpuPerf_Freq wakelock
D/PMS     (  908): releaseHCC(436e32d0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  908): releaseHCC(43c4a5d0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4456): Grow heap (frag case) to 15.466MB for 2475476-byte allocation
,I/dalvikvm-heap( 4456): Grow heap (frag case) to 17.556MB for 3713210-byte allocation
,W/jxcore-log( 4456): Initializing JXcore engine
,W/jxcore-log( 4456): JXcore engine is ready
,W/jxcore-log( 4456): Starting JXcore engine
,W/jxcore-log( 4456): Platform android
W/jxcore-log( 4456): 
,W/jxcore-log( 4456): Process ARCH arm
W/jxcore-log( 4456): 
,D/PMS     (  908): releaseWL(442b43a0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4456): JXcore Cordova bridge is ready!
I/jxcore-log( 4456): 
,W/jxcore-log( 4456): JXcore engine is started
,I/chromium( 4456): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/Choreographer( 4456): Skipped 161 frames!  The application may be doing too much work on its main thread.
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1184): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,I/jxcore-log( 4456): Toggling radios to true
I/jxcore-log( 4456): 
,D/BluetoothAdapter( 4456): enable(): BT is already enabled..!
,D/WifiManager( 4456): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
W/HtcDLNAServiceManager(  908): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  908): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  908): Settings:Agentvalue: 2
W/Settings:Agent(  908): >> traceCallingStack()
W/Settings:Agent(  908): Process.myPid(): 908
W/Settings:Agent(  908): Process.myTid(): 1379
W/Settings:Agent(  908): Process.myUid(): 1000
W/Settings:Agent(  908): 
W/Settings:Agent(  908): 
,W/System.err(  908): java.lang.Throwable: stack dump
W/System.err(  908): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  908): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  908): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  908): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  908): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  908): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  908): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  908): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  908): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  908): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  908): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  908): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  908): 
W/Settings:Agent(  908): << traceCallingStack(): 1(ms)
D/WifiManager( 4456): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  908): doBoolean: DISCONNECT
D/WifiManager( 4456): reconnect: Base Package Name=com.test.thalitest, uid=10389
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): TDLS: Tear down peers
,I/wpa_supplicant( 1184): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4456): Radios toggled
I/jxcore-log( 4456): 
,D/BluetoothManagerService(  908): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 4456): Got Device Bluetooth address: B4:CE:F6:AB:A4:6A
I/jxcore-log( 4456): 
D/WifiService(  908): New client listening to asynchronous messages
D/WifiService(  908): setWifiEnabled: true pid=4456, uid=10389
E/WifiService(  908): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  908): isSprintWifiRestricted(): false
I/WifiService(  908): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  908): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
I/jxcore-log( 4456): Perf Test app loaded loaded
I/jxcore-log( 4456): 
I/jxcore-log( 4456): check test folder
I/jxcore-log( 4456): 
I/jxcore-log( 4456): found test : ./testFindPeers.js
I/jxcore-log( 4456): 
,I/jxcore-log( 4456): found test : ./testSendData.js
I/jxcore-log( 4456): 
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1184): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1184): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1184): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  908): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  908): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  908): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  908): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  908): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1184): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1184): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/Tethering(  908): interfaceLinkStateChanged wlan0, false
E/wpa_supplicant( 1184): send_and_recv error -67 - cmd 12
D/Tethering(  908): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1184): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1184): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb7ad9bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1184):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1184): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1184): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1184): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1184): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1184): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1184): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1184): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1184): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1184): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1184): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1184): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_s,upplicant( 1184): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1184): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1184): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1184): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1184): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1184): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1184): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1184): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1184): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1184): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1184): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1184): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1184): nl80211: Event message available
D/wpa_supplicant( 1184): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1184): nl80211: Ignore disconnect event triggered during reassociation
D/WifiNative-wlan0(  908):    returned true
D/WifiPerfLock(  908): release()
,D/WifiStateMachine(  908): PerfLock released for exiting ConnectedState
D/WifiNative-wlan0(  908): doBoolean: DRIVER POWERMODE 0
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0",
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1184): Power_Mode_Type mode = 0
I/wpa_supplicant( 1184): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 61
D/Tethering(  908): [isWifi] getHotspotEnabled: false
D/ConnectivityService(  908): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
,D/PMS     (  908): acquireWL(437eae10): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 908 1000 null
D/Tethering(  908): interfaceLinkStateChanged wlan0, false
D/Tethering(  908): interfaceStatusChanged wlan0, false
D/Tethering(  908): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  908):    returned true
,D/WifiNative-wlan0(  908): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  908):    returned true
D/libc    (  908): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-, SUCCESS
D/DhcpStateMachine(  908): [RunningState] Stop DHCP
D/WifiP2pService(  908): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  908): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023975
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024252
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024312
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024316
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024323
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024326
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025783
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028638
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029573
D/WifiStateMachine(  908): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  908): doBoolean: RECONNECT
D/libc    (  908): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-, SUCCESS
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): Fast associate: Old scan results
I/wpa_supplicant( 1184): wpa_supplicant_scan enter
I/wpa_supplicant( 1184): State: DISCONNECTED -> SCANNING
D/WifiNative-wlan0(  908):    returned true
D/WifiDataStallTracker(  908): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  908): Enter handleNetworkDisconnect
D/WifiDataStallTracker(  908): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
I/wpa_supplicant( 1184): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1184): wpa_supplicant_trigger_scan +
D/WifiDataStallTracker(  908): stopDataStallAlarm: current tag=20249 mDataStallAlarmIntent=PendingIntent{42fe0988: PendingIntentRecord{42001e60 android broadcastIntent}}
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1184): Scan req (ret=0) - timeout 30 secs
,D/wpa_supplicant( 1184): nl80211: Event message available
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSID
D/wpa_supplicant( 1184): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiNative-wlan0(  908): doBoolean: DRIVER POWERMODE 0
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false),
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1184): Power_Mode_Type mode = 0
I/wpa_supplicant( 1184): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  908):    returned true
,D/WifiNative-wlan0(  908): doBoolean: DRIVER BTCOEXMODE 2
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023975
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024252
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiP2pService(  908): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024312
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024316
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024323
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024326
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025783
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  908):    returned true
D/WifiStateMachine(  908): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/UsbnetStateTracker(  908): isAvailable+-
D/UsbnetStateTracker(  908): reconnect
,D/UsbnetStateTracker(  908): isAvailable+-
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028638
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029573
D/WifiStateTracker(  908): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  908): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  908): Provision feature enable=false
D/ConnectivityService(  908): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WifiP2pService(  908): P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  908): default: reconnect()
D/MDST    (  908): default: setTeardownRequested(false)
D/MDST    (  908): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  908): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  908): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
,D/ConnectivityService(  908): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  908): Exit handleNetworkDisconnect
D/WISPrService( 4126): >>>>>WISPrService start isConnected = false<<<<<
D/WifiDataStallTracker(  908): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  908): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent DefaultState
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4126): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  908): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/WifiStateTracker(  908): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/ConnectivityService(  908): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  908): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/WifiService(  908): New client listening to asynchronous messages
D/ConnectivityService(  908): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
,D/WISPrService( 4126): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  908): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4126): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,V/NativeCrypto( 1361): Read error: ssl=0x66359fd0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1361): SSL shutdown failed: ssl=0x66359fd0: I/O error during system call, Broken pipe
W/ConnectivityService(  908): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  908): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  908): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)',
D/ConnectivityService(  908): handleConnectivityChange: resetting
D/ConnectivityService(  908): resetConnections(wlan0, 3)
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/PMS     (  908): acquireWL(4271e358): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
D/libc    (  364): [NET] entry_id:3   entry:0xb7f348e0  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb7f39190  removed 
D/libc    (  364): [NET] entry_id:5   entry:0xb7f39348  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb7f39428  removed 
D/libc    (  364): [NET] entry_id:6   entry:0xb7f39090  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb7f394f0  removed 
D/libc    (  364): [NET] entry_id:7   entry:0xb7f34fe8  removed 
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
D/ConnectivityService(  908): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  908): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  908): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  908): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  908): acquireWL(426e4350): PARTIAL_WAKE_LOCK  NetworkStats 0x1 908 1000 null
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023975
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024252
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024312
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024316
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024323
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by  (908/1000)
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024326
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025783
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028638
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  908): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029573
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1361/10029)
,D/WirelessDisplayService(  908): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  908): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:0
D/ConnectivityService(  908): reportInetCondition for net -1, percentage: 0 by  (1361/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1361/10029)
D/PMS     (  908): releaseWL(4271e358): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1361/10029)
D/WifiStateMachine(  908): startScan Pid: 908 Uid 1000
I//system/bin/ip(  364): RTNETLINK answers: No such process
I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,D/WifiNative-wlan0(  908): doBoolean: SCAN
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1184): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  908):    returned false
D/BatSI   (  908): WIFI scan started for: 650a0300 uid:1000
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
D/PMS     (  908): releaseWL(426e4350): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  908): mActiveDefaultNetwork: -1
D/ConnectivityService(  908): handleInetConditionChange: no active default network - ignore
,I/Choreographer( 4456): Skipped 84 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4456): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  908): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  908): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  908): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4508 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/GpsLocationProvider(  908): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  908): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  908): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  908): ignore wifi update if we are not in OPENING or CLOSING
D/Tethering(  908): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  908): bSetPropertyMultiRAB:false
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by  (908/1000)
D/PMS     (  908): acquireWL(4242d2a0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 908 1000 null
D/PMS     (  908): releaseWL(4242d2a0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.docs (4306/10100)
D/Tethering(  908): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
,I/Tethering(  908): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  908): ipv4Default null
I/Tethering(  908): No IPv4 upstream interface, giving up.
D/Tethering(  908): TetherMasterSM: InitialState processMessage what=3
I/ConnectivityHelper( 1273): [onReceive] WIFI(1): DISCONNECTED
,D/CaptivePortalTracker(  908): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  908): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  908): NoActiveNetworkState
,D/htcCheckinService(  908): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  908): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.backuptransport (1576/10029)
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.htc.launcher (1273/10076)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.docs (4306/10100)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2167/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2167/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2167/10029)
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023975
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024252
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024312
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024316
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024323
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024326
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025783
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028638
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029573
,I/MusicStore( 4508): Database version: 95
,W/ContextImpl( 4508): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4508): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4508): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4508): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4508): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4508, uid=10154, userID:0
,D/WifiDisplayAdapter(  908): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  908):     Client/Owner: Client
D/WifiDisplayAdapter(  908):     GroupId: 
D/WifiDisplayAdapter(  908):     Passphrase: 
D/WifiDisplayAdapter(  908):     SessionId: 0
D/WifiDisplayAdapter(  908):     IP Address: }
,D/MediaRouterService(  908): Client com.google.android.music (pid 4508): Registered
,I/MediaRouter( 4508): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  908): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  908):     Client/Owner: Client
D/WifiDisplayAdapter(  908):     GroupId: 
D/WifiDisplayAdapter(  908):     Passphrase: 
D/WifiDisplayAdapter(  908):     SessionId: 0
D/WifiDisplayAdapter(  908):     IP Address: }
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (2722/10021)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.music (4508/10154)
,I/ActivityManager(  908): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4528 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4508): getSelectedRoute
,I/NetworkMonitor( 4508): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.google.android.music (4508/10154)
,I/PMS     (  908): Going to sleep due to screen timeout...
,I/SensorManager(  908): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42218148
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  908): disable: get sensor name = CM36282 Light sensor
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 2
W/SensorService(  908): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42218148, eanble = 0, strlen(mName) = 59
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  908): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41c75840
W/SensorService(  908): Listener[1] = com.htc.smartdim.sensor_eye@41cff808
,W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  908): mThumbnailWidth=360, mThumbnailHeight=640
V/LightsService(  908): setLight #2: color=#0
W/BatSI   (  908): Couldn't get kernel wake lock stats
D/qdlights(  908): set_light_buttons_func: on=0 brightness=0
V/LightsService(  908): setLight #0: color=#0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4508, uid=10154, userID:0
,D/ACRA    ( 4528): ACRA is enabled for com.facebook.katana, intializing...
,W/PMS     (  908): mWirelessDisplayManager is null
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,D/WirelessDisplayService(  908): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  908): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,D/Process (  908): killProcessQuiet, pid=4241
D/PMS     (  908): acquireWL(43d5f1d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
,I/ActivityManager(  908): Killing 4241:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/ACRA    ( 4528): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4528): Looking for error files in /data/data/com.facebook.katana/app_minidumps
D/PMS     (  908): releaseWL(43d5f1d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  908): Recipient 4241
,D/WifiService(  908): Client connection lost with reason: 4
,W/SystemClassLoaderAdder( 4528): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4528): Preparing secondary program dexes.
V/DexLibLoader( 4528): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4528): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4528): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4528): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4528): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4528): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4528): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar,
V/DexLibLoader( 4528): Dex already copied
D/OdexVerifier( 4528): Odex verification is skipped.
,V/DexLibLoader( 4528): Creating class loader
,V/DexLibLoader( 4528): Finished creating class loader
V/DexLibLoader( 4528): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
,V/DexLibLoader( 4528): Dex already copied
D/OdexVerifier( 4528): Odex verification is skipped.
,V/DexLibLoader( 4528): Creating class loader
,V/DexLibLoader( 4528): Finished creating class loader
V/DexLibLoader( 4528): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4528): Dex already copied
D/OdexVerifier( 4528): Odex verification is skipped.
,V/DexLibLoader( 4528): Creating class loader
,V/DexLibLoader( 4528): Finished creating class loader
V/DexLibLoader( 4528): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
,V/DexLibLoader( 4528): Dex already copied
D/OdexVerifier( 4528): Odex verification is skipped.
,V/DexLibLoader( 4528): Creating class loader
,V/DexLibLoader( 4528): Finished creating class loader
,V/DexLibLoader( 4528): Verifying classes from secondary dexes.
,D/DexLibLoader( 4528): DexLibLoader.ensureDexLoaded took 23 ms
,D/SurfaceControl(  908): Excessive delay in blankDisplay() while turning screen off: 316ms
D/PMS     (  908): nativeSetInteractive:false
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  908): nativeSetInteractive:false done
D/PMS     (  908): nativeSetAutoSuspend:true
D/PMS     (  908): nativeSetAutoSuspend:true done
D/HABCtrl (  908): TPE algorithm. remove timeout.
D/PMS     (  908): OOBE c monitor 11
I/InputManager(  908): Cancel all due to getting PMS screen off broadcast
,V/KeyguardServiceDelegate(  908): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43918280)
I/IntentController( 1117): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/NfcService( 1255): ScreenObserver: OFF
,D/NfcService( 1255): applyRouting - 0
,V/KeyguardServiceDelegate(  908): **** SHOWN CALLED ****
D/PMN     (  908): wakingUp
,D/NfcService( 1255): applyRouting -2
D/WirelessDisplayService(  908): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  908): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  908): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
I/WindowManager(  908): No lock screen! windowToken=null
D/PMS     (  908): acquireWL(4389b890): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1255 1027 null
D/PMN     (  908): onScreenOn
,I/InputMethodManagerService(  908): screenObserver, isScreenOn=false
D/PMS     (  908): releaseWL(4389b890): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/InputMethodManagerService(  908): Disable input method client, pid=4456
,D/AlarmManager(  908): ACTION_SCREEN_ON
I/AlarmManager(  908): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  908): [AlarmQueuing] done recovering
I/AlarmManager(  908): [AlarmQueuing] recover EPS screen off blocked alarms
,D/WifiDataStallTracker(  908): onReceive: action=android.intent.action.SCREEN_ON
W/ResourceType( 4456): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4456): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41b6e110 VFEDH.C. .F...... 0,0-720,1134 #64}
,D/WifiNative-wlan0(  908): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/WifiNative-wlan0(  908): doBoolean: SET pno 0
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1184): SET_SCREEN_ON:On
I/wpa_supplicant( 1184): htc_wext_set_keepalive +
I/wpa_supplicant( 1184): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1184): getPrivFuncNum +	
I/wpa_supplicant( 1184): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1184): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1184): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1184): htc_wext_set_TX_TRACKING (0)+
,I/wpa_supplicant( 1184): htc_wext_set_TX_TRACKING - ret = 0
,D/WifiNative-wlan0(  908):    returned true
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): CTRL_IFACE SET 'pno'='0'
I/wpa_supplicant( 1184): wpa_supplicant_scan enter
,D/WifiNative-wlan0(  908):    returned true
I/AlarmManager(  908): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  908): acquireWL(4389a370): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
D/PMS     (  908): releaseWL(4389a370): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,D/MtpService( 2722): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2722): [MTP][onReceive]-
,D/NfcService( 1255): applyRouting - 0
,D/NfcService( 1255): applyRouting -2
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PMS     (  908): acquireWL(441010f8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1255 1027 null
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
D/PMS     (  908): releaseWL(441010f8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/NotificationService(  908): batLight: Full, plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c800
D/qdlights(  908): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/WirelessDisplayService(  908): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  908): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  908): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/WirelessDisplayService(  908): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/qdlights(  908): [LedInfo] has indicator attribute
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/NotificationService(  908): batLight: Full, plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c800
D/qdlights(  908): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/NetworkPolicy(  908): updateScreenOn: false
,I/ClockThread( 1117): stop update clock
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  908): acquireWL(43b5fb80): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(43b5fb80): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): acquireWL(43d68af8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(43d68af8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1762): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1762): onScreenOn: 1450287750748
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1762): onScreenOn: 1450287750749
,I/SensorManager(  908): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41c75840
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  908): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 2
W/SensorService(  908): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41c75840, eanble = 0, strlen(mName) = 91
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  908): Listener[0] = com.htc.smartdim.sensor_eye@41cff808
,W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  908): goingToSleep
D/WifiDataStallTracker(  908): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  908): stopDataStallAlarm: current tag=20250 mDataStallAlarmIntent=null
,D/WifiNative-wlan0(  908): doBoolean: SET_SCREEN_ON 0
D/WifiNative-wlan0(  908): doBoolean: SET pno 1
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1184): SET_SCREEN_ON:Off
I/wpa_supplicant( 1184): htc_wext_set_keepalive +
I/wpa_supplicant( 1184): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1184): getPrivFuncNum +	
I/wpa_supplicant( 1184): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1184): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1184): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 1184): get_ip_address source addr = 02000000
I/wpa_supplicant( 1184): htc_wext_set_keepalive gateway addr = 00000000
I/wpa_supplicant( 1184): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  908):    returned true
D/PMS     (  908): acquireWL(43437b68): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 908 1000 null
D/AlarmManager(  908): ACTION_SCREEN_OFF
I/AlarmManager(  908): [AlarmQueuing] screen off now: 
I/AlarmManager(  908): [AlarmQueuing] data connection: true
I/AlarmManager(  908): [AlarmQueuing] wifi connection: true
D/PMS     (  908): acquireWL(432030c8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 908 1000 null
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1184): CTRL_IFACE SET 'pno'='1'
,V/SRS_Proc(  371): ParamSet string: screen_state=off
D/PMS     (  908): releaseWL(43437b68): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/NetworkPolicy(  908): updateScreenOn: false
,D/ContactMessageStore( 1240): start background delete task...
D/ContactMessageStore( 1240): size: 0 , 0
,D/ContactMessageStore( 1240): Background delete complete
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1184): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1184): nl80211: Event message available
D/wpa_supplicant( 1184): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
,D/WifiNative-wlan0(  908):    returned true
D/wpa_supplicant( 1184): nl80211: Event message available
D/wpa_supplicant( 1184): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1184): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1184): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1184): nl80211: Survey data missing
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1184): Sorted scan results
I/wpa_supplicant( 1184): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-50
D/wpa_supplicant( 1184): BSS: last_scan_res_used=1/32 last_scan_full=0
D/wpa_supplicant( 1184): Add randomness: count=8 entropy=0
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1184): WPS: AP[0] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1184): wpa_supplicant_pick_network+
I/wpa_supplicant( 1184): Selecting BSS from priority group 1
I/wpa_supplicant( 1184): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1184): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1184): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1184):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1184):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-50
I/wpa_supplicant( 1184): Start print parameters
I/wpa_supplicant( 1184): wpa_s->wpa_state is 3
I/wpa_supplicant( 1184): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1184): isConcurrentMode() is 0
I/wpa_supplicant( 1184): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1184): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1184): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1184): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1184): wpa_s->reassociate is 1
I/wpa_supplicant( 1184): wpa_s->is_screen_on 0
I/wpa_supplicant( 1184): wpa_s->ifname wlan0
I/wpa_supplicant( 1184): End print parameters
I/wpa_supplicant( 1184): selected network = 1
D/wpa_supplicant( 1184): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb7adb4e8  current_ssid=0x0
D/wpa_supplicant( 1184): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1184): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1184): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1184): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1184): check if in concurrent case
I/wpa_supplicant( 1184): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1184): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1184): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1184): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1184): RSN: PMKSA cache search - network_ctx=0xb7adb4e8 try_opportunistic=0
D/wpa_supplicant( 1184): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1184): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1184): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1184): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1184): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1184): nl,80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1184): nl80211: Unsubscribe mgmt frames handle 0xb7ada718 (mode change)
D/wpa_supplicant( 1184): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7ada718
D/wpa_supplicant( 1184): nl80211: Register frame type=0xd0 nl_handle=0xb7ada718
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1184): nl80211: Register frame type=0xd0 nl_handle=0xb7ada718
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1184): nl80211: Register frame type=0xd0 nl_handle=0xb7ada718
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1184): nl80211: Register frame type=0xd0 nl_handle=0xb7ada718
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1184): nl80211: Register frame type=0xd0 nl_handle=0xb7ada718
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1184): nl80211: Register frame type=0xd0 nl_handle=0xb7ada718
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1184): nl80211: Register frame type=0xd0 nl_handle=0xb7ada718
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1184): nl80211: Register frame type=0xd0 nl_handle=0xb7ada718
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1184): nl80211: Register frame type=0xd0 nl_handle=0xb7ada718
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1184): nl80211: Register frame type=0xd0 nl_handle=0xb7ada718
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1184): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1184):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1184):   * freq=2412
D/wpa_supplicant( 1184):   * Auth Type 0
D/wpa_supplicant( 1184):   * WPA Versions 0x2
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1184): nl80211: Connect request send successfully
D/wpa_supplicant( 1184): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1184): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1184): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/WifiNative-wlan0(  908): doBoolean: DRIVER SETSUSPENDMODE 1
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  908):    returned true
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023975
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024252
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024312
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024316
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024323
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024326
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025783
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028638
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029573
D/PMS     (  908): releaseWL(432030c8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/WifiNative-wlan0(  908): doBoolean: SET pno 1
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): CTRL_IFACE SET 'pno'='1'
D/WifiNative-wlan0(  908):    returned true
D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  908): doString: LIST_DONGLES
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  908): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1184): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1184): reply (666) for get BSS: id=0
I/wpa_supplicant( 1184): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1184): freq=5220
I/wpa_supplicant( 1184): level=-48
I/wpa_supplicant( 1184): tsf=0000000022430320
I/wpa_supplicant( 1184): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1184): ssid=NG7005g
I/wpa_supplicant( 1184): ====
I/wpa_supplicant( 1184): id=1
I/wpa_supplicant( 1184): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1184): freq=2412
I/wpa_supplicant( 1184): level=-50
I/wpa_supplicant( 1184): tsf=0000000103972692
I/wpa_supplicant( 1184): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1184): ssid=NG700
I/wpa_supplicant( 1184): ====
I/wpa_supplicant( 1184): id=2
I/wpa_supplicant( 1184): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1184): freq=2427
I/wpa_supplicant( 1184): level=-78
I/wpa_supplicant( 1184): tsf=0000000022430335
I/wpa_supplicant( 1184): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1184): ssid=Gonzos
I/wpa_supplicant( 1184): ====
I/wpa_supplicant( 1184): id=3
I/wpa_supplicant( 1184): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1184): freq=2462
I/wpa_supplicant( 1184): level=-89
I/wpa_supplicant( 1184): tsf=0000000022430338
I/wpa_supplicant( 1184): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1184): ssid=UPC Wi-Free
I/wpa_supplicant( 1184): ====
I/wpa_supplicant( 1184): id=4
I/wpa_supplicant( 1184): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1184): freq=2462
I/wpa_supplicant( 1184): level=-89
I/wpa_supplicant( 1184): tsf=0000000022430342
I/wpa_supplicant( 1184): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1184): ssid=UPC5999698
I/wpa_supplicant( 1184): ####
D/WirelessDisplayService(  908): getDiscoveryDongleList
D/WifiStateMachine(  908): == begin of scan result ==
D/WifiStateMachine(  908): == (5) end of scan result ==
D/WifiManager( 1222): getScanResults enter 
D/WifiStateMachine(  908): == begin of scan result ==
D/WirelessDisplayService(  908): getDiscoveryDongleList
D/WifiStateMachine(  908): == (5) end of scan result ==
W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  908): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 22430320, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/WifiStateMachine(  908): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 2412, timestamp: 103972692, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  908): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2427, timestamp: 22430335, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  908): 3: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 22430338, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  908): 4: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -89, frequency: 2462, timestamp: 22430342, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  908): add 5 to mScanResults
D/BatSI   (  908): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  908): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,D/PMS     (  908): acquireWL(42fd3f20): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] getTotalRam: 1873 Mb
D/PMS     (  908): releaseWL(42fd3f20): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): acquireWL(436ddbc8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(436ddbc8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1762): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1762): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1762): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1762): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1762): onScreenOff
,D/wpa_supplicant( 1184): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1184): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1184): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1184): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1184): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1184): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1184): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1184): nl80211: Event message available
D/wpa_supplicant( 1184): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1184): nl80211: Connect event
D/wpa_supplicant( 1184): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1184): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1184): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1184): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1184): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1184): Add randomness: count=9 entropy=1
I/wpa_supplicant( 1184): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1184): TDLS: Remove peers on association
D/wpa_supplicant( 1184): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1184): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1184): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1184): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1184): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1184): EAPOL: enable timer tick
D/wpa_supplicant( 1184): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1184): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/wpa_supplicant( 1184): Get randomness: len=32 entropy=2
D/WifiMonitor(  908): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  908): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  908): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  908): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  908): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  908): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  908): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  908): Enter handleAssociatedWithEvent
D/WifiStateMachine(  908): Associated
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  908): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  908): Exit handleAssociatedWithEvent
D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHA,KE
D/WifiStateMachine(  908): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  908): updateConnectedAP...
I/wpa_supplicant( 1184): htc_wext_set_keepalive +
I/wpa_supplicant( 1184): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1184): getPrivFuncNum +	
I/wpa_supplicant( 1184): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1184): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1184): htc_wext_set_keepalive - ret = 0
D/WifiApDatabaseHandler(  908): updateConnectedAP...
D/WifiStateMachine(  908): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/Tethering(  908): interfaceLinkStateChanged wlan0, false
,D/Tethering(  908): interfaceStatusChanged wlan0, false
D/Tethering(  908): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  908): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  908): This record is existed, only update it...
,D/WifiStateMachine(  908): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  908): updateConnectedAP...
D/Tethering(  908): interfaceLinkStateChanged wlan0, true
,D/Tethering(  908): interfaceStatusChanged wlan0, true
,D/Tethering(  908): [isWifi] getHotspotEnabled: false
I/wpa_supplicant( 1184): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb7ada9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 1184):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1184): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1184): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f21b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 1184):    broadcast key
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1184): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1184): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1184): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1184): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 1184): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1184): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1184): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1184): set send_ind_to_ndc = 0
I/wpa_supplicant( 1184): htc_wext_set_TX_TRACKING (1)+
,I/wpa_supplicant( 1184): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1184): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1184): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1184): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1184): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1184): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1184): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1184): EAPOL: SUPP_BE entering state IDLE
,D/wpa_supplicant( 1184): EAPOL authentication completed successfully
I/wpa_supplicant( 1184): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1184): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1184): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1184): nl80211: if_removed already cleared - ignore event
D/Tethering(  908): interfaceLinkStateChanged wlan0, true
D/Tethering(  908): interfaceStatusChanged wlan0, true
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/Tethering(  908): [isWifi] getHotspotEnabled: false
,D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
,D/WifiMonitor(  908): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  908): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  908): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  908): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,W/dalvikvm( 4528): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4528): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4528): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/WifiStateMachine(  908): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,W/dalvikvm( 4528): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/WifiApDatabaseHandler(  908): updateConnectedAP...
,W/dalvikvm( 4528): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4528): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4528): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/WifiStateMachine(  908): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  908): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  908): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  908): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  908): This record is existed, only update it...
,D/WifiStateMachine(  908): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  908): updateConnectedAP...
,D/WifiDataStallTracker(  908): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  908): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  908): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  908): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  908): Provision feature enable=false
,D/ConnectivityService(  908): mActiveDefaultNetwork: -1
D/WISPrService( 4126): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 4126): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  908): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  908): updateConnectedAP...
,D/WifiNative-wlan0(  908): doBoolean: SET pno 0
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1184): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1184): nl80211: Event message available
D/wpa_supplicant( 1184): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/WifiNative-wlan0(  908):    returned true
,D/DhcpStateMachine(  908): [StoppedState] Start DHCP
,D/WifiStateMachine(  908): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/WifiNative-wlan0(  908): doBoolean: DRIVER BTCOEXMODE 1
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiStateMachine(  908): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  908): acquireWL(430445b8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 908 1000 null
,D/WifiStateMachine(  908): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiNative-wlan0(  908):    returned true
D/WifiNative-wlan0(  908): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  908):    returned true
D/WifiNative-wlan0(  908): doBoolean: DRIVER POWERMODE 1
D/wpa_supplicant( 1184): nl80211: Event message available
D/wpa_supplicant( 1184): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1184): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1184): Power_Mode_Type mode = 1
I/wpa_supplicant( 1184): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  908):    returned true
D/WifiNative-wlan0(  908): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  908):    returned null
E/WifiStateMachine(  908): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  908): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  908):    returned null
D/WifiP2pService(  908): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42584e00 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  908): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42584e00 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
,W/dalvikvm( 4528): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4528): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4528): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4528): Verify
,D/WifiService(  908): New client listening to asynchronous messages
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4528/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4528): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4528): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4528): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  908): killProcessQuiet, pid=3856
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  908): Killing 3856:com.htc.mediamanager/u0a34 (adj 15): empty #17
,D/AutoSetting( 1321): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  908): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4566 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.sense.hsp (1321/10055)
,D/AutoSetting( 1321): Util - no network available!
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.sense.hsp (1321/10055)
,D/AutoSetting( 1321): service - onCreate()
,D/AutoSetting( 1321): service - AddressCache: using context: com.htc.Weather
,D/AutoSetting( 1321): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/LocationManagerService(  908): request 424ec340 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/LocationManagerService(  908): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1321): service - mHandler: cancel location update
,D/AutoSetting( 1321): service -           changes count: 0
,W/fb4a(:<default>):UserScope( 4528): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4528): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4528): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4566): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4566): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4566): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4566): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  908): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4582 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.setupwizard (4566/10079)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.setupwizard (4566/10079)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.setupwizard (4566/10079)
,I/ActivityManager(  908): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4596 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
I/ActivityManager(  908): Recipient 3856
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  908): killProcessQuiet, pid=4060
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Killing 4060:com.google.android.talk/u0a111 (adj 15): empty #17
,D/wpa_supplicant( 1184): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1184): EAPOL: disable timer tick
,I/dalvikvm-heap( 4528): Grow heap (frag case) to 9.953MB for 84664-byte allocation
E/dalvikvm( 4528): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4528): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4596): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4596): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/GAV2    ( 4596): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,I/dalvikvm-heap( 4528): Grow heap (frag case) to 9.968MB for 28144-byte allocation
,W/ContextImpl( 4596): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
E/dalvikvm( 4528): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 4528): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4528): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 4528): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 4596): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
E/dalvikvm( 4528): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4528): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/dalvikvm( 4528): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4528): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4528): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4528): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4528): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4528): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4528): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4528): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4528): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4528): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/dalvikvm-heap( 4528): Grow heap (frag case) to 10.036MB for 39954-byte allocation
,I/ActivityManager(  908): Recipient 4060
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/dalvikvm-heap( 4528): Grow heap (frag case) to 10.112MB for 79892-byte allocation
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.magazines (4596/10151)
V/WebViewChromiumFactoryProvider( 4596): Binding Chromium to main looper Looper (main, tid 1) {41b66040}
I/LibraryLoader( 4596): Expected native library version number "",actual native library version number ""
I/chromium( 4596): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4596): Initializing chromium process, renderers=0
,D/PMS     (  908): acquireWL(43d3f740): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,D/PMS     (  908): acquireWL(43d75cc0): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,E/AudioManagerAndroid( 4596): BLUETOOTH permission is missing!
D/PMS     (  908): releaseWL(43d3f740): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4596): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4596): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4596): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4596): Local Branch: 
I/Adreno-EGL( 4596): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4596): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4596):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4596): Starting up...
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.magazines (4596/10151)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.magazines (4596/10151)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (4104/10160)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (4104/10160)
,D/Process (  908): killProcessQuiet, pid=4276
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/dalvikvm-heap( 4528): Grow heap (frag case) to 10.276MB for 75760-byte allocation
I/ActivityManager(  908): Killing 4276:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2167/10029)
,I/iu.Environment( 2167): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2167): num queued entries: 0
,I/iu.UploadsManager( 2167): num updated entries: 0
,I/iu.SyncManager( 2167): NEXT; no task
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2167/10029)
I/ActivityManager(  908): Recipient 4276
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2167/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4528/10027)
W/BroadcastQueue(  908): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43c5e2d0 u0 ReceiverList{43c5e1b0 4528 com.facebook.katana/10027/u0 remote:43c4d830}}
W/BroadcastQueue(  908): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43c5e2d0 u0 ReceiverList{43c5e1b0 4528 com.facebook.katana/10027/u0 remote:43c4d830}}
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1361/10029)
W/BroadcastQueue(  908): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43d49850 u0 ReceiverList{43d497f0 4528 com.facebook.katana/10027/u0 remote:43170018}}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1361/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023975
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024252
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024312
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024316
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024323
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024326
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025783
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028638
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029573
,I/ActivityManager(  908): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4635 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4528/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4528/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4528/10027)
,W/ContextImpl( 4635): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4635): isEpsOn(), nState = 0
D/PMS     (  908): acquireWL(4315b930): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4635 1000 null
,D/PMS     (  908): acquireWL(437fee38): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(437fee38): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/SmartSyncUtils( 4635): getMobilePolicyEnabled, result = true
D/PMS     (  908): releaseWL(4315b930): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4528): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4528): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/libc    (  908): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent DefaultState
,W/ContextImpl( 4528): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  908): killProcessQuiet, pid=4306
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 4306:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,D/AutoSetting( 1321): receiver - intent: android.intent.action.USER_PRESENT
,I/ActivityManager(  908): Recipient 4306
,D/AutoSetting( 1321): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/TetherSettings( 4126): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4126): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4126): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4126): Cust_ConnectToPC   : spcsc>false
D/        ( 4126): Cust_ConnectToPC   : IPT>true
,D/        ( 4126): Cust_ConnectToPC   : Singel_USB>false
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/Settings( 4126): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4126): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4126): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4126): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 4126): onReceive:android.intent.action.USER_PRESENT
,W/ContextImpl( 4126): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 4126): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4126): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 4126):  defaultType:0
,D/libc    (  908): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/libc    (  908): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/libc    (  908): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/libc    (  908): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  908): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  908):    returned true
D/WifiNative-wlan0(  908): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1184): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1184): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,W/ContextImpl( 4635): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4635): isEpsOn(), nState = 0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 61
D/SmartSyncUtils( 4635): getMobilePolicyEnabled, result = true
,D/WifiNative-wlan0(  908):    returned true
D/WifiNative-wlan0(  908): doBoolean: DRIVER BTCOEXMODE 2
,D/SmartSyncUtils( 4635): isEpsOn(), nState = 0
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  908):    returned true
,D/WifiStateMachine(  908): handlePostDhcpSetup release wake lock during DHCP
D/WifiP2pService(  908): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  908): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiService(  908): New client listening to asynchronous messages
,D/PMS     (  908): releaseWL(430445b8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
I/SensorManager(  908): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41cff808
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  908): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 1
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41cff808, eanble = 0, strlen(mName) = 36
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  908): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 0
W/SensorService(  908): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41cff808, eanble = 0, strlen(mName) = 36
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=33 [3][1][0]
I/SensorManager(  908): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41cff808
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
D/WifiStateMachine(  908): gateway: /192.168.1.1
,D/WifiNative-wlan0(  908): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0,
I/wpa_supplicant( 1184): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1184): htc_wext_set_keepalive +
I/wpa_supplicant( 1184): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1184): getPrivFuncNum +	
I/wpa_supplicant( 1184): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1184): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1184): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1184): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1184): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  908):    returned true
D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  908): VerifyingLinkState enter
D/WifiStateMachine(  908): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
,D/WifiStateMachine(  908): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  908): VerifyingLinkState: enableIpv6
E/ActivityThread(  908): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@423addd8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  908): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@423addd8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  908): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  908): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  908): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  908): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  908): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  908): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  908): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  908): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  908): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  908): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  908): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  908): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  908): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  908): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  908): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  908): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  908): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  908): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  908): 	at dalvik.system.NativeStart.main(Native Method)
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED -1 -> 3
,D/WifiStateMachine(  908): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -50, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  908): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  908): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiWatchdogStateMachine(  908): WAN detection
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateTracker(  908): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  908): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  908): Provision feature enable=false
V/NetworkPolicy(  908): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/ConnectivityService(  908): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  908): Policy requires mobile/UNKNOWN teardown quickly
,D/WISPrService( 4126): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
D/MDST    (  908): default: teardown()
D/MDST    (  908): default: setTeardownRequested(true)
D/MDST    (  908): default: setEnableApn apnType =default , enable=false
D/MDST    (  908): default: setTeardownRequested(true)
D/ConnectivityService(  908): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  908): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
D/libc    (  908): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  908): syncGetConfiguredNetworks
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED connected
E/ConnectivityService(  908): Unexpected mtu value: android.net.wifi.WifiStateTracker@424e8928
D/ConnectivityService(  908): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/ConnectivityService(  908): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  908): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  908): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  908): handleConnectivityChange: resetting
D/Nat464Xlat(  908): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  908): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  908): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  908): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  908): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  908): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  908): acquireWL(4393eac0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 908 1000 null
D/WirelessDisplayService(  908): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,D/WirelessDisplayService(  908):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.setupwizard (4566/10079)
,I/QuickSettingWifi( 1117): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/PMS     (  908): acquireWL(438be2b0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2167 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,I/CheckinService( 2167): Checkin interval check for package: unspecified last checkin: 1450287702637 min interval config: 0 actual interval: 50106,
D/PMS     (  908): acquireWL(437fb470): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2167 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(4393eac0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  908): releaseWL(438be2b0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2167): Checking schedule, now: 1450287752750 next: 1450287732609
,I/CheckinService( 2167): active receiver: enabled
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2167, uid=10029, userID:0
,I/CheckinService( 2167): Preparing to send checkin request
,I/EventLogService( 2167): Accumulating logs since 1450287698322
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2167/10029)
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  908): mActiveDefaultNetwork: WIFI
,I/CheckinRequestBuilder( 2167): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  908): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2167): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  908): getNetworkInfo networkType=9 called by com.google.android.gms (2167/10029)
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2167/10029)
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  908): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4693 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,W/dalvikvm( 4693): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4693): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4693): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4693): install
,I/MultiDex( 4693): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4693): loading existing secondary dex files
,I/MultiDex( 4693): load found 3 secondary dex files
,I/MultiDex( 4693): install done
,W/dalvikvm( 4693): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4693): VFY: unable to resolve instance field 36
,W/dalvikvm( 4693): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4693): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ProviderInstaller( 4693): Installed default security provider GmsCore_OpenSSL
,W/dalvikvm( 4693): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4693): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/WearableService( 1222): callingUid 10029, callindPid: 1222
,W/dalvikvm( 4693): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4693): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4693): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
W/dalvikvm( 4693): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4693): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/LocationInitializer( 2167): Restart initialization of location
,E/MDM     ( 1222): [118] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1361): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1361): Proximity feature is not enabled.
,V/GLSActivity( 1361): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1222): No location to return for getLastLocation()
,W/FusedLocationProvider( 1222): location=null
D/PMS     (  908): acquireWL(42689c38): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(42689c38): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023975
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024252
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024312
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024316
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024323
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024326
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025783
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028638
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029573
,I/WVCdm   (  371): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  371): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/NativeLibraryUtils( 4693): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  371): PrepareKeyRequest: nonce=1463102627
,I/WVCdm   (  371): CdmEngine::CloseSession
,D/PMS     (  908): releaseWL(437eae10): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  908): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  908): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  908): [AlarmQueuing] connectivity wifi: true
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/GpsLocationProvider(  908): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  908): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  908): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  908): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by  (908/1000)
D/PMS     (  908): acquireWL(426c5e60): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 908 1000 null
D/PMS     (  908): releaseWL(426c5e60): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,V/Tethering(  908): bSetPropertyMultiRAB:false
,D/CaptivePortalTracker(  908): NoActiveNetworkState,
D/Tethering(  908): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,I/Tethering(  908): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
,I/Tethering(  908): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.backuptransport (1576/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.htc.launcher (1273/10076)
I/Tethering(  908): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
I/Tethering(  908): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  908): Found interface wlan0
D/Tethering(  908): TetherMasterSM: InitialState processMessage what=3
,D/AccTypeManager( 1341): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ConnectivityHelper( 1273): [onReceive] WIFI(1): CONNECTED
,I/NetworkMonitor( 4508): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2167/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.setupwizard (4566/10079)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.musicenhancer (3915/10053)
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.google.android.music (4508/10154)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4528/10027)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
,D/CaptivePortalTracker(  908): DelayedCaptiveCheckState
D/htcCheckinService(  908): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  908): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023975
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024252
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024312
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024316
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024323
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024326
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025783
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028638
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029573
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.backuptransport (1576/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2167/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4528/10027)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/PMS     (  908): acquireWL(4263f388): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2167/10029)
W/AccTypeManager( 1341): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1341): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!,
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4528/10027)
D/PMS     (  908): releaseWL(4263f388): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  908): getActiveNetworkInfo called by  (2722/10021)
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/ExternalAccountType( 1341): Unsupported attribute readOnly
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,D/AutoSetting( 1321): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4566): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4566): onReceive CONNECTIVITY_CHANGE networkType=1
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.sense.hsp (1321/10055)
D/AutoSetting( 1321): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/AutoSetting( 1321): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 1321): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1321): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.sense.hsp (1321/10055)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.magazines (4596/10151)
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (4104/10160)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (4104/10160)
,W/Settings( 4693): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/PMS     (  908): acquireWL(4300d5b0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2167 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(4300d5b0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I/CheckinService( 2167): Checkin interval check for package: unspecified last checkin: 1450287702637 min interval config: 0 actual interval: 51211
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
I/dalvikvm-heap( 4104): Grow heap (frag case) to 13.518MB for 1821008-byte allocation
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2167, uid=10029, userID:0
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,I/iu.Environment( 2167): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2167/10029)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2167/10029)
I/iu.UploadsManager( 2167): num queued entries: 0
I/iu.UploadsManager( 2167): num updated entries: 0
,I/iu.SyncManager( 2167): NEXT; no task
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2167/10029)
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/libc    ( 1361): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1361): [NET] getaddrinfo-,err=8
D/libc    ( 1361): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1361): [NET] getaddrinfo-, 1
,D/libc    ( 1361): [NET] getaddrinfo_proxy+
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1361/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1361/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1361/10029)
D/PMS     (  908): acquireWL(42711830): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1361/10029)
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =faf2 +++++
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET] NOT IN CACHE
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,I/jxcore-log( 4456): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 4456): 
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 227
D/libc    (  364): [NET]res_nsend:resplen=79
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1361): [NET] getaddrinfo_proxy-, success
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (4693/10029)
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/libc    ( 1361): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1361): [NET] getaddrinfo-,err=8
,D/libc    ( 1361): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1361): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1361/10029)
,D/WVCdm   (  371): PrepareKeyRequest: nonce=44337377
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1361/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1361/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1361/10029)
,I/WVCdm   (  371): CdmEngine::CloseSession
,D/PMS     (  908): acquireWL(4279d538): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1361/10029)
,D/PMS     (  908): releaseWL(42711830): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  908): reportInetCondition for net 1, percentage: 100 by  (1361/10029)
,D/ConnectivityService(  908): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  908): handleInetConditionChange: starting a change hold
,D/PMS     (  908): releaseWL(4279d538): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(434e4748): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  908): reportInetCondition for net 1, percentage: 100 by  (1361/10029)
D/ConnectivityService(  908): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  908): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  908): reportInetCondition for net 1, percentage: 100 by  (1361/10029)
,D/ConnectivityService(  908): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  908): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1361/10029)
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023975
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024252
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024312
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024316
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024323
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024326
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025783
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028638
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029573
,D/PMS     (  908): releaseWL(434e4748): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,I/Adreno-EGL( 4693): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4693): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4693): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4693): Local Branch: 
I/Adreno-EGL( 4693): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4693): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4693):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4693): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4693): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4693): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4693): Local Branch: 
I/Adreno-EGL( 4693): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4693): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4693):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4693): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4693): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4693): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4693): Local Branch: 
I/Adreno-EGL( 4693): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4693): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4693):                  aa63bbd948f41d15fc72f585e
,I/CheckinRequestBuilder( 2167): Classify the device as Phone.
,D/libc    ( 2167): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2167): [NET] getaddrinfo-,err=8
D/libc    ( 2167): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2167): [NET] getaddrinfo-, 1
,D/libc    ( 2167): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =5564 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 243
D/libc    (  364): [NET]res_nsend:resplen=84
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2167): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2167): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2167): [NET] getaddrinfo-,err=8
,D/libc    ( 2167): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2167): [NET] getaddrinfo-,err=8
,D/libc    ( 2167): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2167): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2167): Sending checkin request (12083 bytes)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4528/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4528/10027)
,D/ConnectivityService(  908): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  908): sendGeneralBroadcast, restrictEnable=false
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=12 [25][3][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
W/fb4a(:<default>):UserScope( 4528): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/fb4a(:<default>):UserScope( 4528): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4528/10027)
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=100 [1][1][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4528/10027)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4528): Called registerBroadcastReceiver twice.
,I/CheckinRequestBuilder( 2167): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  908): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2167): Failed to find provider info for com.google.android.wearable.settings
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4528/10027)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4528/10027)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4528/10027)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4528/10027)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4528/10027)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4528/10027)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4528/10027)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4528/10027)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4528/10027)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4528/10027)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4528/10027)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4528/10027)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4528/10027)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4528/10027)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4528/10027)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4528/10027)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4528/10027)
D/PMS     (  908): releaseWL(43d75cc0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4528/10027)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4528/10027)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4528/10027)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4528/10027)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (4528/10027)
,D/ConnectivityService(  908): getNetworkInfo networkType=9 called by com.google.android.gms (2167/10029)
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [1][0][0]
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2167/10029)
,I/CheckinRequestBuilder( 2167): Classify the device as Phone.
,I/CheckinTask( 2167): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2167): Checking schedule, now: 1450287755204 next: 1450810692190
,I/CheckinService( 2167): active receiver: disabled
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2167, uid=10029, userID:0
,D/PMS     (  908): acquireWL(43203080): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4508 10154 null
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023975
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024252
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024312
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024316
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024323
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024326
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025783
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028638
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029573
,I/CheckinService( 2167): Checking schedule, now: 1450287755232 next: 1450810692190
,I/CheckinService( 2167): active receiver: disabled
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2167, uid=10029, userID:0,
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023975
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024252
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024312
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024316
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024323
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024326
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025783
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028638
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029573
D/CheckinService( 2167): Recording last checkin time for package unspecified as 1450287755239
W/ContextImpl( 4508): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/PMS     (  908): releaseWL(437fb470): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4508, uid=10154, userID:0
,W/ContextImpl( 4508): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
I/MusicLeanback( 4508): Conditions not met for autocaching.
,I/MusicLeanback( 4508): Stop autocaching.
,D/PMS     (  908): releaseWL(43203080): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2167/10029)
,D/GCM     ( 1361): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/WifiStateMachine(  908): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  908): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  908): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  908): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-,err=8
D/libc    (  908): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  908): [NET] getaddrinfo-, 1
,D/libc    (  908): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =8dca +++++,
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  908): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  908): Find DNS Address www.htc.com/23.59.123.86
,I/GAV2    ( 4596): Thread[GAThread,5,main]: No campaign data found.
,D/AutoSetting( 1522): service - handleMessage() stop self
,D/AutoSetting( 1522): service - onDestroy() END
,D/AutoSetting( 1522): service - handleMessage() quit looper
,D/Process (  908): killProcessQuiet, pid=4324
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 4324:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4324
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  908): killProcessQuiet, pid=4349
,I/ActivityManager(  908): Killing 4349:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  908): Recipient 4349
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1321): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1321): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1321): service - requestNLP() NetworkLocationProvider not enabled
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1341): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  908): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4748 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,W/SystemReader( 1255): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "sms"
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1273): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "smsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
W/AccTypeManager( 1341): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1341): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "mms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/Launcher( 1273): Deferring update until onResume
,D/Launcher( 1273): waitUntilResume // bindAppsUpdated
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "mmsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "sms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "smsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "mms"
,I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
E/ExternalAccountType( 1341): Unsupported attribute readOnly
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/PackageManager(  908):   Scheme: "mmsto"
,D/PhoneApp( 1240): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,W/dalvikvm( 4748): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4748): VFY: unable to resolve instance field 36
,W/dalvikvm( 4748): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,I/Babel   ( 4748): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4748): MmsConfig.loadMmsSettings
,V/JNIHelp ( 4748): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  908): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4771 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4748, uid=10111, userID:0
,W/Settings( 4748): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4748, uid=10111, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4748, uid=10111, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4748, uid=10111, userID:0
,D/MessageFrequencyProvider( 4771): onCreate
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4748, uid=10111, userID:0
,V/GetPrviateResource( 4771): GetPrviateResource
,V/GetPrviateResource( 4771): GetPrviateResource
D/MmsCustomizationProvider( 4771): query uri: content://htc-mms-customization/mms-ua/ua_string
,I/ProviderInstaller( 4748): Installed default security provider GmsCore_OpenSSL
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4748, uid=10111, userID:0
D/PMS     (  908): acquireWL(44108f58): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4748 10111 null
,D/MmsCustomizationProvider( 4771): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/[PluginManager]RegisterService( 1321): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1321): handle notify Blinkfeed plugin client changed
I/ActivityManager(  908): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/Babel   ( 4748): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4748): MmsConfig.loadFromDatabase
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/IcingCorporaProvider( 2858): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
E/Babel   ( 4748): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4748): MmsConfig.loadFromResources
,E/Babel   ( 4748): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4748): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,D/PMS     (  908): acquireWL(437fd480): PARTIAL_WAKE_LOCK  Icing 0x1 2167 10029 WorkSource{10029 com.google.android.gms}
,D/Process (  908): killProcessQuiet, pid=3915
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  908): Killing 3915:com.htc.musicenhancer/u0a53 (adj 15): empty #17
D/PMS     (  908): releaseWL(437fd480): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/MessageCustFlag( 4771): sense_version=6.0
,D/BTAccessoryUtil( 4771): createReceiver
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 3915
,D/BTAccessoryUtil( 4771): registerReceiver return intent = null
D/MessageCustFlag( 4771): sku_id=99
,W/SystemReader( 4771): Cannot find message_ambs_application_id, use default value instead
D/PMS     (  908): acquireWL(438be098): PARTIAL_WAKE_LOCK  Icing 0x1 2167 10029 WorkSource{10029 com.google.android.gms}
,D/Messaging( 4771): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4771): networkCode: 
,D/MessageCustFlag( 4771): sku_id=99
D/MmsConfig( 4771): SIE smsPri: null
,D/MmsConfig( 4771): networkCode: 
,D/HtcTelephonyCapability( 4771): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4771): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 4771): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4771): Cannot find qct_8960_interface, use default value instead
D/PMS     (  908): releaseWL(44108f58): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/Process (  908): killProcessQuiet, pid=4293
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 4293:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4293
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): releaseWL(438be098): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  908): Resuming delayed broadcast
,D/PMS     (  908): acquireWL(42d34b38): PARTIAL_WAKE_LOCK  Icing 0x1 2167 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  908): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  908): acquireWL(43d64f28): PARTIAL_WAKE_LOCK  AsyncService 0x1 4104 10160 null
,I/dalvikvm-heap( 4104): Grow heap (frag case) to 15.218MB for 1821008-byte allocation
D/PMS     (  908): releaseWL(43d64f28): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  908): releaseWL(42d34b38): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  908): Resuming delayed broadcast
,D/PMS     (  908): acquireWL(42704cd8): PARTIAL_WAKE_LOCK  Icing 0x1 2167 10029 WorkSource{10029 com.google.android.gms}
,I/dalvikvm-heap( 4104): Grow heap (frag case) to 16.949MB for 1821008-byte allocation
I/ActivityManager(  908): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,D/PMS     (  908): releaseWL(42704cd8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  908): Resuming delayed broadcast
D/CaptivePortalTracker(  908): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  908): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  908): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
I/ActivityManager(  908): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
D/PMS     (  908): acquireWL(42fea8c0): PARTIAL_WAKE_LOCK  Icing 0x1 2167 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(42fea8c0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  908): Resuming delayed broadcast
,D/PMS     (  908): acquireWL(439d5f98): PARTIAL_WAKE_LOCK  Icing 0x1 2167 10029 WorkSource{10029 com.google.android.gms}
,D/PackageBroadcastService( 2167): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2167): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  908): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/Icing   ( 2167): updateResources: need to parse f{com.google.android.gms}
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41bf6d50 +
,I/Prism.WidgetManager( 1273): onLoadItems() +
,I/IcingCorporaProvider( 2858): UpdateCorporaTask done [took 1197 ms] updated apps [took 1197 ms] 
I/ActivityManager(  908): Resuming delayed broadcast
,W/PackageManager(  908): Unable to load service info ResolveInfo{431152b8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  908): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  908): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  908): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  908): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  908): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  908): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  908): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  908): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  908): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  908): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  908): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  908): 	at dalvik.system.NativeStart.main(Native Method)
,E/Prism.WidgetManager( 1273): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1273): onLoadItems() -
,I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41bf6d50 -
,D/PhoneApp( 1240): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1240): -- N1 =0
,D/PhoneApp( 1240): -- N2 =0
,D/PhoneApp( 1240): -- N3 =0
,I/GCoreNlp( 1222): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/RemoteDisplayProvider(  908): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  908): start
,D/LocationProviderProxy(  908): applying state to connected service
,D/PMS     (  908): acquireWL(4239bfa0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(4239bfa0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  908): applying state to connected service
,D/PMS     (  908): acquireWL(420d83c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(420d83c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(41e7b068): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(41e7b068): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 2167): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,D/Messaging( 4771): mNeedToUpdateDate2 start
,D/MmsConfig( 4771): packageName: com.htc.vvm.att does not exist
D/ReportIndicatorCache( 4771): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4771): 
D/MmsAsyncWorkHandler( 4771): HM tk = 20001
,D/ReportIndicatorCache( 4771): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4771): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41b733a0
,I/Messaging( 4771): mccmnc> 
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
,D/MmsSmsV2Provider( 1240):  phoneType = -1
,D/MmsSmsV2Provider( 1240): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/DraftCache( 4771): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4771): [DraftCache/1] refresh
D/MmsConfig( 4771): networkCode: ,
,D/Messaging( 4771): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/MmsSmsV2Provider( 1240):  phoneType = -1
,D/MmsSmsV2Provider( 1240): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
D/PhoneStorageUtil( 4771): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4771): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4771): createReceiver
,D/MessageCustFlag( 4771): sense_version=6.0
,D/Jerry   ( 4771): start to preload cursor >>>>>>>
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
,D/MmsSmsV2Provider( 1240):  phoneType = -1
D/TelephUtils( 1240): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
V/MmsProvider( 1240): Update uri=content://mms, match=0
,V/MmsProvider( 1240): selection=st=129 AND m_type!=134
,D/MmsSmsV2Provider( 1240): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,I/Icing   ( 2167): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/Messaging( 4771): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4771): TransactionService is going to be woken up.
,D/Messaging( 4771): mNeedToUpdateDate2: false
,V/TransactionService( 4771): 1-Creating TransactionService
V/TransactionService( 4771): onStartCommand: 1
,D/MmsSystemEventReceiver( 4771): unRegisterForConnectionStateChanges
V/TransactionService( 4771): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4771): Loading previous transactions.
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
,D/AccFlag ( 1240): sku_id=99
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/DraftCache( 4771): [DraftCache/472] rebuildCache
,D/AccFlag ( 1240): device_type: 1
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
,D/MmsSmsV2Provider( 1240):  phoneType = -1
D/TransactionService( 4771): Force set service start id to 1
V/TransactionService( 4771): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4771): unRegisterForConnectionStateChanges
D/PMS     (  908): releaseWL(439d5f98): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/TransactionService( 4771): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4771): Destroying TransactionService
,V/TransactionService( 4771): 4-Handling incoming message: { when=-3ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/MmsSmsV2Provider( 1240):  phoneType = -1
,D/MmsSmsV2Provider( 1240): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 4771): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/Jerry   ( 1240): URI_DRAFT
D/Messaging( 4771): ViewCache CreatePreload
,D/Messaging( 4771): ViewCache CreatePreloadOnlyMultipleOpsList
,D/Cust_MMSMS( 4771): _has_set_default_values_2=true
,D/DraftCache( 4771): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 4771): [DraftCache/472] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4771): 
D/MmsAsyncWorkHandler( 4771): HM tk = 20002
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1240): sku_id=99
,D/MsgPreferenceUtils( 4771): def_index: 0
,D/MsgPreferenceUtils( 4771): globalIndex = 1
D/MsgPreferenceUtils( 4771): phone state: true
D/MsgPreferenceUtils( 4771): sd state: false
,D/MsgPreferenceUtils( 4771): vIndex = 0
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
,D/AccFlag ( 1240): sku_id=99
,I/ActivityManager(  908): Waited long enough for: ServiceRecord{4272f1c0 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/GAV4    ( 4748): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  908): acquireWL(423bde68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  908): sending alarm PendingIntent{4397af18: PendingIntentRecord{426f51b0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=122329, Int=0
,D/PMS     (  908): acquireWL(42fcf088): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(423bde68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1361/10029)
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [15][0][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/PMS     (  908): acquireWL(425df378): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(425df378): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(42fcf088): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(426c9c98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023975
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024252
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024312
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024316
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024323
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024326
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025783
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028638
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029573
,D/PMS     (  908): releaseWL(426c9c98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(43c916c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1361/10029)
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023975
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024252
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024312
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024316
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024323
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024326
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025783
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028638
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029573
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/PMS     (  908): acquireWL(42508240): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(44260d58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1222): Vacuum at: now=1450287769336 tag=VacuumService
D/PMS     (  908): releaseWL(43c916c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(42508240): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(426d7b00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1361/10029)
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  908): releaseWL(44260d58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023975
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024252
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024312
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024316
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024323
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024326
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025783
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028638
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029573
,D/PMS     (  908): releaseWL(426d7b00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(4377cca8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023975
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024252
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024312
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024316
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024323
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024326
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025783
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025798
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028638
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029573
,D/PMS     (  908): releaseWL(4377cca8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(425c7ca8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023975
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024252
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024312
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024316
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024323
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024326
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025783
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025798
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028638
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029573
,D/PMS     (  908): releaseWL(425c7ca8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(42fd0148): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1361/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023975
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024252
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024312
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024316
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024323
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024326
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025783
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025798
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028638
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029573
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/PMS     (  908): releaseWL(42fd0148): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): acquireWL(43c6b5c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1361/10029)
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023975
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024252
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024312
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024316
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024323
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024326
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025783
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028638
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029573
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/PMS     (  908): acquireWL(4378fb40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(4378fb40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(43176558): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(43c6b5c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(42fd5f10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023975
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024252
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024312
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024316
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024323
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024326
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025783
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028638
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029573
,D/PMS     (  908): releaseWL(42fd5f10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1222): Scheduling Phenotype for one-off execution 8994 seconds from now (1450287769903)
,D/GetConfigurationSnapshotOperation( 1222): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1222): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1222): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1222): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1222): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1222): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1222): Using platform SSLCertificateSocketFactory
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/LocationManagerService(  908): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1222): [NET] getaddrinfo-,err=8
D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1222): [NET] getaddrinfo-, 1
D/libc    ( 1222): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =39fe +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 193
D/libc    (  364): [NET]res_nsend:resplen=87
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1222): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1222): [NET] getaddrinfo-,err=8
D/libc    ( 1222): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1222): [NET] getaddrinfo-,err=8
,D/PMS     (  908): releaseWL(43176558): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(4215da38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023975
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024252
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024312
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024316
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024323
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024326
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025783
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028638
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029573
,D/PMS     (  908): releaseWL(4215da38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(426a57e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=25 [8][2][0]
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1361/10029)
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023975
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024252
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024312
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024316
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024323
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024326
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025783
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028638
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029573
,D/PMS     (  908): releaseWL(426a57e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(43c3fb40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
I/BatteryService(  908): n_update end
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  908): BroadcastReceiver::onReceive-
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): releaseWL(43c3fb40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(43c371c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43c371c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  908): updateBatteryInfo
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
,I/HtcPowerSaver(  908): >> updateStatus
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(42fec9d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f3f240: PendingIntentRecord{41ee52e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=133192, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42fec9d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  908): acquireWL(442b6de0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  908): sending alarm PendingIntent{42686718: PendingIntentRecord{4265b3b8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=134049, Int=0
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1361/10029)
,D/PMS     (  908): releaseWL(442b6de0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1321): service - mHandler: update timezone
,D/AutoSetting( 1321): service - handleMessage() stop self
,D/AutoSetting( 1321): service - handleMessage() quit looper
D/AutoSetting( 1321): service - onDestroy() END
,D/AutoSetting( 1522): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  908): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1522): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1522): service - onCreate()
D/AutoSetting( 1522): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1522): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
W/ActivityManager(  908): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/DotMatrix( 1566): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
D/AutoSetting( 1522): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1522): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1522): service - mHandler: update timezone
,D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  908): batLight: Full, plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c800
D/qdlights(  908): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1522): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1522): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1522): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1522): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1566): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1117): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41cb6de0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.htclocationservice 2 7 2 11
,D/PMS     (  908): acquireWL(43205808): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41d027d8: PendingIntentRecord{425319f8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141712, Int=0
,D/GpsLocationProvider(  908): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  908): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  908): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/PMS     (  908): acquireWL(43bf2198): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 908 1000 null
,D/PMS     (  908): releaseWL(43205808): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/libc    (  908): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-,err=8
D/libc    (  908): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  908): [NET] getaddrinfo-, 1
,D/libc    (  908): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =b767 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  364): [NET]res_nsend:resplen=243
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  908): [NET] getaddrinfo_proxy-, success
I/global  (  908): call createSocket() return a new socket.
D/libc    (  908): [NET] getaddrinfo+,hn 14(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  908): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  908): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  908): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  908):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  908): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/Process (  908): killProcessQuiet, pid=4382
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 4382:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4382
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): releaseWL(43bf2198): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,D/ContactMessageStore( 1240): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1240): MSG_NOTIFY_CS_TO_SYNC <<
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/ActivityManager(  908): Waited long enough for: ServiceRecord{435287b0 u0 com.htc.htclocationservice/.AutoSettingService}
,D/AutoSetting( 1522): service - handleMessage() stop self
,D/AutoSetting( 1522): service - onDestroy() END
,D/AutoSetting( 1522): service - handleMessage() quit looper
,D/Process (  908): killProcessQuiet, pid=4396
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 4396:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4396
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0,
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  908): acquireWL(42bc3578): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10027}
,V/AlarmManager(  908): sending alarm PendingIntent{42439720: PendingIntentRecord{43849640 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=171934, Int=0
,D/PMS     (  908): releaseWL(42bc3578): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1240): switchBindHtcMsgCursor: null
,D/PMS     (  908): acquireWL(439039f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(439039f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  908): updateBatteryInfo
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(43d84f00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43d84f00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(4397aaa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f3f240: PendingIntentRecord{41ee52e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=193191, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4397aaa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  908): acquireWL(42703df8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42703df8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(434e5f08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(434e5f08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(43c08d30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f3f240: PendingIntentRecord{41ee52e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=253192, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43c08d30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(43c7f990): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
I/BatteryService(  908): n_update end
D/PMS     (  908): releaseWL(43c7f990): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(43bd0890): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f3f240: PendingIntentRecord{41ee52e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=313192, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43bd0890): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/jxcore-log( 4456): Connected to the server!
I/jxcore-log( 4456): 
,I/chromium( 4456): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  908): acquireWL(42591520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): releaseWL(42591520): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(44228d60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  908): releaseWL(44228d60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(430d6d28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f3f240: PendingIntentRecord{41ee52e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=373192, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(430d6d28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 4456): --- start :testFindPeers.js---
I/jxcore-log( 4456): 
,I/jxcore-log( 4456): testFindPeers created [object Object]
I/jxcore-log( 4456): 
,I/jxcore-log( 4456): serverPort is 8876
I/jxcore-log( 4456): 
W/dalvikvm( 4456): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4456): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4456): threadid=1: thread exiting with uncaught exception (group=0x41733e30)
,E/ActivityManager(  908): App crashed! Process: com.test.thalitest
E/AndroidRuntime( 4456): FATAL EXCEPTION: main
E/AndroidRuntime( 4456): Process: com.test.thalitest, PID: 4456
E/AndroidRuntime( 4456): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4456): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:134)
E/AndroidRuntime( 4456): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:133)
E/AndroidRuntime( 4456): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:183)
E/AndroidRuntime( 4456): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:95)
E/AndroidRuntime( 4456): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:92)
E/AndroidRuntime( 4456): 	at io.jxcore.node.JXcoreExtension$5.Receiver(JXcoreExtension.java:155)
E/AndroidRuntime( 4456): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4456): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4456): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4456): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4456): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4456): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4456): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4456): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4456): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4456): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4456): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4456): 	at dalvik.system.NativeStart.main(Native Method)
W/ActivityManager(  908):   Force finishing activity com.test.thalitest/.MainActivity
,D/Process (  908): killProcessQuiet, pid=4028
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
I/ActivityManager(  908): Killing 4028:com.google.android.gm/u0a107 (adj 15): empty #17
,D/Process ( 4456): killProcess, pid=4456
,D/Process ( 4456): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,W/InputDispatcher(  908): channel '423677d0 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  908): channel '423677d0 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  908): Attempted to unregister already unregistered input channel '423677d0 com.test.thalitest.MainActivity (s)'
I/WindowManager(  908): WINDOW DIED Window{423677d0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager(  908): Recipient 4456
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Process com.test.thalitest (pid 4456) has died.
D/WifiService(  908): Client connection lost with reason: 4
,I/ActivityManager(  908): Recipient 4028
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Binder  ( 1208): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1208): java.lang.NullPointerException
W/Binder  ( 1208): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1208): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1208): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1208): 	at dalvik.system.NativeStart.run(Native Method)
W/InputMethodManagerService(  908): Got RemoteException sending setActive(false) notification to pid 4456 uid 10389
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(438614a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): releaseWL(438614a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(43907da0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43907da0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,D/PMS     (  908): acquireWL(428b2e68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f3f240: PendingIntentRecord{41ee52e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=433192, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(428b2e68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  908): acquireWL(430d3d10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(430d3d10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(4409c638): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f3f240: PendingIntentRecord{41ee52e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=493192, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4409c638): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(427a6e30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(427a6e30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(4248edd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f3f240: PendingIntentRecord{41ee52e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=553192, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4248edd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(44132bf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(44132bf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  908): acquireWL(43915070): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f3f240: PendingIntentRecord{41ee52e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=613192, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43915070): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ContactMessageStore( 1240): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1240): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1240): sku_id=99
D/ContactMessageStore( 1240): start background delete task...
,D/ContactMessageStore( 1240): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1240): size: 0 , 0
,D/ContactMessageStore( 1240): Background delete complete
,D/PMS     (  908): acquireWL(43c618e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43c618e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(43803b40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f3f240: PendingIntentRecord{41ee52e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=673192, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43803b40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(439cc7d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(439cc7d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(438cf560): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f3f240: PendingIntentRecord{41ee52e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=733192, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(438cf560): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42cf5310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42cf5310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(427302b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f3f240: PendingIntentRecord{41ee52e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=793192, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(427302b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(439c03c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(439c03c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(42698ca8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f3f240: PendingIntentRecord{41ee52e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=853192, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42698ca8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(439dbbf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(439dbbf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  908): updateBatteryInfo
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(4395a4c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4395a4c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(43c8ffe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f3f240: PendingIntentRecord{41ee52e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=913191, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43c8ffe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43860d38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43860d38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(43c2aa18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f3f240: PendingIntentRecord{41ee52e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=973191, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1273): Grow heap (frag case) to 12.657MB for 50416-byte allocation
,D/PMS     (  908): releaseWL(43c2aa18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(4383de60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4383de60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/ConnectivityService(  908): Sampling interval elapsed, updating statistics ..
,D/PMS     (  908): acquireWL(438fffa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41dfefc0: PendingIntentRecord{424f30e0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=782524, Int=0
,D/ConnectivityService(  908): Done.
,D/ConnectivityService(  908): Setting timer for 720seconds
,I/ActivityManager(  908): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4879 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  908): sending alarm PendingIntent{42489008: PendingIntentRecord{42488fd0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1450287857839, Int=10800000
,V/AlarmManager(  908): sending alarm PendingIntent{431237f8: PendingIntentRecord{4277e920 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450288021979, Int=1800000
,V/AlarmManager(  908): sending alarm PendingIntent{42371d98: PendingIntentRecord{42607b38 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450288578314, Int=900000
,V/AlarmManager(  908): sending alarm PendingIntent{438585e8: PendingIntentRecord{430c9390 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450288652654, Int=0
,D/PMS     (  908): acquireWL(437fe018): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2167 10029 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4635): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  908): acquireWL(4317f7c0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2167 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(437fe018): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,D/PowerUsageService( 4635): call getInstance()
,D/SmartSyncUtils( 4635): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4635): MY_DEBUG = false
D/PMS     (  908): acquireWL(43212188): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4635 1000 null
,D/PMS     (  908): releaseWL(438fffa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/SmartSyncScreenOnOffTimeReceiver( 4635): [updateNmRange] bManual = false
D/SmartSyncScreenOnOffTimeReceiver( 4635): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 4635): AlarmOnTime = -1
I/EventLogService( 2167): Aggregate from 1450287752781 (log), 1450286221939 (data)
D/SmartSyncScreenOnOffTimeReceiver( 4635): SettingOnTime = 1450332000000, randomSettingOnTime = 1450331000000
D/SmartSyncScreenOnOffTimeReceiver( 4635): SettingOffTime = 1450317600000, randomSettingOffTime = 1450320941000
D/SmartSyncScreenOnOffTimeReceiver( 4635): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4635): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4635): bNightModeTurnOffOnce = false
W/BatSI   (  908): Couldn't get kernel wake lock stats
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.aurora (4879/10049)
,D/PMS     (  908): releaseWL(43212188): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023975
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024252
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024312
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024316
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024323
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024326
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025783
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028638
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029573
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023975
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024252
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024312
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024316
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024323
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024326
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025783
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028638
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029573
,D/PMS     (  908): releaseWL(4317f7c0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,D/Process (  908): killProcessQuiet, pid=4427
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 4427:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4427
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): acquireWL(4242fc50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  908): sending alarm PendingIntent{43cb3cd0: PendingIntentRecord{42659ba0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1007398, Int=0
,D/PMS     (  908): acquireWL(423bfbf0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(423bfbf0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(4242fc50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(41fed558): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1361 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1361/10029)
,D/ConnectivityService(  908): reportInetCondition for net 1, percentage: 100 by  (1361/10029)
D/ConnectivityService(  908): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  908): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1361/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023975
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024252
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024312
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024316
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024323
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360024326
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025783
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025798
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028638
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360029573
,D/PMS     (  908): releaseWL(41fed558): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  908): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=3 [192][6][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/PMS     (  908): acquireWL(42656d08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PMS     (  908): releaseWL(42656d08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(4262db38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f3f240: PendingIntentRecord{41ee52e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1033192, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4262db38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(4248ec38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4248ec38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(42667368): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42667368): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(43216060): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f3f240: PendingIntentRecord{41ee52e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1093192, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43216060): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43948ff8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43948ff8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(43c60f48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f3f240: PendingIntentRecord{41ee52e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1153192, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1273): Grow heap (frag case) to 12.657MB for 50416-byte allocation
,D/PMS     (  908): releaseWL(43c60f48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(4246bba8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4246bba8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  908): acquireWL(420e21d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f3f240: PendingIntentRecord{41ee52e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1213192, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(420e21d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43748758): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43748758): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(43569ca0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f3f240: PendingIntentRecord{41ee52e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1273191, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43569ca0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(426f2c78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(426f2c78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(42673948): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  908): sending alarm PendingIntent{41f3f240: PendingIntentRecord{41ee52e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1333192, Int=0
,I/dalvikvm-heap( 1273): Grow heap (frag case) to 12.704MB for 50416-byte allocation
D/PMS     (  908): releaseWL(42673948): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42517e30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  908): releaseWL(42517e30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
,I/HtcPowerSaver(  908): >> updateStatus
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(43bd0248): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f3f240: PendingIntentRecord{41ee52e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1393192, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43bd0248): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(437e9dc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(437e9dc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(430cf380): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(430cf380): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(42537540): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f3f240: PendingIntentRecord{41ee52e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1453192, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42537540): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42659388): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  908): BroadcastReceiver::onReceive-
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): releaseWL(42659388): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  908): runPSCheck
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(41e61000): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(41e61000): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(42673320): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f3f240: PendingIntentRecord{41ee52e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1513192, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42673320): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(440e2b60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
,D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): releaseWL(440e2b60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(425dd220): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f3f240: PendingIntentRecord{41ee52e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1573192, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(425dd220): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(437e6b48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): releaseWL(437e6b48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  908): updateBatteryInfo
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,W/ContextImpl( 4635): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,D/TetherSettings( 4126): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4126): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4126): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4126): Cust_ConnectToPC   : spcsc>false
D/        ( 4126): Cust_ConnectToPC   : IPT>true
D/        ( 4126): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 4126): project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4126): Index of the first 1 = 3
W/ContextImpl( 4126): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 4126): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 4126): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4126): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4126): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 4126): [ACC]android_networking:tethering_guard_support=false
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
W/ContextImpl( 4126): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  908): acquireWL(4242de48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(4242de48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(43407f78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f3f240: PendingIntentRecord{41ee52e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1633192, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(43407f78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42716960): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
,D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PMS     (  908): releaseWL(42716960): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(42709b38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42709b38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(42677390): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f3f240: PendingIntentRecord{41ee52e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1693192, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42677390): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(43c3dcb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(43c3dcb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(4340ad90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  908): releaseWL(4340ad90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  908): acquireWL(42d68130): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f3f240: PendingIntentRecord{41ee52e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1753192, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42d68130): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(441eee38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(441eee38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,D/HtcPowerSaver(  908): updateBatteryInfo
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,D/PMS     (  908): acquireWL(427b1e48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(427b1e48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  908): acquireWL(426aa570): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f3f240: PendingIntentRecord{41ee52e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1813192, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(426aa570): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(44228ce0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  908): updateBatteryInfo
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  908): releaseWL(44228ce0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,I/ProcessStatsService(  908): Prepared write state in 45ms
,I/ProcessStatsService(  908): Pruning old procstats: /data/system/procstats/state-2015-12-16-04-01-20.bin
,D/PMS     (  908): acquireWL(442519b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(442519b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  908): acquireWL(4354cf10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41f3f240: PendingIntentRecord{41ee52e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1873192, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4354cf10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(431f78c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(431f78c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1566): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1566): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4919): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4919): ====startRecUseTime====
D/htc.customization.log.level( 4919):  is 
W/CustomizationLogLevel( 4919): Level value is invalid, use default level 2
D/CustomizationManager( 4919):  Read ACC file spent 0.068 (s)
D/CIDMapFileReader( 4919): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4919): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4919): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4919): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4919): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4919): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4919): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4919): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4919): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4919): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4919): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4919): Parsing tag category name = system
I/CustomizationCIDLoader( 4919): Parsing tag category name = application
I/CustomizationCIDLoader( 4919): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4919): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4919): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4919): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4919): Parsing tag category name = Settings
D/CustomizationManager( 4919):  Read CID file spent 0.114 (s)
D/CustomizationManager( 4919):  All configurations done spent 0.114 (s)
W/HtcNativeFlag( 4919): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4919): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4919): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4919): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  908): deletePackageAsUser: pkg=com.test.thalitest, pid=4919, uid=2000 user=0
I/ActivityManager(  908): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  908): killProcessQuiet, pid=4508
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  908): killProcessQuiet, pid=4596
I/ActivityManager(  908): Killing 4508:com.google.android.music:main/u0a154 (adj 15): empty for 1800s
I/ActivityManager(  908): Killing 4596:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1802s
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  908): killProcessQuiet, pid=4582
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  908): killProcessQuiet, pid=4566
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  908): Killing 4582:com.android.chrome/u0a96 (adj 15): empty for 1802s
I/ActivityManager(  908): Killing 4566:com.google.android.setupwizard/u0a79 (adj 15): empty for 1802s
W/asset   (  908): Copying FileAsset 0x62bc6ab8 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  908): Recipient 4566
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 4582
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/PackageSettings(  908): Skipping PackageSetting{42254ab0 com.example.hello/10397} due to missing metadata
E/JavaBinder(  908): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  908): !!! FAILED BINDER TRANSACTION !!!
I/ActivityManager(  908): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 4596
D/MediaRouterService(  908): Client com.google.android.music (pid 4508): Died!
I/ActivityManager(  908): Recipient 4508
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1566): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1566): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1566): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
W/BroadcastQueue(  908): Failure sending broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
W/BroadcastQueue(  908): android.os.DeadObjectException
W/BroadcastQueue(  908): 	at android.os.BinderProxy.transact(Native Method)
W/BroadcastQueue(  908): 	at android.app.ApplicationThreadProxy.scheduleRegisteredReceiver(ApplicationThreadNative.java:1211)
W/BroadcastQueue(  908): 	at com.android.server.am.BroadcastQueue.performReceiveLocked(BroadcastQueue.java:454)
W/BroadcastQueue(  908): 	at com.android.server.am.BroadcastQueue.deliverToRegisteredReceiverLocked(BroadcastQueue.java:564)
W/BroadcastQueue(  908): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:636)
W/BroadcastQueue(  908): 	at com.android.server.am.BroadcastQueue$1.handleMessage(BroadcastQueue.java:147)
W/BroadcastQueue(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/BroadcastQueue(  908): 	at android.os.Looper.loop(Looper.java:157)
W/BroadcastQueue(  908): 	at com.android.server.am.ActivityManagerService$AThread.run(ActivityManagerService.java:2098)
D/AccTypeManager( 1341): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/VoicemailCleanupService( 1299): Cleaning up data for package: com.test.thalitest
D/PMS     (  908): acquireWL(43c149e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
W/SQLiteConnectionPool( 2167): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
W/GeofencerStateMachine( 1222): Ignoring removeGeofence because network location is disabled.
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "sms"
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/InputMethodManagerService(  908): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/PMS     (  908): releaseWL(43c149e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "smsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/Launcher( 1273): Deferring update until onResume
D/Launcher( 1273): waitUntilResume // bindAppsRemoved
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/[PluginManager]RegisterService( 1321): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1321): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1273): action: android.intent.action.PACKAGE_REMOVED
W/SystemReader( 1255): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mmsto"
W/AccTypeManager( 1341): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1341): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "sms"
I/IcingCorporaProvider( 2858): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
E/ExternalAccountType( 1341): Unsupported attribute readOnly
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "smsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/ActivityManager(  908): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4933 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mmsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
D/PhoneApp( 1240): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  908): acquireWL(43ab7620): PARTIAL_WAKE_LOCK  Icing 0x1 2167 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2858): UpdateCorporaTask done [took 304 ms] updated apps [took 304 ms] 
W/PackageManager(  908): Unable to load service info ResolveInfo{4249d428 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  908): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  908): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  908): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  908): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  908): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  908): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  908): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  908): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  908): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  908): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  908): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  908): 	at dalvik.system.NativeStart.main(Native Method)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.docs (4933/10100)
D/RemoteDisplayProvider(  908): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  908): start
I/ActivityManager(  908): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4955 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
E/SQLiteLog( 4933): (3850) statement aborts at 59: [DELETE FROM CachedSearch111 WHERE timestamp<?] disk I/O error
E/SQLiteDBG( 4933): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.apps.docs/databases/DocList.db, handle = 0x5cab06f8
E/AbstractDatabaseInstance( 4933): Failed to delete from CachedSearch111
E/AbstractDatabaseInstance( 4933): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AbstractDatabaseInstance( 4933): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AbstractDatabaseInstance( 4933): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AbstractDatabaseInstance( 4933): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AbstractDatabaseInstance( 4933): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AbstractDatabaseInstance( 4933): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AbstractDatabaseInstance( 4933): 	at ahl.b(AbstractDatabaseInstance.java:310)
E/AbstractDatabaseInstance( 4933): 	at aid.a(DatabaseModelLoader.java:340)
E/AbstractDatabaseInstance( 4933): 	at aiN.a(ObsoleteDataCleanerImpl.java:100)
E/AbstractDatabaseInstance( 4933): 	at fv.run(DocsApplication.java:288)
W/dalvikvm( 4933): threadid=11: thread exiting with uncaught exception (group=0x41733e30)
E/AndroidRuntime( 4933): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 4933): Process: com.google.android.apps.docs, PID: 4933
E/AndroidRuntime( 4933): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4933): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4933): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 4933): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4933): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4933): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 4933): 	at ahl.b(AbstractDatabaseInstance.java:310)
E/AndroidRuntime( 4933): 	at aid.a(DatabaseModelLoader.java:340)
E/AndroidRuntime( 4933): 	at aiN.a(ObsoleteDataCleanerImpl.java:100)
E/AndroidRuntime( 4933): 	at fv.run(DocsApplication.java:288)
E/ActivityManager(  908): App crashed! Process: com.google.android.apps.docs
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.docs (4933/10100)
D/Process ( 4933): killProcess, pid=4933
D/Process ( 4933): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
W/AtomicFile(  908): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
E/DropBoxManagerService(  908): Can't write: system_app_crash
E/DropBoxManagerService(  908): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  908): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  908): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  908): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  908): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  908): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  908): 	... 5 more
W/AppWidgetServiceImpl(  908): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
I/ActivityManager(  908): Recipient 4933
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Process com.google.android.apps.docs (pid 4933) has died.
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.apps.docs/.sync.syncadapter.ContentSyncService in 1000ms
W/ContextImpl( 4955): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  908): Delay finish: com.android.keychain/.KeyChainBroadcastReceiver
E/SQLiteDatabase( 4955): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4955): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4955): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4955): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4955): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4955): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4955): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4955): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4955): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4955): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4955): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4955): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4955): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4955): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4955): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4955): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4955): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4955): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4955): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4955): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4955): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4955): threadid=10: thread exiting with uncaught exception (group=0x41733e30)
E/AndroidRuntime( 4955): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4955): Process: com.android.keychain, PID: 4955
E/AndroidRuntime( 4955): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4955): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4955): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4955): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4955): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4955): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4955): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4955): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4955): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4955): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4955): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4955): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4955): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4955): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4955): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4955): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4955): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4955): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4955): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4955): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  908): App crashed! Process: com.android.keychain
D/ErrorReport(  908): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4955): killProcess, pid=4955
D/Process ( 4955): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  908): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  908): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1450289556900.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  908): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  908): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  908): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  908): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  908): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  908): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  908): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  908): 	... 4 more
I/ActivityManager(  908): Recipient 4955
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Process com.android.keychain (pid 4955) has died.
W/ActivityManager(  908): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10940ms
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4971 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/AppTag  ( 4971): getInstance(Context context)
D/AppTag  ( 4971): getInstance(Context context)
D/AppTag  ( 4971): onCreate()
I/ActivityManager(  908): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
D/PMS     (  908): acquireWL(441b7d00): PARTIAL_WAKE_LOCK  AsyncService 0x1 4104 10160 null
D/PMS     (  908): releaseWL(441b7d00): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  908): Resuming delayed broadcast
W/dalvikvm( 4142): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 2167): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2167): Clearing selected account for com.test.thalitest
I/ActivityManager(  908): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
I/LocationSettingsChecker( 2167): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 2167): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2167): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5cb2b680
E/DriveAsyncService( 2167): disk I/O error (code 3850)
E/DriveAsyncService( 2167): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2167): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2167): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2167): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2167): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2167): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2167): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2167): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2167): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2167): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2167): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2167): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2167): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2167): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2167): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2167): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteDatabase( 2167): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 2167): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2167): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2167): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2167): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2167): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2167): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2167): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2167): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2167): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2167): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2167): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2167): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2167): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2167): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2167): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2167): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 2167): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2167): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2167): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2167): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 2167): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 2167): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 2167): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 2167): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/PhenotypeInitializer( 2167): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/PhenotypeInitializer( 2167): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 2167): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 2167): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 2167): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/PhenotypeInitializer( 2167): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/PhenotypeInitializer( 2167): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/PhenotypeInitializer( 2167): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/PhenotypeInitializer( 2167): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2167): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2167): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 2167): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 2167): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 2167): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 2167): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 2167): 	at android.os.Looper.loop(Looper.java:157)
E/PhenotypeInitializer( 2167): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 2167): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 2167): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2167): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2167): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2167): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2167): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2167): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2167): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2167): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2167): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2167): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2167): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2167): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2167): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2167): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2167): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 2167): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 2167): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 2167): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 2167): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2167): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2167): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2167): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 2167): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 2167): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 2167): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 2167): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 2167): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 2167): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 2167): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 2167): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 2167): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 2167): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 2167): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 2167): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 2167): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 2167): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 2167): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 2167): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 2167): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 2167): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 2167): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 2167): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 2167): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 2167): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 2167): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 2167): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 2167): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 2167): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 2167): (8) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/gH_CompatibleDatabase( 2167): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/dalvikvm( 2167): threadid=48: thread exiting with uncaught exception (group=0x41733e30)
E/ActivityManager(  908): App crashed! Process: com.google.android.gms
E/AndroidRuntime( 2167): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 2167): Process: com.google.android.gms, PID: 2167
E/AndroidRuntime( 2167): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 2167): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2167): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 2167): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 2167): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2167): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 2167): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 2167): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 2167): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2167): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2167): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2167): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BaseAppContext( 2167): Using Auth Proxy for data requests.
D/Process ( 2167): killProcess, pid=2167
D/Process ( 2167): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  908): Can't write: system_app_crash
E/DropBoxManagerService(  908): java.io.FileNotFoundException: /data/system/dropbox/drop145.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  908): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  908): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  908): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  908): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  908): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  908): 	... 5 more
I/ActivityManager(  908): Recipient 2167
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Process com.google.android.gms (pid 2167) has died.
D/WifiService(  908): Client connection lost with reason: 4
D/PMS     (  908): handleWLDeath(43ab7620): PARTIAL_WAKE_LOCK  Icing 0x1
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 10492ms
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 20491ms
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 30491ms
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 30491ms
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 30491ms
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 30490ms
I/ActivityManager(  908): Resuming delayed broadcast
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41bf6d50 +
I/Prism.WidgetManager( 1273): onLoadItems() +

```
