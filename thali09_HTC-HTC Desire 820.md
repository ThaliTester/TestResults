#### Test 56204092c98eeae_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main,
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  909):    returned true
E/cutils-trace( 4483): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4483): ====startRecUseTime====
D/htc.customization.log.level( 4483):  is 
W/CustomizationLogLevel( 4483): Level value is invalid, use default level 2
D/CustomizationManager( 4483):  Read ACC file spent 0.057 (s)
D/CIDMapFileReader( 4483): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4483): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4483): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4483): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4483): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4483): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4483): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4483): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4483): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4483): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4483): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4483): Parsing tag category name = system
I/CustomizationCIDLoader( 4483): Parsing tag category name = application
I/CustomizationCIDLoader( 4483): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4483): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4483): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4483): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4483): Parsing tag category name = Settings
D/CustomizationManager( 4483):  Read CID file spent 0.097 (s)
D/CustomizationManager( 4483):  All configurations done spent 0.097 (s)
W/HtcNativeFlag( 4483): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4483): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4483): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4483): Fail to get flag for type 'language', use default value: -1
--------- beginning of /dev/log/system
W/CpuWake (  909): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  909): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  909): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  909): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  909): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  909): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  909): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4483
D/PMS     (  909): acquireHCC(437e8778): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 909 1000 null
D/PMS     (  909): acquireHCC(437e7590): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 909 1000 null
W/asset   (  909): Copying FileAsset 0x6648e910 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  909): @test_code: getHtcIntentFlag: 0 obj: 1123599672
I/FeedHostManager( 1275): [onPause]
I/FeedProviderManager( 1275): onPause
I/SocialFeedProvider( 1275): +onPause
I/SocialFeedProvider( 1275): -onPause
I/FeedHostManager( 1275): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41b6af30
D/PMS     (  909): acquireWL(437d94d8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 909 1000 null
I/ActivityManager(  909): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4494 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1275): [trimMemory] 20
W/asset   ( 4494): Copying FileAsset 0x5c7c3428 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4494): Binding Chromium to main looper Looper (main, tid 1) {41a797e8}
I/LibraryLoader( 4494): Expected native library version number "",actual native library version number ""
I/chromium( 4494): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4494): Initializing chromium process, renderers=0
D/PMS     (  909): acquireWL(425ef8f0): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  909): acquireWL(42596188): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  909): releaseWL(425ef8f0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
W/System.err(  909): java.lang.Throwable: stack dump
D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  909): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@424f9708:true
W/System.err(  909): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  909): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  909): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  909): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  909): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4494): 1101594352: getState(). Returning 12
I/Adreno-EGL( 4494): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4494): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4494): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4494): Local Branch: 
I/Adreno-EGL( 4494): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4494): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4494):                  aa63bbd948f41d15fc72f585e
W/chromium( 4494): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4494): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4494): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4494): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4494): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4494): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4494): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4494): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4494): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4494): CordovaWebView is running on device made by: HTC
,W/AwContents( 4494): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  909): Disable input method client, pid=1275
W/ResourceType( 4494): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4494): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41ac15a0, mServedView=org.apache.cordova.engine.SystemWebView{41a87208 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/InputMethodManagerService(  909): Enable input method client, pid=4494
W/XT9_C   ( 1215): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1215): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1215): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1215): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 4494): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  909): Displayed com.test.thalitest/.MainActivity: +308ms
D/PMS     (  909): releaseWL(437d94d8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/JsMessageQueue( 4494): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 4494): JniHelper::setJavaVM(0x41552048), pthread_self() = 1662921656
D/JX-Cordova( 4494): jxcore cordova android initializing
,I/dalvikvm-heap( 4494): Grow heap (frag case) to 11.944MB for 42938-byte allocation
,I/dalvikvm-heap( 4494): Grow heap (frag case) to 12.021MB for 96598-byte allocation
,I/dalvikvm-heap( 4494): Grow heap (frag case) to 12.101MB for 144892-byte allocation
,I/dalvikvm-heap( 4494): Grow heap (frag case) to 12.216MB for 217334-byte allocation
,I/dalvikvm-heap( 4494): Grow heap (frag case) to 12.393MB for 325996-byte allocation
,I/dalvikvm-heap( 4494): Grow heap (frag case) to 12.666MB for 488990-byte allocation
,I/dalvikvm-heap( 4494): Grow heap (frag case) to 13.641MB for 1100216-byte allocation
,I/dalvikvm-heap( 4494): Grow heap (frag case) to 14.599MB for 1650320-byte allocation
,I/dalvikvm-heap( 4494): Grow heap (frag case) to 15.853MB for 2475476-byte allocation
,I/dalvikvm-heap( 4494): Grow heap (frag case) to 18.051MB for 3713210-byte allocation
,W/CpuWake (  909): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  909): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  909): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  909): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  909): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  909): <<release mCpuPerf_Freq wakelock
D/PMS     (  909): releaseHCC(437e8778): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  909): releaseHCC(437e7590): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4494): Initializing JXcore engine
,W/jxcore-log( 4494): JXcore engine is ready
,W/jxcore-log( 4494): Starting JXcore engine
,W/jxcore-log( 4494): Platform android
W/jxcore-log( 4494): 
,W/jxcore-log( 4494): Process ARCH arm
W/jxcore-log( 4494): 
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1169): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,I/jxcore-log( 4494): JXcore Cordova bridge is ready!
I/jxcore-log( 4494): 
,W/jxcore-log( 4494): JXcore engine is started
,I/chromium( 4494): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PMS     (  909): releaseWL(42596188): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4494): Toggling radios to true
I/jxcore-log( 4494): 
,D/BluetoothAdapter( 4494): enable(): BT is already enabled..!
,D/WifiManager( 4494): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
,W/HtcDLNAServiceManager(  909): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  909): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  909): Settings:Agentvalue: 2
W/Settings:Agent(  909): >> traceCallingStack()
W/Settings:Agent(  909): Process.myPid(): 909
W/Settings:Agent(  909): Process.myTid(): 1660
W/Settings:Agent(  909): Process.myUid(): 1000
W/Settings:Agent(  909): 
W/Settings:Agent(  909): 
,W/System.err(  909): java.lang.Throwable: stack dump
W/System.err(  909): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  909): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  909): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  909): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
,W/System.err(  909): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  909): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  909): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
,W/System.err(  909): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
D/WifiService(  909): New client listening to asynchronous messages
D/WifiService(  909): setWifiEnabled: true pid=4494, uid=10389
E/WifiService(  909): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  909): isSprintWifiRestricted(): false
I/WifiService(  909): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  909): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/System.err(  909): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  909): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  909): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  909): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  909): 
W/Settings:Agent(  909): << traceCallingStack(): 5(ms)
D/WifiManager( 4494): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  909): doBoolean: DISCONNECT
D/WifiManager( 4494): reconnect: Base Package Name=com.test.thalitest, uid=10389
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): TDLS: Tear down peers
I/wpa_supplicant( 1169): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4494): Radios toggled
I/jxcore-log( 4494): 
D/BluetoothManagerService(  909): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4494): Got Device Bluetooth address: B4:CE:F6:AB:A4:6A
I/jxcore-log( 4494): 
I/jxcore-log( 4494): Perf Test app loaded loaded
I/jxcore-log( 4494): 
I/jxcore-log( 4494): check test folder
I/jxcore-log( 4494): 
I/jxcore-log( 4494): found test : ./testFindPeers.js
I/jxcore-log( 4494): 
,I/jxcore-log( 4494): found test : ./testSendData.js
I/jxcore-log( 4494): 
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1169): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1169): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1169): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  909): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  909): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  909): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  909): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1169): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1169): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
,E/wpa_supplicant( 1169): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1169): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1169): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8488bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1169):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1169): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1169): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1169): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1169): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1169): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1169): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1169): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1169): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1169): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1169): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1169): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1169): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1169): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1169): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1169): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1169): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1169): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1169): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1169): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1169): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1169): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1169): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1169): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:4,8 SSID=NG700
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/WifiNative-wlan0(  909):    returned true
D/WifiPerfLock(  909): release()
D/WifiStateMachine(  909): PerfLock released for exiting ConnectedState
D/Tethering(  909): interfaceLinkStateChanged wlan0, false
,D/Tethering(  909): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 0
D/Tethering(  909): [isWifi] getHotspotEnabled: false
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1169): Power_Mode_Type mode = 0
I/wpa_supplicant( 1169): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/ConnectivityService(  909): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  909): acquireWL(42490be0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 909 1000 null
D/WifiP2pService(  909): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/Tethering(  909): interfaceLinkStateChanged wlan0, false
D/WifiNative-wlan0(  909):    returned true
D/Tethering(  909): interfaceStatusChanged wlan0, false
,D/Tethering(  909): [isWifi] getHotspotEnabled: false
D/DhcpStateMachine(  909): [RunningState] Stop DHCP
D/libc    (  909): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/libc    (  909): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiNative-wlan0(  909): doBoolean: RECONNECT
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): Fast associate: Old scan results
I/wpa_supplicant( 1169): wpa_supplicant_scan enter
I/wpa_supplicant( 1169): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1169): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1169): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1169): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023601
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023766
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023838
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023842
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023896
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023899
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025230
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025256
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028285
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029157
D/WifiNative-wlan0(  909):    returned true
D/WifiStateMachine(  909): Enter handleNetworkDisconnect
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1169): Power_Mode_Type mode = 0
I/wpa_supplicant( 1169): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  909):    returned true
D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  909): Exit handleNetworkDisconnect
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiDataStallTracker(  909): stopDataStallAlarm: current tag=19730 mDataStallAlarmIntent=PendingIntent{436f2fb0: PendingIntentRecord{424c64d0 android broadcastIntent}}
D/WIFI_ICON( 1120): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiP2pService(  909): InactiveState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1120): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
I/IntentController( 1120): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WISPrService( 3849): >>>>>WISPrService start isConnected = false<<<<<
D/UsbnetStateTracker(  909): isAvailable+-
D/UsbnetStateTracker(  909): reconnect
,D/UsbnetStateTracker(  909): isAvailable+-
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023601
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023766
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023838
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023842
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023896
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023899
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025230
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025256
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028285
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029157
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  909): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  909): Provision feature enable=false
D/ConnectivityService(  909): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  909): default: reconnect()
D/MDST    (  909): default: setTeardownRequested(false)
D/MDST    (  909): default: setEnableApn apnType =default , enable=true
,D/WifiStateMachine(  909): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS,
D/WISPrService( 3849): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/WISPrService( 3849): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  909): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 3849): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  909): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/WifiService(  909): New client listening to asynchronous messages
D/ConnectivityService(  909): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  909): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  909): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  909): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  909): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  909): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  909): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,V/NativeCrypto( 1367): Read error: ssl=0x65f85a80: I/O error during system call, Connection timed out
D/libc    (  362): [NET] entry_id:3   entry:0xb8e5a8e0  removed 
D/libc    (  362): [NET] entry_id:7   entry:0xb8e5f280  removed 
D/libc    (  362): [NET] entry_id:4   entry:0xb8e5f190  removed 
D/libc    (  362): [NET] entry_id:5   entry:0xb8e5f348  removed 
D/libc    (  362): [NET] entry_id:1   entry:0xb8e5f428  removed 
D/libc    (  362): [NET] entry_id:6   entry:0xb8e5f090  removed 
D/libc    (  362): [NET] entry_id:2   entry:0xb8e5f4f0  removed 
D/libc    (  362): [NET] entry_id:8   entry:0xb8e5afb0  removed 
,D/libc    (  362): *************************
D/libc    (  362): *** DNS CACHE FLUSHED ***
D/libc    (  362): *************************
W/ConnectivityService(  909): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  909): handleConnectivityChange: resetting
D/ConnectivityService(  909): resetConnections(wlan0, 3)
D/ConnectivityService(  909): flush DNS cache for net 1(wlan0)
D/WIFI_ICON( 1120): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/PMS     (  909): acquireWL(425d96c0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
D/Nat464Xlat(  909): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  909): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/WirelessDisplayService(  909): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  909): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,V/NativeCrypto( 1367): SSL shutdown failed: ssl=0x65f85a80: I/O error during system call, Broken pipe
,D/WifiStateMachine(  909): startScan Pid: 909 Uid 1000
,D/WifiNative-wlan0(  909): doBoolean: SCAN
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
D/ConnectivityService(  909): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  909): acquireWL(4236da90): PARTIAL_WAKE_LOCK  NetworkStats 0x1 909 1000 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  909): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
D/BatSI   (  909): WIFI scan started for: 650a0300 uid:1000
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023601
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023766
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1169): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  909):    returned false
,I//system/bin/ip(  362): RTNETLINK answers: No such process
,I/logwrapper(  362): /system/bin/ip terminated by exit(2)
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023838
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023842
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023896
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023899
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025230
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025256
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028285
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029157
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
D/ConnectivityService(  909): reportInetCondition for net -1, percentage: 0 by  (1367/10029)
D/PMS     (  909): releaseWL(4236da90): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/QuickSettingWifi( 1120): receive.wifiConnect:false wifiAPname:null elapse:1
,I/QuickSettingWifi( 1120): receive.wifiConnect:false wifiAPname:null elapse:1
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
D/PMS     (  909): releaseWL(425d96c0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
D/ConnectivityService(  909): mActiveDefaultNetwork: -1
D/ConnectivityService(  909): handleInetConditionChange: no active default network - ignore
,I/Choreographer( 4494): Skipped 95 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4494): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/Tethering(  909): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  909): [AlarmQueuing] connectivity wifi: false
,D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1229/10029)
,D/PMS     (  909): acquireWL(42519f60): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 909 1000 null
,I/NetworkMonitor( 3901): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.google.android.music (3901/10154)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.backuptransport (1574/10029)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.htc.launcher (1275/10076)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1229/10029)
,I/ConnectivityHelper( 1275): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.docs (4346/10100)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2187/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/CaptivePortalTracker(  909): DelayedCaptiveCheckState
D/CaptivePortalTracker(  909): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  909): NoActiveNetworkState
D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/Tethering(  909): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  909): bSetPropertyMultiRAB:false
,D/Tethering(  909): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
,I/Tethering(  909): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  909): ipv4Default null
,I/Tethering(  909): No IPv4 upstream interface, giving up.
,D/Tethering(  909): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2187/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2187/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.docs (4346/10100)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1941/10021)
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023601
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023766
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023838
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023842
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023896
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023899
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025230
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025256
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028285
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029157
,I/ActivityManager(  909): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4546 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/GpsLocationProvider(  909): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  909): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  909): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  909): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  909): releaseWL(42519f60): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ACRA    ( 4546): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4546): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4546): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4546): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4546): Preparing secondary program dexes.
V/DexLibLoader( 4546): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4546): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4546): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4546): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4546): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4546): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4546): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4546): Dex already copied
D/OdexVerifier( 4546): Odex verification is skipped.
,V/DexLibLoader( 4546): Creating class loader
,V/DexLibLoader( 4546): Finished creating class loader
V/DexLibLoader( 4546): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
,V/DexLibLoader( 4546): Dex already copied
D/OdexVerifier( 4546): Odex verification is skipped.
,V/DexLibLoader( 4546): Creating class loader
,V/DexLibLoader( 4546): Finished creating class loader
V/DexLibLoader( 4546): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
,V/DexLibLoader( 4546): Dex already copied
D/OdexVerifier( 4546): Odex verification is skipped.
,V/DexLibLoader( 4546): Creating class loader
,V/DexLibLoader( 4546): Finished creating class loader
V/DexLibLoader( 4546): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4546): Dex already copied
,D/OdexVerifier( 4546): Odex verification is skipped.
,V/DexLibLoader( 4546): Creating class loader
,V/DexLibLoader( 4546): Finished creating class loader,
V/DexLibLoader( 4546): Verifying classes from secondary dexes.,
,D/DexLibLoader( 4546): DexLibLoader.ensureDexLoaded took 19 ms
,I/PMS     (  909): Going to sleep due to screen timeout...
,I/SensorManager(  909): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42123220
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  909): disable: get sensor name = CM36282 Light sensor
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 2
W/SensorService(  909): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42123220, eanble = 0, strlen(mName) = 59
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  909): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41b8c3f0
W/SensorService(  909): Listener[1] = com.htc.smartdim.sensor_eye@426414c8
,W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  909): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  909): Couldn't get kernel wake lock stats
V/LightsService(  909): setLight #2: color=#0
D/qdlights(  909): set_light_buttons_func: on=0 brightness=0
V/LightsService(  909): setLight #0: color=#0
,D/WirelessDisplayService(  909): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  909): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  909): mWirelessDisplayManager is null
,I/SensorManager(  909): mEventCount = 1350
,D/SurfaceControl(  909): Excessive delay in blankDisplay() while turning screen off: 314ms
D/NfcService( 1257): ScreenObserver: OFF
,D/NfcService( 1257): applyRouting - 0
D/PMS     (  909): nativeSetInteractive:false
D/PMS     (  909): nativeSetInteractive:false done
D/PMS     (  909): nativeSetAutoSuspend:true
D/PMS     (  909): nativeSetAutoSuspend:true done
D/HABCtrl (  909): TPE algorithm. remove timeout.
,D/PMS     (  909): OOBE c monitor 11
,V/KeyguardServiceDelegate(  909): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@431c41a8)
D/PMN     (  909): wakingUp
,V/KeyguardServiceDelegate(  909): **** SHOWN CALLED ****
,D/NfcService( 1257): applyRouting -2
D/PMS     (  909): acquireWL(42e508b0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1257 1027 null
I/WindowManager(  909): No lock screen! windowToken=null
I/InputMethodManagerService(  909): screenObserver, isScreenOn=false
I/InputMethodManagerService(  909): Disable input method client, pid=4494
W/ResourceType( 4494): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4494): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41a87208 VFEDH.C. .F...... 0,0-720,1134 #64}
D/PMS     (  909): acquireWL(432bff80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
D/PMS     (  909): releaseWL(42e508b0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMS     (  909): releaseWL(432bff80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMN     (  909): onScreenOn
I/InputManager(  909): Cancel all due to getting PMS screen off broadcast
D/HtcPowerSaver(  909): updateBatteryInfo
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/WirelessDisplayService(  909): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1120): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/WirelessDisplayService(  909): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  909): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,D/MtpService( 1941): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 1941): [MTP][onReceive]-
,D/NfcService( 1257): applyRouting - 0
,D/NfcService( 1257): applyRouting -2
I/HtcPowerSaver(  909): << updateStatus
D/PMS     (  909): acquireWL(4323bbd0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1257 1027 null
V/NotificationService(  909): batLight: Full, plugged
V/LightsService(  909): setLight #8: color=#c8c800
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  909): setLight #8: color=#c800
D/qdlights(  909): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/PMS     (  909): releaseWL(4323bbd0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/qdlights(  909): [LedInfo] has indicator attribute
D/WirelessDisplayService(  909): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  909): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  909): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  909): onReceive: action=android.intent.action.SCREEN_ON
D/WifiNative-wlan0(  909): doBoolean: SET_SCREEN_ON 1
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1169): SET_SCREEN_ON:On
I/wpa_supplicant( 1169): htc_wext_set_keepalive +
I/wpa_supplicant( 1169): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1169): getPrivFuncNum +	
I/wpa_supplicant( 1169): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1169): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1169): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1169): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1169): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  909):    returned true
,D/WifiNative-wlan0(  909): doBoolean: SET pno 0
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): CTRL_IFACE SET 'pno'='0'
,I/wpa_supplicant( 1169): wpa_supplicant_scan enter
,D/WifiNative-wlan0(  909):    returned true
,V/SRS_Proc(  370): ParamSet string: screen_state=on
,D/WirelessDisplayService(  909): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AlarmManager(  909): ACTION_SCREEN_ON
I/AlarmManager(  909): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  909): [AlarmQueuing] done recovering
I/AlarmManager(  909): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  909): [AlarmQueuing] done EPS screen off alarm recovering
V/NotificationService(  909): batLight: Full, plugged
V/LightsService(  909): setLight #8: color=#c8c800
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  909): setLight #8: color=#c800
D/qdlights(  909): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/NetworkPolicy(  909): updateScreenOn: false
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,I/ClockThread( 1120): stop update clock
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  909): acquireWL(43d1b288): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1229 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(43d1b288): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): acquireWL(442dfb88): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1229 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(442dfb88): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1743): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1743): onScreenOn: 1452883485036
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1743): onScreenOn: 1452883485036
,I/SensorManager(  909): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41b8c3f0
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  909): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 2
W/SensorService(  909): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41b8c3f0, eanble = 0, strlen(mName) = 91
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  909): Listener[0] = com.htc.smartdim.sensor_eye@426414c8
,W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/WifiDataStallTracker(  909): onReceive: action=android.intent.action.SCREEN_OFF
D/PMN     (  909): goingToSleep
D/PMS     (  909): acquireWL(431b9b70): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 909 1000 null
D/AlarmManager(  909): ACTION_SCREEN_OFF
I/AlarmManager(  909): [AlarmQueuing] screen off now: 
I/AlarmManager(  909): [AlarmQueuing] data connection: true
,I/AlarmManager(  909): [AlarmQueuing] wifi connection: true
D/WifiDataStallTracker(  909): stopDataStallAlarm: current tag=19731 mDataStallAlarmIntent=null
D/WifiNative-wlan0(  909): doBoolean: SET pno 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
,D/WifiNative-wlan0(  909): doBoolean: SET_SCREEN_ON 0
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1169): CTRL_IFACE SET 'pno'='1'
D/PMS     (  909): acquireWL(43958ba0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 909 1000 null
D/PMS     (  909): releaseWL(431b9b70): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1169): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1169): nl80211: Event message available
,D/wpa_supplicant( 1169): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1169): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1169): nl80211: Survey data missing
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1169): Sorted scan results
I/wpa_supplicant( 1169): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-52
D/wpa_supplicant( 1169): BSS: last_scan_res_used=1/32 last_scan_full=0
D/wpa_supplicant( 1169): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1169): WPS: AP[0] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1169): wpa_supplicant_pick_network+
I/wpa_supplicant( 1169): Selecting BSS from priority group 1
I/wpa_supplicant( 1169): Recent assoc_freq = 0 rssi = 0
D/WifiNative-wlan0(  909):    returned true
D/wpa_supplicant( 1169): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1169): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1169):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1169):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-52
I/wpa_supplicant( 1169): Start print parameters
I/wpa_supplicant( 1169): wpa_s->wpa_state is 3
I/wpa_supplicant( 1169): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1169): isConcurrentMode() is 0
I/wpa_supplicant( 1169): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1169): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1169): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1169): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1169): wpa_s->reassociate is 1
I/wpa_supplicant( 1169): wpa_s->is_screen_on 1
I/wpa_supplicant( 1169): wpa_s->ifname wlan0
I/wpa_supplicant( 1169): End print parameters
I/wpa_supplicant( 1169): selected network = 1
D/wpa_supplicant( 1169): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb848a4e8  current_ssid=0x0
D/wpa_supplicant( 1169): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1169): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1169): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1169): check if in concurrent case
I/wpa_supplicant( 1169): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
,D/WifiNative-wlan0(  909): doBoolean: DRIVER SETSUSPENDMODE 1
D/wpa_supplicant( 1169): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1169): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1169): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1169): RSN: PMKSA cache search - network_ctx=0xb848a4e8 try_opportunistic=0
D/wpa_supplicant( 1169): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1169): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1169): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1169): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1169): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1169): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1169): nl80211: Unsubscribe mgmt frames handle 0xb8489718 (mode change)
D/wpa_supplicant( 1169): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8489718
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8489718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8489718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8489718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8489718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8489718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8489718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8489718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8489718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8489718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Register frame type=0xd0 nl_handle=0xb8489718
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1169): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1169):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1169):   * freq=2412
D/wpa_supplicant( 1169):   * Auth Type 0
D/wpa_supplicant( 1169):   * WPA Versions 0x2
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1169): nl80211: Connect request send successfully
D/wpa_supplicant( 1169): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1169): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1169): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1169): SET_SCREEN_ON:Off
I/wpa_supplicant( 1169): htc_wext_set_keepalive +
I/wpa_supplicant( 1169): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1169): getPrivFuncNum +	
I/wpa_supplicant( 1169): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1169): htc_wext_set_keepalive fnum = 0x8bf6
,I/wpa_supplicant( 1169): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 1169): get_ip_address source addr = 02000000
I/wpa_supplicant( 1169): htc_wext_set_keepalive gateway addr = 00000000
I/wpa_supplicant( 1169): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  909):    returned true
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  909):    returned true
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  909): doBoolean: SET pno 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): CTRL_IFACE SET 'pno'='1'
D/WifiNative-wlan0(  909):    returned true
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023601
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023766
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023838
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023842
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023896
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023899
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025230
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025256
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028285
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029157
D/PMS     (  909): releaseWL(43958ba0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
V/SRS_Proc(  370): ParamSet string: screen_state=off
D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1169): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1169): reply (376) for get BSS: id=0
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1169): freq=5220
I/wpa_supplicant( 1169): level=-46
I/wpa_supplicant( 1169): tsf=0000000021650208
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG7005g
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=1
I/wpa_supplicant( 1169): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): freq=2412
I/wpa_supplicant( 1169): level=-52
I/wpa_supplicant( 1169): tsf=0000000104931900
I/wpa_supplicant( 1169): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1169): ssid=NG700
I/wpa_supplicant( 1169): ====
I/wpa_supplicant( 1169): id=2
I/wpa_supplicant( 1169): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1169): freq=2452
I/wpa_supplicant( 1169): level=-85
I/wpa_supplicant( 1169): tsf=0000000021650224
I/wpa_supplicant( 1169): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1169): ssid=Gonzos
I/wpa_supplicant( 1169): ####
D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (3) end of scan result ==
D/WifiManager( 1229): getScanResults enter 
D/WirelessDisplayService(  909): getDiscoveryDongleList
D/WifiStateMachine(  909): == begin of scan result ==
D/WifiStateMachine(  909): == (3) end of scan result ==
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 21650208, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -52, frequency: 2412, timestamp: 104931900, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2452, timestamp: 21650224, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 3 to mScanResults
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/BatSI   (  909): WIFI scan stopped for: 440a0300 uid:1000
D/NetworkPolicy(  909): updateScreenOn: false
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ContactMessageStore( 1243): start background delete task...
D/ContactMessageStore( 1243): size: 0 , 0
D/ContactMessageStore( 1243): Background delete complete
,W/dalvikvm( 4546): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 4546): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 4546): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 4546): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 4546): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 4546): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 4546): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
D/AutoSetting( 1301): service - mHandler: cancel location update
D/AutoSetting( 1301): service -           changes count: 0
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] getTotalRam: 1873 Mb
D/PMS     (  909): acquireWL(425da9b0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1229 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(425da9b0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): acquireWL(42ad80f0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1229 10029 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1743): onScreenOff.
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1743): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1743): disableBatteryAlarm
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1743): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1743): onScreenOff
D/PMS     (  909): releaseWL(42ad80f0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/wpa_supplicant( 1169): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1169): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1169): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1169): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1169): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1169): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1169): nl80211: if_removed already cleared - ignore event
D/Tethering(  909): interfaceLinkStateChanged wlan0, false
D/Tethering(  909): interfaceStatusChanged wlan0, false
D/Tethering(  909): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1169): nl80211: Connect event
D/wpa_supplicant( 1169): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1169): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1169): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1169): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1169): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1169): Add randomness: count=7 entropy=1
I/wpa_supplicant( 1169): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1169): TDLS: Remove peers on association
D/wpa_supplicant( 1169): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/Tethering(  909): interfaceLinkStateChanged wlan0, true
D/Tethering(  909): interfaceStatusChanged wlan0, true
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1169): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1169): EAPOL: External notification - EAP success=0
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/Tethering(  909): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 1169): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1169): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1169): EAPOL: enable timer tick
D/wpa_supplicant( 1169): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1169): htc_wext_set_keepalive +
I/wpa_supplicant( 1169): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1169): getPrivFuncNum +	
I/wpa_supplicant( 1169): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1169): htc_wext_set_keepalive fnum = 0x8bf6
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
I/wpa_supplicant( 1169): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1169): State: ASSOCIATED -> 4WAY_HANDSHAKE
,D/wpa_supplicant( 1169): Get randomness: len=32 entropy=2
,D/WifiMonitor(  909): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  909): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  909): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  909): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  909): WifiMonitor:getFreqFromEventString() 2412
,D/HTCRequest(  909): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/WifiMonitor(  909): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  909): handleAssociatedWithEvent. bLFR =false
,D/WifiMonitor(  909): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  909): Enter handleAssociatedWithEvent
,D/WifiStateMachine(  909): Associated
D/WifiStateMachine(  909): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  909): Exit handleAssociatedWithEvent
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,I/wpa_supplicant( 1169): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb84899f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1169):    addr=c0:ff:d4:d3:aa:48
D/WifiStateMachine(  909): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  909): updateConnectedAP...
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1169): EAPOL: External notification - portValid=1
D/WifiApDatabaseHandler(  909): updateConnectedAP...
I/wpa_supplicant( 1169): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f39b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1169):    broadcast key
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  909): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1169): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1169): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1169): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1169): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1169): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
,D/WifiMonitor(  909): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1169): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1169): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1169): netlink: Operstate: linkmode=-1, operstate=6
D/WifiApDatabaseHandler(  909): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  909): This record is existed, only update it...
I/wpa_supplicant( 1169): set send_ind_to_ndc = 0,
I/wpa_supplicant( 1169): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1169): htc_wext_set_TX_TRACKING - ret = 0
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1169): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1169): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1169): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/wpa_supplicant( 1169): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1169): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1169): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1169): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1169): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 18
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1169): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1169): EAPOL authentication completed successfully
,I/wpa_supplicant( 1169): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1169): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1169): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/wpa_supplicant( 1169): nl80211: if_removed already cleared - ignore event
,D/WifiApDatabaseHandler(  909): updateConnectedAP...
,D/Tethering(  909): interfaceLinkStateChanged wlan0, true
,D/Tethering(  909): interfaceStatusChanged wlan0, true
,D/Tethering(  909): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  909): updateConnectedAP...
,D/WifiStateMachine(  909): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
I/IntentController( 1120): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiStateMachine(  909): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WIFI_ICON( 1120): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiApDatabaseHandler(  909): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  909): This record is existed, only update it...
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  909): updateConnectedAP...
,D/WISPrService( 3849): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3849): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  909): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  909): Provision feature enable=false
,D/ConnectivityService(  909): mActiveDefaultNetwork: -1
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  909): updateConnectedAP...
,D/WifiNative-wlan0(  909): doBoolean: SET pno 0
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1169): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/WifiNative-wlan0(  909):    returned true
D/DhcpStateMachine(  909): [StoppedState] Start DHCP
,D/WifiStateMachine(  909): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1169): Power_Mode_Type mode = 1
I/wpa_supplicant( 1169): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doString: DRIVER WLS_BATCHING GET,
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd: failed to issue private commands,
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  909):    returned null
,E/WifiStateMachine(  909): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  909): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  909):    returned null
D/WifiStateMachine(  909): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  909): acquireWL(435ec4c8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 909 1000 null
D/WifiStateMachine(  909): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  909): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42559970 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  909): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42559970 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1169): nl80211: Event message available
D/wpa_supplicant( 1169): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1169): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
,I/QuickSettingWifi( 1120): receive.wifiConnect:false wifiAPname:null elapse:0
,W/dalvikvm( 4546): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4546): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4546): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4546): Verify
,D/WifiService(  909): New client listening to asynchronous messages
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4546): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4546): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4546): Grow heap (frag case) to 9.509MB for 73240-byte allocation
,D/Process (  909): killProcessQuiet, pid=3882
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  909): Killing 3882:com.htc.mediamanager/u0a34 (adj 15): empty #17
,D/AutoSetting( 1301): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  909): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4581 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1301/10055)
,D/AutoSetting( 1301): Util - no network available!
,D/AutoSetting( 1301): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1301/10055)
D/AutoSetting( 1301): service - mHandler: cancel location update
D/AutoSetting( 1301): service -           changes count: 0
,W/fb4a(:<default>):UserScope( 4546): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4546): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4546): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
I/ActivityManager(  909): Recipient 3882
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MobileConnectivityChangeReceiver( 4581): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4581): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4581): onOtaspChanged old =0, new =3
V/PhoneMonitor( 4581): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,D/libc    (  909): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
,I/ActivityManager(  909): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4599 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  909): killProcessQuiet, pid=4282
,I/ActivityManager(  909): Killing 4282:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4581/10079)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4581/10079)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4581/10079)
,I/ActivityManager(  909): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4629 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Recipient 4282
,D/WifiService(  909): Client connection lost with reason: 4
,D/Process (  909): killProcessQuiet, pid=4187
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  909): Killing 4187:com.google.android.talk/u0a111 (adj 15): empty #17
,E/dalvikvm( 4546): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4546): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4546): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4546): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4546): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4546): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,D/libc    (  909): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  909): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  909):    returned true
,D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1169): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1169): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
I/ActivityManager(  909): Recipient 4187
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  909):    returned true
,D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1169): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  909):    returned true
,D/WifiStateMachine(  909): handlePostDhcpSetup release wake lock during DHCP
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  909): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  909): releaseWL(435ec4c8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,I/dalvikvm-heap( 4546): Grow heap (frag case) to 9.959MB for 84664-byte allocation
E/dalvikvm( 4546): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4546): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4546): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/dalvikvm( 4546): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4546): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4546): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
,W/Vold    (  352): Returning OperationFailed - no handler for errno 30
W/dalvikvm( 4546): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4546): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4546): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4546): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4546): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4546): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
W/ContextImpl( 4629): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [3][0][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,W/ContextImpl( 4629): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,D/WIFI_ICON( 1120): updateWifiState: RSSI_CHANGED -1 -> 3
D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1169): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,D/WifiStateMachine(  909): gateway: /192.168.1.1
,D/WifiNative-wlan0(  909): doBoolean: DRIVER GATEWAY-ADD 16885952
W/GAV2    ( 4629): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1169): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1169): htc_wext_set_keepalive +
I/wpa_supplicant( 1169): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1169): getPrivFuncNum +	
I/wpa_supplicant( 1169): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1169): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1169): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1169): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1169): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  909):    returned true
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  909): VerifyingLinkState enter
D/WifiStateMachine(  909): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  909): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  909): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -51, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiWatchdogStateMachine(  909): WAN detection
,I/IntentController( 1120): receive(android.net.wifi.STATE_CHANGE,1,false)
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
V/NetworkPolicy(  909): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/ConnectivityService(  909): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  909): Provision feature enable=false
D/ConnectivityService(  909): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  909): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  909): default: teardown()
D/MDST    (  909): default: setTeardownRequested(true)
D/MDST    (  909): default: setEnableApn apnType =default , enable=false
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
D/WISPrService( 3849): >>>>>WISPrService start isConnected = true<<<<<
,W/ContextImpl( 4629): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
I/dalvikvm-heap( 4546): Grow heap (frag case) to 9.971MB for 28144-byte allocation
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  909): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  909): syncGetConfiguredNetworks
D/MDST    (  909): default: setTeardownRequested(true)
D/ConnectivityService(  909): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
D/WIFI_ICON( 1120): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1120): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/ConnectivityService(  909): Unexpected mtu value: android.net.wifi.WifiStateTracker@42404280
D/ConnectivityService(  909): handleConnectivityChange: netType=1 doReset=false resetMask=0
,W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4629): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  909): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  909): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  909): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,D/libc    (  362): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  909): handleConnectivityChange: resetting
D/Nat464Xlat(  909): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  909): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  909): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  909): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  909): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  909): acquireWL(42c57578): PARTIAL_WAKE_LOCK  NetworkStats 0x1 909 1000 null
D/ConnectivityService(  909): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
D/WirelessDisplayService(  909): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/wpa_supplicant( 1169): EAPOL: startWhen --> 0
D/wpa_supplicant( 1169): EAPOL: disable timer tick
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/WirelessDisplayService(  909):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=100 [1][1][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4581/10079)
I/dalvikvm-heap( 4546): Grow heap (frag case) to 10.012MB for 39954-byte allocation
I/QuickSettingWifi( 1120): receive.wifiConnect:true wifiAPname:NG700 elapse:2
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): releaseWL(42c57578): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/PMS     (  909): acquireWL(4429dd60): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
I//system/bin/ip(  362): RTNETLINK answers: No such file or directory
I/logwrapper(  362): /system/bin/ip terminated by exit(254)
,D/PMS     (  909): acquireWL(43d3b7e0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2187): Checkin interval check for package: unspecified last checkin: 1452883438290 min interval config: 0 actual interval: 47938
D/PMS     (  909): releaseWL(4429dd60): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2187): Checking schedule, now: 1452883486234 next: 1452883468251
,I/CheckinService( 2187): active receiver: enabled
,I//system/bin/ip(  362): RTNETLINK answers: No such process
,I/logwrapper(  362): /system/bin/ip terminated by exit(2)
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2187, uid=10029, userID:0
,I/dalvikvm-heap( 4546): Grow heap (frag case) to 10.088MB for 79892-byte allocation
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2187/10029)
,D/ConnectivityService(  909): mActiveDefaultNetwork: WIFI
I/CheckinService( 2187): Preparing to send checkin request
I/EventLogService( 2187): Accumulating logs since 1452883433079
,I/CheckinRequestBuilder( 2187): Checkin reason type: 8 attempt count: 1
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (4629/10151)
I/ActivityManager(  909): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2187): Failed to find provider info for com.google.android.wearable.settings
,V/WebViewChromiumFactoryProvider( 4629): Binding Chromium to main looper Looper (main, tid 1) {41a7e2b0}
,I/LibraryLoader( 4629): Expected native library version number "",actual native library version number ""
I/chromium( 4629): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4629): Initializing chromium process, renderers=0
,D/PMS     (  909): acquireWL(44311a38): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
,D/PMS     (  909): acquireWL(44301758): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
,E/AudioManagerAndroid( 4629): BLUETOOTH permission is missing!
D/PMS     (  909): releaseWL(44311a38): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4629): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4629): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4629): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4629): Local Branch: 
I/Adreno-EGL( 4629): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4629): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4629):                  aa63bbd948f41d15fc72f585e
,I/dalvikvm-heap( 4546): Grow heap (frag case) to 10.276MB for 75760-byte allocation
,I/NSApplication( 4629): Starting up...
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
W/BroadcastQueue(  909): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43830ee8 u0 ReceiverList{429d15a8 4546 com.facebook.katana/10027/u0 remote:42ef0600}}
W/BroadcastQueue(  909): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43830ee8 u0 ReceiverList{429d15a8 4546 com.facebook.katana/10027/u0 remote:42ef0600}}
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (4629/10151)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (4629/10151)
W/BroadcastQueue(  909): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43707170 u0 ReceiverList{4251b118 4546 com.facebook.katana/10027/u0 remote:426a2718}}
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023601
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023766
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023838
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023842
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023896
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023899
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025230
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025256
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028285
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029157
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [2][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4116/10160)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4116/10160)
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,D/Process (  909): killProcessQuiet, pid=4314
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  909): Killing 4314:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2187/10029)
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Recipient 4314
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2187/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2187/10029)
,D/AutoSetting( 1301): receiver - intent: android.intent.action.USER_PRESENT
D/TetherSettings( 3849): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3849): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3849): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3849): Cust_ConnectToPC   : spcsc>false
D/        ( 3849): Cust_ConnectToPC   : IPT>true
D/        ( 3849): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3849): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3849): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3849): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3849): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/AutoSetting( 1301): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
D/ConnectivityService(  909): getNetworkInfo networkType=9 called by com.google.android.gms (2187/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2187/10029)
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,I/PSReceiver( 3849): onReceive:android.intent.action.USER_PRESENT
I/SmartNS_PSService( 3849): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3849): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3849):  defaultType:0
W/ContextImpl( 3849): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  909): acquireWL(43825388): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1229 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(43825388): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  909): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4681 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  352): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4546): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4546): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4546): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  909): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4697 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,W/ContextImpl( 4681): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4681): isEpsOn(), nState = 0
,D/PMS     (  909): acquireWL(42335c38): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4681 1000 null
,W/dalvikvm( 4697): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/SmartSyncUtils( 4681): getMobilePolicyEnabled, result = true
,W/dalvikvm( 4697): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/PMS     (  909): releaseWL(42335c38): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
I/MultiDex( 4697): VM with version 1.6.0 does not have multidex support
I/MultiDex( 4697): install
,I/MultiDex( 4697): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,D/Process (  909): killProcessQuiet, pid=4346
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/MultiDex( 4697): loading existing secondary dex files
,I/MultiDex( 4697): load found 3 secondary dex files
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  909): Killing 4346:com.google.android.apps.docs/u0a100 (adj 15): empty #17
I/MultiDex( 4697): install done
,I/ActivityManager(  909): Recipient 4346
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 4681): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4681): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4681): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4681): isEpsOn(), nState = 0
D/WifiService(  909): New client listening to asynchronous messages
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  909): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@426414c8
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  909): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 1
W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@426414c8, eanble = 0, strlen(mName) = 36
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  909): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 0
W/SensorService(  909): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@426414c8, eanble = 0, strlen(mName) = 36
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  909): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@426414c8
W/dalvikvm( 4697): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4697): VFY: unable to resolve instance field 36
,E/ActivityThread(  909): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42641a58 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  909): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42641a58 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  909): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  909): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  909): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  909): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  909): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  909): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  909): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  909): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  909): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  909): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  909): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  909): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  909): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  909): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  909): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  909): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  909): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  909): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  909): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 4697): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4697): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ProviderInstaller( 4697): Installed default security provider GmsCore_OpenSSL
,W/dalvikvm( 4697): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4697): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,W/dalvikvm( 4697): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4697): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4697): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4697): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4697): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/WearableService( 1229): callingUid 10029, callindPid: 1229
,D/LocationInitializer( 2187): Restart initialization of location
,E/MDM     ( 1229): [119] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/GCoreFlp( 1229): No location to return for getLastLocation()
,W/FusedLocationProvider( 1229): location=null
D/PMS     (  909): acquireWL(4226a288): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1229 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(4226a288): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023601
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023766
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023838
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023842
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023896
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023899
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025230
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025256
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028285
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029157
,D/AuthorizationBluetoothService( 1367): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1367): Proximity feature is not enabled.
,I/WVCdm   (  370): Level3 Library Nov 20 2013 18:09:31
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/WVCdm   (  370): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  370): CdmEngine::OpenSession
,I/WVCdm   (  370): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  370): CdmEngine::GenerateKeyRequest
,D/NativeLibraryUtils( 4697): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  370): PrepareKeyRequest: nonce=2510318713
,I/WVCdm   (  370): CdmEngine::CloseSession
,D/PMS     (  909): releaseWL(42490be0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  909): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  909): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/GpsLocationProvider(  909): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  909): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,D/GpsLocationProvider(  909): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  909): ignore wifi update if we are not in OPENING or CLOSING
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
I/AlarmManager(  909): [AlarmQueuing] connectivity wifi: true
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
D/PMS     (  909): acquireWL(4256d570): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 909 1000 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): releaseWL(4256d570): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1229/10029)
D/CaptivePortalTracker(  909): NoActiveNetworkState
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,V/Tethering(  909): bSetPropertyMultiRAB:false
,D/Tethering(  909): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/ConnectivityHelper( 1275): [onReceive] WIFI(1): CONNECTED
,I/Tethering(  909): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
,I/Tethering(  909): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/NetworkMonitor( 3901): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2187/10029)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.google.android.music (3901/10154)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1229/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4581/10079)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.htc.launcher (1275/10076)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.musicenhancer (3964/10053)
I/Tethering(  909): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  909): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  909): Found interface wlan0
,D/Tethering(  909): TetherMasterSM: InitialState processMessage what=3
D/AccTypeManager( 1343): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  909): DelayedCaptiveCheckState
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(43824558): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.backuptransport (1574/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.backuptransport (1574/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/PMS     (  909): releaseWL(43824558): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2187/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2187/10029)
W/AccTypeManager( 1343): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1343): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023601
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023766
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023838
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023842
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023896
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023899
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025230
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025256
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028285
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029157
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1941/10021)
,E/ExternalAccountType( 1343): Unsupported attribute readOnly
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (4697/10029)
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,D/AutoSetting( 1301): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4581): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4581): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1301/10055)
,D/AutoSetting( 1301): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1301): service - onStartCommand() screen is off, don't request location
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (4629/10151)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1301/10055)
D/AutoSetting( 1301): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1301): service - onStartCommand() check timezone in 30000
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4116/10160)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4116/10160)
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): acquireWL(43205200): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2187): Checkin interval check for package: unspecified last checkin: 1452883438290 min interval config: 0 actual interval: 49058
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,D/PMS     (  909): releaseWL(43205200): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/dalvikvm-heap( 4116): Grow heap (frag case) to 13.501MB for 1821008-byte allocation
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2187, uid=10029, userID:0
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2187/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2187/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2187/10029)
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,I/Adreno-EGL( 4697): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4697): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4697): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4697): Local Branch: 
I/Adreno-EGL( 4697): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4697): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4697):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4697): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4697): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4697): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4697): Local Branch: 
I/Adreno-EGL( 4697): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4697): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4697):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4697): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4697): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4697): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4697): Local Branch: 
I/Adreno-EGL( 4697): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4697): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4697):                  aa63bbd948f41d15fc72f585e
,I/WVCdm   (  370): CdmEngine::OpenSession
,I/WVCdm   (  370): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  370): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  370): PrepareKeyRequest: nonce=1385099624
,I/WVCdm   (  370): CdmEngine::CloseSession
,W/Settings( 4697): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinRequestBuilder( 2187): Classify the device as Phone.
,D/libc    ( 2187): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2187): [NET] getaddrinfo-,err=8
D/libc    ( 2187): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2187): [NET] getaddrinfo-, 1
,D/libc    ( 2187): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =b96 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,W/dalvikvm( 4494): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4494): threadid=1: thread exiting with uncaught exception (group=0x4164ae30)
,E/ActivityManager(  909): App crashed! Process: com.test.thalitest
E/AndroidRuntime( 4494): FATAL EXCEPTION: main
E/AndroidRuntime( 4494): Process: com.test.thalitest, PID: 4494
E/AndroidRuntime( 4494): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4494): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4494): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4494): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4494): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4494): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4494): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4494): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4494): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4494): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4494): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4494): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4494): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4494): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4494): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4494): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4494): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4494): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4494): 	at dalvik.system.NativeStart.main(Native Method)
W/ActivityManager(  909):   Force finishing activity com.test.thalitest/.MainActivity
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 169
D/libc    (  362): [NET]res_nsend:resplen=84
D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2187): [NET] getaddrinfo_proxy-, success
,D/Process (  909): killProcessQuiet, pid=4369
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
,I/ActivityManager(  909): Killing 4369:com.htc.backup/1000 (adj 15): empty #17
D/Process ( 4494): killProcess, pid=4494
D/Process ( 4494): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/ActivityManager(  909): Recipient 4369
,D/libc    ( 2187): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2187): [NET] getaddrinfo-,err=8
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/JavaBinder(  909): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  909): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder( 1215): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  909): Got RemoteException sending setActive(false) notification to pid 4494 uid 10389
,D/libc    ( 2187): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2187): [NET] getaddrinfo-,err=8
D/libc    ( 2187): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2187): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2187): Sending checkin request (12081 bytes)
,I/ActivityManager(  909): Recipient 4494
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  909): WIN DEATH: Window{423a4b88 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager(  909): Process com.test.thalitest (pid 4494) has died.
,D/WifiService(  909): Client connection lost with reason: 4
,D/libc    (  909): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-,err=8
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  909): [NET] getaddrinfo-, 1
,D/libc    (  909): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1,
D/libc    (  362): [NET] +++++ res_nsend xid =c21a +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE,
,I/CheckinRequestBuilder( 2187): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  909): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2187): Failed to find provider info for com.google.android.wearable.settings
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  362): [NET]res_nsend:resplen=172
D/libc    (  362): [NET]res_queryN: exit 3, ancount=4
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  909): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  909): Find DNS Address www.htc.com/23.44.209.153
,D/ConnectivityService(  909): getNetworkInfo networkType=9 called by com.google.android.gms (2187/10029)
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=9 [22][2][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2187/10029)
,D/PMS     (  909): releaseWL(44301758): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/CheckinRequestBuilder( 2187): Classify the device as Phone.
,I/CheckinTask( 2187): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2187): Checking schedule, now: 1452883489387 next: 1453406426382
,I/CheckinService( 2187): active receiver: disabled
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2187, uid=10029, userID:0
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023601
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023766
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023838
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023842
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023896
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023899
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025230
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025256
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028285
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029157
I/CheckinService( 2187): Checking schedule, now: 1452883489408 next: 1453406426382
,I/CheckinService( 2187): active receiver: disabled
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2187, uid=10029, userID:0
,D/CheckinService( 2187): Recording last checkin time for package unspecified as 1452883489416
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023601
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023766
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023838
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023842
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023896
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023899
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025230
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025256
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028285
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029157
,D/PMS     (  909): releaseWL(43d3b7e0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2187/10029)
,D/PMS     (  909): acquireWL(442ea240): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 1367): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    ( 1367): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1367): [NET] getaddrinfo-,err=8
D/libc    ( 1367): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1367): [NET] getaddrinfo-, 1
,D/libc    ( 1367): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =b6fd +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 235
D/libc    (  362): [NET]res_nsend:resplen=79
D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1367): [NET] getaddrinfo_proxy-, success
,W/fb4a(:<default>):UserScope( 4546): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4546): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [2][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
D/libc    ( 1367): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
D/libc    ( 1367): [NET] getaddrinfo-,err=8
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [1][0][0]
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/libc    ( 1367): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1367): [NET] getaddrinfo-,err=8
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
,D/PMS     (  909): acquireWL(4263b678): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
,D/PMS     (  909): releaseWL(442ea240): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
,D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1367/10029)
D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  909): handleInetConditionChange: starting a change hold
,D/PMS     (  909): releaseWL(4263b678): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(434d5b70): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
,D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1367/10029)
D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  909): handleInetConditionChange: currently in hold - not setting new end evt,
,E/fb4a(:<default>):LocalFbBroadcastManager( 4546): Called registerBroadcastReceiver twice.
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1367/10029)
D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  909): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023601
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023766
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023838
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023842
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023896
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023899
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025230
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025256
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028285
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029157
D/PMS     (  909): releaseWL(434d5b70): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/ConnectivityService(  909): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  909): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=28 [7][2][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0],
,D/WifiStateMachine(  909): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  909): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
,I/GAV2    ( 4629): Thread[GAThread,5,main]: No campaign data found.
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC <<
,D/AutoSetting( 1512): service - handleMessage() stop self
,D/AutoSetting( 1512): service - onDestroy() END
,D/AutoSetting( 1512): service - handleMessage() quit looper
,D/Process (  909): killProcessQuiet, pid=4333
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4333:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 4333
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcKeyguardAppUpdateMonitor( 1120): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
,I/HtcKeyguardAppUpdateMonitor( 1120): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1120): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1343): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  909): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4759 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "sms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,W/AccTypeManager( 1343): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1343): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "smsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,W/Prism.AllAppsManager( 1275): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/SystemReader( 1257): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/Launcher( 1275): Deferring update until onResume
,D/Launcher( 1275): waitUntilResume // bindAppsUpdated
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,E/ExternalAccountType( 1343): Unsupported attribute readOnly
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "sms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "smsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
,D/PhoneApp( 1243): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,D/AutoSetting( 1301): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1301): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1301): service - requestNLP() NetworkLocationProvider not enabled
,I/Babel   ( 4759): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4759): MmsConfig.loadMmsSettings
,W/dalvikvm( 4759): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4759): VFY: unable to resolve instance field 36
,W/dalvikvm( 4759): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4759): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  909): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4782 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4759, uid=10111, userID:0
,W/Settings( 4759): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4759, uid=10111, userID:0
,D/MessageFrequencyProvider( 4782): onCreate
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4759, uid=10111, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4759, uid=10111, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4759, uid=10111, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4759, uid=10111, userID:0
V/GetPrviateResource( 4782): GetPrviateResource
,D/MmsCustomizationProvider( 4782): query uri: content://htc-mms-customization/mms-ua/ua_string
,V/GetPrviateResource( 4782): GetPrviateResource
D/PMS     (  909): acquireWL(441ffa20): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4759 10111 null
,D/MmsCustomizationProvider( 4782): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/[PluginManager]RegisterService( 1301): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1301): handle notify Blinkfeed plugin client changed
,I/IcingCorporaProvider( 2861): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/Babel   ( 4759): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4759): MmsConfig.loadFromDatabase
,D/PMS     (  909): acquireWL(4253cef0): PARTIAL_WAKE_LOCK  AsyncService 0x1 4116 10160 null
,I/ActivityManager(  909): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  909): acquireWL(42b12598): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(4253cef0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ProviderInstaller( 4759): Installed default security provider GmsCore_OpenSSL
E/Babel   ( 4759): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4759): MmsConfig.loadFromResources
,E/Babel   ( 4759): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4759): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/dalvikvm-heap( 4116): Grow heap (frag case) to 15.201MB for 1821008-byte allocation
,I/dalvikvm-heap( 4116): Grow heap (frag case) to 16.936MB for 1821008-byte allocation
,D/MessageCustFlag( 4782): sense_version=6.0
,D/BTAccessoryUtil( 4782): createReceiver
,W/PackageManager(  909): Unable to load service info ResolveInfo{43307490 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  909): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  909): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  909): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  909): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  909): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  909): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  909): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  909): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  909): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  909): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  909): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  909): 	at dalvik.system.NativeStart.main(Native Method)
,D/PMS     (  909): releaseWL(42b12598): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/BTAccessoryUtil( 4782): registerReceiver return intent = null
D/MessageCustFlag( 4782): sku_id=99
,W/SystemReader( 4782): Cannot find message_ambs_application_id, use default value instead
D/PMS     (  909): releaseWL(441ffa20): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
I/ActivityManager(  909): Resuming delayed broadcast
,D/Messaging( 4782): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4782): networkCode: 
D/MessageCustFlag( 4782): sku_id=99
D/MmsConfig( 4782): SIE smsPri: null
,D/MmsConfig( 4782): networkCode: 
D/HtcTelephonyCapability( 4782): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4782): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4782): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4782): Cannot find qct_8960_interface, use default value instead
,D/PMS     (  909): acquireWL(44311a38): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/Process (  909): killProcessQuiet, pid=4386
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  909): Killing 4386:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 4386
,D/PackageBroadcastService( 2187): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2187): Null package name or gms related package.  Ignoreing.
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/ActivityManager(  909): Resuming delayed broadcast
,I/Icing   ( 2187): updateResources: need to parse f{com.google.android.gms}
,D/RemoteDisplayProvider(  909): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  909): start
,I/GCoreNlp( 1229): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  909): applying state to connected service
,D/CaptivePortalTracker(  909): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  909): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
,D/LocationProviderProxy(  909): applying state to connected service
D/ConnectivityService(  909): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/PMS     (  909): acquireWL(4254ae30): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1229 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(4254ae30): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): acquireWL(4245b118): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1229 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(4245b118): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): acquireWL(423e8458): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1229 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(423e8458): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2861): UpdateCorporaTask done [took 678 ms] updated apps [took 678 ms] 
,D/Process (  909): killProcessQuiet, pid=3964
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3964:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3964
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1275): loadItems() com.htc.launcher.pageview.WidgetManager@41b0dc70 +
,I/Prism.WidgetManager( 1275): onLoadItems() +
,I/Icing   ( 2187): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2187): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  909): releaseWL(44311a38): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1275): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1275): onLoadItems() -
,I/Prism.ItemManager( 1275): loadItems() com.htc.launcher.pageview.WidgetManager@41b0dc70 -
,D/PhoneApp( 1243): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1243): -- N1 =0
,D/PhoneApp( 1243): -- N2 =0
,D/PhoneApp( 1243): -- N3 =0
,D/Messaging( 4782): mNeedToUpdateDate2 start
,D/MmsConfig( 4782): packageName: com.htc.vvm.att does not exist
D/ReportIndicatorCache( 4782): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4782): 
D/MmsAsyncWorkHandler( 4782): HM tk = 20001
D/ReportIndicatorCache( 4782): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4782): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41a8b608
,I/Messaging( 4782): mccmnc> ,
D/DraftCache( 4782): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4782): [DraftCache/1] refresh
,D/MmsConfig( 4782): networkCode: 
,D/Messaging( 4782): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/MmsSmsV2Provider( 1243):  phoneType = -1
,D/MmsSmsV2Provider( 1243): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/PhoneStorageUtil( 4782): HtcWrapEnvironment.getSupportedStorages() >1
,D/PhoneStorageUtil( 4782): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4782): createReceiver
,D/MessageCustFlag( 4782): sense_version=6.0
D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
,D/Jerry   ( 4782): start to preload cursor >>>>>>>
,D/AccFlag ( 1243): sku_id=99
,D/TelephUtils( 1243): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
V/MmsProvider( 1243): Update uri=content://mms, match=0
,V/MmsProvider( 1243): selection=st=129 AND m_type!=134
,D/Messaging( 4782): Reset downloading state: 0
D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
V/MmsSystemEventReceiver( 4782): TransactionService is going to be woken up.
D/MmsSmsV2Provider( 1243):  phoneType = -1
D/MmsSmsV2Provider( 1243): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/DraftCache( 4782): [DraftCache/475] rebuildCache
,V/TransactionService( 4782): 1-Creating TransactionService
V/TransactionService( 4782): onStartCommand: 1
,D/MmsSystemEventReceiver( 4782): unRegisterForConnectionStateChanges
V/TransactionService( 4782): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4782): Loading previous transactions.
,D/Messaging( 4782): mNeedToUpdateDate2: false
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 72
,D/MmsSmsV2Provider( 1243):  phoneType = -1
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1243): device_type: 1
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/MmsSmsV2Provider( 1243):  phoneType = -1
,D/MmsSmsV2Provider( 1243): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/TransactionService( 4782): Force set service start id to 1
,V/TransactionService( 4782): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/Messaging( 4782): ViewCache CreatePreload
D/Messaging( 4782): ViewCache CreatePreloadOnlyMultipleOpsList
,D/MmsSystemEventReceiver( 4782): unRegisterForConnectionStateChanges
,D/TransactionService( 4782): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4782): Destroying TransactionService
,D/Cust_MMSMS( 4782): _has_set_default_values_2=true
,V/TransactionService( 4782): 4-Handling incoming message: { when=-5ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/Jerry   ( 1243): URI_DRAFT
,D/MsgPreferenceUtils( 4782): def_index: 0
,D/DraftCache( 4782): hasDraft() = false mNeedNotifyChange = true
,D/MsgPreferenceUtils( 4782): globalIndex = 1
D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
D/MmsSmsV2Provider( 1243):  phoneType = -1
,D/MmsSmsV2Provider( 1243): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/DraftCache( 4782): [DraftCache/475] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4782): 
D/MmsAsyncWorkHandler( 4782): HM tk = 20002
D/MsgPreferenceUtils( 4782): phone state: true
D/MsgPreferenceUtils( 4782): sd state: false
,D/MsgPreferenceUtils( 4782): vIndex = 0
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1243): sku_id=99
,D/Messaging( 4782): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1243): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1243): sku_id=99
,D/PMS     (  909): acquireWL(425f1388): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41a77070: PendingIntentRecord{41e97c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=119866, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(425f1388): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/GAV4    ( 4759): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  909): acquireWL(423b1268): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  909): sending alarm PendingIntent{43817330: PendingIntentRecord{424d0110 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=122504, Int=0
,D/PMS     (  909): acquireWL(42310378): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(423b1268): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=20 [10][2][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/PMS     (  909): acquireWL(423b0fc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(423b0fc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(42310378): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(4226c020): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023601
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023766
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023838
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023842
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023896
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023899
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025230
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025256
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028285
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029157
,D/PMS     (  909): releaseWL(4226c020): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(42537388): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023601
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023766
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023838
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023842
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023896
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023899
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025230
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025256
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028285
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029157
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,D/PMS     (  909): acquireWL(442c3798): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  909): acquireWL(425ef3b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1229): Vacuum at: now=1452883502848 tag=VacuumService
D/PMS     (  909): releaseWL(42537388): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(442c3798): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(43aeb198): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023601
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023766
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023838
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023842
,D/PMS     (  909): releaseWL(425ef3b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023896
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023899
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025230
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025256
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028285
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029157
,D/PMS     (  909): releaseWL(43aeb198): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(432ba358): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023601
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023766
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023838
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023842
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023896
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023899
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025230
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025256
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028285
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029157
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/PMS     (  909): releaseWL(432ba358): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): acquireWL(43065788): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023601
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023766
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023838
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023842
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023896
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023899
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025230
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025256
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028285
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029157
,D/PMS     (  909): releaseWL(43065788): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(435d07b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023601
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023766
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023838
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023842
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023896
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023899
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025230
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025256
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028285
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029157
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): releaseWL(435d07b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): acquireWL(423af778): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023601
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023766
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023838
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023842
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023896
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023899
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025230
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025256
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028285
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029157
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,D/PMS     (  909): acquireWL(43c77050): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(43c77050): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(4234fa98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(423af778): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(425ea860): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023601
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023766
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023838
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023842
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023896
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023899
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025230
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025256
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028285
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029157
,D/PMS     (  909): releaseWL(425ea860): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1229/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1229/10029)
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1229): Scheduling Phenotype for one-off execution 8246 seconds from now (1452883503416)
,D/GetConfigurationSnapshotOperation( 1229): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1229): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1229): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1229): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1229): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1229): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1229): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  909): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1229/10029)
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1229/10029),
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,D/libc    ( 1229): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1229): [NET] getaddrinfo-,err=8
,D/libc    ( 1229): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1229): [NET] getaddrinfo-, 1
,D/libc    ( 1229): [NET] getaddrinfo_proxy+
,D/libc    (  362): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =ce67 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 252
D/libc    (  362): [NET]res_nsend:resplen=87
D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1229): [NET] getaddrinfo_proxy-, success,
,D/libc    ( 1229): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1229): [NET] getaddrinfo-,err=8
D/libc    ( 1229): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1229): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  909): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1229/10029)
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=9 [11][1][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1229/10029)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,D/PMS     (  909): releaseWL(4234fa98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(438511f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023601
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023766
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023838
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023842
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023896
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023899
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025230
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025256
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028285
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029157
,D/PMS     (  909): releaseWL(438511f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(4249dc70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1169): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023601
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023766
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023838
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023842
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023896
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023899
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025230
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025256
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028285
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029157
,D/PMS     (  909): releaseWL(4249dc70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(43958d68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
I/BatteryService(  909): n_update end
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): releaseWL(43958d68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  909): acquireWL(4321cc28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  909): sending alarm PendingIntent{431432d0: PendingIntentRecord{4261de38 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=135042, Int=0
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
,D/PMS     (  909): releaseWL(4321cc28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1301): service - mHandler: update timezone
,D/AutoSetting( 1301): service - handleMessage() stop self
,D/AutoSetting( 1512): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  909): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1301): service - handleMessage() quit looper
,D/AutoSetting( 1512): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker,
,D/AutoSetting( 1512): service - onCreate()
,D/AutoSetting( 1301): service - onDestroy() END
W/ActivityManager(  909): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1512): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1512): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
V/NotificationService(  909): batLight: Full, plugged
V/LightsService(  909): setLight #8: color=#c8c800
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  909): setLight #8: color=#c800
D/qdlights(  909): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/DotMatrix( 1562): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
D/DotMatrix( 1562): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1512): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1512): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1512): service - mHandler: update timezone
,D/AutoSetting( 1512): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1512): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1512): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1512): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1562): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1562): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/PhoneStatusBar( 1120): removeNotification.gc:53
,I/RemoteViews( 1120): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1120): release indeterminate drawable android.widget.OnDemandProgressBar{41dc09c8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1120): com.htc.htclocationservice 2 6 2 11
,D/PMS     (  909): acquireWL(442ce968): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{423dd020: PendingIntentRecord{42573f80 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141284, Int=0
,D/GpsLocationProvider(  909): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  909): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  909): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  909): acquireWL(43563220): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 909 1000 null
D/PMS     (  909): releaseWL(442ce968): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  909): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-,err=8
D/libc    (  909): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  909): [NET] getaddrinfo-, 1
,D/libc    (  909): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =61da +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  362): [NET]res_nsend:resplen=238
D/libc    (  362): [NET]res_queryN: exit 3, ancount=10
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  909): [NET] getaddrinfo_proxy-, success
,I/global  (  909): call createSocket() return a new socket.
D/libc    (  909): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  909): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  909): [reportHTCStatus] eventMask = 3 , status = 0
D/GpsLocationProvider(  909): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  909):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  909): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED,
,D/Process (  909): killProcessQuiet, pid=4418
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4418:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 4418
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  909): releaseWL(43563220): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1243): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  909): Waited long enough for: ServiceRecord{4354d558 u0 com.htc.htclocationservice/.AutoSettingService},
,D/PMS     (  909): acquireWL(42c8fe68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42c8fe68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 1512): service - handleMessage() stop self
,D/AutoSetting( 1512): service - onDestroy() END
,D/AutoSetting( 1512): service - handleMessage() quit looper
,D/Process (  909): killProcessQuiet, pid=4433
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4433:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 4433
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  909): acquireWL(431ad900): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10027}
,V/AlarmManager(  909): sending alarm PendingIntent{436abf80: PendingIntentRecord{43dd0fa8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=173390, Int=0
,D/PMS     (  909): releaseWL(431ad900): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,I/ClearcutLoggerApiImpl( 1367): disconnect managed GoogleApiClient
,D/TelephonyReceiver( 1243): switchBindHtcMsgCursor: null
,D/PMS     (  909): acquireWL(4249f118): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41a77070: PendingIntentRecord{41e97c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=179866, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4249f118): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(437f4628): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  909): releaseWL(437f4628): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HtcPowerSaver(  909): updateBatteryInfo
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  909): acquireWL(435d90e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(435d90e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  909): acquireWL(4320f618): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41a77070: PendingIntentRecord{41e97c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=239866, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4320f618): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  909): acquireWL(441f44b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/PMS     (  909): releaseWL(441f44b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
,D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PMS     (  909): runPSCheck
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  909): acquireWL(43ae46f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41a77070: PendingIntentRecord{41e97c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=299866, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43ae46f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  909): acquireWL(43286e98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43286e98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Process (  909): killProcessQuiet, pid=4081
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4081:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 4081
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0,
,D/PMS     (  909): acquireWL(442f9d80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(442f9d80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
,D/PowerUI ( 1120): closing low battery warning: level=100
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  909): acquireWL(442809d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41a77070: PendingIntentRecord{41e97c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=359866, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(442809d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(437c82e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
,I/BatteryService(  909): n_update end
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PMS     (  909): releaseWL(437c82e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  909): acquireWL(4366e680): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(4366e680): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  909): acquireWL(42ab8718): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41a77070: PendingIntentRecord{41e97c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=419866, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42ab8718): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(423f65a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(423f65a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1120): closing low battery warning: level=100
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  909): acquireWL(44299048): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41a77070: PendingIntentRecord{41e97c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=479866, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(44299048): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(44291cc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,I/BatteryService(  909): n_update end
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(44291cc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
,I/HtcPowerSaver(  909): >> updateStatus
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  909): acquireWL(434f3bf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(434f3bf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
,D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,D/PowerUI ( 1120): closing low battery warning: level=100
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  909): acquireWL(41a71a68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41a77070: PendingIntentRecord{41e97c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=539866, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(41a71a68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43b25188): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43b25188): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(4316bc08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(4316bc08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
,D/PowerUI ( 1120): closing low battery warning: level=100
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(442a7c68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41a77070: PendingIntentRecord{41e97c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=599866, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(442a7c68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(4331eae8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(4331eae8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  355): inotify_add_watch failed. (No such file or directory),
,D/ContactMessageStore( 1243): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1243): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1243): sku_id=99
,D/ContactMessageStore( 1243): start background delete task...
,D/ContactMessageStore( 1243): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1243): size: 0 , 0
,D/ContactMessageStore( 1243): Background delete complete
,D/PMS     (  909): acquireWL(42c50c40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PMS     (  909): releaseWL(42c50c40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(4252e438): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41a77070: PendingIntentRecord{41e97c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=659866, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4252e438): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(436a05d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
D/UsbnetService(  909): BroadcastReceiver::onReceive+
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(436a05d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck,
D/HtcPowerSaver(  909): Checking...
,I/HtcPowerSaver(  909): >> updateStatus
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(42ff3420): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41a77070: PendingIntentRecord{41e97c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=719866, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42ff3420): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43cf8e30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43cf8e30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(42c31758): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41a77070: PendingIntentRecord{41e97c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=779867, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42c31758): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42639bb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(42639bb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(435066c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
,D/PMS     (  909): releaseWL(435066c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(42bfab88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41a77070: PendingIntentRecord{41e97c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=839866, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1275): Grow heap (frag case) to 12.665MB for 50416-byte allocation
,D/PMS     (  909): releaseWL(42bfab88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(431c3400): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PowerUI ( 1120): closing low battery warning: level=100,
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): releaseWL(431c3400): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(4382c280): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41a77070: PendingIntentRecord{41e97c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=899866, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4382c280): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43e1d3f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43e1d3f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(431cd2e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(431cd2e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(432bb7b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41a77070: PendingIntentRecord{41e97c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=959867, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(432bb7b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43533bb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43533bb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/ConnectivityService(  909): Sampling interval elapsed, updating statistics ..
,D/PMS     (  909): acquireWL(42460f58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41d01548: PendingIntentRecord{4240ea38 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=782700, Int=0
,D/ConnectivityService(  909): Done.
,D/ConnectivityService(  909): Setting timer for 720seconds
,I/ActivityManager(  909): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4891 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
V/AlarmManager(  909): sending alarm PendingIntent{42238420: PendingIntentRecord{4263c408 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452883590805, Int=10800000
V/AlarmManager(  909): sending alarm PendingIntent{42d2f328: PendingIntentRecord{42501898 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1452883777396, Int=1800000
,V/AlarmManager(  909): sending alarm PendingIntent{4248ce20: PendingIntentRecord{42405590 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452884311386, Int=900000
,V/AlarmManager(  909): sending alarm PendingIntent{42592a40: PendingIntentRecord{425e4650 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1452884386708, Int=0
,D/PMS     (  909): acquireWL(43564ed8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(43dbfe70): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(43564ed8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4681): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4681): call getInstance()
,D/PowerUsageList:PowerUsageHelper( 4681): MY_DEBUG = false
,D/SmartSyncUtils( 4681): isEpsOn(), nState = 0
D/PMS     (  909): acquireWL(431a5d08): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4681 1000 null
,D/PMS     (  909): releaseWL(42460f58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
I/EventLogService( 2187): Aggregate from 1452883486270 (log), 1452881977265 (data)
D/SmartSyncScreenOnOffTimeReceiver( 4681): [updateNmRange] bManual = false
D/SmartSyncScreenOnOffTimeReceiver( 4681): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 4681): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4681): SettingOnTime = 1452924000000, randomSettingOnTime = 1452921900000
D/SmartSyncScreenOnOffTimeReceiver( 4681): SettingOffTime = 1452909600000, randomSettingOffTime = 1452914663000
D/SmartSyncScreenOnOffTimeReceiver( 4681): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4681): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4681): bNightModeTurnOffOnce = false
W/BatSI   (  909): Couldn't get kernel wake lock stats
D/PMS     (  909): releaseWL(431a5d08): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.aurora (4891/10049)
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023601
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023766
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023838
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023842
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023896
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023899
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025230
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025256
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028285
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029157
,D/PMS     (  909): releaseWL(43dbfe70): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023601
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023766
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023838
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023842
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023896
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023899
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025230
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025256
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028285
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029157
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,D/PMS     (  909): acquireWL(425e09f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(425e09f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,D/Process (  909): killProcessQuiet, pid=4465
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4465:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Recipient 4465
,D/PMS     (  909): acquireWL(4235b550): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  909): sending alarm PendingIntent{437ec670: PendingIntentRecord{423c36d8 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1009595, Int=0
,D/PMS     (  909): acquireWL(42267940): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(42267940): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(4235b550): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(42519c60): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
,D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1367/10029)
D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  909): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023601
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023766
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023838
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023842
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023896
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023899
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025230
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025256
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028285
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029157
,D/PMS     (  909): releaseWL(42519c60): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  909): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=13 [121][16][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1169): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1169): nl80211: survey data missing!
E/wpa_supplicant( 1169): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1169): environment dirty rate=0 [0][0][0]
,D/PMS     (  909): acquireWL(431af8f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41a77070: PendingIntentRecord{41e97c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1019866, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(431af8f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43db0918): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(43db0918): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(423ef8c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(423ef8c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(437fd870): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41a77070: PendingIntentRecord{41e97c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1079866, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(437fd870): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43cac8e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(43cac8e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(430e1320): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(430e1320): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(425ebfe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41a77070: PendingIntentRecord{41e97c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1139866, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(425ebfe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(423da7e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
,D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(423da7e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43292c78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41a77070: PendingIntentRecord{41e97c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1199866, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43292c78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(4237a238): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1120): closing low battery warning: level=100
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(4237a238): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  355): inotify_add_watch failed. (No such file or directory),
,D/PMS     (  909): acquireWL(435a22d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41a77070: PendingIntentRecord{41e97c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1259866, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1275): Grow heap (frag case) to 12.711MB for 50416-byte allocation
,D/PMS     (  909): releaseWL(435a22d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42642718): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PMS     (  909): releaseWL(42642718): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43822a10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43822a10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(432052e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41a77070: PendingIntentRecord{41e97c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1319866, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(432052e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(424dd5f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PMS     (  909): releaseWL(424dd5f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(426064f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(426064f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(43c33f08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41a77070: PendingIntentRecord{41e97c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1379866, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false),
,D/PMS     (  909): releaseWL(43c33f08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43367488): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(43367488): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(44296940): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(44296940): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
,I/HtcPowerSaver(  909): >> updateStatus
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43da6e98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41a77070: PendingIntentRecord{41e97c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1439866, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43da6e98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(431a5df8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(431a5df8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(423aa440): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(423aa440): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43798f50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41a77070: PendingIntentRecord{41e97c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1499866, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43798f50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(44303058): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/PMS     (  909): releaseWL(44303058): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(44264840): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(44264840): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43151708): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41a77070: PendingIntentRecord{41e97c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1559867, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43151708): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(4314fed0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(4314fed0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(4314cd50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41a77070: PendingIntentRecord{41e97c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1619866, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4314cd50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(4240e4d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/PMS     (  909): releaseWL(4240e4d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(425c5190): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(425c5190): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PMS     (  909): runPSCheck
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): Checking...
,I/HtcPowerSaver(  909): >> updateStatus
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(437bf5d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41a77070: PendingIntentRecord{41e97c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1679866, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(437bf5d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(434d5dc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(434d5dc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(442f94d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(442f94d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1120): closing low battery warning: level=100
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): >> updateStatus
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(437f5b48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41a77070: PendingIntentRecord{41e97c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1739866, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(437f5b48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(432a7d30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
I/BatteryService(  909): n_update end
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PMS     (  909): releaseWL(432a7d30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(44202500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
I/BatteryService(  909): n_update end
D/PMS     (  909): releaseWL(44202500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1120): closing low battery warning: level=100
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(441dfe88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41a77070: PendingIntentRecord{41e97c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1799866, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(441dfe88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,D/PMS     (  909): acquireWL(43d52008): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43d52008): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  909): updateBatteryInfo
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  355): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  909): acquireWL(437c5790): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PMS     (  909): releaseWL(437c5790): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
I/ProcessStatsService(  909): Prepared write state in 43ms
,I/ProcessStatsService(  909): Pruning old procstats: /data/system/procstats/state-2016-01-15-04-28-38.bin
,D/PMS     (  909): acquireWL(4341db90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41a77070: PendingIntentRecord{41e97c40 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1859866, Int=0
,I/IntentController( 1120): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1275): Grow heap (frag case) to 12.760MB for 50416-byte allocation
,D/PMS     (  909): releaseWL(4341db90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(442bbd08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(442bbd08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1120): closing low battery warning: level=100
D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4940): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4940): ====startRecUseTime====
D/htc.customization.log.level( 4940):  is 
W/CustomizationLogLevel( 4940): Level value is invalid, use default level 2
D/CustomizationManager( 4940):  Read ACC file spent 0.105 (s)
D/CIDMapFileReader( 4940): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4940): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4940): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4940): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4940): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4940): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4940): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4940): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4940): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4940): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4940): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4940): Parsing tag category name = system
I/CustomizationCIDLoader( 4940): Parsing tag category name = application
I/CustomizationCIDLoader( 4940): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4940): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4940): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4940): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4940): Parsing tag category name = Settings
D/CustomizationManager( 4940):  Read CID file spent 0.157 (s)
D/CustomizationManager( 4940):  All configurations done spent 0.157 (s)
W/HtcNativeFlag( 4940): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4940): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4940): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4940): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  909): deletePackageAsUser: pkg=com.test.thalitest, pid=4940, uid=2000 user=0
I/ActivityManager(  909): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  909): killProcessQuiet, pid=4629
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  909): killProcessQuiet, pid=4599
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  909): Killing 4629:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1803s
I/ActivityManager(  909): Killing 4599:com.android.chrome/u0a96 (adj 15): empty for 1803s
I/ActivityManager(  909): Killing 4581:com.google.android.setupwizard/u0a79 (adj 15): empty for 1803s
D/Process (  909): killProcessQuiet, pid=4581
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  909): killProcessQuiet, pid=3901
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  909): Killing 3901:com.google.android.music:main/u0a154 (adj 15): empty for 1803s
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Recipient 4599
I/ActivityManager(  909): Recipient 4581
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/asset   (  909): Copying FileAsset 0x6cf796a8 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
W/PackageSettings(  909): Skipping PackageSetting{42158ca0 com.example.hello/10397} due to missing metadata
I/ActivityManager(  909): Recipient 4629
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/ActivityManager(  909): Recipient 3901
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  909): Client com.google.android.music (pid 3901): Died!
I/HtcKeyguardAppUpdateMonitor( 1120): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1562): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1562): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1562): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/BroadcastQueue(  909): Failure sending broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
W/BroadcastQueue(  909): android.os.DeadObjectException
W/BroadcastQueue(  909): 	at android.os.BinderProxy.transact(Native Method)
W/BroadcastQueue(  909): 	at android.content.IIntentReceiver$Stub$Proxy.performReceive(IIntentReceiver.java:124)
W/BroadcastQueue(  909): 	at com.android.server.am.BroadcastQueue.performReceiveLocked(BroadcastQueue.java:457)
W/BroadcastQueue(  909): 	at com.android.server.am.BroadcastQueue.deliverToRegisteredReceiverLocked(BroadcastQueue.java:564)
W/BroadcastQueue(  909): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:636)
W/BroadcastQueue(  909): 	at com.android.server.am.BroadcastQueue$1.handleMessage(BroadcastQueue.java:147)
W/BroadcastQueue(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/BroadcastQueue(  909): 	at android.os.Looper.loop(Looper.java:157)
W/BroadcastQueue(  909): 	at com.android.server.am.ActivityManagerService$AThread.run(ActivityManagerService.java:2098)
I/HtcKeyguardAppUpdateMonitor( 1120): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1120): ApplicationsIntentReceiver replacing:false
W/GeofencerStateMachine( 1229): Ignoring removeGeofence because network location is disabled.
D/AccTypeManager( 1343): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  909): acquireWL(435e4470): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1229 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(435e4470): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/VoicemailCleanupService( 1320): Cleaning up data for package: com.test.thalitest
W/SystemReader( 1257): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
W/SQLiteConnectionPool( 2187): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "sms"
I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "smsto"
I/Launcher( 1275): Deferring update until onResume
D/Launcher( 1275): waitUntilResume // bindAppsRemoved
I/[PluginManager]RegisterService( 1301): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/[PluginManager]RegisterService( 1301): handle notify Blinkfeed plugin client changed
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mms"
W/AccTypeManager( 1343): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1343): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/Prism.PackageStateRece_( 1275): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "sms"
I/IcingCorporaProvider( 2861): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/InputMethodManagerService(  909): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "smsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
E/ExternalAccountType( 1343): Unsupported attribute readOnly
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
I/ActivityManager(  909): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4954 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1243 :
D/PhoneApp( 1243): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  909): acquireWL(437e6860): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2861): UpdateCorporaTask done [took 357 ms] updated apps [took 356 ms] 
W/FileUtils( 4954): Failed to chmod(/data/data/com.google.android.apps.docs/databases/DocList.db): libcore.io.ErrnoException: chmod failed: EROFS (Read-only file system)
E/SQLiteDatabase( 4954): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4954): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4954): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4954): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4954): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4954): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4954): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4954): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4954): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4954): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4954): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4954): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4954): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4954): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4954): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4954): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4954): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4954): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4954): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4954): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4954): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4954): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4954): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4954): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4954): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4954): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4954): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4954): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4954): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4954): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4954): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4954): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4954): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4954): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4954): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4954): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4954): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4954): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4954): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4954): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4954): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4954): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4954): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4954): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4954): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4954): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4954): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4954): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4954): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4954): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4954): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4954): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4954): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4954): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4954): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4954): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4954): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4954): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4954): Opened ClientFlag.db in read-only mode
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.docs (4954/10100)
I/ActivityManager(  909): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4976 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.docs (4954/10100)
W/GAV2    ( 4954): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ContextImpl( 4976): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  909): Delay finish: com.android.keychain/.KeyChainBroadcastReceiver
E/SQLiteDatabase( 4976): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4976): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4976): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4976): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4976): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4976): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4976): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4976): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4976): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4976): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4976): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4976): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4976): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4976): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4976): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4976): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4976): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4976): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4976): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4976): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4976): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4976): threadid=10: thread exiting with uncaught exception (group=0x4164ae30)
E/AndroidRuntime( 4976): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4976): Process: com.android.keychain, PID: 4976
E/AndroidRuntime( 4976): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4976): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4976): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4976): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4976): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4976): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4976): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4976): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4976): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4976): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4976): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4976): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4976): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4976): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4976): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4976): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4976): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4976): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4976): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4976): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  909): App crashed! Process: com.android.keychain
D/ErrorReport(  909): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4976): killProcess, pid=4976
D/Process ( 4976): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  909): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  909): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452885291995.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  909): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  909): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  909): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  909): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  909): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  909): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  909): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  909): 	... 4 more
I/ActivityManager(  909): Recipient 4976
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Process com.android.keychain (pid 4976) has died.
W/ActivityManager(  909): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4995 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
W/GAV2    ( 4954): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
D/AppTag  ( 4995): getInstance(Context context)
D/AppTag  ( 4995): getInstance(Context context)
D/AppTag  ( 4995): onCreate()
D/PMS     (  909): acquireWL(437f6388): PARTIAL_WAKE_LOCK  AsyncService 0x1 4116 10160 null
D/PMS     (  909): releaseWL(437f6388): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/dalvikvm( 4143): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 2187): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2187): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 2187): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2187): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 2187): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2187): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 2187): Removing dialog suppression flag for package com.test.thalitest
I/ActivityManager(  909): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
E/SQLiteLog( 2187): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 2187): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2187): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x6613d650
E/SQLiteDBG( 2187): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6dff8900
W/dalvikvm( 2187): threadid=48: thread exiting with uncaught exception (group=0x4164ae30)
E/DriveAsyncService( 2187): disk I/O error (code 3850)
E/DriveAsyncService( 2187): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2187): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2187): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2187): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2187): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2187): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2187): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2187): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2187): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2187): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2187): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2187): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2187): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2187): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2187): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2187): 	at java.lang.Thread.run(Thread.java:864)
E/AndroidRuntime( 2187): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2187): Process: com.google.android.gms, PID: 2187
E/AndroidRuntime( 2187): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2187): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2187): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2187): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2187): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2187): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2187): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2187): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2187): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2187): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2187): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2187): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2187): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2187): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2187): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2187): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2187): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2187): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2187): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteDatabase( 2187): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 2187): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2187): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2187): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2187): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2187): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2187): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2187): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2187): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2187): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2187): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2187): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2187): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2187): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2187): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2187): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2187): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 2187): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2187): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2187): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2187): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 2187): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 2187): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2187): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2187): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2187): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2187): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2187): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2187): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2187): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2187): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2187): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2187): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2187): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2187): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2187): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2187): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 2187): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 2187): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 2187): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 2187): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2187): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2187): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2187): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  909): App crashed! Process: com.google.android.gms
E/PhenotypeInitializer( 2187): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 2187): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 2187): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 2187): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/PhenotypeInitializer( 2187): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/PhenotypeInitializer( 2187): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 2187): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 2187): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 2187): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/PhenotypeInitializer( 2187): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/PhenotypeInitializer( 2187): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/PhenotypeInitializer( 2187): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/PhenotypeInitializer( 2187): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2187): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2187): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 2187): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 2187): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 2187): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 2187): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 2187): 	at android.os.Looper.loop(Looper.java:157)
E/PhenotypeInitializer( 2187): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 2187): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 2187): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 2187): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 2187): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 2187): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 2187): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 2187): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 2187): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 2187): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 2187): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 2187): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 2187): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 2187): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 2187): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 2187): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 2187): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 2187): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 2187): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 2187): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 2187): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 2187): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 2187): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 2187): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 2187): killProcess, pid=2187
D/Process ( 2187): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/Prism.ItemManager( 1275): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1275): loadItems() com.htc.launcher.pageview.WidgetManager@41b0dc70 +
I/Prism.WidgetManager( 1275): onLoadItems() +
E/DropBoxManagerService(  909): Can't write: system_app_crash
E/DropBoxManagerService(  909): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  909): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  909): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  909): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  909): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  909): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  909): 	... 5 more
I/ActivityManager(  909): Recipient 2187
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Process com.google.android.gms (pid 2187) has died.
D/PMS     (  909): handleWLDeath(437e6860): PARTIAL_WAKE_LOCK  Icing 0x1
D/WifiService(  909): Client connection lost with reason: 4
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 10999ms
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 20999ms
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 20998ms
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20998ms
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20997ms
I/ActivityManager(  909): Resuming delayed broadcast
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20990ms
E/SQLiteLog( 1367): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1367): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x63fa1950
W/dalvikvm( 1367): threadid=1: thread exiting with uncaught exception (group=0x4164ae30)
E/AndroidRuntime( 1367): FATAL EXCEPTION: main
E/AndroidRuntime( 1367): Process: com.google.process.gapps, PID: 1367
E/AndroidRuntime( 1367): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1367): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1367): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1367): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1367): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1367): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1367): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1367): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1367): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1367): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1367): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1367): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1367): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1367): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1367): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1367): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1367): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1367): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1367): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1367): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1367): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1367): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1367): 	... 10 more
E/ActivityManager(  909): App crashed! Process: com.google.process.gapps
E/DropBoxManagerService(  909): Can't write: system_app_crash
E/DropBoxManagerService(  909): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  909): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  909): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  909): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  909): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  909): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  909): 	... 5 more
D/Process ( 1367): killProcess, pid=1367
W/PackageManager(  909): Unable to load service info ResolveInfo{433432c8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  909): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  909): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  909): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  909): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  909): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  909): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  909): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  909): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  909): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  909): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  909): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  909): 	at dalvik.system.NativeStart.main(Native Method)
I/ActivityManager(  909): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5025 uid=10098 gids={50098, 3003, 5012}
D/Process ( 1367): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 

```
