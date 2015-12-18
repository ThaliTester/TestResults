#### Test 50650278d76d9c3_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
V/LightsService(  910): setLight #0: color=#24
V/LightsService(  910): setLight #0: color=#21
,V/LightsService(  910): setLight #0: color=#1a
V/LightsService(  910): setLight #0: color=#14
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -61 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  910):    returned true
E/cutils-trace( 4362): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4362): ====startRecUseTime====
D/htc.customization.log.level( 4362):  is 
W/CustomizationLogLevel( 4362): Level value is invalid, use default level 2
D/CustomizationManager( 4362):  Read ACC file spent 0.066 (s)
D/CIDMapFileReader( 4362): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4362): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4362): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4362): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4362): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4362): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4362): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4362): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4362): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4362): Parsing tag item name = HTC__031
I/SensorManager(  910): mEventCount = 900
V/CustomizationCIDLoader( 4362): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4362): Parsing tag category name = system
I/CustomizationCIDLoader( 4362): Parsing tag category name = application
I/CustomizationCIDLoader( 4362): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4362): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4362): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4362): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4362): Parsing tag category name = Settings
D/CustomizationManager( 4362):  Read CID file spent 0.106 (s)
D/CustomizationManager( 4362):  All configurations done spent 0.107 (s)
W/HtcNativeFlag( 4362): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4362): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4362): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4362): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  910): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  910): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  910): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  910): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  910): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  910): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  910): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4362
D/PMS     (  910): acquireHCC(43d8e400): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 910 1000 null
D/PMS     (  910): acquireHCC(42f878c8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 910 1000 null
W/asset   (  910): Copying FileAsset 0x69f1edf8 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  910): @test_code: getHtcIntentFlag: 0 obj: 1114448256
I/FeedHostManager( 1272): [onPause]
I/FeedProviderManager( 1272): onPause
I/FeedHostManager( 1272): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@424a2438
I/SocialFeedProvider( 1272): +onPause
I/SocialFeedProvider( 1272): -onPause
D/PMS     (  910): acquireWL(42e25760): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 910 1000 null
I/ActivityManager(  910): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4373 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1272): [trimMemory] 20
W/asset   ( 4373): Copying FileAsset 0x5c77c970 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4373): Binding Chromium to main looper Looper (main, tid 1) {423ea218}
I/LibraryLoader( 4373): Expected native library version number "",actual native library version number ""
I/chromium( 4373): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4373): Initializing chromium process, renderers=0
D/PMS     (  910): acquireWL(42f50c88): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  910): acquireWL(42efd948): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  910): java.lang.Throwable: stack dump
D/BluetoothManagerService(  910): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42e1a0c8:true
W/System.err(  910): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  910): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  910): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  910): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  910): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4373): 1111489616: getState(). Returning 12
D/PMS     (  910): releaseWL(42efd948): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4373): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4373): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4373): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4373): Local Branch: 
I/Adreno-EGL( 4373): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4373): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4373):                  aa63bbd948f41d15fc72f585e
W/chromium( 4373): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4373): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4373): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4373): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4373): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4373): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4373): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4373): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4373): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4373): CordovaWebView is running on device made by: HTC
,W/AwContents( 4373): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  910): Disable input method client, pid=1272
I/ActivityManager(  910): Displayed com.test.thalitest/.MainActivity: +275ms
W/ResourceType( 4373): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4373): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@42431300, mServedView=org.apache.cordova.engine.SystemWebView{423f6f68 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1211): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1211): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1211): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1211): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  910): Enable input method client, pid=4373
W/AwContents( 4373): nativeOnDraw failed; clearing to background color.
D/PMS     (  910): releaseWL(42e25760): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/JsMessageQueue( 4373): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 4373): JniHelper::setJavaVM(0x41fa2010), pthread_self() = 1663392992
D/JX-Cordova( 4373): jxcore cordova android initializing
,I/dalvikvm-heap( 4373): Grow heap (frag case) to 11.600MB for 144892-byte allocation
,I/dalvikvm-heap( 4373): Grow heap (frag case) to 11.716MB for 217334-byte allocation
,I/dalvikvm-heap( 4373): Grow heap (frag case) to 11.892MB for 325996-byte allocation
,I/dalvikvm-heap( 4373): Grow heap (frag case) to 12.166MB for 488990-byte allocation
,I/dalvikvm-heap( 4373): Grow heap (frag case) to 12.573MB for 733480-byte allocation
,I/dalvikvm-heap( 4373): Grow heap (frag case) to 14.020MB for 1650320-byte allocation
,I/dalvikvm-heap( 4373): Grow heap (frag case) to 15.435MB for 2475476-byte allocation
,I/dalvikvm-heap( 4373): Grow heap (frag case) to 17.479MB for 3713210-byte allocation
,W/CpuWake (  910): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  910): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  910): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  910): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  910): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  910): <<release mCpuPerf_Freq wakelock
D/PMS     (  910): releaseHCC(43d8e400): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  910): releaseHCC(42f878c8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4373): Initializing JXcore engine
,W/jxcore-log( 4373): JXcore engine is ready
,W/jxcore-log( 4373): Starting JXcore engine
,W/jxcore-log( 4373): Platform android
W/jxcore-log( 4373): 
,W/jxcore-log( 4373): Process ARCH arm
W/jxcore-log( 4373): 
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -61 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
,I/jxcore-log( 4373): JXcore Cordova bridge is ready!
I/jxcore-log( 4373): 
,W/jxcore-log( 4373): JXcore engine is started
I/chromium( 4373): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/Choreographer( 4373): Skipped 136 frames!  The application may be doing too much work on its main thread.
,D/PMS     (  910): releaseWL(42f50c88): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4373): Toggling radios to true
I/jxcore-log( 4373): 
,D/BluetoothAdapter( 4373): enable(): BT is already enabled..!
,D/WifiManager( 4373): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
W/HtcDLNAServiceManager(  910): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  910): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  910): Settings:Agentvalue: 2
W/Settings:Agent(  910): >> traceCallingStack()
W/Settings:Agent(  910): Process.myPid(): 910
W/Settings:Agent(  910): Process.myTid(): 1379
W/Settings:Agent(  910): Process.myUid(): 1000
W/Settings:Agent(  910): 
W/Settings:Agent(  910): 
,W/System.err(  910): java.lang.Throwable: stack dump
W/System.err(  910): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  910): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  910): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  910): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  910): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  910): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  910): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  910): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  910): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  910): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  910): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  910): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  910): 
W/Settings:Agent(  910): << traceCallingStack(): 1(ms)
,D/WifiManager( 4373): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  910): doBoolean: DISCONNECT
D/WifiManager( 4373): reconnect: Base Package Name=com.test.thalitest, uid=10389
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): TDLS: Tear down peers
,I/wpa_supplicant( 1187): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4373): Radios toggled
I/jxcore-log( 4373): 
,D/BluetoothManagerService(  910): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 4373): Got Device Bluetooth address: B4:CE:F6:AB:A4:6A
I/jxcore-log( 4373): 
D/WifiService(  910): setWifiEnabled: true pid=4373, uid=10389
E/WifiService(  910): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  910): New client listening to asynchronous messages
I/WifiService(  910): isSprintWifiRestricted(): false
I/WifiService(  910): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  910): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
I/jxcore-log( 4373): Perf Test app loaded loaded
I/jxcore-log( 4373): 
I/Choreographer( 4373): Skipped 78 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 4373): check test folder
I/jxcore-log( 4373): 
,I/jxcore-log( 4373): found test : ./testFindPeers.js
I/jxcore-log( 4373): 
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1187): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1187): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1187): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  910): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  910): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  910): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1187): TDLS: Remove peers on disassociation
,D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1187): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1187): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1187): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1187): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8e74bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1187):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1187): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1187): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1187): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1187): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1187): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1187): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1187): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1187): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1187): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1187): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1187): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1187): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1187): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1187): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1187): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1187): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1187): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1187): Wireless event: cmd=0x8b15 len=20
D/wpa_sup,plicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1187): nl80211: Ignore disconnect event triggered during reassociation
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiNative-wlan0(  910):    returned true
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/WifiPerfLock(  910): release()
D/WifiStateMachine(  910): PerfLock released for exiting ConnectedState
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
,D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): Power_Mode_Type mode = 0
I/wpa_supplicant( 1187): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 61
,D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/ConnectivityService(  910): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  910): acquireWL(42c99ed0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 910 1000 null
D/WifiP2pService(  910): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  910): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  910):    returned true
I/jxcore-log( 4373): found test : ./testSendData.js
I/jxcore-log( 4373): 
D/DhcpStateMachine(  910): [RunningState] Stop DHCP
D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  910): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  910): doBoolean: RECONNECT
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): Fast associate: Old scan results
I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1187): nl80211: Event message available
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  910): stopDataStallAlarm: current tag=20072 mDataStallAlarmIntent=PendingIntent{42df73b0: PendingIntentRecord{42ed2310 android broadcastIntent}}
,D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): Enter handleNetworkDisconnect
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): Power_Mode_Type mode = 0
I/wpa_supplicant( 1187): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/UsbnetStateTracker(  910): isAvailable+-
D/UsbnetStateTracker(  910): reconnect
D/UsbnetStateTracker(  910): isAvailable+-
D/WifiNative-wlan0(  910):    returned true
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  910): Provision feature enable=false
D/ConnectivityService(  910): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/MDST    (  910): default: reconnect()
D/MDST    (  910): default: setTeardownRequested(false)
D/MDST    (  910): default: setEnableApn apnType =default , enable=true
D/WifiP2pService(  910): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  910): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  910): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  910): Exit handleNetworkDisconnect
,D/WISPrService( 3752): >>>>>WISPrService start isConnected = false<<<<<
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  910): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '29 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 29 Failed to remove route from default table (No such process)'
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  910): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
,V/NativeCrypto( 1359): Read error: ssl=0x64231f98: I/O error during system call, Connection timed out
,D/WISPrService( 3752): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiService(  910): New client listening to asynchronous messages
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): handleConnectivityChange: resetting
D/ConnectivityService(  910): resetConnections(wlan0, 3)
D/WISPrService( 3752): >>>>>WISPrService start isConnected = false<<<<<
,V/NativeCrypto( 1359): SSL shutdown failed: ssl=0x64231f98: I/O error during system call, Broken pipe
,D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/libc    (  363): [NET] entry_id:3   entry:0xb8748db8  removed 
D/libc    (  363): [NET] entry_id:4   entry:0xb8748c88  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb8748f70  removed 
D/libc    (  363): [NET] entry_id:5   entry:0xb873fc20  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb8744458  removed 
D/libc    (  363): [NET] entry_id:6   entry:0xb87442d8  removed 
,D/libc    (  363): *************************,
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
D/PMS     (  910): acquireWL(449519a8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  910): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  910): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  910): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  910): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/WISPrService( 3752): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WirelessDisplayService(  910): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  910): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WifiStateMachine(  910): startScan Pid: 910 Uid 1000
D/WifiNative-wlan0(  910): doBoolean: SCAN
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  910):    returned false
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
D/PMS     (  910): acquireWL(42f3ddb8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/ConnectivityService(  910): reportInetCondition for net -1, percentage: 0 by  (1359/10029)
D/BatSI   (  910): WIFI scan started for: 650a0300 uid:1000
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/PMS     (  910): releaseWL(449519a8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): mActiveDefaultNetwork: -1
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): handleInetConditionChange: no active default network - ignore
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
,D/PMS     (  910): releaseWL(42f3ddb8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/chromium( 4373): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  910): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  910): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  910): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4424 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
D/GpsLocationProvider(  910): [handleMessage] UPDATE_NETWORK_STATE
D/CaptivePortalTracker(  910): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/CaptivePortalTracker(  910): NoActiveNetworkState
D/GpsLocationProvider(  910): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  910): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  910): ignore wifi update if we are not in OPENING or CLOSING
D/Tethering(  910): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  910): bSetPropertyMultiRAB:false
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(44334808): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/PMS     (  910): releaseWL(44334808): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1601/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (4221/10100)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.launcher (1272/10076)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/Tethering(  910): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
I/Tethering(  910): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
I/Tethering(  910): ipv4Default null
,I/Tethering(  910): No IPv4 upstream interface, giving up.
,D/Tethering(  910): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.docs (4221/10100)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
,I/ConnectivityHelper( 1272): [onReceive] WIFI(1): DISCONNECTED
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
,I/MusicStore( 4424): Database version: 95
,W/ContextImpl( 4424): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4424): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4424): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4424): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4424): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4424, uid=10154, userID:0
,D/WifiDisplayAdapter(  910): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  910):     Client/Owner: Client
D/WifiDisplayAdapter(  910):     GroupId: 
D/WifiDisplayAdapter(  910):     Passphrase: 
D/WifiDisplayAdapter(  910):     SessionId: 0
D/WifiDisplayAdapter(  910):     IP Address: }
,D/MediaRouterService(  910): Client com.google.android.music (pid 4424): Registered
,I/MediaRouter( 4424): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  910): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  910):     Client/Owner: Client
D/WifiDisplayAdapter(  910):     GroupId: 
D/WifiDisplayAdapter(  910):     Passphrase: 
D/WifiDisplayAdapter(  910):     SessionId: 0
D/WifiDisplayAdapter(  910):     IP Address: }
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.music (4424/10154)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (2712/10021)
,I/ActivityManager(  910): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4444 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4424): getSelectedRoute
,D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.google.android.music (4424/10154)
I/NetworkMonitor( 4424): type=WIFI subType= reason=null isConnected=false
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4424, uid=10154, userID:0
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(42f6ada0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/PMS     (  910): releaseWL(42f6ada0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/Process (  910): killProcessQuiet, pid=4155
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4155:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4155
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ACRA    ( 4444): ACRA is enabled for com.facebook.katana, intializing...
D/WifiService(  910): Client connection lost with reason: 4
,D/ACRA    ( 4444): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4444): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4444): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4444): Preparing secondary program dexes.
V/DexLibLoader( 4444): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4444): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4444): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4444): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4444): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4444): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4444): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4444): Dex already copied
D/OdexVerifier( 4444): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4444): Creating class loader
,V/DexLibLoader( 4444): Finished creating class loader
V/DexLibLoader( 4444): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4444): Dex already copied
D/OdexVerifier( 4444): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4444): Creating class loader
,V/DexLibLoader( 4444): Finished creating class loader
,V/DexLibLoader( 4444): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4444): Dex already copied
D/OdexVerifier( 4444): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4444): Creating class loader
,V/DexLibLoader( 4444): Finished creating class loader
V/DexLibLoader( 4444): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4444): Dex already copied
D/OdexVerifier( 4444): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4444): Creating class loader
,V/DexLibLoader( 4444): Finished creating class loader
,V/DexLibLoader( 4444): Verifying classes from secondary dexes.
,D/DexLibLoader( 4444): DexLibLoader.ensureDexLoaded took 22 ms
,I/PMS     (  910): Going to sleep due to screen timeout...
,I/ActivityManager(  910): mThumbnailWidth=360, mThumbnailHeight=640
,I/SensorManager(  910): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42a99aa0
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  910): disable: get sensor name = CM36282 Light sensor
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 2
W/SensorService(  910): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42a99aa0, eanble = 0, strlen(mName) = 59
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  910): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4263e980
W/SensorService(  910): Listener[1] = com.htc.smartdim.sensor_eye@424f33a8
,W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/BatSI   (  910): Couldn't get kernel wake lock stats
V/LightsService(  910): setLight #2: color=#0
D/qdlights(  910): set_light_buttons_func: on=0 brightness=0
V/LightsService(  910): setLight #0: color=#0
,D/WirelessDisplayService(  910): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  910): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  910): mWirelessDisplayManager is null
,W/dalvikvm( 4444): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4444): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4444): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4444): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4444): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4444): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4444): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-61
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-61
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-82
I/wpa_supplicant( 1187): [NULL] fe:94:e3:11:35:3c freq=2462 level=-93
I/wpa_supplicant( 1187): [NULL] fc:94:e3:11:35:3a freq=2462 level=-93
D/wpa_supplicant( 1187): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=7 entropy=0
D/wpa_supplicant( 1187): Add randomness: count=8 entropy=1
D/wpa_supplicant( 1187): Add randomness: count=9 entropy=2
D/wpa_supplicant( 1187): Add randomness: count=10 entropy=3
D/wpa_supplicant( 1187): Add randomness: count=11 entropy=4
D/wpa_supplicant( 1187): Add randomness: count=12 entropy=5
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1187): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-61
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 3
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 1
I/wpa_supplicant( 1187): wpa_s->is_screen_on 1
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): selected network = 1
D/wpa_supplicant( 1187): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8e764e8  current_ssid=0x0
D/wpa_supplicant( 1187): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1187): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1187): TDLS: TDLS is allowed in the target BSS
I/wpa_supplic,ant( 1187): check if in concurrent case
I/wpa_supplicant( 1187): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  910): doString: LIST_DONGLES
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1187): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1187): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1187): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1187): RSN: PMKSA cache search - network_ctx=0xb8e764e8 try_opportunistic=0
D/wpa_supplicant( 1187): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1187): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1187): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1187): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1187): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1187): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1187): nl80211: Unsubscribe mgmt frames handle 0xb8e75718 (mode change)
D/wpa_supplicant( 1187): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8e75718
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718,
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Connect (ifindex=22),
D/wpa_supplicant( 1187):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1187):   * freq=2412
D/wpa_supplicant( 1187):   * Auth Type 0
D/wpa_supplicant( 1187):   * WPA Versions 0x2
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1187): nl80211: Connect request send successfully
D/wpa_supplicant( 1187): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  910): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1187): reply (755) for get BSS: id=0
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-51
I/wpa_supplicant( 1187): tsf=0000000105141144
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
,I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-61
I/wpa_supplicant( 1187): tsf=0000000105141161
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=2
I/wpa_supplicant( 1187): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-61
,I/wpa_supplicant( 1187): tsf=0000000105141157
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1187): ssid=01ABC
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=3
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2427
I/wpa_supplicant( 1187): level=-82
I/wpa_supplicant( 1187): tsf=0000000105141164
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=4
I/wpa_supplicant( 1187): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1187): freq=2462
I/wpa_supplicant( 1187): level=-93
I/wpa_supplicant( 1187): tsf=0000000105141168
I/wpa_supplicant( 1187): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=UPC Wi-Free
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=5
I/wpa_supplicant( 1187): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1187): freq=2462
I/wpa_supplicant( 1187): level=-93
I/wpa_supplicant( 1187): tsf=0000000105141172
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=UPC0039325
I/wpa_supplicant( 1187): ####
,D/WirelessDisplayService(  910): getDiscoveryDongleList
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/WifiStateMachine(  910): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 5220, timestamp: 105141144, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -61, frequency: 2412, timestamp: 105141161, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -61, frequency: 2412, timestamp: 105141157, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): == begin of scan result ==
D/WifiStateMachine(  910): == (6) end of scan result ==
,D/WifiManager( 1223): getScanResults enter 
,D/WirelessDisplayService(  910): getDiscoveryDongleList
D/WifiStateMachine(  910): == begin of scan result ==
,D/WifiStateMachine(  910): == (6) end of scan result ==
,D/WifiStateMachine(  910): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2427, timestamp: 105141164, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 4: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -93, frequency: 2462, timestamp: 105141168, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 5: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -93, frequency: 2462, timestamp: 105141172, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): add 6 to mScanResults
D/BatSI   (  910): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  910): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/wpa_supplicant( 1187): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
,D/wpa_supplicant( 1187): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1187): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1187): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1187): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1187): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1187): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1187): nl80211: Connect event
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1187): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1187): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1187): Add randomness: count=13 entropy=6
I/wpa_supplicant( 1187): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1187): TDLS: Remove peers on association
D/wpa_supplicant( 1187): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1187): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1187): EAPOL: enable timer tick
D/wpa_supplicant( 1187): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1187): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1187): Get randomness: len=32 entropy=7
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
,D/WifiMonitor(  910): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  910): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  910): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  910): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  910): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  910): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 1187): htc_wext_set_keepalive +
,I/wpa_supplicant( 1187): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1187): getPrivFuncNum +	
I/wpa_supplicant( 1187): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1187): htc_wext_set_keepalive fnum = 0x8bf6
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  910): Enter handleAssociatedWithEvent
D/WifiStateMachine(  910): Associated
I/wpa_supplicant( 1187): htc_wext_set_keepalive - ret = 0
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  910): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  910): Exit handleAssociatedWithEvent
D/WifiStateMachine(  910): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  910): updateConnectedAP...,
D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/WifiStateMachine(  910): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/Tethering(  910): interfaceLinkStateChanged wlan0, true
,D/Tethering(  910): interfaceStatusChanged wlan0, true
D/WifiApDatabaseHandler(  910): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  910): This record is existed, only update it...
D/Tethering(  910): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
,I/wpa_supplicant( 1187): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb8e759f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1187):    addr=c0:ff:d4:d3:aa:48
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1187): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1187): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f13b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1187):    broadcast key
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1187): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1187): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1187): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1187): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  910): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1187): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1187): set send_ind_to_ndc = 0
,I/wpa_supplicant( 1187): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1187): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1187): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1187): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1187): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1187): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1187): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1187): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1187): EAPOL authentication completed successfully
I/wpa_supplicant( 1187): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 79
,D/wpa_supplicant( 1187): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1187): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1187): nl80211: if_removed already cleared - ignore event
D/Tethering(  910): interfaceLinkStateChanged wlan0, true
D/Tethering(  910): interfaceStatusChanged wlan0, true
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/SurfaceControl(  910): Excessive delay in blankDisplay() while turning screen off: 310ms
D/PMS     (  910): nativeSetInteractive:false
D/PMS     (  910): nativeSetInteractive:false done
D/PMS     (  910): nativeSetAutoSuspend:true
D/PMS     (  910): nativeSetAutoSuspend:true done
D/HABCtrl (  910): TPE algorithm. remove timeout.
D/PMS     (  910): OOBE c monitor 11
I/InputManager(  910): Cancel all due to getting PMS screen off broadcast
,V/KeyguardServiceDelegate(  910): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@43a16428)
,V/KeyguardServiceDelegate(  910): **** SHOWN CALLED ****
D/NfcService( 1256): ScreenObserver: OFF
,D/NfcService( 1256): applyRouting - 0
D/PMN     (  910): wakingUp
I/WindowManager(  910): No lock screen! windowToken=null
D/PMN     (  910): onScreenOn
I/InputMethodManagerService(  910): screenObserver, isScreenOn=false
I/InputMethodManagerService(  910): Disable input method client, pid=4373
,I/IntentController( 1117): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/NfcService( 1256): applyRouting -2
W/ResourceType( 4373): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4373): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{423f6f68 VFEDH.C. .F...... 0,0-720,1134 #64}
D/WirelessDisplayService(  910): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  910): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  910): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  910): acquireWL(43d4a958): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
D/PMS     (  910): releaseWL(43d4a958): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMS     (  910): acquireWL(441bf060): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/NfcService( 1256): applyRouting - 0
,D/MtpService( 2712): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/NfcService( 1256): applyRouting -2
,D/MtpService( 2712): [MTP][onReceive]-
D/PMS     (  910): releaseWL(441bf060): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/AlarmManager(  910): ACTION_SCREEN_ON
I/AlarmManager(  910): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  910): [AlarmQueuing] done recovering
I/AlarmManager(  910): [AlarmQueuing] recover EPS screen off blocked alarms
D/PMS     (  910): acquireWL(42e3b350): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
I/AlarmManager(  910): [AlarmQueuing] done EPS screen off alarm recovering
,W/dalvikvm( 4444): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
D/PMS     (  910): releaseWL(42e3b350): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/WifiStateMachine(  910): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  910): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WirelessDisplayService(  910): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  910): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  910): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  910): onReceive: action=android.intent.action.SCREEN_ON
D/WifiApDatabaseHandler(  910): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/WifiStateMachine(  910): This record is existed, only update it...
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
,I/HtcPowerSaver(  910): >> updateStatus
,I/ClockThread( 1117): stop update clock
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiNative-wlan0(  910): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): SET_SCREEN_ON:On
I/wpa_supplicant( 1187): htc_wext_set_keepalive +
I/wpa_supplicant( 1187): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1187): getPrivFuncNum +	
I/wpa_supplicant( 1187): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1187): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1187): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1187): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1187): htc_wext_set_TX_TRACKING - ret = 0
,D/WifiNative-wlan0(  910):    returned true
,D/WISPrService( 3752): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/WISPrService( 3752): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  910): Provision feature enable=false
D/ConnectivityService(  910): mActiveDefaultNetwork: -1
,V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/WirelessDisplayService(  910): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/NetworkPolicy(  910): updateScreenOn: false
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
D/DhcpStateMachine(  910): [StoppedState] Start DHCP
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -61 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
W/dalvikvm( 4444): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 1
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): Power_Mode_Type mode = 1
I/wpa_supplicant( 1187): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  910):    returned null
E/WifiStateMachine(  910): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/WifiStateMachine(  910): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  910): acquireWL(442bca80): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 910 1000 null
D/WifiStateMachine(  910): handlePreDhcpSetup mBluetoothConnectionActive: false
,D/WifiNative-wlan0(  910):    returned null
D/WifiP2pService(  910): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42ec7a68 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42ec7a68 target=com.android.internal.util.StateMachine$SmHandler }
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
,D/PMS     (  910): acquireWL(44998850): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  910): releaseWL(44998850): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(42f5d838): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1781): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1781): onScreenOn: 1450463648264
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1781): onScreenOn: 1450463648264
D/PMS     (  910): releaseWL(42f5d838): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/SensorManager(  910): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4263e980
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  910): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 2
W/SensorService(  910): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4263e980, eanble = 0, strlen(mName) = 91
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  910): Listener[0] = com.htc.smartdim.sensor_eye@424f33a8
,W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  910): goingToSleep
D/PMS     (  910): acquireWL(44a4b778): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 910 1000 null
,E/FbInjectorInitializer( 4444): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/AlarmManager(  910): ACTION_SCREEN_OFF
I/AlarmManager(  910): [AlarmQueuing] screen off now: 
I/AlarmManager(  910): [AlarmQueuing] data connection: true
,I/AlarmManager(  910): [AlarmQueuing] wifi connection: true
D/WifiDataStallTracker(  910): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  910): stopDataStallAlarm: current tag=20073 mDataStallAlarmIntent=null
,D/WifiNative-wlan0(  910): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): SET_SCREEN_ON:Off
I/wpa_supplicant( 1187): htc_wext_set_keepalive +
I/wpa_supplicant( 1187): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1187): getPrivFuncNum +	
I/wpa_supplicant( 1187): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1187): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1187): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 1187): get_ip_address source addr = 02000000
I/wpa_supplicant( 1187): htc_wext_set_keepalive gateway addr = 00000000
I/wpa_supplicant( 1187): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  910):    returned true
D/PMS     (  910): releaseWL(44a4b778): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/PMS     (  910): acquireWL(444bbc08): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 910 1000 null
,D/PMS     (  910): releaseWL(444bbc08): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,V/SRS_Proc(  371): ParamSet string: screen_state=off
,D/ContactMessageStore( 1238): start background delete task...
D/ContactMessageStore( 1238): size: 0 , 0
,D/ContactMessageStore( 1238): Background delete complete
D/NetworkPolicy(  910): updateScreenOn: false
,D/AutoSetting( 1329): service - mHandler: cancel location update
,D/AutoSetting( 1329): service -           changes count: 0
,D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] getTotalRam: 1873 Mb
D/PMS     (  910): acquireWL(43b25e90): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(43b25e90): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43edb640): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43edb640): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/fb4a(:<default>):StaticBindingVerifier( 4444): Verify
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1781): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1781): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1781): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1781): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1781): onScreenOff
,D/WifiService(  910): New client listening to asynchronous messages
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4444): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4444): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4444): Grow heap (frag case) to 9.511MB for 73240-byte allocation
,D/Process (  910): killProcessQuiet, pid=3790
,I/ActivityManager(  910): Killing 3790:com.htc.mediamanager/u0a34 (adj 15): empty #17
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,I/ActivityManager(  910): Recipient 3790
,D/AutoSetting( 1329): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4492 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1329/10055)
,D/AutoSetting( 1329): Util - no network available!
,D/AutoSetting( 1329): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/AutoSetting( 1329): service - mHandler: cancel location update
,D/AutoSetting( 1329): service -           changes count: 0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1329/10055)
,W/fb4a(:<default>):UserScope( 4444): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4444): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4444): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4492): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4492): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4492): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4492): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  910): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4517 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  910): killProcessQuiet, pid=4056
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  910): Killing 4056:com.google.android.talk/u0a111 (adj 15): empty #17
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4492/10079)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4492/10079)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4492/10079)
,D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  910): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): Power_Mode_Type mode = 0
I/wpa_supplicant( 1187): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/Process (  910): killProcessQuiet, pid=4191
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/WifiP2pService(  910): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/ActivityManager(  910): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4531 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
D/PMS     (  910): releaseWL(442bca80): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
I/ActivityManager(  910): Killing 4191:com.google.android.partnersetup/u0a32 (adj 15): empty #17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [1][0][0]
I/wpa_supplicant( 1187): Change stage from stage0 to stage3
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WiFioffload: SignalStrength: =97
I/ActivityManager(  910): Recipient 4191
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED -1 -> 3
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): gateway: /192.168.1.1
,D/WifiNative-wlan0(  910): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1187): htc_wext_set_keepalive +
I/wpa_supplicant( 1187): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1187): getPrivFuncNum +	
I/wpa_supplicant( 1187): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1187): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1187): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1187): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1187): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  910): VerifyingLinkState enter
D/WifiStateMachine(  910): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  910): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  910): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -60, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
I/ActivityManager(  910): Recipient 4056
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiWatchdogStateMachine(  910): WAN detection
V/NetworkPolicy(  910): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  910): Provision feature enable=false
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED connected
I/dalvikvm-heap( 4444): Grow heap (frag case) to 9.954MB for 84664-byte allocation
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  910): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  910): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  910): default: teardown()
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/MDST    (  910): default: setTeardownRequested(true)
D/MDST    (  910): default: setEnableApn apnType =default , enable=false
D/MDST    (  910): default: setTeardownRequested(true)
D/ConnectivityService(  910): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  910): Unexpected mtu value: android.net.wifi.WifiStateTracker@42d69fc8
,D/ConnectivityService(  910): handleConnectivityChange: netType=1 doReset=false resetMask=0
E/dalvikvm( 4444): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
W/dalvikvm( 4444): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,I/dalvikvm-heap( 4444): Grow heap (frag case) to 9.968MB for 28144-byte allocation
E/dalvikvm( 4444): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 4444): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4444): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 4444): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,I/QuickSettingWifi( 1117): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,E/dalvikvm( 4444): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4444): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4444): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
,E/dalvikvm( 4444): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4444): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4444): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4444): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4444): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4444): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4444): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4444): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4444): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  910): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  910): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  910): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  910): handleConnectivityChange: resetting
D/Nat464Xlat(  910): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  910): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  910): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  910): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  910): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  910): acquireWL(449914f0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4492/10079)
I/dalvikvm-heap( 4444): Grow heap (frag case) to 10.037MB for 39954-byte allocation
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/WirelessDisplayService(  910): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  910):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [3][0][0]
,I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
,I/logwrapper(  363): /system/bin/ip terminated by exit(254)
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,I/dalvikvm-heap( 4444): Grow heap (frag case) to 10.113MB for 79892-byte allocation
,D/ConnectivityService(  910): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  910): releaseWL(449914f0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WISPrService( 3752): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  910): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  910): syncGetConfiguredNetworks
,D/PMS     (  910): acquireWL(44abf2f0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2157 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(44ab9fd8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2157 10029 WorkSource{10029 com.google.android.gms}
,D/wpa_supplicant( 1187): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1187): EAPOL: disable timer tick
,I/CheckinService( 2157): Checkin interval check for package: unspecified last checkin: 1450463597266 min interval config: 0 actual interval: 51828
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/PMS     (  910): releaseWL(44abf2f0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4531): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4531): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
I/CheckinService( 2157): Checking schedule, now: 1450463649106 next: 1450463627225
,I/CheckinService( 2157): active receiver: enabled
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2157, uid=10029, userID:0
,W/GAV2    ( 4531): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,I/dalvikvm-heap( 4444): Grow heap (frag case) to 10.250MB for 75760-byte allocation
,W/ContextImpl( 4531): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
I/CheckinService( 2157): Preparing to send checkin request
,I/EventLogService( 2157): Accumulating logs since 1450463593332
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4531): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42e3c618 u0 ReceiverList{42e226f8 4444 com.facebook.katana/10027/u0 remote:423d8b88}}
,W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42e3c618 u0 ReceiverList{42e226f8 4444 com.facebook.katana/10027/u0 remote:423d8b88}}
,W/BroadcastQueue(  910): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42e07890 u0 ReceiverList{42e19588 4444 com.facebook.katana/10027/u0 remote:42ab8ff8}}
,I/CheckinRequestBuilder( 2157): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  910): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2157): Failed to find provider info for com.google.android.wearable.settings
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): acquireWL(42ce40e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42ce40e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4531/10151)
,V/WebViewChromiumFactoryProvider( 4531): Binding Chromium to main looper Looper (main, tid 1) {423e3790}
,I/LibraryLoader( 4531): Expected native library version number "",actual native library version number ""
,I/chromium( 4531): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4531): Initializing chromium process, renderers=0
,D/PMS     (  910): acquireWL(42971340): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,E/AudioManagerAndroid( 4531): BLUETOOTH permission is missing!
D/PMS     (  910): acquireWL(426ae010): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  910): releaseWL(42971340): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4531): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4531): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4531): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4531): Local Branch: 
I/Adreno-EGL( 4531): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4531): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4531):                  aa63bbd948f41d15fc72f585e
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4444): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  910): getNetworkInfo networkType=9 called by com.google.android.gms (2157/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4444): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4444): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NSApplication( 4531): Starting up...
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4531/10151)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4531/10151)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (3531/10160)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (3531/10160)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/AutoSetting( 1329): receiver - intent: android.intent.action.USER_PRESENT
,D/AutoSetting( 1329): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/TetherSettings( 3752): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3752): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3752): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3752): Cust_ConnectToPC   : spcsc>false
D/        ( 3752): Cust_ConnectToPC   : IPT>true
D/        ( 3752): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3752): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3752): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3752): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3752): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,I/PSReceiver( 3752): onReceive:android.intent.action.USER_PRESENT
W/ContextImpl( 3752): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  910): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4583 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/SmartNS_PSService( 3752): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3752): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3752):  defaultType:0
,I/ActivityManager(  910): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4595 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,W/dalvikvm( 4583): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4583): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4583): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4583): install
,I/MultiDex( 4583): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4583): loading existing secondary dex files
,I/MultiDex( 4583): load found 3 secondary dex files
,I/MultiDex( 4583): install done
,W/dalvikvm( 4583): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4583): VFY: unable to resolve instance field 36
,W/dalvikvm( 4583): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
W/ContextImpl( 4595): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,V/JNIHelp ( 4583): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/SmartSyncUtils( 4595): isEpsOn(), nState = 0
D/PMS     (  910): acquireWL(42eff940): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4595 1000 null
,D/PMS     (  910): releaseWL(42eff940): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4595): getMobilePolicyEnabled, result = true
,D/Process (  910): killProcessQuiet, pid=4221
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4221:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,W/ContextImpl( 4595): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4595): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4595): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4595): isEpsOn(), nState = 0
D/WifiService(  910): New client listening to asynchronous messages
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  910): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@424f33a8
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  910): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 1
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@424f33a8, eanble = 0, strlen(mName) = 36
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  910): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 0
W/SensorService(  910): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@424f33a8, eanble = 0, strlen(mName) = 36
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  910): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@424f33a8
E/ActivityThread(  910): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42f2a450 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  910): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42f2a450 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  910): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  910): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  910): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  910): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  910): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  910): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  910): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  910): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  910): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  910): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  910): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  910): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  910): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  910): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  910): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  910): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  910): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  910): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  910): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  910): 	at dalvik.system.NativeStart.main(Native Method)
,I/ProviderInstaller( 4583): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1223): callingUid 10029, callindPid: 1223
,W/dalvikvm( 4583): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4583): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,W/dalvikvm( 4583): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4583): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4583): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4583): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4583): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,E/MDM     ( 1223): [113] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 2157): Restart initialization of location
,D/AuthorizationBluetoothService( 1359): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1359): Proximity feature is not enabled.
I/ActivityManager(  910): Recipient 4221
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1223): No location to return for getLastLocation()
,W/FusedLocationProvider( 1223): location=null
D/PMS     (  910): acquireWL(42c8f980): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(42c8f980): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
,I/WVCdm   (  371): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  371): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/PMS     (  910): releaseWL(42c99ed0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  910): NetTransition Wakelock for ConnectedState released by timeout
,D/NativeLibraryUtils( 4583): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  371): PrepareKeyRequest: nonce=2313981782,
,V/Tethering(  910): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  910): [AlarmQueuing] connectivity wifi: true
,I/WVCdm   (  371): CdmEngine::CloseSession
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  910): NoActiveNetworkState
D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,D/AccTypeManager( 1342): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/PMS     (  910): acquireWL(42e5d478): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1601/10029)
,I/NetworkMonitor( 4424): type=WIFI subType= reason=null isConnected=true
V/Tethering(  910): bSetPropertyMultiRAB:false
,D/Tethering(  910): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,I/Tethering(  910): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  910): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  910): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  910): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  910): Found interface wlan0
,D/Tethering(  910): TetherMasterSM: InitialState processMessage what=3
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.google.android.music (4424/10154)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.musicenhancer (3831/10053)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(44019038): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4492/10079)
,I/ConnectivityHelper( 1272): [onReceive] WIFI(1): CONNECTED
D/GpsLocationProvider(  910): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  910): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  910): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  910): ignore wifi update if we are not in OPENING or CLOSING
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.launcher (1272/10076)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1601/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
D/PMS     (  910): releaseWL(44019038): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
D/PMS     (  910): releaseWL(42e5d478): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
W/AccTypeManager( 1342): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1342): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (2712/10021)
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/ExternalAccountType( 1342): Unsupported attribute readOnly
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/AutoSetting( 1329): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4492): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4492): onReceive CONNECTIVITY_CHANGE networkType=1
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1329/10055)
D/AutoSetting( 1329): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1329): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 1329): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1329): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1329/10055)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4531/10151)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (3531/10160)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (3531/10160)
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): acquireWL(43df0ce0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2157 10029 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,I/CheckinService( 2157): Checkin interval check for package: unspecified last checkin: 1450463597266 min interval config: 0 actual interval: 52826
D/PMS     (  910): releaseWL(43df0ce0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2157, uid=10029, userID:0
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,I/Adreno-EGL( 4583): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4583): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4583): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4583): Local Branch: 
I/Adreno-EGL( 4583): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4583): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4583):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4583): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4583): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4583): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4583): Local Branch: 
I/Adreno-EGL( 4583): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4583): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4583):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4583): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4583): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4583): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4583): Local Branch: 
I/Adreno-EGL( 4583): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4583): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4583):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (4583/10029)
W/Settings( 4583): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/dalvikvm( 4373): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,W/dalvikvm( 4373): threadid=1: thread exiting with uncaught exception (group=0x41fb3e30)
,E/AndroidRuntime( 4373): FATAL EXCEPTION: main
E/AndroidRuntime( 4373): Process: com.test.thalitest, PID: 4373
E/AndroidRuntime( 4373): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4373): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 4373): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 4373): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 4373): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 4373): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 4373): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 4373): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4373): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4373): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4373): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4373): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4373): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4373): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4373): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4373): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4373): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4373): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4373): 	at dalvik.system.NativeStart.main(Native Method)
I/WVCdm   (  371): CdmEngine::OpenSession
E/ActivityManager(  910): App crashed! Process: com.test.thalitest
I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
W/ActivityManager(  910):   Force finishing activity com.test.thalitest/.MainActivity
,D/Process (  910): killProcessQuiet, pid=4245
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
,I/ActivityManager(  910): Killing 4245:com.htc.backup/1000 (adj 15): empty #17
D/Process ( 4373): killProcess, pid=4373
D/Process ( 4373): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,D/WVCdm   (  371): PrepareKeyRequest: nonce=1678928756
,I/WVCdm   (  371): CdmEngine::CloseSession
,I/CheckinRequestBuilder( 2157): Classify the device as Phone.
,D/libc    ( 2157): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2157): [NET] getaddrinfo-,err=8
D/libc    ( 2157): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2157): [NET] getaddrinfo-, 1
,D/libc    ( 2157): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =607f +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  910): WIN DEATH: Window{42d27c10 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager(  910): Recipient 4373
D/WifiService(  910): Client connection lost with reason: 4
I/ActivityManager(  910): Process com.test.thalitest (pid 4373) has died.
I/ActivityManager(  910): Recipient 4245
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Binder  ( 1211): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1211): java.lang.NullPointerException
W/Binder  ( 1211): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1211): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1211): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1211): 	at dalvik.system.NativeStart.run(Native Method)
,W/InputMethodManagerService(  910): Got RemoteException sending setActive(false) notification to pid 4373 uid 10389
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 244
D/libc    (  363): [NET]res_nsend:resplen=84
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 2157): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2157): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2157): [NET] getaddrinfo-,err=8
,D/libc    ( 2157): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2157): [NET] getaddrinfo-,err=8
D/libc    ( 2157): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2157): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2157): Sending checkin request (12198 bytes)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,W/fb4a(:<default>):UserScope( 4444): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4444): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=6 [16][1][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4444): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-,err=8
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  910): [NET] getaddrinfo-, 1
D/libc    (  910): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =8a64 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,I/CheckinRequestBuilder( 2157): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  910): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2157): Failed to find provider info for com.google.android.wearable.settings
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=172
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  910): Find DNS Address www.htc.com/23.59.123.86
,D/ConnectivityService(  910): getNetworkInfo networkType=9 called by com.google.android.gms (2157/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [4][0][0]
,I/CheckinRequestBuilder( 2157): Classify the device as Phone.
,I/CheckinTask( 2157): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2157): Checking schedule, now: 1450463652084 next: 1450986589072
,I/CheckinService( 2157): active receiver: disabled
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2157, uid=10029, userID:0
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
,D/PMS     (  910): acquireWL(441ac918): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4424 10154 null
,I/CheckinService( 2157): Checking schedule, now: 1450463652141 next: 1450986589072
,I/CheckinService( 2157): active receiver: disabled
,D/CheckinService( 2157): Recording last checkin time for package unspecified as 1450463652147
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2157, uid=10029, userID:0
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
,W/ContextImpl( 4424): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/PMS     (  910): releaseWL(44ab9fd8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4424, uid=10154, userID:0
,I/MusicLeanback( 4424): Conditions not met for autocaching.
,I/MusicLeanback( 4424): Stop autocaching.
,W/ContextImpl( 4424): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/PMS     (  910): releaseWL(441ac918): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029),
,D/PMS     (  910): acquireWL(43ed57c8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/GCM     ( 1359): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    ( 1359): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1359): [NET] getaddrinfo-,err=8
D/libc    ( 1359): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1359): [NET] getaddrinfo-, 1
D/libc    ( 1359): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =3d0c +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 254
D/libc    (  363): [NET]res_nsend:resplen=79
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1359): [NET] getaddrinfo_proxy-, success
D/PMS     (  910): releaseWL(426ae010): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/libc    ( 1359): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1359): [NET] getaddrinfo-,err=8
,D/libc    ( 1359): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1359): [NET] getaddrinfo-,err=8
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/PMS     (  910): acquireWL(4428bd18): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/PMS     (  910): releaseWL(43ed57c8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1359/10029)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  910): handleInetConditionChange: starting a change hold
,D/PMS     (  910): releaseWL(4428bd18): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(444c51c8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029),
D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1359/10029)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1359/10029)
,D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
,D/PMS     (  910): releaseWL(444c51c8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [10][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/AutoSetting( 1519): service - handleMessage() stop self
,D/AutoSetting( 1519): service - onDestroy() END
,D/AutoSetting( 1519): service - handleMessage() quit looper
,D/WifiStateMachine(  910): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  910): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,I/GAV2    ( 4531): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  910): killProcessQuiet, pid=4264
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4264:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,D/Process (  910): killProcessQuiet, pid=4208
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4208:com.htc.cs.dm/u0a98 (adj 15): empty #18
,I/ActivityManager(  910): Recipient 4264
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Recipient 4208
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
,I/ActivityManager(  910): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4663 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "sms"
,D/AccTypeManager( 1342): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1272): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/SystemReader( 1256): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/Launcher( 1272): Deferring update until onResume
,D/Launcher( 1272): waitUntilResume // bindAppsUpdated
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mms"
W/AccTypeManager( 1342): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1342): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "sms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mms"
,E/ExternalAccountType( 1342): Unsupported attribute readOnly
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,D/AutoSetting( 1329): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1329): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1329): service - requestNLP() NetworkLocationProvider not enabled
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,D/PhoneApp( 1238): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4663): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4663): MmsConfig.loadMmsSettings
,W/dalvikvm( 4663): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4663): VFY: unable to resolve instance field 36
,W/dalvikvm( 4663): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4663): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  910): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4686 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4663, uid=10111, userID:0
,W/Settings( 4663): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/PackageManager(  910): Unable to load service info ResolveInfo{43036128 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  910): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  910): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  910): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  910): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  910): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  910): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  910): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  910): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  910): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  910): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  910): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  910): 	at dalvik.system.NativeStart.main(Native Method)
,D/MessageFrequencyProvider( 4686): onCreate
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4663, uid=10111, userID:0
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4663, uid=10111, userID:0
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4663, uid=10111, userID:0
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4663, uid=10111, userID:0
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4663, uid=10111, userID:0
V/GetPrviateResource( 4686): GetPrviateResource
V/GetPrviateResource( 4686): GetPrviateResource
,D/MmsCustomizationProvider( 4686): query uri: content://htc-mms-customization/mms-ua/ua_string
D/PMS     (  910): acquireWL(43d8e3a8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4663 10111 null
,D/MmsCustomizationProvider( 4686): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/[PluginManager]RegisterService( 1329): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1329): handle notify Blinkfeed plugin client changed
I/Babel   ( 4663): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4663): MmsConfig.loadFromDatabase
,I/ActivityManager(  910): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/IcingCorporaProvider( 2808): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  910): acquireWL(42710588): PARTIAL_WAKE_LOCK  Icing 0x1 2157 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(426ae550): PARTIAL_WAKE_LOCK  AsyncService 0x1 3531 10160 null
,D/PMS     (  910): releaseWL(426ae550): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  910): releaseWL(42710588): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Babel   ( 4663): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4663): MmsConfig.loadFromResources
,E/Babel   ( 4663): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4663): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/ActivityManager(  910): Resuming delayed broadcast
D/PMS     (  910): releaseWL(43d8e3a8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ProviderInstaller( 4663): Installed default security provider GmsCore_OpenSSL
,D/PMS     (  910): acquireWL(42e3b140): PARTIAL_WAKE_LOCK  Icing 0x1 2157 10029 WorkSource{10029 com.google.android.gms}
D/MessageCustFlag( 4686): sense_version=6.0
D/BTAccessoryUtil( 4686): createReceiver
,D/Process (  910): killProcessQuiet, pid=3831
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/BTAccessoryUtil( 4686): registerReceiver return intent = null
D/MessageCustFlag( 4686): sku_id=99
,W/SystemReader( 4686): Cannot find message_ambs_application_id, use default value instead
I/ActivityManager(  910): Killing 3831:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,D/PackageBroadcastService( 2157): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/Messaging( 4686): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4686): networkCode: 
D/MessageCustFlag( 4686): sku_id=99
D/MmsConfig( 4686): SIE smsPri: null
,D/MmsConfig( 4686): networkCode: 
I/ActivityManager(  910): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
I/ActivityManager(  910): Recipient 3831
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/HtcTelephonyCapability( 4686): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 4686): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4686): getRATByHtcTelephonyCapability:1
W/SystemReader( 4686): Cannot find qct_8960_interface, use default value instead
I/PackageBroadcastService( 2157): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  910): Resuming delayed broadcast
,I/Icing   ( 2157): updateResources: need to parse f{com.google.android.gms}
,D/RemoteDisplayProvider(  910): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  910): start
,I/GCoreNlp( 1223): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  910): applying state to connected service
,D/LocationProviderProxy(  910): applying state to connected service
D/PMS     (  910): acquireWL(42f125f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(42f125f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(42d145c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(42d145c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42e51500): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42e51500): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  910): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/IcingCorporaProvider( 2808): UpdateCorporaTask done [took 468 ms] updated apps [took 468 ms] 
,I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1272): loadItems() com.htc.launcher.pageview.WidgetManager@42476d50 +
,I/Prism.WidgetManager( 1272): onLoadItems() +
,I/Icing   ( 2157): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2157): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  910): releaseWL(42e3b140): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1272): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1272): onLoadItems() -
,I/Prism.ItemManager( 1272): loadItems() com.htc.launcher.pageview.WidgetManager@42476d50 -
,D/PhoneApp( 1238): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1238): -- N1 =0
,D/PhoneApp( 1238): -- N2 =0
,D/PhoneApp( 1238): -- N3 =0
,D/Messaging( 4686): mNeedToUpdateDate2 start
,D/MmsConfig( 4686): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4686): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4686): 
D/MmsAsyncWorkHandler( 4686): HM tk = 20001
,D/ReportIndicatorCache( 4686): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4686): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@423f14b8
,I/Messaging( 4686): mccmnc> 
D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/MmsSmsV2Provider( 1238):  phoneType = -1
,D/MmsSmsV2Provider( 1238): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/DraftCache( 4686): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4686): [DraftCache/1] refresh
,D/MmsConfig( 4686): networkCode: 
,D/Messaging( 4686): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/MmsSmsV2Provider( 1238):  phoneType = -1
,D/MmsSmsV2Provider( 1238): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/PhoneStorageUtil( 4686): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4686): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4686): createReceiver
,D/MessageCustFlag( 4686): sense_version=6.0
,D/Jerry   ( 4686): start to preload cursor >>>>>>>
,D/Messaging( 4686): mNeedToUpdateDate2: false
D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/MmsSmsV2Provider( 1238):  phoneType = -1
D/TelephUtils( 1238): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
V/MmsProvider( 1238): Update uri=content://mms, match=0
,V/MmsProvider( 1238): selection=st=129 AND m_type!=134
,D/Messaging( 4686): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4686): TransactionService is going to be woken up.
,D/Messaging( 4686): ViewCache CreatePreload
,D/Messaging( 4686): ViewCache CreatePreloadOnlyMultipleOpsList
,V/TransactionService( 4686): 1-Creating TransactionService
,V/TransactionService( 4686): onStartCommand: 1
,D/MmsSystemEventReceiver( 4686): unRegisterForConnectionStateChanges
,D/Cust_MMSMS( 4686): _has_set_default_values_2=true
V/TransactionService( 4686): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4686): Loading previous transactions.
,D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
,D/AccFlag ( 1238): device_type: 1
,D/MsgPreferenceUtils( 4686): def_index: 0
D/TransactionService( 4686): Force set service start id to 1
V/TransactionService( 4686): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4686): unRegisterForConnectionStateChanges
,D/TransactionService( 4686): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4686): Destroying TransactionService
,V/TransactionService( 4686): 4-Handling incoming message: { when=-3ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/MsgPreferenceUtils( 4686): globalIndex = 1
D/MsgPreferenceUtils( 4686): phone state: true
D/MsgPreferenceUtils( 4686): sd state: false
,D/MsgPreferenceUtils( 4686): vIndex = 0
D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MmsSmsV2Provider( 1238):  phoneType = -1
,D/MmsSmsV2Provider( 1238): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
,D/AccFlag ( 1238): sku_id=99
,D/DraftCache( 4686): [DraftCache/466] rebuildCache
,D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/MmsSmsV2Provider( 1238):  phoneType = -1
,D/MmsSmsV2Provider( 1238): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 4686): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
,D/Jerry   ( 1238): URI_DRAFT
,D/DraftCache( 4686): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 4686): [DraftCache/466] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4686): 
D/MmsAsyncWorkHandler( 4686): HM tk = 20002
D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1238): sku_id=99
,D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
,D/AccFlag ( 1238): sku_id=99
,I/GAV4    ( 4663): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  910): killProcessQuiet, pid=4295
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4295:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4295
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  910): acquireWL(42e18fe8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  910): sending alarm PendingIntent{43e13230: PendingIntentRecord{430045f8 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=123168, Int=0
,D/PMS     (  910): acquireWL(42ffc4a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42e18fe8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [10][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/PMS     (  910): acquireWL(42fe6d60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42ffc4a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42fe6d60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(4493b748): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
,D/PMS     (  910): releaseWL(4493b748): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43e9b9d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): acquireWL(433f9548): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43d522d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1223): Vacuum at: now=1450463666203 tag=VacuumService
D/PMS     (  910): releaseWL(43e9b9d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(433f9548): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43000cf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
,D/PMS     (  910): releaseWL(43000cf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43d522d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(4404e9b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/PMS     (  910): releaseWL(4404e9b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(434c2d58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
,D/PMS     (  910): releaseWL(434c2d58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(44a042b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
D/PMS     (  910): releaseWL(44a042b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(43038740): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): acquireWL(43a48df0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43a48df0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(4499ebc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43038740): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43e63f98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
,D/PMS     (  910): releaseWL(43e63f98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1223): Scheduling Phenotype for one-off execution 10861 seconds from now (1450463666725)
,D/GetConfigurationSnapshotOperation( 1223): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1223): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/dalvikvm( 1223): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1223): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1223): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1223): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1223): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  910): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 1223): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1223): [NET] getaddrinfo-,err=8
D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1223): [NET] getaddrinfo-, 1
D/libc    ( 1223): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =9925 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=87
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1223): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1223): [NET] getaddrinfo-,err=8
D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1223): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  910): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [8][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): releaseWL(4499ebc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(44055098): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
,D/PMS     (  910): releaseWL(44055098): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(444ddde0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [2][0][0]
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
,D/PMS     (  910): releaseWL(444ddde0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(44264e40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): releaseWL(44264e40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/UsbnetService(  910): BroadcastReceiver::onReceive+
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(442f7860): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
I/BatteryService(  910): n_update end
D/PMS     (  910): releaseWL(442f7860): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  910): acquireWL(432d6f18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  910): sending alarm PendingIntent{42c054d8: PendingIntentRecord{42ff6160 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=135585, Int=0
,D/PMS     (  910): releaseWL(432d6f18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/AutoSetting( 1329): service - mHandler: update timezone
,D/AutoSetting( 1329): service - handleMessage() stop self
,D/AutoSetting( 1519): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1519): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1519): service - onCreate()
,D/AutoSetting( 1329): service - handleMessage() quit looper
W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1329): service - onDestroy() END
D/AutoSetting( 1519): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1519): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 1519): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1519): service - onStartCommand() handle command from HSP: processTimeZoneID
V/NotificationService(  910): batLight: Full, plugged
,V/LightsService(  910): setLight #8: color=#c8c800
,D/AutoSetting( 1519): service - mHandler: update timezone
,D/DotMatrix( 1589): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1589): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1519): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1519): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1519): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1519): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1589): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1589): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1117): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{42536a38 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.htclocationservice 3 7 2 11
,D/PMS     (  910): acquireWL(43b08440): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42c78a80: PendingIntentRecord{42c78a20 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141487, Int=0
,D/GpsLocationProvider(  910): ALARM_XTRA_TIMEOUT
D/PMS     (  910): acquireWL(441af360): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/GpsLocationProvider(  910): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  910): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  910): releaseWL(43b08440): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/libc    (  910): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-,err=8
D/libc    (  910): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  910): [NET] getaddrinfo-, 1
D/libc    (  910): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =a638 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  363): [NET]res_nsend:resplen=238
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo_proxy-, success
I/global  (  910): call createSocket() return a new socket.
D/libc    (  910): [NET] getaddrinfo+,hn 14(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  910): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  910): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  910): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  910):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  910): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/Process (  910): killProcessQuiet, pid=4310
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 ,
I/ActivityManager(  910): Killing 4310:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4310
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  910): releaseWL(441af360): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/ContactMessageStore( 1238): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1238): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{44274488 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  910): acquireWL(449d0da8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
V/AlarmManager(  910): sending alarm PendingIntent{42b980a8: PendingIntentRecord{42807810 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=157161, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(449d0da8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/AutoSetting( 1519): service - handleMessage() stop self
,D/AutoSetting( 1519): service - onDestroy() END
,D/AutoSetting( 1519): service - handleMessage() quit looper
D/Process (  910): killProcessQuiet, pid=4028
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4028:com.google.android.gm/u0a107 (adj 15): empty #17
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Recipient 4028
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  910): acquireWL(439154e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10027}
,V/AlarmManager(  910): sending alarm PendingIntent{43e52948: PendingIntentRecord{44335f50 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=170803, Int=0
,D/PMS     (  910): releaseWL(439154e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1238): switchBindHtcMsgCursor: null
,D/PMS     (  910): acquireWL(43957dc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  910): n_update end
,D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): releaseWL(43957dc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(42febcc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42febcc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(43baa290): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42b980a8: PendingIntentRecord{42807810 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=217161, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43baa290): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  910): acquireWL(42fea378): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42fea378): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  910): acquireWL(44428700): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42b980a8: PendingIntentRecord{42807810 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=277161, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(44428700): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(42f37f90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42f37f90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(43d61608): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42b980a8: PendingIntentRecord{42807810 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=337160, Int=0
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43d61608): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  910): acquireWL(43d7cac0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43d7cac0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(42c0b0f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): releaseWL(42c0b0f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  910): acquireWL(43004a50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
V/AlarmManager(  910): sending alarm PendingIntent{42b980a8: PendingIntentRecord{42807810 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=397160, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43004a50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1187): nl80211: Disconnect event
I/wpa_supplicant( 1187): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
I/wpa_supplicant( 1187): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  910): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getReasonFromEventString() 0
D/HTCRequest(  910): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  910): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  910): Enter handleNetworkDisconnect
I/wpa_supplicant( 1187): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 1187): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1187): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1187): send_and_recv error -67 - cmd 12
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1187): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1187): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8e74bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1187):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1187): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1187): netlink: Operstate: linkmode=-1, operstate=5
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1187): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1187): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1187): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1187): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:0,0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): Power_Mode_Type mode = 0
I/wpa_supplicant( 1187): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 61
D/wpa_supplicant( 1187): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1187): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1187): nl80211: if_removed already cleared - ignore event
D/Tethering(  910): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  910):    returned true
D/wpa_supplicant( 1187): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1187): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 1187): nl80211: if_removed already cleared - ignore event
D/Tethering(  910): [isWifi] getHotspotEnabled: false
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/wpa_supplicant( 1187): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1187): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1187): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1187): Wireless event: cmd=0x8b15 len=20
,D/WifiNative-wlan0(  910):    returned true
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
,D/Tethering(  910): interfaceStatusChanged wlan0, false
,D/DhcpStateMachine(  910): [RunningState] Stop DHCP
D/WifiP2pService(  910): InactiveState{ when=-6ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-6ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  910): Exit handleNetworkDisconnect
D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiDataStallTracker(  910): stopDataStallAlarm: current tag=20074 mDataStallAlarmIntent=null
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiPerfLock(  910): release()
D/WifiStateMachine(  910): PerfLock released for exiting ConnectedState
D/libc    (  910): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): Power_Mode_Type mode = 0
I/wpa_supplicant( 1187): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  910):    returned true
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/ConnectivityService(  910): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  910): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  910): acquireWL(444535c0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 910 1000 null
D/ConnectivityService(  910): Provision feature enable=false
D/ConnectivityService(  910): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiP2pService(  910): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/UsbnetStateTracker(  910): isAvailable+-
D/UsbnetStateTracker(  910): reconnect
,D/UsbnetStateTracker(  910): isAvailable+-
D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WISPrService( 3752): >>>>>WISPrService start isConnected = false<<<<<
D/WifiNative-wlan0(  910): doBoolean: SET pno 1
,D/WISPrService( 3752): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1187): CTRL_IFACE SET 'pno'='1'
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/ConnectivityService(  910): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  910): default: reconnect()
D/MDST    (  910): default: setTeardownRequested(false)
D/MDST    (  910): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  910): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  910): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  910): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1187): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
,D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '53 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 53 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  910): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '54 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 54 Failed to remove route from default table (No such process)'
,D/WISPrService( 3752): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
,D/WISPrService( 3752): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,V/NativeCrypto( 1359): Read error: ssl=0x63fa6008: I/O error during system call, Connection timed out
D/ConnectivityService(  910): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '55 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 55 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): handleConnectivityChange: resetting
D/ConnectivityService(  910): resetConnections(wlan0, 3)
D/PMS     (  910): acquireWL(43dd7ca0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): flush DNS cache for net 1(wlan0)
D/libc    (  363): [NET] entry_id:5   entry:0xb873ff98  removed 
D/libc    (  363): [NET] entry_id:3   entry:0xb87440f8  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb8744428  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb87444e0  removed 
D/libc    (  363): [NET] entry_id:4   entry:0xb87442c8  removed 
,D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
,V/NativeCrypto( 1359): SSL shutdown failed: ssl=0x63fa6008: I/O error during system call, Broken pipe
D/Nat464Xlat(  910): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  910): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  910): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  910): acquireWL(42fea690): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  910): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4492/10079)
D/WirelessDisplayService(  910): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
,D/WirelessDisplayService(  910): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WifiStateMachine(  910): startScan Pid: 910 Uid 1000
,D/WifiNative-wlan0(  910): doBoolean: SET pno 0
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1187): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: SCAN
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/BatSI   (  910): WIFI scan started for: 450a0300 uid:1000
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +,
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiNative-wlan0(  910):    returned true
,D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
D/ConnectivityService(  910): reportInetCondition for net -1, percentage: 0 by  (1359/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/PMS     (  910): releaseWL(43dd7ca0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/PMS     (  910): releaseWL(42fea690): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  910): mActiveDefaultNetwork: -1
,D/ConnectivityService(  910): handleInetConditionChange: no active default network - ignore
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  910): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  910): [AlarmQueuing] connectivity wifi: false
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
D/CaptivePortalTracker(  910): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/CaptivePortalTracker(  910): NoActiveNetworkState
,D/Tethering(  910): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(434c5bf0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/GpsLocationProvider(  910): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  910): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  910): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  910): ignore wifi update if we are not in OPENING or CLOSING
,I/NetworkMonitor( 4424): type=WIFI subType= reason=null isConnected=false
,V/Tethering(  910): bSetPropertyMultiRAB:false
D/Tethering(  910): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  910): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  910): ipv4Default null
I/Tethering(  910): No IPv4 upstream interface, giving up.
,D/Tethering(  910): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.google.android.music (4424/10154)
D/PMS     (  910): releaseWL(434c5bf0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4492/10079)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
,I/ConnectivityHelper( 1272): [onReceive] WIFI(1): DISCONNECTED
D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.launcher (1272/10076)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1601/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (2712/10021)
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/AutoSetting( 1329): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4492): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4492): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1329): Util - no network available!
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1329/10055)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1329/10055)
,D/AutoSetting( 1329): service - onCreate()
,D/AutoSetting( 1329): service - AddressCache: using context: com.htc.Weather
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4531/10151)
D/LocationManagerService(  910): request 42dc2be8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/LocationManagerService(  910): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1329): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1329): service - mHandler: cancel location update
D/AutoSetting( 1329): service -           changes count: 0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (3531/10160)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (3531/10160)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
,I/iu.Environment( 2157): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2157): num queued entries: 0
,I/iu.UploadsManager( 2157): num updated entries: 0
,I/iu.SyncManager( 2157): NEXT; no task
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-61
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-62
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-82
I/wpa_supplicant( 1187): [NULL] fc:94:e3:11:35:3a freq=2462 level=-92
I/wpa_supplicant( 1187): [NULL] fe:94:e3:11:35:3c freq=2462 level=-93
D/wpa_supplicant( 1187): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=14 entropy=0
D/wpa_supplicant( 1187): Add randomness: count=15 entropy=1
D/wpa_supplicant( 1187): Add randomness: count=16 entropy=2
D/wpa_supplicant( 1187): Add randomness: count=17 entropy=3
D/wpa_supplicant( 1187): Add randomness: count=18 entropy=4
D/wpa_supplicant( 1187): Add randomness: count=19 entropy=5
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): blist: c0:ff:d4:d3:aa:48 count[1]
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1187): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1187):    skip - blacklisted (count=1 limit=0)
D/wpa_supplicant( 1187): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1187): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 5: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1187): No APs found - clear blacklist and try again
E/wpa_supplicant( 1187): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1187): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1187): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-62
I/wpa_supplicant( ,1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 3
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): selected network = 1
D/wpa_supplicant( 1187): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8e764e8  current_ssid=0x0
D/wpa_supplicant( 1187): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1187): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1187): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1187): check if in concurrent case
,I/wpa_supplicant( 1187): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1187): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1187): wpa_supplicant_associate, 1780
,D/wpa_supplicant( 1187): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1187): RSN: PMKSA cache search - network_ctx=0xb8e764e8 try_opportunistic=0
D/wpa_supplicant( 1187): RSN: Search for BSSID c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 1187): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1187): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
,D/wpa_supplicant( 1187): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1187): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1187): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1187): nl80211: Unsubscribe mgmt frames handle 0xb8e75718 (mode change)
D/wpa_supplicant( 1187): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8e75718
,D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
D/WifiMonitor(  910): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
D/WifiNative-wlan0(  910): doBoolean: SET pno 1
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1187): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1187):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1187):   * freq=2412
D/wpa_supplicant( 1187):   * Auth Type 0
D/wpa_supplicant( 1187):   * WPA Versions 0x2
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 46
,D/wpa_supplicant( 1187): nl80211: Connect request send successfully
D/wpa_supplicant( 1187): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - EAP fail=0
,D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): CTRL_IFACE SET 'pno'='1'
E/wpa_supplicant( 1187): send_and_recv error -16 - cmd 75
D/wpa_supplicant( 1187): nl80211: Sched scan start failed: ret=-16 (Device or resource busy)
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1" Return -1
,D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  910):    returned false
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  910): doString: LIST_DONGLES
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  910): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1187): reply (756) for get BSS: id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-62
I/wpa_supplicant( 1187): tsf=0000000400652774
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=6
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-51,
I/wpa_supplicant( 1187): tsf=0000000105141144
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=7
I/wpa_supplicant( 1187): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-61
I/wpa_supplicant( 1187): tsf=0000000400652763
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1187): ssid=01ABC
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=8
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2427
I/wpa_supplicant( 1187): level=-82
I/wpa_supplicant( 1187): tsf=0000000400652783
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=9
I/wpa_supplicant( 1187): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1187): freq=2462
I/wpa_supplicant( 1187): level=-92
I/wpa_supplicant( 1187): tsf=0000000400652802
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=UPC0039325
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=10
I/wpa_supplicant( 1187): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1187): freq=2462
I/wpa_supplicant( 1187): level=-93
I/wpa_supplicant( 1187): tsf=0000000400652793
I/wpa_supplicant( 1187): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=UPC Wi-Free
I/wpa_supplicant( 1187): ####
,D/WirelessDisplayService(  910): getDiscoveryDongleList
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/WifiStateMachine(  910): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -62, frequency: 2412, timestamp: 400652774, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 5220, timestamp: 105141144, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -61, frequency: 2412, timestamp: 400652763, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2427, timestamp: 400652783, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  910): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -92, frequency: 2462, timestamp: 400652802, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): == begin of scan result ==
,D/WifiStateMachine(  910): == (6) end of scan result ==
,D/WifiManager( 1223): getScanResults enter 
D/WifiStateMachine(  910): == begin of scan result ==
,D/WirelessDisplayService(  910): getDiscoveryDongleList
,D/WifiStateMachine(  910): == (6) end of scan result ==
D/WifiStateMachine(  910): 5: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -93, frequency: 2462, timestamp: 400652793, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): add 6 to mScanResults
D/BatSI   (  910): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  910): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/wpa_supplicant( 1187): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1187): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1187): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1187): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1187): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1187): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1187): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1187): nl80211: Connect event
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1187): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1187): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1187): Add randomness: count=20 entropy=6
I/wpa_supplicant( 1187): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1187): TDLS: Remove peers on association
D/wpa_supplicant( 1187): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/WifiMonitor(  910): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  910): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1187): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1187): EAPOL: enable timer tick
D/wpa_supplicant( 1187): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1187): htc_wext_set_keepalive +
I/wpa_supplicant( 1187): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1187): getPrivFuncNum +	
D/HTCRequest(  910): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
I/wpa_supplicant( 1187): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1187): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1187): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1187): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/HTCRequest(  910): WifiMonitor:getFreqFromEventString() 2412
D/wpa_supplicant( 1187): Get randomness: len=32 entropy=7
D/HTCRequest(  910): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  910): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  910): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  910): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  910): interfaceLinkStateChanged wlan0,, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  910): Enter handleAssociatedWithEvent
D/WifiStateMachine(  910): Associated
D/WifiStateMachine(  910): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  910): Exit handleAssociatedWithEvent
D/Tethering(  910): interfaceLinkStateChanged wlan0, true
D/WifiStateMachine(  910): BSSID was changed, update WiFi database
D/Tethering(  910): interfaceStatusChanged wlan0, true
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/WifiStateMachine(  910): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  910): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  910): This record is existed, only update it...
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  910): updateConnectedAP...
I/wpa_supplicant( 1187): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb8e759f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1187):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1187): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1187): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f13b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1187):    broadcast key
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1187): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1187): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
I/wpa_supplicant( 1187): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1187): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1187): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  910): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1187): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1187): set send_ind_to_ndc = 0
I/wpa_supplicant( 1187): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1187): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1187): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1187): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1187): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1187): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1187): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1187): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1187): EAPOL authentication completed successfully
I/wpa_supplicant( 1187): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 79
D/Tethering(  910): interfaceLinkStateChanged wlan0, true
D/Tethering(  910): interfaceStatusChanged wlan0, true
D/wpa_supplicant( 1187): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1187): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1187): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/WifiStateMachine(  910): fetchFrequency(), freq = 2412
D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  910): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  910): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  910): This record is existed, only update it...
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  910): Provision feature enable=false
D/ConnectivityService(  910): mActiveDefaultNetwork: -1
D/WISPrService( 3752): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/WISPrService( 3752): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiNative-wlan0(  910): doBoolean: SET pno 0
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): CTRL_IFACE SET 'pno'='0'
,D/WifiNative-wlan0(  910):    returned true
D/DhcpStateMachine(  910): [StoppedState] Start DHCP
,D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 1
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
D/WifiStateMachine(  910): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  910): acquireWL(4485e550): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 910 1000 null
,D/WifiStateMachine(  910): handlePreDhcpSetup mBluetoothConnectionActive: false
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): Power_Mode_Type mode = 1
I/wpa_supplicant( 1187): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 61
D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1187): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  910):    returned null
E/WifiStateMachine(  910): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  910):    returned null
D/WifiP2pService(  910): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42ec7a68 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42ec7a68 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
,D/wpa_supplicant( 1187): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1187): EAPOL: disable timer tick
,D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  910): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1187): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
D/WifiP2pService(  910): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  910): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): releaseWL(4485e550): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=33 [3][1][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -61 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1187): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED -1 -> 3
,D/WifiStateMachine(  910): gateway: /192.168.1.1
,D/WifiNative-wlan0(  910): doBoolean: DRIVER GATEWAY-ADD 16885952
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1187): htc_wext_set_keepalive +
I/wpa_supplicant( 1187): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1187): getPrivFuncNum +	
I/wpa_supplicant( 1187): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1187): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1187): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1187): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1187): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  910):    returned true
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  910): VerifyingLinkState enter
D/WifiStateMachine(  910): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  910): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  910): VerifyingLinkState: enableIpv6
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -61, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
V/NetworkPolicy(  910): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,D/WifiWatchdogStateMachine(  910): WAN detection
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  910): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  910): Provision feature enable=false
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED connected
D/ConnectivityService(  910): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
V/ConnectivityService(  910): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  910): default: teardown()
D/MDST    (  910): default: setTeardownRequested(true)
D/MDST    (  910): default: setEnableApn apnType =default , enable=false
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/WISPrService( 3752): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [1][0][0]
,I/wpa_supplicant( 1187): Change stage from stage0 to stage3
,D/WifiStateMachine(  910): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
D/MDST    (  910): default: setTeardownRequested(true)
D/ConnectivityService(  910): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  910): Unexpected mtu value: android.net.wifi.WifiStateTracker@42d69fc8
D/ConnectivityService(  910): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): syncGetConfiguredNetworks
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  910): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  910): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
,D/ConnectivityService(  910): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  910): handleConnectivityChange: resetting
D/Nat464Xlat(  910): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  910): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  910): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  910): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  910): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  910): acquireWL(43e31858): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  910): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  910):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4492/10079)
,I/QuickSettingWifi( 1117): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/PMS     (  910): acquireWL(43d00400): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2157 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(43e31858): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
,I/logwrapper(  363): /system/bin/ip terminated by exit(254)
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  910): mActiveDefaultNetwork: WIFI
,D/PMS     (  910): acquireWL(44190540): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2157 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2157): Checkin interval check for package: unspecified last checkin: 1450463652147 min interval config: 0 actual interval: 293671
D/PMS     (  910): releaseWL(43d00400): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2157): Checking schedule, now: 1450463945827 next: 1450463682072
,I/CheckinService( 2157): active receiver: enabled
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2157, uid=10029, userID:0
,I/CheckinService( 2157): Preparing to send checkin request
,I/EventLogService( 2157): Accumulating logs since 1450463649135
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
,I/CheckinRequestBuilder( 2157): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  910): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2157): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  910): getNetworkInfo networkType=9 called by com.google.android.gms (2157/10029)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  371): PrepareKeyRequest: nonce=721472205
,I/Adreno-EGL( 4583): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4583): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4583): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4583): Local Branch: 
I/Adreno-EGL( 4583): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4583): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4583):                  aa63bbd948f41d15fc72f585e
,I/WVCdm   (  371): CdmEngine::CloseSession
,I/Adreno-EGL( 4583): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4583): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4583): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4583): Local Branch: 
I/Adreno-EGL( 4583): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4583): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4583):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4583): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4583): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4583): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4583): Local Branch: 
I/Adreno-EGL( 4583): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4583): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4583):                  aa63bbd948f41d15fc72f585e
,D/PMS     (  910): releaseWL(444535c0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  910): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  910): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  910): [AlarmQueuing] connectivity wifi: true
D/CaptivePortalTracker(  910): NoActiveNetworkState
,V/Tethering(  910): bSetPropertyMultiRAB:false
D/Tethering(  910): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1601/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4492/10079)
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
,I/ConnectivityHelper( 1272): [onReceive] WIFI(1): CONNECTED
,I/NetworkMonitor( 4424): type=WIFI subType= reason=null isConnected=true
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.google.android.music (4424/10154)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.launcher (1272/10076)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/Tethering(  910): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  910): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
I/Tethering(  910): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
,I/Tethering(  910): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  910): Found interface wlan0
,D/Tethering(  910): TetherMasterSM: InitialState processMessage what=3
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
D/PMS     (  910): acquireWL(446b1960): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/PMS     (  910): acquireWL(43e654b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/GpsLocationProvider(  910): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  910): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  910): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  910): ignore wifi update if we are not in OPENING or CLOSING
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,I/wpa_supplicant( 1187): Change stage from stage3 to stage1
D/PMS     (  910): releaseWL(43e654b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  910): releaseWL(446b1960): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (2712/10021)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,W/Settings( 4583): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (4583/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/AutoSetting( 1329): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1329/10055)
D/AutoSetting( 1329): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1329): service - onStartCommand() screen is off, don't request location
D/MobileConnectivityChangeReceiver( 4492): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/MobileConnectivityChangeReceiver( 4492): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1329): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1329): service - onStartCommand() check timezone in 30000
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1329/10055)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4531/10151)
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (3531/10160)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (3531/10160)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,I/CheckinService( 2157): Checkin interval check for package: unspecified last checkin: 1450463652147 min interval config: 0 actual interval: 294611
D/PMS     (  910): acquireWL(441a0ec8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2157 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(441a0ec8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2157, uid=10029, userID:0
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,I/iu.Environment( 2157): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2157): num queued entries: 0
,I/iu.UploadsManager( 2157): num updated entries: 0
,I/iu.SyncManager( 2157): NEXT; no task
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/libc    ( 1359): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1359): [NET] getaddrinfo-,err=8
D/libc    ( 1359): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1359): [NET] getaddrinfo-, 1
,D/libc    ( 1359): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/libc    (  363): [NET] +++++ res_nsend xid =fb7e +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/PMS     (  910): acquireWL(42bc7fb8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 247
D/libc    (  363): [NET]res_nsend:resplen=79
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1359): [NET] getaddrinfo_proxy-, success
,D/WVCdm   (  371): PrepareKeyRequest: nonce=574304652
,D/libc    ( 1359): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1359): [NET] getaddrinfo-,err=8
,I/WVCdm   (  371): CdmEngine::CloseSession
,D/libc    ( 1359): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1359): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,I/CheckinRequestBuilder( 2157): Classify the device as Phone.
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/libc    ( 2157): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,V/NativeCrypto( 2157): SSL shutdown failed: ssl=0x6e141310: I/O error during system call, Connection timed out
,D/libc    ( 2157): [NET] getaddrinfo-,err=8
,D/libc    ( 2157): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    ( 2157): [NET] getaddrinfo-, 1
D/libc    ( 2157): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =dadf +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=84
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2157): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2157): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2157): [NET] getaddrinfo-,err=8
,D/libc    ( 2157): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2157): [NET] getaddrinfo-,err=8
,D/libc    ( 2157): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2157): [NET] getaddrinfo-,err=8
,D/PMS     (  910): acquireWL(42ef9b58): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/PMS     (  910): releaseWL(42bc7fb8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1359/10029)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  910): handleInetConditionChange: starting a change hold
,D/PMS     (  910): releaseWL(42ef9b58): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43e74648): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1359/10029)
,D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1359/10029)
,D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
,I/CheckinTask( 2157): Sending checkin request (12205 bytes)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
D/PMS     (  910): releaseWL(43e74648): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=7 [26][2][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,I/CheckinRequestBuilder( 2157): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  910): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2157): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  910): getNetworkInfo networkType=9 called by com.google.android.gms (2157/10029)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=100 [1][1][0]
,I/wpa_supplicant( 1187): Change stage from stage1 to stage3
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
,I/CheckinRequestBuilder( 2157): Classify the device as Phone.
,I/CheckinTask( 2157): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2157): Checking schedule, now: 1450463947789 next: 1450986884781
,I/CheckinService( 2157): active receiver: disabled
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2157, uid=10029, userID:0
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
I/CheckinService( 2157): Checking schedule, now: 1450463947813 next: 1450986884781
,I/CheckinService( 2157): active receiver: disabled
,D/CheckinService( 2157): Recording last checkin time for package unspecified as 1450463947817
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2157, uid=10029, userID:0
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
,D/PMS     (  910): releaseWL(44190540): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
,D/GCM     ( 1359): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-,err=8
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  910): [NET] getaddrinfo-, 1
,D/libc    (  910): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =294f +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=172
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  910): Find DNS Address www.htc.com/23.59.123.86
,D/WifiStateMachine(  910): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  910): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1342): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  910): acquireWL(42c9ea60): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4663 10111 null
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "sms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "smsto"
,W/Prism.AllAppsManager( 1272): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,W/SystemReader( 1256): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,D/PMS     (  910): releaseWL(42c9ea60): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  910): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
W/AccTypeManager( 1342): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1342): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mmsto"
I/Launcher( 1272): Deferring update until onResume
,D/Launcher( 1272): waitUntilResume // bindAppsUpdated
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/ActivityManager(  910): Resuming delayed broadcast
,I/[PluginManager]RegisterService( 1329): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1329): handle notify Blinkfeed plugin client changed
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "sms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/IcingCorporaProvider( 2808): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mmsto"
,I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
E/ExternalAccountType( 1342): Unsupported attribute readOnly
,D/PhoneApp( 1238): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/ActivityManager(  910): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  910): acquireWL(446b3f48): PARTIAL_WAKE_LOCK  Icing 0x1 2157 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(44ac48d0): PARTIAL_WAKE_LOCK  AsyncService 0x1 3531 10160 null
,D/PMS     (  910): releaseWL(44ac48d0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  910): releaseWL(446b3f48): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Resuming delayed broadcast
,D/PMS     (  910): acquireWL(42e594a0): PARTIAL_WAKE_LOCK  Icing 0x1 2157 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  910): releaseWL(42e594a0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,D/PMS     (  910): acquireWL(4331c3a8): PARTIAL_WAKE_LOCK  Icing 0x1 2157 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(4331c3a8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
,D/PMS     (  910): acquireWL(438f38a8): PARTIAL_WAKE_LOCK  Icing 0x1 2157 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(438f38a8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Resuming delayed broadcast
,D/PMS     (  910): acquireWL(42e752d8): PARTIAL_WAKE_LOCK  Icing 0x1 2157 10029 WorkSource{10029 com.google.android.gms}
,D/PackageBroadcastService( 2157): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/ActivityManager(  910): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/PackageBroadcastService( 2157): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 2157): updateResources: need to parse f{com.google.android.gms}
,W/PackageManager(  910): Unable to load service info ResolveInfo{42f04308 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  910): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  910): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  910): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  910): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  910): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  910): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  910): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  910): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  910): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  910): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  910): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  910): 	at dalvik.system.NativeStart.main(Native Method)
,I/IcingCorporaProvider( 2808): UpdateCorporaTask done [took 462 ms] updated apps [took 462 ms] 
I/ActivityManager(  910): Resuming delayed broadcast
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  910): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/RemoteDisplayProvider(  910): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  910): start
,I/GCoreNlp( 1223): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  910): applying state to connected service
D/PMS     (  910): acquireWL(43c46428): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(43c46428): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  910): applying state to connected service
D/PMS     (  910): acquireWL(42f86678): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(42f86678): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(4427aad0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(4427aad0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1272): loadItems() com.htc.launcher.pageview.WidgetManager@42476d50 +
,I/Prism.WidgetManager( 1272): onLoadItems() +
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{43e78858 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/Icing   ( 2157): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2157): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  910): releaseWL(42e752d8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1272): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1272): onLoadItems() -
,I/Prism.ItemManager( 1272): loadItems() com.htc.launcher.pageview.WidgetManager@42476d50 -
,D/PhoneApp( 1238): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1238): -- N1 =0
,D/PhoneApp( 1238): -- N2 =0
,D/PhoneApp( 1238): -- N3 =0
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(445035d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(445035d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(43a08478): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,D/PMS     (  910): acquireWL(441dbbe8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 910 1000 null
,V/AlarmManager(  910): sending alarm PendingIntent{425ae358: PendingIntentRecord{42ddaa50 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=433163, Int=0
,I/ActivityManager(  910): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4860 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  910): sending alarm PendingIntent{42f66dc0: PendingIntentRecord{42f1b1f8 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1450463753332, Int=10800000
,V/AlarmManager(  910): sending alarm PendingIntent{42d74968: PendingIntentRecord{4303ed60 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450463774435, Int=1800000
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(4386a728): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/PMS     (  910): releaseWL(441dbbe8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  910): releaseWL(4386a728): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  910): acquireWL(42f49f70): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2157 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43a08478): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029}
,D/PMS     (  910): acquireWL(43400898): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2157 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42f49f70): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/EventLogService( 2157): Aggregate from 1450463945861 (log), 1450461974336 (data)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.aurora (4860/10049)
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
,D/PMS     (  910): releaseWL(43400898): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1329): service - mHandler: update timezone
,D/AutoSetting( 1329): service - handleMessage() stop self
,D/AutoSetting( 1519): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1329): service - handleMessage() quit looper
,W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1329): service - onDestroy() END
,D/AutoSetting( 1519): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1519): service - onCreate()
,W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1519): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1519): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/DotMatrix( 1589): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
D/DotMatrix( 1589): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1519): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1519): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1519): service - mHandler: update timezone
,D/AutoSetting( 1519): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1519): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1519): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1519): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1589): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1589): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1117): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{427bb7e8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.htclocationservice 3 7 2 11
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{4499d598 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  910): acquireWL(42fc7e68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42b980a8: PendingIntentRecord{42807810 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=457161, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42fc7e68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/AutoSetting( 1519): service - handleMessage() stop self
,D/AutoSetting( 1519): service - onDestroy() END
,D/AutoSetting( 1519): service - handleMessage() quit looper
,D/Process (  910): killProcessQuiet, pid=4344
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4344:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Recipient 4344
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  910): acquireWL(42fd4898): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42fd4898): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  910): acquireWL(433a0678): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
V/AlarmManager(  910): sending alarm PendingIntent{42b980a8: PendingIntentRecord{42807810 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=517161, Int=0
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(433a0678): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(42f3b3c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42f3b3c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(42d96ef8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42b980a8: PendingIntentRecord{42807810 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=577161, Int=0
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42d96ef8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(449c7718): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(449c7718): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1238): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1238): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1238): sku_id=99
D/ContactMessageStore( 1238): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1238): start background delete task...
D/ContactMessageStore( 1238): size: 0 , 0
,D/ContactMessageStore( 1238): Background delete complete
,D/PMS     (  910): acquireWL(42f46f30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42b980a8: PendingIntentRecord{42807810 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=637161, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42f46f30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1187): nl80211: Disconnect event
I/wpa_supplicant( 1187): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
I/wpa_supplicant( 1187): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
I/wpa_supplicant( 1187): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 1187): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1187): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1187): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1187): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1187): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8e74bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1187):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1187): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1187): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1187): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1187): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1187): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1187): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1187): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1187): nl80211: if_removed already cleared - ignore event
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
D/HTCRequest(  910): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getReasonFromString CTRL-EV,ENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getReasonFromEventString() 0
D/HTCRequest(  910): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  910): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/WifiStateMachine(  910): Enter handleNetworkDisconnect
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): Power_Mode_Type mode = 0
I/wpa_supplicant( 1187): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 61
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 1187): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1187): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1187): nl80211: if_removed already cleared - ignore event
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1187): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1187): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1187): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1187): Wireless event: cmd=0x8b15 len=20
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/Tethering(  910): [isWifi] getHotspotEnabled: false
,D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  910):    returned true
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
,D/Tethering(  910): interfaceStatusChanged wlan0, false
,D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/WifiP2pService(  910): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/DhcpStateMachine(  910): [RunningState] Stop DHCP
D/WifiStateMachine(  910): Exit handleNetworkDisconnect
D/WifiPerfLock(  910): release()
,D/WifiStateMachine(  910): PerfLock released for exiting ConnectedState
,D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
D/libc    (  910): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiDataStallTracker(  910): stopDataStallAlarm: current tag=20075 mDataStallAlarmIntent=null
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
D/ConnectivityService(  910): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  910): acquireWL(42ff4018): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 910 1000 null
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): Power_Mode_Type mode = 0
I/wpa_supplicant( 1187): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 61
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/UsbnetStateTracker(  910): isAvailable+-
D/UsbnetStateTracker(  910): reconnect
D/UsbnetStateTracker(  910): isAvailable+-
,D/WifiNative-wlan0(  910):    returned true
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  910): Provision feature enable=false
D/ConnectivityService(  910): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiP2pService(  910): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  910): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  910): default: reconnect()
D/MDST    (  910): default: setTeardownRequested(false)
D/MDST    (  910): default: setEnableApn apnType =default , enable=true
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 3752): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 3752): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiNative-wlan0(  910): doBoolean: SET pno 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): CTRL_IFACE SET 'pno'='1'
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/ConnectivityService(  910): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  910): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  910): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
E/NativeDaemonConnector.ResponseQueue(  910): more buffered than allowed: 10 >= 10
E/NativeDaemonConnector.ResponseQueue(  910): Removing request: null (7)
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 3752): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '74 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 74 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  910): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WISPrService( 3752): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1187): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
,D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
,D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,V/NativeCrypto( 1359): Read error: ssl=0x63fa0008: I/O error during system call, Connection timed out
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '75 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 75 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '76 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 76 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): handleConnectivityChange: resetting
D/ConnectivityService(  910): resetConnections(wlan0, 3)
,V/NativeCrypto( 1359): SSL shutdown failed: ssl=0x63fa0008: I/O error during system call, Broken pipe
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
D/libc    (  363): [NET] entry_id:1   entry:0xb8744410  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb8744108  removed 
D/libc    (  363): [NET] entry_id:3   entry:0xb8743fd8  removed 
,D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
D/PMS     (  910): acquireWL(43ed6bb0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
D/ConnectivityService(  910): flush DNS cache for net 1(wlan0)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
D/Nat464Xlat(  910): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  910): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WirelessDisplayService(  910): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  910): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
D/ConnectivityService(  910): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  910): acquireWL(441abb18): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  910): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4492/10079)
D/ConnectivityService(  910): reportInetCondition for net -1, percentage: 0 by  (1359/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,D/WifiStateMachine(  910): startScan Pid: 910 Uid 1000
,D/WifiNative-wlan0(  910): doBoolean: SET pno 0
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1187): nl80211: Sched scan stop sent (ret=0)
I/wpa_supplicant( 1187): wpa_supplicant_scan enter
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/PMS     (  910): releaseWL(43ed6bb0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: SCAN
I//system/bin/ip(  363): RTNETLINK answers: No such process
I/logwrapper(  363): /system/bin/ip terminated by exit(2)
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1187): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1187): Failed to initiate AP scan
I/wpa_supplicant( 1187): Failed to initiate AP scan, Failed_to_scan_counter:1
,D/WifiNative-wlan0(  910):    returned true
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/BatSI   (  910): WIFI scan started for: 450a0300 uid:1000
D/PMS     (  910): releaseWL(441abb18): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  910): mActiveDefaultNetwork: -1
,D/ConnectivityService(  910): handleInetConditionChange: no active default network - ignore
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  910): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  910): [AlarmQueuing] connectivity wifi: false
,D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/PMS     (  910): acquireWL(44552198): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
,D/GpsLocationProvider(  910): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  910): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  910): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  910): ignore wifi update if we are not in OPENING or CLOSING
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
D/CaptivePortalTracker(  910): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  910): NoActiveNetworkState
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): releaseWL(44552198): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1187): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1187): Failed to initiate AP scan
,I/wpa_supplicant( 1187): Failed to initiate AP scan, Failed_to_scan_counter:2
,I/NetworkMonitor( 4424): type=WIFI subType= reason=null isConnected=false
D/Tethering(  910): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  910): bSetPropertyMultiRAB:false
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1601/10029)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.launcher (1272/10076)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.google.android.music (4424/10154)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4492/10079)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/Tethering(  910): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
,I/ConnectivityHelper( 1272): [onReceive] WIFI(1): DISCONNECTED
D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
I/Tethering(  910): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  910): ipv4Default null
,I/Tethering(  910): No IPv4 upstream interface, giving up.
,D/Tethering(  910): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (2712/10021)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/AutoSetting( 1329): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/AutoSetting( 1329): Util - no network available!
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1329/10055)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1329/10055)
D/MobileConnectivityChangeReceiver( 4492): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4492): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1329): service - onCreate()
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4531/10151)
,D/AutoSetting( 1329): service - AddressCache: using context: com.htc.Weather
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (3531/10160)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (3531/10160)
D/AutoSetting( 1329): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/LocationManagerService(  910): request 42dc2be8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/LocationManagerService(  910): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1329): service - mHandler: cancel location update
D/AutoSetting( 1329): service -           changes count: 0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
,I/iu.Environment( 2157): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2157): num queued entries: 0
,I/iu.UploadsManager( 2157): num updated entries: 0
,I/iu.SyncManager( 2157): NEXT; no task
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1187): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1187): Failed to initiate AP scan
,I/wpa_supplicant( 1187): Failed to initiate AP scan, Failed_to_scan_counter:3
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 1187): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-61
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-62
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-82
I/wpa_supplicant( 1187): [NULL] fc:94:e3:11:35:3a freq=2462 level=-92
I/wpa_supplicant( 1187): [NULL] fe:94:e3:11:35:3c freq=2462 level=-93
D/wpa_supplicant( 1187): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=21 entropy=0
D/wpa_supplicant( 1187): Add randomness: count=22 entropy=1
D/wpa_supplicant( 1187): Add randomness: count=23 entropy=2
D/wpa_supplicant( 1187): Add randomness: count=24 entropy=3
D/wpa_supplicant( 1187): Add randomness: count=25 entropy=4
D/wpa_supplicant( 1187): Add randomness: count=26 entropy=5
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): blist: c0:ff:d4:d3:aa:48 count[1]
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1187): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1187):    skip - blacklisted (count=1 limit=0)
D/wpa_supplicant( 1187): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1187): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 5: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1187): No APs found - clear blacklist and try again
E/wpa_supplicant( 1187): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1187): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1187): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-62
I/wpa_supplicant( ,1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 3
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): selected network = 1
D/wpa_supplicant( 1187): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8e764e8  current_ssid=0x0
D/wpa_supplicant( 1187): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1187): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1187): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1187): check if in concurrent case
I/wpa_supplicant( 1187): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiNative-wlan0(  910): doBoolean: SET pno 1
,D/WifiMonitor(  910): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
D/wpa_supplicant( 1187): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1187): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1187): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1187): RSN: PMKSA cache search - network_ctx=0xb8e764e8 try_opportunistic=0
D/wpa_supplicant( 1187): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1187): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1187): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
,D/wpa_supplicant( 1187): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1187): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1187): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1187): nl80211: Unsubscribe mgmt frames handle 0xb8e75718 (mode change)
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1187): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8e75718
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1187):   * bssid=c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 1187):   * freq=2412
D/wpa_supplicant( 1187):   * Auth Type 0
D/wpa_supplicant( 1187):   * WPA Versions 0x2
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1187): nl80211: Connect request send successfully
D/wpa_supplicant( 1187): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 1187): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): CTRL_IFACE SET 'pno'='1'
E/wpa_supplicant( 1187): send_and_recv error -16 - cmd 75
D/wpa_supplicant( 1187): nl80211: Sched scan start failed: ret=-16 (Device or resource busy)
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1" Return -1
D/WifiNative-wlan0(  910):    returned false
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  910): doString: LIST_DONGLES
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  910): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (760) for get BSS: id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-62
I/wpa_supplicant( 1187): tsf=0000000649781922
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=11
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-51
I/wpa_supplicant( 1187): tsf=0000000105141144
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=12
I/wpa_supplicant( 1187): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-61
I/wpa_supplicant( 1187): tsf=0000000649781911
,I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1187): ssid=01ABC
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=13
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2427
I/wpa_supplicant( 1187): level=-82
I/wpa_supplicant( 1187): tsf=0000000649781931
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=14
I/wpa_supplicant( 1187): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1187): freq=2462
I/wpa_supplicant( 1187): level=-92
I/wpa_supplicant( 1187): tsf=0000000649781949
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=UPC0039325
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=15
I/wpa_supplicant( 1187): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1187): freq=2462
I/wpa_supplicant( 1187): level=-93
I/wpa_supplicant( 1187): tsf=0000000649781940
I/wpa_supplicant( 1187): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=UPC Wi-Free
I/wpa_supplicant( 1187): ####
,D/WirelessDisplayService(  910): getDiscoveryDongleList
W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  910): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -62, frequency: 2412, timestamp: 649781922, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/WifiStateMachine(  910): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 5220, timestamp: 105141144, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -61, frequency: 2412, timestamp: 649781911, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): == begin of scan result ==
D/WifiStateMachine(  910): == (6) end of scan result ==
D/WifiManager( 1223): getScanResults enter 
D/WifiStateMachine(  910): == begin of scan result ==
D/WifiStateMachine(  910): == (6) end of scan result ==
,D/WirelessDisplayService(  910): getDiscoveryDongleList
D/WifiStateMachine(  910): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2427, timestamp: 649781931, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -92, frequency: 2462, timestamp: 649781949, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 5: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -93, frequency: 2462, timestamp: 649781940, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): add 6 to mScanResults
D/BatSI   (  910): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  910): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/wpa_supplicant( 1187): nl80211: Event message available,
D/wpa_supplicant( 1187): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1187): nl80211: Connect event
I/wpa_supplicant( 1187): wlan0: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
I/wpa_supplicant( 1187): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
I/wpa_supplicant( 1187): State: ASSOCIATING -> DISCONNECTED
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1187): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1187): htc_wext_set_TX_TRACKING (0)+,
I/wpa_supplicant( 1187): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1187): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - EAP success=0
,D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/HTCRequest(  910): WifiMonitor:getBSSIDFromString CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
D/HTCRequest(  910): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:getSSIDFromString CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
,D/HTCRequest(  910): WifiMonitor:getFrequencyFromString CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
D/HTCRequest(  910): WifiMonitor:getFreqFromEventString() 0
D/HTCRequest(  910): WifiMonitor:getStatusCodeFromString CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
D/HTCRequest(  910): WifiMonitor:getStatusCodeFromEventString() 1
,D/HTCRequest(  910): WifiMonitor::handleAssociateRejectEvent: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1 ssid='NG700' freq=0
D/HTCRequest(  910): WifiMonitor::handleAssociateRejectEvent: NetworkID=-1 WifiSSID='NG700' freq=0 BSSID=c0:ff:d4:d3:aa:48 ReasonCode=1 locally_generated=0 frequency=0 macAddress=null
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =DISCONNECTED
D/WifiStateMachine(  910): Enter handleAssociateRejectEvent
D/WifiStateMachine(  910): Message = NetworkID=-1 WifiSSID='NG700' freq=0 BSSID=c0:ff:d4:d3:aa:48 ReasonCode=1 locally_generated=0 frequency=0 macAddress=null
,D/WifiStateMachine(  910): Exit handleAssociateRejectEvent,
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter,
I/wpa_supplicant( 1187): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID,
,D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING,
,D/WifiStateMachine(  910): startScan Pid: 910 Uid 1000
,D/WifiNative-wlan0(  910): doBoolean: SET pno 0
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): CTRL_IFACE SET 'pno'='0'
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
,D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: SCAN
,D/BatSI   (  910): WIFI scan started for: 450a0300 uid:1000
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
D/WifiNative-wlan0(  910):    returned false
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-62
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-70
I/wpa_supplicant( 1187): [NULL] fc:94:e3:11:35:3a freq=2462 level=-92
D/wpa_supplicant( 1187): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=27 entropy=6
D/wpa_supplicant( 1187): Add randomness: count=28 entropy=7
D/wpa_supplicant( 1187): Add randomness: count=29 entropy=8
D/wpa_supplicant( 1187): Add randomness: count=30 entropy=9
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): blist: c0:ff:d4:d3:aa:48 count[1]
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1187):    skip - blacklisted (count=1 limit=0)
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1187): 3: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1187): No APs found - clear blacklist and try again
E/wpa_supplicant( 1187): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1187): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-62
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 3
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): selected network = 1
D/wpa_supplicant( 1187): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48 , bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8e764e8  current_ssid=0x0
D/wpa_supplicant( 1187): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1187): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1187): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1187): check if in concurrent case
I/wpa_supplicant( 1187): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 1187): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1187): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1187): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1187): RSN: PMKSA cache search - network_ctx=0xb8e764e8 try_opportunistic=0
D/wpa_supplicant( 1187): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1187): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1187): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1187): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1187): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1187): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1187): nl80211: Unsubscribe mgmt frames handle 0xb8e75718 (mode change)
D/wpa_supplicant( 1187): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8e75718
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/WifiMonitor(  910): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1187):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1187):   * freq=2412
D/wpa_supplicant( 1187):   * Auth Type 0
D/wpa_supplicant( 1187):   * WPA Versions 0x2
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  910): doBoolean: SET pno 1
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1187): nl80211: Connect request send successfully
D/wpa_supplicant( 1187): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
W/WifiHW  (  910): QCOM Debug wif,i_send_command "IFNAME=wlan0 SET pno 1"
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): CTRL_IFACE SET 'pno'='1'
E/wpa_supplicant( 1187): send_and_recv error -16 - cmd 75
D/wpa_supplicant( 1187): nl80211: Sched scan start failed: ret=-16 (Device or resource busy)
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1" Return -1
D/WifiNative-wlan0(  910):    returned false
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  910): doString: LIST_DONGLES
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  910): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1187): reply (760) for get BSS: id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-62
I/wpa_supplicant( 1187): tsf=0000000654242044
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=11
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-51
I/wpa_supplicant( 1187): tsf=0000000654242017
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=12
I/wpa_supplicant( 1187): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-61
I/wpa_supplicant( 1187): tsf=0000000649781911
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1187): ssid=01ABC
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=13
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2427
I/wpa_supplicant( 1187): level=-70
I/wpa_supplicant( 1187): tsf=0000000654242054
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=14
I/wpa_supplicant( 1187): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1187): freq=2462
I/wpa_supplicant( 1187): level=-92
I/wpa_supplicant( 1187): tsf=0000000654242063
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=UPC0039325,
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=15
I/wpa_supplicant( 1187): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1187): freq=2462
I/wpa_supplicant( 1187): level=-93
I/wpa_supplicant( 1187): tsf=0000000649781940
I/wpa_supplicant( 1187): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=UPC Wi-Free
I/wpa_supplicant( 1187): ####
,D/WirelessDisplayService(  910): getDiscoveryDongleList
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/WifiStateMachine(  910): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -62, frequency: 2412, timestamp: 654242044, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 5220, timestamp: 654242017, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -61, frequency: 2412, timestamp: 649781911, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -70, frequency: 2427, timestamp: 654242054, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -92, frequency: 2462, timestamp: 654242063, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 5: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -93, frequency: 2462, timestamp: 649781940, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): add 6 to mScanResults
D/BatSI   (  910): WIFI scan stopped for: 440a0300 uid:1000
,D/WifiStateMachine(  910): == begin of scan result ==
D/WifiStateMachine(  910): == (6) end of scan result ==
,D/WifiManager( 1223): getScanResults enter ,
D/WifiStateMachine(  910): == begin of scan result ==
D/WifiStateMachine(  910): == (6) end of scan result ==
,D/WirelessDisplayService(  910): getDiscoveryDongleList,
D/WifiNotificationController(  910): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/wpa_supplicant( 1187): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1187): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1187): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1187): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1187): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1187): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1187): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1187): nl80211: Connect event
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1187): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1187): netlink: Operstate: linkmode=-1, operstate=5
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1187): Add randomness: count=31 entropy=10
I/wpa_supplicant( 1187): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1187): TDLS: Remove peers on association
D/wpa_supplicant( 1187): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  910): [isWifi] getHotspotEnabled: false
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1187): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1187): EAPOL: enable timer tick
D/wpa_supplicant( 1187): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1187): htc_wext_set_keepalive +
I/wpa_supplicant( 1187): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1187): getPrivFuncNum +	
I/wpa_supplicant( 1187): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1187): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1187): htc_wext_set_keepalive - ret = 0
,I/wpa_supplicant( 1187): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1187): Get randomness: len=32 entropy=11
D/Tethering(  910): interfaceLinkStateChanged wlan0, true
D/Tethering(  910): interfaceStatusChanged wlan0, true
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  910): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  910): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/HTCRequest(  910): WifiMonitor:getFreqFromEventString() 2412
,D/HTCRequest(  910): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  910): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  910): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  910): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  910): Enter handleAssociatedWithEvent
D/WifiStateMachine(  910): Associated
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  910): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  910): Exit handleAssociatedWithEvent
,D/WifiStateMachine(  910): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/WifiStateMachine(  910): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiApDatabaseHandler(  910): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  910): This record is existed, only update it...
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
I/wpa_supplicant( 1187): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb8e759f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 1187):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1187): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1187): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f13b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1187):    broadcast key
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1187): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1187): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1187): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1187): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiMonitor(  910): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1187): netlink: Operstate: linkmode=-1, operstate=6
,I/wpa_supplicant( 1187): set send_ind_to_ndc = 0
I/wpa_supplicant( 1187): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1187): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1187): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1187): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1187): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1187): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1187): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1187): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1187): EAPOL authentication completed successfully
I/wpa_supplicant( 1187): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1187): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1187): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1187): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/Tethering(  910): interfaceLinkStateChanged wlan0, true
D/Tethering(  910): interfaceStatusChanged wlan0, true
,D/Tethering(  910): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  910): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false,
D/WifiStateMachine(  910): WifiApDatabaseHandler, WiFi AP database Inserting ..
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiApDatabaseHandler(  910): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  910): This record is existed, only update it...
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/WISPrService( 3752): >>>>>WISPrService start isConnected = false<<<<<
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  910): Provision feature enable=false
,D/ConnectivityService(  910): mActiveDefaultNetwork: -1
D/WISPrService( 3752): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/WifiNative-wlan0(  910): doBoolean: SET pno 0
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1187): CTRL_IFACE SET 'pno'='0'
,D/WifiNative-wlan0(  910):    returned true
,D/DhcpStateMachine(  910): [StoppedState] Start DHCP
,D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
,D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): Power_Mode_Type mode = 1
I/wpa_supplicant( 1187): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/wpa_supplicant( 1187): nl80211: Event message available
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/wpa_supplicant( 1187): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  910):    returned null
E/WifiStateMachine(  910): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING STOP
D/WifiStateMachine(  910): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  910): acquireWL(43da7b78): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 910 1000 null
D/WifiStateMachine(  910): handlePreDhcpSetup mBluetoothConnectionActive: false
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  910):    returned null
D/WifiP2pService(  910): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42ec7a68 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42ec7a68 target=com.android.internal.util.StateMachine$SmHandler }
,D/wpa_supplicant( 1187): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1187): EAPOL: disable timer tick
,D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  910): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1187): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiP2pService(  910): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  910): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  910):    returned true
,D/WifiStateMachine(  910): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): releaseWL(43da7b78): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=50 [4][2][0]
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -61 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): gateway: /192.168.1.1
D/WifiNative-wlan0(  910): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1187): htc_wext_set_keepalive +
I/wpa_supplicant( 1187): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1187): getPrivFuncNum +	
I/wpa_supplicant( 1187): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1187): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1187): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1187): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1187): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  910): VerifyingLinkState enter
D/WifiStateMachine(  910): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  910): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  910): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -61, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,D/WifiWatchdogStateMachine(  910): WAN detection
D/ConnectivityService(  910): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  910): Provision feature enable=false
D/ConnectivityService(  910): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  910): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  910): default: teardown()
D/MDST    (  910): default: setTeardownRequested(true)
D/MDST    (  910): default: setEnableApn apnType =default , enable=false
V/NetworkPolicy(  910): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/MDST    (  910): default: setTeardownRequested(true)
D/ConnectivityService(  910): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
,D/WISPrService( 3752): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
E/ConnectivityService(  910): Unexpected mtu value: android.net.wifi.WifiStateTracker@42d69fc8
D/ConnectivityService(  910): handleConnectivityChange: netType=1 doReset=false resetMask=0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,I/wpa_supplicant( 1187): Change stage from stage0 to stage3
D/WifiStateMachine(  910): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  910): syncGetConfiguredNetworks
,D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  910): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  910): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  910): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  910): handleConnectivityChange: resetting
D/Nat464Xlat(  910): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  910): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
,D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/QuickSettingWifi( 1117): receive.wifiConnect:true wifiAPname:NG700 elapse:2
D/WirelessDisplayService(  910): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  910):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/PMS     (  910): acquireWL(43b46d10): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/ConnectivityService(  910): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4492/10079)
D/ConnectivityService(  910): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  910): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/PMS     (  910): acquireWL(43f4af80): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2157 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,I/CheckinService( 2157): Checkin interval check for package: unspecified last checkin: 1450463947817 min interval config: 0 actual interval: 251821
D/PMS     (  910): releaseWL(43b46d10): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  910): acquireWL(43e39cb8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2157 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43f4af80): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
I/logwrapper(  363): /system/bin/ip terminated by exit(254)
I/CheckinService( 2157): Checking schedule, now: 1450464199645 next: 1450463977781
I/CheckinService( 2157): active receiver: enabled
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2157, uid=10029, userID:0
,D/ConnectivityService(  910): mActiveDefaultNetwork: WIFI
,I/CheckinService( 2157): Preparing to send checkin request
,I/EventLogService( 2157): Accumulating logs since 1450463976107
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
,I/CheckinRequestBuilder( 2157): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  910): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2157): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  910): getNetworkInfo networkType=9 called by com.google.android.gms (2157/10029)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=100 [1][1][0]
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  371): PrepareKeyRequest: nonce=175520354
,I/Adreno-EGL( 4583): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4583): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4583): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4583): Local Branch: 
I/Adreno-EGL( 4583): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4583): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4583):                  aa63bbd948f41d15fc72f585e
,I/WVCdm   (  371): CdmEngine::CloseSession
,I/Adreno-EGL( 4583): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4583): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4583): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4583): Local Branch: 
I/Adreno-EGL( 4583): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4583): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4583):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4583): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4583): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4583): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4583): Local Branch: 
I/Adreno-EGL( 4583): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4583): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4583):                  aa63bbd948f41d15fc72f585e
,D/PMS     (  910): releaseWL(42ff4018): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  910): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/AlarmManager(  910): [AlarmQueuing] connectivity wifi: true
,V/Tethering(  910): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
V/Tethering(  910): bSetPropertyMultiRAB:false
,D/Tethering(  910): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/Tethering(  910): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  910): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  910): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  910): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  910): Found interface wlan0
,D/Tethering(  910): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,I/ConnectivityHelper( 1272): [onReceive] WIFI(1): CONNECTED
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/CaptivePortalTracker(  910): NoActiveNetworkState
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.launcher (1272/10076)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1601/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4492/10079)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/PMS     (  910): acquireWL(446af758): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.google.android.music (4424/10154)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (4583/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(44596c68): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,I/NetworkMonitor( 4424): type=WIFI subType= reason=null isConnected=true
D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/GpsLocationProvider(  910): [handleMessage] UPDATE_NETWORK_STATE
W/Settings( 4583): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/GpsLocationProvider(  910): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  910): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  910): ignore wifi update if we are not in OPENING or CLOSING
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
I/wpa_supplicant( 1187): Change stage from stage3 to stage1
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
D/PMS     (  910): releaseWL(44596c68): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  910): releaseWL(446af758): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (2712/10021)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/AutoSetting( 1329): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/MobileConnectivityChangeReceiver( 4492): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4492): onReceive CONNECTIVITY_CHANGE networkType=1
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1329/10055)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
I/WVCdm   (  371): CdmEngine::OpenSession
D/AutoSetting( 1329): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1329): service - onStartCommand() screen is off, don't request location
I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
D/AutoSetting( 1329): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1329): service - onStartCommand() check timezone in 30000
I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1329/10055)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4531/10151)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (3531/10160)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (3531/10160)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/CheckinService( 2157): Checkin interval check for package: unspecified last checkin: 1450463947817 min interval config: 0 actual interval: 252928
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/PMS     (  910): acquireWL(42bf6470): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2157 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(42bf6470): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/iu.Environment( 2157): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2157, uid=10029, userID:0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
I/iu.UploadsManager( 2157): num queued entries: 0
I/iu.UploadsManager( 2157): num updated entries: 0
I/iu.SyncManager( 2157): NEXT; no task
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/libc    ( 1359): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1359): [NET] getaddrinfo-,err=8
D/libc    ( 1359): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1359): [NET] getaddrinfo-, 1
D/libc    ( 1359): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/PMS     (  910): acquireWL(429bfdf0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/libc    (  363): [NET] +++++ res_nsend xid =82eb +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
,D/WVCdm   (  371): PrepareKeyRequest: nonce=4004886549
,I/WVCdm   (  371): CdmEngine::CloseSession
,I/CheckinRequestBuilder( 2157): Classify the device as Phone.
,D/libc    ( 2157): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
V/NativeCrypto( 2157): SSL shutdown failed: ssl=0x66c9f9e8: I/O error during system call, Connection timed out
,D/libc    ( 2157): [NET] getaddrinfo-,err=8
D/libc    ( 2157): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2157): [NET] getaddrinfo-, 1
D/libc    ( 2157): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =50f +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 295
D/libc    (  363): [NET]res_nsend:resplen=79
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]res_nsend:resplen=84
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1359): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2157): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1359): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1359): [NET] getaddrinfo-,err=8
,D/libc    ( 2157): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2157): [NET] getaddrinfo-,err=8
,D/libc    ( 1359): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1359): [NET] getaddrinfo-,err=8
D/libc    ( 2157): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2157): [NET] getaddrinfo-,err=8
D/libc    ( 2157): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2157): [NET] getaddrinfo-,err=8
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,I/CheckinTask( 2157): Sending checkin request (12207 bytes)
,D/WifiStateMachine(  910): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  910): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-,err=8
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  910): [NET] getaddrinfo-, 1
,D/libc    (  910): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =3e9e +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/PMS     (  910): acquireWL(42ea9a98): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/PMS     (  910): releaseWL(429bfdf0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1359/10029)
,D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  910): handleInetConditionChange: starting a change hold
,D/PMS     (  910): releaseWL(42ea9a98): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(4499c860): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1359/10029)
,D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1359/10029)
,D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029,
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
,D/PMS     (  910): releaseWL(4499c860): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=27 [33][9][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=172
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  910): Find DNS Address www.htc.com/23.59.123.86
,I/CheckinRequestBuilder( 2157): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  910): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2157): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  910): getNetworkInfo networkType=9 called by com.google.android.gms (2157/10029)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=33 [3][1][0]
I/wpa_supplicant( 1187): Change stage from stage1 to stage3
,I/CheckinRequestBuilder( 2157): Classify the device as Phone.
,I/CheckinTask( 2157): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2157): Checking schedule, now: 1450464203711 next: 1450987140706
,I/CheckinService( 2157): active receiver: disabled
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2157, uid=10029, userID:0
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
,I/CheckinService( 2157): Checking schedule, now: 1450464203737 next: 1450987140706
,I/CheckinService( 2157): active receiver: disabled
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2157, uid=10029, userID:0
,D/CheckinService( 2157): Recording last checkin time for package unspecified as 1450464203743
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
,D/PMS     (  910): releaseWL(43e39cb8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
,D/GCM     ( 1359): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{43f9b150 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1342): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  910): acquireWL(42f4a1c0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4663 10111 null
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "sms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1272): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,W/AccTypeManager( 1342): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1342): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,W/SystemReader( 1256): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mmsto"
,I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/Launcher( 1272): Deferring update until onResume
,D/Launcher( 1272): waitUntilResume // bindAppsUpdated
D/PMS     (  910): releaseWL(42f4a1c0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/[PluginManager]RegisterService( 1329): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1329): handle notify Blinkfeed plugin client changed
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "sms"
,I/IcingCorporaProvider( 2808): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "smsto"
,E/ExternalAccountType( 1342): Unsupported attribute readOnly
,I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,D/PhoneApp( 1238): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/ActivityManager(  910): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  910): acquireWL(442cfe70): PARTIAL_WAKE_LOCK  Icing 0x1 2157 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42d21818): PARTIAL_WAKE_LOCK  AsyncService 0x1 3531 10160 null
,D/PMS     (  910): releaseWL(42d21818): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/PackageBroadcastService( 2157): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 2157): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  910): Resuming delayed broadcast
,I/Icing   ( 2157): updateResources: need to parse f{com.google.android.gms}
,W/PackageManager(  910): Unable to load service info ResolveInfo{4429d2d0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  910): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  910): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  910): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  910): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  910): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  910): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  910): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  910): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  910): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  910): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  910): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  910): 	at dalvik.system.NativeStart.main(Native Method)
,I/IcingCorporaProvider( 2808): UpdateCorporaTask done [took 531 ms] updated apps [took 530 ms] 
,D/RemoteDisplayProvider(  910): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  910): start
,I/GCoreNlp( 1223): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  910): applying state to connected service
D/PMS     (  910): acquireWL(42f16270): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(42f16270): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  910): applying state to connected service
,D/PMS     (  910): acquireWL(449b89f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(449b89f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(445784e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(445784e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  910): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/Icing   ( 2157): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1272): loadItems() com.htc.launcher.pageview.WidgetManager@42476d50 +
,I/Prism.WidgetManager( 1272): onLoadItems() +
,I/Icing   ( 2157): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  910): releaseWL(442cfe70): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1272): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1272): onLoadItems() -
,I/Prism.ItemManager( 1272): loadItems() com.htc.launcher.pageview.WidgetManager@42476d50 -
,D/PhoneApp( 1238): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1238): -- N1 =0
,D/PhoneApp( 1238): -- N2 =0
,D/PhoneApp( 1238): -- N3 =0
,D/PMS     (  910): acquireWL(43d78e20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43d78e20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/AutoSetting( 1329): service - mHandler: update timezone
D/AutoSetting( 1329): service - handleMessage() stop self
D/AutoSetting( 1329): service - onDestroy() END
,D/AutoSetting( 1329): service - handleMessage() quit looper
,D/AutoSetting( 1519): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1519): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1519): service - onCreate(),
D/AutoSetting( 1519): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1519): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
,D/DotMatrix( 1589): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1589): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,D/AutoSetting( 1519): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1519): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1519): service - mHandler: update timezone
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1519): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1519): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1519): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1519): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1589): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1589): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1117): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{4268d308 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.htclocationservice 3 7 2 11
,D/PMS     (  910): acquireWL(4430c018): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42b980a8: PendingIntentRecord{42807810 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=697161, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(4430c018): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1187): nl80211: Disconnect event
I/wpa_supplicant( 1187): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
I/wpa_supplicant( 1187): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
I/wpa_supplicant( 1187): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 1187): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1187): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1187): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1187): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1187): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8e74bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1187):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1187): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1187): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1187): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1187): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1187): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1187): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1187): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1187): nl80211: if_removed already cleared - ignore event
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
D/HTCRequest(  910): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getReasonFromString CTRL-EV,ENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getReasonFromEventString() 0
D/HTCRequest(  910): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  910): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/WifiStateMachine(  910): Enter handleNetworkDisconnect
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): Power_Mode_Type mode = 0
I/wpa_supplicant( 1187): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 61
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  910):    returned true
D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/WifiP2pService(  910): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1187): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1187): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1187): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1187): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1187): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/DhcpStateMachine(  910): [RunningState] Stop DHCP
D/wpa_supplicant( 1187): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 1187): Wireless event: cmd=0x8b15 len=20
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
,D/Tethering(  910): interfaceStatusChanged wlan0, false
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
E/NativeDaemonConnector.ResponseQueue(  910): more buffered than allowed: 10 >= 10
,E/NativeDaemonConnector.ResponseQueue(  910): Removing request: null (14)
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  910): stopDataStallAlarm: current tag=20076 mDataStallAlarmIntent=null
D/WifiStateMachine(  910): Exit handleNetworkDisconnect
,D/WifiPerfLock(  910): release()
D/WifiStateMachine(  910): PerfLock released for exiting ConnectedState
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  910): Provision feature enable=false
D/ConnectivityService(  910): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/libc    (  910): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): Power_Mode_Type mode = 0
I/wpa_supplicant( 1187): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  910):    returned true
D/UsbnetStateTracker(  910): isAvailable+-
D/UsbnetStateTracker(  910): reconnect
,D/UsbnetStateTracker(  910): isAvailable+-
D/ConnectivityService(  910): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/PMS     (  910): acquireWL(4492c970): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 910 1000 null
D/WifiP2pService(  910): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  910): default: reconnect()
D/MDST    (  910): default: setTeardownRequested(false)
D/MDST    (  910): default: setEnableApn apnType =default , enable=true
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  910): doBoolean: SET pno 1
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): CTRL_IFACE SET 'pno'='1'
D/ConnectivityService(  910): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  910): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  910): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
E/NativeDaemonConnector.ResponseQueue(  910): more buffered than allowed: 11 >= 10
E/NativeDaemonConnector.ResponseQueue(  910): Removing request: null (27)
E/NativeDaemonConnector.ResponseQueue(  910): more buffered than allowed: 10 >= 10
E/NativeDaemonConnector.ResponseQueue(  910): Removing request: null (30)
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '95 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 95 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
,D/ConnectivityService(  910): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WISPrService( 3752): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 3752): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1187): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 3752): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
D/WISPrService( 3752): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,V/NativeCrypto( 1359): Read error: ssl=0x6423fd70: I/O error during system call, Connection timed out
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '96 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 96 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '97 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 97 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): handleConnectivityChange: resetting
D/ConnectivityService(  910): resetConnections(wlan0, 3)
V/NativeCrypto( 1359): SSL shutdown failed: ssl=0x6423fd70: I/O error during system call, Broken pipe
D/libc    (  363): [NET] entry_id:1   entry:0xb8748f68  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb8749018  removed 
D/libc    (  363): [NET] entry_id:3   entry:0xb8744458  removed 
,D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
D/PMS     (  910): acquireWL(4419c070): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): flush DNS cache for net 1(wlan0)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
D/Nat464Xlat(  910): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  910): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
D/ConnectivityService(  910): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  910): acquireWL(4348ed00): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  910): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:0
D/WirelessDisplayService(  910): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  910): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WifiStateMachine(  910): startScan Pid: 910 Uid 1000
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4492/10079)
D/ConnectivityService(  910): reportInetCondition for net -1, percentage: 0 by  (1359/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/WifiNative-wlan0(  910): doBoolean: SET pno 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 76
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
D/wpa_supplicant( 1187): nl80211: Sched scan stop sent (ret=0)
I/wpa_supplicant( 1187): wpa_supplicant_scan enter
D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: SCAN
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1187): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1187): Failed to initiate AP scan
,I/wpa_supplicant( 1187): Failed to initiate AP scan, Failed_to_scan_counter:1
,D/WifiNative-wlan0(  910):    returned true
I//system/bin/ip(  363): RTNETLINK answers: No such process
D/PMS     (  910): releaseWL(4419c070): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/BatSI   (  910): WIFI scan started for: 450a0300 uid:1000
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
I/logwrapper(  363): /system/bin/ip terminated by exit(2)
I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
,D/PMS     (  910): releaseWL(4348ed00): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  910): mActiveDefaultNetwork: -1
,D/ConnectivityService(  910): handleInetConditionChange: no active default network - ignore
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
V/Tethering(  910): mTetherableUsbRegexs:{(usb0)(ncm0)}
,I/AlarmManager(  910): [AlarmQueuing] connectivity wifi: false
D/Tethering(  910): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  910): bSetPropertyMultiRAB:false
,D/Tethering(  910): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
,D/GpsLocationProvider(  910): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  910): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  910): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  910): ignore wifi update if we are not in OPENING or CLOSING
I/Tethering(  910): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  910): ipv4Default null
I/Tethering(  910): No IPv4 upstream interface, giving up.
D/Tethering(  910): TetherMasterSM: InitialState processMessage what=3
I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1187): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1187): Failed to initiate AP scan
I/wpa_supplicant( 1187): Failed to initiate AP scan, Failed_to_scan_counter:2
D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
D/CaptivePortalTracker(  910): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
I/NetworkMonitor( 4424): type=WIFI subType= reason=null isConnected=false
,D/CaptivePortalTracker(  910): NoActiveNetworkState
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.google.android.music (4424/10154)
D/PMS     (  910): acquireWL(43376c00): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): releaseWL(43376c00): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
,I/ConnectivityHelper( 1272): [onReceive] WIFI(1): DISCONNECTED
,D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1601/10029)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.launcher (1272/10076)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4492/10079)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  910): getActiveNetworkInfo called by  (2712/10021)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/AutoSetting( 1329): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4492): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4492): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1329): Util - no network available!
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1329/10055)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1329/10055)
,D/AutoSetting( 1329): service - onCreate()
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4531/10151)
D/AutoSetting( 1329): service - AddressCache: using context: com.htc.Weather
D/AutoSetting( 1329): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/LocationManagerService(  910): request 42dc2be8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/LocationManagerService(  910): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1329): service - mHandler: cancel location update
,D/AutoSetting( 1329): service -           changes count: 0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (3531/10160)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (3531/10160)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
,I/iu.Environment( 2157): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
I/iu.UploadsManager( 2157): num queued entries: 0
,I/iu.UploadsManager( 2157): num updated entries: 0
,I/iu.SyncManager( 2157): NEXT; no task
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
,I/wpa_supplicant( 1187): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1187): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1187): Failed to initiate AP scan
,I/wpa_supplicant( 1187): Failed to initiate AP scan, Failed_to_scan_counter:3
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-62
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-70
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=32 entropy=0
D/wpa_supplicant( 1187): Add randomness: count=33 entropy=1
D/wpa_supplicant( 1187): Add randomness: count=34 entropy=2
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): blist: c0:ff:d4:d3:aa:48 count[1]
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1187):    skip - blacklisted (count=1 limit=0)
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): No APs found - clear blacklist and try again
E/wpa_supplicant( 1187): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1187): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-62
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 3
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): selected network = 1
D/wpa_supplicant( 1187): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8e764e8  current_ssid=0x0
D/wpa_sup,plicant( 1187): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1187): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1187): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1187): check if in concurrent case
I/wpa_supplicant( 1187): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiNative-wlan0(  910): doBoolean: SET pno 1
D/WifiMonitor(  910): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1187): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1187): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1187): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1187): RSN: PMKSA cache search - network_ctx=0xb8e764e8 try_opportunistic=0
D/wpa_supplicant( 1187): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1187): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1187): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1187): netlink: Operstate: linkmode=-1, operstate=5
,D/wpa_supplicant( 1187): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1187): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1187): nl80211: Unsubscribe mgmt frames handle 0xb8e75718 (mode change)
D/wpa_supplicant( 1187): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8e75718
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1187):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1187):   * freq=2412
D/wpa_supplicant( 1187):   * Auth Type 0
,D/wpa_supplicant( 1187):   * WPA Versions 0x2
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1187): nl80211: Connect request send successfully
D/wpa_supplicant( 1187): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 1187): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): CTRL_IFACE SET 'pno'='1'
E/wpa_supplicant( 1187): send_and_recv error -16 - cmd 75
D/wpa_supplicant( 1187): nl80211: Sched scan start failed: ret=-16 (Device or resource busy)
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1" Return -1
,D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiNative-wlan0(  910):    returned false
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  910): doString: LIST_DONGLES
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  910): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (521) for get BSS: id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-62
I/wpa_supplicant( 1187): tsf=0000000702792604
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=11,
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-51
I/wpa_supplicant( 1187): tsf=0000000702792579
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=13
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2427
I/wpa_supplicant( 1187): level=-70
I/wpa_supplicant( 1187): tsf=0000000702792617
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=14
I/wpa_supplicant( 1187): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1187): freq=2462
I/wpa_supplicant( 1187): level=-92
I/wpa_supplicant( 1187): tsf=0000000654242063
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=UPC0039325
I/wpa_supplicant( 1187): ####
,D/WirelessDisplayService(  910): getDiscoveryDongleList
W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  910): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -62, frequency: 2412, timestamp: 702792604, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/WifiStateMachine(  910): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 5220, timestamp: 702792579, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): == begin of scan result ==
,D/WifiStateMachine(  910): == (4) end of scan result ==
,D/WifiManager( 1223): getScanResults enter 
D/WifiStateMachine(  910): == begin of scan result ==
,D/WifiStateMachine(  910): == (4) end of scan result ==
D/WifiStateMachine(  910): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -70, frequency: 2427, timestamp: 702792617, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -92, frequency: 2462, timestamp: 654242063, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): add 4 to mScanResults
D/BatSI   (  910): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  910): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  910): getDiscoveryDongleList
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/wpa_supplicant( 1187): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1187): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1187): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1187): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1187): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1187): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1187): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1187): nl80211: Connect event
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1187): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1187): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1187): Add randomness: count=35 entropy=3
I/wpa_supplicant( 1187): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412,
D/wpa_supplicant( 1187): TDLS: Remove peers on association
D/wpa_supplicant( 1187): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - EAP success=0
,D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1187): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1187): EAPOL: enable timer tick
D/wpa_supplicant( 1187): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1187): htc_wext_set_keepalive +
I/wpa_supplicant( 1187): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1187): getPrivFuncNum +	
,I/wpa_supplicant( 1187): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1187): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1187): htc_wext_set_keepalive - ret = 0
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
I/wpa_supplicant( 1187): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1187): Get randomness: len=32 entropy=4
D/WifiMonitor(  910): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  910): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  910): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
D/WifiMonitor(  910): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  910): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  910): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  910): Enter handleAssociatedWithEvent
D/WifiStateMachine(  910): Associated
,D/WifiStateMachine(  910): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  910): Exit handleAssociatedWithEvent
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  910): BSSID was changed, update WiFi database
D/Tethering(  910): interfaceLinkStateChanged wlan0, true
D/Tethering(  910): interfaceStatusChanged wlan0, true
D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/Tethering(  910): [isWifi] getHotspotEnabled: false
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
I/wpa_supplicant( 1187): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/WifiStateMachine(  910): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb8e759f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 1187):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1187): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1187): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f13b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1187):    broadcast key
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1187): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1187): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1187): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/WifiMonitor(  910): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1187): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiApDatabaseHandler(  910): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  910): This record is existed, only update it...
E/wpa_supplicant( 1187): wlan0: Connect to SSID: NG700
,D/wpa_supplicant( 1187): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1187): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1187): set send_ind_to_ndc = 0
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1187): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1187): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1187): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1187): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1187): EAPOL: SUPP_BE entering state SUCCESS
,D/wpa_supplicant( 1187): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1187): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1187): EAPOL authentication completed successfully
I/wpa_supplicant( 1187): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 79
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1187): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1187): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/wpa_supplicant( 1187): nl80211: if_removed already cleared - ignore event
D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/Tethering(  910): interfaceLinkStateChanged wlan0, true
D/Tethering(  910): interfaceStatusChanged wlan0, true
,D/Tethering(  910): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
,D/WifiApDatabaseHandler(  910): updateConnectedAP...,
,D/WifiStateMachine(  910): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiStateMachine(  910): WifiApDatabaseHandler, WiFi AP database Inserting ..
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  910): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  910): Provision feature enable=false
,D/ConnectivityService(  910): mActiveDefaultNetwork: -1
D/WifiApDatabaseHandler(  910): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  910): This record is existed, only update it...
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/WISPrService( 3752): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3752): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{444231f8 u0 com.htc.htclocationservice/.AutoSettingService}
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/WifiNative-wlan0(  910): doBoolean: SET pno 0
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1187): CTRL_IFACE SET 'pno'='0'
,D/WifiNative-wlan0(  910):    returned true
,D/DhcpStateMachine(  910): [StoppedState] Start DHCP
,D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 1
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): Power_Mode_Type mode = 1
I/wpa_supplicant( 1187): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 61
D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1187): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  910):    returned null
E/WifiStateMachine(  910): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING STOP
D/WifiStateMachine(  910): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  910): acquireWL(4392f100): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 910 1000 null
,D/WifiStateMachine(  910): handlePreDhcpSetup mBluetoothConnectionActive: false
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/WifiNative-wlan0(  910):    returned null
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
D/WifiP2pService(  910): InactiveState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42ec7a68 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-3ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42ec7a68 target=com.android.internal.util.StateMachine$SmHandler }
,D/wpa_supplicant( 1187): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1187): EAPOL: disable timer tick
,D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  910): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1187): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  910): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  910): releaseWL(4392f100): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [4][0][0]
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -62 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): gateway: /192.168.1.1
D/WifiNative-wlan0(  910): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1187): htc_wext_set_keepalive +
I/wpa_supplicant( 1187): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1187): getPrivFuncNum +	
I/wpa_supplicant( 1187): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1187): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1187): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1187): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1187): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  910): VerifyingLinkState enter
D/WifiStateMachine(  910): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  910): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  910): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -62, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiWatchdogStateMachine(  910): WAN detection
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED connected
V/NetworkPolicy(  910): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  910): Provision feature enable=false
D/ConnectivityService(  910): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
,V/ConnectivityService(  910): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  910): default: teardown()
D/MDST    (  910): default: setTeardownRequested(true)
D/MDST    (  910): default: setEnableApn apnType =default , enable=false
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/WISPrService( 3752): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/MDST    (  910): default: setTeardownRequested(true)
D/ConnectivityService(  910): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  910): Unexpected mtu value: android.net.wifi.WifiStateTracker@42d69fc8
,D/ConnectivityService(  910): handleConnectivityChange: netType=1 doReset=false resetMask=0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
I/wpa_supplicant( 1187): Change stage from stage0 to stage3
D/WifiStateMachine(  910): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  910): syncGetConfiguredNetworks
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  910): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  910): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  910): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  910): handleConnectivityChange: resetting
D/Nat464Xlat(  910): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  910): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/WirelessDisplayService(  910): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  910):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  910): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  910): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  910): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  910): acquireWL(43ecb938): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4492/10079)
I/QuickSettingWifi( 1117): receive.wifiConnect:true wifiAPname:NG700 elapse:2
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=100 [1][1][0]
,D/PMS     (  910): acquireWL(44938300): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2157 10029 WorkSource{10029 com.google.android.gms}
,I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
,I/logwrapper(  363): /system/bin/ip terminated by exit(254)
,I/CheckinService( 2157): Checkin interval check for package: unspecified last checkin: 1450464203743 min interval config: 0 actual interval: 44502
D/PMS     (  910): acquireWL(42faa3b8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2157 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(44938300): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2157): Checking schedule, now: 1450464248257 next: 1450464233706
,I/CheckinService( 2157): active receiver: enabled
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2157, uid=10029, userID:0
,I/CheckinService( 2157): Preparing to send checkin request
,I/EventLogService( 2157): Accumulating logs since 1450464199778
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/ConnectivityService(  910): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  910): releaseWL(43ecb938): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,I/CheckinRequestBuilder( 2157): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  910): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2157): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  910): getNetworkInfo networkType=9 called by com.google.android.gms (2157/10029)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  371): PrepareKeyRequest: nonce=624843439
,I/Adreno-EGL( 4583): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4583): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4583): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4583): Local Branch: 
I/Adreno-EGL( 4583): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4583): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4583):                  aa63bbd948f41d15fc72f585e
,I/WVCdm   (  371): CdmEngine::CloseSession
,I/Adreno-EGL( 4583): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4583): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4583): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4583): Local Branch: 
I/Adreno-EGL( 4583): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4583): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4583):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4583): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4583): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4583): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4583): Local Branch: 
I/Adreno-EGL( 4583): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4583): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4583):                  aa63bbd948f41d15fc72f585e
,W/Settings( 4583): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (4583/10029)
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
D/PMS     (  910): releaseWL(4492c970): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
D/ConnectivityService(  910): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/AlarmManager(  910): [AlarmQueuing] connectivity wifi: true
,D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
,D/GpsLocationProvider(  910): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  910): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
V/Tethering(  910): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/GpsLocationProvider(  910): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  910): ignore wifi update if we are not in OPENING or CLOSING
,D/CaptivePortalTracker(  910): NoActiveNetworkState
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(43a3d440): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/PMS     (  910): releaseWL(43a3d440): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1601/10029)
I/ConnectivityHelper( 1272): [onReceive] WIFI(1): CONNECTED
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.launcher (1272/10076)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4492/10079)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(43eccc18): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,V/Tethering(  910): bSetPropertyMultiRAB:false
,D/Tethering(  910): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,I/Tethering(  910): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/Tethering(  910): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
,I/Tethering(  910): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  910): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  910): Found interface wlan0
D/Tethering(  910): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/NetworkMonitor( 4424): type=WIFI subType= reason=null isConnected=true
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.google.android.music (4424/10154)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/WVCdm   (  371): PrepareKeyRequest: nonce=35932259
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
D/PMS     (  910): releaseWL(43eccc18): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,I/WVCdm   (  371): CdmEngine::CloseSession
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (2712/10021)
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,I/CheckinRequestBuilder( 2157): Classify the device as Phone.
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/AutoSetting( 1329): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/AutoSetting( 1329): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/MobileConnectivityChangeReceiver( 4492): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/AutoSetting( 1329): service - onStartCommand() screen is off, don't request location
,D/MobileConnectivityChangeReceiver( 4492): onReceive CONNECTIVITY_CHANGE networkType=1
D/libc    ( 2157): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2157): [NET] getaddrinfo-,err=8
D/libc    ( 2157): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2157): [NET] getaddrinfo-, 1
,D/libc    ( 2157): [NET] getaddrinfo_proxy+
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1329/10055)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1329/10055)
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/AutoSetting( 1329): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1329): service - onStartCommand() check timezone in 30000
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
V/NativeCrypto( 2157): SSL shutdown failed: ssl=0x66cc2ad8: I/O error during system call, Connection timed out
D/libc    (  363): [NET] +++++ res_nsend xid =494b +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4531/10151)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=50 [2][1][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (3531/10160)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (3531/10160)
,D/PMS     (  910): acquireWL(447d65c0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2157 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2157): Checkin interval check for package: unspecified last checkin: 1450464203743 min interval config: 0 actual interval: 45728
D/PMS     (  910): releaseWL(447d65c0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2157, uid=10029, userID:0
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 251
D/libc    (  363): [NET]res_nsend:resplen=84
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 2157): [NET] getaddrinfo_proxy-, success
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,I/iu.Environment( 2157): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,I/iu.UploadsManager( 2157): num queued entries: 0
,I/iu.UploadsManager( 2157): num updated entries: 0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
I/iu.SyncManager( 2157): NEXT; no task
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/libc    ( 2157): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2157): [NET] getaddrinfo-,err=8
D/libc    ( 1359): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1359): [NET] getaddrinfo-,err=8
D/libc    ( 1359): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1359): [NET] getaddrinfo-, 1
,D/libc    ( 1359): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =3302 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/PMS     (  910): acquireWL(44596c68): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/libc    ( 2157): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2157): [NET] getaddrinfo-,err=8
D/libc    ( 2157): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2157): [NET] getaddrinfo-,err=8
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=79
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1359): [NET] getaddrinfo_proxy-, success
,I/CheckinTask( 2157): Sending checkin request (12206 bytes)
,D/libc    ( 1359): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1359): [NET] getaddrinfo-,err=8
,I/CheckinRequestBuilder( 2157): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  910): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2157): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  910): getNetworkInfo networkType=9 called by com.google.android.gms (2157/10029)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=14 [21][3][0]
,I/CheckinRequestBuilder( 2157): Classify the device as Phone.
,I/CheckinTask( 2157): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 2157): Checking schedule, now: 1450464250271 next: 1450987187266
,I/CheckinService( 2157): active receiver: disabled
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2157, uid=10029, userID:0
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
,I/CheckinService( 2157): Checking schedule, now: 1450464250297 next: 1450987187266
,I/CheckinService( 2157): active receiver: disabled
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2157, uid=10029, userID:0
,D/CheckinService( 2157): Recording last checkin time for package unspecified as 1450464250302
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
,D/PMS     (  910): releaseWL(42faa3b8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
,D/GCM     ( 1359): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc    ( 1359): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1359): [NET] getaddrinfo-,err=8
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/PMS     (  910): acquireWL(44530540): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/PMS     (  910): releaseWL(44596c68): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1359/10029)
,D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  910): handleInetConditionChange: starting a change hold
,D/PMS     (  910): releaseWL(44530540): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(4441b370): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1359/10029)
,D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1359/10029)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
,D/PMS     (  910): releaseWL(4441b370): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [7][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-,err=8
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  910): [NET] getaddrinfo-, 1
,D/libc    (  910): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =91bc +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=172
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  910): Find DNS Address www.htc.com/23.59.123.86
,D/WifiStateMachine(  910): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  910): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
,I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1272): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,D/AccTypeManager( 1342): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Launcher( 1272): Deferring update until onResume
,D/Launcher( 1272): waitUntilResume // bindAppsUpdated
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "sms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,D/PMS     (  910): acquireWL(42cda980): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4663 10111 null
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,W/SystemReader( 1256): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mmsto"
W/AccTypeManager( 1342): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1342): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/ActivityManager(  910): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "sms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/[PluginManager]RegisterService( 1329): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1329): handle notify Blinkfeed plugin client changed
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
D/PMS     (  910): releaseWL(42cda980): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
I/ActivityManager(  910): Resuming delayed broadcast
,I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/PackageManager(  910):   Scheme: "smsto"
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mmsto"
,I/IcingCorporaProvider( 2808): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
E/ExternalAccountType( 1342): Unsupported attribute readOnly
,D/PhoneApp( 1238): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/ActivityManager(  910): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  910): acquireWL(42d3a140): PARTIAL_WAKE_LOCK  Icing 0x1 2157 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42be77d8): PARTIAL_WAKE_LOCK  AsyncService 0x1 3531 10160 null
,D/PMS     (  910): releaseWL(42be77d8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  910): releaseWL(42d3a140): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  910): acquireWL(42e3b2a8): PARTIAL_WAKE_LOCK  Icing 0x1 2157 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42e3b2a8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Resuming delayed broadcast
,D/PMS     (  910): acquireWL(42f73658): PARTIAL_WAKE_LOCK  Icing 0x1 2157 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,D/PMS     (  910): releaseWL(42f73658): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
,D/PMS     (  910): acquireWL(42e6d510): PARTIAL_WAKE_LOCK  Icing 0x1 2157 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42e6d510): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Resuming delayed broadcast
,D/PMS     (  910): acquireWL(42e40e38): PARTIAL_WAKE_LOCK  Icing 0x1 2157 10029 WorkSource{10029 com.google.android.gms}
D/PackageBroadcastService( 2157): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
W/PackageManager(  910): Unable to load service info ResolveInfo{42dd0d48 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  910): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  910): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  910): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  910): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  910): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  910): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  910): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  910): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  910): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  910): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  910): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  910): 	at dalvik.system.NativeStart.main(Native Method)
,I/PackageBroadcastService( 2157): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  910): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/Icing   ( 2157): updateResources: need to parse f{com.google.android.gms}
,D/RemoteDisplayProvider(  910): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,I/IcingCorporaProvider( 2808): UpdateCorporaTask done [took 489 ms] updated apps [took 489 ms] 
D/RemoteDisplayProvider(  910): start
I/ActivityManager(  910): Resuming delayed broadcast
,I/GCoreNlp( 1223): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  910): applying state to connected service
D/PMS     (  910): acquireWL(43e676e8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(43e676e8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  910): applying state to connected service
D/PMS     (  910): acquireWL(443d88f0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(443d88f0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42fc2948): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42fc2948): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  910): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{42cdd398 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1272): loadItems() com.htc.launcher.pageview.WidgetManager@42476d50 +
,I/Prism.WidgetManager( 1272): onLoadItems() +
,I/Icing   ( 2157): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,E/Prism.WidgetManager( 1272): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1272): onLoadItems() -
,I/Prism.ItemManager( 1272): loadItems() com.htc.launcher.pageview.WidgetManager@42476d50 -
,I/Icing   ( 2157): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  910): releaseWL(42e40e38): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PhoneApp( 1238): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1238): -- N1 =0
,D/PhoneApp( 1238): -- N2 =0
,D/PhoneApp( 1238): -- N3 =0
,D/AutoSetting( 1519): service - handleMessage() stop self
,D/AutoSetting( 1519): service - onDestroy() END
,D/AutoSetting( 1519): service - handleMessage() quit looper
,D/PMS     (  910): acquireWL(4427c7e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4427c7e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/AutoSetting( 1329): service - mHandler: update timezone
,D/AutoSetting( 1329): service - handleMessage() stop self
,D/AutoSetting( 1329): service - handleMessage() quit looper
,D/AutoSetting( 1329): service - onDestroy() END
,D/AutoSetting( 1519): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1519): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1519): service - onCreate()
W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1519): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1519): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/DotMatrix( 1589): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1589): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1519): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1519): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1519): service - mHandler: update timezone
V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1519): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1519): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1519): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1519): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1589): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1589): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1117): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{427bd8a0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.htclocationservice 1 8 2 11
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{44305938 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  910): acquireWL(44a13b20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
V/AlarmManager(  910): sending alarm PendingIntent{42b980a8: PendingIntentRecord{42807810 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=757161, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(44a13b20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/AutoSetting( 1519): service - handleMessage() stop self
,D/AutoSetting( 1519): service - onDestroy() END
,D/AutoSetting( 1519): service - handleMessage() quit looper
,D/PMS     (  910): acquireWL(444d76a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{4262a2c8: PendingIntentRecord{42d74780 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=783340, Int=0
D/ConnectivityService(  910): Sampling interval elapsed, updating statistics ..
,D/PMS     (  910): releaseWL(444d76a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  910): Done.
,D/ConnectivityService(  910): Setting timer for 720seconds
,D/PMS     (  910): acquireWL(42f4dd78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42f4dd78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(441ac990): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
V/AlarmManager(  910): sending alarm PendingIntent{42b980a8: PendingIntentRecord{42807810 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=817161, Int=0
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(441ac990): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42f31a08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42f31a08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(4422afc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42b980a8: PendingIntentRecord{42807810 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=877161, Int=0
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(4422afc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43933178): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43933178): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(444e2318): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42b980a8: PendingIntentRecord{42807810 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=937161, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(444e2318): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42ed9d90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42ed9d90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(43e9c080): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): releaseWL(43e9c080): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43dd3d80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
V/AlarmManager(  910): sending alarm PendingIntent{42b980a8: PendingIntentRecord{42807810 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=997161, Int=0
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43dd3d80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43262658): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42e40768: PendingIntentRecord{42f3f650 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450464473652, Int=900000
,V/AlarmManager(  910): sending alarm PendingIntent{42be0be0: PendingIntentRecord{42f8e640 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450464549689, Int=0
,W/ContextImpl( 4595): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4595): call getInstance()
,D/SmartSyncUtils( 4595): isEpsOn(), nState = 0
D/PMS     (  910): acquireWL(4442cd98): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4595 1000 null
,D/PowerUsageList:PowerUsageHelper( 4595): MY_DEBUG = false
D/PMS     (  910): releaseWL(43262658): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 4595): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4595): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4595): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4595): SettingOnTime = 1450504800000, randomSettingOnTime = 1450502913000
,D/SmartSyncScreenOnOffTimeReceiver( 4595): SettingOffTime = 1450490400000, randomSettingOffTime = 1450494769000
,D/SmartSyncScreenOnOffTimeReceiver( 4595): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4595): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4595): bNightModeTurnOffOnce = false
D/PMS     (  910): releaseWL(4442cd98): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
W/BatSI   (  910): Couldn't get kernel wake lock stats
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1187): nl80211: Disconnect event
I/wpa_supplicant( 1187): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
I/wpa_supplicant( 1187): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  910): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getReasonFromEventString() 0
D/HTCRequest(  910): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  910): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  910): Enter handleNetworkDisconnect
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
I/wpa_supplicant( 1187): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 1187): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1187): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1187): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1187): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1187): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8e74bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1187):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1187): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1187): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1187): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1187): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1187): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1187): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_,supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1187): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1187): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): Power_Mode_Type mode = 0
I/wpa_supplicant( 1187): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/wpa_supplicant( 1187): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1187): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1187): nl80211: if_removed already cleared - ignore event
D/WifiNative-wlan0(  910):    returned true
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
,D/wpa_supplicant( 1187): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1187): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1187): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 1187): Wireless event: cmd=0x8b15 len=20
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/WifiP2pService(  910): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  910): P2pEnabledState{ when=-6ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
,D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/DhcpStateMachine(  910): [RunningState] Stop DHCP
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
,D/Tethering(  910): interfaceStatusChanged wlan0, false
,D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
E/NativeDaemonConnector.ResponseQueue(  910): more buffered than allowed: 10 >= 10
,E/NativeDaemonConnector.ResponseQueue(  910): Removing request: null (39)
,D/libc    (  910): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  910): Exit handleNetworkDisconnect
D/WifiPerfLock(  910): release()
D/WifiStateMachine(  910): PerfLock released for exiting ConnectedState
,D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): Power_Mode_Type mode = 0,
I/wpa_supplicant( 1187): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 61
D/WifiDataStallTracker(  910): stopDataStallAlarm: current tag=20077 mDataStallAlarmIntent=null
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12,
,D/WifiNative-wlan0(  910):    returned true
D/ConnectivityService(  910): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  910): acquireWL(4492c220): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 910 1000 null
D/WifiP2pService(  910): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  910): Provision feature enable=false
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/UsbnetStateTracker(  910): isAvailable+-
D/UsbnetStateTracker(  910): reconnect
,D/UsbnetStateTracker(  910): isAvailable+-
D/ConnectivityService(  910): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  910): default: reconnect()
D/MDST    (  910): default: setTeardownRequested(false)
D/MDST    (  910): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  910): handleConnectivityChange: netType=1 doReset=true resetMask=3
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  910): doBoolean: SET pno 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1187): CTRL_IFACE SET 'pno'='1'
,D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WISPrService( 3752): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
E/NativeDaemonConnector.ResponseQueue(  910): more buffered than allowed: 10 >= 10
E/NativeDaemonConnector.ResponseQueue(  910): Removing request: null (50)
D/ConnectivityService(  910): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  910): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '116 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 116 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  910): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
,D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WISPrService( 3752): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1187): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '117 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 117 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WISPrService( 3752): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
,D/WISPrService( 3752): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,V/NativeCrypto( 1359): Read error: ssl=0x668fee30: I/O error during system call, Connection timed out
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '118 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 118 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): handleConnectivityChange: resetting
D/ConnectivityService(  910): resetConnections(wlan0, 3)
D/PMS     (  910): acquireWL(441ad7f0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,V/NativeCrypto( 1359): SSL shutdown failed: ssl=0x668fee30: I/O error during system call, Broken pipe
D/libc    (  363): [NET] entry_id:2   entry:0xb87444e0  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb8744428  removed 
D/libc    (  363): [NET] entry_id:3   entry:0xb87440e8  removed 
,D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
,D/ConnectivityService(  910): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  910): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  910): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false,
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  910): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
D/ConnectivityService(  910): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
D/ConnectivityService(  910): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:0
I//system/bin/ip(  363): RTNETLINK answers: No such process
I/logwrapper(  363): /system/bin/ip terminated by exit(2)
D/WirelessDisplayService(  910): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  910): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/PMS     (  910): acquireWL(43d1aa58): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4492/10079)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/ConnectivityService(  910): reportInetCondition for net -1, percentage: 0 by  (1359/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/WifiStateMachine(  910): startScan Pid: 910 Uid 1000
I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiNative-wlan0(  910): doBoolean: SET pno 0
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1187): nl80211: Sched scan stop sent (ret=0)
I/wpa_supplicant( 1187): wpa_supplicant_scan enter
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: SCAN
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): releaseWL(441ad7f0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/BatSI   (  910): WIFI scan started for: 450a0300 uid:1000
I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1187): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1187): Failed to initiate AP scan
I/wpa_supplicant( 1187): Failed to initiate AP scan, Failed_to_scan_counter:1
D/WifiNative-wlan0(  910):    returned true
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:0
,D/ConnectivityService(  910): mActiveDefaultNetwork: -1
D/ConnectivityService(  910): handleInetConditionChange: no active default network - ignore
,D/PMS     (  910): releaseWL(43d1aa58): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,V/Tethering(  910): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  910): [AlarmQueuing] connectivity wifi: false
,D/Tethering(  910): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  910): bSetPropertyMultiRAB:false
D/Tethering(  910): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  910): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  910): ipv4Default null
I/Tethering(  910): No IPv4 upstream interface, giving up.
D/GpsLocationProvider(  910): [handleMessage] UPDATE_NETWORK_STATE
D/Tethering(  910): TetherMasterSM: InitialState processMessage what=3
D/GpsLocationProvider(  910): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  910): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  910): ignore wifi update if we are not in OPENING or CLOSING
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
D/CaptivePortalTracker(  910): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/PMS     (  910): acquireWL(42835e20): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/PMS     (  910): releaseWL(42835e20): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.google.android.music (4424/10154)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1601/10029)
I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1187): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1187): Failed to initiate AP scan
,I/wpa_supplicant( 1187): Failed to initiate AP scan, Failed_to_scan_counter:2
I/NetworkMonitor( 4424): type=WIFI subType= reason=null isConnected=false
D/CaptivePortalTracker(  910): NoActiveNetworkState
,I/ConnectivityHelper( 1272): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.launcher (1272/10076)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4492/10079)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (2712/10021)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/AutoSetting( 1329): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4492): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4492): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1329): Util - no network available!
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1329/10055)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1329/10055)
,D/AutoSetting( 1329): service - onCreate()
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4531/10151)
,D/AutoSetting( 1329): service - AddressCache: using context: com.htc.Weather
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (3531/10160)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (3531/10160)
,D/AutoSetting( 1329): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/LocationManagerService(  910): request 42dc2be8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/LocationManagerService(  910): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1329): service - mHandler: cancel location update
,D/AutoSetting( 1329): service -           changes count: 0
,I/iu.Environment( 2157): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
I/iu.UploadsManager( 2157): num queued entries: 0
I/iu.UploadsManager( 2157): num updated entries: 0
,I/iu.SyncManager( 2157): NEXT; no task
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1187): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1187): Failed to initiate AP scan
,I/wpa_supplicant( 1187): Failed to initiate AP scan, Failed_to_scan_counter:3,
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-62
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=36 entropy=0
D/wpa_supplicant( 1187): Add randomness: count=37 entropy=1
D/wpa_supplicant( 1187): Add randomness: count=38 entropy=2
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): blist: c0:ff:d4:d3:aa:48 count[1]
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1187):    skip - blacklisted (count=1 limit=0)
D/wpa_supplicant( 1187): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): No APs found - clear blacklist and try again
E/wpa_supplicant( 1187): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1187): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-62
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 3
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): selected network = 1
D/wpa_supplicant( 1187): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8e764e8  current_ssid=0x0
D/wpa_sup,plicant( 1187): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1187): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1187): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1187): check if in concurrent case
I/wpa_supplicant( 1187): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiNative-wlan0(  910): doBoolean: SET pno 1
D/WifiMonitor(  910): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
D/wpa_supplicant( 1187): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1187): wpa_supplicant_associate, 1780
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1187): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1187): RSN: PMKSA cache search - network_ctx=0xb8e764e8 try_opportunistic=0
D/wpa_supplicant( 1187): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1187): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1187): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1187): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1187): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1187): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1187): nl80211: Unsubscribe mgmt frames handle 0xb8e75718 (mode change)
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1187): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8e75718
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1187):   * bssid=c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 1187):   * freq=2412
D/wpa_supplicant( 1187):   * Auth Type 0
D/wpa_supplicant( 1187):   * WPA Versions 0x2
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1187): nl80211: Connect request send successfully
D/wpa_supplicant( 1187): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - EAP fail=0
,D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): CTRL_IFACE SET 'pno'='1'
,E/wpa_supplicant( 1187): send_and_recv error -16 - cmd 75
D/wpa_supplicant( 1187): nl80211: Sched scan start failed: ret=-16 (Device or resource busy)
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1" Return -1
D/WifiNative-wlan0(  910):    returned false
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  910): doString: LIST_DONGLES
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  910): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (378) for get BSS: id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-62
I/wpa_supplicant( 1187): tsf=0000001028322241
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=16
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-51
I/wpa_supplicant( 1187): tsf=0000001028322216
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=17
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2427
I/wpa_supplicant( 1187): level=-79
I/wpa_supplicant( 1187): tsf=0000001028322251
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ####
,D/WifiStateMachine(  910): == begin of scan result ==
D/WifiStateMachine(  910): == (3) end of scan result ==
W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  910): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -62, frequency: 2412, timestamp: 1028322241, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 5220, timestamp: 1028322216, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 1028322251, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): add 3 to mScanResults
D/BatSI   (  910): WIFI scan stopped for: 440a0300 uid:1000
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/WifiNotificationController(  910): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WirelessDisplayService(  910): getDiscoveryDongleList
D/WifiManager( 1223): getScanResults enter 
D/WifiStateMachine(  910): == begin of scan result ==
D/WifiStateMachine(  910): == (3) end of scan result ==
,D/WirelessDisplayService(  910): getDiscoveryDongleList
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/wpa_supplicant( 1187): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
,D/wpa_supplicant( 1187): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1187): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1187): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1187): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
,D/wpa_supplicant( 1187): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1187): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1187): nl80211: Connect event
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1187): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1187): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1187): Add randomness: count=39 entropy=3
I/wpa_supplicant( 1187): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1187): TDLS: Remove peers on association
D/wpa_supplicant( 1187): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - portValid=0
,D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - portEnabled=1
,D/wpa_supplicant( 1187): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1187): EAPOL: enable timer tick
D/wpa_supplicant( 1187): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1187): htc_wext_set_keepalive +
I/wpa_supplicant( 1187): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1187): getPrivFuncNum +	
I/wpa_supplicant( 1187): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1187): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1187): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1187): State: ASSOCIATED -> 4WAY_HANDSHAKE
,D/wpa_supplicant( 1187): Get randomness: len=32 entropy=4
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  910): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  910): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
,D/HTCRequest(  910): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  910): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  910): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  910): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  910): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  910): Enter handleAssociatedWithEvent
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  910): Associated
,D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  910): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  910): Exit handleAssociatedWithEvent
D/WifiStateMachine(  910): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/WifiStateMachine(  910): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  910): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  910): This record is existed, only update it...
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/Tethering(  910): interfaceLinkStateChanged wlan0, true
D/Tethering(  910): interfaceStatusChanged wlan0, true
,D/Tethering(  910): [isWifi] getHotspotEnabled: false,
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
,D/WifiApDatabaseHandler(  910): updateConnectedAP...,
,I/wpa_supplicant( 1187): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE,
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb8e759f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1187):    addr=c0:ff:d4:d3:aa:48
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 11
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1187): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1187): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f13b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 1187):    broadcast key
,D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1187): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 1187): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 1187): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1187): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1187): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
E/wpa_supplicant( 1187): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1187): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1187): set send_ind_to_ndc = 0
I/wpa_supplicant( 1187): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1187): htc_wext_set_TX_TRACKING - ret = 0
,D/wpa_supplicant( 1187): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1187): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1187): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1187): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1187): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1187): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Authorized
,D/wpa_supplicant( 1187): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1187): EAPOL authentication completed successfully
I/wpa_supplicant( 1187): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 79
,D/wpa_supplicant( 1187): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1187): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1187): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  910): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  910): interfaceLinkStateChanged wlan0, true
,D/Tethering(  910): interfaceStatusChanged wlan0, true
D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  910): fetchFrequency(), freq = 2412
D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  910): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/ConnectivityService(  910): Provision feature enable=false
,D/ConnectivityService(  910): mActiveDefaultNetwork: -1
D/WifiApDatabaseHandler(  910): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateMachine(  910): This record is existed, only update it...
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/WISPrService( 3752): >>>>>WISPrService start isConnected = false<<<<<
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WISPrService( 3752): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/WifiNative-wlan0(  910): doBoolean: SET pno 0
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): CTRL_IFACE SET 'pno'='0'
D/WifiNative-wlan0(  910):    returned true
D/DhcpStateMachine(  910): [StoppedState] Start DHCP
,D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 1
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): Power_Mode_Type mode = 1
I/wpa_supplicant( 1187): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 61
D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1187): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
,D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  910):    returned null
E/WifiStateMachine(  910): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  910):    returned null
D/WifiStateMachine(  910): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  910): acquireWL(44a05968): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 910 1000 null
D/WifiStateMachine(  910): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  910): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42ec7a68 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42ec7a68 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:0
,D/wpa_supplicant( 1187): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1187): EAPOL: disable timer tick
,D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  910): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1187): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  910):    returned true
,D/WifiStateMachine(  910): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  910): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  910): releaseWL(44a05968): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/WifiP2pService(  910): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=16 [6][1][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -61 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1187): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
,D/WifiStateMachine(  910): gateway: /192.168.1.1
,D/WifiNative-wlan0(  910): doBoolean: DRIVER GATEWAY-ADD 16885952
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1187): htc_wext_set_keepalive +
I/wpa_supplicant( 1187): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1187): getPrivFuncNum +	
I/wpa_supplicant( 1187): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1187): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1187): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1187): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1187): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  910): VerifyingLinkState enter
D/WifiStateMachine(  910): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  910): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  910): VerifyingLinkState: enableIpv6
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED -1 -> 3
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -61, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiWatchdogStateMachine(  910): WAN detection
E/NativeDaemonConnector.ResponseQueue(  910): more buffered than allowed: 10 >= 10
E/NativeDaemonConnector.ResponseQueue(  910): Removing request: null (52)
V/NetworkPolicy(  910): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
,D/WISPrService( 3752): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): Provision feature enable=false
D/ConnectivityService(  910): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  910): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  910): default: teardown()
D/MDST    (  910): default: setTeardownRequested(true)
D/MDST    (  910): default: setEnableApn apnType =default , enable=false
D/MDST    (  910): default: setTeardownRequested(true)
D/ConnectivityService(  910): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [1][0][0]
I/wpa_supplicant( 1187): Change stage from stage0 to stage3
,D/WifiStateMachine(  910): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
D/WifiStateMachine(  910): syncGetConfiguredNetworks
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED connected
E/ConnectivityService(  910): Unexpected mtu value: android.net.wifi.WifiStateTracker@42d69fc8
D/ConnectivityService(  910): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  910): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  910): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
E/NativeDaemonConnector.ResponseQueue(  910): more buffered than allowed: 10 >= 10
E/NativeDaemonConnector.ResponseQueue(  910): Removing request: null (60)
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  910): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  910): handleConnectivityChange: resetting
D/Nat464Xlat(  910): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  910): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  910): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  910): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  910): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/WirelessDisplayService(  910): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  910):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
,I/QuickSettingWifi( 1117): receive.wifiConnect:true wifiAPname:NG700 elapse:1
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/PMS     (  910): acquireWL(43d9f120): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4492/10079)
D/PMS     (  910): acquireWL(44989568): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2157 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43ed3fa0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2157 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2157): Checkin interval check for package: unspecified last checkin: 1450464250302 min interval config: 0 actual interval: 323532
,I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
,I/logwrapper(  363): /system/bin/ip terminated by exit(254)
D/PMS     (  910): releaseWL(44989568): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2157): Checking schedule, now: 1450464573842 next: 1450464280266
,I/CheckinService( 2157): active receiver: enabled
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2157, uid=10029, userID:0
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,I/CheckinService( 2157): Preparing to send checkin request
,I/EventLogService( 2157): Accumulating logs since 1450464248308
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
,D/ConnectivityService(  910): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): releaseWL(43d9f120): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/CheckinRequestBuilder( 2157): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  910): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2157): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  910): getNetworkInfo networkType=9 called by com.google.android.gms (2157/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  371): PrepareKeyRequest: nonce=753896871
,I/WVCdm   (  371): CdmEngine::CloseSession
,I/Adreno-EGL( 4583): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4583): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4583): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4583): Local Branch: 
I/Adreno-EGL( 4583): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4583): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4583):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4583): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4583): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4583): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4583): Local Branch: 
I/Adreno-EGL( 4583): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4583): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4583):                  aa63bbd948f41d15fc72f585e
,D/PMS     (  910): acquireWL(43a649b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  910): updateBatteryInfo
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PMS     (  910): releaseWL(43a649b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,I/Adreno-EGL( 4583): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4583): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4583): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4583): Local Branch: 
I/Adreno-EGL( 4583): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4583): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4583):                  aa63bbd948f41d15fc72f585e
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Settings( 4583): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (4583/10029)
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/PMS     (  910): releaseWL(4492c220): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  910): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/AlarmManager(  910): [AlarmQueuing] connectivity wifi: true
,V/Tethering(  910): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  910): NoActiveNetworkState
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1601/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,I/ConnectivityHelper( 1272): [onReceive] WIFI(1): CONNECTED
,V/Tethering(  910): bSetPropertyMultiRAB:false
D/Tethering(  910): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
I/Tethering(  910): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/Tethering(  910): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
,I/Tethering(  910): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  910): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/Tethering(  910): Found interface wlan0
D/Tethering(  910): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.launcher (1272/10076)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.google.android.music (4424/10154)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4492/10079)
D/PMS     (  910): acquireWL(44041c58): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
I/NetworkMonitor( 4424): type=WIFI subType= reason=null isConnected=true
D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(43b1d6d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WVCdm   (  371): PrepareKeyRequest: nonce=4249597111
D/GpsLocationProvider(  910): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  910): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  910): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  910): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
D/PMS     (  910): releaseWL(43b1d6d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  910): releaseWL(44041c58): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (2712/10021)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/AutoSetting( 1329): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1329/10055)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/MobileConnectivityChangeReceiver( 4492): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/MobileConnectivityChangeReceiver( 4492): onReceive CONNECTIVITY_CHANGE networkType=1
D/AutoSetting( 1329): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1329): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 1329): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1329): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1329/10055)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4531/10151)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/WVCdm   (  371): CdmEngine::CloseSession
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (3531/10160)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (3531/10160)
,D/PMS     (  910): acquireWL(433e7058): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2157 10029 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,I/CheckinService( 2157): Checkin interval check for package: unspecified last checkin: 1450464250302 min interval config: 0 actual interval: 324631
D/PMS     (  910): releaseWL(433e7058): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2157, uid=10029, userID:0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/CheckinRequestBuilder( 2157): Classify the device as Phone.
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/iu.Environment( 2157): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,I/iu.UploadsManager( 2157): num queued entries: 0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
,I/iu.UploadsManager( 2157): num updated entries: 0
,I/iu.SyncManager( 2157): NEXT; no task
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/libc    ( 1359): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1359): [NET] getaddrinfo-,err=8
D/libc    ( 1359): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1359): [NET] getaddrinfo-, 1
,D/libc    ( 1359): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =20e5 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/PMS     (  910): acquireWL(44453908): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/libc    ( 2157): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2157): [NET] getaddrinfo-,err=8
V/NativeCrypto( 2157): SSL shutdown failed: ssl=0x66c9f9e8: I/O error during system call, Connection timed out
D/libc    ( 2157): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2157): [NET] getaddrinfo-, 1
V/NativeCrypto( 2157): SSL shutdown failed: ssl=0x6e145978: I/O error during system call, Connection timed out
D/libc    ( 2157): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =3ffa +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=79
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
,D/libc    ( 1359): [NET] getaddrinfo_proxy-, success
D/libc    (  363): [NET]res_nsend:resplen=84
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2157): [NET] getaddrinfo_proxy-, success,
,D/libc    ( 2157): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2157): [NET] getaddrinfo-,err=8
,D/libc    ( 1359): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1359): [NET] getaddrinfo-,err=8
,D/libc    ( 2157): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2157): [NET] getaddrinfo-,err=8
D/libc    ( 2157): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2157): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2157): Sending checkin request (12202 bytes)
D/libc    ( 1359): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1359): [NET] getaddrinfo-,err=8
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/PMS     (  910): acquireWL(43aeefe8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/PMS     (  910): releaseWL(44453908): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1359/10029)
,D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  910): handleInetConditionChange: starting a change hold
,D/PMS     (  910): releaseWL(43aeefe8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42f5ee28): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1359/10029)
,D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1359/10029)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
,D/PMS     (  910): releaseWL(42f5ee28): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinRequestBuilder( 2157): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  910): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2157): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  910): getNetworkInfo networkType=9 called by com.google.android.gms (2157/10029)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=33 [27][9][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
,D/ConnectivityService(  910): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,I/CheckinRequestBuilder( 2157): Classify the device as Phone.
,I/CheckinTask( 2157): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2157): Checking schedule, now: 1450464575945 next: 1450987512938
,I/CheckinService( 2157): active receiver: disabled
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2157, uid=10029, userID:0
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
,I/CheckinService( 2157): Checking schedule, now: 1450464575969 next: 1450987512938
,I/CheckinService( 2157): active receiver: disabled
,D/CheckinService( 2157): Recording last checkin time for package unspecified as 1450464575975
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2157, uid=10029, userID:0
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
,D/PMS     (  910): releaseWL(43ed3fa0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
,D/GCM     ( 1359): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-,err=8
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  910): [NET] getaddrinfo-, 1
,D/libc    (  910): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =611b +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=172
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  910): Find DNS Address www.htc.com/23.59.123.86
,D/WifiStateMachine(  910): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  910): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1342): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/PMS     (  910): acquireWL(43dc1d60): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4663 10111 null
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "sms"
W/SystemReader( 1256): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1272): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/ActivityManager(  910): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "smsto"
I/Launcher( 1272): Deferring update until onResume
,D/Launcher( 1272): waitUntilResume // bindAppsUpdated
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/[PluginManager]RegisterService( 1329): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1329): handle notify Blinkfeed plugin client changed
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mms"
,W/AccTypeManager( 1342): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/ActivityManager(  910): Resuming delayed broadcast
,D/AccTypeManager( 1342): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/PMS     (  910): releaseWL(43dc1d60): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/IcingCorporaProvider( 2808): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "sms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mms"
,E/ExternalAccountType( 1342): Unsupported attribute readOnly
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,D/PMS     (  910): acquireWL(439402d0): PARTIAL_WAKE_LOCK  AsyncService 0x1 3531 10160 null
,I/ActivityManager(  910): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  910): releaseWL(439402d0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,D/PhoneApp( 1238): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
D/PMS     (  910): acquireWL(43b52e20): PARTIAL_WAKE_LOCK  Icing 0x1 2157 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(43b52e20): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  910): acquireWL(43da55c8): PARTIAL_WAKE_LOCK  Icing 0x1 2157 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(43da55c8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,D/PMS     (  910): acquireWL(42d254f0): PARTIAL_WAKE_LOCK  Icing 0x1 2157 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42d254f0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Resuming delayed broadcast
,D/PMS     (  910): acquireWL(43e46d90): PARTIAL_WAKE_LOCK  Icing 0x1 2157 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
,D/PMS     (  910): releaseWL(43e46d90): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Resuming delayed broadcast
,D/PMS     (  910): acquireWL(43cfcbd8): PARTIAL_WAKE_LOCK  Icing 0x1 2157 10029 WorkSource{10029 com.google.android.gms}
,D/PackageBroadcastService( 2157): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2157): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  910): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/PMS     (  910): releaseWL(43cfcbd8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43d4dd70): PARTIAL_WAKE_LOCK  Icing 0x1 2157 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 2157): updateResources: need to parse f{com.google.android.gms}
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  910): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{42de9678 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/ActivityManager(  910): Resuming delayed broadcast
,I/IcingCorporaProvider( 2808): UpdateCorporaTask done [took 805 ms] updated apps [took 805 ms] 
,I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1272): loadItems() com.htc.launcher.pageview.WidgetManager@42476d50 +
,I/Prism.WidgetManager( 1272): onLoadItems() +
,W/PackageManager(  910): Unable to load service info ResolveInfo{4455ddf8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  910): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  910): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  910): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  910): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  910): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  910): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  910): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  910): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  910): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  910): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  910): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  910): 	at dalvik.system.NativeStart.main(Native Method)
,I/Icing   ( 2157): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2157): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  910): releaseWL(43d4dd70): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PhoneApp( 1238): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1238): -- N1 =0
,D/PhoneApp( 1238): -- N2 =0
,D/PhoneApp( 1238): -- N3 =0
,E/Prism.WidgetManager( 1272): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1272): onLoadItems() -
,I/Prism.ItemManager( 1272): loadItems() com.htc.launcher.pageview.WidgetManager@42476d50 -
,D/RemoteDisplayProvider(  910): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  910): start
,I/GCoreNlp( 1223): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/PMS     (  910): acquireWL(44b08830): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(44b08830): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(44a1d7e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(44a1d7e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  910): applying state to connected service
,D/LocationProviderProxy(  910): applying state to connected service
D/PMS     (  910): acquireWL(4498c888): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(4498a188): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(4498c888): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(4498a188): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(44935d78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
V/AlarmManager(  910): sending alarm PendingIntent{42b980a8: PendingIntentRecord{42807810 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1057160, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(44935d78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/AutoSetting( 1329): service - mHandler: update timezone
,D/AutoSetting( 1329): service - handleMessage() stop self
,D/AutoSetting( 1329): service - handleMessage() quit looper
,D/AutoSetting( 1329): service - onDestroy() END
,D/AutoSetting( 1519): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1519): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1519): service - onCreate()
W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1519): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1519): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/DotMatrix( 1589): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1589): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AutoSetting( 1519): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1519): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1519): service - mHandler: update timezone
,D/AutoSetting( 1519): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1519): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1519): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1519): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1589): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1589): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1117): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{42536a38 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.htclocationservice 3 15 4 11
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{44acbaf0 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  910): acquireWL(444f87d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(444f87d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
,D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 1519): service - handleMessage() stop self
,D/AutoSetting( 1519): service - onDestroy() END
,D/AutoSetting( 1519): service - handleMessage() quit looper
,D/PMS     (  910): acquireWL(44343fd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
V/AlarmManager(  910): sending alarm PendingIntent{42b980a8: PendingIntentRecord{42807810 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1117161, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(44343fd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(4433deb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4433deb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(442f79a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42b980a8: PendingIntentRecord{42807810 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1177161, Int=0
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(442f79a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(442cfa30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/PMS     (  910): releaseWL(442cfa30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  910): acquireWL(442b3200): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(442b3200): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(44299bc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42b980a8: PendingIntentRecord{42807810 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1237161, Int=0
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(44299bc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(44297dd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
D/PMS     (  910): releaseWL(44297dd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  910): updateBatteryInfo
,D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  910): onReceive BATTERY_CHANGED
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,W/ContextImpl( 4595): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,D/TetherSettings( 3752): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3752): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3752): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3752): Cust_ConnectToPC   : spcsc>false
D/        ( 3752): Cust_ConnectToPC   : IPT>true
,D/        ( 3752): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 3752): project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3752): Index of the first 1 = 3
W/Settings( 3752): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3752): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3752): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3752): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 3752): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 3752): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
D/SmartNS_Utility( 3752): [ACC]android_networking:tethering_guard_support=false
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(4427a168): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42b980a8: PendingIntentRecord{42807810 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1297161, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(4427a168): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(44279e70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): releaseWL(44279e70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,D/PowerUI ( 1117): closing low battery warning: level=100
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(44270e58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(44270e58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1117): closing low battery warning: level=100
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
,I/HtcPowerSaver(  910): >> updateStatus
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(441ad7f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42b980a8: PendingIntentRecord{42807810 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1357161, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(441ad7f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(441a46e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(441a46e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/HtcPowerSaver(  910): << updateStatus
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(44044498): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(44044498): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43edb208): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42b980a8: PendingIntentRecord{42807810 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1417161, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(43edb208): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43ecb560): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): releaseWL(43ecb560): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(43e59c48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
D/PMS     (  910): releaseWL(43e59c48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(42d857d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42b980a8: PendingIntentRecord{42807810 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1477161, Int=0
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42d857d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42b61aa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42b61aa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
,D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(42ba9890): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
D/PMS     (  910): releaseWL(42ba9890): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(42d628c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42b980a8: PendingIntentRecord{42807810 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1537161, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42d628c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1187): nl80211: Disconnect event
I/wpa_supplicant( 1187): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
I/wpa_supplicant( 1187): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  910): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getReasonFromEventString() 0
D/HTCRequest(  910): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
I/wpa_supplicant( 1187): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/HTCRequest(  910): WifiMonitor:getFreqFromEventString() 2412
D/wpa_supplicant( 1187): TDLS: Remove peers on disassociation
D/WifiMonitor(  910): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1187): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/WifiStateMachine(  910): Enter handleNetworkDisconnect
E/wpa_supplicant( 1187): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1187): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1187): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8e74bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1187):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1187): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1187): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1187): htc_wext_set_TX_TRACKING (0)+
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1187): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1187): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1187): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00,:00:00:00
,D/Tethering(  910): [isWifi] getHotspotEnabled: false
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: SUPP_BE entering state INITIALIZE
,D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1187): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 61
D/wpa_supplicant( 1187): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1187): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1187): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1187): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1187): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1187): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1187): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1187): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1187): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1187): Wireless event: cmd=0x8b15 len=20
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  910):    returned true
D/Tethering(  910): interfaceStatusChanged wlan0, false
,D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
,D/Tethering(  910): interfaceStatusChanged wlan0, false
D/WifiP2pService(  910): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  910): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/DhcpStateMachine(  910): [RunningState] Stop DHCP
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
D/ConnectivityService(  910): Sampling interval elapsed, updating statistics ..
D/PMS     (  910): acquireWL(42beb708): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  910): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/WifiStateMachine(  910): Exit handleNetworkDisconnect
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/WifiPerfLock(  910): release()
,D/WifiStateMachine(  910): PerfLock released for exiting ConnectedState
,D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  910): stopDataStallAlarm: current tag=20078 mDataStallAlarmIntent=null
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): Power_Mode_Type mode = 0
I/wpa_supplicant( 1187): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
V/AlarmManager(  910): sending alarm PendingIntent{4262a2c8: PendingIntentRecord{42d74780 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1503376, Int=0
D/PMS     (  910): releaseWL(42beb708): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/ConnectivityService(  910): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  910): acquireWL(42fcb5e0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 910 1000 null
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WifiP2pService(  910): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  910): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  910):    returned true
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/ConnectivityService(  910): Done.
,D/ConnectivityService(  910): Setting timer for 720seconds
D/ConnectivityService(  910): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  910): Provision feature enable=false
,D/ConnectivityService(  910): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/UsbnetStateTracker(  910): isAvailable+-
D/UsbnetStateTracker(  910): reconnect
D/UsbnetStateTracker(  910): isAvailable+-
,D/WISPrService( 3752): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3752): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  910): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  910): default: reconnect()
D/MDST    (  910): default: setTeardownRequested(false)
D/MDST    (  910): default: setEnableApn apnType =default , enable=true
E/NativeDaemonConnector.ResponseQueue(  910): more buffered than allowed: 10 >= 10
E/NativeDaemonConnector.ResponseQueue(  910): Removing request: null (71)
D/ConnectivityService(  910): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  910): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
,D/ConnectivityService(  910): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiNative-wlan0(  910): doBoolean: SET pno 1
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): CTRL_IFACE SET 'pno'='1'
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1187): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '137 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 137 Failed to remove route from default table (No such process)'
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  910): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  910): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 3752): >>>>>WISPrService start isConnected = false<<<<<
V/NativeCrypto( 1359): Read error: ssl=0x6423fd70: I/O error during system call, Connection timed out
,D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '138 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 138 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  910): Exception trying to remove a route: java.lang.IllegalStateException: command '139 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 139 Failed to remove route from default table (No such process)'
D/ConnectivityService(  910): handleConnectivityChange: resetting
,D/ConnectivityService(  910): resetConnections(wlan0, 3)
,D/WISPrService( 3752): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  363): [NET] entry_id:1   entry:0xb8748f68  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb8749018  removed 
D/libc    (  363): [NET] entry_id:3   entry:0xb8744458  removed 
V/NativeCrypto( 1359): SSL shutdown failed: ssl=0x6423fd70: I/O error during system call, Broken pipe
,D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
D/PMS     (  910): acquireWL(441683f8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  910): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  910): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:0
I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/ConnectivityService(  910): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  910): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/PMS     (  910): acquireWL(42ccafe8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
D/ConnectivityService(  910): reportInetCondition for net -1, percentage: 0 by  (1359/10029)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4492/10079)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/PMS     (  910): releaseWL(441683f8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
I//system/bin/ip(  363): RTNETLINK answers: No such process
D/WirelessDisplayService(  910): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,D/WirelessDisplayService(  910): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WifiStateMachine(  910): startScan Pid: 910 Uid 1000
,D/WifiNative-wlan0(  910): doBoolean: SET pno 0
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1187): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1187): nl80211: Sched scan stop sent (ret=0)
I/wpa_supplicant( 1187): wpa_supplicant_scan enter
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/WifiNative-wlan0(  910):    returned true
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/WifiNative-wlan0(  910): doBoolean: SCAN
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1187): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1187): Failed to initiate AP scan
,I/wpa_supplicant( 1187): Failed to initiate AP scan, Failed_to_scan_counter:1
,D/WifiNative-wlan0(  910):    returned true
D/BatSI   (  910): WIFI scan started for: 450a0300 uid:1000
,D/ConnectivityService(  910): mActiveDefaultNetwork: -1
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
D/ConnectivityService(  910): handleInetConditionChange: no active default network - ignore
,D/PMS     (  910): releaseWL(42ccafe8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  910): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  910): [AlarmQueuing] connectivity wifi: false
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1187): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1187): Failed to initiate AP scan
,I/wpa_supplicant( 1187): Failed to initiate AP scan, Failed_to_scan_counter:2
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
D/GpsLocationProvider(  910): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  910): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  910): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  910): ignore wifi update if we are not in OPENING or CLOSING
D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/CaptivePortalTracker(  910): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  910): NoActiveNetworkState
,I/ConnectivityHelper( 1272): [onReceive] WIFI(1): DISCONNECTED
D/Tethering(  910): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  910): bSetPropertyMultiRAB:false
D/Tethering(  910): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  910): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  910): ipv4Default null
I/Tethering(  910): No IPv4 upstream interface, giving up.
I/NetworkMonitor( 4424): type=WIFI subType= reason=null isConnected=false
,D/Tethering(  910): TetherMasterSM: InitialState processMessage what=3
D/PMS     (  910): acquireWL(42cdec28): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): releaseWL(42cdec28): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.launcher (1272/10076)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.google.android.music (4424/10154)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4492/10079)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1601/10029)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (2712/10021)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/AutoSetting( 1329): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4492): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4492): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1329): Util - no network available!
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1329/10055)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1329/10055)
,D/AutoSetting( 1329): service - onCreate()
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4531/10151)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (3531/10160)
,D/AutoSetting( 1329): service - AddressCache: using context: com.htc.Weather
,D/AutoSetting( 1329): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/LocationManagerService(  910): request 42dc2be8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (3531/10160)
D/LocationManagerService(  910): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1329): service - mHandler: cancel location update
,D/AutoSetting( 1329): service -           changes count: 0
,I/iu.Environment( 2157): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2157): num queued entries: 0
,I/iu.UploadsManager( 2157): num updated entries: 0
,I/iu.SyncManager( 2157): NEXT; no task
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/PMS     (  910): acquireWL(42eee568): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42eee568): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1187): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1187): Failed to initiate AP scan
,I/wpa_supplicant( 1187): Failed to initiate AP scan, Failed_to_scan_counter:3
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1187): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=40 entropy=0
D/wpa_supplicant( 1187): Add randomness: count=41 entropy=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): blist: c0:ff:d4:d3:aa:48 count[1]
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): No APs found - clear blacklist and try again
E/wpa_supplicant( 1187): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1187): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-79
D/wpa_supplicant( 1187): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=42 entropy=2
D/wpa_supplicant( 1187): Add randomness: count=43 entropy=3
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1187): State: DISCONNECTED -> INACTIVE
,D/WifiNative-wlan0(  910): doBoolean: SET pno 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): CTRL_IFACE SET 'pno'='1'
,D/WifiMonitor(  910): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 75
,D/wpa_supplicant( 1187): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  910): doString: LIST_DONGLES
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =INACTIVE
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0,
D/WifiNative-wlan0(  910): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (378) for get BSS: id=1
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-62
I/wpa_supplicant( 1187): tsf=0000001028322241
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=18
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-51
I/wpa_supplicant( 1187): tsf=0000001558721710
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=19
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11,
I/wpa_supplicant( 1187): freq=2427
I/wpa_supplicant( 1187): level=-79
I/wpa_supplicant( 1187): tsf=0000001558721735
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ####
D/WifiP2pService(  910): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@4404c838 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@4404c838 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@4404c838 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  910): getDiscoveryDongleList
D/WifiManager( 1223): getScanResults enter 
D/WifiStateMachine(  910): == begin of scan result ==
D/WifiStateMachine(  910): == (3) end of scan result ==
D/WifiStateMachine(  910): == begin of scan result ==
D/WifiStateMachine(  910): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -62, frequency: 2412, timestamp: 1028322241, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 5220, timestamp: 1558721710, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/WifiStateMachine(  910): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2427, timestamp: 1558721735, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): add 3 to mScanResults
D/BatSI   (  910): WIFI scan stopped for: 440a0300 uid:1000
,D/WifiStateMachine(  910): == (3) end of scan result ==
,D/WirelessDisplayService(  910): getDiscoveryDongleList,
D/WifiNotificationController(  910): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/WifiStateMachine(  910): startScan Pid: 910 Uid 1000
,D/WifiNative-wlan0(  910): doBoolean: SET pno 0
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1187): nl80211: Sched scan stop sent (ret=0)
I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
,D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: SCAN
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1187): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1187): Failed to initiate AP scan
,I/wpa_supplicant( 1187): Failed to initiate AP scan, Failed_to_scan_counter:1
,D/BatSI   (  910): WIFI scan started for: 450a0300 uid:1000
D/WifiNative-wlan0(  910):    returned true
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1187): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1187): Failed to initiate AP scan
,I/wpa_supplicant( 1187): Failed to initiate AP scan, Failed_to_scan_counter:2
,I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1187): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1187): Failed to initiate AP scan
,I/wpa_supplicant( 1187): Failed to initiate AP scan, Failed_to_scan_counter:3
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-81
D/wpa_supplicant( 1187): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=44 entropy=4
D/wpa_supplicant( 1187): Add randomness: count=45 entropy=5
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1187): 1: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1187): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-81
D/wpa_supplicant( 1187): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=46 entropy=6
D/wpa_supplicant( 1187): Add randomness: count=47 entropy=7
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): clear disabled list - type=1
I/wpa_supplicant( 1187): No suitable network found
W/wpa_supplicant( 1187): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1187): State: INACTIVE -> INACTIVE
,D/WifiNative-wlan0(  910): doBoolean: SET pno 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1187): CTRL_IFACE SET 'pno'='1'
D/WifiP2pService(  910): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1187): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
,D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  910): doString: LIST_DONGLES
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  910): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (260) for get BSS: id=18
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-51
I/wpa_supplicant( 1187): tsf=0000001564701883
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=19
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2427
I/wpa_supplicant( 1187): level=-81
I/wpa_supplicant( 1187): tsf=0000001564701908
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ####
,D/WirelessDisplayService(  910): getDiscoveryDongleList
W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/WifiStateMachine(  910): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 5220, timestamp: 1564701883, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  910): == begin of scan result ==
,D/WifiManager( 1223): getScanResults enter 
D/WifiStateMachine(  910): == (2) end of scan result ==
,D/WifiStateMachine(  910): == begin of scan result ==
,D/WifiStateMachine(  910): == (2) end of scan result ==
,D/WirelessDisplayService(  910): getDiscoveryDongleList
D/WifiStateMachine(  910): 1: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2427, timestamp: 1564701908, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): add 2 to mScanResults
D/BatSI   (  910): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  910): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 77 (NL80211_CMD_SCHED_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-62
D/wpa_supplicant( 1187): BSS: last_scan_res_used=1/32 last_scan_full=1
D/wpa_supplicant( 1187): Add randomness: count=48 entropy=8
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1187): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1187): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1187): wpa_supplicant_pick_network+
I/wpa_supplicant( 1187): Selecting BSS from priority group 1
I/wpa_supplicant( 1187): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1187): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1187): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1187):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  910): doString: LIST_DONGLES
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1187):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-62
I/wpa_supplicant( 1187): Start print parameters
I/wpa_supplicant( 1187): wpa_s->wpa_state is 3
I/wpa_supplicant( 1187): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1187): isConcurrentMode() is 0
I/wpa_supplicant( 1187): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1187): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1187): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1187): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1187): wpa_s->reassociate is 0
I/wpa_supplicant( 1187): wpa_s->is_screen_on 0
I/wpa_supplicant( 1187): wpa_s->ifname wlan0
I/wpa_supplicant( 1187): End print parameters
I/wpa_supplicant( 1187): selected network = 20
D/wpa_supplicant( 1187): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8e764e8  current_ssid=0x0
D/wpa_supplicant( 1187): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1187): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1187): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1187): check if in concurrent case
,I/wpa_supplicant( 1187): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz),
D/wpa_supplicant( 1187): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1187): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1187): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1187): RSN: PMKSA cache search - network_ctx=0xb8e764e8 try_opportunistic=0
D/wpa_supplicant( 1187): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1187): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1187): State: SCANNING -> ASSOCIATING,
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1187): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1187): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1187): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1187): nl80211: Unsubscribe mgmt frames handle 0xb8e75718 (mode change)
D/wpa_supplicant( 1187): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8e75718
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Register frame type=0xd0 nl_handle=0xb8e75718
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1187): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1187):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1187):   * freq=2412
D/wpa_supplicant( 1187):   * Auth Type 0
D/wpa_supplicant( 1187):   * WPA Versions 0x2
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1187): nl80211: Connect request send successfully
D/wpa_supplicant( 1187): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - EAP fail=0
,D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  910): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1187): reply (379) for get BSS: id=18
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-51
I/wpa_supplicant( 1187): tsf=0000001564701883
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=19
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2427
I/wpa_supplicant( 1187): level=-81
I/wpa_supplicant( 1187): tsf=0000001564701908
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=20
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-62
I/wpa_supplicant( 1187): tsf=0000001566686867
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ####
,D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =INACTIVE newSupplicantState =ASSOCIATING
,D/WirelessDisplayService(  910): getDiscoveryDongleList
,D/WifiStateMachine(  910): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 5220, timestamp: 1564701883, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/WifiStateMachine(  910): 1: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2427, timestamp: 1564701908, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -62, frequency: 2412, timestamp: 1566686867, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  910): add 3 to mScanResults
D/WifiStateMachine(  910): == begin of scan result ==
D/WifiStateMachine(  910): == (3) end of scan result ==
D/WifiManager( 1223): getScanResults enter 
D/WifiStateMachine(  910): == begin of scan result ==
,D/WifiStateMachine(  910): == (3) end of scan result ==
,D/WirelessDisplayService(  910): getDiscoveryDongleList,
D/WifiNotificationController(  910): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/wpa_supplicant( 1187): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1187): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1187): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1187): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1187): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1187): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1187): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1187): nl80211: Connect event
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1187): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1187): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1187): Add randomness: count=49 entropy=9
I/wpa_supplicant( 1187): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1187): TDLS: Remove peers on association
D/wpa_supplicant( 1187): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Unauthorized
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1187): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1187): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1187): EAPOL: enable timer tick
D/wpa_supplicant( 1187): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1187): htc_wext_set_keepalive +
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1187): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1187): getPrivFuncNum +	
I/wpa_supplicant( 1187): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1187): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1187): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1187): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1187): Get randomness: len=32 entropy=10
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  910): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  910): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  910): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  910): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  910): handleAssociatedWi,thEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  910): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  910): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  910): Enter handleAssociatedWithEvent
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  910): Associated
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  910): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  910): Exit handleAssociatedWithEvent
D/WifiStateMachine(  910): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
D/WifiApDatabaseHandler(  910): updateConnectedAP...
D/WifiStateMachine(  910): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/Tethering(  910): [isWifi] getHotspotEnabled: false
D/Tethering(  910): interfaceLinkStateChanged wlan0, true
D/Tethering(  910): interfaceStatusChanged wlan0, true
,D/Tethering(  910): [isWifi] getHotspotEnabled: false
,I/wpa_supplicant( 1187): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb8e759f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1187):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1187): EAPOL: External notification - portValid=1
,I/wpa_supplicant( 1187): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f13b4a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1187):    broadcast key
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1187): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1187): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1187): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
,I/wpa_supplicant( 1187): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiApDatabaseHandler(  910): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  910): This record is existed, only update it...
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiMonitor(  910): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1187): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1187): netlink: Operstate: linkmode=-1, operstate=6
D/WifiApDatabaseHandler(  910): updateConnectedAP...
I/wpa_supplicant( 1187): set send_ind_to_ndc = 0
I/wpa_supplicant( 1187): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1187): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1187): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1187): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1187): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1187): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1187): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1187): EAPOL: SUPP_PAE entering state AUTHENTICATED
,D/wpa_supplicant( 1187): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1187): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1187): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1187): EAPOL authentication completed successfully
I/wpa_supplicant( 1187): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1187): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1187): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1187): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  910): interfaceLinkStateChanged wlan0, true
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/Tethering(  910): interfaceStatusChanged wlan0, true
D/Tethering(  910): [isWifi] getHotspotEnabled: false
,D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...,
,D/WifiStateMachine(  910): fetchFrequency(), freq = 2412,
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiStateMachine(  910): WifiApDatabaseHandler, WiFi AP database Inserting ..
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  910): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  910): Provision feature enable=false
D/ConnectivityService(  910): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiApDatabaseHandler(  910): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  910): This record is existed, only update it...
D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  910): updateConnectedAP...
,D/WISPrService( 3752): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3752): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  910): updateConnectedAP...
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:0
,D/WifiNative-wlan0(  910): doBoolean: SET pno 0
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): CTRL_IFACE SET 'pno'='0'
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1187): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1187): nl80211: Event message available
,D/wpa_supplicant( 1187): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/WifiNative-wlan0(  910):    returned true
,D/DhcpStateMachine(  910): [StoppedState] Start DHCP
,D/WifiStateMachine(  910): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 1
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiStateMachine(  910): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  910): acquireWL(4431d8c8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 910 1000 null
,D/WifiStateMachine(  910): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): Power_Mode_Type mode = 1
I/wpa_supplicant( 1187): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 61
D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1187): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  910):    returned null
E/WifiStateMachine(  910): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  910): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  910):    returned null
D/WifiP2pService(  910): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42ec7a68 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-3ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42ec7a68 target=com.android.internal.util.StateMachine$SmHandler }
,D/wpa_supplicant( 1187): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1187): EAPOL: disable timer tick
,D/WifiStateMachine(  910): startScan Pid: 910 Uid 1000
,D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  910): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  910): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  910):    returned true
,D/WifiNative-wlan0(  910): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1187): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): handlePostDhcpSetup release wake lock during DHCP
D/WifiP2pService(  910): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  910): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): releaseWL(4431d8c8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [4][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -62 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
D/WIFI_ICON( 1117): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): gateway: /192.168.1.1
D/WifiNative-wlan0(  910): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1187): htc_wext_set_keepalive +
I/wpa_supplicant( 1187): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1187): getPrivFuncNum +	
I/wpa_supplicant( 1187): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1187): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1187): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1187): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1187): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  910): VerifyingLinkState enter
D/WifiStateMachine(  910): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiNative-wlan0(  910): doBoolean: SCAN TYPE=ONLY
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): wpa_supplicant_scan enter
I/wpa_supplicant( 1187): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1187): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1187): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  910): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -62, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
D/BatSI   (  910): WIFI scan started for: 450a0300 uid:1000
E/NativeDaemonConnector.ResponseQueue(  910): more buffered than allowed: 10 >= 10
E/NativeDaemonConnector.ResponseQueue(  910): Removing request: null (73)
D/WifiDataStallTracker(  910): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  910): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiWatchdogStateMachine(  910): WAN detection
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  910): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
V/NetworkPolicy(  910): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/ConnectivityService(  910): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  910): Provision feature enable=false
D/ConnectivityService(  910): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  910): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  910): default: teardown()
D/MDST    (  910): default: setTeardownRequested(true)
D/MDST    (  910): default: setEnableApn apnType =default , enable=false
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/MDST    (  910): default: setTeardownRequested(true)
D/ConnectivityService(  910): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
,E/ConnectivityService(  910): Unexpected mtu value: android.net.wifi.WifiStateTracker@42d69fc8
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  910): handleConnectivityChange: netType=1 doReset=false resetMask=0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
D/WISPrService( 3752): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  910): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
,I/QuickSettingWifi( 1117): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,I/wpa_supplicant( 1187): Change stage from stage0 to stage3
D/WifiStateMachine(  910): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  910): syncGetConfiguredNetworks
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
E/NetdConnector(  910): NDC Command {147 interface route add wlan0 default 192.168.1.0 24 0.0.0.0} took too long (797ms)
D/ConnectivityService(  910): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  910): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  910): handleConnectivityChange: resetting
D/Nat464Xlat(  910): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  910): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  910): sendGeneralBroadcastDelayed, restrictEnable=false
D/PMS     (  910): acquireWL(42f46840): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
D/ConnectivityService(  910): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  910): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4492/10079)
D/WirelessDisplayService(  910): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  910):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/PMS     (  910): acquireWL(441813b0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2157 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(42f46840): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
I/logwrapper(  363): /system/bin/ip terminated by exit(254)
,I/CheckinService( 2157): Checkin interval check for package: unspecified last checkin: 1450464575975 min interval config: 0 actual interval: 537121
D/PMS     (  910): acquireWL(43829778): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2157 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(441813b0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2157): Checking schedule, now: 1450465113103 next: 1450464605938
,I/CheckinService( 2157): active receiver: enabled
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2157, uid=10029, userID:0
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/CheckinService( 2157): Preparing to send checkin request
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
I/EventLogService( 2157): Accumulating logs since 1450464573879
I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  910): mActiveDefaultNetwork: WIFI
,I/CheckinRequestBuilder( 2157): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  910): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2157): Failed to find provider info for com.google.android.wearable.settings
,D/PMS     (  910): releaseWL(42fcb5e0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  910): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  910): getNetworkInfo networkType=9 called by com.google.android.gms (2157/10029)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 1359): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,E/dalvikvm( 1359): Could not find class 'android.net.Network', referenced from method com.google.android.gms.http.l.a
,W/dalvikvm( 1359): VFY: unable to resolve check-cast 229 (Landroid/net/Network;) in Lcom/google/android/gms/http/l;
,W/dalvikvm( 1359): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/libc    ( 1359): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1359): [NET] getaddrinfo-,err=8
D/libc    ( 1359): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1359): [NET] getaddrinfo-, 1
,D/libc    ( 1359): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =776f +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/WifiStateMachine(  910): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  910): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  910): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  910): [AlarmQueuing] connectivity wifi: true
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by  (910/1000)
,D/CaptivePortalTracker(  910): NoActiveNetworkState
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
,I/NetworkMonitor( 4424): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.google.android.music (4424/10154)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.setupwizard (4492/10079)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.backuptransport (1601/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
D/PMS     (  910): acquireWL(442b4c88): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
I/ConnectivityHelper( 1272): [onReceive] WIFI(1): CONNECTED
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
V/Tethering(  910): bSetPropertyMultiRAB:false
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/Tethering(  910): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,I/Tethering(  910): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  910): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  910): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  910): ipv4Default 0.0.0.0/0 -> 192.168.1.1
,I/Tethering(  910): Found interface wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.htc.launcher (1272/10076)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/PMS     (  910): acquireWL(4428ac78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
,D/Tethering(  910): TetherMasterSM: InitialState processMessage what=3
D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  910): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/PMS     (  910): acquireWL(43e5e1a0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 910 1000 WorkSource{10160}
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (2712/10021)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.facebook.katana (4444/10027)
D/PMS     (  910): acquireWL(449d38d0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 910 1000 WorkSource{10029}
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
,D/GpsLocationProvider(  910): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  910): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  910): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  910): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  910): releaseWL(4428ac78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  910): releaseWL(442b4c88): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(44ac4438): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/PMS     (  910): releaseWL(44ac4438): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(43b69770): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/PMS     (  910): releaseWL(43b69770): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(441c6e38): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/AutoSetting( 1329): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4492): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4492): onReceive CONNECTIVITY_CHANGE networkType=1
D/PMS     (  910): releaseWL(441c6e38): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1329/10055)
D/AutoSetting( 1329): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1329): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 1329): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1329): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1329/10055)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.magazines (4531/10151)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (3531/10160)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.apps.plus (3531/10160)
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
,I/CheckinService( 2157): Checkin interval check for package: unspecified last checkin: 1450464575975 min interval config: 0 actual interval: 538228
D/PMS     (  910): acquireWL(44168a28): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2157 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(43b7b4c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/PMS     (  910): releaseWL(44168a28): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(43e5e1a0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 WorkSource{10160}
D/PMS     (  910): releaseWL(43b7b4c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2157, uid=10029, userID:0
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,I/iu.Environment( 2157): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
I/iu.UploadsManager( 2157): num queued entries: 0
,I/iu.UploadsManager( 2157): num updated entries: 0
,I/iu.SyncManager( 2157): NEXT; no task
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/PMS     (  910): acquireWL(43d80bd8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/libc    ( 1359): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1359): [NET] getaddrinfo-,err=8
D/libc    ( 1359): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1359): [NET] getaddrinfo-, 1
,D/libc    ( 1359): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =e950 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315361571412
,W/AlarmManager(  910): Alarm trigger time is over 1 year: setImplLocked(PendingIntent{42bd2de0: PendingIntentRecord{4300c348 com.google.android.gms startService}}) : type=2 triggerAtTime=315361571412 win=-1 tElapsed=315361571412 maxElapsed=551881571411 interval=0 standalone=false
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(441cb760): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/PMS     (  910): releaseWL(449d38d0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 WorkSource{10029}
,D/PMS     (  910): releaseWL(441cb760): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/wpa_supplicant( 1187): nl80211: Event message available
D/wpa_supplicant( 1187): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1187): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1187): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1187): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1187): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1187): nl80211: Survey data missing
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1187): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1187): Sorted scan results
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-51
I/wpa_supplicant( 1187): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-65
I/wpa_supplicant( 1187): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-81
D/wpa_supplicant( 1187): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1187): Add randomness: count=50 entropy=0
D/wpa_supplicant( 1187): Add randomness: count=51 entropy=1
,D/wpa_supplicant( 1187): Add randomness: count=52 entropy=2
,D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  910): doString: LIST_DONGLES
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/WirelessDisplayService(  910): getDiscoveryDongleList
,D/WifiNative-wlan0(  910): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1187): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1187): reply (379) for get BSS: id=18
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1187): freq=5220
I/wpa_supplicant( 1187): level=-51
I/wpa_supplicant( 1187): tsf=0000001571542142
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG7005g
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=19
I/wpa_supplicant( 1187): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1187): freq=2427
I/wpa_supplicant( 1187): level=-81
I/wpa_supplicant( 1187): tsf=0000001571542174
I/wpa_supplicant( 1187): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1187): ssid=Gonzos
I/wpa_supplicant( 1187): ====
I/wpa_supplicant( 1187): id=20
I/wpa_supplicant( 1187): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1187): freq=2412
I/wpa_supplicant( 1187): level=-65
I/wpa_supplicant( 1187): tsf=0000001571542164
I/wpa_supplicant( 1187): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1187): ssid=NG700
I/wpa_supplicant( 1187): ####
,D/WifiStateMachine(  910): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -65, 0
D/WifiStateMachine(  910): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -51, frequency: 5220, timestamp: 1571542142, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 1: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2427, timestamp: 1571542174, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -65, frequency: 2412, timestamp: 1571542164, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  910): add 3 to mScanResults
,V/ScoreHelper(  910): Only print Top 10 in ApScanList
,V/ScoreHelper(  910):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 13 [-65], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  910):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-51], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  910):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  910): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  910):  + computeScore(NG700): 1
,D/WifiStateMachine(  910): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  910): == begin of scan result ==
D/WifiManager( 1223): getScanResults enter 
,D/BatSI   (  910): WIFI scan stopped for: 440a0300 uid:1000
,D/WifiStateMachine(  910): == (3) end of scan result ==
D/WifiStateMachine(  910): == begin of scan result ==
,D/WirelessDisplayService(  910): getDiscoveryDongleList
,D/WifiStateMachine(  910): == (3) end of scan result ==
D/WifiNotificationController(  910): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=84
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1359): [NET] getaddrinfo_proxy-, success
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=79
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1359): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1359): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1359): [NET] getaddrinfo-,err=8
,D/libc    ( 1359): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1359): [NET] getaddrinfo-,err=8
,D/libc    ( 1359): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1359): [NET] getaddrinfo-,err=8
D/libc    ( 1359): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1359): [NET] getaddrinfo-,err=8
D/PMS     (  910): acquireWL(44264190): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
D/PMS     (  910): releaseWL(44264190): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,D/libc    ( 1359): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1359): [NET] getaddrinfo-,err=8
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/PMS     (  910): acquireWL(43b224e0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/PMS     (  910): releaseWL(43d80bd8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1359/10029)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  910): handleInetConditionChange: starting a change hold
,D/PMS     (  910): releaseWL(43b224e0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43470af0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1359/10029)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1359/10029)
,D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  910): handleInetConditionChange: currently in hold - not setting new end evt
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315361571412
,D/PMS     (  910): releaseWL(43470af0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  371): PrepareKeyRequest: nonce=3841576933
,I/Adreno-EGL( 4583): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4583): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4583): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4583): Local Branch: 
I/Adreno-EGL( 4583): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4583): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4583):                  aa63bbd948f41d15fc72f585e
,I/WVCdm   (  371): CdmEngine::CloseSession
,I/Adreno-EGL( 4583): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4583): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4583): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4583): Local Branch: 
I/Adreno-EGL( 4583): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4583): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4583):                  aa63bbd948f41d15fc72f585e
,D/libc    (  910): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-,err=8
D/libc    (  910): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  910): [NET] getaddrinfo-, 1
D/libc    (  910): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =e708 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=172
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  910): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  910): Find DNS Address www.htc.com/23.59.123.86
,D/ConnectivityService(  910): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=25 [27][7][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,I/Adreno-EGL( 4583): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4583): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4583): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4583): Local Branch: 
I/Adreno-EGL( 4583): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4583): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4583):                  aa63bbd948f41d15fc72f585e
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{44188118 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (4583/10029)
W/Settings( 4583): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  371): PrepareKeyRequest: nonce=1779039079
,I/WVCdm   (  371): CdmEngine::CloseSession
,I/CheckinRequestBuilder( 2157): Classify the device as Phone.
,D/libc    ( 2157): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2157): [NET] getaddrinfo-,err=8
,V/NativeCrypto( 2157): SSL shutdown failed: ssl=0x6e145978: I/O error during system call, Connection timed out
D/libc    ( 2157): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    ( 2157): [NET] getaddrinfo-, 1
,D/libc    ( 2157): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =6903 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2157): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2157): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2157): [NET] getaddrinfo-,err=8
,D/libc    ( 2157): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2157): [NET] getaddrinfo-,err=8
,D/libc    ( 2157): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2157): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2157): Sending checkin request (12208 bytes)
,I/CheckinRequestBuilder( 2157): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  910): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2157): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  910): getNetworkInfo networkType=9 called by com.google.android.gms (2157/10029)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=15 [19][3][0]
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
,I/CheckinRequestBuilder( 2157): Classify the device as Phone.
,I/CheckinTask( 2157): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 2157): Checking schedule, now: 1450465116796 next: 1450988053791
,I/CheckinService( 2157): active receiver: disabled
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2157, uid=10029, userID:0
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
,I/CheckinService( 2157): Checking schedule, now: 1450465116814 next: 1450988053791
,I/CheckinService( 2157): active receiver: disabled
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315361571412
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2157, uid=10029, userID:0
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023629
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023942
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024021
,D/CheckinService( 2157): Recording last checkin time for package unspecified as 1450465116821
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024026
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024029
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025334
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025348
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028012
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315361571412
,D/PMS     (  910): releaseWL(43829778): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2157/10029)
,D/GCM     ( 1359): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
,D/PMS     (  910): acquireWL(43e67a00): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4663 10111 null
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
W/SystemReader( 1256): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "sms"
,D/AccTypeManager( 1342): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1272): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mmsto"
,I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/Launcher( 1272): Deferring update until onResume
D/Launcher( 1272): waitUntilResume // bindAppsUpdated
,I/[PluginManager]RegisterService( 1329): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1329): handle notify Blinkfeed plugin client changed
W/AccTypeManager( 1342): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1342): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "sms"
D/PMS     (  910): releaseWL(43e67a00): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/IcingCorporaProvider( 2808): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,D/PMS     (  910): acquireWL(438f2798): PARTIAL_WAKE_LOCK  AsyncService 0x1 3531 10160 null
,D/PMS     (  910): releaseWL(438f2798): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,E/ExternalAccountType( 1342): Unsupported attribute readOnly
,D/PhoneApp( 1238): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,D/PMS     (  910): acquireWL(433c53d0): PARTIAL_WAKE_LOCK  Icing 0x1 2157 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(433c53d0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(43d4de08): PARTIAL_WAKE_LOCK  Icing 0x1 2157 10029 WorkSource{10029 com.google.android.gms}
,D/PackageBroadcastService( 2157): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2157): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 2157): updateResources: need to parse f{com.google.android.gms}
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  910): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  910): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/IcingCorporaProvider( 2808): UpdateCorporaTask done [took 1140 ms] updated apps [took 1140 ms] 
,I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1272): loadItems() com.htc.launcher.pageview.WidgetManager@42476d50 +
,I/Prism.WidgetManager( 1272): onLoadItems() +
,W/PackageManager(  910): Unable to load service info ResolveInfo{44286308 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  910): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  910): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  910): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  910): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  910): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  910): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  910): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  910): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  910): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  910): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  910): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  910): 	at dalvik.system.NativeStart.main(Native Method)
,I/Icing   ( 2157): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2157): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  910): releaseWL(43d4de08): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1272): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1272): onLoadItems() -
,I/Prism.ItemManager( 1272): loadItems() com.htc.launcher.pageview.WidgetManager@42476d50 -
,D/PhoneApp( 1238): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1238): -- N1 =0
,D/PhoneApp( 1238): -- N2 =0
,D/PhoneApp( 1238): -- N3 =0
,D/RemoteDisplayProvider(  910): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  910): start
,I/GCoreNlp( 1223): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  910): applying state to connected service
,D/PMS     (  910): acquireWL(42d8d680): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42d8d680): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  910): applying state to connected service
,D/PMS     (  910): acquireWL(42d3ec10): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42d3ec10): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42cef6d8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42cef6d8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42c85ee0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42b980a8: PendingIntentRecord{42807810 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1597161, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42c85ee0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42bb55e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,D/PMS     (  910): acquireWL(42a29748): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 910 1000 null
,V/AlarmManager(  910): sending alarm PendingIntent{425ae358: PendingIntentRecord{42ddaa50 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1601294, Int=0
,D/PMS     (  910): releaseWL(42bb55e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
,D/PMS     (  910): acquireWL(425d04d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
,D/PMS     (  910): releaseWL(42a29748): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  910): releaseWL(425d04d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AutoSetting( 1329): service - mHandler: update timezone
,D/AutoSetting( 1329): service - handleMessage() stop self
,D/AutoSetting( 1329): service - handleMessage() quit looper
,D/AutoSetting( 1329): service - onDestroy() END
,D/AutoSetting( 1519): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1519): service - onCreate()
,D/AutoSetting( 1519): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1519): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
V/NotificationService(  910): batLight: Full, plugged
,V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/AutoSetting( 1519): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/DotMatrix( 1589): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1589): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1519): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1519): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1519): service - mHandler: update timezone
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1519): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1519): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1519): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1519): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1589): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1589): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1117): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{42535f30 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.htclocationservice 1 7 2 11
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{4498b420 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  910): acquireWL(4261cd60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  910): releaseWL(4261cd60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/AutoSetting( 1519): service - handleMessage() stop self
,D/AutoSetting( 1519): service - onDestroy() END
,D/AutoSetting( 1519): service - handleMessage() quit looper
,D/PMS     (  910): acquireWL(42efa0b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42efa0b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(42eddd08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
V/AlarmManager(  910): sending alarm PendingIntent{42b980a8: PendingIntentRecord{42807810 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1657161, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42eddd08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42d08140): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42d08140): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
,D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(44974de8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
D/PMS     (  910): releaseWL(44974de8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(42e9e3a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42b980a8: PendingIntentRecord{42807810 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1717161, Int=0
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42e9e3a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(426876b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(426876b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1117): closing low battery warning: level=100
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(42ea99b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): releaseWL(42ea99b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(42e4f048): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42b980a8: PendingIntentRecord{42807810 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1777161, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42e4f048): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(43e7d058): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(43e7d058): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,D/PMS     (  910): acquireWL(42ec1190): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  910): releaseWL(42ec1190): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  910): acquireWL(442b3398): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
V/AlarmManager(  910): sending alarm PendingIntent{42b980a8: PendingIntentRecord{42807810 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1837161, Int=0
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,I/ProcessStatsService(  910): Prepared write state in 40ms
,I/ProcessStatsService(  910): Prepared write state in 24ms
,D/PMS     (  910): releaseWL(442b3398): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  910): Pruning old procstats: /data/system/procstats/state-2015-12-18-06-46-21.bin
,D/PMS     (  910): acquireWL(43e4c578): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
V/AlarmManager(  910): sending alarm PendingIntent{427c2c08: PendingIntentRecord{42eb8930 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1821029, Int=1800000
D/PMS     (  910): acquireWL(44186188): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
V/AlarmManager(  910): sending alarm PendingIntent{42e41ac8: PendingIntentRecord{42e7e138 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1847190, Int=0
,V/AlarmManager(  910): sending alarm PendingIntent{42e40768: PendingIntentRecord{42f3f650 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450465373652, Int=900000
,D/PMS     (  910): releaseWL(44186188): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,W/ContextImpl( 4595): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/LocationManagerService(  910): getAllProviders()=[passive, gps, network]
D/PMS     (  910): releaseWL(43e4c578): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
W/BatSI   (  910): Couldn't get kernel wake lock stats
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,D/PMS     (  910): acquireWL(4422ec38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(4422ec38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(4323f208): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): releaseWL(4323f208): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(44269d78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
V/AlarmManager(  910): sending alarm PendingIntent{42b980a8: PendingIntentRecord{42807810 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1897161, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(44269d78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 5286): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 5286): ====startRecUseTime====
D/htc.customization.log.level( 5286):  is 
W/CustomizationLogLevel( 5286): Level value is invalid, use default level 2
D/CustomizationManager( 5286):  Read ACC file spent 0.100 (s)
D/CIDMapFileReader( 5286): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5286): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5286): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5286): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 5286): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5286): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 5286): Parsing tag item name = HTC__016
D/CIDMapFileReader( 5286): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5286): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5286): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5286): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 5286): Parsing tag category name = system
I/CustomizationCIDLoader( 5286): Parsing tag category name = application
I/CustomizationCIDLoader( 5286): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5286): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5286): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5286): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5286): Parsing tag category name = Settings
D/CustomizationManager( 5286):  Read CID file spent 0.153 (s)
D/CustomizationManager( 5286):  All configurations done spent 0.154 (s)
W/HtcNativeFlag( 5286): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 5286): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 5286): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 5286): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  910): deletePackageAsUser: pkg=com.test.thalitest, pid=5286, uid=2000 user=0
I/ActivityManager(  910): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
W/asset   (  910): Copying FileAsset 0x62a3b748 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
W/PackageSettings(  910): Skipping PackageSetting{42a7a070 com.example.hello/10397} due to missing metadata
I/ActivityManager(  910): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1589): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1589): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1589): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1223): Ignoring removeGeofence because network location is disabled.
D/PMS     (  910): acquireWL(42e8f828): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PMS     (  910): releaseWL(42e8f828): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/Launcher( 1272): Deferring update until onResume
D/Launcher( 1272): waitUntilResume // bindAppsRemoved
D/AccTypeManager( 1342): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/VoicemailCleanupService( 1300): Cleaning up data for package: com.test.thalitest
W/SystemReader( 1256): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/[PluginManager]RegisterService( 1329): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
D/Prism.PackageStateRece_( 1272): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "sms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/[PluginManager]RegisterService( 1329): handle notify Blinkfeed plugin client changed
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "smsto"
W/AccTypeManager( 1342): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1342): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/IcingCorporaProvider( 2808): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
E/ExternalAccountType( 1342): Unsupported attribute readOnly
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/ActivityManager(  910): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5300 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "sms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mmsto"
D/PhoneApp( 1238): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  910): acquireWL(42d5b898): PARTIAL_WAKE_LOCK  Icing 0x1 2157 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(42d5b898): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(42cf12f8): PARTIAL_WAKE_LOCK  Icing 0x1 2157 10029 WorkSource{10029 com.google.android.gms}
I/InputMethodManagerService(  910): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/IcingCorporaProvider( 2808): UpdateCorporaTask done [took 372 ms] updated apps [took 372 ms] 
E/SQLiteDatabase( 5300): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 5300): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5300): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5300): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5300): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5300): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5300): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5300): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5300): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5300): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5300): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5300): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5300): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5300): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5300): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5300): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 5300): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 5300): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 5300): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 5300): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 5300): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 5300): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 5300): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 5300): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 5300): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 5300): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 5300): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 5300): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 5300): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 5300): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 5300): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 5300): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5300): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5300): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 5300): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5300): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5300): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 5300): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 5300): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 5300): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 5300): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5300): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5300): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 5300): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 5300): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5300): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5300): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5300): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 5300): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 5300): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 5300): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 5300): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 5300): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5300): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5300): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 5300): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 5300): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 5300): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 5300): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 5300): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 5300): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 5300): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 5300): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 5300): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 5300): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 5300): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 5300): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 5300): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 5300): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 5300): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 5300): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5300): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 5300): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 5300): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 5300): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 5300): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 5300): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 5300): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 5300): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 5300): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 5300): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5300): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5300): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5300): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5300): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5300): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5300): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5300): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5300): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5300): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5300): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5300): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5300): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5300): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5300): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 5300): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 5300): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 5300): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 5300): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 5300): threadid=11: thread exiting with uncaught exception (group=0x41fb3e30)
E/AndroidRuntime( 5300): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 5300): Process: com.google.android.apps.docs, PID: 5300
E/AndroidRuntime( 5300): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5300): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5300): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5300): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5300): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5300): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5300): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5300): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5300): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5300): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5300): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5300): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5300): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5300): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5300): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 5300): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 5300): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 5300): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 5300): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ActivityManager(  910): App crashed! Process: com.google.android.apps.docs
E/DropBoxManagerService(  910): Can't write: system_app_crash
E/DropBoxManagerService(  910): java.io.FileNotFoundException: /data/system/dropbox/drop158.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  910): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  910): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  910): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  910): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  910): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  910): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  910): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  910): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  910): 	... 5 more
D/Process ( 5300): killProcess, pid=5300
D/Process ( 5300): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  910): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5320 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Recipient 5300
I/ActivityManager(  910): Process com.google.android.apps.docs (pid 5300) has died.
W/ContextImpl( 5320): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  910): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=5333 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 5320): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5320): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5320): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5320): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5320): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5320): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5320): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5320): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5320): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5320): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5320): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5320): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5320): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5320): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5320): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5320): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 5320): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 5320): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5320): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5320): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5320): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 5320): threadid=10: thread exiting with uncaught exception (group=0x41fb3e30)
E/AndroidRuntime( 5320): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5320): Process: com.android.keychain, PID: 5320
E/AndroidRuntime( 5320): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5320): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5320): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5320): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5320): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5320): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5320): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5320): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5320): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5320): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5320): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5320): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5320): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5320): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5320): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 5320): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 5320): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5320): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5320): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5320): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  910): App crashed! Process: com.android.keychain
D/ErrorReport(  910): HtcErrorReportManager Begin---add error logs to dropbox
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1272): loadItems() com.htc.launcher.pageview.WidgetManager@42476d50 +
I/Prism.WidgetManager( 1272): onLoadItems() +
D/AppTag  ( 5333): getInstance(Context context)
D/Process ( 5320): killProcess, pid=5320
D/AppTag  ( 5333): getInstance(Context context)
D/Process ( 5320): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/AppTag  ( 5333): onCreate()
E/ErrorReport(  910): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  910): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1450465455270.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  910): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  910): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  910): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  910): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  910): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  910): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  910): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  910): 	... 4 more
I/ActivityManager(  910): Recipient 5320
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Process com.android.keychain (pid 5320) has died.
W/ActivityManager(  910): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/PMS     (  910): acquireWL(42f00df8): PARTIAL_WAKE_LOCK  AsyncService 0x1 3531 10160 null
D/PMS     (  910): releaseWL(42f00df8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/dalvikvm( 3989): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 2157): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2157): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 2157): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2157): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 2157): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2157): Module APK com.google.android.play.games already loaded
I/ActivityManager(  910): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
I/LocationSettingsChecker( 2157): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 2157): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2157): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5cac8af8
E/SQLiteLog( 2157): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2157): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x66b01c08
W/dalvikvm( 2157): threadid=48: thread exiting with uncaught exception (group=0x41fb3e30)
E/DriveAsyncService( 2157): disk I/O error (code 3850)
E/DriveAsyncService( 2157): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2157): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2157): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2157): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2157): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2157): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2157): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2157): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2157): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2157): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2157): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2157): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2157): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2157): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2157): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2157): 	at java.lang.Thread.run(Thread.java:864)
E/AndroidRuntime( 2157): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2157): Process: com.google.android.gms, PID: 2157
E/AndroidRuntime( 2157): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2157): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2157): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2157): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2157): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2157): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2157): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2157): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2157): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2157): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2157): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2157): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2157): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2157): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2157): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2157): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2157): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2157): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2157): 	at java.lang.Thread.run(Thread.java:864)
E/ActivityManager(  910): App crashed! Process: com.google.android.gms
E/SQLiteDatabase( 2157): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 2157): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2157): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2157): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2157): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2157): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2157): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2157): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2157): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2157): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2157): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2157): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2157): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2157): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2157): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2157): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 2157): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 2157): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 2157): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 2157): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2157): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2157): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2157): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 2157): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 2157): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 2157): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 2157): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 2157): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 2157): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 2157): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 2157): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 2157): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 2157): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 2157): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 2157): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 2157): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 2157): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 2157): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 2157): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 2157): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 2157): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 2157): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 2157): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 2157): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 2157): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 2157): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 2157): killProcess, pid=2157
D/Process ( 2157): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  910): Can't write: system_app_crash
E/DropBoxManagerService(  910): java.io.FileNotFoundException: /data/system/dropbox/drop160.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  910): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  910): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  910): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  910): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  910): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  910): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  910): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  910): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  910): 	... 5 more
W/PackageManager(  910): Unable to load service info ResolveInfo{4426fda0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  910): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  910): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  910): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  910): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  910): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  910): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  910): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  910): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  910): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  910): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  910): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  910): 	at dalvik.system.NativeStart.main(Native Method)
I/ActivityManager(  910): Recipient 2157
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  910): handleWLDeath(42cf12f8): PARTIAL_WAKE_LOCK  Icing 0x1
D/WifiService(  910): Client connection lost with reason: 4
I/ActivityManager(  910): Process com.google.android.gms (pid 2157) has died.
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 11000ms
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 20999ms
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 20998ms
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20997ms
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20997ms
I/ActivityManager(  910): Resuming delayed broadcast
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20995ms
E/SQLiteLog( 1359): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1359): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x64020a10
W/dalvikvm( 1359): threadid=1: thread exiting with uncaught exception (group=0x41fb3e30)
E/ActivityManager(  910): App crashed! Process: com.google.process.gapps
E/AndroidRuntime( 1359): FATAL EXCEPTION: main
E/AndroidRuntime( 1359): Process: com.google.process.gapps, PID: 1359
E/AndroidRuntime( 1359): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1359): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1359): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1359): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1359): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1359): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1359): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1359): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1359): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1359): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1359): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1359): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1359): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1359): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1359): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1359): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1359): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1359): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1359): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1359): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1359): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1359): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1359): 	... 10 more
E/DropBoxManagerService(  910): Can't write: system_app_crash
E/DropBoxManagerService(  910): java.io.FileNotFoundException: /data/system/dropbox/drop161.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  910): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  910): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  910): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  910): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  910): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  910): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  910): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  910): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  910): 	... 5 more
D/Process ( 1359): killProcess, pid=1359
D/Process ( 1359): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  910): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5364 uid=10098 gids={50098, 3003, 5012}
I/DeviceManagement( 5364): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=5364 dbg=false s=true
I/DeviceManagement( 5364): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 5364): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 5364): WorkflowService: Starting workflow service
I/DeviceManagement( 5364): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@42410d30] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 5364): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5364): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 5364): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 5364): ModelRegistry: Loading model meta data from resources...
I/DeviceManagement( 5364): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/ActivityManager(  910): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5378 uid=10099 gids={50099, 3003, 5012}
I/DeviceManagement( 5364): SessionStateController: Checking invariants...
I/ActivityManager(  910): Recipient 1359
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  910): Client connection lost with reason: 4
I/ActivityManager(  910): Process com.google.process.gapps (pid 1359) has died.
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20846ms

```
