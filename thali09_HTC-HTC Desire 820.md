#### Test 506502789b39735_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  907):    returned true
,--------- beginning of /dev/log/system
V/LightsService(  907): setLight #0: color=#26
V/LightsService(  907): setLight #0: color=#23
V/LightsService(  907): setLight #0: color=#1c
V/LightsService(  907): setLight #0: color=#16
E/cutils-trace( 4483): Error opening trace file: No such file or directory (2)
V/LightsService(  907): setLight #0: color=#14
I/ActivityManager(  907): Waited long enough for: ServiceRecord{43045ef8 u0 com.htc.htclocationservice/.AutoSettingService}
D/CustomizationManager( 4483): ====startRecUseTime====
D/htc.customization.log.level( 4483):  is 
W/CustomizationLogLevel( 4483): Level value is invalid, use default level 2
D/CustomizationManager( 4483):  Read ACC file spent 0.055 (s)
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
D/CustomizationManager( 4483):  Read CID file spent 0.094 (s)
D/CustomizationManager( 4483):  All configurations done spent 0.094 (s)
W/HtcNativeFlag( 4483): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4483): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4483): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4483): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  907): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  907): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4483
D/PMS     (  907): acquireHCC(42500850): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 907 1000 null
D/PMS     (  907): acquireHCC(4256d5f0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 907 1000 null
I/Intent  (  907): @test_code: getHtcIntentFlag: 0 obj: 1142519232
I/FeedHostManager( 1272): [onPause]
I/FeedProviderManager( 1272): onPause
I/FeedHostManager( 1272): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41bd8790
I/SocialFeedProvider( 1272): +onPause
I/SocialFeedProvider( 1272): -onPause
D/PMS     (  907): acquireWL(440cc5e8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
I/ActivityManager(  907): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4495 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1272): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 4495): Binding Chromium to main looper Looper (main, tid 1) {41a96a80}
I/LibraryLoader( 4495): Expected native library version number "",actual native library version number ""
I/chromium( 4495): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4495): Initializing chromium process, renderers=0
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  907): java.lang.Throwable: stack dump
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42626c08:true
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4495): 1101713136: getState(). Returning 12
D/PMS     (  907): acquireWL(424b1358): PARTIAL_WAKE_LOCK  AudioMix 0x1 369 1013 null
D/PMS     (  907): acquireWL(425809c8): PARTIAL_WAKE_LOCK  AudioMix 0x1 369 1013 null
D/PMS     (  907): releaseWL(424b1358): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4495): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4495): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4495): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4495): Local Branch: 
I/Adreno-EGL( 4495): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4495): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4495):                  aa63bbd948f41d15fc72f585e
W/chromium( 4495): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4495): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4495): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4495): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4495): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4495): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4495): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4495): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4495): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4495): CordovaWebView is running on device made by: HTC
,W/AwContents( 4495): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  907): Disable input method client, pid=1272
,W/ResourceType( 4495): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4495): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41ade5a0, mServedView=org.apache.cordova.engine.SystemWebView{41aa4208 VFEDH.C. .F...... 0,0-720,1134 #64}
I/InputMethodManagerService(  907): Enable input method client, pid=4495
,D/PMS     (  907): releaseWL(440cc5e8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
W/XT9_C   ( 1210): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1210): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,I/ActivityManager(  907): Displayed com.test.thalitest/.MainActivity: +271ms
,D/JsMessageQueue( 4495): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4495): JniHelper::setJavaVM(0x4156e048), pthread_self() = 1662557800
,D/JX-Cordova( 4495): jxcore cordova android initializing
,I/dalvikvm-heap( 4495): Grow heap (frag case) to 11.624MB for 144892-byte allocation
,I/dalvikvm-heap( 4495): Grow heap (frag case) to 11.739MB for 217334-byte allocation
,I/dalvikvm-heap( 4495): Grow heap (frag case) to 11.915MB for 325996-byte allocation
,I/dalvikvm-heap( 4495): Grow heap (frag case) to 12.189MB for 488990-byte allocation
,I/dalvikvm-heap( 4495): Grow heap (frag case) to 12.595MB for 733480-byte allocation
,I/dalvikvm-heap( 4495): Grow heap (frag case) to 14.041MB for 1650320-byte allocation
,I/dalvikvm-heap( 4495): Grow heap (frag case) to 15.456MB for 2475476-byte allocation
,I/dalvikvm-heap( 4495): Grow heap (frag case) to 17.495MB for 3713210-byte allocation
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
W/jxcore-log( 4495): Initializing JXcore engine
W/jxcore-log( 4495): JXcore engine is ready
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,W/CpuWake (  907): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  907): <<release mCpuPerf_Freq wakelock
D/PMS     (  907): releaseHCC(42500850): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null,
,D/PMS     (  907): releaseHCC(4256d5f0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/jxcore-log( 4495): Starting JXcore engine
,W/jxcore-log( 4495): Platform android
W/jxcore-log( 4495): 
,W/jxcore-log( 4495): Process ARCH arm
W/jxcore-log( 4495): 
,I/jxcore-log( 4495): JXcore Cordova bridge is ready!
I/jxcore-log( 4495): 
,W/jxcore-log( 4495): JXcore engine is started
,I/Choreographer( 4495): Skipped 133 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4495): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/PMS     (  907): releaseWL(425809c8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4495): Toggling radios to true
I/jxcore-log( 4495): 
,D/BluetoothAdapter( 4495): enable(): BT is already enabled..!
,D/WifiManager( 4495): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
W/HtcDLNAServiceManager(  907): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  907): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  907): Settings:Agentvalue: 2
W/Settings:Agent(  907): >> traceCallingStack()
W/Settings:Agent(  907): Process.myPid(): 907
W/Settings:Agent(  907): Process.myTid(): 1368
W/Settings:Agent(  907): Process.myUid(): 1000
W/Settings:Agent(  907): 
W/Settings:Agent(  907): ,
W/System.err(  907): java.lang.Throwable: stack dump
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  907): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  907): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  907): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  907): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  907): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
,W/System.err(  907): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  907): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  907): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  907): 
W/Settings:Agent(  907): << traceCallingStack(): 1(ms)
D/WifiManager( 4495): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiNative-wlan0(  907): doBoolean: DISCONNECT
D/WifiManager( 4495): reconnect: Base Package Name=com.test.thalitest, uid=10389,
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): TDLS: Tear down peers
,I/wpa_supplicant( 1161): wpa_driver_nl80211_disconnect(reason_code=3)
,I/jxcore-log( 4495): Radios toggled
I/jxcore-log( 4495): 
,D/BluetoothManagerService(  907): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiService(  907): New client listening to asynchronous messages
D/WifiService(  907): setWifiEnabled: true pid=4495, uid=10389
E/WifiService(  907): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  907): isSprintWifiRestricted(): false
I/WifiService(  907): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  907): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
I/jxcore-log( 4495): Got Device Bluetooth address: B4:CE:F6:AB:A4:6A
I/jxcore-log( 4495): 
I/jxcore-log( 4495): Perf Test app loaded loaded
I/jxcore-log( 4495): 
I/Choreographer( 4495): Skipped 77 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 4495): check test folder
I/jxcore-log( 4495): 
,I/jxcore-log( 4495): found test : ./testFindPeers.js
I/jxcore-log( 4495): 
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1161): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1161): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1161): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  907): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  907): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
,D/WifiMonitor(  907): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1161): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1161): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1161): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1161): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1161): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb7d5ebc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1161):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1161): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1161): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1161): htc_wext_set_TX_TRACKING (0)+,
I/wpa_supplicant( 1161): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1161): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1161): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1161): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18,
D/wpa_supplicant( 1161): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00,
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1161): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1161): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1161): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1161): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1161): htc_wext_set_TX_TRACKING - ret = 0
,D/wpa_supplicant( 1161): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1161): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1161): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1161): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1161): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1161): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1161): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1161): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1161): Wireless event: cmd=0x8b15 len=20
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1161): nl80211: Ignore disconnect event triggered during reassociation
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
,D/WifiNative-wlan0(  907):    returned true
D/WifiPerfLock(  907): release()
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiStateMachine(  907): PerfLock released for exiting ConnectedState
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700,
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
I/jxcore-log( 4495): found test : ./testSendData.js
I/jxcore-log( 4495): 
,D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
D/Tethering(  907): [isWifi] getHotspotEnabled: false
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1161): Power_Mode_Type mode = 0
I/wpa_supplicant( 1161): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
D/ConnectivityService(  907): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  907): acquireWL(43c70148): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 907 1000 null
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
,D/DhcpStateMachine(  907): [RunningState] Stop DHCP
D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023617
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023865
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024003
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024008
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024028
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025324
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025344
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028880
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  907): doBoolean: RECONNECT
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=19750 mDataStallAlarmIntent=PendingIntent{4264de88: PendingIntentRecord{42490468 android broadcastIntent}}
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): Fast associate: Old scan results
I/wpa_supplicant( 1161): wpa_supplicant_scan enter
I/wpa_supplicant( 1161): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1161): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1161): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1161): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): Enter handleNetworkDisconnect
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1161): Power_Mode_Type mode = 0
I/wpa_supplicant( 1161): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 61
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023617
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023865
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024003
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024008
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024028
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025324
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025344
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028880
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1113): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/IntentController( 1113): receive(android.net.wifi.STATE_CHANGE,1,false)
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  907):    returned true
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  907): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  907): Provision feature enable=false
D/WifiP2pService(  907): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  907): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/UsbnetStateTracker(  907): isAvailable+-
D/UsbnetStateTracker(  907): reconnect
,D/UsbnetStateTracker(  907): isAvailable+-
,D/WISPrService( 3832): >>>>>WISPrService start isConnected = false<<<<<
,D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  907): default: reconnect()
D/MDST    (  907): default: setTeardownRequested(false)
D/MDST    (  907): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  907): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  907): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiService(  907): New client listening to asynchronous messages
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '29 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 29 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
,D/ConnectivityService(  907): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  907): Exit handleNetworkDisconnect
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
I/IntentController( 1113): receive(android.net.wifi.STATE_CHANGE,1,false)
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 3832): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,D/WISPrService( 3832): >>>>>WISPrService start isConnected = false<<<<<
,V/NativeCrypto( 1378): Read error: ssl=0x65ecb340: I/O error during system call, Connection timed out
D/libc    (  362): [NET] entry_id:3   entry:0xb860b320  removed 
D/libc    (  362): [NET] entry_id:4   entry:0xb860afd8  removed 
D/libc    (  362): [NET] entry_id:1   entry:0xb860b428  removed 
D/libc    (  362): [NET] entry_id:5   entry:0xb860b240  removed 
D/libc    (  362): [NET] entry_id:2   entry:0xb860b0e8  removed 
D/libc    (  362): [NET] entry_id:6   entry:0xb8606f60  removed 
,D/libc    (  362): *************************
D/libc    (  362): *** DNS CACHE FLUSHED ***
D/libc    (  362): *************************
,D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/WIFI_ICON( 1113): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/ConnectivityService(  907): resetConnections(wlan0, 3)
D/ConnectivityService(  907): flush DNS cache for net 1(wlan0)
,D/WISPrService( 3832): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,V/NativeCrypto( 1378): SSL shutdown failed: ssl=0x65ecb340: I/O error during system call, Broken pipe
D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  907): acquireWL(4334b040): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(4332d448): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  907): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,I/QuickSettingWifi( 1113): receive.wifiConnect:false wifiAPname:null elapse:1
D/WifiStateMachine(  907): startScan Pid: 907 Uid 1000
,D/WifiNative-wlan0(  907): doBoolean: SCAN
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1161): Ongoing scan action - reject new request (wpa_state=3)(scanning=1)
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN" Return -1
,D/WifiNative-wlan0(  907):    returned false
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023617
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023865
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024003
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024008
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024028
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025324
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025344
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028880
D/BatSI   (  907): WIFI scan started for: 650a0300 uid:1000
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1378/10029)
D/ConnectivityService(  907): reportInetCondition for net -1, percentage: 0 by  (1378/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1378/10029)
I//system/bin/ip(  362): RTNETLINK answers: No such process
,I/logwrapper(  362): /system/bin/ip terminated by exit(2)
D/PMS     (  907): releaseWL(4334b040): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1378/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1378/10029)
D/PMS     (  907): releaseWL(4332d448): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/QuickSettingWifi( 1113): receive.wifiConnect:false wifiAPname:null elapse:0
D/ConnectivityService(  907): mActiveDefaultNetwork: -1
D/ConnectivityService(  907): handleInetConditionChange: no active default network - ignore
,I/chromium( 4495): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: false
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
D/CaptivePortalTracker(  907): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  907): NoActiveNetworkState
,D/Tethering(  907): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
V/Tethering(  907): bSetPropertyMultiRAB:false
,D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  907): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  907): ipv4Default null
I/Tethering(  907): No IPv4 upstream interface, giving up.
I/ConnectivityHelper( 1272): [onReceive] WIFI(1): DISCONNECTED
,D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1595/10029)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1272/10076)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4276/10100)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4276/10100)
D/PMS     (  907): acquireWL(42660c20): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (4347/10154)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
,D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,I/NetworkMonitor( 4347): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023617
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023865
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024003
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024008
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024028
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025324
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025344
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028880
D/ConnectivityService(  907): getActiveNetworkInfo called by  (2710/10021)
,I/ActivityManager(  907): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4546 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  907): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  907): releaseWL(42660c20): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
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
,V/DexLibLoader( 4546): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4546): Dex already copied
D/OdexVerifier( 4546): Odex verification is skipped.
,V/DexLibLoader( 4546): Creating class loader
,V/DexLibLoader( 4546): Finished creating class loader
V/DexLibLoader( 4546): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4546): Dex already copied
D/OdexVerifier( 4546): Odex verification is skipped.
,V/DexLibLoader( 4546): Creating class loader
,V/DexLibLoader( 4546): Finished creating class loader
V/DexLibLoader( 4546): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4546): Dex already copied
D/OdexVerifier( 4546): Odex verification is skipped.
,V/DexLibLoader( 4546): Creating class loader
,V/DexLibLoader( 4546): Finished creating class loader
V/DexLibLoader( 4546): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4546): Dex already copied
D/OdexVerifier( 4546): Odex verification is skipped.
,V/DexLibLoader( 4546): Creating class loader
V/DexLibLoader( 4546): Finished creating class loader
,V/DexLibLoader( 4546): Verifying classes from secondary dexes.,
D/DexLibLoader( 4546): DexLibLoader.ensureDexLoaded took 20 ms
,W/dalvikvm( 4546): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4546): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4546): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 4546): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 4546): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4546): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4546): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4546): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4546): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/wpa_supplicant( 1161): nl80211: Event message available
D/wpa_supplicant( 1161): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1161): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1161): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1161): nl80211: Survey data missing
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1161): Sorted scan results
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1161): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1161): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-50
I/wpa_supplicant( 1161): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-78
D/wpa_supplicant( 1161): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1161): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1161): Add randomness: count=7 entropy=1
D/wpa_supplicant( 1161): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1161): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1161): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
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
I/wpa_supplicant( 1161):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-50
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
D/wpa_supplicant( 1161): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb7d604e8  current_ssid=0x0
D/wpa_supplicant( 1161): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1161): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1161): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1161): check if in concurrent case
,I/wpa_supplicant( 1161): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz),
D/wpa_supplicant( 1161): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1161): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1161): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1161): RSN: PMKSA cache search - network_ctx=0xb7d604e8 try_opportunistic=0
D/wpa_supplicant( 1161): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1161): RSN: No PMKSA cache entry found
,I/wpa_supplicant( 1161): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1161): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1161): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1161): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 6
,D/wpa_supplicant( 1161): nl80211: Unsubscribe mgmt frames handle 0xb7d5f718 (mode change)
D/wpa_supplicant( 1161): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7d5f718
D/wpa_supplicant( 1161): nl80211: Register frame type=0xd0 nl_handle=0xb7d5f718
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1161): nl80211: Register frame type=0xd0 nl_handle=0xb7d5f718
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1161): nl80211: Register frame type=0xd0 nl_handle=0xb7d5f718
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1161): nl80211: Register frame type=0xd0 nl_handle=0xb7d5f718
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1161): nl80211: Register frame type=0xd0 nl_handle=0xb7d5f718
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 58,
D/wpa_supplicant( 1161): nl80211: Register frame type=0xd0 nl_handle=0xb7d5f718
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1161): nl80211: Register frame type=0xd0 nl_handle=0xb7d5f718
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1161): nl80211: Register frame type=0xd0 nl_handle=0xb7d5f718
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1161): nl80211: Register frame type=0xd0 nl_handle=0xb7d5f718
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1161): nl80211: Register frame type=0xd0 nl_handle=0xb7d5f718
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1161): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1161):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1161):   * freq=2412
D/wpa_supplicant( 1161):   * Auth Type 0
D/wpa_supplicant( 1161):   * WPA Versions 0x2
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1161): nl80211: Connect request send successfully
D/wpa_supplicant( 1161): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1161): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1161): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
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
I/wpa_supplicant( 1161): reply (489) for get BSS: id=0
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1161): freq=5220
I/wpa_supplicant( 1161): level=-49
I/wpa_supplicant( 1161): tsf=0000000105810942
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG7005g
,I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=1
I/wpa_supplicant( 1161): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-50
I/wpa_supplicant( 1161): tsf=0000000105810959
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1161): ssid=NG700
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=2
I/wpa_supplicant( 1161): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1161): freq=2427
I/wpa_supplicant( 1161): level=-78
I/wpa_supplicant( 1161): tsf=0000000105810963
I/wpa_supplicant( 1161): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1161): ssid=Gonzos
I/wpa_supplicant( 1161): ====
I/wpa_supplicant( 1161): id=3
I/wpa_supplicant( 1161): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1161): freq=2412
I/wpa_supplicant( 1161): level=-50
I/wpa_supplicant( 1161): tsf=0000000105810955
I/wpa_supplicant( 1161): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1161): ssid=01ABC
I/wpa_supplicant( 1161): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiManager( 1224): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 105810942, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 2412, timestamp: 105810959, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -78, frequency: 2427, timestamp: 105810963, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -50, frequency: 2412, timestamp: 105810955, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
D/BatSI   (  907): WIFI scan stopped for: 640a0300 uid:1000
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,E/FbInjectorInitializer( 4546): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/wpa_supplicant( 1161): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1161): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1161): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1161): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1161): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1161): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1161): nl80211: if_removed already cleared - ignore event
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
I/wpa_supplicant( 1161): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1161): TDLS: Remove peers on association
D/wpa_supplicant( 1161): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1161): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1161): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1161): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1161): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
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
I/wpa_supplicant( 1161): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1161): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1161): Get randomness: len=32 entropy=5
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  907): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
D/Tethering(  907): interfaceStatusChanged wlan0, true
D/WifiMonitor(  907): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/HTCRequest(  907): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  907): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  907): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  907): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  907): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  907): Enter handleAssociatedWithEvent
D/WifiStateMachine(  907): Associated
D/WifiStateMachine(  907): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  907): Exit handleAssociatedWithEvent
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  907): BSSID was changed, update WiFi database
I/wpa_supplicant( 1161): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb7d5f9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1161):    addr=c0:ff:d4:d3:aa:48
D/WifiApDatabaseHandler(  907): updateConnectedAP...
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1161): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1161): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1161): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6fa3b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1161):    broadcast key
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1161): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1161): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
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
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1161): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1161): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
D/Tethering(  907): interfaceStatusChanged wlan0, true
D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  907): This record is existed, only update it...
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  907): updateConnectedAP...
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/WifiStateMachine(  907): fetchFrequency(), freq = 2412
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  907): This record is existed, only update it...
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiApDatabaseHandler(  907): updateConnectedAP...
I/IntentController( 1113): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1113): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): mActiveDefaultNetwork: -1
D/WISPrService( 3832): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 3832): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  907): updateConnectedAP...
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023617
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023865
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024003
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024008
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024028
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025324
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025344
,D/DhcpStateMachine(  907): [StoppedState] Start DHCP
D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [2][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1161): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  907):    returned true
,W/fb4a(:<default>):StaticBindingVerifier( 4546): Verify
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028880
,D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1161): Power_Mode_Type mode = 1
I/wpa_supplicant( 1161): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  907):    returned null
E/WifiStateMachine(  907): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  907):    returned null
D/WifiStateMachine(  907): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  907): acquireWL(439342a0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 907 1000 null
D/WifiStateMachine(  907): handlePreDhcpSetup mBluetoothConnectionActive: false
,D/WifiP2pService(  907): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42392850 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42392850 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1113): receive.wifiConnect:false wifiAPname:null elapse:0
,I/PMS     (  907): Going to sleep due to screen timeout...
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42102670
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = CM36282 Light sensor
W/SensorService(  907): pid=907, uid=1000
,W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42102670, eanble = 0, strlen(mName) = 59
,W/SensorService(  907): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  907): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41ee23f0
W/SensorService(  907): Listener[1] = com.htc.smartdim.sensor_eye@425a1ac0
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  907): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  907): Couldn't get kernel wake lock stats
V/LightsService(  907): setLight #2: color=#0
D/qdlights(  907): set_light_buttons_func: on=0 brightness=0
V/LightsService(  907): setLight #0: color=#0
,D/WirelessDisplayService(  907): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  907): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  907): mWirelessDisplayManager is null
,D/SurfaceControl(  907): Excessive delay in blankDisplay() while turning screen off: 318ms
D/PMS     (  907): nativeSetInteractive:false
D/NfcService( 1255): ScreenObserver: OFF
,D/NfcService( 1255): applyRouting - 0
D/PMS     (  907): nativeSetInteractive:false done
D/PMS     (  907): nativeSetAutoSuspend:true
D/PMS     (  907): nativeSetAutoSuspend:true done
D/HABCtrl (  907): TPE algorithm. remove timeout.
D/PMS     (  907): OOBE c monitor 11
I/InputManager(  907): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  907): screenObserver, isScreenOn=false
I/InputMethodManagerService(  907): Disable input method client, pid=4495
W/ResourceType( 4495): No package identifier when getting name for resource number 0x00000064
I/IntentController( 1113): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
I/InputMethodManager( 4495): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41aa4208 VFEDH.C. .F...... 0,0-720,1134 #64}
,D/NfcService( 1255): applyRouting -2
,V/KeyguardServiceDelegate(  907): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@439c9918)
,V/KeyguardServiceDelegate(  907): **** SHOWN CALLED ****
D/PMS     (  907): acquireWL(436aad80): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1255 1027 null
D/PMS     (  907): releaseWL(436aad80): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  907): wakingUp
D/WifiService(  907): New client listening to asynchronous messages
I/WindowManager(  907): No lock screen! windowToken=null
D/PMN     (  907): onScreenOn
,I/SensorManager(  907): mEventCount = 1050
,I/SensorManager(  907): mEventCount = 1050
D/WirelessDisplayService(  907): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  907): acquireWL(425def88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(425def88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/MtpService( 2710): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/NfcService( 1255): applyRouting - 0
,D/MtpService( 2710): [MTP][onReceive]-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/AlarmManager(  907): ACTION_SCREEN_ON
I/AlarmManager(  907): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done recovering
I/AlarmManager(  907): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,D/NfcService( 1255): applyRouting -2
,D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_ON
D/PMS     (  907): acquireWL(42f3ba80): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1255 1027 null
D/PMS     (  907): releaseWL(42f3ba80): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -49 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1161): SET_SCREEN_ON:On
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
I/wpa_supplicant( 1161): htc_wext_set_keepalive +
I/wpa_supplicant( 1161): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1161): getPrivFuncNum +	
I/wpa_supplicant( 1161): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1161): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1161): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1161): htc_wext_set_TX_TRACKING (1)+
,I/wpa_supplicant( 1161): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  907):    returned true
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3,
I/ClockThread( 1113): stop update clock
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,V/SRS_Proc(  369): ParamSet string: screen_state=on
,D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/NetworkPolicy(  907): updateScreenOn: false
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4546): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4546): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  907): acquireWL(43162558): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(43162558): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(43f09090): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43f09090): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1740): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1740): onScreenOn: 1450229635775
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1740): onScreenOn: 1450229635776
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41ee23f0
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41ee23f0, eanble = 0, strlen(mName) = 91
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  907): Listener[0] = com.htc.smartdim.sensor_eye@425a1ac0
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/dalvikvm-heap( 4546): Grow heap (frag case) to 9.511MB for 73240-byte allocation
D/PMN     (  907): goingToSleep
D/PMS     (  907): acquireWL(433a0cf8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 907 1000 null
,D/Process (  907): killProcessQuiet, pid=4245
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=19751 mDataStallAlarmIntent=null
I/ActivityManager(  907): Killing 4245:com.google.android.partnersetup/u0a32 (adj 15): empty #17
D/AlarmManager(  907): ACTION_SCREEN_OFF
I/AlarmManager(  907): [AlarmQueuing] screen off now: 
I/AlarmManager(  907): [AlarmQueuing] data connection: true
,I/AlarmManager(  907): [AlarmQueuing] wifi connection: true
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1161): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1161): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 0
I/ActivityManager(  907): Recipient 4245
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  907): acquireWL(43310d10): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 907 1000 null
D/PMS     (  907): releaseWL(433a0cf8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1161): SET_SCREEN_ON:Off
I/wpa_supplicant( 1161): htc_wext_set_keepalive +
I/wpa_supplicant( 1161): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1161): getPrivFuncNum +	
I/wpa_supplicant( 1161): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1161): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1161): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1161): htc_wext_set_keepalive gateway addr = 00000000
I/wpa_supplicant( 1161): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  907):    returned true
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
,D/WifiStateMachine(  907): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/AutoSetting( 1315): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  907): releaseWL(439342a0): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1315/10055)
,I/ActivityManager(  907): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4600 uid=10079 gids={50079, 3003, 5012}
,D/AutoSetting( 1315): Util - no network available!
,V/SRS_Proc(  369): ParamSet string: screen_state=off
,D/AutoSetting( 1315): service - onCreate()
,D/AutoSetting( 1315): service - AddressCache: using context: com.htc.Weather
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1315/10055),
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,D/LocationManagerService(  907): request 423e77d8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1161): WiFioffload: SignalStrength: =97
,D/LocationManagerService(  907): provider request: passive ProviderRequest[ON interval=0]
,D/WifiNative-wlan0(  907):    returned true
D/AutoSetting( 1315): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/WifiStateMachine(  907): gateway: /192.168.1.1
D/WifiNative-wlan0(  907): doBoolean: DRIVER GATEWAY-ADD 16885952
D/AutoSetting( 1315): service - mHandler: cancel location update
,D/AutoSetting( 1315): service -           changes count: 0
D/NetworkPolicy(  907): updateScreenOn: false
D/WIFI_ICON( 1113): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1161): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1161): htc_wext_set_keepalive +
I/wpa_supplicant( 1161): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1161): getPrivFuncNum +	
I/wpa_supplicant( 1161): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1161): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1161): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1161): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1161): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  907): VerifyingLinkState enter
D/WifiStateMachine(  907): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/ContactMessageStore( 1240): start background delete task...
D/ContactMessageStore( 1240): size: 0 , 0
D/ContactMessageStore( 1240): Background delete complete
,W/fb4a(:<default>):UserScope( 4546): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4546): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4546): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/wpa_supplicant( 1161): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  907): VerifyingLinkState: enableIpv6
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -50, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/PMS     (  907): releaseWL(43310d10): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,D/WifiWatchdogStateMachine(  907): WAN detection
,I/IntentController( 1113): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/MobileConnectivityChangeReceiver( 4600): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4600): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4600): onOtaspChanged old =0, new =3
V/NetworkPolicy(  907): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  907): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  907): default: teardown()
D/MDST    (  907): default: setTeardownRequested(true)
,D/MDST    (  907): default: setEnableApn apnType =default , enable=false
V/PhoneMonitor( 4600): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
D/WISPrService( 3832): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
I/wpa_supplicant( 1161): environment dirty rate=0 [1][0][0]
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  907): syncGetConfiguredNetworks
D/MDST    (  907): default: setTeardownRequested(true)
D/ConnectivityService(  907): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  907): Unexpected mtu value: android.net.wifi.WifiStateTracker@4241b038
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/WIFI_ICON( 1113): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/ActivityManager(  907): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4619 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4600/10079)
,D/ConnectivityService(  907): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    (  362): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  907): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  907): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
D/WirelessDisplayService(  907): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/WirelessDisplayService(  907):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  907): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  907): acquireWL(42695938): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,I/QuickSettingWifi( 1113): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4600/10079)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4600/10079)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4600/10079)
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] getTotalRam: 1873 Mb
I//system/bin/ip(  362): RTNETLINK answers: No such file or directory
,I/logwrapper(  362): /system/bin/ip terminated by exit(254)
D/PMS     (  907): acquireWL(430ef8a0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(430ef8a0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(43746dd0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(43746dd0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1740): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1740): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1740): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1740): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1740): onScreenOff
,I//system/bin/ip(  362): RTNETLINK answers: No such process
,I/logwrapper(  362): /system/bin/ip terminated by exit(2)
,I/ActivityManager(  907): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4642 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,I/ActivityManager(  907): Killing 4276:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,D/Process (  907): killProcessQuiet, pid=4276
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/ConnectivityService(  907): mActiveDefaultNetwork: WIFI
,E/dalvikvm( 4546): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
W/dalvikvm( 4546): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4546): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4546): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4546): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4546): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(42695938): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  907): acquireWL(43538420): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(433c19e8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
I/CheckinService( 2174): Checkin interval check for package: unspecified last checkin: 1450229588055 min interval config: 0 actual interval: 47985
D/PMS     (  907): releaseWL(43538420): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I/CheckinService( 2174): Checking schedule, now: 1450229636046 next: 1450229618027
I/CheckinService( 2174): active receiver: enabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2174, uid=10029, userID:0
I/dalvikvm-heap( 4546): Grow heap (frag case) to 9.958MB for 84664-byte allocation
E/dalvikvm( 4546): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4546): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4546): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4546): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4546): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
I/CheckinService( 2174): Preparing to send checkin request
I/EventLogService( 2174): Accumulating logs since 1450229583661
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
,E/cutils  (  345): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  345): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4642): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  345): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 4642): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  345): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4546): Grow heap (frag case) to 9.975MB for 28144-byte allocation
,W/dalvikvm( 4546): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4546): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/GAV2    ( 4642): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/dalvikvm( 4546): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4546): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4546): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4546): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4546): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,E/cutils  (  345): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  345): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4642): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  345): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 4642): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/CheckinRequestBuilder( 2174): Checkin reason type: 8 attempt count: 1
W/Vold    (  345): Returning OperationFailed - no handler for errno 30
I/ActivityManager(  907): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2174): Failed to find provider info for com.google.android.wearable.settings
,D/wpa_supplicant( 1161): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1161): EAPOL: disable timer tick
,I/dalvikvm-heap( 4546): Grow heap (frag case) to 10.013MB for 39954-byte allocation
,I/ActivityManager(  907): Recipient 4276
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4546): Grow heap (frag case) to 10.089MB for 79892-byte allocation
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (2174/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4642/10151)
V/WebViewChromiumFactoryProvider( 4642): Binding Chromium to main looper Looper (main, tid 1) {41a9b1c8}
I/LibraryLoader( 4642): Expected native library version number "",actual native library version number ""
I/chromium( 4642): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4642): Initializing chromium process, renderers=0
V/GLSActivity( 1378): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1378): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  907): acquireWL(4419f240): PARTIAL_WAKE_LOCK  AudioMix 0x1 369 1013 null
,E/AudioManagerAndroid( 4642): BLUETOOTH permission is missing!
D/PMS     (  907): acquireWL(4404fa40): PARTIAL_WAKE_LOCK  AudioMix 0x1 369 1013 null
D/PMS     (  907): releaseWL(4419f240): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4642): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4642): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4642): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4642): Local Branch: 
I/Adreno-EGL( 4642): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4642): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4642):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4642): Starting up...
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4642/10151)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4642/10151)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,I/dalvikvm-heap( 4546): Grow heap (frag case) to 10.277MB for 75760-byte allocation
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/Process (  907): killProcessQuiet, pid=4292
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3651/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3651/10160)
,I/ActivityManager(  907): Killing 4292:com.htc.backup/1000 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  907): Recipient 4292
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4685 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{436e7638 u0 ReceiverList{436e74f0 4546 com.facebook.katana/10027/u0 remote:436d7960}}
W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{436e7638 u0 ReceiverList{436e74f0 4546 com.facebook.katana/10027/u0 remote:436d7960}}
W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{43c7d280 u0 ReceiverList{43c7d220 4546 com.facebook.katana/10027/u0 remote:43be9580}}
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023617
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023865
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024003
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024008
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024028
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025324
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025344
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028880
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1378/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/AutoSetting( 1315): receiver - intent: android.intent.action.USER_PRESENT
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
D/AutoSetting( 1315): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/TetherSettings( 3832): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3832): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3832): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3832): Cust_ConnectToPC   : spcsc>false
D/        ( 3832): Cust_ConnectToPC   : IPT>true
D/        ( 3832): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3832): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3832): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3832): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3832): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1378/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
I/PSReceiver( 3832): onReceive:android.intent.action.USER_PRESENT
,W/dalvikvm( 4685): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
I/SmartNS_PSService( 3832): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3832): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3832):  defaultType:0
,W/dalvikvm( 4685): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
I/MultiDex( 4685): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4685): install
,I/MultiDex( 4685): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
W/ContextImpl( 3832): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/MultiDex( 4685): loading existing secondary dex files
,I/MultiDex( 4685): load found 3 secondary dex files
,I/MultiDex( 4685): install done
,D/PMS     (  907): acquireWL(4292a6f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4703 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,W/dalvikvm( 4685): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4685): VFY: unable to resolve instance field 36
,W/dalvikvm( 4685): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/PMS     (  907): releaseWL(4292a6f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
V/JNIHelp ( 4685): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ProviderInstaller( 4685): Installed default security provider GmsCore_OpenSSL
,E/cutils  (  345): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4546): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  345): Returning OperationFailed - no handler for errno 30
,E/cutils  (  345): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4546): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  345): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4703): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,E/cutils  (  345): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4546): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,W/dalvikvm( 4685): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4685): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
W/Vold    (  345): Returning OperationFailed - no handler for errno 30
,D/SmartSyncUtils( 4703): isEpsOn(), nState = 0
,W/dalvikvm( 4685): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4685): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4685): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4685): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4685): Link of class 'Lcom/google/android/gms/common/j/c;' failed
D/PMS     (  907): acquireWL(44056860): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4703 1000 null
,D/PMS     (  907): releaseWL(44056860): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4703): getMobilePolicyEnabled, result = true
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  907): killProcessQuiet, pid=4316
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4316:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4316
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 4703): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4703): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4703): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4703): getMobilePolicyEnabled, result = true
I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@425a1ac0
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
D/WifiService(  907): New client listening to asynchronous messages
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 1
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@425a1ac0, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 0
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@425a1ac0, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@425a1ac0
E/ActivityThread(  907): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@425a2008 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  907): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@425a2008 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,I/WVCdm   (  369): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  369): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  369): CdmEngine::OpenSession
,I/WVCdm   (  369): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  369): CdmEngine::GenerateKeyRequest
,D/WearableService( 1224): callingUid 10029, callindPid: 1224
,E/MDM     ( 1224): [113] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 2174): Restart initialization of location
,D/AuthorizationBluetoothService( 1378): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1378): Proximity feature is not enabled.
,V/GLSActivity( 1378): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1224): No location to return for getLastLocation()
,D/NativeLibraryUtils( 4685): Install completed successfully. count=14 extracted=0
,W/FusedLocationProvider( 1224): location=null
D/PMS     (  907): acquireWL(43942280): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(43942280): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023617
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023865
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024003
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024008
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024028
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025324
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025344
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028880
,D/WVCdm   (  369): PrepareKeyRequest: nonce=429210311
,I/WVCdm   (  369): CdmEngine::CloseSession
,D/PMS     (  907): releaseWL(43c70148): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  907): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: true
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,D/CaptivePortalTracker(  907): NoActiveNetworkState
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,I/ConnectivityHelper( 1272): [onReceive] WIFI(1): CONNECTED
V/Tethering(  907): bSetPropertyMultiRAB:false
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1595/10029)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1272/10076)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(431e3608): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
I/Tethering(  907): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  907): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  907): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  907): ipv4Default 0.0.0.0/0 -> 192.168.1.1
,I/Tethering(  907): Found interface wlan0
D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
,I/NetworkMonitor( 4347): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4600/10079)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1595/10029)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (4347/10154)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.musicenhancer (3949/10053)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
D/AccTypeManager( 1340): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,I/WVCdm   (  369): CdmEngine::OpenSession
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
I/WVCdm   (  369): CdmEngine::QueryKeyControlInfo
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,I/WVCdm   (  369): CdmEngine::GenerateKeyRequest
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(42490990): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023617
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023865
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024003
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024008
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024028
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025324
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025344
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028880
,D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  907): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  907): releaseWL(42490990): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
D/PMS     (  907): releaseWL(431e3608): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (2710/10021)
,W/AccTypeManager( 1340): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1340): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1340): Unsupported attribute readOnly
,D/WVCdm   (  369): PrepareKeyRequest: nonce=2463849224
,D/AutoSetting( 1315): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4600): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4600): onReceive CONNECTIVITY_CHANGE networkType=1
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1315/10055)
,D/AutoSetting( 1315): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1315): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 1315): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1315): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1315/10055)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4642/10151)
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
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3651/10160)
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3651/10160)
,I/WVCdm   (  369): CdmEngine::CloseSession
D/PMS     (  907): acquireWL(426ad158): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2174): Checkin interval check for package: unspecified last checkin: 1450229588055 min interval config: 0 actual interval: 49071
D/PMS     (  907): releaseWL(426ad158): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2174, uid=10029, userID:0
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1378/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1378/10029)
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
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
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (4685/10029)
,D/WifiStateMachine(  907): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,W/Settings( 4685): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/jxcore-log( 4495): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 4495): 
,I/CheckinRequestBuilder( 2174): Classify the device as Phone.
,D/libc    ( 2174): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2174): [NET] getaddrinfo-,err=8
D/libc    ( 2174): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2174): [NET] getaddrinfo-, 1
,D/libc    ( 2174): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =4a4d +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 26
D/libc    (  362): [NET]res_nsend:resplen=84
D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2174): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2174): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2174): [NET] getaddrinfo-,err=8
,D/libc    ( 2174): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2174): [NET] getaddrinfo-,err=8
D/libc    ( 2174): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2174): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2174): Sending checkin request (12254 bytes)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,W/fb4a(:<default>):UserScope( 4546): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4546): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=4 [22][1][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4546): Called registerBroadcastReceiver twice.
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4546/10027)
,I/CheckinRequestBuilder( 2174): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  907): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2174): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (2174/10029)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=50 [4][2][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
,I/CheckinRequestBuilder( 2174): Classify the device as Phone.
,I/CheckinTask( 2174): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 2174): Checking schedule, now: 1450229638893 next: 1450752575888
,I/CheckinService( 2174): active receiver: disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2174, uid=10029, userID:0
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023617
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023865
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024003
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024008
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024028
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024034
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025324
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025344
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028880
D/libc    (  362): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =8bde +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  362): [NET] NOT IN CACHE
I/CheckinService( 2174): Checking schedule, now: 1450229638928 next: 1450752575888
,I/CheckinService( 2174): active receiver: disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2174, uid=10029, userID:0
,D/CheckinService( 2174): Recording last checkin time for package unspecified as 1450229638935
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023617
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023865
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024003
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024008
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024028
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025324
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025344
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028880
,D/PMS     (  907): releaseWL(433c19e8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2174/10029)
D/PMS     (  907): acquireWL(4258dbe0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
D/GCM     ( 1378): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    ( 1378): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1378): [NET] getaddrinfo-,err=8
D/libc    ( 1378): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1378): [NET] getaddrinfo-, 1
,D/libc    ( 1378): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
,D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =8421 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1378/10029)
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 287
D/libc    (  362): [NET]res_nsend:resplen=79
D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1378): [NET] getaddrinfo_proxy-, success
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  362): [NET]res_nsend:resplen=172
D/libc    (  362): [NET]res_queryN: exit 3, ancount=4
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  907): Find DNS Address www.htc.com/23.59.123.86
,D/libc    ( 1378): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1378): [NET] getaddrinfo-,err=8
,D/libc    ( 1378): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1378): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1378/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1378/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1378/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1378/10029)
,D/PMS     (  907): releaseWL(4404fa40): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/PMS     (  907): acquireWL(43c34500): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1378/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1378/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1378/10029)
,D/PMS     (  907): releaseWL(4258dbe0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1378/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1378/10029)
,D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
,D/PMS     (  907): releaseWL(43c34500): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(440d7990): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1378/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1378/10029)
,D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1378/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1378/10029)
,D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1378/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023617
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023865
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024003
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024008
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024028
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025324
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025344
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028880
,D/PMS     (  907): releaseWL(440d7990): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=25 [12][3][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(42f6e4d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  907): sending alarm PendingIntent{41cb1698: PendingIntentRecord{41cb11b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=110798, Int=0
,D/PMS     (  907): releaseWL(42f6e4d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/GAV2    ( 4642): Thread[GAThread,5,main]: No campaign data found.
,D/ContactMessageStore( 1240): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1240): MSG_NOTIFY_CS_TO_SYNC <<
,D/Process (  907): killProcessQuiet, pid=4263
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4263:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4263
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1528): service - handleMessage() stop self,
,D/AutoSetting( 1528): service - onDestroy() END
,D/AutoSetting( 1528): service - handleMessage() quit looper
,D/Process (  907): killProcessQuiet, pid=4371
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4371:com.htc.mediamanager/u0a34 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4371
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
,I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1340): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/ActivityManager(  907): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4761 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/dalvikvm-heap( 1272): Grow heap (frag case) to 12.632MB for 53840-byte allocation
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1272): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,W/SystemReader( 1255): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
W/AccTypeManager( 1340): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1340): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/Launcher( 1272): Deferring update until onResume
,D/Launcher( 1272): waitUntilResume // bindAppsUpdated
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
,E/ExternalAccountType( 1340): Unsupported attribute readOnly
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
,D/PhoneApp( 1240): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,W/dalvikvm( 4761): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4761): VFY: unable to resolve instance field 36
I/Babel   ( 4761): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4761): MmsConfig.loadMmsSettings
,W/dalvikvm( 4761): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4761): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  907): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4784 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
D/AutoSetting( 1315): service - mRequestRunnable: screen on delay 10s, request NLP now
D/AutoSetting( 1315): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1315): service - requestNLP() NetworkLocationProvider not enabled
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4761, uid=10111, userID:0
,W/Settings( 4761): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MessageFrequencyProvider( 4784): onCreate
,V/GetPrviateResource( 4784): GetPrviateResource
V/GetPrviateResource( 4784): GetPrviateResource
,D/MmsCustomizationProvider( 4784): query uri: content://htc-mms-customization/mms-ua/ua_string
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4761, uid=10111, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4761, uid=10111, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4761, uid=10111, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4761, uid=10111, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4761, uid=10111, userID:0
D/PMS     (  907): acquireWL(433eb888): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4761 10111 null
,D/MmsCustomizationProvider( 4784): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 4761): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/Babel   ( 4761): MmsConfig.loadFromDatabase
I/[PluginManager]RegisterService( 1315): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
I/[PluginManager]RegisterService( 1315): handle notify Blinkfeed plugin client changed
I/ActivityManager(  907): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
E/Babel   ( 4761): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 4761): MmsConfig.loadFromResources
E/Babel   ( 4761): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 4761): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/IcingCorporaProvider( 2848): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PMS     (  907): acquireWL(4266efe8): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
I/ProviderInstaller( 4761): Installed default security provider GmsCore_OpenSSL
D/PMS     (  907): releaseWL(4266efe8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(433eb888): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
D/Process (  907): killProcessQuiet, pid=4395
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4395:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/PMS     (  907): acquireWL(4328c0f0): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
D/MessageCustFlag( 4784): sense_version=6.0
D/BTAccessoryUtil( 4784): createReceiver
D/BTAccessoryUtil( 4784): registerReceiver return intent = null
D/MessageCustFlag( 4784): sku_id=99
,W/SystemReader( 4784): Cannot find message_ambs_application_id, use default value instead
I/ActivityManager(  907): Recipient 4395
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  907): Client connection lost with reason: 4
,D/Messaging( 4784): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4784): networkCode: 
,D/MessageCustFlag( 4784): sku_id=99
D/MmsConfig( 4784): SIE smsPri: null
,D/MmsConfig( 4784): networkCode: 
D/HtcTelephonyCapability( 4784): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4784): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4784): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4784): Cannot find qct_8960_interface, use default value instead
,W/PackageManager(  907): Unable to load service info ResolveInfo{4262eda8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,D/PMS     (  907): releaseWL(4328c0f0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.googlequicksearchbox/.GelStubAppWatcher
,D/PMS     (  907): acquireWL(43dc2f60): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43dc2f60): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): acquireWL(43026620): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  907): acquireWL(43c895f8): PARTIAL_WAKE_LOCK  AsyncService 0x1 3651 10160 null
,D/PMS     (  907): releaseWL(43c895f8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  907): releaseWL(43026620): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  907): acquireWL(433e5a60): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(433e5a60): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,D/PMS     (  907): acquireWL(43615f80): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43615f80): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
,D/PMS     (  907): acquireWL(4315df30): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4315df30): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): acquireWL(426a5880): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/PackageBroadcastService( 2174): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/ActivityManager(  907): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/PMS     (  907): releaseWL(426a5880): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageBroadcastService( 2174): Null package name or gms related package.  Ignoreing.
D/PMS     (  907): acquireWL(43bbb1f0): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  907): start
,I/Icing   ( 2174): updateResources: need to parse f{com.google.android.gms}
,I/GCoreNlp( 1224): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  907): applying state to connected service
D/PMS     (  907): acquireWL(436a0e80): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2848): UpdateCorporaTask done [took 372 ms] updated apps [took 371 ms] 
,D/LocationProviderProxy(  907): applying state to connected service
D/PMS     (  907): releaseWL(436a0e80): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  907): Resuming delayed broadcast
D/PMS     (  907): acquireWL(43334600): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(43334600): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(43956d58): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43956d58): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  907): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1272): loadItems() com.htc.launcher.pageview.WidgetManager@41b29c70 +
,I/Prism.WidgetManager( 1272): onLoadItems() +
,I/Icing   ( 2174): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2174): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  907): releaseWL(43bbb1f0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/Process (  907): killProcessQuiet, pid=3949
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3949:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3949
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/Prism.WidgetManager( 1272): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1272): onLoadItems() -
,I/Prism.ItemManager( 1272): loadItems() com.htc.launcher.pageview.WidgetManager@41b29c70 -
,D/PhoneApp( 1240): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1240): -- N1 =0
,D/PhoneApp( 1240): -- N2 =0
,D/PhoneApp( 1240): -- N3 =0
,D/Messaging( 4784): mNeedToUpdateDate2 start
,D/MmsConfig( 4784): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4784): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4784): 
D/MmsAsyncWorkHandler( 4784): HM tk = 20001
,D/ReportIndicatorCache( 4784): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4784): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41a9d490
,I/Messaging( 4784): mccmnc> 
,D/DraftCache( 4784): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4784): [DraftCache/1] refresh
,D/MmsConfig( 4784): networkCode: 
,D/Messaging( 4784): ViewCache CreatePreloadOnlyConversationList
,D/MessageCustFlag( 4784): sense_version=6.0
,D/Jerry   ( 4784): start to preload cursor >>>>>>>
,D/PhoneStorageUtil( 4784): HtcWrapEnvironment.getSupportedStorages() >1
,D/PhoneStorageUtil( 4784): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4784): createReceiver
,D/TelephUtils( 1240): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,V/MmsProvider( 1240): Update uri=content://mms, match=0
,V/MmsProvider( 1240): selection=st=129 AND m_type!=134
,D/Messaging( 4784): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4784): TransactionService is going to be woken up.
,V/TransactionService( 4784): 1-Creating TransactionService
V/TransactionService( 4784): onStartCommand: 1
,D/MmsSystemEventReceiver( 4784): unRegisterForConnectionStateChanges
V/TransactionService( 4784): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4784): Loading previous transactions.
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1240): device_type: 1
D/TransactionService( 4784): Force set service start id to 1
V/TransactionService( 4784): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4784): unRegisterForConnectionStateChanges
,D/TransactionService( 4784): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4784): Destroying TransactionService
,V/TransactionService( 4784): 4-Handling incoming message: { when=-2ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 69
,D/MmsSmsV2Provider( 1240):  phoneType = -1
,D/MmsSmsV2Provider( 1240): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/MmsSmsV2Provider( 1240):  phoneType = -1
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 69
,D/MmsSmsV2Provider( 1240):  phoneType = -1
,D/MmsSmsV2Provider( 1240): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/Messaging( 4784): ViewCache CreatePreload
,D/Messaging( 4784): ViewCache CreatePreloadOnlyMultipleOpsList
,D/Messaging( 4784): mNeedToUpdateDate2: false
,D/Cust_MMSMS( 4784): _has_set_default_values_2=true
,D/MsgPreferenceUtils( 4784): def_index: 0
,D/MsgPreferenceUtils( 4784): globalIndex = 1
,D/MsgPreferenceUtils( 4784): phone state: true
,D/MsgPreferenceUtils( 4784): sd state: false
,D/MsgPreferenceUtils( 4784): vIndex = 0
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/MmsSmsV2Provider( 1240):  phoneType = -1
,D/MmsSmsV2Provider( 1240): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 69
,D/AccFlag ( 1240): sku_id=99
,D/DraftCache( 4784): [DraftCache/478] rebuildCache
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/MmsSmsV2Provider( 1240):  phoneType = -1
,D/MmsSmsV2Provider( 1240): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 4784): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 69
,D/Jerry   ( 1240): URI_DRAFT
,D/DraftCache( 4784): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 4784): [DraftCache/478] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4784): 
D/MmsAsyncWorkHandler( 4784): HM tk = 20002
D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1240): sku_id=99
,D/TelephUtils( 1240): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 69
,D/AccFlag ( 1240): sku_id=99
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{43c0b670 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/GAV4    ( 4761): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  907): acquireWL(4415d1b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{434a2fe0: PendingIntentRecord{43d64708 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=122313, Int=0
,D/PMS     (  907): acquireWL(4410f098): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4415d1b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1378/10029)
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [10][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/PMS     (  907): acquireWL(440721e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4410f098): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(440721e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(44050740): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023617
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023865
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024003
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024008
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024028
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025324
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025344
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028880
,D/PMS     (  907): releaseWL(44050740): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4404a2e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1378/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023617
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023865
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024003
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024008
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024028
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024034
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025324
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025344
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028880
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(43ec11f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43cb29d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1224): Vacuum at: now=1450229651714 tag=VacuumService
D/PMS     (  907): releaseWL(4404a2e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43ec11f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43c6e028): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023617
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023865
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024003
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024008
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024028
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024034
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025324
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025344
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028880
,D/PMS     (  907): releaseWL(43c6e028): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(437238f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1378/10029)
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023617
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023865
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024003
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024008
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024028
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025324
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025344
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028880
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(437238f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43cb29d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(425012d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023617
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023865
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024003
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024008
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024028
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024034
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025324
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025344
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028880
,D/PMS     (  907): releaseWL(425012d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(422b44e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1378/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023617
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023865
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024003
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024008
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024028
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025324
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025344
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028880
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(422b44e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(42365470): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1378/10029)
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023617
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023865
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024003
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024008
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024028
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025324
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025344
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028880
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(42642cc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42642cc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(426a5190): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42365470): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4265be30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023617
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023865
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024003
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024008
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024028
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024034
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025324
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025344
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028880
,D/PMS     (  907): releaseWL(4265be30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
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
,I/PhenotypeConfigurator( 1224): Scheduling Phenotype for one-off execution 12381 seconds from now (1450229652270)
,D/GetConfigurationSnapshotOperation( 1224): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1224): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1224): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1224): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1224): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1224): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1224): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  907): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0,
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
W/dalvikvm( 1224): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/libc    ( 1224): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1224): [NET] getaddrinfo-,err=8
D/libc    ( 1224): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1224): [NET] getaddrinfo-, 1
,D/libc    ( 1224): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =f56e +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 226
D/libc    (  362): [NET]res_nsend:resplen=87
D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1224): [NET] getaddrinfo_proxy-, success
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
D/libc    ( 1224): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1224): [NET] getaddrinfo-,err=8
D/libc    ( 1224): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1224): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  907): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [10][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): releaseWL(426a5190): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42561300): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023617
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023865
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024003
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024008
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024028
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024034
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025324
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025344
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028880
,D/PMS     (  907): releaseWL(42561300): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43663068): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1378/10029)
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023617
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023865
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024003
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024008
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024028
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025324
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025344
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028880
,D/PMS     (  907): releaseWL(43663068): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4241ab40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4241ab40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1113): closing low battery warning: level=100
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43ac6c98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/PMS     (  907): releaseWL(43ac6c98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(433eb7d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{41e75590: PendingIntentRecord{43fc6660 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=136812, Int=0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1378/10029)
,D/PMS     (  907): releaseWL(433eb7d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1315): service - mHandler: update timezone
,D/AutoSetting( 1528): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1528): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1528): service - onCreate()
,D/AutoSetting( 1315): service - handleMessage() stop self
D/AutoSetting( 1528): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1528): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
V/NotificationService(  907): batLight: Full, plugged
,D/AutoSetting( 1315): service - handleMessage() quit looper
,D/AutoSetting( 1315): service - onDestroy() END
,D/DotMatrix( 1583): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1583): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,D/AutoSetting( 1528): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1528): service - onStartCommand() handle command from HSP: processTimeZoneID
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AutoSetting( 1528): service - mHandler: update timezone
,D/AutoSetting( 1528): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1528): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1528): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1528): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1583): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1583): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1113): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41be9d20 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1113): com.htc.htclocationservice 2 7 3 11
,D/PMS     (  907): acquireWL(435f06b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{42518350: PendingIntentRecord{422bcd28 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141342, Int=0
,D/GpsLocationProvider(  907): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  907): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  907): acquireWL(425345c8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/PMS     (  907): releaseWL(435f06b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =8a19 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  362): [NET] NOT IN CACHE
,D/libc    (  362): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  362): [NET]res_nsend:resplen=238
,D/libc    (  362): [NET]res_queryN: exit 3, ancount=10
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
I/global  (  907): call createSocket() return a new socket.
D/libc    (  907): [NET] getaddrinfo+,hn 12(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  907): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  907): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  907): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  907):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/Process (  907): killProcessQuiet, pid=4416
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4416:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4416
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): releaseWL(425345c8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/ContactMessageStore( 1240): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1240): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{425cc318 u0 com.htc.htclocationservice/.AutoSettingService}
,D/AutoSetting( 1528): service - handleMessage() stop self
,D/AutoSetting( 1528): service - onDestroy() END
,D/AutoSetting( 1528): service - handleMessage() quit looper
,D/Process (  907): killProcessQuiet, pid=4430
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4430:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4430
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(43516368): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41cb1698: PendingIntentRecord{41cb11b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=170797, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43516368): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42605dd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10027}
,V/AlarmManager(  907): sending alarm PendingIntent{43c7c768: PendingIntentRecord{439f3910 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=174739, Int=0
,D/PMS     (  907): releaseWL(42605dd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1240): switchBindHtcMsgCursor: null
,D/PMS     (  907): acquireWL(439447d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(439447d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(4264bdd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4264bdd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,I/ClearcutLoggerApiImpl( 1378): disconnect managed GoogleApiClient
,D/PMS     (  907): acquireWL(43156638): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41cb1698: PendingIntentRecord{41cb11b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=230798, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43156638): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(42526f40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42526f40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(42651f80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41cb1698: PendingIntentRecord{41cb11b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=290798, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42651f80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(43ee7950): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43ee7950): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(426657f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(426657f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 4495): Connected to the server!
I/jxcore-log( 4495): 
,I/chromium( 4495): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  907): acquireWL(43c7d960): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41cb1698: PendingIntentRecord{41cb11b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=350798, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43c7d960): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(4304e3f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4304e3f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(4413f388): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41cb1698: PendingIntentRecord{41cb11b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=410797, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4413f388): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(4324e578): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4324e578): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(44195f40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41cbc238: PendingIntentRecord{4248bb98 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=446801, Int=0
,D/PMS     (  907): acquireWL(433ffaf8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
,I/ActivityManager(  907): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4877 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  907): sending alarm PendingIntent{42655340: PendingIntentRecord{426aae10 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1450229740624, Int=10800000
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43476d18): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(44195f40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10049}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  907): acquireWL(4352d098): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 907 1000 WorkSource{10160}
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=1 [141][2][0]
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
D/PMS     (  907): acquireWL(425de498): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 907 1000 WorkSource{10029}
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.aurora (4877/10049)
,D/PMS     (  907): releaseWL(433ffaf8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(43476d18): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4315c688): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(4315c688): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(430563f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(430563f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(431674e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023617
,D/PMS     (  907): releaseWL(431674e8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023865
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024003
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024008
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024028
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025324
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025344
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028880
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4310ccc8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
,D/PMS     (  907): releaseWL(4352d098): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 WorkSource{10160}
,D/Process (  907): killProcessQuiet, pid=4114
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  907): releaseWL(4310ccc8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/ActivityManager(  907): Killing 4114:com.google.android.gm/u0a107 (adj 15): empty #17
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360447066
,W/AlarmManager(  907): Alarm trigger time is over 1 year: setImplLocked(PendingIntent{430c51b8: PendingIntentRecord{43c79928 com.google.android.gms startService}}) : type=2 triggerAtTime=315360447066 win=-1 tElapsed=315360447066 maxElapsed=551880447063 interval=0 standalone=false
,I/ActivityManager(  907): Recipient 4114
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(44158d48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(425de498): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 WorkSource{10029}
,D/PMS     (  907): releaseWL(44158d48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  907): acquireWL(43aaacd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41cb1698: PendingIntentRecord{41cb11b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=470798, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43aaacd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43402cf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41cbc238: PendingIntentRecord{4248bb98 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=476926, Int=0
,D/PMS     (  907): acquireWL(43937d90): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
,D/PMS     (  907): releaseWL(43402cf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(435baee8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(43937d90): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(435baee8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(431e8dd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(431e8dd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(43c0ad28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41cb1698: PendingIntentRecord{41cb11b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=530798, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43c0ad28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(440ca458): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(440ca458): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(43c773e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41cb1698: PendingIntentRecord{41cb11b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=590798, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43c773e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43b5ae28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43b5ae28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  349): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1240): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1240): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1240): sku_id=99
D/ContactMessageStore( 1240): start background delete task...
,D/ContactMessageStore( 1240): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1240): size: 0 , 0
,D/ContactMessageStore( 1240): Background delete complete
,D/Process (  907): killProcessQuiet, pid=4466
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4466:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4466
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(434f77e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41cb1698: PendingIntentRecord{41cb11b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=650798, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(434f77e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43310e68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43310e68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(431035d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41cb1698: PendingIntentRecord{41cb11b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=710798, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(431035d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4316a300): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4316a300): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4358efa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41cb1698: PendingIntentRecord{41cb11b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=770798, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4358efa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(423c4968): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(423c4968): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(42d78878): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41cb1698: PendingIntentRecord{41cb11b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=830798, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42d78878): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43b51490): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43b51490): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(425fc750): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  907): sending alarm PendingIntent{41cb1698: PendingIntentRecord{41cb11b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=890798, Int=0
,D/PMS     (  907): releaseWL(425fc750): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43d28c20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43d28c20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(43951ed8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41cb1698: PendingIntentRecord{41cb11b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=950797, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43951ed8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(440de210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(440de210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(4332b290): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,D/ConnectivityService(  907): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  907): sending alarm PendingIntent{41cf2a28: PendingIntentRecord{424257f0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=782487, Int=0
,V/AlarmManager(  907): sending alarm PendingIntent{437ddc10: PendingIntentRecord{43556c80 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450230031375, Int=1800000
,V/AlarmManager(  907): sending alarm PendingIntent{42460e10: PendingIntentRecord{423f72a8 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450230460927, Int=900000
,V/AlarmManager(  907): sending alarm PendingIntent{424e3680: PendingIntentRecord{4254a0b0 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450230536670, Int=0
D/ConnectivityService(  907): Done.
,D/ConnectivityService(  907): Setting timer for 720seconds
,D/PMS     (  907): acquireWL(433d5828): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4703): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  907): acquireWL(43c6b328): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(433d5828): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
D/PowerUsageService( 4703): call getInstance()
D/SmartSyncUtils( 4703): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4703): MY_DEBUG = false
D/PMS     (  907): acquireWL(435983e8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4703 1000 null
,D/PMS     (  907): releaseWL(4332b290): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/SmartSyncScreenOnOffTimeReceiver( 4703): [updateNmRange] bManual = false
D/SmartSyncScreenOnOffTimeReceiver( 4703): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 4703): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4703): SettingOnTime = 1450245600000, randomSettingOnTime = 1450243599000
I/EventLogService( 2174): Aggregate from 1450229636082 (log), 1450228231257 (data)
D/SmartSyncScreenOnOffTimeReceiver( 4703): SettingOffTime = 1450231200000, randomSettingOffTime = 1450233307000
D/SmartSyncScreenOnOffTimeReceiver( 4703): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4703): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 4703): bNightModeTurnOffOnce = false
,D/PMS     (  907): releaseWL(435983e8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023617
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023865
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024003
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024008
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024028
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025324
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025344
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028880
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360447066
,D/PMS     (  907): releaseWL(43c6b328): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,D/PMS     (  907): acquireWL(42578b70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{42644680: PendingIntentRecord{43f650f0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1010066, Int=0
,D/PMS     (  907): acquireWL(4252c7d0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4252c7d0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42578b70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42500850): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1378/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1378/10029)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1378/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023617
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023865
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024003
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024008
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024028
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025324
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025344
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028880
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360447066
,D/PMS     (  907): releaseWL(42500850): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=17 [98][17][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(42145fe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41cb1698: PendingIntentRecord{41cb11b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1010798, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42145fe0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(41e98bf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(41e98bf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(41e6b5d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(41e6b5d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(41dc37f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41cb1698: PendingIntentRecord{41cb11b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1070798, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(41dc37f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(41b9d280): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
,D/PMS     (  907): releaseWL(41b9d280): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): >> updateStatus
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(424d0f30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41cb1698: PendingIntentRecord{41cb11b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1130798, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(424d0f30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(424160f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(424160f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1113): closing low battery warning: level=100
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
,D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42365470): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
,D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(42365470): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(41c646a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41cb1698: PendingIntentRecord{41cb11b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1190798, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(41c646a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(41aaa128): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(41aaa128): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1113): closing low battery warning: level=100
,D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  349): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  907): acquireWL(4245f850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41cb1698: PendingIntentRecord{41cb11b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1250798, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4245f850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(423c4a08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(423c4a08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/ContextImpl( 4703): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3832): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3832): Cust_ConnectToPC   : Internet_Sharing>true
,D/        ( 3832): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3832): Cust_ConnectToPC   : spcsc>false
D/        ( 3832): Cust_ConnectToPC   : IPT>true
,D/        ( 3832): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 3832): project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3832): Index of the first 1 = 3
W/ContextImpl( 3832): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 3832): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3832): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 3832): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/SmartNS_NSReceiver( 3832): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 3832): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,D/SmartNS_Utility( 3832): [ACC]android_networking:tethering_guard_support=false
,D/PMS     (  907): acquireWL(43195cf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(43195cf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(424c98c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41cb1698: PendingIntentRecord{41cb11b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1310798, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(424c98c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(422a15e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(422a15e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(4242a840): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(4242a840): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(423a8248): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41cb1698: PendingIntentRecord{41cb11b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1370798, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(423a8248): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(41dd9188): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(41dd9188): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(424c6da0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(424c6da0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(41ce2fd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41cb1698: PendingIntentRecord{41cb11b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1430798, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(41ce2fd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4334acd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): releaseWL(4334acd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1113): closing low battery warning: level=100
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(41f7d130): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(41f7d130): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1113): closing low battery warning: level=100
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(4230b950): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41cb1698: PendingIntentRecord{41cb11b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1490798, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4230b950): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4317f220): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4317f220): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42627890): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42627890): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42665290): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41cb1698: PendingIntentRecord{41cb11b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1550797, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42665290): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42090a70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42090a70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42538bf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42538bf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(44195f98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41cb1698: PendingIntentRecord{41cb11b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1610797, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(44195f98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(430b1810): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(430b1810): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(430c6668): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(430c6668): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(440d4930): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41cb1698: PendingIntentRecord{41cb11b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1670798, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1272): Grow heap (frag case) to 12.684MB for 50416-byte allocation
,D/PMS     (  907): releaseWL(440d4930): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4349de70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/PMS     (  907): releaseWL(4349de70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(435319c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(435319c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(42585558): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41cb1698: PendingIntentRecord{41cb11b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1730797, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42585558): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(44060e80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(44060e80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(4358e1e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4358e1e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(42395e98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41cb1698: PendingIntentRecord{41cb11b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1790798, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42395e98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,D/PMS     (  907): acquireWL(43c7ace8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43c7ace8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(425e7cf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(425e7cf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  349): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  907): acquireWL(43b9d8f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41cb1698: PendingIntentRecord{41cb11b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1850798, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
I/ProcessStatsService(  907): Prepared write state in 44ms
,D/PMS     (  907): releaseWL(43b9d8f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ProcessStatsService(  907): Pruning old procstats: /data/system/procstats/state-2015-12-15-15-43-24.bin
,D/PMS     (  907): acquireWL(42638e70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42638e70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1113): closing low battery warning: level=100
,D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43b83450): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43b83450): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1583): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1583): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4938): Error opening trace file: No such file or directory (2)
D/PMS     (  907): acquireWL(440740f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
D/ConnectivityService(  907): Sampling interval elapsed, updating statistics ..
D/Process (  907): killProcessQuiet, pid=4642
I/ActivityManager(  907): Killing 4642:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1802s
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
D/Process (  907): killProcessQuiet, pid=4619
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
D/Process (  907): killProcessQuiet, pid=4600
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
D/Process (  907): killProcessQuiet, pid=4347
I/ActivityManager(  907): Killing 4619:com.android.chrome/u0a96 (adj 15): empty for 1802s
V/AlarmManager(  907): sending alarm PendingIntent{41cf2a28: PendingIntentRecord{424257f0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1727490, Int=0
I/ActivityManager(  907): Killing 4600:com.google.android.setupwizard/u0a79 (adj 15): empty for 1802s
I/ActivityManager(  907): Killing 4347:com.google.android.music:main/u0a154 (adj 15): empty for 1802s
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
V/AlarmManager(  907): sending alarm PendingIntent{41f0e638: PendingIntentRecord{42571cc8 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1820767, Int=1800000
D/PMS     (  907): acquireWL(433d91e0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
I/ActivityManager(  907): Recipient 4619
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
V/AlarmManager(  907): sending alarm PendingIntent{42952108: PendingIntentRecord{439b5f38 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1849562, Int=0
D/ConnectivityService(  907): Done.
D/ConnectivityService(  907): Setting timer for 720seconds
V/AlarmManager(  907): sending alarm PendingIntent{420dec98: PendingIntentRecord{43f650f0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1910145, Int=0
I/ActivityManager(  907): Recipient 4600
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 4347
D/MediaRouterService(  907): Client com.google.android.music (pid 4347): Died!
V/AlarmManager(  907): sending alarm PendingIntent{42460e10: PendingIntentRecord{423f72a8 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450231360927, Int=900000
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  907): releaseWL(433d91e0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  907): acquireWL(4375fcb0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(4375fcb0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
D/LocationManagerService(  907): getAllProviders()=[passive, gps, network]
W/ContextImpl( 4703): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
W/BatSI   (  907): Couldn't get kernel wake lock stats
D/PMS     (  907): releaseWL(440740f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
I/ActivityManager(  907): Recipient 4642
V/GLSActivity( 1378): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1378): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  907): acquireWL(42f9ca90): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1378 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1378/10029)
D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1378/10029)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1378/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023617
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023865
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024003
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024008
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024028
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024034
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025324
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025344
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028880
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360447066
D/PMS     (  907): releaseWL(42f9ca90): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/CustomizationManager( 4938): ====startRecUseTime====
D/htc.customization.log.level( 4938):  is 
W/CustomizationLogLevel( 4938): Level value is invalid, use default level 2
W/BatSI   (  907): Couldn't get kernel wake lock stats
W/dalvikvm( 1378): VFY: unable to find class referenced in signature (Landroid/net/Network;)
E/dalvikvm( 1378): Could not find class 'android.net.Network', referenced from method com.google.android.gms.http.l.a
W/dalvikvm( 1378): VFY: unable to resolve check-cast 229 (Landroid/net/Network;) in Lcom/google/android/gms/http/l;
W/dalvikvm( 1378): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
W/BatSI   (  907): Couldn't get kernel wake lock stats
D/libc    ( 1378): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1378): [NET] getaddrinfo-,err=8
D/libc    ( 1378): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1378): [NET] getaddrinfo-, 1
D/libc    ( 1378): [NET] getaddrinfo_proxy+
D/libc    (  362): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  362): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  362): [NET] +++++ res_nsend xid =1b16 +++++
D/libc    (  362): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  362): [NET]res_queryN: exit 3, ancount=2
D/libc    (  362): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  362): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1378): [NET] getaddrinfo_proxy-, success
D/CustomizationManager( 4938):  Read ACC file spent 0.077 (s)
D/CIDMapFileReader( 4938): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4938): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4938): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4938): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4938): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4938): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4938): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4938): Parsing tag item name = HTC__M27
D/libc    ( 1378): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1378): [NET] getaddrinfo-,err=8
D/CIDMapFileReader( 4938): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4938): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4938): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4938): Parsing tag category name = system
I/CustomizationCIDLoader( 4938): Parsing tag category name = application
I/CustomizationCIDLoader( 4938): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4938): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4938): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4938): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4938): Parsing tag category name = Settings
D/CustomizationManager( 4938):  Read CID file spent 0.126 (s)
D/CustomizationManager( 4938):  All configurations done spent 0.126 (s)
W/HtcNativeFlag( 4938): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4938): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4938): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4938): Fail to get flag for type 'language', use default value: -1
D/libc    ( 1378): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1378): [NET] getaddrinfo-,err=8
D/libc    ( 1378): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1378): [NET] getaddrinfo-,err=8
W/BatSI   (  907): Couldn't get kernel wake lock stats
D/PackageManager(  907): deletePackageAsUser: pkg=com.test.thalitest, pid=4938, uid=2000 user=0
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
I/ActivityManager(  907): Killing 4495:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
D/Process (  907): killProcessQuiet, pid=4495
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
W/ActivityManager(  907): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  907):   Force finishing activity ActivityRecord{42472728 u0 com.test.thalitest/.MainActivity t2}
W/InputDispatcher(  907): channel '41dd9280 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  907): channel '41dd9280 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
W/InputDispatcher(  907): Attempted to unregister already unregistered input channel '41dd9280 com.test.thalitest.MainActivity (s)'
I/WindowManager(  907): WINDOW DIED Window{41dd9280 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  907): Client connection lost with reason: 4
W/PackageSettings(  907): Skipping PackageSetting{421a6340 com.example.hello/10397} due to missing metadata
W/InputMethodManagerService(  907): Got RemoteException sending setActive(false) notification to pid 4495 uid 10389
W/Binder  ( 1210): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1210): java.lang.NullPointerException
W/Binder  ( 1210): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1210): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1210): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1210): 	at dalvik.system.NativeStart.run(Native Method)
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
D/DotMatrix( 1583): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1583): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1583): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver replacing:false
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/SQLiteConnectionPool( 2174): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
D/PMS     (  907): acquireWL(41b68080): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
W/GeofencerStateMachine( 1224): Ignoring removeGeofence because network location is disabled.
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/PMS     (  907): releaseWL(41b68080): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(4415c2f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{41cb1698: PendingIntentRecord{41cb11b8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1910798, Int=0
D/AccTypeManager( 1340): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
I/Launcher( 1272): Deferring update until onResume
D/Launcher( 1272): waitUntilResume // bindAppsRemoved
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=10 [167][18][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1161): Recv Cmd 1: IFNAME=wlan0
D/VoicemailCleanupService( 1286): Cleaning up data for package: com.test.thalitest
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1161): nl80211: survey data missing!
E/wpa_supplicant( 1161): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1161): environment dirty rate=0 [0][0][0]
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
I/[PluginManager]RegisterService( 1315): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/ActivityManager(  907): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 1315): handle notify Blinkfeed plugin client changed
W/SystemReader( 1255): Cannot find nfc_is_upgrade_to_ar890, use default value instead
W/AccTypeManager( 1340): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1340): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/Prism.PackageStateRece_( 1272): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
I/ActivityManager(  907): Resuming delayed broadcast
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/IcingCorporaProvider( 2848): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  907): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/ActivityManager(  907): Resuming delayed broadcast
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/ActivityManager(  907): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4959 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
E/ExternalAccountType( 1340): Unsupported attribute readOnly
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1240 :
D/PhoneApp( 1240): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/InputMethodManagerService(  907): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/PMS     (  907): acquireWL(426965c8): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(426965c8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(41c9f578): PARTIAL_WAKE_LOCK  Icing 0x1 2174 10029 WorkSource{10029 com.google.android.gms}
E/SQLiteLog( 2848): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2848): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x635858e0
E/IcingCorporaProvider( 2848): Exception thrown from notifyTableChanged
E/IcingCorporaProvider( 2848): java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2848): 	at apg.a(PG:301)
E/IcingCorporaProvider( 2848): 	at apg.c(PG:222)
E/IcingCorporaProvider( 2848): 	at clo.b(PG:660)
E/IcingCorporaProvider( 2848): 	at clo.a(PG:651)
E/IcingCorporaProvider( 2848): 	at clo.g(PG:597)
E/IcingCorporaProvider( 2848): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/IcingCorporaProvider( 2848): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/IcingCorporaProvider( 2848): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/IcingCorporaProvider( 2848): 	at clp.Rl(PG:910)
E/IcingCorporaProvider( 2848): 	at clr.tL(PG:827)
E/IcingCorporaProvider( 2848): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/IcingCorporaProvider( 2848): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/IcingCorporaProvider( 2848): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/IcingCorporaProvider( 2848): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/IcingCorporaProvider( 2848): 	at android.os.Looper.loop(Looper.java:157)
E/IcingCorporaProvider( 2848): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/IcingCorporaProvider( 2848): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 2848): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/IcingCorporaProvider( 2848): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/IcingCorporaProvider( 2848): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/IcingCorporaProvider( 2848): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/IcingCorporaProvider( 2848): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/IcingCorporaProvider( 2848): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/IcingCorporaProvider( 2848): 	at apa.a(PG:382)
E/IcingCorporaProvider( 2848): 	at apg.i(PG:325)
E/IcingCorporaProvider( 2848): 	at aph.call(PG:215)
E/IcingCorporaProvider( 2848): 	at apg.a(PG:299)
E/IcingCorporaProvider( 2848): 	... 15 more
W/IcingCorporaProvider( 2848): notifyTableChanged failed.
W/IcingCorporaProvider( 2848): Table change notification failed for TableStorageSpec[applications]
I/IcingCorporaProvider( 2848): UpdateCorporaTask done [took 333 ms] updated apps [took 333 ms] 
E/SQLiteDatabase( 1224): Failed to open database '/data/data/com.google.android.gms/databases/playlog.db'.
E/SQLiteDatabase( 1224): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1224): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1224): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1224): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1224): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1224): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1224): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1224): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1224): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1224): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1224): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1224): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1224): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1224): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1224): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 1224): 	at com.google.android.gms.playlog.store.r.b(SourceFile:421)
E/SQLiteDatabase( 1224): 	at com.google.android.gms.playlog.store.r.a(SourceFile:303)
E/SQLiteDatabase( 1224): 	at com.google.android.gms.playlog.service.d.a(SourceFile:123)
E/SQLiteDatabase( 1224): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/SQLiteDatabase( 1224): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1224): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1224): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/SQLiteDatabase( 1224): 	at java.lang.Thread.run(Thread.java:864)
E/PlayLogIntentService( 1224): not an error (code 0): Could not open the database in read/write mode.
E/PlayLogIntentService( 1224): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PlayLogIntentService( 1224): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PlayLogIntentService( 1224): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/PlayLogIntentService( 1224): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/PlayLogIntentService( 1224): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PlayLogIntentService( 1224): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PlayLogIntentService( 1224): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PlayLogIntentService( 1224): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/PlayLogIntentService( 1224): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/PlayLogIntentService( 1224): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/PlayLogIntentService( 1224): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/PlayLogIntentService( 1224): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PlayLogIntentService( 1224): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PlayLogIntentService( 1224): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PlayLogIntentService( 1224): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PlayLogIntentService( 1224): 	at com.google.android.gms.playlog.store.r.b(SourceFile:421)
E/PlayLogIntentService( 1224): 	at com.google.android.gms.playlog.store.r.a(SourceFile:303)
E/PlayLogIntentService( 1224): 	at com.google.android.gms.playlog.service.d.a(SourceFile:123)
E/PlayLogIntentService( 1224): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/PlayLogIntentService( 1224): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/PlayLogIntentService( 1224): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/PlayLogIntentService( 1224): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/PlayLogIntentService( 1224): 	at java.lang.Thread.run(Thread.java:864)
D/PMS     (  907): releaseWL(41c9f578): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
E/SQLiteDatabase( 4959): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4959): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4959): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4959): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4959): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4959): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4959): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4959): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4959): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4959): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4959): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4959): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4959): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4959): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4959): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4959): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4959): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4959): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4959): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4959): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4959): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4959): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4959): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4959): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4959): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4959): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4959): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4959): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4959): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4959): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4959): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4959): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4959): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4959): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4959): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4959): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4959): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4959): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4959): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4959): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4959): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4959): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4959): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4959): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4959): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4959): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4959): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4959): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4959): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4959): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4959): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4959): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4959): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4959): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4959): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4959): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4959): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4959): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4959): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4959): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4959): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4959): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4959): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4959): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4959): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4959): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4959): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4959): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4959): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4959): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4959): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4959): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4959): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4959): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4959): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4959): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4959): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4959): threadid=11: thread exiting with uncaught exception (group=0x41666e30)
E/AndroidRuntime( 4959): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4959): Process: com.google.android.apps.docs, PID: 4959
E/AndroidRuntime( 4959): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4959): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4959): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4959): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4959): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4959): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4959): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4959): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4959): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4959): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4959): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4959): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4959): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4959): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4959): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4959): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4959): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4959): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4959): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ActivityManager(  907): App crashed! Process: com.google.android.apps.docs
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
E/SQLiteDatabase( 4959): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4959): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4959): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4959): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4959): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4959): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4959): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4959): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4959): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4959): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4959): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4959): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4959): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4959): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4959): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4959): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4959): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4959): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4959): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4959): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4959): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4959): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4959): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4959): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4959): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4959): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4959): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4959): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4959): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4959): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4959): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4959): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4959): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4959): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4959): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4959): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4959): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4959): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4959): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4959): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4959): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4959): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4959): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4959): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4959): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4959): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4959): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4959): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4959): Opened ClientFlag.db in read-only mode
D/Process ( 4959): killProcess, pid=4959
D/Process ( 4959): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  907): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4980 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  907): Recipient 4959
I/ActivityManager(  907): Process com.google.android.apps.docs (pid 4959) has died.
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ContextImpl( 4980): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  907): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4996 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4980): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4980): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4980): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4980): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4980): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4980): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4980): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4980): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4980): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4980): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4980): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4980): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4980): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4980): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4980): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4980): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4980): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4980): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4980): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4980): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4980): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4980): threadid=10: thread exiting with uncaught exception (group=0x41666e30)
E/AndroidRuntime( 4980): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4980): Process: com.android.keychain, PID: 4980
E/AndroidRuntime( 4980): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4980): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4980): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4980): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4980): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4980): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4980): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4980): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4980): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4980): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4980): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4980): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4980): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4980): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4980): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4980): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4980): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4980): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4980): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4980): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  907): App crashed! Process: com.android.keychain
W/PackageManager(  907): Unable to load service info ResolveInfo{422ae000 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1272): loadItems() com.htc.launcher.pageview.WidgetManager@41b29c70 +
I/Prism.WidgetManager( 1272): onLoadItems() +
D/AppTag  ( 4996): getInstance(Context context)
D/Process ( 4980): killProcess, pid=4980
D/Process ( 4980): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1450231441479.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/AppTag  ( 4996): getInstance(Context context)
I/ActivityManager(  907): Recipient 4980
I/ActivityManager(  907): Process com.android.keychain (pid 4980) has died.
W/ActivityManager(  907): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/AppTag  ( 4996): onCreate()
D/PMS     (  907): acquireWL(42fbd1e0): PARTIAL_WAKE_LOCK  AsyncService 0x1 3651 10160 null
D/PMS     (  907): releaseWL(42fbd1e0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/dalvikvm( 4075): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 2174): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2174): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 2174): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2174): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 2174): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2174): Module APK com.google.android.play.games already loaded
I/ActivityManager(  907): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
I/LocationSettingsChecker( 2174): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 2174): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2174): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6dd316f8
E/SQLiteLog( 2174): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2174): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x65630290
W/dalvikvm( 2174): threadid=44: thread exiting with uncaught exception (group=0x41666e30)
E/DriveAsyncService( 2174): disk I/O error (code 3850)
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

```
