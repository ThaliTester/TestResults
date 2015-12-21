#### Test 54312298c831015_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 19
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 38
D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1186): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  909):    returned true
--------- beginning of /dev/log/system
V/LightsService(  909): setLight #0: color=#26
V/LightsService(  909): setLight #0: color=#23
V/LightsService(  909): setLight #0: color=#1c
V/LightsService(  909): setLight #0: color=#15
V/LightsService(  909): setLight #0: color=#14
E/cutils-trace( 4611): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4611): ====startRecUseTime====
D/htc.customization.log.level( 4611):  is 
W/CustomizationLogLevel( 4611): Level value is invalid, use default level 2
D/CustomizationManager( 4611):  Read ACC file spent 0.056 (s)
D/CIDMapFileReader( 4611): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4611): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4611): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4611): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4611): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4611): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4611): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4611): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4611): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4611): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4611): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4611): Parsing tag category name = system
I/CustomizationCIDLoader( 4611): Parsing tag category name = application
I/CustomizationCIDLoader( 4611): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4611): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4611): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4611): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4611): Parsing tag category name = Settings
D/CustomizationManager( 4611):  Read CID file spent 0.096 (s)
D/CustomizationManager( 4611):  All configurations done spent 0.096 (s)
W/HtcNativeFlag( 4611): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4611): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4611): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4611): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  909): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  909): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  909): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  909): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  909): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  909): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  909): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4611
D/PMS     (  909): acquireHCC(420fa960): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 909 1000 null
D/PMS     (  909): acquireHCC(42039618): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 909 1000 null
W/asset   (  909): Copying FileAsset 0x62aff8c8 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  909): @test_code: getHtcIntentFlag: 0 obj: 1115878312
I/FeedHostManager( 1273): [onPause]
I/FeedProviderManager( 1273): onPause
I/FeedHostManager( 1273): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41df5560
I/SocialFeedProvider( 1273): +onPause
I/SocialFeedProvider( 1273): -onPause
D/PMS     (  909): acquireWL(42759d38): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 909 1000 null
I/ActivityManager(  909): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4623 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
W/asset   ( 4623): Copying FileAsset 0x5c7ca428 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1273): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 4623): Binding Chromium to main looper Looper (main, tid 1) {41d3c3d8}
I/LibraryLoader( 4623): Expected native library version number "",actual native library version number ""
I/chromium( 4623): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4623): Initializing chromium process, renderers=0
D/PMS     (  909): acquireWL(421f3900): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  909): acquireWL(4202ef30): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  909): java.lang.Throwable: stack dump
D/BluetoothManagerService(  909): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@428992d8:true
W/System.err(  909): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  909): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  909): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  909): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  909): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4623): 1104485904: getState(). Returning 12
D/PMS     (  909): releaseWL(421f3900): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4623): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4623): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4623): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4623): Local Branch: 
I/Adreno-EGL( 4623): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4623): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4623):                  aa63bbd948f41d15fc72f585e
W/chromium( 4623): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4623): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4623): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4623): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4623): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4623): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4623): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4623): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4623): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4623): CordovaWebView is running on device made by: HTC
,W/AwContents( 4623): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  909): Disable input method client, pid=1273
,W/ResourceType( 4623): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4623): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41d834c0, mServedView=org.apache.cordova.engine.SystemWebView{41d49128 VFEDH.C. .F....I. 0,0-720,1134 #64}
,W/AwContents( 4623): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  909): Displayed com.test.thalitest/.MainActivity: +298ms
W/XT9_C   ( 1208): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1208): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  909): Enable input method client, pid=4623
D/PMS     (  909): releaseWL(42759d38): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/JsMessageQueue( 4623): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4623): JniHelper::setJavaVM(0x418f5010), pthread_self() = 1662762816
,D/JX-Cordova( 4623): jxcore cordova android initializing
,I/dalvikvm-heap( 4623): Grow heap (frag case) to 11.549MB for 96598-byte allocation
,I/dalvikvm-heap( 4623): Grow heap (frag case) to 11.632MB for 144892-byte allocation
,I/dalvikvm-heap( 4623): Grow heap (frag case) to 11.753MB for 217334-byte allocation
,I/dalvikvm-heap( 4623): Grow heap (frag case) to 11.926MB for 325996-byte allocation
,I/dalvikvm-heap( 4623): Grow heap (frag case) to 12.184MB for 488990-byte allocation
,I/dalvikvm-heap( 4623): Grow heap (frag case) to 13.174MB for 1100216-byte allocation
,I/dalvikvm-heap( 4623): Grow heap (frag case) to 14.037MB for 1650320-byte allocation
,I/dalvikvm-heap( 4623): Grow heap (frag case) to 15.435MB for 2475476-byte allocation
,W/CpuWake (  909): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  909): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  909): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  909): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  909): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  909): <<release mCpuPerf_Freq wakelock
,D/PMS     (  909): releaseHCC(420fa960): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  909): releaseHCC(42039618): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4623): Grow heap (frag case) to 17.493MB for 3713210-byte allocation
,W/jxcore-log( 4623): Initializing JXcore engine
,W/jxcore-log( 4623): JXcore engine is ready
,W/jxcore-log( 4623): Starting JXcore engine
,W/jxcore-log( 4623): Platform android
W/jxcore-log( 4623): 
,W/jxcore-log( 4623): Process ARCH arm
W/jxcore-log( 4623): 
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 19
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 57
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1186): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,I/jxcore-log( 4623): JXcore Cordova bridge is ready!
I/jxcore-log( 4623): 
,W/jxcore-log( 4623): JXcore engine is started
,I/chromium( 4623): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PMS     (  909): releaseWL(4202ef30): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/SensorManager(  909): mEventCount = 1050
,I/jxcore-log( 4623): Toggling radios to true
I/jxcore-log( 4623): 
,D/BluetoothAdapter( 4623): enable(): BT is already enabled..!
,D/WifiManager( 4623): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
W/HtcDLNAServiceManager(  909): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  909): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  909): Settings:Agentvalue: 2
W/Settings:Agent(  909): >> traceCallingStack()
W/Settings:Agent(  909): Process.myPid(): 909
W/Settings:Agent(  909): Process.myTid(): 1221
W/Settings:Agent(  909): Process.myUid(): 1000
W/Settings:Agent(  909): 
W/Settings:Agent(  909): 
,W/System.err(  909): java.lang.Throwable: stack dump
W/System.err(  909): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  909): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  909): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  909): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  909): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  909): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  909): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  909): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  909): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  909): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  909): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  909): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  909): 
W/Settings:Agent(  909): << traceCallingStack(): 1(ms)
D/WifiManager( 4623): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  909): doBoolean: DISCONNECT
D/WifiManager( 4623): reconnect: Base Package Name=com.test.thalitest, uid=10389
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1186): TDLS: Tear down peers
I/wpa_supplicant( 1186): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4623): Radios toggled
I/jxcore-log( 4623): 
D/BluetoothManagerService(  909): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiService(  909): New client listening to asynchronous messages
D/WifiService(  909): setWifiEnabled: true pid=4623, uid=10389
E/WifiService(  909): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  909): isSprintWifiRestricted(): false
I/WifiService(  909): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  909): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
I/jxcore-log( 4623): Got Device Bluetooth address: B4:CE:F6:AB:A4:6A
I/jxcore-log( 4623): 
I/jxcore-log( 4623): Perf Test app loaded loaded
I/jxcore-log( 4623): 
I/jxcore-log( 4623): check test folder
I/jxcore-log( 4623): 
I/jxcore-log( 4623): found test : ./testFindPeers.js
I/jxcore-log( 4623): 
,I/jxcore-log( 4623): found test : ./testSendData.js
I/jxcore-log( 4623): 
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1186): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1186): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1186): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  909): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  909): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  909): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  909): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getFreqFromEventString() 2412
,D/WifiMonitor(  909): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1186): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1186): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1186): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1186): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1186): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1186): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1186): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1186): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1186): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1186): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb7f75bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1186):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1186): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1186): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1186): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1186): netlink: Operstate: linkmode=-1, operstate=5
D/Tethering(  909): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1186): htc_wext_set_TX_TRACKING (0)+
D/Tethering(  909): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1186): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1186): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1186): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1186): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1186): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1186): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1186): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1186): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1186): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1186): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1186): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1186): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1186): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1186): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/Tethering(  909): [isWifi] getHotspotEnabled: false
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1186): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1186): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1186): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1186): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1186): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1186): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1186): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1186): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1186): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1186): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1186): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1186): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1186): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1186): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1186): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1186): RT,M_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1186): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1186): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1186): nl80211: Event message available
D/wpa_supplicant( 1186): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1186): nl80211: Ignore disconnect event triggered during reassociation
D/Tethering(  909): interfaceLinkStateChanged wlan0, false
D/Tethering(  909): interfaceStatusChanged wlan0, false
D/Tethering(  909): [isWifi] getHotspotEnabled: false
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/WifiNative-wlan0(  909):    returned true
D/WifiPerfLock(  909): release()
,D/WifiStateMachine(  909): PerfLock released for exiting ConnectedState
D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1186): Power_Mode_Type mode = 0
I/wpa_supplicant( 1186): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1186): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  909):    returned true
,D/libc    (  909): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  909): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  909): acquireWL(427f9478): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 909 1000 null
D/WifiP2pService(  909): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023757
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024057
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024063
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024065
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024073
,D/DhcpStateMachine(  909): [RunningState] Stop DHCP
D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  909): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  909): doBoolean: RECONNECT
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1186): Fast associate: Old scan results
I/wpa_supplicant( 1186): wpa_supplicant_scan enter
I/wpa_supplicant( 1186): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1186): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1186): wpa_supplicant_trigger_scan +
D/WifiNative-wlan0(  909):    returned true
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1186): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1186): nl80211: Event message available
D/wpa_supplicant( 1186): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiStateMachine(  909): Enter handleNetworkDisconnect
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  909): stopDataStallAlarm: current tag=20013 mDataStallAlarmIntent=PendingIntent{432c6cd8: PendingIntentRecord{42840270 android broadcastIntent}}
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025610
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029133
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023757
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024057
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024063
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024065
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024073
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025610
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029133
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  909): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  909): Provision feature enable=false
,D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1186): Power_Mode_Type mode = 0
I/wpa_supplicant( 1186): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  909):    returned true
D/UsbnetStateTracker(  909): isAvailable+-
D/WISPrService( 3829): >>>>>WISPrService start isConnected = false<<<<<
D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 2
D/UsbnetStateTracker(  909): reconnect
D/UsbnetStateTracker(  909): isAvailable+-
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1186): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  909):    returned true
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  909): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/WifiP2pService(  909): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/MDST    (  909): default: reconnect()
D/MDST    (  909): default: setTeardownRequested(false)
D/MDST    (  909): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  909): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  909): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  909): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiService(  909): New client listening to asynchronous messages
D/WifiStateMachine(  909): Exit handleNetworkDisconnect
D/WISPrService( 3829): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  909): setRSSItoWifiInfo: NetworkDetailedState=SCANNING,
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false),
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,I/jxcore-log( 4623): found test : ./testSendData2.js
I/jxcore-log( 4623): 
W/ConnectivityService(  909): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  909): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  909): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/ConnectivityService(  909): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  909): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  909): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  909): handleConnectivityChange: resetting
,D/ConnectivityService(  909): resetConnections(wlan0, 3)
,V/NativeCrypto( 1358): Read error: ssl=0x66114c60: I/O error during system call, Connection timed out
,E/jxcore  ( 4623): Error!: missing ) after argument list
E/jxcore  ( 4623): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
,I/Choreographer( 4623): Skipped 80 frames!  The application may be doing too much work on its main thread.
D/PMS     (  909): acquireWL(43b7f7e8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,V/NativeCrypto( 1358): SSL shutdown failed: ssl=0x66114c60: I/O error during system call, Broken pipe
D/libc    (  364): [NET] entry_id:3   entry:0xb7fa2108  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb7fa22f0  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb7fa2428  removed 
D/libc    (  364): [NET] entry_id:5   entry:0xb7fa1fd8  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb7fa24f0  removed 
D/libc    (  364): [NET] entry_id:6   entry:0xb7f9df88  removed 
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
,D/WISPrService( 3829): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  909): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,D/WISPrService( 3829): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  909): flush DNS cache for net 1(wlan0)
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023757
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024057
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024063
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024065
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024073
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025610
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029133
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1358/10029)
D/Nat464Xlat(  909): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
D/WirelessDisplayService(  909): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  909): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/Nat464Xlat(  909): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  909): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  909): acquireWL(4284bac0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 909 1000 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
D/ConnectivityService(  909): reportInetCondition for net -1, percentage: 0 by  (1358/10029)
D/ConnectivityService(  909): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
I/chromium( 4623): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/WifiStateMachine(  909): startScan Pid: 909 Uid 1000
D/WifiNative-wlan0(  909): doBoolean: SCAN
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1186): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  909):    returned false
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
D/BatSI   (  909): WIFI scan started for: 650a0300 uid:1000
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1358/10029)
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:2
D/PMS     (  909): releaseWL(4284bac0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  909): releaseWL(43b7f7e8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1358/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1358/10029)
D/ConnectivityService(  909): mActiveDefaultNetwork: -1
D/ConnectivityService(  909): handleInetConditionChange: no active default network - ignore
,V/Tethering(  909): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  909): [AlarmQueuing] connectivity wifi: false
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/CaptivePortalTracker(  909): DelayedCaptiveCheckState
D/CaptivePortalTracker(  909): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/CaptivePortalTracker(  909): NoActiveNetworkState
D/GpsLocationProvider(  909): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  909): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  909): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  909): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
D/PMS     (  909): acquireWL(42deb320): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 909 1000 null
D/PMS     (  909): releaseWL(42deb320): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.backuptransport (1572/10029)
D/Tethering(  909): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,I/ConnectivityHelper( 1273): [onReceive] WIFI(1): DISCONNECTED
V/Tethering(  909): bSetPropertyMultiRAB:false
D/Tethering(  909): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  909): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  909): ipv4Default null
I/Tethering(  909): No IPv4 upstream interface, giving up.
,D/Tethering(  909): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.htc.launcher (1273/10076)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
,I/NetworkMonitor( 4497): type=WIFI subType= reason=null isConnected=false
,D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.google.android.music (4497/10154)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023757
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024057
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024063
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024065
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024073
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025610
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029133
D/ConnectivityService(  909): getActiveNetworkInfo called by  (2710/10021)
,I/ActivityManager(  909): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4675 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4675): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4675): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4675): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4675): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk,
,V/DexLibLoader( 4675): Preparing secondary program dexes.
V/DexLibLoader( 4675): Loaded 4 raw lines of metadata.
V/DexLibLoader( 4675): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4675): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4675): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4675): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4675): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
,V/DexLibLoader( 4675): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4675): Dex already copied
D/OdexVerifier( 4675): Odex verification is skipped.
,V/DexLibLoader( 4675): Creating class loader
,V/DexLibLoader( 4675): Finished creating class loader
V/DexLibLoader( 4675): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4675): Dex already copied
D/OdexVerifier( 4675): Odex verification is skipped.
,V/DexLibLoader( 4675): Creating class loader
,V/DexLibLoader( 4675): Finished creating class loader
V/DexLibLoader( 4675): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4675): Dex already copied
D/OdexVerifier( 4675): Odex verification is skipped.
,V/DexLibLoader( 4675): Creating class loader
,V/DexLibLoader( 4675): Finished creating class loader
V/DexLibLoader( 4675): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4675): Dex already copied
D/OdexVerifier( 4675): Odex verification is skipped.
,V/DexLibLoader( 4675): Creating class loader
,V/DexLibLoader( 4675): Finished creating class loader
,V/DexLibLoader( 4675): Verifying classes from secondary dexes.
,D/DexLibLoader( 4675): DexLibLoader.ensureDexLoaded took 21 ms
,W/dalvikvm( 4675): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4675): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4675): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4675): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4675): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4675): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4675): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4675): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1186): nl80211: Event message available
D/wpa_supplicant( 1186): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1186): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1186): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1186): nl80211: Survey data missing
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1186): Sorted scan results
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1186): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1186): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
D/wpa_supplicant( 1186): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1186): Add randomness: count=5 entropy=0
D/wpa_supplicant( 1186): Add randomness: count=6 entropy=1
D/wpa_supplicant( 1186): Add randomness: count=7 entropy=2
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1186): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1186): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1186): wpa_supplicant_pick_network+
I/wpa_supplicant( 1186): Selecting BSS from priority group 1
I/wpa_supplicant( 1186): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1186): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1186): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1186): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1186):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1186):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1186): Start print parameters
I/wpa_supplicant( 1186): wpa_s->wpa_state is 3
I/wpa_supplicant( 1186): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1186): isConcurrentMode() is 0
I/wpa_supplicant( 1186): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1186): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1186): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1186): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1186): wpa_s->reassociate is 1
I/wpa_supplicant( 1186): wpa_s->is_screen_on 1
I/wpa_supplicant( 1186): wpa_s->ifname wlan0
I/wpa_supplicant( 1186): End print parameters
I/wpa_supplicant( 1186): selected network = 1
D/wpa_supplicant( 1186): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb7f774e8  current_ssid=0x0
D/wpa_supplicant( 1186): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1186): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1186): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1186): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1186): check if in concurrent case
,I/wpa_supplicant( 1186): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,D/wpa_supplicant( 1186): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1186): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1186): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1186): RSN: PMKSA cache search - network_ctx=0xb7f774e8 try_opportunistic=0
D/wpa_supplicant( 1186): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1186): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1186): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1186): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1186): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1186): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1186): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1186): nl80211: Unsubscribe mgmt frames handle 0xb7f76718 (mode change)
,D/wpa_supplicant( 1186): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7f76718
D/wpa_supplicant( 1186): nl80211: Register frame type=0xd0 nl_handle=0xb7f76718
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1186): nl80211: Register frame type=0xd0 nl_handle=0xb7f76718
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1186): nl80211: Register frame type=0xd0 nl_handle=0xb7f76718
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1186): nl80211: Register frame type=0xd0 nl_handle=0xb7f76718
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1186): nl80211: Register frame type=0xd0 nl_handle=0xb7f76718
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1186): nl80211: Register frame type=0xd0 nl_handle=0xb7f76718
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1186): nl80211: Register frame type=0xd0 nl_handle=0xb7f76718
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1186): nl80211: Register frame type=0xd0 nl_handle=0xb7f76718
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1186): nl80211: Register frame type=0xd0 nl_handle=0xb7f76718
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1186): nl80211: Register frame type=0xd0 nl_handle=0xb7f76718
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1186): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1186):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1186):   * freq=2412
D/wpa_supplicant( 1186):   * Auth Type 0
,D/wpa_supplicant( 1186):   * WPA Versions 0x2
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1186): nl80211: Connect request send successfully
D/wpa_supplicant( 1186): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1186): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1186): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1186): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1186): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1186): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1186): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1186): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1186): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 18
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  909): doString: LIST_DONGLES
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING,
W/dalvikvm( 4675): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/WifiNative-wlan0(  909): doString: BSS RANGE=0- MASK=0x21987,
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987",
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1186): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1186): reply (351) for get BSS: id=0
I/wpa_supplicant( 1186): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1186): freq=5220
I/wpa_supplicant( 1186): level=-48
I/wpa_supplicant( 1186): tsf=0000000105131017
I/wpa_supplicant( 1186): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1186): ssid=NG7005g
I/wpa_supplicant( 1186): ====
I/wpa_supplicant( 1186): id=1
I/wpa_supplicant( 1186): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1186): freq=2412
I/wpa_supplicant( 1186): level=-57
I/wpa_supplicant( 1186): tsf=0000000105131034
I/wpa_supplicant( 1186): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1186): ssid=NG700
I/wpa_supplicant( 1186): ====
I/wpa_supplicant( 1186): id=2
I/wpa_supplicant( 1186): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1186): freq=2412
I/wpa_supplicant( 1186): level=-57
,I/wpa_supplicant( 1186): tsf=0000000105131029
I/wpa_supplicant( 1186): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1186): ssid=01ABC
I/wpa_supplicant( 1186): ####
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (3) end of scan result ==
D/WifiManager( 1223): getScanResults enter 
,D/WifiStateMachine(  909): == begin of scan result ==
,D/WifiStateMachine(  909): == (3) end of scan result ==
,D/WirelessDisplayService(  909): getDiscoveryDongleList
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/WifiStateMachine(  909): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 105131017, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 105131034, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 105131029, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  909): add 3 to mScanResults
D/BatSI   (  909): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  909): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,E/FbInjectorInitializer( 4675): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/wpa_supplicant( 1186): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1186): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1186): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 1186): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1186): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1186): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1186): nl80211: if_removed already cleared - ignore event
D/Tethering(  909): interfaceLinkStateChanged wlan0, false
,D/Tethering(  909): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1186): nl80211: Event message available
D/wpa_supplicant( 1186): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1186): nl80211: Connect event
D/wpa_supplicant( 1186): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1186): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1186): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1186): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1186): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1186): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1186): Add randomness: count=8 entropy=3
I/wpa_supplicant( 1186): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1186): TDLS: Remove peers on association
D/wpa_supplicant( 1186): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1186): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1186): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1186): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1186): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1186): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1186): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1186): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1186): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1186): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1186): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1186): EAPOL: enable timer tick
D/wpa_supplicant( 1186): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1186): htc_wext_set_keepalive +
I/wpa_supplicant( 1186): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1186): getPrivFuncNum +	
I/wpa_supplicant( 1186): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1186): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1186): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1186): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1186): Get randomness: len=32 entropy=4
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  909): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  909): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  909): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412,
D/WifiMonitor(  909): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  909): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  909): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  909): Enter handleAssociatedWithEvent
D/WifiStateMachine(  909): Associated
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE,
D/Tethering(  909): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  909): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  909): Exit handleAssociatedWithEvent
,D/WifiStateMachine(  909): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  909): updateConnectedAP...
D/WifiApDatabaseHandler(  909): updateConnectedAP...
D/Tethering(  909): interfaceLinkStateChanged wlan0, true
,D/Tethering(  909): interfaceStatusChanged wlan0, true
,D/WifiStateMachine(  909): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/Tethering(  909): [isWifi] getHotspotEnabled: false
,I/wpa_supplicant( 1186): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1186): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb7f769f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1186):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1186): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1186): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1186): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f1ab4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1186):    broadcast key
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1186): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1186): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1186): State: GROUP_HANDSHAKE -> COMPLETED
,I/wpa_supplicant( 1186): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1186): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1186): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 1186): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1186): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1186): netlink: Operstate: linkmode=-1, operstate=6
D/WifiMonitor(  909): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1186): set send_ind_to_ndc = 0
I/wpa_supplicant( 1186): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1186): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1186): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1186): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1186): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1186): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1186): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1186): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1186): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1186): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1186): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1186): EAPOL authentication completed successfully
I/wpa_supplicant( 1186): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1186): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1186): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1186): nl80211: if_removed already cleared - ignore event
,D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/WifiApDatabaseHandler(  909): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  909): This record is existed, only update it...
D/Tethering(  909): interfaceLinkStateChanged wlan0, true
,D/Tethering(  909): interfaceStatusChanged wlan0, true
D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/Tethering(  909): [isWifi] getHotspotEnabled: false
,D/WifiApDatabaseHandler(  909): updateConnectedAP...
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
,D/WifiApDatabaseHandler(  909): updateConnectedAP...
,I/PMS     (  909): Going to sleep due to screen timeout...
,I/SensorManager(  909): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@423ea220
,W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  909): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  909): pid=909, uid=1000
I/ActivityManager(  909): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  909): Couldn't get kernel wake lock stats
V/LightsService(  909): setLight #2: color=#0
D/qdlights(  909): set_light_buttons_func: on=0 brightness=0
,V/LightsService(  909): setLight #0: color=#0
W/SensorService(  909): Active sensors: size = 2
W/SensorService(  909): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@423ea220, eanble = 0, strlen(mName) = 59
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  909): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@422c9498
W/SensorService(  909): Listener[1] = com.htc.smartdim.sensor_eye@4295e988
W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/WirelessDisplayService(  909): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  909): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,D/WifiStateMachine(  909): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  909): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
W/PMS     (  909): mWirelessDisplayManager is null
D/WifiApDatabaseHandler(  909): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  909): This record is existed, only update it...
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  909): updateConnectedAP...
,D/WISPrService( 3829): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3829): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  909): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  909): Provision feature enable=false
D/ConnectivityService(  909): mActiveDefaultNetwork: -1
,D/WifiStateMachine(  909): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  909): updateConnectedAP...
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023757
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024057
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024063
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024065
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024073
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025588
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025610
,D/DhcpStateMachine(  909): [StoppedState] Start DHCP
D/WifiStateMachine(  909): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1186): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029133
D/WifiStateMachine(  909): handlePreDhcpSetup Held wake lock during DHCP
D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1186): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  909):    returned true
,D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1186): Power_Mode_Type mode = 1
I/wpa_supplicant( 1186): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  909):    returned true
,D/WifiNative-wlan0(  909): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  909):    returned null
E/WifiStateMachine(  909): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  909): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  909):    returned null
D/PMS     (  909): acquireWL(43d16d38): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 909 1000 null
D/WifiStateMachine(  909): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  909): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@427594f8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@427594f8 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:0
,W/fb4a(:<default>):StaticBindingVerifier( 4675): Verify
,D/SurfaceControl(  909): Excessive delay in blankDisplay() while turning screen off: 320ms
D/PMS     (  909): nativeSetInteractive:false
D/PMS     (  909): nativeSetInteractive:false done
D/PMS     (  909): nativeSetAutoSuspend:true
D/PMS     (  909): nativeSetAutoSuspend:true done
D/HABCtrl (  909): TPE algorithm. remove timeout.
D/PMS     (  909): OOBE c monitor 11
D/NfcService( 1256): ScreenObserver: OFF
,D/NfcService( 1256): applyRouting - 0
,I/IntentController( 1117): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/NfcService( 1256): applyRouting -2
I/InputManager(  909): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  909): screenObserver, isScreenOn=false
I/InputMethodManagerService(  909): Disable input method client, pid=4623
D/PMS     (  909): acquireWL(43a598a0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
D/PMS     (  909): releaseWL(43a598a0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/KeyguardServiceDelegate(  909): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43691720)
W/ResourceType( 4623): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4623): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41d49128 VFEDH.C. .F...... 0,0-720,1134 #64}
,V/KeyguardServiceDelegate(  909): **** SHOWN CALLED ****
D/PMN     (  909): wakingUp
D/WifiService(  909): New client listening to asynchronous messages
I/WindowManager(  909): No lock screen! windowToken=null
D/WirelessDisplayService(  909): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  909): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  909): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMN     (  909): onScreenOn
D/PMS     (  909): acquireWL(427e58c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
D/AlarmManager(  909): ACTION_SCREEN_ON
I/AlarmManager(  909): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  909): [AlarmQueuing] done recovering
I/AlarmManager(  909): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  909): [AlarmQueuing] done EPS screen off alarm recovering
,D/PMS     (  909): releaseWL(427e58c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/MtpService( 2710): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2710): [MTP][onReceive]-
,D/NfcService( 1256): applyRouting - 0
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/WifiDataStallTracker(  909): onReceive: action=android.intent.action.SCREEN_ON
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): acquireWL(426dfa10): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/NfcService( 1256): applyRouting -2
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): releaseWL(426dfa10): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/WirelessDisplayService(  909): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  909): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  909): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/ClockThread( 1117): stop update clock
D/WifiNative-wlan0(  909): doBoolean: SET_SCREEN_ON 1
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
V/NotificationService(  909): batLight: Full, plugged
V/LightsService(  909): setLight #8: color=#c8c800
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  909): setLight #8: color=#c800
D/qdlights(  909): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1186): SET_SCREEN_ON:On
I/wpa_supplicant( 1186): htc_wext_set_keepalive +
I/wpa_supplicant( 1186): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1186): getPrivFuncNum +	
I/wpa_supplicant( 1186): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1186): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1186): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1186): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1186): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  909):    returned true
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
I/wpa_supplicant( 1186): Change stage from stage0 to stage3
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
V/SRS_Proc(  371): ParamSet string: screen_state=on
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1186): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  909):    returned true
,D/WirelessDisplayService(  909): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4675/10027)
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
,W/fb4a(:<default>):BaseAnalyticsConfig( 4675): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4675): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  909): acquireWL(442dc310): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(442dc310): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): acquireWL(43bbf520): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(43bbf520): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/dalvikvm-heap( 4675): Grow heap (frag case) to 9.511MB for 73240-byte allocation
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1765): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1765): onScreenOn: 1450738873056
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1765): onScreenOn: 1450738873057
,I/SensorManager(  909): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@422c9498
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  909): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 2
W/SensorService(  909): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@422c9498, eanble = 0, strlen(mName) = 91
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  909): Listener[0] = com.htc.smartdim.sensor_eye@4295e988
,W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  909): goingToSleep
D/PMS     (  909): acquireWL(43ba98e8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 909 1000 null
,D/Process (  909): killProcessQuiet, pid=4422
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  909): Killing 4422:com.htc.backup/1000 (adj 15): empty #17
D/AlarmManager(  909): ACTION_SCREEN_OFF
I/AlarmManager(  909): [AlarmQueuing] screen off now: 
I/AlarmManager(  909): [AlarmQueuing] data connection: true
I/AlarmManager(  909): [AlarmQueuing] wifi connection: true
,D/WifiDataStallTracker(  909): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  909): stopDataStallAlarm: current tag=20014 mDataStallAlarmIntent=null
,D/WifiNative-wlan0(  909): doBoolean: SET_SCREEN_ON 0
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1186): SET_SCREEN_ON:Off
I/wpa_supplicant( 1186): htc_wext_set_keepalive +
I/wpa_supplicant( 1186): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1186): getPrivFuncNum +	
I/wpa_supplicant( 1186): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1186): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1186): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 1186): get_ip_address source addr = 02000000
I/wpa_supplicant( 1186): htc_wext_set_keepalive gateway addr = 00000000
I/wpa_supplicant( 1186): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  909):    returned true
D/PMS     (  909): acquireWL(43173df8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 909 1000 null
I/ActivityManager(  909): Recipient 4422
D/PMS     (  909): releaseWL(43173df8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  909): releaseWL(43ba98e8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
V/SRS_Proc(  371): ParamSet string: screen_state=off
,I/ActivityManager(  909): Start proc com.htc.sense.hsp for broadcast com.htc.sense.hsp/.weather.location.AutoSettingReceiver: pid=4708 uid=10055 gids={50055, 1023, 3003, 5012}
,D/NetworkPolicy(  909): updateScreenOn: false
D/ContactMessageStore( 1241): start background delete task...
D/ContactMessageStore( 1241): size: 0 , 0
D/ContactMessageStore( 1241): Background delete complete
,W/fb4a(:<default>):UserScope( 4675): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4675): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4675): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] getTotalRam: 1873 Mb
D/PMS     (  909): acquireWL(43bf9a20): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(43bf9a20): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): acquireWL(435b1d00): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(435b1d00): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1765): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1765): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1765): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1765): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1765): onScreenOff
,E/dalvikvm( 4675): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4675): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4675): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4675): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4675): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 4675): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4675): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4675): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4675): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4675): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4675): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4675): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4675): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4675): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4675): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4675): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4675): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4675): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,D/PluginProvider( 4708): PluginProvider onCreate
,D/PluginProvider( 4708): current plugin count: 18
,D/HtcAppUPService( 4708): HtcUPDataProvider onCreate()
,I/dalvikvm-heap( 4675): Grow heap (frag case) to 9.909MB for 39954-byte allocation
,I/dalvikvm-heap( 4675): Grow heap (frag case) to 9.985MB for 79892-byte allocation
,D/AutoSetting( 4708): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/dalvikvm-heap( 4675): Grow heap (frag case) to 10.063MB for 84664-byte allocation
,I/ActivityManager(  909): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4725 uid=10079 gids={50079, 3003, 5012}
,D/Process (  909): killProcessQuiet, pid=4438
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  909): Killing 4438:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/AutoSetting( 4708): Util - no network available!
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (4708/10055)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (4708/10055)
I/ActivityManager(  909): Recipient 4438
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/AutoSetting( 4708): service - onCreate()
D/AutoSetting( 4708): service - AddressCache: using context: com.htc.Weather
D/AutoSetting( 4708): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/LocationManagerService(  909): request 421c8b58 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/LocationManagerService(  909): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 4708): service - mHandler: cancel location update
,D/AutoSetting( 4708): service -           changes count: 0
,D/MobileConnectivityChangeReceiver( 4725): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4725): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4725): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4725): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  909): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4742 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4725/10079)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4725/10079)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4725/10079)
,I/dalvikvm-heap( 4675): Grow heap (frag case) to 10.277MB for 75760-byte allocation
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4675/10027)
,W/BroadcastQueue(  909): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43e757d0 u0 ReceiverList{43e756b0 4675 com.facebook.katana/10027/u0 remote:43e5f330}}
,W/BroadcastQueue(  909): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43e757d0 u0 ReceiverList{43e756b0 4675 com.facebook.katana/10027/u0 remote:43e5f330}}
,W/BroadcastQueue(  909): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42872100 u0 ReceiverList{428720a0 4675 com.facebook.katana/10027/u0 remote:442af6f0}}
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023757
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024057
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024063
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024065
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024073
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025610
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029133
,D/Process (  909): killProcessQuiet, pid=4354
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/libc    (  909): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
I/ActivityManager(  909): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4756 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
I/ActivityManager(  909): Killing 4354:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4675/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4675/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4675/10027)
,I/ActivityManager(  909): Recipient 4354
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/wpa_supplicant( 1186): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1186): EAPOL: disable timer tick
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4756): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
D/PMS     (  909): acquireWL(43938940): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(43938940): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4756): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAV2    ( 4756): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4756): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4756): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4675): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4675): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4675): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,D/libc    (  909): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  909): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1186): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  909):    returned true
,D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1186): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1186): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  909):    returned true
,D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1186): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  909):    returned true
,D/WifiStateMachine(  909): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): releaseWL(43d16d38): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiP2pService(  909): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=100 [1][1][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1186): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (4756/10151)
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED -1 -> 3
D/WifiStateMachine(  909): gateway: /192.168.1.1
,D/WifiNative-wlan0(  909): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1186): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1186): htc_wext_set_keepalive +
I/wpa_supplicant( 1186): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1186): getPrivFuncNum +	
I/wpa_supplicant( 1186): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1186): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1186): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1186): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1186): htc_wext_set_keepalive - ret = 0
V/WebViewChromiumFactoryProvider( 4756): Binding Chromium to main looper Looper (main, tid 1) {41d35138}
D/WifiNative-wlan0(  909):    returned true
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  909): VerifyingLinkState enter
,D/WifiStateMachine(  909): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  909): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  909): VerifyingLinkState: enableIpv6
,I/LibraryLoader( 4756): Expected native library version number "",actual native library version number ""
,I/chromium( 4756): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4756): Initializing chromium process, renderers=0
,D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -57, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiWatchdogStateMachine(  909): WAN detection
,E/AudioManagerAndroid( 4756): BLUETOOTH permission is missing!
V/NetworkPolicy(  909): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  909): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/PMS     (  909): acquireWL(43a46d50): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/ConnectivityService(  909): Provision feature enable=false
D/PMS     (  909): acquireWL(42934450): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/ConnectivityService(  909): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  909): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  909): default: teardown()
D/MDST    (  909): default: setTeardownRequested(true)
D/MDST    (  909): default: setEnableApn apnType =default , enable=false
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/MDST    (  909): default: setTeardownRequested(true)
,I/Adreno-EGL( 4756): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4756): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4756): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4756): Local Branch: 
I/Adreno-EGL( 4756): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4756): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4756):                  aa63bbd948f41d15fc72f585e
,D/WISPrService( 3829): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  909): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
D/PMS     (  909): releaseWL(43a46d50): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/ConnectivityService(  909): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  909): Unexpected mtu value: android.net.wifi.WifiStateTracker@426bf960
,D/ConnectivityService(  909): handleConnectivityChange: netType=1 doReset=false resetMask=0
,D/WifiStateMachine(  909): syncGetConfiguredNetworks
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  909): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
,D/ConnectivityService(  909): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
I/QuickSettingWifi( 1117): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  909): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  909): handleConnectivityChange: resetting
D/Nat464Xlat(  909): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  909): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  909): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  909): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  909): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  909): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  909): acquireWL(442d8d28): PARTIAL_WAKE_LOCK  NetworkStats 0x1 909 1000 null
D/WirelessDisplayService(  909): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/WirelessDisplayService(  909):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4725/10079)
I/NSApplication( 4756): Starting up...
I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
D/PMS     (  909): acquireWL(442c7318): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4106 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (4756/10151)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (4756/10151)
,D/PMS     (  909): acquireWL(442bda10): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4106 10029 WorkSource{10029 com.google.android.gms}
I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
D/PMS     (  909): releaseWL(442c7318): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,I/CheckinService( 4106): Checkin interval check for package: unspecified last checkin: 1450738826820 min interval config: 0 actual interval: 46978
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  909): mActiveDefaultNetwork: WIFI
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4155/10160)
D/PMS     (  909): releaseWL(442d8d28): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4155/10160)
,I/CheckinService( 4106): Disabling old GoogleServicesFramework version
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$Receiver, state=2, flag=1, pid=4106, uid=10029, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$TriggerReceiver, state=2, flag=1, pid=4106, uid=10029, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$SecretCodeReceiver, state=2, flag=1, pid=4106, uid=10029, userID:0
,W/dalvikvm( 4106): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4106): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/iu.SyncManager( 4106): SYNC; picasa accounts
,D/NetworkLogImpl( 4106): Loaded NetworkSpeedPredictor
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,I/iu.Environment( 4106): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (4106/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (4106/10029)
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (4106/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (4106/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (4106/10029)
,I/iu.UploadsManager( 4106): num queued entries: 0
,I/iu.UploadsManager( 4106): num updated entries: 0
,I/iu.SyncManager( 4106): NEXT; no task
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1358/10029)
I/CheckinService( 4106): Checking schedule, now: 1450738873896 next: 1450738856791
,I/CheckinService( 4106): active receiver: enabled
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1358/10029)
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=4106, uid=10029, userID:0
,I/ActivityManager(  909): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4827 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/CheckinService( 4106): Preparing to send checkin request
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (4106/10029)
,I/EventLogService( 4106): Accumulating logs since 1450738822723
,W/ContextImpl( 4827): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4827): isEpsOn(), nState = 0
D/PMS     (  909): acquireWL(42839e40): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4827 1000 null
,D/SmartSyncUtils( 4827): getMobilePolicyEnabled, result = true
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/AutoSetting( 4708): receiver - intent: android.intent.action.USER_PRESENT
,D/Process (  909): killProcessQuiet, pid=4291
I/ActivityManager(  909): Killing 4291:com.htc.task/u0a71 (adj 15): empty #17
,D/PMS     (  909): releaseWL(42839e40): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/AutoSetting( 4708): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/TetherSettings( 3829): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3829): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3829): Cust_ConnectToPC   : Modem_Link>false
,D/        ( 3829): Cust_ConnectToPC   : spcsc>false
D/        ( 3829): Cust_ConnectToPC   : IPT>true
,D/        ( 3829): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3829): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3829): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3829): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3829): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 3829): onReceive:android.intent.action.USER_PRESENT
I/ActivityManager(  909): Recipient 4291
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 3829): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 3829): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3829): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3829):  defaultType:0
,E/dalvikvm( 4106): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a
,W/dalvikvm( 4106): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
,W/dalvikvm( 4106): VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;)
,W/dalvikvm( 4106): VFY: unable to resolve virtual method 6547: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
,W/dalvikvm( 4106): VFY: unable to resolve static field 229 (SUPPORTED_ABIS) in Landroid/os/Build;
,I/CheckinRequestBuilder( 4106): Checkin reason type: 8 attempt count: 1
W/ContextImpl( 4827): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/WifiService(  909): New client listening to asynchronous messages
,D/SmartSyncUtils( 4827): isEpsOn(), nState = 0
D/SmartSyncUtils( 4827): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4827): getMobilePolicyEnabled, result = true
I/ActivityManager(  909): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4106): Failed to find provider info for com.google.android.wearable.settings
D/WifiService(  909): New client listening to asynchronous messages
,I/SensorManager(  909): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4295e988
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  909): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 1
W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4295e988, eanble = 0, strlen(mName) = 36
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  909): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 0
W/SensorService(  909): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4295e988, eanble = 0, strlen(mName) = 36
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  909): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4295e988
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
E/ActivityThread(  909): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42945f80 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  909): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42945f80 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/ConnectivityService(  909): getNetworkInfo networkType=9 called by com.google.android.gms (4106/10029)
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (4106/10029)
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,V/GLSActivity( 1358): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1358): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  909): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4852 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,W/dalvikvm( 4852): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4852): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4852): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4852): install
,I/MultiDex( 4852): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4852): loading existing secondary dex files
,I/MultiDex( 4852): load found 3 secondary dex files
,I/MultiDex( 4852): install done
,W/dalvikvm( 4852): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
W/dalvikvm( 4852): VFY: unable to resolve instance field 36
,W/dalvikvm( 4852): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4852): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ProviderInstaller( 4852): Installed default security provider GmsCore_OpenSSL
,W/dalvikvm( 4852): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4852): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,W/dalvikvm( 4852): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4852): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4852): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4852): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4852): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/WearableService( 1223): callingUid 10029, callindPid: 1223
D/PMS     (  909): releaseWL(427f9478): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  909): NetTransition Wakelock for ConnectedState released by timeout
D/LocationInitializer( 4106): Restart initialization of location
E/MDM     ( 1223): [118] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  909): mTetherableUsbRegexs:{(usb0)(ncm0)}
,V/Tethering(  909): bSetPropertyMultiRAB:false
,D/Tethering(  909): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,D/CaptivePortalTracker(  909): NoActiveNetworkState
I/AlarmManager(  909): [AlarmQueuing] connectivity wifi: true
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(4428e088): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 909 1000 null
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(428cfd58): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/AccTypeManager( 1344): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Tethering(  909): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  909): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  909): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  909): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  909): Found interface wlan0
D/Tethering(  909): TetherMasterSM: InitialState processMessage what=3
,D/GpsLocationProvider(  909): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  909): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  909): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  909): ignore wifi update if we are not in OPENING or CLOSING
,D/CaptivePortalTracker(  909): DelayedCaptiveCheckState
,I/ConnectivityHelper( 1273): [onReceive] WIFI(1): CONNECTED
,I/NetworkMonitor( 4497): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.musicenhancer (3943/10053)
D/PMS     (  909): releaseWL(428cfd58): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  909): releaseWL(4428e088): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.google.android.music (4497/10154)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.htc.launcher (1273/10076)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.backuptransport (1572/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.backuptransport (1572/10029)
D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
W/GCoreFlp( 1223): No location to return for getLastLocation()
,W/FusedLocationProvider( 1223): location=null
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): acquireWL(4271b950): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023757
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (4725/10079)
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024057
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024063
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024065
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024073
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4675/10027)
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025610
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029133
D/PMS     (  909): releaseWL(4271b950): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4675/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4675/10027)
W/AccTypeManager( 1344): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1344): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023757
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024057
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024063
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024065
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024073
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025610
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029133
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/AuthorizationBluetoothService( 1358): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1358): Proximity feature is not enabled.
,I/WVCdm   (  371): Level3 Library Nov 20 2013 18:09:31
,E/ExternalAccountType( 1344): Unsupported attribute readOnly
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
W/WVCdm   (  371): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,V/GLSActivity( 1358): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/NativeLibraryUtils( 4852): Install completed successfully. count=14 extracted=0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (2710/10021)
,D/AutoSetting( 4708): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/MobileConnectivityChangeReceiver( 4725): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4725): onReceive CONNECTIVITY_CHANGE networkType=1
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (4708/10055)
,D/AutoSetting( 4708): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/WVCdm   (  371): PrepareKeyRequest: nonce=2961045758
,D/AutoSetting( 4708): service - onStartCommand() screen is off, don't request location
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (4756/10151)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (4708/10055)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/AutoSetting( 4708): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 4708): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4155/10160)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (4155/10160)
,D/PMS     (  909): acquireWL(43e1b630): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4106 10029 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,I/CheckinService( 4106): Checkin interval check for package: unspecified last checkin: 1450738826820 min interval config: 0 actual interval: 48076
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): releaseWL(43e1b630): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,I/dalvikvm-heap( 4155): Grow heap (frag case) to 13.502MB for 1821008-byte allocation
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4106, uid=10029, userID:0
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,I/WVCdm   (  371): CdmEngine::CloseSession
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (4106/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (4106/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (4106/10029)
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1358/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1358/10029)
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  371): PrepareKeyRequest: nonce=460756541
,I/WVCdm   (  371): CdmEngine::CloseSession
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (4852/10029)
,W/dalvikvm( 4623): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4623): threadid=1: thread exiting with uncaught exception (group=0x41906e30)
,E/ActivityManager(  909): App crashed! Process: com.test.thalitest
E/AndroidRuntime( 4623): FATAL EXCEPTION: main
E/AndroidRuntime( 4623): Process: com.test.thalitest, PID: 4623
E/AndroidRuntime( 4623): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4623): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4623): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4623): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4623): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4623): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4623): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4623): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4623): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4623): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4623): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4623): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4623): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4623): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4623): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4623): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4623): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4623): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4623): 	at dalvik.system.NativeStart.main(Native Method)
W/ActivityManager(  909):   Force finishing activity com.test.thalitest/.MainActivity
,D/Process (  909): killProcessQuiet, pid=3867
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
,I/ActivityManager(  909): Killing 3867:com.htc.mediamanager/u0a34 (adj 15): empty #17
D/Process ( 4623): killProcess, pid=4623
D/Process ( 4623): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,I/Adreno-EGL( 4852): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4852): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4852): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4852): Local Branch: 
I/Adreno-EGL( 4852): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4852): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4852):                  aa63bbd948f41d15fc72f585e
,I/ActivityManager(  909): Recipient 3867
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Recipient 4623
,W/InputDispatcher(  909): channel '427f9ab0 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  909): channel '427f9ab0 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  909): Attempted to unregister already unregistered input channel '427f9ab0 com.test.thalitest.MainActivity (s)'
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  909): Client connection lost with reason: 4
I/ActivityManager(  909): Process com.test.thalitest (pid 4623) has died.
I/WindowState(  909): WIN DEATH: Window{427f9ab0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/WindowManager(  909): WINDOW DIED Window{427f9ab0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/Adreno-EGL( 4852): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4852): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4852): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4852): Local Branch: 
I/Adreno-EGL( 4852): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4852): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4852):                  aa63bbd948f41d15fc72f585e
,W/InputMethodManagerService(  909): Got RemoteException sending setActive(false) notification to pid 4623 uid 10389
,W/Binder  ( 1208): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1208): java.lang.NullPointerException
W/Binder  ( 1208): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1208): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1208): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1208): 	at dalvik.system.NativeStart.run(Native Method)
,I/Adreno-EGL( 4852): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4852): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4852): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4852): Local Branch: 
I/Adreno-EGL( 4852): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4852): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4852):                  aa63bbd948f41d15fc72f585e
,W/Settings( 4852): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4675/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4675/10027)
,W/fb4a(:<default>):UserScope( 4675): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4675): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4675/10027)
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4675/10027)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4675): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4675/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4675/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4675/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4675/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4675/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4675/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4675/10027)
,I/CheckinRequestBuilder( 4106): Classify the device as Phone.
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4675/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4675/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4675/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4675/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4675/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4675/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4675/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4675/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4675/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4675/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4675/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4675/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4675/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4675/10027)
,W/dalvikvm( 4106): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (4675/10027)
,D/libc    ( 4106): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4106): [NET] getaddrinfo-,err=8
,D/libc    ( 4106): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 4106): [NET] getaddrinfo-, 1
,D/libc    ( 4106): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =b2ff +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 290
D/libc    (  364): [NET]res_nsend:resplen=84
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4106): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4106): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4106): [NET] getaddrinfo-,err=8
,D/libc    ( 4106): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4106): [NET] getaddrinfo-,err=8
,D/libc    ( 4106): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4106): [NET] getaddrinfo-,err=8
,I/CheckinTask( 4106): Sending checkin request (12205 bytes)
,D/WifiStateMachine(  909): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  909): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  909): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-,err=8
D/libc    (  909): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  909): [NET] getaddrinfo-, 1
,D/libc    (  909): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =3063 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/PMS     (  909): releaseWL(42934450): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  909): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  909): Find DNS Address www.htc.com/104.81.130.175
,I/CheckinRequestBuilder( 4106): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  909): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4106): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  909): getNetworkInfo networkType=9 called by com.google.android.gms (4106/10029)
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=20 [20][4][0]
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (4106/10029)
,I/CheckinRequestBuilder( 4106): Classify the device as Phone.
,I/CheckinTask( 4106): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 4106): Checking schedule, now: 1450738876946 next: 1451261813941
,I/CheckinService( 4106): active receiver: disabled
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4106, uid=10029, userID:0
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023757
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023939
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024057
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024063
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024065
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024073
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025588
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025610
,I/CheckinService( 4106): Checking schedule, now: 1450738876965 next: 1451261813941
,I/CheckinService( 4106): active receiver: disabled
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029133
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4106, uid=10029, userID:0
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023757
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024057
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024063
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024065
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024073
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025588
,D/CheckinService( 4106): Recording last checkin time for package unspecified as 1450738876971
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025610
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029133
,D/PMS     (  909): releaseWL(442bda10): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (4106/10029)
,D/PMS     (  909): acquireWL(43a70900): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 1358): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    ( 1358): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1358): [NET] getaddrinfo-,err=8
D/libc    ( 1358): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1358): [NET] getaddrinfo-, 1
,D/libc    ( 1358): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =fe23 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1358/10029)
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 217
D/libc    (  364): [NET]res_nsend:resplen=79
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1358): [NET] getaddrinfo_proxy-, success,
,D/libc    ( 1358): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1358): [NET] getaddrinfo-,err=8
,D/libc    ( 1358): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1358): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1358/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1358/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1358/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1358/10029)
,D/PMS     (  909): acquireWL(442842a0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1358/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1358/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1358/10029)
,D/PMS     (  909): releaseWL(43a70900): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1358/10029)
,D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1358/10029)
D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  909): handleInetConditionChange: starting a change hold
,D/PMS     (  909): releaseWL(442842a0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(4379e858): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1358/10029)
,D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1358/10029)
D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  909): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1358/10029)
,D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1358/10029)
,D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  909): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1358/10029)
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023757
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023939
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024057
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024063
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024065
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024073
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025588
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025610
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029133
,D/PMS     (  909): releaseWL(4379e858): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  909): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [11][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,I/GAV2    ( 4756): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  909): killProcessQuiet, pid=4524
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4524:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  909): Client connection lost with reason: 4
,I/ActivityManager(  909): Recipient 4524
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC <<
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=4106, uid=10029, userID:0
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=4106, uid=10029, userID:0
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=4106, uid=10029, userID:0
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=4106, uid=10029, userID:0
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1344): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "sms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1273): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/ActivityManager(  909): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4909 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "smsto"
,I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/Launcher( 1273): Deferring update until onResume
D/Launcher( 1273): waitUntilResume // bindAppsUpdated
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
W/AccTypeManager( 1344): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1344): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  909):   Scheme: "mms",
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,D/AutoSetting( 4708): service - mRequestRunnable: screen on delay 10s, request NLP now
,W/SystemReader( 1256): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/AutoSetting( 4708): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 4708): service - requestNLP() NetworkLocationProvider not enabled
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "sms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "smsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,E/ExternalAccountType( 1344): Unsupported attribute readOnly
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,D/PhoneApp( 1241): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4909): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4909): MmsConfig.loadMmsSettings
,W/dalvikvm( 4909): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4909): VFY: unable to resolve instance field 36
,W/dalvikvm( 4909): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4909): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  909): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4932 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4909, uid=10111, userID:0
,D/MessageFrequencyProvider( 4932): onCreate
,W/Settings( 4909): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/GetPrviateResource( 4932): GetPrviateResource
D/MmsCustomizationProvider( 4932): query uri: content://htc-mms-customization/mms-ua/ua_string
,V/GetPrviateResource( 4932): GetPrviateResource
,I/ProviderInstaller( 4909): Installed default security provider GmsCore_OpenSSL
,D/CaptivePortalTracker(  909): DelayedCaptiveCheckState
,D/ConnectivityService(  909): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/MessageCustFlag( 4932): sense_version=6.0
D/BTAccessoryUtil( 4932): createReceiver
D/CaptivePortalTracker(  909): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/BTAccessoryUtil( 4932): registerReceiver return intent = null
D/MessageCustFlag( 4932): sku_id=99
W/SystemReader( 4932): Cannot find message_ambs_application_id, use default value instead
D/MmsCustomizationProvider( 4932): query uri: content://htc-mms-customization/mms-ua/ua_profile
D/Messaging( 4932): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4932): networkCode: 
D/MessageCustFlag( 4932): sku_id=99
D/MmsConfig( 4932): SIE smsPri: null
D/MmsConfig( 4932): networkCode: 
I/Babel   ( 4909): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/Babel   ( 4909): MmsConfig.loadFromDatabase
D/HtcTelephonyCapability( 4932): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 4932): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4932): getRATByHtcTelephonyCapability:1
W/SystemReader( 4932): Cannot find qct_8960_interface, use default value instead
,E/Babel   ( 4909): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4909): MmsConfig.loadFromResources
,E/Babel   ( 4909): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4909): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4909, uid=10111, userID:0
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4909, uid=10111, userID:0
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4909, uid=10111, userID:0
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4909, uid=10111, userID:0
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4909, uid=10111, userID:0
,D/PMS     (  909): acquireWL(443f2208): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4909 10111 null
,I/[PluginManager]RegisterService( 4708): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 4708): handle notify Blinkfeed plugin client changed
I/ActivityManager(  909): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/IcingCorporaProvider( 2826): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PMS     (  909): acquireWL(443112b8): PARTIAL_WAKE_LOCK  Icing 0x1 4106 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(443f2208): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/PMS     (  909): releaseWL(443112b8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.google.android.googlequicksearchbox/.GelStubAppWatcher
,D/PMS     (  909): acquireWL(442e6c40): PARTIAL_WAKE_LOCK  Icing 0x1 4106 10029 WorkSource{10029 com.google.android.gms}
,W/PackageManager(  909): Unable to load service info ResolveInfo{42921838 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,D/PMS     (  909): releaseWL(442e6c40): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  909): Resuming delayed broadcast
,D/PMS     (  909): acquireWL(442ccc68): PARTIAL_WAKE_LOCK  AsyncService 0x1 4155 10160 null
,I/ActivityManager(  909): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  909): acquireWL(442c7318): PARTIAL_WAKE_LOCK  Icing 0x1 4106 10029 WorkSource{10029 com.google.android.gms}
,I/dalvikvm-heap( 4155): Grow heap (frag case) to 15.200MB for 1821008-byte allocation
D/PMS     (  909): releaseWL(442ccc68): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/dalvikvm-heap( 4155): Grow heap (frag case) to 16.936MB for 1821008-byte allocation
D/PMS     (  909): releaseWL(442c7318): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  909): acquireWL(44295bb8): PARTIAL_WAKE_LOCK  Icing 0x1 4106 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(44295bb8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41dc9c70 +
,I/Prism.WidgetManager( 1273): onLoadItems() +
I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,D/PMS     (  909): acquireWL(43e91878): PARTIAL_WAKE_LOCK  Icing 0x1 4106 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(43e91878): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  909): Resuming delayed broadcast
,D/PackageBroadcastService( 4106): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/ActivityManager(  909): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PMS     (  909): acquireWL(43e725d8): PARTIAL_WAKE_LOCK  Icing 0x1 4106 10029 WorkSource{10029 com.google.android.gms}
I/PackageBroadcastService( 4106): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 4106): updateResources: need to parse f{com.google.android.gms}
,I/IcingCorporaProvider( 2826): UpdateCorporaTask done [took 532 ms] updated apps [took 532 ms] 
I/ActivityManager(  909): Resuming delayed broadcast
,E/Prism.WidgetManager( 1273): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1273): onLoadItems() -
,I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41dc9c70 -
,D/RemoteDisplayProvider(  909): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  909): start
,I/GCoreNlp( 1223): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/PMS     (  909): acquireWL(426ed4e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(426ed4e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(438fe7f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(438fe7f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  909): applying state to connected service
,D/LocationProviderProxy(  909): applying state to connected service
,D/PMS     (  909): acquireWL(41f2edd8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): acquireWL(443190a0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(443190a0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(41f2edd8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PhoneApp( 1241): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1241): -- N1 =0
,D/PhoneApp( 1241): -- N2 =0
,D/PhoneApp( 1241): -- N3 =0
,I/Icing   ( 4106): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 4106): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/Messaging( 4932): mNeedToUpdateDate2 start
,D/MmsConfig( 4932): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4932): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4932): 
D/MmsAsyncWorkHandler( 4932): HM tk = 20001
D/ReportIndicatorCache( 4932): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4932): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41d436f0
,I/Messaging( 4932): mccmnc> 
D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/DraftCache( 4932): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4932): [DraftCache/1] refresh
D/MmsSmsV2Provider( 1241):  phoneType = -1
,D/MmsSmsV2Provider( 1241): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/MmsConfig( 4932): networkCode: 
,D/Messaging( 4932): ViewCache CreatePreloadOnlyConversationList
,D/PMS     (  909): releaseWL(43e725d8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/MmsSmsV2Provider( 1241):  phoneType = -1
D/MmsSmsV2Provider( 1241): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
D/PhoneStorageUtil( 4932): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4932): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 4932): createReceiver
D/MessageCustFlag( 4932): sense_version=6.0
D/Jerry   ( 4932): start to preload cursor >>>>>>>
D/TelephUtils( 1241): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
V/MmsProvider( 1241): Update uri=content://mms, match=0
V/MmsProvider( 1241): selection=st=129 AND m_type!=134
D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/MmsSmsV2Provider( 1241):  phoneType = -1
D/MmsSmsV2Provider( 1241): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/Messaging( 4932): Reset downloading state: 0
V/MmsSystemEventReceiver( 4932): TransactionService is going to be woken up.
D/Messaging( 4932): mNeedToUpdateDate2: false
V/TransactionService( 4932): 1-Creating TransactionService
V/TransactionService( 4932): onStartCommand: 1
D/MmsSystemEventReceiver( 4932): unRegisterForConnectionStateChanges
V/TransactionService( 4932): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 4932): Loading previous transactions.
D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/AccFlag ( 1241): sku_id=99
,D/DraftCache( 4932): [DraftCache/496] rebuildCache
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1241): device_type: 1
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/MmsSmsV2Provider( 1241):  phoneType = -1
,D/MmsSmsV2Provider( 1241): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/TransactionService( 4932): Force set service start id to 1
V/TransactionService( 4932): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4932): unRegisterForConnectionStateChanges
V/TransactionService( 4932): Destroying TransactionService
,D/TransactionService( 4932): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4932): 4-Handling incoming message: { when=-2ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
D/Messaging( 4932): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/MmsSmsV2Provider( 1241):  phoneType = -1
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
,D/Jerry   ( 1241): URI_DRAFT
D/Messaging( 4932): ViewCache CreatePreload
,D/Messaging( 4932): ViewCache CreatePreloadOnlyMultipleOpsList
,D/DraftCache( 4932): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 4932): [DraftCache/496] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4932): 
D/MmsAsyncWorkHandler( 4932): HM tk = 20002
D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1241): sku_id=99
,D/Cust_MMSMS( 4932): _has_set_default_values_2=true
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
,D/AccFlag ( 1241): sku_id=99
,D/MsgPreferenceUtils( 4932): def_index: 0
,D/MsgPreferenceUtils( 4932): globalIndex = 1
D/MsgPreferenceUtils( 4932): phone state: true
,D/MsgPreferenceUtils( 4932): sd state: false
,D/MsgPreferenceUtils( 4932): vIndex = 0
,D/Process (  909): killProcessQuiet, pid=3943
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3943:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3943
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Waited long enough for: ServiceRecord{42dd6940 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/GAV4    ( 4909): Thread[GAThread,5,main]: No campaign data found.
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/Process (  909): killProcessQuiet, pid=4546
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4546:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 4546
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=4106, uid=10029, userID:0
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=4106, uid=10029, userID:0
,I/CheckinService( 4106): Done disabling old GoogleServicesFramework version
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=4106, uid=10029, userID:0
,D/PMS     (  909): acquireWL(43a54d20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43a54d20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): closing low battery warning: level=100
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  909): acquireWL(43a4e138): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  909): sending alarm PendingIntent{428cc608: PendingIntentRecord{42935088 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=127300, Int=0
,V/AlarmManager(  909): sending alarm PendingIntent{42907998: PendingIntentRecord{43ade078 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=135920, Int=0
,D/PMS     (  909): acquireWL(43b8ba40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1358/10029)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=25 [8][2][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0,
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/PMS     (  909): acquireWL(425d8460): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(425d8460): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(43b8ba40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(43a4e138): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1358/10029)
,D/PMS     (  909): acquireWL(427f4498): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023757
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024057
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024063
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024065
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024073
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025610
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029133
,D/PMS     (  909): releaseWL(427f4498): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(428e0940): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1358/10029)
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=100 [1][1][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023757
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024057
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024063
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024065
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024073
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025610
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029133
,D/PMS     (  909): acquireWL(43544560): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(436ab818): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 1223): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1223): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1223): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1223): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/PMS     (  909): releaseWL(428e0940): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/GoogleURLConnFactory( 1223): Using platform SSLCertificateSocketFactory
D/PMS     (  909): acquireWL(43413090): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1358/10029)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023757
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024057
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024063
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024065
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024073
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025610
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029133
,D/PMS     (  909): releaseWL(43413090): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/PhenotypeConfigurator( 1223): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,D/PMS     (  909): releaseWL(436ab818): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(43d28b58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023757
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024057
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024063
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024065
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024073
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025610
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029133,
,D/PMS     (  909): releaseWL(43d28b58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/SQLiteConnectionPool( 4106): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  909): acquireWL(434650c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1358/10029)
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023757
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024057
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024063
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024065
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024073
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025610
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029133
,D/PMS     (  909): releaseWL(434650c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(42870048): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1358/10029)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023757
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024057
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024063
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024065
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024073
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025610
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029133
,W/dalvikvm( 1223): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
D/PMS     (  909): releaseWL(42870048): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    ( 1223): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 4
D/libc    ( 1223): [NET] getaddrinfo-,err=8
D/libc    ( 1223): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 1024
D/libc    ( 1223): [NET] getaddrinfo-, 1
,D/libc    ( 1223): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =da82 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 18084,
D/libc    (  364): [NET]res_nsend:resplen=45
D/libc    (  364): [NET]res_queryN: exit 3, ancount=1
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1223): [NET] getaddrinfo_proxy-, success,
,D/libc    ( 1223): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 4
,D/libc    ( 1223): [NET] getaddrinfo-,err=8
D/libc    ( 1223): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 4
,D/libc    ( 1223): [NET] getaddrinfo-,err=8
,W/PhenotypeConfigurator( 1223): Server returned 404
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): acquireWL(43a60008): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1358/10029)
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=9 [11][1][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/PMS     (  909): releaseWL(43544560): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023757
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024057
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024063
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024065
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024073,
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025610
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029133
,D/PMS     (  909): acquireWL(43e6eea0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1223): Vacuum at: now=1450738904689 tag=VacuumService
,D/PMS     (  909): releaseWL(43a60008): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(43662960): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023757
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024057
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024063
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024065
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024073
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025588
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025610
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029133
,D/PMS     (  909): releaseWL(43662960): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(43e6eea0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(43ed6380): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023757
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024057
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024063
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024065
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024073
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025610
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029133
,D/PMS     (  909): releaseWL(43ed6380): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(434f66a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1358/10029)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=100 [1][1][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023757
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024057
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024063
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024065
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024073
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025610
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029133
,D/PMS     (  909): releaseWL(434f66a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 4708): service - has update message, not stop
,D/AutoSetting( 4708): service - mHandler: update timezone
,D/AutoSetting( 1505): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1505): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1505): service - onCreate()
W/ActivityManager(  909): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  909): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1505): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1505): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 1505): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1505): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1505): service - mHandler: update timezone
,D/AutoSetting( 1505): service - processTimeZoneID() system nitz: ,
,D/AutoSetting( 1505): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1505): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1505): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1558): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1558): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1117): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41d40608 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.htclocationservice 2 11 3 11
,D/PMS     (  909): acquireWL(428f3a30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{425561b0: PendingIntentRecord{42556130 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141457, Int=0
,D/GpsLocationProvider(  909): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  909): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  909): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  909): acquireWL(43a636c8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 909 1000 null
D/PMS     (  909): releaseWL(428f3a30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  909): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-,err=8
D/libc    (  909): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  909): [NET] getaddrinfo-, 1
,D/libc    (  909): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =86b8 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59,
D/libc    (  364): [NET]res_nsend:resplen=238
D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS,
D/libc    (  909): [NET] getaddrinfo_proxy-, success
I/global  (  909): call createSocket() return a new socket.
D/libc    (  909): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  909): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  909): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  909): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  909):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  909): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  909): releaseWL(43a636c8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC <<
,D/PMS     (  909): acquireWL(43e6f3e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422615a0: PendingIntentRecord{42230f68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=152700, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,I/ActivityManager(  909): Waited long enough for: ServiceRecord{42d3d798 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  909): releaseWL(43e6f3e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43a485e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
I/BatteryService(  909): n_update end
D/PMS     (  909): releaseWL(43a485e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PMS     (  909): runPSCheck
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 4708): service - handleMessage() stop self
,D/AutoSetting( 4708): service - handleMessage() quit looper
,D/AutoSetting( 4708): service - onDestroy() END
,D/Process (  909): killProcessQuiet, pid=4560
,I/ActivityManager(  909): Killing 4560:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Recipient 4560
,D/AutoSetting( 1505): service - handleMessage() stop self
,D/AutoSetting( 1505): service - onDestroy() END
,D/AutoSetting( 1505): service - handleMessage() quit looper
,I/ActivityManager(  909): Killing 4088:com.google.android.gm/u0a107 (adj 15): empty #17
D/Process (  909): killProcessQuiet, pid=4088
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Recipient 4088
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  909): acquireWL(4283ef88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10027}
,V/AlarmManager(  909): sending alarm PendingIntent{43f0d940: PendingIntentRecord{43e6c6c8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=176061, Int=0
,D/PMS     (  909): releaseWL(4283ef88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1241): switchBindHtcMsgCursor: null
,D/PMS     (  909): acquireWL(43a49d88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  909): sending alarm PendingIntent{43e11ff8: PendingIntentRecord{42935088 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=187317, Int=0
,D/PMS     (  909): releaseWL(43a49d88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(43a61630): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1358/10029)
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=8 [35][3][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/PMS     (  909): acquireWL(42e85c50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(43a61630): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(42e85c50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(43e466d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023757
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024057
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024063
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024065
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024073
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025610
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029133
,D/PMS     (  909): releaseWL(43e466d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(43e6d210): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1358/10029)
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023757
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024057
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024063
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024065
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024073
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025610
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029133
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/PMS     (  909): acquireWL(43477890): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(43e6d210): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1223): Scheduling Phenotype for one-off execution 6866 seconds from now (1450738955263)
,D/GetConfigurationSnapshotOperation( 1223): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1223): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1223): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  909): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1223): [NET] getaddrinfo-,err=8
D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1223): [NET] getaddrinfo-, 1
,D/libc    ( 1223): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =3e0b +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 200
D/libc    (  364): [NET]res_nsend:resplen=87
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1223): [NET] getaddrinfo_proxy-, success,
,D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1223): [NET] getaddrinfo-,err=8
,D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1223): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  909): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=12 [8][1][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  909): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  909): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/PMS     (  909): releaseWL(43477890): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(42d137d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023757
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023939
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024057
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024063
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024065
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024073
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025610
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029133
,D/PMS     (  909): releaseWL(42d137d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(43692ab8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1358/10029)
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [2][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023757
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024057
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024063
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024065
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024073
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025610
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029133
,D/PMS     (  909): releaseWL(43692ab8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(44311268): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PMS     (  909): releaseWL(44311268): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,I/ClearcutLoggerApiImpl( 1358): disconnect managed GoogleApiClient
,D/PMS     (  909): acquireWL(442d9b20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
V/AlarmManager(  909): sending alarm PendingIntent{422615a0: PendingIntentRecord{42230f68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=212700, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(442d9b20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(442d9578): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(442d9578): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  909): acquireWL(43e91878): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43e91878): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  909): acquireWL(43d19608): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422615a0: PendingIntentRecord{42230f68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=272700, Int=0
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43d19608): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  909): acquireWL(43c00a88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/PMS     (  909): releaseWL(43c00a88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
,I/HtcPowerSaver(  909): >> updateStatus
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  909): acquireWL(43a58478): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43a58478): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(43a53e60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422615a0: PendingIntentRecord{42230f68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=332699, Int=0
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43a53e60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  909): acquireWL(43a53b80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43a53b80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): closing low battery warning: level=100
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
,I/HtcPowerSaver(  909): >> updateStatus
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  909): acquireWL(439e0958): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422615a0: PendingIntentRecord{42230f68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=392699, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(439e0958): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  909): acquireWL(439407d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(439407d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(435797a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422615a0: PendingIntentRecord{42230f68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=452699, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(435797a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  909): acquireWL(43523468): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43523468): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  909): acquireWL(4345ff70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422615a0: PendingIntentRecord{42230f68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=512699, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4345ff70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  909): acquireWL(42deb370): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42deb370): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(42877fb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422615a0: PendingIntentRecord{42230f68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=572699, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42877fb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42697a28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42697a28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(41e42a80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(41e42a80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  909): BroadcastReceiver::onReceive-
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  352): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1241): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1241): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1241): sku_id=99
D/ContactMessageStore( 1241): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1241): start background delete task...
D/ContactMessageStore( 1241): size: 0 , 0
,D/ContactMessageStore( 1241): Background delete complete
,D/PMS     (  909): acquireWL(42415300): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422615a0: PendingIntentRecord{42230f68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=632700, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42415300): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42875950): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42875950): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(43a4ff48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
D/PMS     (  909): releaseWL(43a4ff48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(426a5ef8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
V/AlarmManager(  909): sending alarm PendingIntent{422615a0: PendingIntentRecord{42230f68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=692700, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(426a5ef8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43b7f0a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(43b7f0a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(427cb270): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(427cb270): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(42831ae8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422615a0: PendingIntentRecord{42230f68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=752699, Int=0
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42831ae8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43e711e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43e711e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(427cc170): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(427cc170): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(427211b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
V/AlarmManager(  909): sending alarm PendingIntent{422615a0: PendingIntentRecord{42230f68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=812700, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false),
,I/dalvikvm-heap( 1273): Grow heap (frag case) to 12.650MB for 50416-byte allocation
D/PMS     (  909): releaseWL(427211b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(425531a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(425531a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43a3fb70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(43a3fb70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(427127a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422615a0: PendingIntentRecord{42230f68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=872700, Int=0
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(427127a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42697628): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42697628): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43d289f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422615a0: PendingIntentRecord{42230f68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=932700, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43d289f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(428df2d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(428df2d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(427f9f28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422615a0: PendingIntentRecord{42230f68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=992700, Int=0
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(427f9f28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  909): Sampling interval elapsed, updating statistics ..
,D/PMS     (  909): acquireWL(428b2e10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{41fea6d0: PendingIntentRecord{426ca118 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=787416, Int=0
,D/ConnectivityService(  909): Done.
,D/ConnectivityService(  909): Setting timer for 720seconds
,I/ActivityManager(  909): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=5043 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  909): sending alarm PendingIntent{41e5e900: PendingIntentRecord{428e04b0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1450738978876, Int=10800000
,V/AlarmManager(  909): sending alarm PendingIntent{4283f568: PendingIntentRecord{427c4970 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450739699229, Int=900000
,V/AlarmManager(  909): sending alarm PendingIntent{42943570: PendingIntentRecord{43e1b1b8 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450739774186, Int=0
,W/ContextImpl( 4827): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4827): call getInstance()
,D/SmartSyncUtils( 4827): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4827): MY_DEBUG = false
D/PMS     (  909): acquireWL(4430e6b8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4827 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4827): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4827): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/PMS     (  909): releaseWL(428b2e10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/SmartSyncScreenOnOffTimeReceiver( 4827): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4827): SettingOnTime = 1450764000000, randomSettingOnTime = 1450763453000
D/SmartSyncScreenOnOffTimeReceiver( 4827): SettingOffTime = 1450749600000, randomSettingOffTime = 1450753853000
D/SmartSyncScreenOnOffTimeReceiver( 4827): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4827): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 4827): bNightModeTurnOffOnce = false
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,D/PMS     (  909): releaseWL(4430e6b8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.aurora (5043/10049)
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023757
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023939
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024057
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024063
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024065
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024073
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025588
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025610
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029133
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,D/Process (  909): killProcessQuiet, pid=4594
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4594:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 4594
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  909): acquireWL(439452d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(439452d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
,I/HtcPowerSaver(  909): >> updateStatus
D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43b825c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  909): sending alarm PendingIntent{42c06e60: PendingIntentRecord{43672428 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1010032, Int=0
,D/PMS     (  909): acquireWL(434731c8): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(434731c8): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(43b825c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(435aeac0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1358/10029)
,D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1358/10029)
D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  909): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1358/10029)
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023757
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023939
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024057
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024063
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024065
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024073
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025588
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025610
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029133
,D/PMS     (  909): releaseWL(435aeac0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  909): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=32 [74][24][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/PMS     (  909): acquireWL(43a2f800): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): releaseWL(43a2f800): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43b775e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422615a0: PendingIntentRecord{42230f68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1052699, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43b775e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42c2bda0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42c2bda0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(42e47d30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
D/PMS     (  909): releaseWL(42e47d30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43c04f38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422615a0: PendingIntentRecord{42230f68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1112700, Int=0
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43c04f38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43906510): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
I/BatteryService(  909): n_update end
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/PMS     (  909): releaseWL(43906510): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(435849b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
D/PMS     (  909): releaseWL(435849b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
,I/HtcPowerSaver(  909): >> updateStatus
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(44265738): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422615a0: PendingIntentRecord{42230f68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1172699, Int=0
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(44265738): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(4312d718): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PMS     (  909): releaseWL(4312d718): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(435dead0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  909): releaseWL(435dead0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  352): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  909): acquireWL(42dd51d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422615a0: PendingIntentRecord{42230f68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1232700, Int=0
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42dd51d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43d38828): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/PMS     (  909): releaseWL(43d38828): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(433b0b48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(433b0b48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(44459cc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422615a0: PendingIntentRecord{42230f68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1292700, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(44459cc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(44337430): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
D/PMS     (  909): releaseWL(44337430): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
,D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(442e6d30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
D/PMS     (  909): releaseWL(442e6d30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(442d9b20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422615a0: PendingIntentRecord{42230f68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1352700, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(442d9b20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(442d5528): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(442d5528): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(442ccc68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
I/BatteryService(  909): n_update end
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): releaseWL(442ccc68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(4428def0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422615a0: PendingIntentRecord{42230f68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1412700, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4428def0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(4428dc00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(4428dc00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,D/PowerUI ( 1117): closing low battery warning: level=100
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43e797d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43e797d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
,I/HtcPowerSaver(  909): >> updateStatus
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43e02400): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
V/AlarmManager(  909): sending alarm PendingIntent{422615a0: PendingIntentRecord{42230f68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1472700, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1273): Grow heap (frag case) to 12.650MB for 50416-byte allocation
,D/PMS     (  909): releaseWL(43e02400): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43d5acb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43d5acb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PMS     (  909): runPSCheck
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43bfa690): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(43bfa690): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43b10f70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422615a0: PendingIntentRecord{42230f68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1532699, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43b10f70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43ab46c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43ab46c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43a5c0c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(43a5c0c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
,I/HtcPowerSaver(  909): >> updateStatus
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43a53360): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422615a0: PendingIntentRecord{42230f68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1592699, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43a53360): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43a53180): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
,D/PMS     (  909): releaseWL(43a53180): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/PowerUI ( 1117): closing low battery warning: level=100
D/HtcPowerSaver(  909): Checking...
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43a3e360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): releaseWL(43a3e360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(43946268): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422615a0: PendingIntentRecord{42230f68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1652699, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(43946268): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(43945f88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(43945f88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(428b3710): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(428b3710): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(426ffc60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422615a0: PendingIntentRecord{42230f68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1712699, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(426ffc60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(4204da70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(4204da70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(4266bf98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(4266bf98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(42657c00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422615a0: PendingIntentRecord{42230f68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1772699, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42657c00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(41f94d20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(41f94d20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,D/PMS     (  909): acquireWL(428a5150): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): releaseWL(428a5150): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  352): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  909): acquireWL(42debeb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422615a0: PendingIntentRecord{42230f68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1832700, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
I/ProcessStatsService(  909): Prepared write state in 39ms
,I/ProcessStatsService(  909): Pruning old procstats: /data/system/procstats/state-2015-12-21-01-31-22.bin
,D/PMS     (  909): releaseWL(42debeb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(4278e950): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): releaseWL(4278e950): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(428b3390): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(428b3390): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(42948008): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{422615a0: PendingIntentRecord{42230f68 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1892700, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42948008): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 5096): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 5096): ====startRecUseTime====
D/htc.customization.log.level( 5096):  is 
W/CustomizationLogLevel( 5096): Level value is invalid, use default level 2
D/CustomizationManager( 5096):  Read ACC file spent 0.111 (s)
D/CIDMapFileReader( 5096): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5096): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5096): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5096): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 5096): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5096): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 5096): Parsing tag item name = HTC__016
D/CIDMapFileReader( 5096): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5096): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5096): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5096): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 5096): Parsing tag category name = system
I/CustomizationCIDLoader( 5096): Parsing tag category name = application
I/CustomizationCIDLoader( 5096): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5096): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5096): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5096): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5096): Parsing tag category name = Settings
D/CustomizationManager( 5096):  Read CID file spent 0.167 (s)
D/CustomizationManager( 5096):  All configurations done spent 0.167 (s)
W/HtcNativeFlag( 5096): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 5096): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 5096): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 5096): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  909): deletePackageAsUser: pkg=com.test.thalitest, pid=5096, uid=2000 user=0
I/ActivityManager(  909): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  909): killProcessQuiet, pid=4756
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  909): killProcessQuiet, pid=4742
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  909): Killing 4756:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1802s
I/ActivityManager(  909): Killing 4742:com.android.chrome/u0a96 (adj 15): empty for 1802s
D/Process (  909): killProcessQuiet, pid=4725
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
D/Process (  909): killProcessQuiet, pid=4497
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  909): Killing 4725:com.google.android.setupwizard/u0a79 (adj 15): empty for 1802s
I/ActivityManager(  909): Killing 4497:com.google.android.music:main/u0a154 (adj 15): empty for 1802s
I/ActivityManager(  909): Recipient 4725
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Recipient 4497
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  909): Client com.google.android.music (pid 4497): Died!
I/ActivityManager(  909): Recipient 4742
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/asset   (  909): Copying FileAsset 0x67582d70 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
W/PackageSettings(  909): Skipping PackageSetting{423e1f98 com.example.hello/10397} due to missing metadata
I/ActivityManager(  909): Recipient 4756
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.test.thalitest
D/DotMatrix( 1558): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1558): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1558): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1223): Ignoring removeGeofence because network location is disabled.
D/AccTypeManager( 1344): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PMS     (  909): acquireWL(443c9a40): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(443c9a40): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "sms"
I/Launcher( 1273): Deferring update until onResume
D/Launcher( 1273): waitUntilResume // bindAppsRemoved
D/VoicemailCleanupService( 1300): Cleaning up data for package: com.test.thalitest
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "smsto"
W/AccTypeManager( 1344): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1344): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mms"
W/SystemReader( 1256): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mmsto"
I/[PluginManager]RegisterService( 4708): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/[PluginManager]RegisterService( 4708): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1273): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "sms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "smsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/IcingCorporaProvider( 2826): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/InputMethodManagerService(  909): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
E/ExternalAccountType( 1344): Unsupported attribute readOnly
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/ActivityManager(  909): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5110 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  909):   Scheme: "mmsto"
D/PhoneApp( 1241): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  909): acquireWL(4428dc00): PARTIAL_WAKE_LOCK  Icing 0x1 4106 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(4428dc00): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): acquireWL(44285fa8): PARTIAL_WAKE_LOCK  Icing 0x1 4106 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2826): UpdateCorporaTask done [took 317 ms] updated apps [took 317 ms] 
D/PMS     (  909): acquireWL(43e1b4b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
D/PMS     (  909): releaseWL(43e1b4b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
W/PackageManager(  909): Unable to load service info ResolveInfo{421f74c8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
E/SQLiteDatabase( 5110): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 5110): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5110): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5110): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5110): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5110): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5110): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5110): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5110): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5110): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5110): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5110): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5110): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5110): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5110): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5110): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 5110): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 5110): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 5110): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 5110): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 5110): threadid=11: thread exiting with uncaught exception (group=0x41906e30)
E/ActivityManager(  909): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 5110): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 5110): Process: com.google.android.apps.docs, PID: 5110
E/AndroidRuntime( 5110): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5110): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5110): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5110): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5110): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5110): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5110): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5110): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5110): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5110): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5110): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5110): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5110): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5110): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5110): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 5110): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 5110): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 5110): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 5110): 	at aho.run(AbstractDatabaseInstance.java:455)
D/Process ( 5110): killProcess, pid=5110
D/Process ( 5110): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  909): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5128 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
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
D/RemoteDisplayProvider(  909): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  909): start
I/ActivityManager(  909): Recipient 5110
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Process com.google.android.apps.docs (pid 5110) has died.
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1558): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
W/AtomicFile(  909): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
W/AppWidgetServiceImpl(  909): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
W/ContextImpl( 5128): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 5128): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5128): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5128): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5128): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5128): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5128): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5128): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5128): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5128): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5128): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5128): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5128): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5128): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5128): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5128): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5128): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 5128): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 5128): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5128): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5128): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5128): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 5128): threadid=10: thread exiting with uncaught exception (group=0x41906e30)
E/ActivityManager(  909): App crashed! Process: com.android.keychain
I/ActivityManager(  909): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=5142 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/AndroidRuntime( 5128): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5128): Process: com.android.keychain, PID: 5128
E/AndroidRuntime( 5128): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5128): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5128): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5128): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5128): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5128): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5128): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5128): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5128): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5128): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5128): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5128): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5128): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5128): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5128): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 5128): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 5128): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5128): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5128): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5128): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  909): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 5128): killProcess, pid=5128
D/Process ( 5128): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
E/ErrorReport(  909): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  909): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1450740678114.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  909): Recipient 5128
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Process com.android.keychain (pid 5128) has died.
W/ActivityManager(  909): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/AppTag  ( 5142): getInstance(Context context)
D/AppTag  ( 5142): getInstance(Context context)
D/AppTag  ( 5142): onCreate()
D/PMS     (  909): acquireWL(4284ab08): PARTIAL_WAKE_LOCK  AsyncService 0x1 4155 10160 null
D/PMS     (  909): releaseWL(4284ab08): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/dalvikvm( 4181): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 4106): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 4106): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 4106): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4106): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 4106): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4106): Module APK com.google.android.play.games already loaded
I/ActivityManager(  909): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
I/LocationSettingsChecker( 4106): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 4106): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 4106): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6539e008
W/dalvikvm( 4106): threadid=28: thread exiting with uncaught exception (group=0x41906e30)
E/AndroidRuntime( 4106): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 4106): Process: com.google.android.gms, PID: 4106
E/AndroidRuntime( 4106): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4106): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 4106): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 4106): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 4106): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 4106): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 4106): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 4106): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 4106): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 4106): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 4106): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 4106): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 4106): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 4106): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 4106): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 4106): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 4106): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 4106): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 4106): 	at java.lang.Thread.run(Thread.java:864)
E/ActivityManager(  909): App crashed! Process: com.google.android.gms
D/Process ( 4106): killProcess, pid=4106
E/SQLiteDatabase( 4106): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 4106): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4106): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4106): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4106): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4106): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4106): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4106): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4106): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4106): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4106): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4106): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4106): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4106): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4106): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4106): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 4106): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 4106): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 4106): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 4106): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4106): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4106): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4106): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 4106): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  909): Can't write: system_app_crash
E/DropBoxManagerService(  909): java.io.FileNotFoundException: /data/system/dropbox/drop145.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  909): Recipient 4106
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Process com.google.android.gms (pid 4106) has died.
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
D/PMS     (  909): handleWLDeath(44285fa8): PARTIAL_WAKE_LOCK  Icing 0x1
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 11000ms
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 11000ms
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 21000ms
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 20999ms
D/WifiService(  909): Client connection lost with reason: 4
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20999ms
I/ActivityManager(  909): Resuming delayed broadcast
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20997ms
E/SQLiteLog( 1358): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1358): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x63f7e208
W/dalvikvm( 1358): threadid=1: thread exiting with uncaught exception (group=0x41906e30)
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
E/ActivityManager(  909): App crashed! Process: com.google.process.gapps
E/DropBoxManagerService(  909): Can't write: system_app_crash
E/DropBoxManagerService(  909): java.io.FileNotFoundException: /data/system/dropbox/drop146.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 1358): killProcess, pid=1358
D/Process ( 1358): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  909): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5172 uid=10098 gids={50098, 3003, 5012}
D/Process (  909): killProcessQuiet, pid=4852
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  909): Killing 4852:com.google.android.gms.unstable/u0a29 (adj 15): empty for 1800s
I/DeviceManagement( 5172): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=5172 dbg=false s=true
I/DeviceManagement( 5172): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 5172): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 5172): WorkflowService: Starting workflow service
I/DeviceManagement( 5172): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41d62e48] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 5172): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5172): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 5172): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5172): ModelRegistry: Loading model meta data from resources...
I/DeviceManagement( 5172): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 5172): SessionStateController: Checking invariants...
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/ActivityManager(  909): Recipient 1358
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  909): Client connection lost with reason: 4
I/ActivityManager(  909): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5186 uid=10099 gids={50099, 3003, 5012}
I/ActivityManager(  909): Process com.google.process.gapps (pid 1358) has died.
W/ActivityManager(  909): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20827ms
I/Prism.ItemManager( 1273): loadItems() com.htc.launcher.pageview.WidgetManager@41dc9c70 +
I/Prism.WidgetManager( 1273): onLoadItems() +
I/ActivityManager(  909): Recipient 4852
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Documents( 5186): Loading roots for com.android.providers.downloads.documents
D/Documents( 5186): Loading roots for com.android.externalstorage.documents
E/SQLiteDatabase( 5186): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 5186): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5186): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5186): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5186): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5186): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5186): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5186): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5186): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5186): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5186): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5186): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5186): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5186): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5186): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5186): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 5186): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 5186): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 5186): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 5186): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 5186): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 5186): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 5186): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 5186): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5186): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5186): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5186): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5186): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5186): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5186): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5186): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 5186): threadid=1: thread exiting with uncaught exception (group=0x41906e30)
E/AndroidRuntime( 5186): FATAL EXCEPTION: main
E/AndroidRuntime( 5186): Process: com.android.documentsui, PID: 5186
E/AndroidRuntime( 5186): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5186): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 5186): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 5186): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 5186): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5186): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5186): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 5186): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 5186): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 5186): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 5186): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 5186): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 5186): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5186): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5186): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5186): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5186): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5186): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5186): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5186): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5186): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5186): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5186): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5186): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5186): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5186): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5186): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 5186): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 5186): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 5186): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 5186): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 5186): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 5186): 	... 10 more
I/ActivityManager(  909): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=5200 uid=10023 gids={50023, 1028, 1015, 1023}
E/ActivityManager(  909): App crashed! Process: com.android.documentsui
I/ActivityManager(  909): Start proc com.google.android.gms for broadcast com.google.android.gms/.nearby.settings.NearbyAppUninstallReceiver: pid=5212 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
D/ErrorReport(  909): HtcErrorReportManager Begin---add error logs to dropbox
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
D/Process ( 5186): killProcess, pid=5186
D/Process ( 5186): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  909): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  909): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1450740678834.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  909): Recipient 5186
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ExternalStorage( 5200): After updating volumes, found 1 active roots
I/ActivityManager(  909): Process com.android.documentsui (pid 5186) has died.
E/SQLiteDatabase( 5172): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 5172): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5172): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5172): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5172): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5172): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5172): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5172): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5172): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5172): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5172): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5172): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5172): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5172): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5172): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5172): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 5172): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 5172): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 5172): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 5172): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 5172): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 5172): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 5172): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 5172): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 5172): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 5172): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 5172): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 5172): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 5172): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 5172): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 5172): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 5172): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 5172): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 5172): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 5172): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 5172): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 5172): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 5172): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel.java:176)
E/SQLiteDatabase( 5172): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 5172): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 5172): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5172): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5172): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5172): 	at java.lang.Thread.run(Thread.java:864)
I/DeviceManagement( 5172): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 5172): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 5172): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
E/SQLiteDatabase( 5172): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 5172): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5172): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5172): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5172): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5172): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5172): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5172): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5172): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5172): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5172): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5172): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5172): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5172): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5172): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5172): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 5172): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 5172): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 5172): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 5172): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 5172): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 5172): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 5172): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 5172): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 5172): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 5172): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 5172): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 5172): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
E/SQLiteDatabase( 5172): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
E/SQLiteDatabase( 5172): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 5172): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 5172): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5172): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5172): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5172): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DeviceManagement( 5172): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@41d62e48]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/DeviceManagement( 5172): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/DeviceManagement( 5172): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/DeviceManagement( 5172): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/DeviceManagement( 5172): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/DeviceManagement( 5172): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/DeviceManagement( 5172): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/DeviceManagement( 5172): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/DeviceManagement( 5172): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/DeviceManagement( 5172): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/DeviceManagement( 5172): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
W/DeviceManagement( 5172): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
W/DeviceManagement( 5172): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/DeviceManagement( 5172): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/DeviceManagement( 5172): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
W/DeviceManagement( 5172): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 5172): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 5172): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 5172): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 5172): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 5172): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 5172): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 5172): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 5172): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 5172): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 5172): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 5172): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 5172): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 5172): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 5172): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 5172): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 5172): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 5172): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 5172): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/DeviceManagement( 5172): WorkflowServ,ice: Stopping workflow service
W/dalvikvm( 5212): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
W/dalvikvm( 5212): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 5212): VM with version 1.6.0 does not have multidex support
I/MultiDex( 5212): install
I/MultiDex( 5212): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
I/MultiDex( 5212): loading existing secondary dex files
I/MultiDex( 5212): load found 3 secondary dex files
I/MultiDex( 5212): install done

```
